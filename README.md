# Auto Stop Switch Blueprint

This Home Assistant blueprint automatically turns off a switch after a specified delay.

## How to Use

1. Copy the link to this repository or directly import the blueprint using the button below.
2. Configure the blueprint in Home Assistant by selecting the desired switch and delay.

## Import the Blueprint

Click the button below to import the blueprint directly into your Home Assistant instance:

[![Import Blueprint to Home Assistant](https://community-assets.home-assistant.io/original/4X/d/7/6/d7625545838a4970873f3a996172212440b7e0ae.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FLobwick%2FHomeAssistant%2Fmain%2Fblueprints%2Fauto_stop_switch.yaml)

## Blueprint Details

- **Name**: Auto Stop Switch
- **Description**: Automatically turns off a switch after it has been turned on for a specified period.
- **Inputs**:
  - `switch_entity`: The switch to control.
  - `wait_time`: Delay (in seconds) before the switch is turned off.