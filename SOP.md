# Product Image Generation SOP

The standard for producing every Velano Living catalogue image. Written from a
full run of 520 cells and corrected wherever a control proved a check wrong.

**Live and retrievable:**
https://shanegardner405-arch.github.io/velano-living-catalogue-images/sop/

## Custody

| What | Where |
| --- | --- |
| Published document | **this repository**, `sop/index.html`, served by GitHub Pages |
| Rendered source | SilverShore repo, `clients/haussmann-inc/catalogue/SOP-image-generation.html` |
| Pipeline source | SilverShore repo, `clients/haussmann-inc/catalogue/` |
| Client registry pointer | SilverShore repo, `clients/haussmann-inc/IMAGE-GENERATION-SOP.md` |

This repository is the active one. The repo the client registry calls canonical,
`shanegardner405-arch/velano-haussmann-aios`, was ARCHIVED and made read-only on
2026-07-22 and cannot accept a pointer. Publishing here also avoids the paid-plan
requirement for Pages on a private repo, and this repository already serves all
42 images the document embeds. It was scanned before publication and
carries no spreadsheet id, no credentials, no local paths and no addresses.

## What it contains

Ten sections: source of truth, the reference set, how a reference becomes an
approved image, the five shots, the prompt templates, generation settings, the
checks and what each cannot do, publishing, standing rules, current state.

The **complete prompt text** for all five shots, 56,654 characters, generated
from the pipeline source rather than retyped. Each template opens with the
actual cells it produced and the measurement that passed them.

## The rules, condensed

- The environment belongs to the **column**, identical across every product.
  Every image 1 is the same studio, every image 3 the same couch and window.
- **Never tone-map a reference.** The finish comes from the photograph, never
  from a colour word.
- **Never attach column Q full frame.** It hands over its room. Crop to a
  surface patch at native resolution and never upscale it.
- **Run the control first.** A check that flags known-good cells is broken, not
  the cells.
- **Never publish a template that has not generated an image.**
- **Geometry is not verified by anything automated.** Four proportion metrics
  were built and all four were wrong at least once.

## State at publication, 2026-08-09

520 cells: 407 generated, 113 original Haussmann photographs that already
conform and should stay. 98 of 104 rows pass the full audit, 0 environment
defects across all 520. On warm woods the generated colour tracks the real
references at a median hue delta of 2.4, against the untouched Haussmann
originals at 2.2.
