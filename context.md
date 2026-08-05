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

## Scope: the Paris around it, and what came after

The chronology runs 1806–2017 and is not only the apparitions and the judgments.

**Before and around (context, never corroboration).** The translation of
St Vincent de Paul's relics on 25 April 1830, four days after Catherine entered
the novitiate — the moment the suppressed-and-restored Vincentian family
recovered its public standing. The July Revolution: the ordinances of 26 July,
the fighting of 27–29 July, the sack of the archbishop's palace on 29 July —
eight days after the first reported apparition and four months before the medal
vision. The February 1831 riots that wrecked Notre-Dame and the archbishopric
and drove de Quélen from his residence, a year before he authorized the medal.
The cholera epidemic of 26 March – 30 September 1832, into which the first
medals went. **Each of these entries says in its own rendered text that it is
the setting and not an explanation or a corroboration**, and no source cited
connects any of them to what Catherine Labouré reported. Keep it that way.

**After.** Her vows on 30 January 1831 and forty years of obscurity at Reuilly;
Aladel's pamphlet of August 1834; the diffusion figures; the chapel's
enlargements in 1849 and 1930; the exhumation of 21 March 1933; the visitor
counts.

## How reported miracles are handled (core#71)

**A miracle is a claim, not an event.** Two things attached to one are datable:

1. **The account** — that a cure or conversion was *reported*, by whom, and when
   first attested. Aladel's *Notice historique* (August 1834) is the type case,
   and the event is the **publication**: a partisan of the devotion, who was
   also the seer's confessor, collecting and circulating claims. Titles name the
   reporter, never a beneficiary.
2. **The recognition act** — a dated Church judgment with a document. There is
   exactly one on this record: **Cardinal Patrizi's decree of 3 June 1842**, and
   it concerns Ratisbonne's conversion at Rome — a different reported event in a
   different city, not the medal and not the Paris apparitions. The existing
   disambiguation entry keeps those apart and must go on doing so.

Consequences that hold:

- No cure is recorded as having happened. No cure claimed for the medal at Paris
  carries a Church judgment of its own, and one without a named reporter and a
  date is not in the dataset at all.
- **The 1933 exhumation is recorded as a report, not a finding.** What is dated
  is that named categories of witness *reported* a body intact and supple. The
  dataset does not say the body was incorrupt, and does not say it was not.
- **"Miraculous" stays a popular attribution.** It is the name Parisians gave
  the medal — the dataset records the naming and never adopts it as a finding.
  The French Wikipedia's gloss is carried too: the name pointed at the medal's
  reported *origin* in a vision, not at power in the object.
- **Counts belong to their counters and are not reconciled.** Medal diffusion:
  the chapel's own figures, Yves Chiron's (via the French Wikipedia), and
  Polistena's, all attributed separately. Attendance: ~2 million a year from a
  2017 Paris tourism observatory survey, ~3 million for 2025 from the French
  Wikipedia. The gap stays.
- **Cures get no approval-ladder rungs.** The six rungs judge the apparitions,
  the medal's cult, the Ratisbonne event and the seer's cause; nothing here
  changed them.

## The datable spine

| Date | Event | Status |
| --- | --- | --- |
| 1806-05-02 | Birth of Catherine Labouré | verified |
| 1830-04-21 | She enters the rue du Bac seminary | day from en.wikipedia — flagged |
| 1830-04-25 | Translation of St Vincent de Paul's relics | verified |
| 1830-07-18/19 | First reported apparition | date verified (chapel site) |
| 1830-07-27 | July Revolution; archbishopric sacked 29 July | verified (Britannica, RHEF) |
| 1830-11-27 | Medal vision | date verified (chapel site) |
| 1830-12 | Third reported apparition | day unknown, month only |
| 1831-01-30 | Vows; Reuilly; forty years of anonymity | day from en.wikipedia — flagged |
| 1831-02-14/15 | Notre-Dame and archbishopric devastated | verified (RHEF 1964) |
| 1832-03-26 | Cholera reaches Paris (to 30 Sept; >18,400 dead) | verified (ENAP); toll disputed |
| 1832-06 | First medals struck/distributed (cholera epidemic) | month verified; day and batch size contested |
| 1834-08 | Aladel prints the first collection of reported graces | month from fr.wikipedia — flagged |
| 1836-02-16 | Paris canonical inquiry opens (Quentin, for de Quélen) | opening date on one devotional source — to verify |
| 1842-01-20 | Reported Ratisbonne conversion, Rome | verified |
| 1842-06-03 | Patrizi decree on the Ratisbonne conversion | verified (secondary) |
| 1849 | Chapel enlarged (Gallois) | year from fr.wikipedia — flagged |
| 1876-12-31 | Death of Catherine; identity as seer becomes known | verified |
| 1894-07-23 | Leo XIII institutes the 27 Nov feast | verified (Cath. Enc. 1911) |
| 1930 | Centenary rebuilding (Richardière) | year from fr.wikipedia — flagged |
| 1933-03-21 | Body exhumed; witnesses report it intact | day from tertiary sources — flagged |
| 1933-05-28 | Beatification (Pius XI) | verified |
| 1947-07-27 | Canonization (Pius XII) | verified (vatican.va speech of 28 Jul) |
| 2017 | Visitor counts, as published by the counting bodies | verified (survey year) |

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
- 1830 seminary entry: 21 April is now recorded from the English Wikipedia and
  stays flagged; a company record would settle it.
- 1933 exhumation: 21 March is now recorded from tertiary sources and stays
  flagged; the official process documents would settle it.
- Feast institution: the 23 July 1894 decree text (Sacred Congregation of
  Rites) — locate in Acta Sanctae Sedis.
- Canonization: the AAS text of the 27 July 1947 canonization itself (the
  cited vatican.va page is the next day's speech).

## Sources not reachable from this session (August 2026)

- **chapellenotredamedelamedaillemiraculeuse.com returned 503** repeatedly, so
  the official chapel pages on Catherine Labouré and on the medal's history
  could not be re-read for this wave. The entries that rest on them are the ones
  the bootstrap already wrote; the new building-history and diffusion figures
  come from the French Wikipedia and are labelled as tertiary.
- **cath.ch returned 403**, so the daily-visitor figure it reports is not cited;
  the annual figure is cited to Aleteia, which names the 2017 Paris tourism
  observatory survey behind it.
- **Yves Chiron's 2007 biography was not read.** The diffusion numbers reach
  this dataset through the French Wikipedia's citation of him, and the entries
  say so rather than collapsing the chain.
- **Left out on purpose**: individual cures and conversions attributed to the
  medal. Aladel's pamphlet collects them, but nothing reachable here names a
  beneficiary with a date and a reporter, and none of them carries a Church act.
  A cure that cannot carry such a source stays out — that is the rule, and this
  note is the record that it was applied rather than forgotten.
