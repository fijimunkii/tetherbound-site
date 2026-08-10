# TetherBound site

Public validation and product-information site for **TetherBound**.

**Give AI access. Keep it bounded.**

TetherBound is a security-first MCP layer for giving **ChatGPT, Codex, and other MCP clients bounded access to machines over Tailscale**. Tailscale provides private connectivity and machine identity; TetherBound adds typed operations, local policy, hard bounds, and audit controls designed for AI access.

Useful discovery terms for the project include **ChatGPT + Tailscale**, **Tailscale MCP**, **ChatGPT MCP**, **Codex + Tailscale**, and **secure AI infrastructure access**. The product name remains TetherBound; this is not an official Tailscale or OpenAI product.

This repository intentionally contains only public website content and early-access intake. The private incubation repository retains its historical `chatgpt-plugin-tailscale` name. The future public Community runtime repository is expected to use the canonical TetherBound name.

## Local preview

```bash
python3 -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

## Deployment

GitHub Pages deploys `main` through `.github/workflows/pages.yml`.

Custom domain: `tetherbound.dev`
