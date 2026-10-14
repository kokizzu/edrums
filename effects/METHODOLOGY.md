# Comparison methodology

[Comparison home](README.md) · [Resume checkpoint](RESUME.md) · [Progress ledger](research-state.json)

Research snapshot and requirements update: **2026-10-14**. This is a growing, source-backed catalogue, not a claim to list every pedal ever manufactured. Hardware revisions and materially different models get separate records. Manufacturer product pages, manuals, effect lists and firmware notes take precedence over reseller specifications. Prices require seller/market sources and are not hardware specifications.

**Latest requirements:** add screen size, monochrome/color and touchscreen fields; display comparison prices in **IDR**. The existing pages have not yet completed this migration. The checkpoint records exactly what remains pending; the new rules below supersede the earlier USD-display convention.

## Reading the data

- **? / unverified** = not established from the cited evidence. It does **not** mean no. Machine-readable unknowns are `null`, not zero or false.
- **No** = an explicitly established absence or a complete, relevant manufacturer specification/manual that excludes the feature.
- **N/A** = the field does not apply, such as preset memory on a conventional analogue overdrive or diagonal screen size on a device without a screen.
- **Partial** = at least one requested field still needs verification. Finding a product page does not complete a record.
- Manufacturer effect totals retain advertised qualifiers such as `+` and `up to`. They are not sound-quality rankings and are not necessarily comparable across brands.

## Categories and size

Primary categories are guitar/multi-instrument processors, bass-focused processors, vocal/acoustic-vocal processors, and dedicated/specialist effects. Cross-references are not duplicate model records. Do not infer that every guitar effect preserves bass low frequencies.

Separate **built-in expression pedal**, **external expression only**, and **neither/unverified**. An expression socket is not an included pedal. Controller-only devices are separate from audio-effects processors.

Dimensions are **millimetres**, normally manufacturer-labelled **width × depth × height**. Keep notes for length/depth naming differences, omitted pedal travel, and conflicting sources. Never use packaging dimensions as unit dimensions. Weight must identify battery inclusion where known.

The **200 × 140 mm** compact filter is `width <= 200 AND depth <= 140`, without rotating the device. Medium is <=300×200 but not compact; large is otherwise; unknown means width or depth is unverified. Footprint does not include plugs, strain relief, adapters or the expression-pedal sweep.

## Controls and live usability

Count rotary controls, footswitches and non-foot buttons separately. A push-encoder counts once as a rotary control, not again as a button. Describe concentric independently adjustable shafts explicitly. Expression toe switches, power switches and mode toggles are separate when verified. Touchscreen widgets are not physical buttons. Palm-operated buttons are not stage-safe footswitches.

Useful additional fields include switch modes, bypass/pass-through, documented preset-change gaps or spillover, tuner mute, looper duration/placement, drum patterns, parallel routing, dry blend and scenes/snapshots. Do not invent latency measurements or subjective quality scores.

## Displays — required for every model

Record **screen presence, screen size, monochrome/color, and touchscreen support** separately. Size normally means the manufacturer's diagonal in inches; keep resolution and technology such as LCD, TFT or OLED in separate optional fields. Never assume OLED means color or color means touchscreen.

If there are multiple displays, distinguish the main screen from auxiliary screens/scribble strips and record their individual dimensions when available. Segmented numeric displays and indicator LEDs must not be silently described as graphical screens. A backlight or colored status LEDs do not establish a color graphical display.

Use explicit documentation or a complete hardware inspection for screen presence and touch status. **Do not estimate diagonal size from a photograph, housing dimensions, a reseller image scale, or a related model.** If a source only establishes a color screen, leave size and touch unknown until independently supported. Record the source and check date for each established field.

For a verified screenless device, screen size is N/A and touchscreen is No/not applicable as clearly labelled. For an unverified device, leave these fields unknown. The new fields must be backfilled into existing records, not just appended to future ones.

## Effects and memory

Keep **maximum simultaneous processing blocks**, **available categories**, **choices per category**, and **overall advertised model count** separate. Fixed amp/cab/utility blocks are not necessarily freely assignable slots. Retain DSP-limit qualifiers. Amp, cabinet, IR and capture counts are separate from effect counts where the source permits.

