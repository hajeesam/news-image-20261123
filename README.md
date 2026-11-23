# news-image-20261123 — "The Front Page"

Sum up 23 November's world news in one image. Entry for the make.fun
bounty **news-image-20261123** ($100, top 50 share it).

## How to run

```sh
python3 main.py
# writes ./output/entry.png (1024x1024)
# or: MAKEFUN_OUTPUT_DIR=/some/dir python3 main.py
```

Python 3 standard library only — no Pillow, no fonts, no network, no
randomness. The program writes the approved render byte-for-byte and
verifies its sha256 before and after writing.

## The image

Masthead **"THE FRONT PAGE"**, Monday 23 November 2026. One dominant
COP31 lead — a drawn conference-collapse scene with a NO DEAL stamp —
beside an hour-by-hour timeline rail (Hormuz dare, COP31 collapse,
Vanuatu M6.5 quake, Kyiv toll, NATO council). The remaining stories are
numbered region-by-region ledger rows (all 35 stories, 7 regions), then
a SCOREBOARD strip (NFL, football, tennis, markets), a NOT IN TODAY'S
COUNT footer and a sources line. Cream paper, black ink, red kickers.

This layout is deliberately different from the referral entries for the
same competition (numbers band + three hero cards + 2x5 card grid +
dotted map + ALSO list + boxed DATE CHECK): one hero only, a timeline
rail instead of a numbers band, ledger rows instead of cards, a
scoreboard instead of a map, left-out dates as one footer line.

## Facts

All 35 stories are from the verified 23 November 2026 news day
(cutoff 05:30 UTC): COP31 collapses with no deal after a record 44
hours of overtime; Trump dares Iran to test the Hormuz blockade; Kyiv
region toll rises to 12; NATO emergency council on Poland; the Asian
sell-off after the Wall Street rout; Democrats clinch 258 House seats;
Alcaraz wins his first ATP Finals crown; Liverpool rout United 4-0.

Certainty is labelled where it matters: the Sudan drone claim is tagged
[CLAIM], the Abu Dhabi talks [ONE SOURCE]. Events from other days
(Shenzhen trilateral, BepiColombo, Cyclone Akvan, GTA VI sales, the
Senate war-powers vote, the ICJ Myanmar ruling, Peru quake, Sparta II,
the 400-drone barrage, Bitcoin below $60,000) are listed as NOT IN
TODAY'S COUNT, not presented as today's news.

Sources: CNN, Reuters, AP, AFP, BBC, PBS NewsHour, Market Samachar,
USGS, BMKG, ATP Tour, NFL Network, The Times, Radio Dabanga,
Eye Radio, Sedena. Scenes are drawn illustrations, not photographs.

## Approved render

- sha256 `92891c30990980d4a6ab5451d88bde817915da4fcb80bdc67bacf4303afc2796`
- 77,497 bytes, 1024x1024, palette-256 PNG
- verified visually; two runs of `main.py` produce byte-identical output
