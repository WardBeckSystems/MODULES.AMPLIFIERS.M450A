# M450A Program Summing Amplifier · Amplifiers

Ward-Beck Systems M450A, 1973|6. Wiki page: [M450A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M450A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 98 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 16 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1973 - M450A - P005 - 3-1.jpg](MANUALS/1973%20-%20M450A%20-%20P005%20-%203-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**N45OA PROGRAM AMPLIFIER**

The two halves of the input signa] are applied to pins and of the edge connector and then proceed via on-board resistors to pins and of 21 presenting ba anced input of approximately 5k ohm to the gna source The two sections of ZI are fo]Towed by power booster transistors Q1, Q2, Q3 and Q4 Pins and of 21 are virtually at ground potential] from s igna 1 standpoint and it i5 impractica] to measure signa | VoLtage at these points The output of 21, pin summed through RI3 pin 8 of 21 _ Thus at C15, the sum of the two haves of the inputs igna ] will be present The gain of the M45oa maybe varied from 32 48 dB by exter_ na resistance combinations associated with pins 10 and 11 Effectively this changes the feedback Toop between pins 13 and of 21 Since the selection of the gain of each amplifier is determined by connections made on the receptacle rather than inside the amplifier a 1 1 M45oA amplifiers within any given system can be freely interchanged without affecting system specifications and operation Fo]owing the preamp] ifier output at C15 1$ 12 dB per octave 1ow iter comprised of R22 R52, R23, R24 C16, C18 8is; fimteingo Pei Bend fdth?beyona Eana. and the audio pass The signa] is then fed to pin of Z2 and subsequently to transistors Q9 Q10, Q11 and Q12 These transistors comprise one ha ] f of the power selection of the actively balanced amplifier output The signa from this half is fed through C23 to pin 13 of the edge connector The s igna for the second ha ] f of the amplifier output is routed to pin of 22 and fo 1owed by transistors Q5 Q6 Q7 and Q8 C28 serves couple the signa &quot; to pin 12 of the edge connector In all instances where the M450A i 5 used its output terminals 12 and 13 must be wired to the input termina and of WBS type 70-7 transformer The secondary of this trans former can be strapped to feed ther 150 or 600 ohm Toad

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmh1TnRqdHJHb28/view?resourcekey=0-vi90sY7JOuFJIoDz9u8vPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmh1TnRqdHJHb28&resourcekey=0-vi90sY7JOuFJIoDz9u8vPw" width="240" alt="1973 - M450A - 450-02-002 - IFIO NENTS MARKED SPECIFIED MPONENT ASSEMBLY FOR SCHEMATIC.jpg"></a><br><sub>1973|6 · 450-02-002 - IFIO NENTS MARKED SPECIFIED MPONENT ASSEMBLY FOR SCHEMATIC · <a href="SCHEMATICS/1973%20-%20M450A%20-%20450-02-002%20-%20IFIO%20NENTS%20MARKED%20SPECIFIED%20MPONENT%20ASSEMBLY%20FOR%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGZONVlEM0Nvbmc/view?resourcekey=0-rWTHqVIuj-JS7sACrPOLFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGZONVlEM0Nvbmc&resourcekey=0-rWTHqVIuj-JS7sACrPOLFg" width="240" alt="1973 - M450A - 450-02-002 - MILE GCNE SCHEMATIC YEEZK.jpg"></a><br><sub>1973|6 · 450-02-002 - MILE GCNE SCHEMATIC YEEZK · <a href="SCHEMATICS/1973%20-%20M450A%20-%20450-02-002%20-%20MILE%20GCNE%20SCHEMATIC%20YEEZK%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblFRZk54TGhPbEk/view?resourcekey=0-6p0_tFFgQOwJLfDikdFaKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblFRZk54TGhPbEk&resourcekey=0-6p0_tFFgQOwJLfDikdFaKw" width="240" alt="1973 - M450A - 450-04-001 - CALE CONNECTOR LAYOUT.jpg"></a><br><sub>1973|6 · 450-04-001 - CALE CONNECTOR LAYOUT · <a href="PINOUTS/1973%20-%20M450A%20-%20450-04-001%20-%20CALE%20CONNECTOR%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M450A - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 7 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 13 of 15 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P1-3: kept SUMMING INPUT (in); RTO-144 sheet says N/A ON M450A (nc)
- disagree P1-5: kept SUMMING INPUT (in); RTO-144 sheet says N/A ON M450A (nc)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +25 V | power |  | high |
| 2 | N/C | nc |  | high |
| 3 | SUMMING INPUT | in | SUMMING INPUT | high |
| 4 | PROGRAM INPUT | in | PROGRAM INPUT | high |
| 5 | SUMMING INPUT | in | SUMMING INPUT | high |
| 6 | PROGRAM INPUT | in | PROGRAM INPUT | high |
| 7 | INPUT SHIELD | shield | PROGRAM INPUT shield | high |
| 8 | COMMON | ground |  | high |
| 9 | GAIN SET | other | GAIN SET | high |
| 10 | GAIN SET | other | GAIN SET | high |
| 11 | GAIN SET | other | GAIN SET | high |
| 12 | OUTPUT | out | OUTPUT | high |
| 13 | OUTPUT | out | OUTPUT | high |
| 14 | N/C | nc |  | high |
| 15 | -25 V | power |  | high |

