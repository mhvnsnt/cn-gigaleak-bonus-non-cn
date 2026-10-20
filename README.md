# cn-gigaleak-bonus-non-cn

Owner-approved non-CN bonus material pulled zero-disk (streamed in 100MiB chunks)
from the Internet Archive item `cartoon-network_20261014`, 2026-10-19/20.
Every asset size API-verified against the source byte counts.

## Release `bonus-non-cn-v1` (152 assets, 15,495,611,824 bytes total)

| Original file | Bytes | Assets |
|---|---|---|
| `Unsorted/nick.7z` | 7,209,034,412 | `nick.7z.part-0000` .. `part-0068` |
| `Unsorted/2024_Nick_Gigaleak.zip` | 4,330,816,233 | `2024.Nick.Gigaleak.zip.part-0000` .. `part-0041` |
| `A TON OF DISNEY PITCH BIBLES AND CLUB PENGUIN PDFS.rar` | 2,478,704,302 | `A.TON.OF.DISNEY.PITCH.BIBLES.AND.CLUB.PENGUIN.PDFS.rar.part-0000` .. `part-0023` |
| `DISNEY LEAKS and wow wow wubbsy fla.rar` | 756,705,253 | `DISNEY.LEAKS.and.wow.wow.wubbsy.fla.rar.part-0000` .. `part-0007` |
| `ClubPenguin.zip` | 436,196,042 | `ClubPenguin.zip.part-0000` .. `part-0004` |
| `Care Bears - Random.7z` | 266,409,663 | `Care.Bears.-.Random.7z.part-0000` .. `part-0002` |
| `Unsorted/rick and morty toonboom files.zip` | 17,745,919 | single asset |

Note: GitHub sanitizes asset names (spaces become dots, parentheses removed).

## Reassembly

Download all parts of one file, then concatenate in numeric order, e.g.:

    cat nick.7z.part-* > nick.7z

`2024_Nick_Gigaleak.zip` and the rick-and-morty zip were stored deflated inside the
source archive and are already decompressed here — the parts reassemble directly
into the usable .zip files.

## Release `tv-gigaleak-smalls-v1`

TV Gigaleak small wins (same repo): `garfield-model-sheets.zip` (14,210,001 bytes,
single asset) and `LTS_MainModelPack_120909.pdf` (250,450,405 bytes,
`LTS.MainModelPack.120909.pdf.part-0000` .. `part-0002` — note GitHub strips the
underscore in asset names; check the release page for exact names).
