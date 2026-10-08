# Media for the home page

Files put here show in the "See it" section of the home page, above Download.
Missing files are skipped; with none the section stays hidden.

| File | Caption on the page | What to capture |
| --- | --- | --- |
| `screenshot-1.png` | Main window: cameras, live event log and filters | The whole window, connected, with events scrolling |
| `screenshot-2.png` | Event statistics | "Show event statistics" switched on, after a few minutes of events |
| `screenshot-3.png` | An event's metadata (double-click a feature) | The colour-coded metadata panel over the log |
| `screenshot-4.png` | Features: choose which events to show | The Features popup |
| `screenshot-5.png` | Settings > General | The General settings popup |
| `screenshot-6.png` | A new version is out | The update notice (see `tools/update_test_server.py` in the source repository to make it appear) |
| `demo.mp4` | (optional) In use | A short H.264 video, best under 25 MB (the upload limit on github.com) |
| `demo.jpg` | (optional) | The picture shown before the video plays |

Tip: blur or crop out camera IP addresses, user names and passwords before uploading.

To add or replace them on github.com: open this folder, **Add file > Upload
files**, drop the files (with exactly these names), **Commit changes**. The
home page shows them a minute later.

Captions and other names: edit `SCREENSHOTS`, `DEMO_VIDEO` and `DEMO_POSTER`
near the top of the script in `index.html`.
