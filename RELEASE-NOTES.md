# MediaCheck 0.16.0 Beta

## Check new files before adding them

- Added **Check new files…**, a temporary workspace for downloads, copies, recordings, and encodes that are not yet part of the permanent library.
- Accepts individual files or recursively scans a selected folder.
- Detects files that still appear to be changing and asks the user to wait for the transfer to finish.

## Quick check or full decode

- A quick check examines file structure, duration, and audio/video stream metadata.
- Full decode reads the entire primary video stream for stronger corruption detection.
- Results distinguish **Quick check passed** from **Full check passed** instead of overstating what was verified.

## Temporary by design

- Preflight results do not enter the library cache, scan history, or persistent review states.
- The preflight window supports cancellation, plain-language details, and CSV export.
- MediaCheck remains read-only and never copies, moves, renames, repairs, or deletes media.

## Other refinements

- The selected preflight mode is locked while a check is running so progress and verdicts cannot become misleading.
- The preflight window now fits above the Windows taskbar on shorter displays, and its details section has its own scrollbar.
- Expanded automated coverage to 85 passing tests.

## Known beta limitations

- The installer is not digitally signed and may trigger Windows SmartScreen.
- FFprobe and FFmpeg must be installed or downloaded separately.
- MediaCheck does not repair, move, rename, or delete media files.

## Installer checksum

`MediaCheck-Setup.exe`

SHA-256:

`736BBDD501287337F25A6728ED62C91AB29A836E1327B55B272F9C74D5F1F2D8`
