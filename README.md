# Discord Server Cloner 2x

*Support the project by leaving a :star:*

---

## Overview
Clone any Discord server structure in seconds. Instead of manually recreating channels, roles and other settings, this tool allows you to duplicate an existing server using your account token.

**More information:** [Cloner Website](https://cloner-one.vercel.app/)

## Requirements
- Node.js 16+
- A Discord account token placed in a `.env` file (`TOKEN=YOUR_TOKEN`)

## Installation
```bash
npm install
```

### Development
Run the project directly with tsx for a fast feedback loop:
```bash
npm start
```

### Production
Compile the TypeScript sources and run the generated JavaScript:
```bash
npm run build
npm run start:prod
```

Backups are stored in `src/src/cloner` with a unique ID so previous backups are kept intact.


### Notes
Never share your account token with anyone. Use this tool responsibly and only with servers you own or manage.

----

### Thank you for your support!
