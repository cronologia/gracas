# gracas — Nossa Senhora das Graças / the Miraculous Medal

An open, source-referenced chronology of the **reported 1830 apparitions to
Catherine Labouré** at the Rue du Bac chapel in Paris, the **Miraculous Medal**
struck in 1832 on the basis of her account, and the **Church judgments** passed
on both — from her birth (1806) to her canonization (1947).

Published site: <https://cronologia.github.io/gracas/> (en / es / pt).

## Posture

The apparitions are recorded as **reported** events: the dataset states who
reported what and when, and what Church authorities ruled and when, citing the
ruling document — it never asserts the supernatural claim as fact, and never
denies it either. Church-approval status is a first-class field: approval here
attached primarily to the medal, the 1894 feast and the seer's canonization,
and the sources disagree about exactly what the 1836 Paris inquiry concluded —
the dataset records the disagreement instead of resolving it.

## How it works

- `data/chronology.json` is the single source of truth (English, hand-edited).
- `node build.js` compiles it into static HTML under `docs/`, served by
  GitHub Pages, in English, Spanish and Portuguese.
- `data/i18n/es.json` and `data/i18n/pt.json` are hand-authored translation
  dictionaries (exact English source string → translation).
- Every fact carries `sources[]`; unverified dates carry `dateVerified: false`
  and render with a `?` flag.

## Contributing / editing

Read `AGENTS.md` and `context.md` first. The non-negotiable editing loop:

```
node scripts/validate-data.js && node --test && node build.js
```

and commit the regenerated `docs/` together with the data change. The sourcing
discipline lives in `cronologia/core` → `skills/sourcing-rules/SKILL.md`.

## License

See `data/chronology.json` references for source attribution. Site code
follows the cronologia/core template.
