# E-commerce Store

Full-stack e-commerce application built with Next.js 13, React, TailwindCSS, Zustand, and Stripe API.

## Features

- Browse products
- Add products to cart
- Complete checkout with Stripe
- Responsive design

## Tech Stack

- **Next.js 13** - React framework
- **React** - Frontend library
- **TailwindCSS** - Styling
- **Zustand** - State management
- **Stripe** - Payment processing

## Getting Started

1. Clone the repository

```bash
git clone <your-repo-url>
cd ecommerce-store-nextjs
```

2. Install dependencies

```bash
npm install
```

3. Create `.env` file in the root directory

```env
STRIPE_SECRET=your_stripe_secret_key
```

Get your Stripe API key from [Stripe Dashboard](https://stripe.com/)

4. Run the development server

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000)

## Project Structure

```
app/
├── (store)/        # Zustand store
├── api/           # API routes
├── product/       # Product pages
├── success/       # Success page
└── cancel/        # Cancel page
```

## Environment Variables

- `STRIPE_SECRET` - Your Stripe secret key

## License

MIT
