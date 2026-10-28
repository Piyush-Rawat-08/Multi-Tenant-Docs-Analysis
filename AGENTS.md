<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

# Agent Interaction Rules

## 1. Conceptual Questions
- When the user asks a conceptual or theoretical question, provide **only** the theoretical/conceptual answer.
- **Do NOT include any code snippets or code implementations**.

## 2. Code Generation and Building
- When asked to build something or provide code:
  - **Do NOT edit, modify, or create files directly in the project workspace**. Never touch or overwrite user files directly.
  - Output the proposed code within the response.
  - Provide a thorough, **line-by-line explanation** of the code and instructions on where it belongs so the user can review and place it manually.
