# Mermaid Flowchart Designer Website

Frontend-only Vite app. Drag/drop Mermaid flowchart shapes, move nodes, connect them, edit arrow labels/styles, edit node shapes/colors, dark mode, responsive mobile UI, auto layout, snap, zoom, Markdown/SVG/PNG export and Mermaid Markdown import.

Run: `npm install` then `npm run dev`.

Build: `npm run build` and deploy `dist/` to GitHub Pages or another static host.


**GitHub setup**

1. Push the changes to the repository’s `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Add this DNS record with your domain provider:

```text
Type: CNAME
Name: flowchart
Target: jacobpclouse.github.io
```

In **Settings → Pages → Custom domain**, enter:

```text
flowchart.jacobpclouse.net
```

GitHub should eventually show the domain as verified and enable HTTPS. The workflow will deploy automatically on every push to `main`.

