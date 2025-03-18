Script extracts EXIF datetime from media files and sets correct ctime according to EXIF.

```bash
Use: exif2ctime directory-to-scan [options]
 -n <mask> find files by given mask
 -v        verbose output
 -w        write EXIF datetime to file ctime
```

Or use: `run directory-to-scan` - to execute gui. \
Сan be used as script for `nemo` file manager.

System dependencies:
- `dcraw` (for jpg|crw|cr2|nef|dng)
- `mediainfo` (for mov|avi|mp4|ts|mkv|3gp)
- `zenity` (for gui dialogue)
- `xterm` (for gui output)
