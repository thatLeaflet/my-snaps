## LocalSend

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/localsend)

Maintained in the LocalSend Github [here](https://github.com/localsend/snap).

## Fastfetch

Maintained by me [here](https://github.com/thatLeaflet/fastfetch-snap).

It's working well, but
* it's not in the Snap Store, so no automatic upgrades
* it's a classic snap, so it's not sandboxed

## Prism Launcher

Maintained by me [here](https://github.com/thatLeaflet/prismlauncher-snap).

It's working well, but
* stores files in a weird location (directly in ~/snap/prismlauncher/common rather than a subdirectory like ~/snap/prismlauncher/common/.local/share/prismlauncher). Maybe a future update will look in new place, breaking things?
* Somehow knows the directory where I built the snap

## Librewolf

Maintained by me [here](https://github.com/thatLeaflet/librewolf-snap).

It's working well, but
* this is a security critical app, but I may not update it in a timely manner and may have security issues as I'm neither a browser or snap expert
  * but in theory has better sandboxing than flatpak version
* has a limited set of permissions (but still home directory access for Downloads folder access, can be disabled through snap command)

## Dconf Editor

Maintained by me [here](https://github.com/thatLeaflet/dconf-editor-snap).

It's working well, but
* it's not in the Snap Store, so no automatic upgrades
* built from 24.04 dconf-editor, so may not be upgraded to newer versions

## Pika Backup

Maintained by me [here](https://github.com/thatLeaflet/pika-backup-snap).

Not working. The app launches, but borgbackup is not working.
