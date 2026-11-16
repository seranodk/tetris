# Tetris

Komplet Tetris-klon til browser og mobil – optimeret til iPhone 15 (portræt, safe-area, ingen zoom/scroll).

**Spil:** https://seranodk.github.io/tetris/

**Version:** 1.2 (se [CHANGELOG.md](CHANGELOG.md))

## Regler (som i moderne Tetris)
- 7-bag tilfældig brikrækkefølge
- SRS-rotation med wall kicks (inkl. I-brikken)
- Hold, ghost-brik og de næste 3 brikker
- Lock delay (0,5 s, max 15 nulstillinger)
- Pointgivning: single/double/triple/Tetris, T-spin (+ mini), back-to-back (×1,5), kombo, soft/hard drop
- Niveau stiger hver 10. linje med officiel faldhastighed; valgfrit startniveau
- Rekord gemmes lokalt

## Styring (iPhone)
| Handling | Knap / gestus |
|---|---|
| Flyt venstre/højre | ◀ ▶ (hold for auto-gentag) eller træk på brættet |
| Drej med uret | grøn knap / tryk på højre halvdel af brættet |
| Drej mod uret | tryk på venstre halvdel af brættet |
| Lynhurtigt ned | hold den lilla dobbelt-pil inde (brikkerne falder til bunden og låser hurtigt) |
| Hard drop | swipe ned på brættet / `Space` |
| Hold | tryk på HOLD-feltet / swipe op |
| Pause | knappen under statistikken |

Tastatur: piletaster (↓ = soft drop), `X`/`↑` drej med uret, `Z` mod uret, `Space` hard drop, `C`/`Shift` hold, `P`/`Esc` pause.

## Lyd
Spillet bruger kun rigtige optagede lyde (ingen syntetiske). Læg `.mp3`-filer i mappen `sounds/`:
`move`, `rotate`, `drop`, `lock`, `hold`, `clear`, `tetris`, `gameover`. Mangler en fil, er der bare stille.

## Filer
- `index.html` – hele spillet i én fil
- `CHANGELOG.md` – versionshistorik
