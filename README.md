# Applet plugins

Plugins for [Applet](https://applet.one): build, run and share small stateful apps from chat, with no local environment.

## Install in ChatGPT or Codex

1. Add this marketplace (needs the [Codex CLI](https://developers.openai.com/codex)):

   ```sh
   codex plugin marketplace add applet-one/plugins
   ```

2. Restart the ChatGPT desktop app, open the Plugins Directory, choose **applet-one** and install **Applet**.
3. Sign in with your applet.one account when asked, then start a new chat: "Build me a small app to track my team's lunch orders".

Update later with `codex plugin marketplace upgrade applet-one`.

## Contents

- `plugins/applet/`: the plugin (`plugin.json`, `mcp.json` pointing at `https://mcp.applet.one/mcp`, skills). Generated from the Applet platform repository; do not edit by hand.
- `.agents/plugins/marketplace.json`: the marketplace catalog.

Feedback and problems: open an issue in this repository.
