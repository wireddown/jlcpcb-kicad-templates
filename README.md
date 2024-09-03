# JLCPCB KiCad Templates

This repo contains KiCad templates for manufacturing PCBs with JLCPCB.

- KiCad 8.0
- [Design rules](https://docs.kicad.org/8.0/en/pcbnew/pcbnew.html#board_setup) for PCB Editor
  - JLCPCB [Manufacturing Capabilities](https://jlcpcb.com/capabilities/pcb-capabilities)
  - JLCPCB [Gerber and Drill files](https://jlcpcb.com/help/article/how-to-generate-gerber-and-drill-files-in-kicad-8)

## Template list

- [2-layer](./2-layer/)
  ```
  "rules": {
    "max_error": 0.005,
    "min_clearance": 0.1,
    "min_connection": 0.1,
    "min_copper_edge_clearance": 0.2,
    "min_hole_clearance": 0.3,
    "min_hole_to_hole": 0.45,
    "min_microvia_diameter": 0.2,
    "min_microvia_drill": 0.1,
    "min_resolved_spokes": 2,
    "min_silk_clearance": 0.15,
    "min_text_height": 1.0,
    "min_text_thickness": 0.153,
    "min_through_hole_diameter": 0.3,
    "min_track_width": 0.1,
    "min_via_annular_width": 0.25,
    "min_via_diameter": 0.5,
    "solder_mask_to_copper_clearance": 0.0,
    "use_height_for_length_calcs": true
  },
  ```

