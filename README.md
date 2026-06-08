# no-ai-ads

A uBlock Origin filter list that blocks ads from AI startups and AI-branded businesses.

## Built with AI
AI did the heavy lifting on building and creating this repo. I know this seems hypocritical to be using AI to block AI and AI related businesses, but AI is a tool at our disposable and it's our choice on how we use it. I chose to use AI responsibly to create tools to combat againest AI. So yes, this list was built with the help of AI. Specifically Claude by Anthropic — one of the companies blocked by this very list.

AI can make mistakes. As always human contributors and edits are always welcome! 

## Subscribe

> ⚠️ **Chrome users:** uBlock Origin on Chrome is the "Lite" version due to Google's Manifest V3 restrictions and does **not** support external filter list subscriptions. Use Firefox or Brave for the full experience.

### Firefox or Brave
1. Install [uBlock Origin](https://ublockorigin.com/) (Firefox) or use Brave's built-in shields
2. Open the uBlock Origin dashboard → **Filter lists** tab → scroll to the bottom
3. Paste this URL into the Import field and hit **Apply changes**:
```
https://raw.githubusercontent.com/andyblueyo/no-ai-ads/main/no-ai-ads.txt
```
The list will auto-update every 7 days.

### Chrome (manual)
1. Open uBlock Origin Lite → **Custom filters** tab
2. Paste the contents of [no-ai-ads.txt](./no-ai-ads.txt) into the text box
3. Hit **Import and append**

You'll need to re-paste manually when the list updates.

## What's blocked

- AI foundation labs (OpenAI, Anthropic, xAI, Mistral, etc.)
- AI coding tools (Cursor, Copilot, Replit, Windsurf, Devin)
- AI search & assistants (Perplexity, Character.AI, You.com)
- AI productivity & writing tools (Grammarly, Jasper, ElevenLabs, etc.)
- AI image & video generation (Midjourney, Runway, Stability AI, Pika, etc.)
- AI infrastructure & B2B (Scale AI, Hugging Face, Databricks, Harvey, etc.)
- AI hardware (Cerebras)

All rules use `$third-party` — meaning these domains are only blocked when loading as ads on other sites, not when you visit them directly.

## Contributing

Spotted an AI ad that isn't blocked? [Open an issue](https://github.com/andyblueyo/no-ai-ads/issues) or submit a PR with the domain added to `no-ai-ads.txt`.

## License

[CC0 1.0 Universal](./LICENSE) — public domain, do whatever you want with it.
