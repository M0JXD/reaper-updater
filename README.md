# REAPER Updater

Script to easily update REAPER on Linux.
Forked from @inyourfoss/reaper-updater to add support for all the architectures and creating a starter script for CLI usage.

## Description

The script grabs and installs the latest REAPER version from <>https://reaper.fm/download.php>.
It can also be used for downloading only without installing.

## Usage

To find out how to use the script, please use the help option:
```
./reaper_updater.sh --help
```

## Dependencies

- libxml
- curl
- tar
- posix-compliant shell
- standard unix/gnu utils (sed, cut, tr)
- xdg-user-dirs
