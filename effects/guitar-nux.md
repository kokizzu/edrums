# NUX guitar / bass multi-effects

[Home](README.md) · [Guitar index](guitar-floorboards.md) · [Methodology](METHODOLOGY.md)

Checked **2026-10-14**. **Partial records**; `?` is unverified. K/F/B = rotary controls / footswitches / separate front buttons; expression toe switches and rear power toggles are additional. Dimensions are normalised to **W×D×H, mm**; NUX manuals often call the long horizontal side `L` rather than `W`. Used prices are deliberately blank where no dependable observation was obtained.

## Hardware and size — all six have built-in expression

| Model / primary source | External expression | K/F/B | Dimensions; weight | Size class | Used USD | New USD observation |
|---|---|---|---|---|---|---|
| [MG-101][101] | No socket in checked rear photo | 4/2/9 [photos] | ?; ? | Unverified | ? | $129, NUX USA [US101] |
| [MG-300, original][300] | No socket in manual | 4/2/8 [manual] | 230×160×58; 754 g | Medium | ? | ? |
| [MG-300 MKII][300ii] | No socket in manual | 4/2/9 [manual] | 241×160×49; 760 g | Medium | ? | $169, NUX USA [US300] |
| [MG-400][400] | ? | 5/4/9 [photo] | ?; ? | Unverified | ? | $229, NUX USA [US400]; $172, Thomann [P1] |
| [MG-30][30] | Yes, EXP or NMP-2 Lite | 6/3/10 [manual] | 313×166×55; 1.5 kg | Large | ? | $329, NUX USA [NAM] |
| [MG-50Li][50] | Yes, EXP or NMP-2 Lite | 7/6/4 [photos] | 393×210×72; 2.8 kg | Large | ? | $549, NUX USA [US50] |

These are single new-price observations, **not** used-to-new market ranges. US versus international seller pricing can differ. All prices checked **2026-10-14**, before destination tax/shipping. MG-300 and MG-300 MKII are distinct hardware records. **MG-30 GEN2 is documented as a firmware update for MG-30**; it is not silently treated as a new hardware model.

## Processing, presets, acoustic/synth and model loading

| Model | Simultaneous blocks / available categories | Presets: factory / user | Acoustic / synth | Third-party IR | NAM / other captures |
|---|---|---|---|---|---|
| MG-101 | **10**: NG, CMP, EFX, AMP, IR, EQ, MOD, DLY, RVB, P.L; 25 electric amps; per-category choices ? | ? / ? | Exact acoustic/synth choices ? | **512 samples**; per-patch user IR plus 12 IR-collection slots | Not established |
| MG-300 | Original multi-effect architecture; exact concurrent count ?; current firmware adds bass-related processing; per-category totals require firmware-specific effect list | ? / ? | Pitch-bender and wah documented; true synth/acoustic simulator ? | **512 samples**, third-party WAV import | Not established for original hardware |
| MG-300 MKII | **10** movable; base library: NG1, CMP2, OD/DIST13, touch-wah1, EQ2, MOD14, DLY7, RVB5; GEN2 adds 4 wah and 3 DeepImage amps | ? / ? | Acoustic-body IRs; octave/rotary can make organ-like sounds, not proof of a full synth engine | **24 collection slots**, 512 samples; per-patch user-IR workflow | **10 NAM A2-Lite native slots** with GEN2; older-format acceptance must follow matching firmware notes |
| MG-400 | **10** movable; selected blocks can change category; GEN2 adds 4 wah, 3 DeepImage amps and 5 DeepImage EFX; exact current total ? | ? / ?; **3 scenes per preset** | **3 acoustic IRs** for electric-to-acoustic sound; 8 bass cab IRs; synth ? | **512 samples**, per-patch user IR plus 12 collection slots | **10 slots; A2-Lite native, A1 converted**, explicitly distinguished in GEN2 notes |
| MG-30 | **11** movable; base published categories: wah5, comp3, gate1, EFX14, EQ4, MOD13, delay8, reverb5; current page lists **35 amps =28 guitar+2 acoustic+5 bass** | Total/factory split ?; 3 Pro Scenes per preset | **3 acoustic IRs +2 acoustic amps**; synth ? | **128 per-patch user IRs**, 1024 samples | GEN2 adds **10 NAM slots**; native **A2-Lite** documented by NUX; do not assume all NAM architectures |
| MG-50Li | **14**, serial/parallel/split, dual amp paths; published EFX14, MOD13, DLY8, RVB5, wah5, comp3, gate1, EQ4 | **297 total; factory/user split conflicts**, see below | Exact acoustic/synth algorithms ? | **60 user IRs**; factory count conflicts | **NAM A2-Lite native** listed; separate proprietary **DeepImage/NUX Image** capture workflow, 30 user amp slots |

The category numbers describe the cited list, not guaranteed totals after every firmware update. Utility blocks, amps, cabinet IRs and captures are not interchangeable effect-count units.

## Ports, power and software

