# Embed Dashboard Creator

A single-file Discord embed builder with a live preview. Design embeds (title, description, color, images, fields, buttons), watch them render like they will in Discord, then send to a Make.com webhook as JSON.

## Stack

- **Pure static HTML** — one file (`index.html`), no framework, no build step, no dependencies
- Webhook URL and Channel ID are saved in the browser's localStorage (never sent to any server)

## Running

```
python3 -m http.server 5000
```

The app is served from the root directory. Open the preview to use it.

## Project structure

```
index.html   # entire app — markup, styles, and logic in one file
README.md    # project documentation
```

## User preferences

<!-- Add user preferences here as they are confirmed -->
