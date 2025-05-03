# Blockchain.com Login Page Clone

This is a modern clone of the Blockchain.com login page built with Next.js, TypeScript, and Tailwind CSS.

## Features

- Responsive design matching Blockchain.com's login page
- Form validation using Formik and Yup
- Password visibility toggle
- Social login options (Google and Apple)
- Remember me functionality
- Toast notifications for form submission
- Modern UI with smooth transitions

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Technologies Used

- Next.js 14
- TypeScript
- Tailwind CSS
- Formik
- Yup
- React Hot Toast
- Heroicons

## Project Structure

```
src/
├── app/
│   ├── page.tsx        # Main login page
│   ├── layout.tsx      # Root layout with Toaster
│   └── globals.css     # Global styles
└── components/         # (if needed for future components)
```

## Customization

You can customize the following:

- Colors and styling in `globals.css`
- Form validation rules in `page.tsx`
- Social login providers
- Toast notification settings

## License

MIT
