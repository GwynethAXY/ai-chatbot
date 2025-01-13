This is an AI enabled chatbot.

## Getting Started
This project uses `pnpm` as a package manager. If you dont have pnpm installed, you can install it globally by running:
```bash
npm install -g pnpm
```

Install the project's packages:
```bash
pnpm i
```

### Running locally

First, paste the provided variables in the `.env.local` file.

Then, run the development server:
```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


# Assignment details
- Next.js was selected as the framework as it provides Server-side Rendering. This is particularly useful for chatbots which handle dynamic content.
- To make calls to LLM providers (OpenAI models were used here), the Vercel AI SDK was used.
- For saving chat histroy and user data (authentication), the data persistence of choice was Neon, a servless Postgres solution.
- NextAuth.js was used for simple and secure authentication
