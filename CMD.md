Here's a brief description of the provided commands:

### Install Dependencies

Use the following command to install project dependencies, including various libraries and packages required for the "Gate - Master API."

```bash
npm add argon2 drizzle-orm pg pino pino-pretty zennv zod jsonwebtoken fastify-zod fastify-guard fastify
```

This command ensures that all the necessary dependencies are installed and ready to be used in the project.

### Install Dev Dependencies

Install development-specific dependencies using the following command:

```bash
npm add zod-to-json-schema @types/jsonwebtoken typescript tsx drizzle-kit @types/pg -D
```

These dev dependencies are essential for development tasks such as type checking, transpilation, and ensuring code quality.

### Initialize TypeScript

Initialize TypeScript configuration for the project with this command:

```bash
npx tsc --init
```

This command sets up TypeScript for your project, enabling type checking and enhancing code quality and maintainability.

### Run Migrations

Execute the following command to run database migrations:

```bash
npm run migrate
```

This step ensures that the database schema is up to date and matches the application's requirements.

### Run the Application

Start the application locally for development purposes with this command:

```bash
npm run dev
```

Running the application locally allows you to test and develop features in a controlled environment before deploying it to production.