For presets, distinguish total addressable slots, factory-filled slots, dedicated user slots and overwriteable memory. `100 total / 55 factory-filled` does not mean 155 presets. Unused locations are not necessarily the only editable locations; library downloads are not onboard storage.

Distinguish electric-to-acoustic simulation, acoustic amp models, acoustic-body IRs, actual synthesizers, monophonic synth-like effects, harmony, pitch correction and vocoders. Disclose required divided pickups and special cables.

## Connections, power and software

List connector types/sizes and counts where verified. Distinguish stereo pairs, single TRS stereo jacks and balanced mono TRS. Track headphone output separately, including shared main-output arrangements. A microphone connector does not prove phantom power; record phantom voltage explicitly. Include harmony-detection inputs, FX loops, MIDI DIN/TRS/USB/Bluetooth, USB-audio channel counts and S/PDIF where established.

USB connectivity does **not** establish USB power, recording, MIDI or editing. Power notes distinguish voltage, polarity, device current draw versus adapter rating, battery type/capacity, charging, and documented USB bus/PD operation. Manufacturer battery runtime is not an independent measurement.

Separate **full editor**, **preset/file manager**, **firmware updater**, **audio driver**, and **mobile audio compatibility**. List Windows/macOS/iOS/Android only for the documented function. Do not infer Linux support from USB class compliance. Note optional Bluetooth adapters, paid apps/accounts and discontinued software where verified.

## IR, NAM and other captures

Keep separate fields for third-party IR loading, native `.nam` loading and architecture restrictions, NAM conversion/optimisation into another format, and proprietary captures/profiles. Include capacities and sample limits when established.

A proprietary capture feature does **not** prove NAM support. An IR loader is not an amp-capture loader. Factory cabinets do not prove third-party IR import. USB updates alone establish none of these. Current firmware can change capabilities; do not carry a limitation from an old manual into a new firmware without checking.

## Price policy — IDR comparison columns

**All comparison price columns must use Indonesian rupiah (IDR), with used and new prices separate.** Prefer verified Indonesian-market listings. Use clear formats such as `Rp1.400.000` or `Rp1.400.000–Rp1.800.000`; label approximate or converted figures. The amounts in that formatting example are illustrative, not a product quote.

Each offer must retain seller, market, condition, date, stock status, source and included accessories. Retain the original currency/amount in provenance when it is not IDR; it is not the display currency. A foreign offer converted to rupiah must be explicitly labelled **FX estimate**, with the original offer, a **verified exchange rate, rate date and rate source**. It is not an Indonesian retail or delivered-price observation. Do not assume an exchange rate or fabricate a local price. If neither local pricing nor a verifiable conversion is available, show `?`.

A single quote is not a market range; a used asking price is not a completed sale. Tax, shipping, import duties, warranty region and accessories may differ. Mark out-of-stock, discontinued and indexed older listings. Do not estimate used prices as an arbitrary percentage of new. Do not mix local and converted observations into one unlabeled range.

**Migration status:** legacy USD price columns remain in the existing comparison pages at this checkpoint. Replace them batch by batch while preserving original price evidence and its observation date. Do not simply change a currency header or erase provenance. Do not claim IDR migration is complete until all eight pages have been checked.

## Coverage, verification and resuming

The catalogue currently prioritises multi-effects, bass and vocal processors, followed by specialist effects. The backlog explicitly records unresearched families; placeholders do not count as completed comparisons. Verify firmware-dependent capabilities and dated prices before purchasing.

Use [RESUME.md](RESUME.md) and [research-state.json](research-state.json) as the continuation entry point. The Markdown comparison pages remain the source of technical data; the JSON file tracks page/model progress and the field template. Read current GitHub contents and SHAs before editing, preserve unrelated work, commit a small completed batch, update the cursor and unresolved fields, and verify the saved files. Do not reset to an earlier checkpoint commit.

Keep observation dates per field/source rather than refreshing all dates when only one field was checked. Record conflicts, do not hide them to fill the table. No unattended or recurring research is configured.
