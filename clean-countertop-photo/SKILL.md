---
name: clean-countertop-photo
description: Clean and finish photographs of installed countertops, kitchens, vanities, and similar stone projects with one minimal photorealistic edit per source photo. Use when a user supplies jobsite photos and asks to remove temporary clutter, subtly correct camera or lighting issues, add genuinely missing faucets or appliances, keep the same fixture designs consistent across every photo in a project, and return authentic 16:9 showcase images. Preserve the real installation. Do not use for general redesigns, virtual staging, decor additions, or style transformations.
---

# Clean Countertop Project Photos

Create one clean, finished project-showcase image per source photo without making the room look redesigned or AI-generated.

## Single-Pass Workflow

1. Inspect every supplied photo from the same project before editing. If an edit target is a local file, load it with the available image-viewing tool first.
2. Establish a project fixture reference before generating:
   - Treat any existing faucet, refrigerator, dishwasher, range or stove, and other permanent fixture visible in the project photos as the master reference for that item.
   - Record its finish, configuration, handle style, proportions, and other defining visual details.
   - Use the master photo as a supporting reference when adding that item to another photo.
   - If an item is absent from every project photo, choose one simple, brand-neutral design that matches the dominant existing finish and kitchen style. When no reliable finish cue exists, use brushed stainless steel. Lock that design and reuse it unchanged throughout the project.
3. Add a fixture or appliance only when its intended installed location or opening is clearly visible and genuinely empty. Do not add an item merely because it is outside the frame, hidden, or blocked.
4. Identify only obvious temporary jobsite clutter. If uncertain about an object, leave it unchanged.
5. Use the available image-generation tool once per source photo. Do not generate alternatives or automatically retry. If a result needs another attempt, wait for the user to request one.
6. Tailor only the visible removal list, genuinely missing items, master fixture references, and necessary camera corrections in the canonical prompt below. Keep every preservation rule.
7. Request one 16:9 horizontal landscape result per source photo at the highest available resolution, ideally 2560 x 1440 pixels. Preserve the original content without cropping; extend only the left and/or right edges when necessary. If exact resolution control is unavailable, accept the highest available 16:9 result rather than spending another generation.
8. Return only the finished image or images. Add no written explanation, alternate version, collage, or before-and-after layout.

## Canonical Edit Prompt

```text
Edit this exact countertop installation photo for a clean, finished project showcase with minimal, photorealistic editing.

Remove only people, pets, tools, drop cloths, boxes, construction debris, and obvious temporary jobsite clutter. If needed, correct the image rotation, excessive tilt, lens distortion, exposure, white balance, and perspective—but keep all adjustments subtle and natural.

Preserve the actual countertop exactly as photographed, including its stone color, pattern, veining, polish, edge profile, seams, dimensions, sink cutout, and reflections. Keep all existing cabinets, sinks, faucets, backsplashes, appliances, walls, windows, trim, outlets, flooring, room layout, plants, and permanent details unchanged.

If a faucet, refrigerator, dishwasher, range or stove, or other required permanent fixture is genuinely missing from a clearly visible intended location, add it. Use the exact same model, design, finish, configuration, handles, proportions, and visual details established by the project's master reference photo. If the item is missing from every project photo, use the one locked brand-neutral design selected for this project and repeat it unchanged in every photo. Never add an item simply because it is outside the frame, hidden, or blocked.

Do not redesign, modernize, stage, decorate, replace, add, or move anything except the genuinely missing fixtures or appliances described above. Do not change cabinet colors, sink dimensions, backsplash details, existing appliance placement, countertops, or stone veining. Do not make the kitchen look like an AI rendering. Preserve natural texture, small imperfections, and realistic phone-photo character. Do not add visible brand names or logos.

If uncertain whether an object is temporary jobsite clutter or whether a fixture is genuinely missing, leave it unchanged.

After cleanup, deliver one 16:9 horizontal landscape image at the highest available resolution, ideally 2560 x 1440 pixels. Preserve all original image content without cropping; naturally extend the left and/or right edges only as needed to create the 16:9 frame.

Return only one finished image for this source photo. Do not add text, logos, borders, captions, watermarks, collages, or before-and-after layouts.
```
