# Supplier API Starter

Starter backend for learning a basic reseller/order-management API. It does not automate platform engagement, create fake accounts, or manipulate followers.

## Requirements
- Node.js 18+
- PostgreSQL

## Setup
1. Copy `.env.example` to `.env` and fill in your PostgreSQL connection string.
2. Create a database in PostgreSQL.
3. Run `sql/schema.sql` against that database.
4. Run `npm install`.
5. Run `npm start`.
6. Test `GET /health` and `GET /api/services`.

## Important
This is a learning starter, not production-ready. Before real use, add authentication and authorization to order endpoints, rate limiting, request validation, audit logging, secure secret management, and tests. Never commit `.env` or passwords to GitHub.
