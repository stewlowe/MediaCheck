# MediaCheck 0.15.2 Beta

## Feedback and support

- Added a prominent **Send feedback** button that opens the official GitHub report form.
- Added clear instructions for reporting a problem and optionally attaching an inspected support bundle.
- Clarified that reports are never sent automatically and that media files should never be attached.
- Added the same feedback guidance to Diagnostics and the downloadable beta package.

## Issue-review improvements

- Enlarged the inline Issue details area and added a draggable divider.
- Added **Expand details view…** beside the Issue details heading for a separate resizable reading window.
- Added playback testing and structured feedback recording for flagged files.
- Issue-report exports now include playback observations, tester severity, notes, container, and codecs.

## Decode-location guidance

- Deep checks now record FFmpeg's last reported decode position and identify approximately where playback should be inspected.
- A missing FFmpeg timestamp is explicitly reported as **Decode error location: unavailable** instead of being confused with a genuine error at `0:00:00`.
- Plain-language guidance explains what the location means and what to check.

## Other refinements

- Added a dedicated pause/enable action for individual library locations.
- Improved issue-pane sizing and button placement on common Windows displays.
- Expanded automated coverage to 79 passing tests.

## Known beta limitations

- The installer is not digitally signed and may trigger Windows SmartScreen.
- FFprobe and FFmpeg must be installed or downloaded separately.
- MediaCheck does not repair, move, rename, or delete media files.

## Installer checksum

`MediaCheck-Setup.exe`

SHA-256:

`986CD0CD6A91ABD7EFAFCCA5F3D769313405A00D236019E039DF62CA93D47C0D`
