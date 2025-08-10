# Relay - Universal Order Tracking Platform

Real-time order tracking infrastructure for any business. Track orders through customizable stages with live updates.

## Overview

Relay enables businesses to provide their customers with real-time order tracking - think Domino's pizza tracker, but for any service:
- 🚗 Auto repair shops
- 🍕 Restaurants & food trucks
- 👔 Dry cleaners
- 🖨️ Print shops
- 🔧 Repair services
- ...and more

## Features

- **Real-time Updates** - Customers see instant status changes via Server-Sent Events (SSE)
- **Customizable Stages** - Businesses define their own tracking pipeline
- **Job Queue Processing** - Automated notifications and status transitions
- **Multi-tenant** - One platform, multiple businesses
- **No Auth Required** - Customers track with just an order ID

## Tech Stack

- **Backend**: Go (SSE, job queues, REST API)
- **Frontend**: SvelteKit (customer tracking, business dashboard)

## Project Structure

```
relay/
├── relay-api/          # Go backend service
│
└── relay-ui/           # SvelteKit frontend
```

## Getting Started

### Prerequisites

- Go 1.24+
- Node.js 22+
- PostgreSQL (or SQLite for development)

### Development Setup


## Contributing

This is a learning project focused on:
- Server-Sent Events (SSE) for real-time updates
- Job queue patterns in Go
- Multi-tenant architecture
- Production deployment practices

## License

MIT

---

Built with ❤️ and Go + SvelteKit
