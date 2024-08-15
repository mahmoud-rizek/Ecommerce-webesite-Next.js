# E-commerce Website

This project is a full-stack e-commerce website built with [Next.js 14](https://nextjs.org/), [Strapi CMS](https://strapi.io/), [Tailwind CSS](https://tailwindcss.com/), and [Stripe](https://stripe.com/) for payment processing.

## Features

- **Product Management**: Manage products via Strapi CMS.
- **User Authentication**: Register, log in, and manage profiles.
- **Shopping Cart**: Add products and checkout with Stripe.
- **Responsive Design**: Built with Tailwind CSS for all devices.

## Getting Started

### Prerequisites

- Node.js >= 18.x
- Strapi CMS setup
- Stripe account

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mahmoud-rizek/Ecommerce-webesite-Next.js
   cd Ecommerce-webesite-Next.js

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables** in a `.env.local` file:

   ```plaintext
   NEXT_PUBLIC_STRAPI_API_URL=http://localhost:1337
   STRIPE_PUBLIC_KEY=your_stripe_public_key
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Authentication

- **Registration & Login**: Users can sign up and log in to access protected routes.
- **JWT Authentication**: Secure routes using JSON Web Tokens (JWT).

## Folder Structure

```csharp
ecommerce-website/
├── components/       # Reusable components
├── pages/            # Next.js pages
├── public/           # Static assets
├── styles/           # Tailwind CSS styles
└── .env.local        # Environment variables
```

