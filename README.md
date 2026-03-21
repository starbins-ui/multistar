# MultiStar

Simple single-page demo for an online sales experience. It includes a login prompt and a basic product grid to simulate browsing and adding items to a cart.

## Features
- Login gate that switches to the storefront when credentials are entered
- Responsive grid of sample products with placeholder images
- Clean dark theme with accent highlights
- **AI Product Assistant** powered by Claude Opus (`claude-opus-4-5`) via the Anthropic API

## Getting Started
1. Open [`multistar17_html code.html`](./multistar17_html%20code.html) in any modern web browser.
2. Enter a username and password (any values) or click the site link to view the storefront.

No build tools or dependencies are required—just open the HTML file locally.

## AI Product Assistant

After entering the shop a **💬 chat button** appears in the bottom-right corner.

1. Click the button to open the chat panel.
2. Paste your [Anthropic API key](https://console.anthropic.com/settings/keys) (`sk-ant-…`) and press **Save**.
3. Ask questions about products, pricing, recommendations, etc.

The assistant uses the **`claude-opus-4-5`** model and keeps a conversation history for the current session. The API key is stored only in `sessionStorage` and is never persisted beyond the browser tab.
