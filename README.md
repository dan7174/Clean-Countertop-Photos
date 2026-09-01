# Clean Countertop Photos

A reusable Codex skill for turning countertop-installation jobsite photos into clean, finished project-showcase images with minimal, photorealistic editing.

## What it does

- Removes only people, pets, tools, drop cloths, boxes, debris, and obvious temporary clutter.
- Preserves the real stone, cabinets, sink, room layout, permanent details, and natural phone-photo character.
- Makes only subtle camera, perspective, exposure, and white-balance corrections.
- Adds genuinely missing faucets or appliances only when their intended location is clearly visible and empty.
- Reuses the same fixture and appliance designs across every photo in one project.
- Produces one 16:9 landscape result per source photo and avoids automatic retries to conserve image-generation credits.

## Install

Use the skill folder at:

https://github.com/dan7174/Clean-Countertop-Photos/tree/main/clean-countertop-photo

In Codex, ask the skill installer to install the skill from that URL. You can also download or clone this repository and copy the `clean-countertop-photo` folder into your skills directory.

## Use

Attach all photos from one countertop project in the same conversation, then say:

```text
Use $clean-countertop-photo to clean these project photos. Preserve the real installation and keep all faucet and appliance designs consistent across the full set.
```

The skill reviews the entire photo set first, establishes shared fixture references, and then performs one minimal edit per source image.

## Repository structure

```text
clean-countertop-photo/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── assets/
    └── icon.svg
```
