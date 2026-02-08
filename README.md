# TechTimeGuy Home Assistant Blueprints

A collection of reusable Home Assistant blueprints focused on
**WLED status indicators, 3D printer monitoring, and workshop automation**.

## Included Blueprints

### TTG – 3D Printer Status → WLED Status LEDs (v3)
- Drives WLED LEDs based on printer status
- Optional WLED speed & intensity control
- Configurable offline behavior
- Designed around Bambu printers, but works with any HA printer integration

## Installation

## TTG – 3D Printer Status → WLED Status LEDs (v3)

Controls a WLED light based on a 3D printer’s status sensor  
(Bambu, OctoPrint, Klipper, etc.).

### Install
1. In Home Assistant, go to **Settings → Automations & Scenes → Blueprints**
2. Click **Import Blueprint**
3. Paste this URL: https://raw.githubusercontent.com/TechTimeGuy/HomeAssistant_Blueprints/main/blueprints/automation/techtimeguy/ttg_printer_status_wled_v1.yaml
4. Click **Preview Blueprint**
5. Click **Import Blueprint**
6. Create a new automation using the blueprint

### Notes
- Status strings are compared in lowercase
- Optional WLED intensity & speed entities are supported
- Offline behavior is configurable (off or solid color)


