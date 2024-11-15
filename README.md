# StripeX - SaaS Stripe Integration Project

![StripeX Demo](https://via.placeholder.com/800x400.png?text=StripeX+Demo)

StripeX is a **Next.js** project designed to demonstrate seamless integration with **Stripe** for managing subscriptions in a SaaS (Software-as-a-Service) application. It features a robust tech stack, modern design patterns, and a focus on scalability.

[Live Demo](https://stripex.vercel.app)

## Features

- **Stripe Integration**: Easy subscription handling via the Stripe API.
- **Authentication**: Powered by [Kinde Auth for Next.js](https://kinde.com/), enabling secure user sign-in/out flows.
- **Dynamic Theming**: Built with `next-themes` for theme toggling.
- **Modern UI Components**: Implemented using Radix UI libraries for accessible and customizable designs.
- **State Management**: State queries and caching handled with `@tanstack/react-query`.
- **Tailwind CSS**: Highly customizable and utility-first CSS framework for consistent styling.
- **Database**: Integrated with Prisma ORM for scalable database operations.

---

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (v14.2.4)
- **Programming Language**: TypeScript
- **Database**: Prisma
- **CSS Framework**: Tailwind CSS
- **API Integration**: Stripe (v16.0.0)
- **UI Components**: Radix UI, Lucide Icons
- **State Management**: React Query

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kunaldhongade/stripex
   cd stripex
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up your environment variables:
   Create a `.env` file in the root directory and add the following:

   ```env
   NEXT_PUBLIC_STRIPE_API_KEY=your_stripe_public_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   DATABASE_URL=your_database_connection_string
   ```

4. Generate Prisma client:

   ```bash
   npx prisma generate
   ```

5. Run the development server:
   ```bash
   npm run dev
   ```

---

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm start`: Start the production server.
- `npm run lint`: Run ESLint for code linting.
- `npm run postinstall`: Generate Prisma client after dependency installation.

---

## Future Enhancements

- Add more detailed Stripe webhook event handling.
- Implement advanced analytics for subscription metrics.
- Add unit and integration tests.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push:
   ```bash
   git push origin feature-name
   ```
4. Open a Pull Request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

Happy coding! 🚀
