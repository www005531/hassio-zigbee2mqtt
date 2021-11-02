FORKED
## Changes
- Added `common/local_build.sh` script
- Removed some obsolete startup debug messages
- Removed duplicate `icon` and `logo`
- Added new pipelines in `pipeline/` with proper names
- Pipelines now reuse a common template to reduce code duplication
- Pipelines now auto-generate `arch` specific jobs based on supported arch in `config.json`
- Restricted Edge pipeline triggers to files in `/common`
- Pipeline triggers migrated to `dev` branch
- Fixed `Docker Pulls` to point to correct location and use markdown code
- Pipelines are now running from [zigbee2mqtt azure org](https://dev.azure.com/zigbee2mqtt/Zigbee2mqtt%20Add-on/_build)
- Tracks latest Zigbee2mqtt [`dev branch`](https://github.com/Koenkk/zigbee2mqtt/commits/dev)