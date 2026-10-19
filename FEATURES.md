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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for 3D modeling, parametric CAD, and 3D-print design:

1. **FreeCAD** — design mechanical parts (org.freecadweb.FreeCAD)
2. **KiCad** — design circuits and PCBs (org.kicad.KiCad)
3. **Arduino IDE** — write and upload microcontroller sketches (cc.arduino.IDE2)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
7. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
8. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
9. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
10. **Godot Engine** (org.godotengine.Godot) — build and test 2D and 3D games.
11. **OBS Studio** (com.obsproject.Studio) — record or stream sessions.
12. **GNOME Clocks** (org.gnome.clocks) — time work sessions and events.
13. **GNOME Extensions** (org.gnome.Extensions) — manage GNOME desktop extensions.
14. **VSCodium** (com.vscodium.codium) — edit code and project files.
15. **GNOME Calendar** (org.gnome.Calendar) — schedule sessions, deadlines, and events.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
