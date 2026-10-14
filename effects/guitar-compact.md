# Compact guitar / multi-instrument processors

[Home](README.md) · [Methodology](METHODOLOGY.md) · [Larger processors](guitar-floorboards.md) · [Bass](bass.md) · [Vocals](vocal.md)

Checked **2026-10-14**. All units below satisfy the **200 mm width × 140 mm depth** filter using published dimensions. Height, plug clearance and expression-pedal movement still matter. Pocket Master is a handheld/desktop processor, not a conventional foot-operated pedal.

**Status: partial records.** `?` means unverified, not no. `K / F / B` means rotary controls / main footswitches / separate push-buttons; expression toe switches are separate. `P / U` means factory / user memory, except where explicitly described as factory-filled total storage. Prices are dated **asking/listed prices**, not sold-price statistics; international USD and Indonesian IDR observations are not interchangeable.

## 1. Hardware, expression and price

### Built-in expression pedal

| Model | Built-in / external expression | K / F / B | Width × depth × height, mm | Weight | Used observation, USD | New observation |
|---|---|---|---|---|---|---|
| [Valeton GP-100][gp100] | Yes / ? | ? / 2 / ? | 198 × 134 × 28* | 800 g | $79.99, GC Good [P1] | $111, Thomann US-facing [P2]; Rp2,635,000, Nafiri [P3] |
| [Valeton GP-150][gp150] | Yes / EXP/FS | 5 / 2 / 6 [controls] | 200 × 139 × 55 | 958 g | ? | $169.99, official shop [P4] |
| [Sonicake Matribox, QME-50][matribox] | Yes / ? | 5 / 2 / 4 [photo] | 200 × 137.5 × 53.6 | 732 g | ? | $129.99, official product page |

### No built-in expression pedal

| Model | Built-in / external expression | K / F / B | Width × depth × height, mm | Weight | Used observation, USD | New observation, USD |
|---|---|---|---|---|---|---|
| [Valeton GP-5][gp5] | No / not established | ? / 1 / ? | 93.5 × 42 × 52* | 237 g | $58.99–63.99, GC Great–Excellent [P5] | $79.99, official shop [P6] |
| [Valeton GP-50][gp50] | No / EXP/FS | 4 / 2 / ? [photo] | 122 × 82 × 54 | 430 g | ? | $119.99, official shop [P7] |
| [Valeton GP-180][gp180] | No / 2 × EXP/FS, shared MIDI functions | 5 / 3 / 16 [controls] | 181 × 139 × 52 | 843 g | ? | $179.99, official shop [P8] |
| [Sonicake Smart Box, QME-20][smartbox] | No / EXP/FS | 1 / 2 / 13 [photo] | 135 × 114 × 51 | 378 g | ? | $94.99, official product page |
| [Sonicake Pocket Master, QME-10][pocket] | No / not established | 1 / 0 conventional / 2 palm buttons [photo] | 103.5 × 85 × 28.5 | 194 g | ? | $64.99, official product page |

*GP-100 height is the manufacturer's published 28 mm figure; do not assume it includes maximum expression-pedal travel. GP-5 dimensions retain the manufacturer's width/depth labels rather than silently rotating the unit. GP-150's 200 × 139 mm fit leaves essentially no spare depth under this filter; cable clearance is additional.*

## 2. Processing, memory, IR and NAM

