# AImpress

An AI-powered image processing platform for enhancing, transforming, and generating visual content.

## Overview

AImpress provides a set of AI-powered tools for working with images, including image enhancement, background removal, object removal, and color replacement.

The application combines user authentication, image processing services, cloud storage, and a credit-based payment system into a single SaaS platform.

## Features

- AI image enhancement
- Image upscaling
- Background removal
- Unwanted object removal
- Image recoloring
- User authentication
- Credit-based usage system
- Payment integration
- Cloud image storage
- Responsive interface

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- Clerk
- MongoDB Atlas
- Cloudinary
- Stripe

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- A MongoDB Atlas database
- A Clerk application
- A Cloudinary account
- A Stripe account
- Required AI service credentials

### Installation

Clone the repository:

```bash
git clone https://github.com/Artiushchenko/AImpress.git
cd AImpress
```

Install dependencies:

```bash
npm install
```

### Environment Variables

Create a `.env.local` file in the root directory and add the required environment variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

MONGODB_URL=your_mongodb_connection_string

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
```

Configure any additional variables required by the image processing services used by the application.

### Development

Start the development server:

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:3000
```

## Production

Create a production build:

```bash
npm run build
```

Start the production server:

```bash
npm run start
```

## Project Structure

```text
AImpress/
├── app/              # Next.js application routes
├── components/       # Reusable UI components
├── constants/        # Application constants
├── hooks/            # Custom React hooks
├── lib/              # Services and utilities
├── public/            # Static assets
├── types/             # TypeScript types
├── middleware.ts      # Application middleware
├── next.config.mjs    # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── package.json       # Project dependencies and scripts
```

## Deployment

The application can be deployed to Vercel with the required environment variables and external services configured.

## License

This project is intended for personal and portfolio use.
