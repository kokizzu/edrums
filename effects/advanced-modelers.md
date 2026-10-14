# Advanced modelers, capture pedals and effects-only processors

[Home](README.md) · [Methodology](METHODOLOGY.md) · [Guitar floorboards](guitar-floorboards.md) · [Compact alternatives](guitar-compact.md)

Checked **2026-10-14**. **Partial records**: `?` means unverified, not No. Native NAM, architecture-limited NAM, converted NAM, proprietary captures and cabinet IRs are different capabilities. An effects-only unit is not necessarily an amp modeler.

## Hardware, size and expression

K/F/B = rotary controls / footswitches / separate buttons. Push-encoders are counted once. Nano Cortex's rotary footswitches are explicitly called out rather than hidden in the knob count. Dimensions are **W×D×H, mm**. Prices are separate **USD** new and used observations; missing used prices have not been invented.

### No built-in expression pedal

| Model / primary source | External expression | K/F/B | W×D×H; weight | Size class | Used USD | New USD observation |
|---|---|---|---|---|---|---|
| [Line 6 HX Stomp][stomp] | Shared EXP1/2, FS4/5; two controllers with appropriate Y cable | 6/3/4 [panel] | Approx. **178×127×64**, 794 g, converted from official FAQ's rounded inches/pounds | Compact | ? | $555, Thomann [P1] |
| [Line 6 HX Effects][hxe] | **2**, shared with amp-control outputs | ?/8/?; six assignable stomp switches plus Mode and Tap | Approx. **274×201×71**, 2.15 kg, converted from official FAQ | Large by the 200 mm medium-depth limit | ? | ? |
| [Neural DSP Nano Cortex][nano] | **One shared EXP/MIDI input** | **7 knobs +2 rotary footswitch encoders /2 FS /5 buttons**; 2 analog switches additional | **144×103×62**, 620 g | Compact | ? | ? |
| [IK Multimedia TONEX ONE][one] | No dedicated EXP socket established | **4/1/1** [photo] | **48×94×53**, 160 g | Compact | ? | $199.99, official indexed listing [P2] |
| [IK Multimedia TONEX Pedal][tonex] | EXP or external single/dual switch | **7/3/0 front-panel** [photo] | **176×142×55**, 906 g | Medium; **2 mm too deep** for compact filter | ? | $429.99 official, tax excluded; $299 international seller [P1] |

### Built-in expression pedal

| Model / primary source | External expression | K/F/B | W×D×H; weight | Size class | Used USD | New USD |
|---|---|---|---|---|---|---|
| [HeadRush Flex Prime][flex] | Yes, separate TRS EXP | ?/3/? + expression toe switch | **295×150×70**, 1.57 kg | Medium | ? | ? |

The rounded Line 6 FAQ dimensions are not precision measurements. They establish the category but should not be used as a millimetre-perfect drilling template. Manufacturer FAQ launch prices are **not** presented as current offers.

## Processing, presets, IR and capture formats

