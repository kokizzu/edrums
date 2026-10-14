# Dedicated synth, acoustic, vocoder and pitch pedals

[Home](README.md) · [Methodology](METHODOLOGY.md) · [Multi-effects](guitar-floorboards.md) · [Vocals](vocal.md)

Research snapshot **2026-10-14**. **Partial records**: `?` means unverified, not No. These are specialist tools, not interchangeable replacements for complete amp/effect processors. Dimensions are **W×D×H, mm**; pedal travel and plugs need extra clearance.

## Hardware, expression and prices

K/F/B = independently adjustable rotary controls / main footswitches / separate buttons. Concentric controls are explained explicitly; expression toe switches and small power/mode switches are additional. Prices are single **USD US-market new-price observations**, checked 2026-10-14, not delivered Indonesian prices. No dependable used-price observation was established for these rows.

### No built-in expression pedal

| Model / technical source | External expression | K/F/B | W×D×H; weight | Size class | Used USD | New USD |
|---|---|---|---|---|---|---|
| [BOSS SY-1][sy1] | Yes, EXP/CTL | **6/1/0**; four knob positions, two concentric pairs | 73×129×59; 450 g incl. battery | Compact | ? | $184.98 sale [P1] |
| [BOSS SY-200][sy200] | Yes, EXP or up to 2 external switches | **8/2/2** | 101×138×63, H65 with feet; 630 g /700 g incl. batteries | Compact | ? | $337.99 [P2] |
| [BOSS AC-3][ac3] | No controller socket listed | **5/1/0**; four knob positions, Level/Reverb concentric | 73×129×59; 425 g incl. battery | Compact | ? | $181.99 [P3] |
| [BOSS VO-1][vo1] | No controller socket listed | **5/1/0**; four knob positions, Level/Blend concentric | 73×129×59; 430 g incl. battery | Compact | ? | $259.00 [P4] |
| [BOSS GM-800][gm800] | **2 CTL/EXP sockets**, up to 4 external switches | **6/4/10** | 246×134×63, H65 with feet; 1.2 kg excl. adapter | Medium | ? | ? |

### Built-in expression pedal

| Model / technical source | External expression | K/F/B | W×D×H; weight | Size class | Used USD | New USD |
|---|---|---|---|---|---|---|
| [BOSS XS-100][xs100] | Yes, CTL1,2/EXP2 | **1/2/2 + expression toe switch** | 147×230×72, max H96; 1.7 kg | Large by the defined depth limit | ? | ? |

## Processing, categories and memory

| Model | Architecture and available choices | Factory / user memory | Synth / acoustic function | Third-party IR / NAM |
|---|---|---|---|---|
| SY-1 | One selected polyphonic synth engine; **121 sounds =11 types×11 variations**; independent dry/synth blend and parallel loop | Panel settings; no stored user-preset bank | **Guitar/bass synth**, standard instrument input; no special pickup | No digital file-import connection listed |
| SY-200 | One selected polyphonic synth engine; **171 sounds across 12 categories**; counts within each category not yet transcribed | **128 editable memories**; factory-filled subset ? | **Guitar/bass synth**, standard instrument input; no special pickup | Micro-USB is documented for firmware updates, not IR/NAM import |
| AC-3 | **4 acoustic simulation modes**: Standard, Jumbo, Enhanced, Piezo; reverb alongside the selected simulation | Panel settings; no stored user-preset bank | **Electric-guitar-to-acoustic simulator**; not merely an acoustic amp model | No digital file-import connection listed |
| VO-1 | **4 modes**: Advanced, Vintage, Talk Box, Choir; one selected mode with direct/effect blending | Panel settings; no stored user-preset bank | **Vocoder** for guitar/bass; Choir can operate without a microphone; not an intelligent vocal harmonizer | No digital file-import connection listed |
| GM-800 | **4 Tone parts +1 Rhythm part**; 1200+ tones, 70+ drum kits; each part has MFX with **93 types** and EQ; scene has **2 MFX**, each 93 types, plus reverb **7** and chorus/delay **9** types | **150 editable Scenes, 100 factory-filled**; separate import-tone memory | **ZEN-Core instrument synth**, including sampled/instrument-style tones; special pickup connection required | Roland Cloud sound expansions are proprietary tone content; IR/NAM loading not established |
| XS-100 | Dedicated polyphonic pitch processing, **±4 octaves**, detune ±50 cents, fixed retuning/drop/capo and pedal shifting; assignable block count N/A | **30 saved memories**; factory-filled subset ? | Pitch shifter, **not** a synth or acoustic simulator | USB is documented for system updates; IR/NAM loading not established |

