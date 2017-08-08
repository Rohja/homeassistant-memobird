# memobird-homeassistant
A Home-Assistant component for Memobird

## Installation

Copy `memobird.py` in your `custom_components` directory of your Home Assistant setup (usualy `/home/homeassistant/.homeassistant/custom_components/notify`

## Configuration

Add the following line to your `configuration.yaml` file

```
notify:
  - name: MyMemobirdPrinterName
    platform: memobird
    api_key: MyAccessKey
    device_id: MyDeviceID
```