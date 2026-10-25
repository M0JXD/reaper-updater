# REAPER Updater

Script to easily update REAPER on Linux.
Forked from @inyourfoss/reaper-updater to add support for all the architectures and creating a starter script for CLI usage.

> [!TIP]
> I personally add this to Linux Mint's "Startup Applications" so REAPER is always up to date. Maybe one day we'll be lucky enough to have a PPA or Debian repo.

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
