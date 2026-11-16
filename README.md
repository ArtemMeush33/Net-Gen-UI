# New Gen UI

A daily working panel that shows a project as a 3D column of layers — Project, People, Agents, Services — with curved links between them.

**Open it:** https://artemmeush33.github.io/Net-Gen-UI/

- Built with [Three.js](https://threejs.org), loaded from a CDN. No build step.
- Everything lives in `index.html`. Tweakable values sit in the `CONFIG` object at the top; layers, items and links are in `LAYERS` and `LINKS` just below it.
- The data is sample data for now. Never commit API keys or secrets: live Notion/Miro data will need a small backend.
