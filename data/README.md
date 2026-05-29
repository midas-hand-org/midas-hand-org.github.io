# MIDAS Hand Asset Slots

This directory is reserved for the final project assets. Suggested structure:

- `paper.pdf`
- `midas_hand_teaser.mp4`
- `midas_hand_render.png`
- `demos/teleoperation.mp4`
- `demos/policy_rollout.mp4`
- `demos/hardware_capabilities.mp4`
- `demos/assembly_preview.mp4`
- `cad/Right_Hand_Assembly.glb` (viewer only)
- `cad/midas_hand.step`
- `cad/bambu_lab_3mf.zip` (downloaded as `MIDAS_ready_to_print_bambu.zip`)
- `cad/bambu_lab_plate_*.3mf`
- `cad/midas_hand_urdf.urdf`
- `bom/midas_hand_bom.csv`
- `assembly/assembly_guide.pdf`
- `assembly/calibration_checklist.pdf`
- `assembly/*.jpg`
- `software/` or links to the main software repository

Software repositories referenced by `software.html`:

- `https://github.com/midas-hand-org/midas_hand_api`
- `https://github.com/midas-hand-org/midas_hand_mujoco`
- `https://github.com/midas-hand-org/midas_hand_retargeter`
- `https://github.com/midas-hand-org/midas_hand_teleop`

The current site uses visual placeholders so these files are not required yet.

The Onshape workspace URL is configured in `cad.html` on the Onshape release block.

License layout used by the website:

- Hardware/CAD/BOM/assembly design materials: CERN-OHL-P-2.0
- Software repositories: MIT unless a repository states otherwise
- Website text, documentation prose, and non-build media: CC BY 4.0 unless otherwise noted

Each major release area has its own page:

- `parts.html`
- `cad.html`
- `assembly.html`
- `software.html`
- `downloads.html`
