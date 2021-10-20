# memobird-homeassistant
A Home-Assistant component for Memobird

# Installation

## HACS - Recommended
- Have [HACS](https://hacs.xyz) installed, this will allow you to easily update.
- Add `https://github.com/Rohja/homeassistant-memobird` as a [custom repository](https://hacs.xyz/docs/navigation/repository) with Type: Integration
- Click Install under "memobird-homeassistant" integration.
- Restart Home-Assistant.

## Manual
- Copy directory `custom_components/memobird` to your `<config dir>/custom_components` directory.
- Configure.
- Restart Home-Assistant.

## Configuration

Add the following line to your `configuration.yaml` file

```
notify:
  - name: MyMemobirdPrinterName
    platform: memobird
    api_key: MyAccessKey
    device_id: MyDeviceID
```

device_id - Double push the printer's button
api_key - Ask official support by email memobird@intretech.com
```
Memobird Device ID: ***
Email address: ***
Description and domain
```