| Model | Simultaneous processing / available choices | Preset storage | Synth / acoustic functions | Third-party IR | NAM / proprietary capture |
|---|---|---|---|---|---|
| HX Stomp | **8 blocks, DSP-limited**, since firmware 3.0; amp/cab/effects share the budget; current category counts not yet transcribed | **126 editable presets**; factory-filled subset ? | Individual synth/acoustic algorithms not yet verified | Yes; slot/sample limits pending | NAM not established; ordinary Helix amp models are not NAM captures |
| HX Effects | **9 blocks, DSP-limited**; no amp-model or factory cab-model blocks; current category counts pending | **128 editable presets**, **4 snapshots each** | Acoustic-body IR use documented; individual synth algorithms ? | Yes, including acoustic-body IRs | NAM not established |
| Nano Cortex | **5 FX slots + Neural Capture + IR**, plus input-gate functionality; **50+ effects/utilities** with NanOS 2; per-category counts pending | **64 presets**, four directly assigned hardware quick-access positions; **25 factory +256 user captures** are separate storage | Specific synth/acoustic algorithms ? | **256 user IRs**, 10 factory IRs; five hardware quick-access IR slots | **Proprietary Neural Capture**, including onboard capture; NAM compatibility not established |
| TONEX ONE | Tone Model playback plus gate, compressor, EQ and reverb; page mentions delay/modulation through software, but exact current onboard algorithm/slot limits need matching firmware documentation | **Official-page conflict: 30 in marketing, 20 in specifications**; do not silently pick one | Amp/cab/pedal captures are not a general synth engine; acoustic simulator ? | Dedicated third-party import workflow not yet verified here | **Proprietary TONEX Tone Models**; NAM compatibility not established |
| TONEX Pedal | Tone Model plus cabinet/VIR or custom IR and tone-shaping stages: gate, EQ, compressor, **2 delay choices, 5 modulation choices, 6 stereo reverbs**; exact freely assignable block limit N/A | **150 editable presets /50 banks**; current Reloaded factory content fills 150 | Specific synth/acoustic simulation ? | **Yes**, custom IR loader separate from Tone Models | **Proprietary TONEX Tone Models**; capture creation is a software workflow, not proof of onboard capture or NAM |
| Flex Prime | **14 DSP blocks**, 5 routing types; current page advertises 600+ amps/cabs/mics/effects, 100+ effects, 100+ amps, 80+ cabs and 360+ cab IRs | Older FAQ states **40 factory rigs**; current factory count and total user capacity ? | Guitar/bass processing; exact synth/acoustic algorithms ? | **Yes**, WAV/AIFF; two IRs can share a block | **Native NAM**, current firmware: A2 Full/Lite and supported legacy models; also proprietary HeadRush/ReValver clones and SuperClones |

### NAM and firmware corrections

**Flex Prime is not restricted to proprietary clones.** Its current manufacturer page explicitly documents **native NAM and TONE3000 access**. It specifies two A2 Full captures simultaneously, or four A2 Lite captures within two NAM blocks. The checked downloads include firmware **5.2**; architecture and DSP restrictions still apply. Its missing vocal input means Prime/Core presets do not automatically preserve vocal processing on Flex Prime.

**HX Stomp's old FAQ says six blocks**, but the official firmware-3.0 release notes increased the limit to **eight**. Similarly, HX Effects' launch FAQ predates full HX Edit support and later model additions. This comparison uses the release notes/current software listing rather than treating the old FAQ's launch-era software limitations and prices as current.

**TONEX ONE's 20-versus-30 preset disagreement** occurs on the same checked official page. It remains unresolved here; no unsupported firmware explanation is invented. TONEX ONE+, TONEX Pedal Bass Edition and other variants should not be substituted silently for the named hardware.

## Connections, power, software and live use

| Model | Audio/control ports | Power; battery/USB-powered? | Configuration apps and USB functions | Other important differences |
|---|---|---|---|---|
| HX Stomp | 2×¼″ in/out; balanced main outputs; stereo TRS send +2 returns; ¼″ headphones; shared EXP/FS; DIN MIDI IN/OUT-THRU; USB-B; DC | Manufacturer specifies **DC-3G supply**, special 2.5 mm pin; **no batteries**; USB-powered operation not established | **HX Edit Windows/macOS**; multichannel USB audio/reamp; iOS USB audio via appropriate adapter, not an iOS editor | Analog or DSP bypass/trails; flexible parallel routing; looper occupies a block |
| HX Effects | Stereo instrument/line routing; **2 mono FX loops or1 stereo**; 2 EXP/amp-control ports; MIDI/USB; exact complete connector inventory and headphone provision pending | Supplied **DC-3G**; FAQ requires at least **2 A clean DC**, 2.5 mm pin; USB/battery power not established | **HX Edit Windows/macOS**; **USB MIDI, not USB audio** | Effects-only; analog/DSP bypass; snapshots and parallel path; looper consumes one of nine blocks |
| Nano Cortex | ¼″ instrument in; XLR/¼″ combo capture in; 2×¼″ balanced out; 3.5 mm phones; shared ¼″ TRS EXP/MIDI Type A; USB-C; DC; remaining capture-routing connector detail pending | **9–12 V centre-negative ≥600 mA OR USB-C 5 V/1.5 A**; no internal battery established | **Cortex Cloud iOS/Android** via Bluetooth; desktop full editor not established; USB audio **4-in/3-out**, fixed 48 kHz; Windows driver /macOS class-compliant | Onboard capture; **no phantom power for condenser capture mic**; ordinary USB-A power is insufficient for full operation |
| TONEX ONE | Instrument in, shared stereo output/headphone workflow and USB-C; exact jack specifications pending | **9 V/120 mA OR USB-C**; polarity not verified here; no internal battery established | TONEX software/editor computer workflow; exact OS-version requirements need linked software specification; USB audio **24-bit/44.1 kHz** | One footswitch with A/B or bypass workflow; no dedicated expression socket established |
| TONEX Pedal | ¼″ instrument input; L/R outputs; headphones; DIN MIDI IN/OUT; EXT.CONTROL; USB-B; DC; output/headphone connector-size verification pending | **9 V centre-negative/320 mA**, included supply; USB-powered operation and batteries not established | TONEX Editor/software **Mac/PC**; USB audio **24-bit/44.1 kHz** | Custom IRs and captures stored separately; included software effects are not automatically additional onboard blocks |
| Flex Prime | ¼″ guitar in; 2×¼″ main out; 3.5 mm aux/phones; stereo TRS FX send/return; external EXP; 3.5 mm MIDI IN/OUT; USB-B | **12 V/3 A centre-POSITIVE** adapter; USB/battery operation not established | Wi-Fi **browser Remote Editor Windows/macOS/iOS/Android**; USB audio **4-in/4-out**, up to 24-bit/96 kHz | 4″ touchscreen; scenes, gapless switching/spillover; 5-min loop layer, 20-min total loop audio; capture creation needs the documented external software/interface workflow |

