# Sevenpreneur AI Clone 🚀

This is a clone of the Sevenpreneur.io platform with AI integration using OpenAI to help users brainstorm and launch digital products.

## Features
- AI Assistant to suggest digital product ideas
- Product listing and detail pages
- Simple Notion-style product structure (Markdown/JSON)
- Tailwind CSS for fast and clean UI
- Mobile-responsive
- Easy deployment to Vercel

## Setup Instructions

1. Clone or unzip the project
2. Install dependencies:

```bash
npm install
```

3. Set up OpenAI API Key:

Create a `.env.local` file:

```env
OPENAI_API_KEY=your_openai_key_here
```

4. Run the project locally:

```bash
npm run dev
```

Visit `http://localhost:3000`

## AI Assistant

Located in `pages/api/ai.ts` and used in the `AIAssistant.tsx` component.

## Deployment

Easiest with [Vercel](https://vercel.com). Just import the project and set the environment variable.
