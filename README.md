# Planetside

A procedural planet demo with a menubar, rendering controls, and grid and terrain options.

## Start here

[Open main build](https://actiondaveinri.github.io/planetside/index.html) · [All projects](https://github.com/ActionDaveInRI/spaceship/blob/main/PROJECTS.md)

One main HTML build.

## Run it

Open the main build through GitHub Pages, or serve the downloaded repository over HTTP. Internet access is needed for Three.js 0.159.0, its addons, and simplex-noise. The current page identifies itself as the menubar build without Photo Mode.

From inside this repository's folder, with Python 3 installed:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8000/>. On Windows, `py -m http.server 8000 --bind 127.0.0.1` is the equivalent command. Stop the server with Ctrl+C.

## Builds and files

| Build | File | Purpose |
|---|---|---|
| Planetside | [index.html](index.html) | The existing main build; use its menubar and in-page controls. |

The file links in this table show source on GitHub. Use the launch links above to run a build.

## Keeping this organized

Keep the documented starting build on `main`. Record changes with a short description of what changed; use named Git milestones (tags) for future checkpoints instead of adding another numbered copy. Preserve existing historical file paths, and update this guide when the launch path changes. Independent experiments can use a clearly named folder or branch.
