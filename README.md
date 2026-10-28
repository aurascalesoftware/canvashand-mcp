# Canvashand

Canvashand is a Figma MCP server plus a Figma plugin. AI clients such as Claude Code, Cursor, Codex, VS Code, Gemini CLI and Windsurf use it to read and edit live Figma files.

This repository holds the listing README and manifests only. Canvashand is proprietary and its source code is not here.

## What it does

- 102 MCP tools to read and edit Figma files.
- Several Figma files at once, with one agent per file.
- Change sessions with rollback, so you can undo what an agent changed.
- No Figma API token and no Dev seat. Figma's rate limits do not apply.

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