**Straps:** GAIN SET: P1-9 P1-10 P1-11

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWpydTJzVFdVcFE/view?resourcekey=0-kSZroDDo5OXrXZ7GKuvuhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWpydTJzVFdVcFE&resourcekey=0-kSZroDDo5OXrXZ7GKuvuhQ" width="240" alt="1973 - M450A - P001 - Title Page.jpg"></a><br><sub>1973|6 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaTlCaHVrdXBCaWM/view?resourcekey=0-nh62oNICi0cSBh7ddnuG9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaTlCaHVrdXBCaWM&resourcekey=0-nh62oNICi0cSBh7ddnuG9w" width="240" alt="1973 - M450A - P003 - 1-1.jpg"></a><br><sub>1973|6 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ3B3TXhheGhveEU/view?resourcekey=0-q3GWdOepVxFmViyogoMxdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ3B3TXhheGhveEU&resourcekey=0-q3GWdOepVxFmViyogoMxdw" width="240" alt="1973 - M450A - P004 - 2-1.jpg"></a><br><sub>1973|6 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb3BFSjN5QW52ZEE/view?resourcekey=0-xUhPTZKhE4Y4_dj2C2DUvw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb3BFSjN5QW52ZEE&resourcekey=0-xUhPTZKhE4Y4_dj2C2DUvw" width="240" alt="1973 - M450A - P005 - 3-1.jpg"></a><br><sub>1973|6 · P005 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVBtdHpLYTNQQUE/view?resourcekey=0-MCJSaqOIJs7QoMWcFH4tRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVBtdHpLYTNQQUE&resourcekey=0-MCJSaqOIJs7QoMWcFH4tRQ" width="240" alt="1973 - M450A - P006 - 3-2.jpg"></a><br><sub>1973|6 · P006 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWm53ZWVJWjI3M2s/view?resourcekey=0-orCB7t1Y-D3EyjWZdCrRAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWm53ZWVJWjI3M2s&resourcekey=0-orCB7t1Y-D3EyjWZdCrRAQ" width="240" alt="1973 - M450A - P007 - 4-1.jpg"></a><br><sub>1973|6 · P007 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT1ZyRTZfSzY5MDg/view?resourcekey=0-qaSJFLmZ3WJd1Nod_IEWzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT1ZyRTZfSzY5MDg&resourcekey=0-qaSJFLmZ3WJd1Nod_IEWzw" width="240" alt="1973 - M450A - P008 - 5-1.jpg"></a><br><sub>1973|6 · P008 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjJSMWNBSksyUXM/view?resourcekey=0-uHu7pYBU_AJJ-GVDXtYJ_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjJSMWNBSksyUXM&resourcekey=0-uHu7pYBU_AJJ-GVDXtYJ_Q" width="240" alt="1973 - M450A - P009 - 5-2.jpg"></a><br><sub>1973|6 · P009 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWnNRWTRqbFgzN0E/view?resourcekey=0-Yje0IoTC8D3YShLVpruFmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWnNRWTRqbFgzN0E&resourcekey=0-Yje0IoTC8D3YShLVpruFmA" width="240" alt="1973 - M450A - P010 - 5-3.jpg"></a><br><sub>1973|6 · P010 - 5-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeTdFelhxTWZEams/view?resourcekey=0-vhTkOaSqQU0WTDkpy5oPSA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeTdFelhxTWZEams&resourcekey=0-vhTkOaSqQU0WTDkpy5oPSA" width="240" alt="1973 - M450A - P011 - 5-4.jpg"></a><br><sub>1973|6 · P011 - 5-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKckJ3MTRsNG1OSFk/view?resourcekey=0-2gZglyjLrzvZCDKXyVnNYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKckJ3MTRsNG1OSFk&resourcekey=0-2gZglyjLrzvZCDKXyVnNYw" width="240" alt="1973 - M450A - Program Amplifer.pdf"></a><br><sub>1973|6 · Program Amplifer</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUNmbGpsQ0V2MkE/view?resourcekey=0-ONv5BjQtKGBQvS5mOmbC-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUNmbGpsQ0V2MkE&resourcekey=0-ONv5BjQtKGBQvS5mOmbC-g" width="240" alt="1977 - M450A - P002.jpg"></a><br><sub>1977|10 · P002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEVCVTBEZmZJS1E/view?resourcekey=0-pAhAwzGrPDg5H2dM3JG7OA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEVCVTBEZmZJS1E&resourcekey=0-pAhAwzGrPDg5H2dM3JG7OA" width="240" alt="1977 - M450A - Program Amplifer.pdf"></a><br><sub>1977|10 · Program Amplifer</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1973 - M450A - 450-02-002 - IFIO NENTS MARKED SPECIFIED MPONENT ASSEMBLY FOR SCHEMATIC.kicad_sch](KICAD/1973%20-%20M450A%20-%20450-02-002%20-%20IFIO%20NENTS%20MARKED%20SPECIFIED%20MPONENT%20ASSEMBLY%20FOR%20SCHEMATIC.kicad_sch)
- [1973 - M450A - 450-02-002 - MILE GCNE SCHEMATIC YEEZK.kicad_sch](KICAD/1973%20-%20M450A%20-%20450-02-002%20-%20MILE%20GCNE%20SCHEMATIC%20YEEZK.kicad_sch)
- [1973 - M450A - Program Amplifer p12.kicad_sch](KICAD/1973%20-%20M450A%20-%20Program%20Amplifer%20p12.kicad_sch)
- [M450A.kicad_sym](KICAD/M450A.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
