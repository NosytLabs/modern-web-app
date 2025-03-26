# Modern Web App

A Next.js application with user settings, authentication, and modern UI components.

## Features

- 🔐 Authentication with NextAuth.js
- 🎨 Modern UI with Tailwind CSS
- 🌙 Dark mode support
- ⚡ Fast and responsive
- 🔍 Type-safe with TypeScript
- 📱 Mobile-friendly design
- 🔧 User settings management
- 🗄️ PostgreSQL database with Prisma

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/NosytLabs/modern-web-app.git
cd modern-web-app
```

2. Install dependencies:
```bash
npm install
```

3. Copy the example environment file:
```bash
cp .env.example .env
```

4. Update the environment variables in `.env` with your configuration.

5. Set up the database:
```bash
npm run prisma:generate
npm run prisma:push
```

6. Start the development server:
```bash
npm run dev
```

## Project Structure

- `/src/app` - App router pages and layouts
- `/src/components` - Reusable UI components
- `/src/lib` - Utility functions and shared logic
- `/src/types` - TypeScript type definitions
- `/src/styles` - Global styles and Tailwind configuration
- `/src/contexts` - React context providers
- `/src/hooks` - Custom React hooks
- `/prisma` - Database schema and migrations

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run test` - Run tests
- `npm run typecheck` - Check TypeScript types
- `npm run prisma:generate` - Generate Prisma client
- `npm run prisma:push` - Push schema changes to database
- `npm run prisma:studio` - Open Prisma Studio

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.