USB audio input/output counts use the manufacturer's interface convention. A capture microphone connector does not establish a dedicated live vocal-effects path. Do not connect an amplifier's speaker output directly to an instrument/capture input; the appropriate load/interface is required.

## Sources

[stomp]: https://line6.com/hx-stomp/
[hxe]: https://line6.com/hx-effects/
[nano]: https://neuraldsp.com/manual/nano-cortex
[one]: https://ikmultimedia.com/products/tonexone
[tonex]: https://ikmultimedia.com/products/tonexpedal
[flex]: https://www.headrushfx.com/products/flex-prime/index.html

- [HX Stomp FAQ](https://kb.line6.com/hx-stomp-faq), ports, dimensions and power; **launch-era block count is superseded** by [Helix 3.0 notes](https://line6.com/support/page/kb/effects-controllers/helix/helix-30-release-notes-r934/).
- [HX Effects FAQ](https://kb.line6.com/hx-effects-faq), processing, dimensions, memory and explicit absence of USB audio; [current HX Edit downloads and supported OS](https://line6.com/software/index.html?hardware=All&name=HX+Edit&os=All&submit_form=set).
- [Nano Cortex current product page](https://neuraldsp.com/nano-cortex); manual sections Hardware Specifications, Effects, Capture Mode, Presets Library, USB Channels and Expression Pedal Configuration.
- [TONEX ONE control photo](https://ikmultimedia.com/cdn/shop/files/TONEX_ONE_MG_3569_r2.jpg?v=1783342577&width=1100); [TONEX Pedal control photo](https://ikmultimedia.com/cdn/shop/files/TONEX-Pedal---Studio-57101.jpg?v=1783348434&width=1100).
- [TONEX Pedal original official page, connection/power descriptions](https://www.ikmultimedia.com/products/tonexpedal/).
- [Flex Prime FAQ](https://support.headrushfx.com/en/support/solutions/articles/69000862403-headrush-flex-prime-frequently-asked-questions), physical I/O, power, dimensions and browser editing; [current firmware downloads](https://www.headrushfx.com/downloads.html); [current NAM format details](https://www.headrushfx.com/cloud/index.html).
- P1: [Thomann B6 page with cross-listed HX Stomp and TONEX Pedal prices](https://www.thomannmusic.com/zoom_b6.htm), USD international-store observations checked **2026-10-14**; destination tax/shipping not included.
- P2: [TONEX ONE official indexed listing](https://www.ikmultimedia.com/products/tonexone/), $199.99 observation checked **2026-10-14**. The corresponding unprefixed product page did not expose a price in extracted text, so this is an indexed observation rather than confirmed checkout pricing.

Other high-end and compact modelers remain explicitly listed in the [coverage backlog](COVERAGE.md). These six records are not a ranking and do not represent the complete market.
