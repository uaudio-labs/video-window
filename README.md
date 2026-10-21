# Video Window

A LUNA Add On that plays a video in sync with LUNA's transport, for scoring and post work.

Requires LUNA 3.1.1 or later.

## Install

1. Download `video-window.lunaaddon` from the latest release on this repository's **Releases**
   page.
2. Double-click the file. LUNA installs it into its Add Ons folder.

To update, install the newer `.lunaaddon` the same way.

## Use

Open it from **Add Ons > Windows > Video Window** while a session is open. It opens as a
floating window; choose the menu item again to close it.

- **Open Video…**, or drop a video file on the window (MP4, MOV or WebM). The video follows
  LUNA's playhead, playing and stopped. When the playhead is outside the video, the window
  says so.
- **Start at** sets the session time at which the video starts, and the timecode of its first
  frame.
- **Format** sets the counter: Min:Sec, timecode at 23.976, 24, 25, 29.97 DF, 29.97 ND or 30
  fps, or Feet+Frames. When you open a video, the counter takes its start timecode and rate
  from the file's timecode track, or its frame rate if it has none.
- **Import Audio** puts the video's audio on a new track, starting at the Start at time (one
  undo step).
- **Audio Off** mutes the video's own soundtrack.
- Hide the header with the ▴ button, or double-click the video; do the same to bring it back.

The session remembers its video, the Start at time, the start timecode and the counter
format, so they come back when you reopen it.

In some LUNA versions **Open Video…** opens nothing. If it doesn't, drop the file on the
window instead.