| Model | Simultaneous blocks / categories and choices | Presets and user storage | Synth / acoustic functions | Third-party IR | NAM / captured models |
|---|---|---|---|---|---|
| GP-100 | 9; 140+ advertised effects/models; 45 guitar/bass/acoustic amps; 40 factory cabs; 50+ other effects | 99 P + 99 U = 198 | Acoustic **amp** models documented; electric-to-acoustic simulator and synth counts ? | 20 user slots | ?; IR capability alone does not establish NAM |
| GP-150 | 12 reorderable blocks; 200+ effects; per-category counts ? | 200 total, 100 factory-filled; factory mix 85 guitar / 10 bass / 5 acoustic | Acoustic presets documented, not proof of a specific simulator; synth ? | 20, 1024/2048 samples | **SnapTone conversion**, 100 model slots / 50 supplied; not labelled unrestricted native `.nam` |
| Matribox | 9 movable blocks; 130+ models; 40 amps, 38 factory cabs, 50+ other effects | 99 P + 99 U = 198 | Category-specific synth/acoustic choices ? | 15 user slots | **NAM A2 workflow** advertised by current official software/download section; see firmware note |
| GP-5 | Up to 9 simultaneous; 100+ effects; modules shown include NR, PRE, DST, N>S, AMP, CAB, EQ, MOD, DLY, RVB; not all necessarily concurrent | 50 P + 50 U = 100 | Exact synth/acoustic choices ? | 20 user slots | SnapTone converted NAM; 80 model slots / 50 supplied |
| GP-50 | 9 simultaneous; 100+ effects; category breakdown ? | 100 total / 55 factory-filled; 45 remaining slots | Exact synth/acoustic choices ? | 20 user slots | SnapTone converted NAM; 80 model slots / 50 supplied |
| GP-180 | 12 reorderable blocks; 200+ effects; category breakdown ? | 200 total / 100 factory-filled | Acoustic presets documented; specific simulator/synth ? | 20, 1024/2048 samples | SnapTone converted NAM; 100 slots / 50 supplied |
| Smart Box | 9: NR, FX1, DRV, AMP, IR, EQ, FX2, DLY, RVB; 130+ effects; individual counts ? | 100 total / 50 factory-filled | Exact synth/acoustic choices ? | 5 user slots | Third-party NAM advertised; native/converted architecture restrictions not established |
| Pocket Master | 9; 100+ effects, 20 amps; DRV/AMP/IR/EQ fixed, NR/FX1/FX2/DLY/RVB movable | 50 non-editable P + 50 editable U | Exact synth/acoustic choices ? | 5 user slots | NAM A2 support in current Manager/SONICLINK downloads; not assumed unrestricted native NAM |

## 3. Connections, power, apps and practical differences

Connector counts refer to physical sockets. A single TRS stereo output is not two independently balanced outputs.

| Model | Audio / control connections | Power and battery | Configuration software | Other relevant features |
|---|---|---|---|---|
| GP-100 | ¼″ TS input; 2 × ¼″ outputs; 3.5 mm aux; 3.5 mm headphones; USB-B | DC 9 V, 500 mA; USB-power/battery support not established | Windows/macOS editor | USB stereo recording; 90 s pre-effects looper; rhythm count conflicts between 99 and 100 in official copy |
| GP-150 | ¼″ input; **L TS unbalanced / R TRS balanced** outputs; 3.5 mm TRRS headset/mic; EXP/FS shared MIDI-in; USB-C | Rechargeable 3000 mAh/3.7 V; DC 9 V centre-negative and USB 5 V/PD charging; ≥1 A operating USB figure; see official charging/adapter requirements | Windows/macOS editor; iOS/Android via Bluetooth | USB 6-in/4-out; 180 s looper; 100+ rhythms; no FX-loop claim |
| Matribox | ¼″ input; L/R ¼″ outputs; 3.5 mm aux; 3.5 mm headphones; USB | DC 9 V; exact required current ?; USB power not established | Windows/macOS editor | USB audio; 90 s looper; 100 rhythms; current NAM update sequence matters |
| GP-5 | ¼″ input; one ¼″ TRS stereo output also serving headphones; USB-C | DC 9 V centre-negative/100 mA, or USB 5 V/190 mA; battery support not established | iOS/Android editing via Bluetooth; Windows/macOS file/firmware management, not assumed full editor | USB 2-in/2-out; analog/digital bypass; app-based rhythms |
| GP-50 | ¼″ input; 2 × ¼″ outputs; 3.5 mm phones; EXP/FS; 3.5 mm TRS MIDI IN/THRU; USB-C | 1450 mAh rechargeable; DC 9 V centre-negative/500 mA or USB 5 V/1 A; DC/USB charging | iOS/Android editing; Windows/macOS file/firmware management | USB 2-in/2-out/reamp; looper; 100 rhythms; analog/digital bypass |
| GP-180 | ¼″ input; L TS unbalanced / R TRS balanced outputs; TRRS headset/mic; 2 × EXP/FS shared MIDI IN and OUT/THRU; USB-C | 3000 mAh rechargeable; DC 9 V centre-negative, USB 5 V/PD; use official operation versus charging requirements | Windows/macOS editor; iOS/Android via Bluetooth | USB 6-in/4-out; 180 s looper; 100+ rhythms; analog/DSP bypass |
| Smart Box | ¼″ input; one ¼″ TRS stereo output; separate 3.5 mm headphones; EXP/FS; USB-C | 2000 mAh rechargeable; DC 9 V centre-negative >700 mA or USB 5 V >1 A | Windows/macOS; mobile app advertised, exact mobile platform verification pending | USB 2-in/2-out with loopback/reamp; 20 s looper; 100 rhythms |
| Pocket Master | ¼″ input; one ¼″ TRS stereo output/headphones; USB-C connections for audio/data and charging | Built-in 1000 mAh lithium battery; USB 5 V | Windows/macOS Manager; iOS/Android SONICLINK | USB stereo audio; 99 rhythms; **palm buttons are not counted as footswitches** |

