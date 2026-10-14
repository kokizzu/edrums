# Guitar / multi-instrument floorboard index

[Home](README.md) · [Compact units](guitar-compact.md) · [BOSS](guitar-boss.md) · [NUX](guitar-nux.md) · [Advanced modelers/capture pedals](advanced-modelers.md) · [Bass](bass.md)

Checked **2026-10-14**. This page adds three larger processors; the linked brand pages contain the other researched floorboards. **Partial records**: `?` is unverified, not No. Dimensions are **width × depth × height, mm**. A built-in pedal does not establish an external-expression socket; both are recorded separately.

## Hardware and expression

All three have built-in expression and documented external expression/footswitch support. K/F/B = rotary controls / main footswitches / separate buttons; expression toe switches and power switches are separate.

| Model / primary source | K/F/B | W×D×H, mm; weight | Size class | Used USD | New USD observation |
|---|---|---|---|---|---|
| [Valeton GP-200][gp200] | ?/8/?; manufacturer gives 25 knobs/buttons combined, not the separate counts | 345×220×62.5; 2.37 kg | Large | ? | ? |
| [Sonicake Matribox II, QME-100][ii] | 5/3/? [manual panel] | 276×164×55.8; 1.54 kg | Medium | ? | $229.99, official shop |
| [Sonicake Matribox II Pro, QME-200][pro] | ?/6/? | ?; ? | Unverified | ? | $299.99, official shop |

New prices are individual official-store observations checked **2026-10-14**, not used-to-new market ranges or Indonesian delivered prices. Matribox II Pro dimensions are intentionally not copied from an unverified reseller listing.

## Processing and memory

| Model | Simultaneous processing; categories / choices | Preset storage | Synth / acoustic | Third-party IR | NAM |
|---|---|---|---|---|---|
| GP-200 | 11 freely movable modules; 240+ models, including 140+ guitar/bass/acoustic amp/cab models and 100+ other effects; per-category counts ? | 256 total: 100 factory +156 user | Acoustic amp/cab models documented; dedicated simulator and synth choices ? | 20 user slots | Not established |
| Matribox II | 10 movable modules; 63 amps, 61 cabs, 93+ pedal effects | 198 total /99 factory-filled | Acoustic-related models advertised; precise simulator/synth algorithms ? | 15 user slots | Current desktop workflow advertises **NAM A2**; architecture/conversion limits need matching release notes |
| Matribox II Pro | Exact simultaneous limit ?; 63 amps, 61 cabs, 93+ pedal effects; repeat effects of the same type supported | 240 total /120 factory-filled | Pitch-shift/Whammy-style use documented; synth/acoustic algorithms ? | 20 user slots | Current desktop workflow advertises **NAM A2**; not assumed arbitrary native `.nam` compatibility |

## Connections, power, applications and live use

| Model | Audio/control ports | Power / battery / USB-powered | Configuration apps | Other practical features |
|---|---|---|---|---|
| GP-200 | ¼″ TS input; 2×¼″ TS out +2×XLR balanced out; mono FX loop; 3.5 mm aux/phones; EXP/FS; DIN MIDI IN/OUT-THRU; USB-C | **9V/1000mA centre-negative**; battery/USB bus operation not established | Full editor **Windows/macOS**; mobile USB audio is not a mobile editor | USB 6-in/4-out; 180 s looper; 100 rhythms; switchable acoustic/electric/line input impedance |
| Matribox II | ¼″ TS input; 2×¼″ balanced TRS out; mono TS FX loop; 3.5 mm aux/phones; EXP/FS; 3.5 mm TRS MIDI IN/OUT; USB-C | **9V/1000mA centre-negative**; battery/USB bus operation not established | Full editor **Windows/macOS**; USB audio Windows/macOS/iOS/Android | 90 s looper; 100 rhythms; loopback/reamp; matching 1.3.0 firmware/editor at checking |
| Matribox II Pro | 2×XLR balanced out, FX loop, headphones, aux, external EXP/FS and USB documented; exact complete socket inventory ?; MIDI claim conflicts | **9V DC**, current/polarity ?; battery/USB bus operation not established | Full editor **Windows/macOS**; USB audio Windows/macOS/iOS/Android | 90 s looper; 100 rhythms; **single linear chain, no scenes, not compatible with Matribox II presets** |

**Matribox II Pro conflict:** the feature list says MIDI I/O, while the same official FAQ says MIDI output is not supported. Do not assume MIDI transmission works merely because a connector or generic feature bullet appears. Its listed firmware is 1.2.2 and NAM-capable software 1.3.1; follow the manufacturer's update sequence rather than assuming all versions interoperate.

## Sources

[gp200]: https://www.valeton.net/product/gp-200/
[ii]: https://www.sonicake.com/products/matribox-ii
[pro]: https://www.sonicake.com/products/matribox-ii-pro

- [Matribox II official manual, firmware 1.3.0](https://cdn.shopify.com/s/files/1/0100/1950/4185/files/Matribox_II_Online_Manual_EN_Firmware_V1.3.0.pdf?v=1780542623), panel diagrams and printed p.45 specifications, visually checked. A pair of balanced mono TRS outputs is not a single stereo TRS headphone socket.
- GP-200's published 25 combined controls are retained as a combined claim until separate rotary/button counts are verified; no arbitrary split has been invented.

For all researched processors organised by size and expression, start at the [comparison home](README.md). Unresearched families and unresolved fields are recorded in [coverage](COVERAGE.md).
