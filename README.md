# Canvashand

Canvashand is a Figma MCP server plus a Figma plugin. AI clients such as Claude Code, Cursor, Codex, VS Code, Gemini CLI and Windsurf use it to read and edit live Figma files.

This repository holds the listing README and manifests only. Canvashand is proprietary and its source code is not here.

## What it does

- 102 MCP tools to read and edit Figma files.
- Several Figma files at once, with one agent per file.
- Change sessions with rollback, so you can undo what an agent changed.
- No Figma API token and no Dev seat. Figma's rate limits do not apply.
- App Store and Google Play screenshot sets made from your app's real screens.

## Store screenshots

Canvashand builds store screenshot sets in Figma from your app's own screens, in five looks with a full or cropped phone. This set uses the Panorama look on Starward, a demo app. See every look at https://www.canvashand.com/#store-screenshots.

<p>
<img src="https://www.canvashand.com/showcase/panorama-iphone-1.webp" width="130" alt="Panorama look, iPhone, screenshot 1 of 6">
<img src="https://www.canvashand.com/showcase/panorama-iphone-2.webp" width="130" alt="Panorama look, iPhone, screenshot 2 of 6">
<img src="https://www.canvashand.com/showcase/panorama-iphone-3.webp" width="130" alt="Panorama look, iPhone, screenshot 3 of 6">
<img src="https://www.canvashand.com/showcase/panorama-iphone-4.webp" width="130" alt="Panorama look, iPhone, screenshot 4 of 6">
<img src="https://www.canvashand.com/showcase/panorama-iphone-5.webp" width="130" alt="Panorama look, iPhone, screenshot 5 of 6">
<img src="https://www.canvashand.com/showcase/panorama-iphone-6.webp" width="130" alt="Panorama look, iPhone, screenshot 6 of 6">
</p>

## Install

1. Install the command line tool:

   ```sh
   curl -fsSL https://www.canvashand.com/install.sh | sh
   ```

2. Connect your AI clients:

   ```sh
   canvashand setup --all
   ```

3. Import the Canvashand plugin in Figma. The steps are at https://www.canvashand.com/setup.

Installers for macOS, Linux and Windows are at https://www.canvashand.com/download.

## Pricing

- Free: 2,000 tool calls a month.
- Pro: $6.99 a month or $69.99 a year. Unlimited calls. Your first Pro plan starts with a 7-day free trial.

Full plan details are at https://www.canvashand.com/pricing.

## Privacy

The plugin talks to the server on 127.0.0.1. Your designs never reach Canvashand's servers.

## Links

- Site: https://www.canvashand.com
- Setup: https://www.canvashand.com/setup
- Download: https://www.canvashand.com/download
- Pricing: https://www.canvashand.com/pricing
- Guides: https://www.canvashand.com/guides
- Privacy: https://www.canvashand.com/privacy

## Support

Email joe@canvashand.com.

## License

Proprietary. All rights reserved.

Figma is a trademark of Figma, Inc. Canvashand is independent and not affiliated with Figma, Inc.
