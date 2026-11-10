# Construction Materials Management — Frontend

A React-based frontend for a construction-materials business management system. The repository contains the client application; an API/backend is not included in this repository.

## Main application areas

The current page structure includes:

- Point of sale (POS)
- Product and inventory management
- Categories
- Customers and suppliers
- Purchase orders
- Invoices and quotations
- Expenses and reports
- Admin settings
- Login

These are frontend areas identified from the application structure. Their end-to-end integration depends on the configured backend/API.

## Tech stack

- React 19
- Vite 7
- React Router
- Tailwind CSS 4
- Radix UI primitives
- React Hook Form and Zod
- Recharts
- ExcelJS and SheetJS for spreadsheet-related features
- Cloudflare Vite plugin and Wrangler deployment tooling

## Requirements

- Node.js (LTS recommended)
- npm

## Getting started

```bash
npm install
npm run dev
```

Use the local development URL printed by Vite.

## Available scripts

- `npm run dev` — start the Vite development server
- `npm run build` — build the frontend
- `npm run start` — preview the built application
- `npm run lint` — run ESLint
- `npm run deploy` — run Wrangler deployment

## Build and deployment

Build locally before deploying:

```bash
npm run build
npm run start
```

The repository includes a Wrangler deploy script and Cloudflare Vite integration. Configure the target Cloudflare account, project and required environment values before using `npm run deploy`; deployment has not been verified as part of this documentation update.

## Configuration

Review the environment and API configuration used by the frontend before connecting it to a backend. Do not commit credentials, access tokens or production secrets.

## Project status

This repository documents the frontend only. Confirm API availability, authentication, role permissions and each business workflow in the target environment before presenting them as fully operational.
