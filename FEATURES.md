# Built-in features for lessonloom-os

Purpose: teaching and lesson planning

1. **prepare study and research files** — run lessonloom-os-workspace. It creates ~/Documents/lessonloom-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run lessonloom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/lessonloom-os-session-plans/.
3. **check study and source readiness** — run lessonloom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/lessonloom-os-workspace features/lessonloom-os-plan features/lessonloom-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for teaching and lesson planning:

1. **Zotero** — org.zotero.Zotero
2. **Anki** — net.ankiweb.Anki
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
