# Cook Videos Generator

A reusable agent Skill for turning an image reference plus a recipe or other step-by-step process into a ~30-second, cinematic, action-focused video prompt for **Seedance 2.5**.

## What it does

- Maps the original process into strict, non-repeating chronological states.
- Designs approximately 16–20 shots with varied scale, camera trajectories, pacing, and physically plausible spectacle.
- Keeps the reference person's identity and/or the finished object's appearance consistent.
- Specifies silent hero performance, action-synchronized sound, lighting, transitions, and a clear final payoff.
- Outputs one production-ready **English prompt**; it does not render the video.

## Installation

Copy `SKILL.md` into your agent's Skills directory, typically as `cook-videos-generator/SKILL.md`, and activate it in your agent or coding assistant according to that product's instructions.

## How to use

Provide (1) a reference image showing the person and/or finished product and (2) the actual recipe, manual, or step-by-step instructions (text, document, image, or accessible URL). Ask the agent to use `cook-videos-generator` to generate the cinematic Seedance 2.5 prompt.

## Attribution

Adapted into Skill format from the user's COOKCUT / Spectacle Kinetic Director instructions. The directing specification remains in `SKILL.md`.