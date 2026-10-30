# Higgins Edge

Connects this Home Assistant to the Higgins control plane. It reads states and executes only allowlisted commands sent by the owner (today: lights on/off). Doors, alarm and energy settings are never controlled.

## Configuration

- `control_plane_url`: provided by chemicalmonkeys.
- `edge_token`: provided by chemicalmonkeys, unique to this property.
