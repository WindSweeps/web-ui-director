# Web UI Director

An Agent Skill for task-first interfaces, content-driven grids, consistent typography, accessibility, and verification in the actual UI. It uses a strict six-unit type scale for authored UI and presentation text.

## Install

**ChatGPT desktop.** In the Git repository plugin installer, enter `https://github.com/WindSweeps/web-ui-director` and install **Web UI Director**. In a new chat, ask ChatGPT or Codex to use Web UI Director on your UI task.

**Codex CLI.** Add the marketplace and install the plugin.

```sh
codex plugin marketplace add WindSweeps/web-ui-director
codex plugin add web-ui-director@windsweeps-ui
```

**Claude Code.** Run these in the terminal.

```sh
claude plugin marketplace add WindSweeps/web-ui-director
claude plugin install web-ui-director@windsweeps-ui
```

In a Claude Code session, invoke `/web-ui-director:web-ui-director` with your task.

**Other Agent Skills clients.** Copy the entire [skill directory](skills/web-ui-director/) into the client's skills directory. Keep `SKILL.md` and `references/` together.

## Example request

> Use Web UI Director to refine this settings page. Keep the primary controls visible, use shared type tokens, and verify keyboard navigation and reflow in the browser.

The plugin contains Markdown instructions and references and requires no API keys or runtime dependencies.