| Model | Audio / control connections | Power and batteries; USB-powered? | Editing apps / other USB functions | Practical features |
|---|---|---|---|---|
| MG-101 | ¼″ input and output; 3.5 mm aux; separate **TRRS headset/mic**; USB-C; DC | DC9V centre-negative; battery operation advertised, exact battery type/current not verified; USB power ? | QuickTone **Windows/macOS**; USB recording/OTG; mobile audio is not proof of mobile editing | 40 s mono /20 s stereo looper; drum machine |
| MG-300 | ¼″ input; single ¼″ main/phone output; 3.5 mm aux; micro-USB; DC | **9V centre-negative** adapter; current ?; batteries/USB bus power not established | QuickTone **Windows/macOS**; USB audio/reamp | 60 s looper; 56 rhythms; input cable required for power-on per manual |
| MG-300 MKII | ¼″ input; single ¼″ stereo main output; 3.5 mm aux; **TRRS headset/mic**; USB-C; DC | **9V**, supplied ACD-006A; required current ?; batteries/USB bus power not established | QuickTone **Windows/macOS**; USB recording/OTG, reamp and loopback; **match GEN2 editor to GEN2 firmware** | 3 Pro Scenes; independent headset-mic settings; not an XLR phantom-powered mic preamp |
| MG-400 | USB audio, main audio ports; exact complete connector inventory remains ? | Adapter requirement and battery/USB-power capability need manual confirmation | QuickTone **Windows/macOS**; GEN2 requires matching editor; USB recording/reamp/loopback | **60 s mono /30 s stereo** looper; scene-based effect switching with trails |
| MG-30 | ¼″ input; 2×¼″ out; mono FX send/return; 3.5 mm aux/phones; EXP1; USB; DC | **9V centre-negative; <400mA** draw; USB bus/battery operation not established | QuickTone **Windows/macOS**; USB audio/MIDI; GEN2 requires GEN2 editor | Parallel post-FX; flexible loop placement; manufacturer includes NMP-2 Lite in documented bundle |
| MG-50Li | ¼″ input; 2×¼″ out + **2×XLR out**; **2 mono FX loops**; 3.5 mm aux/phones; 3.5 mm MIDI IN/OUT; EXP; USB-C; NBT-1 port | **12V/1.5A centre-negative**, draw <1400mA; **5000mAh/7.4V rechargeable**; USB-powered operation not established | NUX Audio **Windows/macOS/iOS/Android**; included NBT-1 Bluetooth module; NUX Image capture app **Windows/macOS**; USB audio/MIDI | Dual signal chains; global source rates battery at 6 h, US copy at 5 h: not independently tested |

## Conflicts and firmware cautions

**MG-50Li:** the global page lists **96 factory +201 user** presets, **42 factory IRs**, and **28 white-box +30 DeepImage** amps; the US page lists **150 factory +147 user**, **60 factory IRs**, and **27 white-box +33 DeepImage** amps. Both agree on 297 total preset locations, 60 user IRs and 30 user amp slots. This catalogue preserves the conflict rather than assigning an unexplained mixture to one firmware. The US introduction's “120 user IR” wording also conflicts with its own detailed 60-user specification.

**MG-101 / MG-300 MKII:** portions of the US pages contain apparent copied model names and mutually inconsistent amp totals. The global page/manual takes precedence where clear. No “MG-101 MKII” record is invented from that wording.

**NAM:** the checked NUX page names MG-300 MKII, MG-400, MG-30 and MG-50Li as currently supported **A2-Lite native** devices. It separately describes A1 conversion and planned support for other devices. “Native” here must retain the architecture qualifier; it does not mean arbitrary `.nam` models run unmodified.

The global download pages explicitly distinguish domestic/Mandarin versus global/English hardware firmware. Use the correct regional firmware, back up presets and install the matching editor. At checking, MG-300 MKII GEN2 was 3.0.0, MG-400 GEN2 3.0.3, MG-30 GEN2 1.0.5, and MG-50Li English firmware 1.1.1. This is a dated documentation snapshot, not an update instruction for an unidentified unit.

## Sources

[101]: https://nuxaudio.com/product/mg101/
[300]: https://nuxaudio.com/product/mg300/
[300ii]: https://nuxaudio.com/product/mg300mkii/
[400]: https://nuxaudio.com/product/mg400/
[30]: https://nuxaudio.com/product/mg30/
[50]: https://nuxaudio.com/product/mg50li/
[US101]: https://www.nux.us/products/mg-101
[US300]: https://www.nux.us/products/mg-300-mkii
[US400]: https://www.nux.us/products/mg-400
[US50]: https://www.nux.us/products/mg-50li
[NAM]: https://www.nux.us/pages/nam-a2-native
[P1]: https://www.thomannmusic.com/nux_mg_400.htm

- [MG-300 manufacturer manual](https://nux.cherubtechnology.com/download/Manual/Effects/Multi_Effects/MG300/NUX_MG300_UserManual_English.pdf), control/I/O diagrams and printed p.14 specifications.
- [MG-300 MKII manufacturer manual](https://nux.cherubtechnology.com/download/Manual/Effects/Multi_Effects/MG300MKII/NUX_MG300MKII_UserManual_English.pdf), front/rear panels and final specifications. Manual predates some GEN2 additions.
- [MG-30 manufacturer V2 manual](https://nux.cherubtechnology.com/download/Manual/Effects/Multi_Effects/MG30/NUX_MG30_UserManualV2_English.pdf), printed pp.2–4 and 14; firmware-sensitive algorithms use the current product page instead.
- MG-101 [front](https://www.nux.us/cdn/shop/files/MG-101.01.jpg?v=1771628910&width=2400) and [rear](https://www.nux.us/cdn/shop/files/MG-101.05.jpg?v=1771628910&width=2400) official images.
- [MG-400 control image](https://www.nux.us/cdn/shop/files/MG-400_Thumbnails.jpg?v=1756899623&width=800).
- MG-50Li [front](https://www.nux.us/cdn/shop/files/MG-50LI.01.jpg?v=1768430650&width=2400) and [rear](https://www.nux.us/cdn/shop/files/MG-50LIWH.02.jpg?v=1768430739&width=2400) official images; rear image establishes two XLR outputs and two send/return pairs.
