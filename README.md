This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


<!-- package.json -->
 "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@kinde-oss/kinde-auth-nextjs": "^2.1.6",
    "@pinecone-database/pinecone": "^2.0.1",
    "@radix-ui/react-avatar": "^1.0.4",
    "@radix-ui/react-dialog": "^1.0.5",
    "@radix-ui/react-dropdown-menu": "^2.0.6",
    "@radix-ui/react-progress": "^1.0.3",
    "@radix-ui/react-slot": "^1.0.2",
    "@radix-ui/react-toast": "^1.1.5",
    "@radix-ui/react-tooltip": "^1.0.7",
    "@tanstack/react-query": "^5.18.0",
    "@trpc/client": "^11.0.0-next-beta.251",
    "@trpc/next": "^11.0.0-next-beta.251",
    "@trpc/react-query": "^11.0.0-next-beta.251",
    "@trpc/server": "^11.0.0-next-beta.251",
    "@types/node": "20.11.13",
    "@types/react": "18.2.48",
    "@types/react-dom": "18.2.18",
    "@uploadthing/react": "^6.2.2",
    "autoprefixer": "10.4.17",
    "class-variance-authority": "^0.7.0",
    "clsx": "^2.1.0",
    "eslint": "8.56.0",
    "eslint-config-next": "14.1.0",
    "lucide-react": "^0.320.0",
    "next": "13.5.2",
    "openai": "^4.26.0",
    "postcss": "8.4.33",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "stripe": "^14.14.0",
    "tailwind-merge": "^2.2.1",
    "tailwindcss": "3.4.1",
    "tailwindcss-animate": "^1.0.7",
    "typescript": "5.3.3",
    "zod": "^3.22.4"
  }
}
