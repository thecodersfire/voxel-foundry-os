# Built-in features for voxel-foundry-os

Purpose: 3D modeling, parametric CAD, and 3D-print design

1. **prepare racing and game notes** — run voxel-foundry-os-workspace. It creates ~/Documents/voxel-foundry-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run voxel-foundry-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/voxel-foundry-os-session-plans/.
3. **check game and controller readiness** — run voxel-foundry-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/voxel-foundry-os-workspace features/voxel-foundry-os-plan features/voxel-foundry-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for 3D modeling, parametric CAD, and 3D-print design:

1. **PrusaSlicer** — com.prusa3d.PrusaSlicer
2. **GIMP** — org.gimp.GIMP
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
