# EShop

Welcome to EShop, a Next.js project for an online store. This project is bootstrapped with `create-next-app` and includes integration with [Clerk](https://clerk.com) for authentication and [PlanetScale](https://planetscale.com/) for the database.

## Getting Started

To get started, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/JeevanJoshi4434/EShop.git
    cd eshop
    ```

2. Rename the `.env.example` file to `.env` and set up your accounts on Clerk and PlanetScale.

3. Obtain your API keys from Clerk: `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` and `CLERK_SECRET_KEY`. Set these values in the `.env` file.

4. Set up your PlanetScale database and obtain the `DATABASE_URL`. Set this value in the `.env` file.

5. Install dependencies and initialize the Prisma database:

    ```bash
    npm install
    npx prisma init
    npx prisma generate
    npx prisma db push
    ```

6. Run the development server:

    ```bash
    npm run dev
    ```

7. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Authors

Special thanks to [Code with Antonio - YouTube](https://www.youtube.com/watch?v=5miHyP6lExg).

Cloned by:
- [Jeevan Joshi - GitHub](https://www.github.com/JeevanJoshi4434)
- [Jeevan Joshi - Instagram](https://www.instagram.com/Jeevan_Joshi_4434)

## Original Source

Check out the original source at [Code with Antonio](https://www.youtube.com/watch?v=5miHyP6lExg).

Feel free to modify and enhance the project according to your needs. Happy coding!