# UtilityX Backend

The UtilityX Backend powers the core functionality of the UtilityX platform.
It manages users, wallets, marketplace orders, transactions, and integrations with payment and utility providers.

## Overview

The backend is responsible for:

* User authentication and account management
* Wallet management and escrow transactions
* Marketplace order creation and matching
* Transaction processing
* Integration with utility APIs and payment gateways

## Tech Stack

* Node.js
* NestJS / Express
* PostgreSQL
* Redis (caching and queues)
* REST APIs

## Folder Structure

src/
├── modules/
│   ├── auth/           # Authentication and authorization
│   ├── users/          # User management
│   ├── wallet/         # Wallet and escrow logic
│   ├── marketplace/    # P2P marketplace engine
│   ├── transactions/   # Transaction tracking
│   └── notifications/  # Alerts and messages
│
├── integrations/
│   ├── payments/       # Payment gateways
│   └── utilities/      # Airtime/data APIs
│
├── database/           # Database configuration
├── shared/             # Utilities and common services
└── main.ts             # Application entry point

## API Responsibilities

The backend exposes APIs for:

* User authentication
* Wallet funding and withdrawal
* Marketplace listings
* Executing trades
* Transaction history

## Running the Project

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run start:dev
```

## Responsibilities of this Repository

* Core platform logic
* Security and authentication
* Marketplace trading engine
* Payment and utility integrations
* Data persistence

## Contribution

Contributions should follow project standards and include appropriate tests.
