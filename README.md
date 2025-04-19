# ⚡ Lightning: **AI‑powered full-stack engineering system — built for Vercel, designed by Likhon.**  
Injects logic via GitHub `raw` links and turns `v0` into an unstoppable dev agent.

## What It Does

- Reads project logic from:
  - [`v0.txt`](https://raw.githubusercontent.com/likhonsheikhcodes/Lightning/main/v0.txt)
  - [`system.txt`](https://raw.githubusercontent.com/likhonsheikhcodes/Lightning/main/system.txt)
- Converts prompts into:
  - Typed React + Tailwind + Shadcn UI
  - API routes, env config, SEO meta
  - Secure, scalable, structured apps

## Live Agent Injection

You can use this inside **OpenAI, Together AI, Groq** or any AI system:

```ts
const messages = [
  {
    role: "system",
    content: await fetch('https://raw.githubusercontent.com/likhonsheikhcodes/Lightning/main/v0.txt').then(r => r.text())
  },
  {
    role: "user",
    content: "Build a dashboard with dark mode, auth, and charts."
  }
]

Repo Structure

File	Purpose
v0.txt	Master system prompt
system.txt	AI behavior, coding style rules
README.md	This file, how it works

Powered By
	•	Vercel
	•	Next.js App Router
	•	Tailwind + Shadcn/ui
	•	Likhon Sheikh’s full-stack AI architecture

⸻

Inject. Prompt. Deploy.
Welcome to the AI coding era.

---

### `system.txt` (already generated, place in root)

Make sure both `v0.txt` and `system.txt` are in the repo’s root so the `raw.githubusercontent` URLs stay simple.

