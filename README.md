# Full Stack E-Commerce Application with Next.js, Stripe, and Sanity

A fully responsive, production-ready e-commerce platform with a sleek design, real-time payment processing, and an easy-to-manage product catalog powered by a headless CMS. This application is designed for scalability and efficiency, offering a seamless shopping experience and dynamic content management.

## Key Features

- **Modern UI/UX Design & Animations**: An intuitive, user-friendly design that enhances the shopping experience.
- **Next.js Integration**: Utilizes file-based routing, server-side rendering, and static generation for optimized performance.
  - Learn about: `getServerSideProps`, `getStaticPaths`, `getStaticProps`.
  - Use Next.js as a backend to handle API endpoints.
- **Advanced State Management**: Manage state efficiently across the entire application using the React Context API.
- **Stripe Integration**: Real payment functionality using Stripe, covering products, shipping rates, and checkout workflows.
- **Sanity CMS**: Dynamic content management for product listings and store details.
  - Clients can update product details and homepage content on the go via a user-friendly interface.
- **Fully Responsive**: The design ensures a seamless experience across all devices.

## Tech Stack

- **Frontend**: Next.js, React, JavaScript, CSS
- **Backend**: Next.js API Routes
- **Payments**: Stripe API for real-time payment processing
- **CMS**: Sanity for dynamic content management
- **Deployment**: Vercel for frontend deployment and integration with Stripe and Sanity

## Getting Started

To set up this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ecommerce-app
   ```

````

2. Install dependencies:
```npm install```

3. Setup environment variable:
````

NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key

````

4. Run the server:
```npm run dev
````
