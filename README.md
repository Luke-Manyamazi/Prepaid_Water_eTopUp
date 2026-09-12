# Prepaid Water eTopUp

> A prototype for digital prepaid water purchases and top-up workflows.

Prepaid Water eTopUp is a lightweight application experiment focused on bringing prepaid utility payments into a web-based workflow. The current repository contains a Node.js server entry point and Firebase-based application configuration.

## Current focus

- Firebase application integration
- Environment-based configuration
- Node.js server startup
- Prepaid water eTopUp product concept

## Technology

| Area | Technology |
|---|---|
| Runtime | Node.js |
| Language | JavaScript (ES modules) |
| Platform services | Firebase |
| Configuration | dotenv |

## Project structure

```text
Prepaid_Water_eTopUp/
├── server/
│   ├── server.js
│   └── services/
│       └── firebaseConfig.js
├── package.json
└── README.md
```

## Getting started

Install dependencies:

```bash
npm install
```

Configure the Firebase environment values expected by `server/services/firebaseConfig.js` using a local environment file. Do not commit credentials or other secrets.

Start the server:

```bash
npm start
```

## Project status

🚧 **Prototype / early development**

The repository is currently best understood as an early-stage prototype rather than a finished production payment platform. Further work is needed around the product flow, water-account integration, transaction processing, validation, testing, and production deployment.

## Engineering focus

This project demonstrates early experimentation with Node.js, ES modules, Firebase integration, environment configuration, and a digital utility-payment product concept.
