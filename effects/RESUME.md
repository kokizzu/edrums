# Resume this effects-comparison project

**Checkpoint date: 2026-10-14. Status: ready to resume; research is not complete.**

Repository: `kokizzu/edrums`, branch `main`, working directory `effects/`.

Read this file first, then [research-state.json](research-state.json), [methodology](METHODOLOGY.md), and [coverage](COVERAGE.md). Use the current repository files as the source of project state; do not depend on a previous chat or recreate the catalogue from memory.

## Latest user requirements — these take precedence

Research guitar, bass and vocal effects like the repository's electronic-drum comparison. Include dedicated/specialist effects as well as multi-effects; the current limited catalogue does not satisfy an exhaustive all-pedals scope. Organise by instrument/function, size and built-in expression versus external-expression support.

Every model must have fields for:

1. Built-in expression pedal, external expression support and toe switch.
2. Separate numbers of rotary controls, footswitches and push-buttons.
3. **Used and new prices displayed in IDR**, with sources, condition/market and dates.
4. Maximum simultaneous effect blocks, available categories and choices per category.
5. Input/output ports, including headphones and relevant microphone/control connections.
6. Factory presets, editable user storage and total storage without double-counting.
7. Synth and electric-to-acoustic simulation; distinguish these from acoustic amp/body-IR models.
8. Width × depth × height and weight, with pedal-travel/plug clearance notes.
9. Battery, voltage/polarity/current and explicit USB-powered operation versus charging/data.
10. IR and NAM loading, architecture restrictions, conversion workflows and proprietary captures.
11. Configuration/editor platforms, separated from drivers, firmware updaters and USB audio.
12. **Screen size**, normally manufacturer-specified diagonal inches; record multiple screens individually.
13. **Monochrome or color display**, separately from technology such as OLED/LCD/TFT.
14. **Touchscreen: yes/no/unverified**, with a source; do not infer it from a color screen.

Useful extra fields already covered in parts of the catalogue include looper, rhythms, USB audio/reamp, MIDI, parallel routing, scenes, bypass/trails, DI/phantom power, special pickup/cable requirements and firmware conflicts. Retain them.

## What is saved

**51 distinct partial model records across 8 comparison pages**, plus their manufacturer/manual/price references. The pre-checkpoint research commit is `cb8f25d34af28a159b6fbf6c472db95d064942ca`. Later checkpoint commits add navigation and these instructions; this SHA is a recovery reference, not an instruction to reset the branch.

| Page | Models |
|---|---:|
| [guitar-compact.md](guitar-compact.md) | 8 |
| [guitar-boss.md](guitar-boss.md) | 7 |
| [guitar-nux.md](guitar-nux.md) | 6 |
| [guitar-floorboards.md](guitar-floorboards.md) | 3 |
| [bass.md](bass.md) | 7 |
| [vocal.md](vocal.md) | 8 |
| [specialist.md](specialist.md) | 6 |
| [advanced-modelers.md](advanced-modelers.md) | 6 |

**No record is certified fully verified.** Existing sources and values must be preserved, but previously labelled verified facts are not immune to correction when a source conflict is found. Cross-referenced models are not extra records.

## Exact interruption state

The user added screen size, monochrome/color, touchscreen and IDR-only comparison prices, then requested an easily resumable checkpoint. Those requirements and the data template are now saved.

**The existing eight comparison pages still contain legacy USD price columns, and they do not yet have a complete display comparison for every model. Neither migration has been completed.** Do not report that all prices were converted or all screens were researched merely because this checkpoint exists. Preserve foreign-currency evidence in provenance when migrating; do not relabel a USD number as rupiah.

The comparison README was not present when this checkpoint work began; the new README supplies the missing navigation. The original root electronic-drum README is to remain intact.

## Next batch — start here

Start with the **8 existing records in `guitar-compact.md`**: Valeton GP-100, GP-150, Sonicake Matribox, Valeton GP-5, GP-50, GP-180, Sonicake Smart Box and Pocket Master.

For this batch:

- Read the current complete page and its references before editing. Check official product pages/manuals for display count, diagonal, monochrome/color and touch capability. Unknown is `?`, not No; an LED indicator is not a graphical display. Do not estimate inches from a photograph.
- Add a display table or explicit hardware columns for all eight models. Record `No display / N/A / No` only when established by documentation or a complete hardware inspection; record segmented numeric readouts separately from graphical displays.
- Replace the **comparison price columns** with used-IDR and new-IDR columns. Prefer verifiable Indonesian seller observations. Where only a foreign offer is available, a conversion must be labelled `FX estimate`, retain the original offer and use a sourced, dated exchange rate. If neither local evidence nor a verified conversion is available, use `?`, not an invented amount.
- Do not silently include tax, shipping or duties; identify included accessories and whether the used listing is an active asking price or older indexed evidence.
- Keep all other processing, power, software, source and conflict notes intact. Update the page's check date only for the fields actually checked; preserve older observation dates.
- Commit the completed batch, then update the page's statuses and next-model cursor in `research-state.json` and this file. Record unresolved fields even when moving to the next batch.

Continue the same migration in this order: `guitar-boss.md`, `guitar-nux.md`, `guitar-floorboards.md`, `bass.md`, `vocal.md`, `specialist.md`, `advanced-modelers.md`. Then expand the backlog, prioritising M-VAVE/CUVAVE, Mooer, Hotone and TC-Helicon plus the remaining mainstream modeler families. This ordering is a work queue, not a recommendation ranking.

## Guardrails for continuing

Use current GitHub file reads and current blob SHAs before writes. Do not overwrite unrelated work or reset commits. Keep commits small enough to resume after each batch. Update model counts only when a distinct hardware/model record is actually added; firmware updates are not automatically new hardware.

The **compact** filter is width ≤200 mm **and** depth ≤140 mm, without rotating the unit. **Medium** is ≤300×200 mm but not compact; **large** is otherwise; **unknown** when either dimension is not verified. Cable and pedal clearance are additional.

Use the source rules in METHODOLOGY.md. Important unresolved conflicts include TONEX ONE memory counts, MG-50Li factory/user and model counts, Matribox II Pro MIDI output, and GP-100 rhythm counts. A model having an official page does not complete all its fields. The old catalogue's technical statements may need firmware-specific rechecking.

No background worker or recurring automation is configured. This file is a durable checkpoint, not a promise of unattended research.

## Copyable continuation request

> Continue the guitar, bass and vocal effects comparison in kokizzu/edrums. Read effects/RESUME.md and effects/research-state.json first. Resume the saved next batch without restarting the catalogue. Include screen size, monochrome/color and touchscreen fields; display used/new prices in IDR. Verify sources, preserve existing research, commit each batch and update the checkpoint.