SY-1 categories are Lead 1/2, Pad, Bass, Strings, Organ, Bell, SFX 1/2 and Seq 1/2. SY-200 adds a different category structure: Lead, Pad, String, Bell, Organ, Bass, Dual, Sweep, Noise, SFX, Seq and Arpeggio. Category names describe available choices, not simultaneously active independent blocks.

## Connections, power and apps

| Model | Audio / control connections | Power; USB-powered? | Configuration apps / other digital functions | Important limitations |
|---|---|---|---|---|
| SY-1 | ¼″ input/output, send/return, TRS EXP/CTL, DC | **9 V battery or PSA adapter; 115 mA**; no USB | No computer editor connection listed | Hold function; parallel dry/effect routing; no headphone output listed |
| SY-200 | ¼″ input/output/send/return; TRS EXP/CTL; 3.5 mm TRS MIDI IN/OUT; micro-USB; DC | **3 AA or PSA adapter; 230 mA**; USB power not listed | No full editor established; Windows/macOS update tools are **not** a full editor | USB is **program-update only**; no headphone output listed |
| AC-3 | ¼″ input; separate ¼″ **G.AMP OUT and LINE OUT**; DC | **9 V battery or PSA adapter; 70 mA**; no USB | No computer editor connection listed | Its two outputs are **different destinations, not a stereo pair** |
| VO-1 | ¼″ instrument input/output/send/return; XLR mic; DC | **9 V battery or PSA adapter; 70 mA**; no USB | No computer editor connection listed | XLR does **not** establish phantom-power support; phantom voltage unverified |
| GM-800 | **Serial GK IN/OUT**; 2×¼″ audio outputs, L shared with phones; 2×CTL/EXP; DIN MIDI IN/OUT; USB-B computer; USB-memory port; DC | Supplied **PSB-1U adapter; 840 mA**; battery/USB bus power not listed | BOSS Tone Studio **Windows/macOS**; USB audio/MIDI, guitar-to-MIDI and re-synthesis | **GK-5/GK-5B or compatible conversion required for guitar input**; Serial GK is not an ordinary analog guitar jack |
| XS-100 | ¼″ input, thru and output; TRS CTL/EXP; 3.5 mm MIDI IN/OUT; USB-C; DC | Supplied adapter; **160 mA draw**; voltage/polarity, USB bus and battery operation not established here | Full editor not established; USB system-update capability alone is not editing/audio | Built-in expression has A/B assignment and toe switching; preserve pedal-travel clearance |

### GM-800 cabling matters

The Serial GK connection uses the manufacturer's **BGK cable** and the appropriate divided pickup/interface. Its connector shape does not make it a standard analog instrument input. Older 13-pin GK equipment requires the appropriate **GKC-AD** conversion; a standard guitar cable is not a substitute. MIDI keyboards/controllers can also drive the sound engine. This differs fundamentally from SY-1/SY-200's ordinary guitar/bass input.

## Sources

[sy1]: https://www.boss.info/global/products/sy-1/specifications/
[sy200]: https://www.boss.info/global/products/sy-200/specifications/
[ac3]: https://www.boss.info/global/products/ac-3/specifications/
[vo1]: https://www.boss.info/global/products/vo-1/specifications/
[gm800]: https://www.boss.info/global/products/gm-800/
[xs100]: https://www.boss.info/global/products/xs-100/specifications/

- Control arrangements: manufacturer specifications above, [AC-3 top photo](https://static.roland.com/assets/images/products/main/ac_3_top_main.jpg), [VO-1 top photo](https://static.roland.com/products/vo-1/image/vo-1_top.png). Independently adjustable concentric rings are counted separately and explicitly disclosed.
- P1: [Sweetwater SY-1](https://www.sweetwater.com/store/detail/SY1--boss-sy-1-guitar-synthesizer-pedal).
- P2: [Sweetwater SY-200](https://www.sweetwater.com/store/detail/SY200--boss-sy-200-guitar-synthesizer-pedal).
- P3: [Sweetwater AC-3](https://www.sweetwater.com/store/detail/AC3--boss-ac-3-acoustic-simulator-pedal).
- P4: [Sweetwater VO-1](https://www.sweetwater.com/store/detail/VO1--boss-vo-1-vocoder-pedal).

The wider universe of dedicated distortion, fuzz, delay, modulation, compressor, EQ, looper and acoustic-body pedals is **not yet exhaustively covered**. See the [coverage backlog](COVERAGE.md).
