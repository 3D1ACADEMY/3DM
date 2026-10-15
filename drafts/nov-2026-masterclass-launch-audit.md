# Pre-Launch Audit — Advanced Facial Aesthetics & Hair Longevity Masterclass

**Working title:** Advanced Facial Aesthetics & Hair Longevity Masterclass — Literature Review Evidence-Based Masterclass | Exosomes, PDRN & Biomimetic Peptides
**Target release:** November 2026
**Audit date:** 15 October 2026
**Status:** Not yet publicly discoverable (site sitemap, `llms.txt`, Lemon Squeezy storefront, DermaRoom partner store and search engines all checked — no listing).

This file lives in `drafts/`, which `.mintignore` excludes from the Mintlify build.

---

## 1. Evidence map for the three pillars

Publication types below are **PubMed's own tags**, retrieved 15 Oct 2026. OCEBM level is inferred from study design.

### Pillar 1 — Exosomes (STRONGEST)

| PMID | Journal / Year | PubMed tag | Notes |
|---|---|---|---|
| 41800726 | *Aesthet Surg J* 2026 | Systematic Review + Meta-Analysis | "Clinical Advances in Exosome-Based Therapies for Aesthetic Medicine: SR & MA of Human Clinical Trials" — **flagship anchor** |
| 37381168 | *J Cosmet Dermatol* 2023 | Systematic Review | Exosome treatment in hair restoration |
| 41515899 | *Int J Mol Sci* 2025 | Systematic Review | Exosome therapies for alopecia areata |
| 40955427 | *Clin Cosmet Investig Dermatol* 2025 | Review (SR) | Exosomes & hair regeneration across alopecia types |
| 39198280 | *Aesthetic Plast Surg* 2025 | Systematic Review | "Regenerative Aesthetics: A Genuine Frontier or Just a Facet of Regenerative Medicine" — sceptical framing, useful for balance |
| 41931695 | *J Drugs Dermatol* 2026 | Scoping Review | Exosome therapies in dermatology |
| 41752855 | *Life (Basel)* 2026 | Journal Article (RCT-titled) | Laser-assisted exosome boosters for scars/facial rejuvenation |
| 40468166 | *J Cosmet Dermatol* 2025 | Journal Article | Fractional CO₂ laser-assisted exosome delivery, hair regrowth (case-level) |

**Verdict:** Level 1 defensible. State that the evidence is early but real.

### Pillar 2 — PDRN / polynucleotides (MODERATE)

| PMID | Journal / Year | PubMed tag | Notes |
|---|---|---|---|
| 39645667 | *J Cosmet Dermatol* 2025 | Systematic Review | "The Effectiveness of Polynucleotides in Esthetic Medicine" — **anchor** |
| 32757710 | *Regen Med* 2020 | Systematic Review | PDRN in wound healing & tissue regeneration |
| 40826297 | *Aesthetic Plast Surg* 2025 | Randomized Controlled Trial | PDRN + BoNT for acne scars |
| 28491036 | *Front Pharmacol* 2017 | Review | Pharmacology & clinical use of PDRN |
| 34832885 | *Pharmaceuticals* 2021 | Review | PDRN for impaired wound healing |
| 37350391 | *Mol Med Rep* 2023 | Bench | PDRN/ERK in keratinocytes & fibroblasts |

**Verdict:** Level 1–2 exists, but most PDRN evidence is wound-healing / orthopaedic, not facial aesthetics. Flag as "borrowed evidence" and grade the aesthetic-specific claims lower (Level 3–4).

### Pillar 3 — Biomimetic peptides (WEAKEST)

| PMID | Journal / Year | PubMed tag | Notes |
|---|---|---|---|
| 40565185 | *Int J Mol Sci* 2025 | Review | Acetyl Hexapeptide-8: skin permeability & efficacy |
| 41384336 | *J Cosmet Dermatol* 2025 | Journal Article | Recombinant human collagen peptide, **in vitro** biomimetic skin model |

