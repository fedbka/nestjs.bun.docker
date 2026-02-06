# NestJS Bun Docker Template

A modern [NestJS](https://nestjs.com/) template powered by [Bun.js](https://bun.sh/) runtime and [Biome.js](https://biomejs.dev/) for linting and formatting.

## Getting Started

### Installation

```bash
bun install
```

### Development

```bash
# Start the application
bun run start

# Start the application in development mode
bun run start:dev

# Start the application in development mode with debug
bun run start:debug

```

## Code Quality

This template uses [Biome.js](https://biomejs.dev/) for linting and formatting.

```bash
# Check code formatting and linting
bun run check

# Auto-fix formatting and linting issues
bun run check:fix

# Format code only
bun run format

# Lint code only
bun run lint

# Auto-fix linting issues
bun run lint:fix

```

## Testing

```bash
# Unit tests
bun test

# Watch mode
bun run test:watch

# Test coverage
bun run test:cov

```

## Project Structure

```
.
├── src/
│   ├── main.ts           # Application entry point
│   ├── app.module.ts     # Root module
│   ├── app.controller.ts # Example controller
│   └── app.service.ts    # Example service
├── biome.json            # Biome configuration
├── nest-cli.json         # NestJS CLI configuration
├── tsconfig.json         # TypeScript configuration
└── package.json          # Dependencies and scripts

## Learn More

- [NestJS Documentation](https://docs.nestjs.com)
- [Bun Documentation](https://bun.sh/docs)
- [Biome Documentation](https://biomejs.dev/guides/getting-started/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)

## License

MIT