This is my cooking-chat app

## Getting Started

First, you will need to set API keys and secrets in a .env file. I have left that out for security reasons.
Required Keys and Secrets

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET={run command openssl rand -base64 32 and copy in the result}

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

GITHUB_ID=
GITHUB_SECRET=

MONGODB_URI=
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

Tests can be run with npm test

Second, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
