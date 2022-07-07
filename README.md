# Nextcloud auto updater

This script run an unattended update for installed nextcloud apps, the
nextcloud installation itself and runs database fixes.

## Usage

```
nextcloud-auto-update <NEXTCLOUD_DIRECTORY>
```

To run it periodically with *CRON*:

```
0 3 * * *	www-data    <PATH_TO_NEXTCLOUD_AUTO_UPDATE> <NEXTCLOUD_DIRECTORY>
```
