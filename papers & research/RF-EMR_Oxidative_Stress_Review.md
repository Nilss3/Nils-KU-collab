# RF-EMR and Oxidative Stress — Literature Review

**Scope:** Radiofrequency electromagnetic radiation (RF-EMR) from mobile phones (GSM, 900/1800/2100 MHz, 4G/5G) and Wi-Fi (2.4/5 GHz) as inducers of oxidative stress — mechanisms, experimental evidence, antioxidant mitigation, and critical appraisal.

**Anchor study:** Yüksel et al. 2016 (PMID 26578367)
**Papers reviewed:** 14 primary + 6 supporting
**Biomarkers covered:** MDA · 8-OHdG · GSH · GSH-Px · SOD · CAT · TOS · ROS
**Compiled:** From PubMed-indexed literature

---

## 1. Executive Summary

Radiofrequency electromagnetic radiation in the 900 MHz – 5 GHz band — emitted by mobile phones, Wi-Fi routers, and base stations — induces oxidative stress in biological tissues at exposure intensities below the ICNIRP thermal threshold. The mechanism is **non-thermal**: low-energy photons cannot ionize water or break covalent bonds, but they perturb cell-membrane voltage-sensitive proteins, producing reactive oxygen species (ROS) through endogenous enzymatic pathways.

