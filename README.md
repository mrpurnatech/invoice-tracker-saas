# Invoice Tracker SaaS

A full-featured SaaS application for tracking and managing invoices with Stripe payment integration.

## Features

- Create, edit, and manage invoices
- Client and contact management
- Stripe payment integration for online payments
- Invoice status tracking (draft, sent, paid, overdue)
- Dashboard with revenue analytics
- Recurring invoice support
- PDF invoice generation
- Email notifications
- Multi-tenant architecture
- Subscription-based access tiers

## Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **Payments:** Stripe API
- **Authentication:** JWT / OAuth2
- **Email:** SendGrid

## Getting Started

### Prerequisites

- Node.js >= 18.x
- PostgreSQL >= 14
- Stripe account and API keys

### Installation

```bash
git clone https://github.com/your-org/invoice-tracker-saas.git
cd invoice-tracker-saas
npm install
```

### Environment Variables

Create a `.env` file in the root directory:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/invoicedb
STRIPE_SECRET_KEY=sk_test_xxx
STRIPE_WEBHOOK_SECRET=whsec_xxx
JWT_SECRET=your_jwt_secret
SENDGRID_API_KEY=your_sendgrid_key
```

### Running the App

```bash
npm run dev
```

## Testing

```bash
npm run test
```

## License

MIT