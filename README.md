# AFF Character Sheet

An Advanced Fighting Fantasy character sheet extension for Owlbear Rodeo.

## Features

This character sheet is specifically designed for Advanced Fighting Fantasy 2nd Edition and includes:

- **Characteristics Section**: Track SKILL, STAMINA, LUCK, and MAGIC with both Initial and Current values
- **Special Skills by Category**: Organized sections for Combat, Movement, Stealth, Knowledge, and Magical special skills
- **Talents Section**: Track your Hero's Major and Minor Talents
- **Drawbacks Section**: Record any Racial Drawbacks
- **Character Info**: Name, Race, Grade, and Experience tracking
- **Notes**: Free-form notes section for additional information

## How to use

- **Edit Values**: Click on values in the right column to edit them directly
- **Edit Mode**: Click the `EDIT` button to modify stat names, section titles, and add/remove entries
- **Characteristics**: Format as "Initial/Current" (e.g., "7/7" or "12/8")
- **Special Skills**: Enter the rank/points for each special skill
- **Export/Import**: `EXPORT` your character to JSON and `IMPORT` it back anytime
- **GM View**: GMs can view all player sheets via the tabs at the top
- **Theme**: Customize colors by clicking on the theme editor

## Building

```bash
npm install
npm run build
```

The built files will be in the `dist` directory, ready to be loaded as an Owlbear Rodeo extension.
