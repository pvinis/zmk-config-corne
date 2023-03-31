# Pavlos' ZMK Config for Aurora Corne

### Flashing

- Download the latest firmware, by running:

```sh
hub api -H "Accept: application/vnd.github+json" /repos/pvinis/zmk-config-corne/actions/artifacts |jq ".artifacts[0].archive_download_url" | xargs hub api > firmware.zip
```

- Then just unzip.
- Connect each side of the keyboard using a cable.
- Double tap the reset button.
- Drop the correctly named firmware (left/right) to the new disc that appears to be mounted on the desktop.
