# Street lamps JOSM style

Improves the visibility of street lamps.

Highlights `highway=street_lamp` objects using different colors depending on the lamp type (LED or electric). Inspired by the [OSMStreetLight project](https://github.com/sb12/OSMStreetLight). Based on and recommended for use with the [LitObjects](https://josm.openstreetmap.de/wiki/Styles/LitObjects) style.

## Features
- Adds a glowing circle around each lamp node
- Uses different colors depending on `lamp_type` (LED / non-LED)
- Supports `light:count` and `light:direction` tags – renders multiple (up to 8) light points for a single lamp. If `light:direction` is missing, it falls back to default angles.

## Settings
Open JOSM's Advanced Settings and type "street_lamps". You can modify the following attributes:
- `base_circle_glow_size`
- `base_circle_glow_opacity` (0.0-1.0)
- `light_point_icon_size`
- `light_point_icon_opacity` (0.0-1.0)
- `light_point_icon_radius`

## Credits
Icons were adapted from the [OSMStreetLight project](https://github.com/sb12/OSMStreetLight).