**Verdict:** Level 5. A search for `(biomimetic peptide*) AND (skin OR collagen OR cosmetic)` returns mostly unrelated literature — the term is **not an established dermatological literature term**. No systematic reviews, no RCTs. Present as a research frontier, not a protocol.

---

## 2. Citations to REMOVE before launch

| PMID | Issue |
|---|---|
| **38481069** | *"Skin boosters: Definitions and varied classifications"* (*Skin Res Technol* 2024) is tagged **RETRACTED PUBLICATION** in PubMed. It is the most commonly cited "skin booster" classification paper in this space, so it is an easy accidental citation. Remove if present. |

---

## 3. Claims to correct before launch

1. **"47 citations, 22 RCTs, 8 systematic reviews"** (Club page, echoed in curriculum copy). Publicly auditable sample of 32 PMIDs yields **5 RCT-tagged (16%) and 3 SR/MA-tagged (9%)** — well below the claimed 47% / 17%. Publish the real itemised breakdown instead of the total.
2. **"ExoLase™"** — `EXOLASE` is a **registered USPTO trademark of BTL Industries** (registered 2025); `EXOLASE ONE` is pending (2026). BTL is a 5,000-employee equipment manufacturer; its EXOLASE ONE is a fused **erbium** laser (1540nm Er:Glass + 2940nm Er:YAG), unrelated to exosomes. A thulium-based protocol using this name creates trademark exposure and undermines the "manufacturer-independent" positioning. Get a trademark search done before the term is embedded in a paid product.
3. **ExoLase legs are asymmetric** — the thulium leg has a directly on-point RCT (**PMID 29340854**, 1927nm fractionated thulium laser for pattern hair loss, evaluator-blinded split-scalp); the exosome leg has no RCT and no approved product. Grade accordingly: Level 2 laser + Level 5 exosome.

---

## 4. Indexing / AI-discovery checklist

The site is explicitly built for AI-search citation (`llms.txt`, `llms-full.txt`, `.md` endpoints, robots.txt open to AI crawlers). The new page must land in all of these or that investment is wasted:

- [ ] Page appears in `/sitemap-pages.xml`
- [ ] Entry added to `/llms.txt` with description
- [ ] Entry added to `/llms-full.txt`
- [ ] `.md` endpoint resolves (append `.md` to the URL)
- [ ] Listing published on the Lemon Squeezy storefront (currently 17 products, none matching)
- [ ] Listing published on the DermaRoom Collective partner store
- [ ] JSON-LD `Course` / `Product` schema with `offers`, `provider`, `hasCourseInstance`
- [ ] Internal links from `/curriculum/`, `/store/`, `/pricing/`, `/hair-masterclass/`

---

## 5. Disclosure additions

- **DermaRoom adjacency:** the partner storefront carries a *"Nouvaderm Thulium Laser"* webinar under an **"Industry Supplied Courses"** category. The hair masterclass teaches thulium 1927nm protocols and is sold through that same storefront. Nouvaderm is a laser manufacturer. One disclosure line neutralises the apparent adjacency.
- **Publish the reference list.** A `/references/` page with all citations, PubMed links and OCEBM levels is the single highest-value trust signal available and costs nothing but disclosure.
- **Study-level vs educator-level independence.** Several cited RCTs (e.g. oral collagen peptide trials) are the class of study typically manufacturer-funded. State plainly that independence is claimed at the level of *who pays the educator*, not *who funded each trial*.

---

## 6. Open items requiring founder input

- [ ] The 47-item reference list from *Board Review Essentials* — needed to complete the full classification
- [ ] Decision on `ExoLase` naming (retain with legal clearance, or rename by mechanism)
- [ ] Decision on publishing OCEBM levels on-page per protocol
- [ ] Willingness to publish the corrected RCT/SR breakdown if the count comes in below 22/8

