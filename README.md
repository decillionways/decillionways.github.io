# decillionways.github.io

The website for apps by Ferrdins, served by GitHub Pages at https://decillionways.github.io/.

One folder per app; each app's repo builds only its own folder (`tools/build-site.mjs`), adds
itself to `apps.json`, and rebuilds the root `index.html` from that list.

| Folder | App | Built by |
|---|---|---|
| `mediahandler/` | Andromeda Media Handler | `node tools/build-site.mjs <this clone>` in the MediaHandler repo |
