# Laravel React Template

This is a template for a Laravel and React application. Best to understand for Next.js Developers. If you're still struggling follow along:

### Whats inside?

-   Laravel 10
-   React 18
-   Lucide React Icons
-   Vite
-   Tailwind CSS
-   Prettier (+ JetBrains IDE Configuration)
-   GitHub Workflow for Code Style and Tests

## Preperation

After you created the repository from this template you need to install the dependencies for the Laravel and React application.

```bash
composer install

npm install # or yarn, pnpm, ...
```

## Development

To start the development server for the Laravel application you can use the following command:

```bash
php artisan serve
```

And in a different terminal window the vite server for the React application:

```bash
npm run dev
```

### Environment Variables

Just copy the `.env.example` file to `.env` and fill in the necessary environment variables.

### React?

The React application is located in the `resources/js` directory. You can start developing your React application there.

## Deployment

For deployment, you should read the [official documentation](https://laravel.com/docs/10.x/deployment) from Laravel.

## Issues

### My GitHub Pipeline keeps failing

Run the following command to fix the code style:

```bash
npm run format
```
