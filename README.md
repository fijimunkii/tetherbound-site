# TetherBound site

Public product-information site for **TetherBound**.

**Give AI access. Keep it bounded.**

TetherBound is a security-first MCP layer for giving **ChatGPT, Codex, and other MCP clients controlled access to machines over Tailscale**. Tailscale provides private connectivity and machine identity; TetherBound adds host admission, Bounded read-only tools, an explicit time-bounded Operator mode, execution/output limits, and audit controls designed for AI access.

Useful discovery terms for the project include **ChatGPT + Tailscale**, **Tailscale MCP**, **ChatGPT MCP**, **Codex + Tailscale**, **self-hosted MCP**, and **secure AI infrastructure access**. The product name remains TetherBound; this is not an official Tailscale or OpenAI product.

The canonical open-source/self-hosted Community runtime is:

- [`fijimunkii/chatgpt-plugin-tailscale`](https://github.com/fijimunkii/chatgpt-plugin-tailscale)

The literal repository name is intentionally retained as a first-class distribution and discovery surface. **TetherBound** is the product and security model; **chatgpt-plugin-tailscale** is the public self-hosted Community project.

This `tetherbound-site` repository contains only public website content and Cloud early-access intake. TetherBound Cloud is an optional hosted layer under validation; it is not required to run the Community product.

## Local preview

```bash
python3 -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

## Deployment

GitHub Pages deploys `main` through `.github/workflows/pages.yml`.

Custom domain: `tetherbound.dev`
