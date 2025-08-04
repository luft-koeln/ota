# Over-the-Air-Update

With the help of GitHub Pages, this project provides the file `firmware_info.json`, which contains the latest sensor firmware version, a SHA256 checksum, and the link to the `firmware.bin` file.
The JSON file is fetched by the OTA Manager of the Luft Köln sensor to check for new firmware updates.

The `gh-pages` branch is updated by a GitHub Action from the firmware repository.

## Update URL

The update information file is available at https://luft-koeln.github.io/ota/firmware_info.json.