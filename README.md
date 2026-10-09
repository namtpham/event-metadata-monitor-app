<p align="center">
  <img src="icon.png" width="96" alt="">
</p>

<h1 align="center">Event Metadata Monitor<br><sub>for ONVIF cameras</sub></h1>

<p align="center">
  See the analytics events of your ONVIF IP cameras live: every event, its state, rule and metadata.<br>
  A free app for Windows 10 / 11 (64-bit).
</p>

<p align="center">
  <a href="https://namtpham.github.io/event-metadata-monitor-app/"><b>Home page</b></a> ·
  <a href="https://github.com/namtpham/event-metadata-monitor-app/releases/latest"><b>Download</b></a> ·
  <a href="https://namtpham.github.io/event-metadata-monitor-app/#whats-new">What's new</a> ·
  <a href="https://namtpham.github.io/event-metadata-monitor-app/#feedback">Feedback</a> ·
  <a href="https://buymeacoffee.com/namtpham">Buy me a coffee</a>
</p>

## What it is

IP cameras with video analytics (line crossing, intrusion, object detection and many more)
report what they see as **ONVIF event metadata**, a stream of XML next to the video. Event
Metadata Monitor connects to that stream over RTSP and shows each event the moment it arrives,
as one readable line: the time, the feature, whether it started or ended (**True** / **False**),
the rule that fired, and the details you choose (object ID, Enter / Exit, speed, count…).

- **Filters** by feature, state and rule; **Pause** (Space) to read.
- **Double-click** a timestamp to copy the event's XML, or a feature to see it colour-coded.
- **Event statistics** per feature, with average rates and Enter / Exit counts.
- **RTP packet loss** and memory charts for long sessions.
- Saves event logs and metadata per camera, if you want.
- Any ONVIF camera: the metadata path is filled in for Avigilon, Axis, Bosch, Dahua, Hanwha Vision, Hikvision
  and Uniview (changeable in Settings), and any other camera works with its own path (Maker Custom). Events from any analytics app, no setup.
- Reconnects by itself; updates itself (Help > Check for updates > Update now).

## Get it

1. Download the `.zip` from the [latest release](https://github.com/namtpham/event-metadata-monitor-app/releases/latest).
2. Unpack it anywhere you can write to (not Program Files) and start `EventMetadataMonitor.exe`.
   New versions install themselves: Help > Check for updates > **Update now**.

Windows may say "Windows protected your PC" for a new app: click **More info > Run anyway**.
The app is portable: your cameras, settings, logs and saved data stay in its folder.

## Feedback

Questions, ideas and bug reports: use the [form on the home page](https://namtpham.github.io/event-metadata-monitor-app/#feedback)
(no account needed) or [open an issue](https://github.com/namtpham/event-metadata-monitor-app/issues/new).

---

This repository holds the app's home page and its releases (the app's source code is not public).
Screenshots for the home page go in [media/](media/).

Made by [Pham Thanh Nam](https://namtpham.github.io/). Like it? [Buy me a coffee](https://buymeacoffee.com/namtpham).
