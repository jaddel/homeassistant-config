# JaDDeL's Home Assistant Configuration

## Automaitons
### ToDo's
- Per room precense detection --> Auto Lights off. 
- Global input boolean per room as motion light blocking entity.
- Global input boolean per room on/off all automations.
- Global input boolean per room on/off adaptive light.
- Input boolean full guest mode.
    - Night mode off?
    - Different brightness settings for adaptive lightning.
    - Hall motion off.
    - Shade automation off.
    - Kitchen motion off.
- Input boolean supervised guest mode.
    - Guest bathroom moderate night mode.
    - Hall moderate night mode.
- Input boolean someone sleeping in the living room.
    - Hall motion off.
    - Kitchen motion off.
    - Moderate night mode living room.
    - Shade automation off.
- Input boolean someone sleeping in the office.
    - Shade automation off. 
    - Moderate adaptive brightness & color settings.
- Bathroom: Find a good solution to detect shower occupancy. 
    - Trend sensor -> Humiditiy / Temp 
- Vacuum wait at bin after 2. run. 
- Vacuum Siri / clean the kitschen 
- Creat washings per week counter. / track detergents consumption. 
### Needs clarification
- Adaptive lightning: possible to set variables for brightness settings?

### Bathroom
#### General
- Close bedroom shades when shower occupied.
#### Motion Light
- Motion Sensor
- Input number timeout
- Turn-off blocking entity
    - Shower occupancy
- Homekit manual turn-off blocking entity
    - Input number timeout
#### Shower Occupancy
- Humidity sensor --> binary sensor shower occupancy
- Add darin sensor to detect shower occupancy.

### Bedroom

#### Light
- Wall switch: add interal light group & add all lights off if any light on.



