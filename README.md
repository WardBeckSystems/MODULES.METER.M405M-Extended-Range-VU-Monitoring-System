# M405M · Meter

Ward-Beck Systems M405M, 1995|28. Wiki page: [M405M on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M405M.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 1 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 4 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 4 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1995 - M405M - 14-292-02-003 - 3 P1 CONNECTOR 3-1 - LAYOUT.wp](MANUALS/1995%20-%20M405M%20-%2014-292-02-003%20-%203%20P1%20CONNECTOR%203-1%20-%20LAYOUT.wp) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Range** | -10 dBu to +10 dBu in five steps. |
| **Input selection** | Pushbutton select between two sources. |
| **Source impedance** | 600 ohms or less, balanced. |
| **Input impedance** | Greater than 20K ohms. |
| **Attenuator Tracking** | ±0.25dB per step, non-cumulative. |
| **Meter ballistics** | Complies with ANSI C16.5. |
| **Frequency response** | ±0.25 dB 30 Hz to 15 kHz. |
| **Monitor output** | ±1 dB from 100 Hz to 5 kHz. |
| **Total harmonic distortion** |  |
| &nbsp;&nbsp;Headset output | Less than 1%, from 50 Hz to 10 kHz. |
| **Speaker output** | Less than 1%, 50 Hz to 10 kHz |
| **Noise** | 40 dB below 0 VU reference. GENERAL M405M EXTENDED RANGE VU MONITORING SYSTEM The M405M has been designed to measure and monitor the average level of an audio signal. This instrument is self-contained and mounts in an EIA standard 19&quot; equipment rack. It is powered by a 24 volt DC wall mount power supply. A &quot;range&quot; attenuator, providing 5 steps (-10, 0, +4, +8, +10 dBu), accommodates audio input levels from -10 to +10 dBu fora 0 meter reading. The M405M accepts two inputs (A orB) at the rear of the instrument. Selection between theA orB inputs maybe made by a pushbutton selector on the front of the unit. An internal speaker, complete with level control, is mounted in the front panel to permit the user to listen to the source being metered. A headset jack is also provided on the front panel for headphone monitoring. A1 VU Meter Amplifier WBS SA14-292B A2 Intercom pre and Output Amplifier WBS M703C F1 314 Amp fast blow fuse Buss AGC0.75 J1 Jack 1/4&quot; headphone Switchcraft NL-11413 LS1 Speaker Misco DC22S M1 Vu Meter Bach-Simpson 544WL R1 Speaker Level Clarostat WBS 10-073 SW1-SW7 Switch Schadow 2CF-GHT-AA WBS recommends the use of replacement parts made by the specified manufacturers for continued optimum equipment performance. M405M EXTENDED RANGE VU MONITORING SYSTEM March 20, 1995 MW94002/M405M.WP |

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRW5INXFHV0RYYm8/view?resourcekey=0-B1v63wkJEzmsd9GLeQmgxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRW5INXFHV0RYYm8&resourcekey=0-B1v63wkJEzmsd9GLeQmgxw" width="240" alt="1995 - M405M - Archived - M405M - METER - MONITOR 003.jpg"></a><br><sub>1995|28 · Archived - M405M - METER - MONITOR 003</sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazduZW1qTHMxVXc/view?resourcekey=0-3VsfYdXwD2x81mQKUBKcAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazduZW1qTHMxVXc&resourcekey=0-3VsfYdXwD2x81mQKUBKcAw" width="240" alt="1995 - M405M - Archived - M405M - METER - MONITOR 001.jpg"></a><br><sub>1995|28 · Archived - M405M - METER - MONITOR 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVVwSF9qd1lsZGc/view?resourcekey=0-E3B4r1SbTMloTl2MJskM4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVVwSF9qd1lsZGc&resourcekey=0-E3B4r1SbTMloTl2MJskM4g" width="240" alt="1995 - M405M - Archived - M405M - METER - MONITOR 002.jpg"></a><br><sub>1995|28 · Archived - M405M - METER - MONITOR 002</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M405M.kicad_sym](KICAD/M405M.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

## 3-D model

[`MECHANICAL/M405M.stl`](MECHANICAL/M405M.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M405M)

- **Size:** 482.09 × 88.14 mm panel, 165 mm deep, 3.2 mm plate (the AutoCAD drawing (hundredths of an inch: a 19" rack panel))
- **From the drawing:** 6 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M405M - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M405M.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
