# Supported devices

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design, except Star Feather)

### Careful with
- generic 1-gang modules - might not support OTA conversion
- BSEED switches - too many variants (can't know which you'll receive)

### Legend

| Symbol | Meaning  |                    |                     |                |                |           |          |
| :----: | -------- | ------------------ | ------------------- | -------------- | -------------- | --------- | -------- |
|   🚧️   | Status   | 🟩️ Fully supported | 🟨️ Mostly supported | 🟧️ In progress | 🟥️ Unsupported |           |          |
|   📦️   | Build    | ✔️ Available       | ❌️ Unavailable      |                |                |           |          |
|   💡️   | Category | 🇲️ Module          | 🇸️ Switch           | 🇴️ Outlet      | 🇵 Plug        | 🇷️ Remote | 🇧️ Board | 
|   ⚡️   | Power    | 🔌️ Mains           | 🔋️ Battery          | 🔱️ USB         |                |           |          |
|   📲️   | Install  | 🛜️ Wireless        | ➿️ By wire          | ❓️ Unknown     |                |           |          |
|   🏭️   | MCU      | `TL` Telink        | `SL` Silicon Labs   | `NXP` NXP      |                |           |          |
|   🅰   | Variant  | 🅰                  | 🅱                  | 🅲             | 🅳              | 🅴        | 🅵        |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡️ | 📲 |  🏭  | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | :--: | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_liygxtcq` <br> `TS0004` | [Tuya 4-gang](https://www.zigbee2mqtt.io/devices/SB04-Zigbee.html) |   | [`#398`](https://github.com/romasku/tuya-zigbee-switch/issues/398) | Supported | 
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_pf7swkqp` <br> `TS0003` | [Tuya 3-gang](https://www.zigbee2mqtt.io/devices/SB03-Zigbee.html) |   | [`#398`](https://github.com/romasku/tuya-zigbee-switch/issues/398) | Supported | 
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_zbfya6h0` <br> `TS0002` | [Tuya 2-gang](https://www.zigbee2mqtt.io/devices/SB02-Zigbee.html) |   | [`#398`](https://github.com/romasku/tuya-zigbee-switch/issues/398) | Supported | 
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_khmapq4n` <br> `TS0001` | [Tuya 1-gang](https://www.zigbee2mqtt.io/devices/SB01-Zigbee.html) |   | [`#398`](https://github.com/romasku/tuya-zigbee-switch/issues/398) | Supported | 

Data from [`device_db.yaml`](/device_db.yaml)
