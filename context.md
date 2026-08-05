# context.md — domain background for gracas

Read together with `AGENTS.md`. This file carries the background an editor
needs before touching `data/chronology.json`.

## The subject in one paragraph

In 1830, Catherine Labouré (1806–1876), a novice of the Daughters of Charity,
reported three apparitions of the Virgin Mary in the chapel of the company's
motherhouse at 140 rue du Bac, Paris: the night of 18–19 July, 27 November
(the "medal vision" — the design and invocation of what became the Miraculous
Medal), and an undated day in December. Her confessor Jean-Marie Aladel CM
brought the request for a medal to Archbishop de Quélen, who authorized it;
the first medals were struck in June 1832, during the Paris cholera epidemic,
and spread by the million within a few years — the people of Paris renamed the
"medal of the Immaculate Conception" the *miraculous* medal. In Portuguese and
Spanish devotion the image is Nossa Senhora das Graças / Nuestra Señora de las
Gracias, which is why this repo is `gracas`.

## The datable spine

| Date | Event | Status |
| --- | --- | --- |
| 1806-05-02 | Birth of Catherine Labouré | verified |
| 1830 (Apr?) | She enters the rue du Bac seminary | month unverified |
| 1830-07-18/19 | First reported apparition | date verified (chapel site) |
| 1830-11-27 | Medal vision | date verified (chapel site) |
| 1830-12 | Third reported apparition | day unknown, month only |
| 1832-06 | First medals struck/distributed (cholera epidemic) | month verified; day and batch size contested |
| 1836-02-16 | Paris canonical inquiry opens (Quentin, for de Quélen) | opening date on one devotional source — to verify |
| 1842-01-20 | Reported Ratisbonne conversion, Rome | verified |
| 1842-06-03 | Patrizi decree on the Ratisbonne conversion | verified (secondary) |
| 1876-12-31 | Death of Catherine; identity as seer becomes known | verified |
| 1894-07-23 | Leo XIII institutes the 27 Nov feast | verified (Cath. Enc. 1911) |
| 1933-05-28 | Beatification (Pius XI); body exhumed same year | verified |
| 1947-07-27 | Canonization (Pius XII) | verified (vatican.va speech of 28 Jul) |

## The critical nuance: what exactly was approved

Three layers, which must never be flattened:

1. **The medal and its cult** — authorized by de Quélen (1832), examined
   favorably by the 1836 diocesan inquiry, honored with a feast by Leo XIII
   (1894). This is where explicit approval lives.
2. **The seer** — beatified 1933, canonized 1947. A judgment on her sanctity,
   read by commentators as implicit confirmation of her account.
3. **The apparitions themselves** — the 1836 inquiry gathered favorable
   evidence but (per the detailed Vincentian-derived account) de Quélen
   pronounced no formal judgment and the proceedings lapsed at his death in
   1839; fr.wikipedia's synthesis states no completed canonical trial ever
   formally declared the apparitions authentic. Devotional sources compress
   this into "declared of supernatural origin in 1836". The dataset records
   both readings, attributed.

The Ratisbonne conversion (Rome, 1842) is the mirror case: a **separate**
reported event that DID receive a formal decree (Cardinal Patrizi, 3 June
1842) — approval of that Roman event, not of the Paris apparitions.

## Attestation chain (why "reported" is doing real work)

Catherine told only her confessor, Aladel; he relayed the account (without her
name) to the archbishop; she refused to testify to the 1836 inquiry and stayed
publicly anonymous until around her death (31 Dec 1876). Her own written
accounts came later, at her confessors' instruction. Everything descriptive
about the apparitions therefore passes through this chain, and entries must
say so rather than narrate the visions as observed fact.

## Glossary of local terms

- **Seminary (Daughters of Charity)** — the company's term for its novitiate.
- **CM** — Congregation of the Mission (Vincentians / Lazarists), Aladel's
  congregation, spiritual directors of the Daughters of Charity.
- **Cardinal Vicar** — the pope's vicar for the diocese of Rome; Patrizi held
  the office in 1842, hence his tribunal judged the Ratisbonne case.
- **Promoter** — the official charged with critically testing the evidence in
  a canonical inquiry (Quentin's role in 1836).

## Open verification threads (mirror of the bootstrap epic issue)

- 1836 inquiry: opening date (16 Feb), 19 sittings, and the no-judgment
  conclusion — all resting on one devotional source; needs the archdiocesan
  archives or a critical biography (Laurentin's *Catherine Labouré* is the
  scholarly standard).
- 1830 April seminary entry: exact date.
- 1933 exhumation: exact date and the official process documents.
- Feast institution: the 23 July 1894 decree text (Sacred Congregation of
  Rites) — locate in Acta Sanctae Sedis.
- Canonization: the AAS text of the 27 July 1947 canonization itself (the
  cited vatican.va page is the next day's speech).
