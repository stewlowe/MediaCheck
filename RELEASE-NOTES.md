# MediaCheck 0.15.0 Beta

## Beta-readiness improvements

- Added one-time **What's new** notes after an upgrade.
- Added a manual, HTTPS-only update-checking framework. It never silently downloads or installs software.
- Added a recovery window for unexpected interface errors with Continue, Diagnostics, and copy-details actions.
- Expanded automated coverage for update safety, interrupted work, large libraries, and settings compatibility.

## Existing highlights

- Read-only quick and deep health checks using FFprobe and FFmpeg
- Fast reuse of unchanged scan results
- Multiple library locations across local, removable, and network storage
- Plain-language issue guidance and focused issue rechecks
- Persistent Reviewed and Ignored issue states
- Scan history and change reports
- Fast duplicate candidates, full byte verification, and frame comparison
- Privacy-conscious diagnostics and support-bundle export

## Known beta limitations

- The installer is not digitally signed and may trigger Windows SmartScreen.
- FFprobe and FFmpeg must be installed or downloaded separately.
- MediaCheck does not repair, move, rename, or delete media files.

## Installer checksum

`MediaCheck-Setup.exe`

SHA-256:

`2EBB1DC7D2A94E4C312A9E48043F592C0336E4A6FF4BAD248B1CD84CF597B06A`