### Firmware-sensitive notes

Sonicake's checked Matribox download section lists firmware **1.1.0** and desktop software **1.1.1** with NAM A2 support; its update instructions require the older software for the firmware-update step. Pocket Master's page lists firmware **1.3.3**, Manager **1.5.2**, and SONICLINK **1.7.2**. Follow each manufacturer's matching updater instructions. These statements describe the published workflow, not an independent compatibility test of every NAM architecture.

GP-150/180 documentation distinguishes operating, charging and fast-charging current. A USB socket or an under-rated phone charger should not be assumed sufficient for every operation. Manufacturer battery runtimes are not independent measurements.

## Sources and dated prices

Manufacturer links in every model heading support the technical rows; control-count supplements are below. Check date for all listed prices: **2026-10-14**. Stock, destination tax, shipping and import costs remain separate. `?` is intentionally retained where no reliable secondhand observation was established.

[gp5]: https://www.valeton.net/product/gp-5/
[gp50]: https://www.valeton.net/product/gp-50/
[gp100]: https://www.valeton.net/product/gp-100/
[gp150]: https://www.valeton.net/product/gp-150/
[gp180]: https://www.valeton.net/product/gp-180/
[matribox]: https://www.sonicake.com/products/matribox
[pocket]: https://www.sonicake.com/products/pocket-master
[smartbox]: https://www.sonicake.com/products/smart-box

- GP-150/180 physical controls: [manufacturer comparison image](https://res.valeton.net/Uploads/wp/2026/03/GP-150-GP180-Comparison-2.png). GP-180 button count includes six quick-access and ten module buttons.
- GP-50 controls: [manufacturer photo](https://res.valeton.net/Uploads/wp/2025/12/gp-50-20.png).
- Matribox controls: [manufacturer photo](https://www.sonicake.com/cdn/shop/products/QME-50.jpg?v=1678434988&width=1096); [official manual](https://cdn.shopify.com/s/files/1/0100/1950/4185/files/Matribox_Online_Manual_Firmware_V1.1.0.pdf?v=1763367433).
- Smart Box controls: [manufacturer photo](https://www.sonicake.com/cdn/shop/files/QME-20-1.jpg?v=1767506736&width=1440).
- Pocket Master controls: [manufacturer photo](https://www.sonicake.com/cdn/shop/files/QME-1001_dc1d58ce-6c19-4bbb-8bc2-1740e5f15f55.jpg?v=1733365197&width=1440).
- [P1: GP-100 used, Guitar Center item 122531515](https://www.guitarcenter.com/Valeton/Used-Valeton-GP-100-Effect-Processor-122531515.gc).
- [P2: GP-100 new, Thomann](https://www.thomannmusic.com/valeton_gp_100.htm). B-stock is separately listed at $102; it is not used-price evidence.
- [P3: GP-100 new, Nafiri Indonesia](https://nafiriguitar.com/products/valeton-gp-100-multi-effects-processor).
- [P4: GP-150 official shop](https://shop.valeton.net/products/gp-150).
- [P5: GP-5 used listings, Guitar Center](https://www.guitarcenter.com/Valeton/Multi-Effects-Pedals.gc). Two observed asks, not a statistically estimated market range.
- [P6: GP-5 official shop](https://shop.valeton.net/products/gp-5).
- [P7: GP-50 official shop](https://shop.valeton.net/products/gp-50).
- [P8: GP-180 official shop](https://shop.valeton.net/products/gp-180).

Other compact processors, including HX Stomp, GT-1000CORE, Ampero Mini and compact capture/specialist pedals, are indexed separately as their records are added. Absence from this page is not a claim that a model fails the size filter.