A 2016 review by [Yakymenko et al.](https://pubmed.ncbi.nlm.nih.gov/26151230/) found that **93 of 100** experimental studies (1995–2015) reported elevated oxidative-stress markers after RF exposure. The [Schuermann & Mevissen 2021 review](https://pmc.ncbi.nlm.nih.gov/articles/PMC8038719/) confirmed the same direction-of-effect across in-vivo, in-vitro, and human studies. The WHO-commissioned [Meyer et al. 2024 systematic review](https://doi.org/10.1016/j.envint.2024.108940) of 100+ animal and 200+ in-vitro studies found consistent oxidative responses in testis, thymus, and plasma — but graded overall certainty as "very low" because of dosimetry and blinding limitations.

**Five non-thermal mechanisms** are best-supported:

1. **Voltage-gated calcium channel (VGCC) activation** ([Pall 2013](https://pubmed.ncbi.nlm.nih.gov/23802593/)) — the most extensively characterised pathway; L-type VGCC blockers abolish RF effects in 23/23 reviewed studies.
2. **NADPH oxidase (NOX) activation** ([Georgiou & Margaritis 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8470280/)) — the membrane-bound gp91phox subunit is intrinsically voltage-sensitive.
3. **Mitochondrial Complex III electron leak** ([Houston 2018](https://pmc.ncbi.nlm.nih.gov/articles/PMC6160547/)) — direct experimental evidence for the dominant ROS source in 1.8 GHz-exposed germ cells.
4. **Fenton chemistry** — converts H₂O₂ into the proximal oxidant •OH (hydroxyl radical) via transition-metal catalysis.
5. **Ion forced-oscillation by ELF components** ([Panagopoulos 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8562392/)) — predicts that pulsed/modulated mobile signals are more bioactive than continuous-wave laboratory signals.

**Water radiolysis is not a viable RF-EMR mechanism.** A 1 GHz photon carries ~4 × 10⁻⁶ eV — roughly nine orders of magnitude below water's 12.6 eV ionization threshold. Hydroxyl radicals arise via the indirect Fenton route, not direct photolysis.

**Antioxidant rescue is consistently demonstrated.** Melatonin, vitamins E and C, folic acid, N-acetylcysteine, and penicillamine all attenuate RF-EMR-induced damage in rodent and cell models — confirming the ROS-mediated nature of the effect.

**Bottom line.** A coherent biochemical case exists for non-thermal RF-induced oxidative stress, but methodological weaknesses — inconsistent dosimetry, sparse blinding, partially non-specific assays, and limited multi-lab replication — keep formal certainty low. Independent replication with rigorous SAR characterisation is the principal open need.

---

## 2. Anchor Study — Yüksel et al. (2016)

**Citation.** Yüksel M, Nazıroğlu M, Özkaya MO. Long-term exposure to electromagnetic radiation from mobile phones and Wi-Fi devices decreases plasma prolactin, progesterone, and estrogen levels but increases uterine oxidative stress in pregnant rats and their offspring. *Endocrine.* 2016;52(2):352–362. PMID: [26578367](https://pubmed.ncbi.nlm.nih.gov/26578367/). DOI: 10.1007/s12020-015-0795-3.

| Parameter | Value |
|---|---|
| Model | Wistar rats — 32 pregnant dams + 40 offspring |
| Tissue | Uterus (primary); maternal plasma (hormones) |
| Exposure sources | Mobile phone GSM 900 MHz · 1800 MHz · Wi-Fi 2450 MHz |
| Duration | 60 min/day across pregnancy + postnatal growth; 52 weeks, four generations |
| Groups | Control · 900 MHz · 1800 MHz · 2450 MHz (n = 8 per group) |
| Design | Double-blind |
| Key markers | MDA (lipid peroxidation), GSH-Px, TOS, prolactin, progesterone, estrogen, body temperature |

**Findings.** All three RF-EMR frequencies produced uterine lipid peroxidation, reduced uterine GSH-Px in developing offspring (weeks 4–5), elevated maternal total oxidant status (TOS), small but significant body-temperature rises, and reduced plasma prolactin, progesterone, and estrogen in dams. Reduced glutathione, total antioxidants, and vitamins A/C/E were unchanged. The proposed mechanism is **TRPV1 cation-channel gating** linked to mitochondrial ROS leak — consistent with the Complex III mechanism characterised later by Houston et al.

**Significance.** One of the few multi-frequency, multi-generation, blinded designs in the literature. Directly relevant to pregnancy and reproductive health.

**Caveats.** Sample sizes per group are modest. Body-temperature increases — though small — complicate the "purely non-thermal" interpretation. The TRPV1 mechanism is hypothesised, not directly demonstrated in this paper.

---

## 3. Comparison Table — 14 Studies

| # | Study | Year | Model | RF source | Frequency | SAR / power | Duration | Key oxidative markers | Direction |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Yüksel et al. | 2016 | Pregnant Wistar rats | Mobile + Wi-Fi | 900 / 1800 / 2450 MHz | n.r. | 60 min/d, 52 wk | MDA, TOS ↑; GSH-Px ↓ | Positive |
| 2 | Yakymenko et al. (review of 100 studies) | 2016 | All | All | 800 MHz – 5 GHz | < ICNIRP | Variable | 93/100 studies positive | Positive |
| 3 | Schuermann & Mevissen (review) | 2021 | All | All RF + ELF | 900 MHz – 2.1 GHz | 0.005–1.2 W/kg | Multiple | MDA, 8-OHdG ↑; GSH ↓ | Positive |
| 4 | Pall (review) | 2013 | All | All EMF | All | All | All | VGCC activation framework | Mechanistic |
| 5 | Georgiou & Margaritis (review) | 2021 | Cell + animal | Mobile + WiFi | All RF | All | All | NOX activation; ROS ↑ | Mechanistic |
| 6 | Houston et al. | 2018 | Mouse germ cells (GC2, GC1-spg) + spermatozoa | Mobile phone | 1.8 GHz | 0.15, 1.5 W/kg | 0–6 h | Mito-ROS ↑; lipid perox ↑ | Positive |
| 7 | Panagopoulos et al. (review) | 2021 | All | Mobile phone | 900 MHz – 5 GHz | All | All | Ion forced-oscillation → VGIC dysregulation | Mechanistic |
| 8 | Pooam, Ahmad et al. | 2022 | HEK293 cells | Generator | 1.8 GHz | −8.5 to −67 dBm | 15 min | ROS ↑ (hormetic) | Positive (hormetic) |
| 9 | Salameh / Daher et al. | 2023 | Fetal rat liver | GSM 900 MHz | 900 MHz | 0.768 W/kg | 24 h/d, prenatal | MDA ↑; SOD/CAT ↓ | Positive |
| 10 | Shokri et al. | 2021 | Mouse testis | Mobile phone | 900 MHz | n.r. | 4 h/d, 30 d | MDA ↑; GSH/GPx ↓ (rescued by melatonin) | Positive |
| 11 | Kıvrak et al. (review) | 2017 | Multiple tissues | All RF | 900 MHz – 2.45 GHz | n.r. | Variable | Antioxidant defence ↓ | Positive |
| 12 | Alkış et al. | 2019 | Rat brain | Mobile-bands | 900 / 1800 / 2100 MHz | 0.04–0.085 W/kg | 6 months | 8-OHdG, MDA ↑ (2100 MHz strongest) | Positive |
| 13 | Lee et al. | 2018 | Aging C57BL/6 mouse brain | UMTS | 1950 MHz | ≈0.4 W/kg | 8 months | No significant OS change | Negative |
| 14 | Meyer et al. (WHO systematic review) | 2024 | All | All RF | All telecoms bands | All | All | Consistent in testis, thymus, plasma; low certainty | Mixed |

n.r. = not reported.

---

## 4. Mechanisms — Diagram and Synthesis

> **Figure 1.** Proposed non-thermal pathways from RF-EMR exposure to oxidative damage. Five membrane / enzyme targets — VGCC activation, NADPH oxidase, TRPV1, mitochondrial Complex III, and ELF ion-forced-oscillation — feed into a ROS pool dominated by superoxide and H₂O₂. Fenton chemistry produces the hydroxyl radical, the proximal driver of lipid peroxidation, DNA oxidation, and protein nitration. Antioxidant rescue (melatonin, vitamins E/C, NAC, folic acid, penicillamine) attenuates damage in animal models.

![Mechanism diagram](mechanism_diagram.png)

### 4.1 Voltage-Gated Calcium Channels (Pall framework)

The most extensively characterized non-thermal mechanism is voltage-gated calcium channel (VGCC) activation, articulated by [Pall (2013)](https://pubmed.ncbi.nlm.nih.gov/23802593/). The S4 voltage sensor of the channel carries roughly 20 positive charges; in Pall's biophysical estimate, the membrane's electrical resistance and high dielectric constant amplify the effective force on this sensor by ~7 × 10⁶-fold relative to a charge in bulk cytoplasm. Activated VGCCs raise intracellular Ca²⁺, which stimulates Ca²⁺/calmodulin-dependent NOS isoforms, increasing nitric oxide (NO). NO reacts with simultaneously elevated O₂•⁻ to form peroxynitrite (ONOO⁻), a potent oxidant that produces 3-nitrotyrosine, lipid peroxidation, and single-strand DNA breaks.

In 23 reviewed studies, L-type VGCC blockers (verapamil, nifedipine) abolished EMF effects — the strongest single line of mechanistic evidence. Critics note that the amplification calculation depends on contested biophysical assumptions and that calcium-channel blockers are not perfectly specific.

### 4.2 NADPH Oxidase (Georgiou–Margaritis framework)

[Georgiou & Margaritis (2021)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8470280/) argue that NADPH oxidase (NOX) is the primary plasma-membrane ROS generator. NOX contains gp91phox, which functions as an associated voltage-gated H⁺ channel — making the enzyme inherently voltage-sensitive. Electromagnetic perturbation of membrane potential activates the NADPH → FAD → haem → O₂ electron-transfer chain, releasing O₂•⁻ that is dismutated to H₂O₂.

Experimental support includes a 3-fold NOX-derived ROS increase in HeLa cells exposed to 875 MHz at 0.240 mW/cm² (about four-fold below ICNIRP), and rapid (15-minute) NOX-2 transcriptional upregulation in HEK293 cells at 1.8 GHz. NOX and VGCC mechanisms are not mutually exclusive — Ca²⁺ from VGCC activation directly stimulates NOX through Rac1 GTPase, creating a feed-forward loop.

### 4.3 Mitochondrial Complex III

[Houston et al. (2018)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6160547/) provide direct in-vitro evidence that Complex III of the mitochondrial electron-transport chain is the dominant ROS source in 1.8 GHz-exposed germ cells. Antimycin A (a Complex III Qᵢ-site inhibitor) potentiated RF-induced ROS, while Complex II substrate entry did not increase ROS. The selectivity for germ cells over somatic cells in the same study is striking and likely reflects germ-cell mitochondrial density and antioxidant capacity differences. The Yüksel 2016 TRPV1 / mitochondrial-pore mechanism is consistent with this site of leak.

### 4.4 Fenton Chemistry — How H₂O₂ Becomes •OH

H₂O₂ is itself a relatively mild oxidant. Its toxicity arises through transition-metal-catalysed conversion to hydroxyl radical:

\[ \mathrm{Fe^{2+} + H_2O_2 \rightarrow Fe^{3+} + {\cdot}OH + HO^-} \]

Superoxide can regenerate Fe²⁺ from Fe³⁺ (Haber–Weiss cycle), sustaining •OH production. In bicarbonate-rich cellular environments, the carbonate radical (CO₃•⁻) becomes the terminal active oxidant and is mobile enough to migrate from membrane sites to nuclear DNA, producing 8-oxo-7,8-dihydroguanine (the precursor of 8-OHdG). This mechanism does not require any novel biophysical interaction — it depends only on the initial RF-induced O₂•⁻ and H₂O₂ pool.

### 4.5 Ion Forced-Oscillation (Panagopoulos framework)

[Panagopoulos et al. (2021)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8562392/) argue that the bioactive component of mobile-phone RF is not the GHz carrier but the polarized, coherent ELF components arising from amplitude modulation, pulsing, and digital encoding (e.g. the 217 Hz GSM frame, the 8.34 Hz TDMA repetition). These ELF-frequency oscillating forces drive synchronous ion movements across membranes that systematically open and close voltage-gated ion channels (VGICs). The hypothesis predicts that real-world pulsed/modulated mobile signals are more bioactive than laboratory continuous-wave signals — a prediction consistent with several experimental observations.

### 4.6 The Water-Radiolysis Question

> **Critical appraisal.** Water radiolysis is **not** a viable RF-EMR mechanism. Direct radiolysis (O–H bond cleavage to form •OH and H•) is well established for *ionizing* radiation — gamma rays, X-rays, high-energy particles — where individual photons carry > 12 eV, sufficient to ionize water. A 1 GHz photon carries about 4 × 10⁻⁶ eV — roughly nine orders of magnitude below water's ionization threshold (~12.6 eV) and well below even the O–H bond dissociation energy (~5.1 eV). No single RF photon, and no plausible multi-photon pathway at the intensities relevant to mobile or Wi-Fi exposure, can break chemical bonds in water.
>
> The primary mechanistic literature reviewed here does not actually invoke water radiolysis; •OH appears via the indirect Fenton route. Loose phrasing such as "radiolysis-like effects" in the popular literature should be treated as imprecise — the demonstrated pathway is **membrane perturbation → enzyme activation → superoxide → Fenton → •OH**.

---

## 5. Dose-Response Patterns

A consistent finding across [Yakymenko et al. (2016)](https://pubmed.ncbi.nlm.nih.gov/26151230/), [Pooam/Ahmad et al. (2022)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8816398/), and [Schuermann & Mevissen (2021)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8038719/) is that RF-EMR oxidative dose–response relationships are **non-linear**. The 2022 HEK293 study explicitly demonstrated hormesis: medium amplitudes (around −31 dBm) produced the largest ROS response, while very low and very high amplitudes produced smaller or absent effects. Schuermann & Mevissen note that OS markers can recover within 30 days of exposure cessation in rats, and that prior low-dose exposure can induce an adaptive antioxidant response.

| Study | Frequency | SAR / power | Duration | Dose-response shape |
|---|---|---|---|---|
| Pooam/Ahmad 2022 | 1.8 GHz | −8.5 to −67 dBm | 15 min | Non-linear / hormetic; max at intermediate amplitude |
| Alkış 2019 | 900/1800/2100 MHz | 0.04–0.085 W/kg | 6 months | Monotonic vs. sham; 2100 MHz strongest |
| Houston 2018 | 1.8 GHz | 0.15, 1.5 W/kg | 0–6 h | Germ-cell-selective; ↑ at 0.15 W/kg |
| Daher 2023 | 900 MHz GSM | 0.768 W/kg (liver) | 24 h/d, prenatal | Stage-dependent; MDA peak at 15.5 dpc |
| Lee 2018 | 1950 MHz UMTS | ≈0.4 W/kg | 8 months | No significant change (aging mouse brain) |
| Schuermann 2021 | 900–2100 MHz | 0.005–1.2 W/kg | 2 h/d – 6 mo | Dose- & duration-dependent; recovery after 30 d |

**Table 2.** Dose-response patterns across the reviewed studies.

**Key observations.** Most positive in-vivo findings occur at SAR levels well below regulatory limits. Null and positive results coexist within the same tissue type depending on species, age, exposure waveform (CW vs. modulated), and outcome timing. Recovery after exposure cessation suggests reversible rather than irreversible OS — biologically plausible for an ROS-mediated effect.

---

## 6. Antioxidant Mitigation

Antioxidant rescue is a recurring design pattern: pre-treating animals with a defined antioxidant attenuates RF-EMR-induced damage, providing simultaneous evidence that (a) the effect is real and (b) it is mediated by ROS rather than by some non-redox mechanism.

| Antioxidant | Model | RF exposure | Markers rescued | Mechanism |
|---|---|---|---|---|
| Melatonin (2 mg/kg i.p.) | Mouse testis (in vivo) | 900 MHz · 4 h/d · 30 d | MDA ↓, GSH ↑, histology ✓ | Radical scavenger; SOD/CAT induction; NRF2 |
| Melatonin | Rat testis | 2.45 GHz · 60 min/d · 30 d | Lipid perox ↓, GSH ↑, GPx ↑, vit E ↑ | Lipo- & hydrophilic free-radical scavenger |
| Vitamin E + C | Rat endometrium | 900 MHz | MDA ↓, OS markers ✓ | Membrane lipid peroxidation chain-break + recycling |
| Vitamin E | Rat brain / testis | 900 MHz | Lipid perox ↓, cell damage ↓ | α-tocopherol chain-breaking antioxidant |
| Folic acid | Rat cerebellum / kidney | Various RF | Cell counts ✓, CAT/GPx ✓ | One-carbon metabolism, antioxidant cofactor |
| Penicillamine | Mouse germ cells (in vitro) | 1.8 GHz · 0.15 W/kg | Mito-ROS ↓ (GC2) | Thiol antioxidant; Cu chelator |
| Vitamin C | Rat cornea / lens | Various RF | Tissue OS ↓ | Hydrophilic scavenger; recycles vitamin E |

**Table 3.** Antioxidant rescue experiments in RF-EMR oxidative-stress models.

**Melatonin is the most extensively studied protective agent.** Beyond direct radical scavenging, it activates NRF2 to upregulate endogenous antioxidants and is unique in being effective in both lipid and aqueous compartments, including the nucleus. The [Shokri et al.](https://onlinelibrary.wiley.com/doi/10.1111/and.13834) mouse testicular study shows clear restoration of MDA, GSH, and germinal-epithelial thickness. Older work from the Nazıroğlu group reports similar protection at 2.45 GHz. Vitamin E (and combinations with vitamin C) prevent endometrial and brain lipid peroxidation. N-acetylcysteine is widely used as a confirmatory tool for the oxidative mechanism. Penicillamine, a thiol antioxidant and copper chelator, attenuates 1.8 GHz mitochondrial ROS in spermatogenic cells in vitro ([Houston 2018](https://pmc.ncbi.nlm.nih.gov/articles/PMC6160547/)).

---

## 7. Research Gaps and Skeptical Perspectives

### 7.1 Methodological concerns

- **Dosimetry and SAR characterization.** Many positive studies do not report SAR; where reported, values are often estimated rather than directly measured. The [Meyer et al. WHO systematic review](https://doi.org/10.1016/j.envint.2024.108940) identifies "inaccurate measurement of exposure" as the principal driver of its very-low-certainty rating.
- **Blinding and sham controls.** Few studies blind handlers and outcome assessors. Sham controls that use restraint holders without RF — as in Yüksel 2016 — may not separate restraint stress from RF effects.
- **Temperature confounding.** RF absorption causes some tissue heating even at sub-thermal SAR. Real-time temperature monitoring during exposure is uncommon.
- **Assay specificity.** TBARS for MDA, 8-OHdG ELISAs, and DCFH-DA fluorescence are all known to be partially non-specific. Validated mass-spectrometry methods are rarely used.
- **Publication bias.** Yakymenko's 93% positive rate likely reflects publication bias to some degree; null results are systematically under-reported in the EMF field.
- **Heterogeneity and replication.** For the same tissue and biomarker, Meyer et al. report SMDs ranging from −3.4 to +5.3 — an effect-direction reversal of more than 8 SMD units. Most positive findings come from a small number of research clusters; independent replication is rare.

### 7.2 ICNIRP and WHO position

The 2020 ICNIRP guidelines maintain exposure limits based on established thermal effects (preventing tissue temperature rises > 1 °C). ICNIRP's stated position is that evidence for non-thermal adverse effects, including oxidative stress, is inconsistent and methodologically limited and does not justify changing limits. WHO has not classified RF-EMR above IARC Group 2B ("possibly carcinogenic") — a category that requires only "limited evidence".

Critics — Hardell, Miller, Yakymenko, Pall, Panagopoulos — argue that the thermal-only paradigm is a fundamental error, that SAR-based limits cannot protect against non-thermal mechanisms, and that the systematic positive signal across the OS literature cannot be explained by methodology alone. The IARC 2B classification is itself a formal acknowledgment of evidence for harm; many researchers argue the 2024 Meyer review's finding of consistent (if low-certainty) signals in testis, thymus, and plasma supports re-examination of regulatory limits rather than continued reliance on thermal endpoints.

### 7.3 Translational and frequency-specific gaps

All in-vivo studies use whole-body rodent exposure, producing dosimetry quite different from human phone-to-head exposure. In-vitro studies use immortalized cell lines exposed to continuous-wave RF for hours, which does not reflect real pulsed/modulated mobile signals. The mechanistic and experimental literature is essentially empty for millimetre-wave 5G (24–100 GHz), where tissue penetration is limited to skin and ocular surfaces and where the VGCC and NOX hypotheses have not been tested.

---

## 8. Bibliography

1. Yakymenko I, Tsybulin O, Sidorik E, Henshel D, Kyrylenko O, Kyrylenko S. Oxidative mechanisms of biological activity of low-intensity radiofrequency radiation. *Electromagn Biol Med.* 2016;35(2):186–202. PMID: 26151230. [pubmed.ncbi.nlm.nih.gov/26151230](https://pubmed.ncbi.nlm.nih.gov/26151230/)
2. Schuermann D, Mevissen M. Manmade electromagnetic fields and oxidative stress — biological effects and consequences for health. *Int J Mol Sci.* 2021;22(7):3772. PMID: 33917298. [pmc.ncbi.nlm.nih.gov/articles/PMC8038719](https://pmc.ncbi.nlm.nih.gov/articles/PMC8038719/)
3. Meyer F, Bitsch A, Forman H, et al. The effects of radiofrequency electromagnetic fields on biomarkers of oxidative stress in vivo and in vitro: A systematic review of experimental studies. *Environ Int.* 2024;191:108940. [doi.org/10.1016/j.envint.2024.108940](https://doi.org/10.1016/j.envint.2024.108940)
4. Pall ML. Electromagnetic fields act via activation of voltage-gated calcium channels to produce beneficial or adverse effects. *J Cell Mol Med.* 2013;17(8):958–965. PMID: 23802593. [pubmed.ncbi.nlm.nih.gov/23802593](https://pubmed.ncbi.nlm.nih.gov/23802593/)
5. Georgiou CD, Margaritis LH. Oxidative stress and NADPH oxidase: connecting electromagnetic fields, cation channels and biological effects. *Int J Mol Sci.* 2021;22(18):10041. PMID: 34576203. [pmc.ncbi.nlm.nih.gov/articles/PMC8470280](https://pmc.ncbi.nlm.nih.gov/articles/PMC8470280/)
6. Houston BJ, Nixon B, King BV, Aitken RJ, De Iuliis GN. Probing the origins of 1,800 MHz radio frequency electromagnetic radiation induced damage in mouse immortalized germ cells and spermatozoa in vitro. *Front Public Health.* 2018;6:270. PMID: 30298125. [pmc.ncbi.nlm.nih.gov/articles/PMC6160547](https://pmc.ncbi.nlm.nih.gov/articles/PMC6160547/)
7. Panagopoulos DJ, Karabarbounis A, Yakymenko I, Chrousos GP. Human-made electromagnetic fields: Ion forced-oscillation and voltage-gated ion channel dysfunction, oxidative stress and DNA damage (Review). *Int J Oncol.* 2021;59(5):92. PMID: 34558651. [pmc.ncbi.nlm.nih.gov/articles/PMC8562392](https://pmc.ncbi.nlm.nih.gov/articles/PMC8562392/)
8. Shokri M, Shamsaei ME, Malekshah AK, Amiri F. The protective effect of melatonin on radiofrequency electromagnetic fields of mobile phone-induced testicular damage in an experimental mouse model. *Andrology.* 2021;9(2):613–620. [onlinelibrary.wiley.com/doi/10.1111/and.13834](https://onlinelibrary.wiley.com/doi/10.1111/and.13834)
9. Kıvrak EG, Yurt KK, Kaplan AA, Alkan I, Altun G. Effects of electromagnetic fields exposure on the antioxidant defense system. *J Microsc Ultrastruct.* 2017;5(4):167–176. PMID: 30023251. [pmc.ncbi.nlm.nih.gov/articles/PMC6025786](https://pmc.ncbi.nlm.nih.gov/articles/PMC6025786/)
10. Pooam M, Jourdan N, Aguida B, Dahon C, Baouz S, Terry C, Raad H, Ahmad M. Exposure to 1.8 GHz radiofrequency field modulates ROS in human HEK293 cells as a function of signal amplitude. *Commun Integr Biol.* 2022;15(1):54–66. PMID: 35126804. [pmc.ncbi.nlm.nih.gov/articles/PMC8816398](https://pmc.ncbi.nlm.nih.gov/articles/PMC8816398/)
11. Yüksel M, Nazıroğlu M, Özkaya MO. Long-term exposure to electromagnetic radiation from mobile phones and Wi-Fi devices decreases plasma prolactin, progesterone, and estrogen levels but increases uterine oxidative stress in pregnant rats and their offspring. *Endocrine.* 2016;52(2):352–362. PMID: 26578367. [pubmed.ncbi.nlm.nih.gov/26578367](https://pubmed.ncbi.nlm.nih.gov/26578367/)
12. Alkış ME, Bilgin HM, Akpolat V, Dasdag S, Yeğin K, Yavaş M, Akdağ M. Effect of 900-, 1800-, and 2100-MHz radiofrequency radiation on DNA and oxidative stress in brain. *Electromagn Biol Med.* 2019;38(1):32–47. [doi.org/10.1080/15368378.2019.1567526](https://doi.org/10.1080/15368378.2019.1567526)
13. Salameh M, Zeitoun-Ghandour S, Sabra L, Daher A, Khalil M, Joumaa WH. Impact of GSM-EMW exposure on the markers of oxidative stress in fetal rat liver. *Sci Rep.* 2023;13:17806. PMID: 37853153. [pmc.ncbi.nlm.nih.gov/articles/PMC10584814](https://pmc.ncbi.nlm.nih.gov/articles/PMC10584814/)
14. Lee HJ, Choi HD, Pack JK, Han NK, Kim N, Jeong YJ, Son Y, Lee YS. Impact of long-term RF-EMF on oxidative stress and neuroinflammation in aging brains of C57BL/6 mice. *Int J Mol Sci.* 2018;19(7):2103. [mdpi.com/1422-0067/19/7/2103](https://www.mdpi.com/1422-0067/19/7/2103)
15. Pall ML. Microwave frequency electromagnetic fields produce widespread neuropsychiatric effects including depression. *J Chem Neuroanat.* 2016;75(Pt B):43–51. PMID: 26300312. [pubmed.ncbi.nlm.nih.gov/26300312](https://pubmed.ncbi.nlm.nih.gov/26300312/)
16. Dasdag S, Akdağ MZ. The link between radiofrequencies emitted from wireless technologies and oxidative stress. *J Chem Neuroanat.* 2016;75(Pt B):85–93. [doi.org/10.1016/j.jchemneu.2015.09.001](https://doi.org/10.1016/j.jchemneu.2015.09.001)
17. Oksay T, Nazıroğlu M, Doğan S, Güzel A, Gümral N, Koşar PA. Protective effects of melatonin against oxidative injury in rat testis induced by wireless (2.45 GHz) devices. *Andrologia.* 2014;46(1):65–72. [onlinelibrary.wiley.com/doi/10.1111/and.12044](https://onlinelibrary.wiley.com/doi/10.1111/and.12044)
18. Henschenmacher B, Bitsch A, de las Heras Gala T, et al. The effect of radiofrequency electromagnetic fields on biomarkers of oxidative stress in vivo and in vitro: A protocol for a systematic review. *Environ Int.* 2022;158:106932. [pmc.ncbi.nlm.nih.gov/articles/PMC8668870](https://pmc.ncbi.nlm.nih.gov/articles/PMC8668870/)
19. Talbi O, Zadeh-Haghighi H, Simon C. The radical pair mechanism cannot explain telecommunication frequency effects on reactive oxygen species. *arXiv:2407.03358.* 2024. [arxiv.org/abs/2407.03358](https://arxiv.org/abs/2407.03358)
20. International Commission on Non-Ionizing Radiation Protection (ICNIRP). Guidelines for limiting exposure to electromagnetic fields (100 kHz to 300 GHz). *Health Phys.* 2020;118(5):483–524. [icnirp.org/cms/upload/publications/ICNIRPrfgdl2020.pdf](https://www.icnirp.org/cms/upload/publications/ICNIRPrfgdl2020.pdf)

---

*Compiled from PubMed-indexed literature · Perplexity Computer · 2026*
