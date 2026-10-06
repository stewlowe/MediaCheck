# MediaCheck 0.15.1 Beta

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

`E5193AAB32E288324E0E37729C479E12F2BC7CC00D04A7FADC123FCCE62DFB17`
