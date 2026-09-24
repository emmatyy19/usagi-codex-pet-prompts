# Usagi Codex Pet Prompts

This repository documents the text prompts and reference links used in a private, unofficial Codex desktop-pet project inspired by Usagi from *Chiikawa*.

## What is public

- `prompts/` contains the generation prompts, repair prompts, and directional-look instructions.
- `references.md` records the external pages used as visual references. Image files are not copied here.
- `NOTICE.md` explains the personal-use and rights status.
- `PUBLICATION.md` is the checklist used to keep private artwork and build files out of Git.

## What is deliberately private

This repository does **not** contain reference images, generated images, animation frames, spritesheets, Codex pet packages, QA contact sheets, screenshots, or installable downloads. Those files remain on the repository owner's machine and are excluded by `.gitignore`.

The prompts are shared as process documentation. They do not grant permission to use Usagi, *Chiikawa*, any linked reference image, or generated derivative artwork. A link is attribution and context; it is not a license. This project is unofficial, unlicensed, personal, and non-commercial.

## Prompt layout

```text
prompts/
  base-pet.md              Main character prompt
  rows/                    Initial animation prompts
  row-retries/             Later corrections and refinements
  look-cardinals.md        Cardinal-direction prompt
  look-anchor-repairs/     Direction-specific repair prompts
  look-mechanics.md        Directional movement rules
```

The private working copy uses the [Hatch Pet Codex skill](https://github.com/openai/codex) to turn these prompts into an 8 × 11 Codex v2 atlas. Anyone adapting the prompts should use an original character or artwork they are authorized to reproduce and distribute.

## Reference status

The supplied discovery links are recorded in [references.md](references.md), along with the visible page/account attribution and current permission status. Several are platform reposts, social posts, or marketplace listings rather than verified rights-holder sources. Original publication links and explicit reuse terms should be added when they can be identified.

No license file is included because the repository owner is not granting rights to the underlying character or linked artwork.
