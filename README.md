# Flexxible - NextJS Application

Welcome to Flexxible, a powerful Next.js application that brings together an array of essential features to supercharge your web development experience. From user management with NextAuth to Google authentication, Graffbase GraphQL database management, JWT, Tailwind CSS, and TypeScript support, Flexxible has got it all covered.

### Live Version: https://flexibble-bay.vercel.app/

## Features
- **User Management**: Integrate user management effortlessly using NextAuth.
- **Google Authentication**: Enable Google authentication for seamless access.
- **Graffbase GraphQL**: Manage your database with Graffbase's GraphQL capabilities.
- **JWT**: Utilize JSON Web Tokens for secure authentication and data exchange.
- **Tailwind CSS**: Enhance your UI with the power of Tailwind CSS.
- **TypeScript**: Benefit from strong typing and error-checking with TypeScript.

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) installed on your machine.
- [Directus](https://directus.io/) instance running as a backend.

### Getting Started
1. **Navigate to the project directory**:
cd flexxible-nextjs

2. **Install the dependencies for the client and server**:
cd client && npm install
cd ../server && npm install

3. **Set up environment variables**:
- Rename `.env.example` to `.env.local` in the `client` and `server` directories and configure the necessary environment variables.

4. **Run the application**:
- Start the client:
  ```
  cd client && npm run dev
  ```
- Start the server:
  ```
  cd server && npm run dev
  ```

5. **Restart your Directus instance** to ensure smooth integration.

Now you're ready to experience the flexibility and power of Flexxible. Happy coding!

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute, report issues, or suggest improvements. We welcome your creativity and insights to make Flexxible even more flexible!
