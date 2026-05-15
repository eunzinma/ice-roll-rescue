# ICE ROLL RESCUE

Mobile web mini game for VARoL, optimized for Instagram profile links, iPhone Safari, Instagram in-app browser, and Android Chrome.

## Project Structure

```text
.
+-- index.html
+-- assets/
|   +-- characters/
|   +-- roller/
|   +-- tutorial/
|   +-- ui/
+-- README.md
+-- vercel.json
```

## Deployment

### Vercel

1. Upload or push this repository to GitHub.
2. Import the repository in Vercel.
3. Use the default settings:
   - Framework Preset: `Other`
   - Build Command: leave empty
   - Output Directory: leave empty
4. Deploy.

The game is a static HTML/CSS/JavaScript project, so no build step is required.

## Local Preview

Open `index.html` in a browser, or run any simple static server from the project root.

Example:

```bash
npx serve .
```

## Mobile Notes

- 9:16 vertical layout
- Full mobile viewport support with safe-area handling
- Scroll, zoom, text selection, and image dragging are disabled
- Touch interaction is optimized for the ice roller
- Optimized mobile PNG assets are used in production paths
