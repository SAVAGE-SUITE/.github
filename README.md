# .github — SAVAGE-SUITE

The org profile for https://github.com/SAVAGE-SUITE lives in `profile/README.md` and is generated.

| To change | Edit | Then |
|---|---|---|
| A property on the roster | `data/properties.json` | push — the Action rebuilds the README |
| Title, blurb, law plaque, footer | `data/profile.json` | push |
| Layout | `templates/profile.tpl.md` | push |

Local: `node scripts/build-profile.mjs` (`--check` verifies, `--ping` demotes dead domains).
Lettering is MBF Royal outlined to paths on champagne `#c9a962` foil — no font binary ships. Never redraw the marks.
