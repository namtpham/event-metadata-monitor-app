# Media for the home page

Files put here show in the "See it" section of the home page, above Download.
Missing files are skipped; with none the section stays hidden.

| File | Caption on the page | What it shows |
| --- | --- | --- |
| `screenshot-1.png` | Main window after 30 hours: cameras, live event log, memory and RTP loss | The whole window, connected, events scrolling |
| `screenshot-2.png` | Event statistics after 30 hours of monitoring | "Show event statistics" switched on |
| `screenshot-3.png` | An event's metadata (double-click a feature) | The colour-coded metadata panel over the log |
| `screenshot-4.png` | Features: choose which events to show | The Features popup |
| `screenshot-5.png` | Right-click a feature: only its events are shown | The Features popup after a right-click on one feature |
| `screenshot-6.png` | Paused (Space): the banner counts the events skipped | The log while paused |
| `screenshot-7.png` | Settings > General | The General settings popup |
| `screenshot-8.png` | A new version is out | The update notice |
| `demo.mp4` | (optional) In use | A short H.264 video, best under 25 MB (the upload limit on github.com) |
| `demo.jpg` | (optional) | The picture shown before the video plays |

The screenshots here were made with simulated camera data (a pretend camera
streaming a fictional analytics app, "SimSight", with a 30-hour session
simulated), so they show no real devices, places or people. If you replace them with captures from real cameras, blur or
crop out IP addresses, user names and passwords first.

To add or replace them on github.com: open this folder, **Add file > Upload
files**, drop the files (with exactly these names), **Commit changes**. The
home page shows them a minute later.

Captions and other names: edit `SCREENSHOTS`, `DEMO_VIDEO` and `DEMO_POSTER`
near the top of the script in `index.html`.
