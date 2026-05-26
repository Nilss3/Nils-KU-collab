# Age Verification in Europe

**A two-track answer — narrow verification for porn and gambling; design regulation, not identity regulation, for social media and games**
**This paper is an opinion piece and research by Nils and does not reflect any position of Kids Unplugged.**

*Geographic scope: European Union · Version 3 — the "red light district / fix the design" thesis · As of May 2026*

---

**In short:** keep age verification limited to the 'red light district' of the internet where scope is clear and there is little spill-over. For social media and games, outright **ban the addictive design**. Ban it entirely from the European market until proven safe for kids and adults. This should be combined with delaying smartphones for teens in order to preserve their prefrontal cortex. 

## Executive summary

The European debate on age verification has been running two separate problems together — porn and gambling on one side, social media, games and the open internet on the other — under one set of policy instruments. That has produced an emerging regime that protects children from pornography somewhat, protects them from algorithmic and game-design harm not at all and could identify every adult European in the process. Moreover, the proposed solutions depend on Google and Apple attestation chains that force you have a smartphone if you want to make use of them, exclude opensource (Linux and degoogled Android) and desktop operating systems, and is being stacked next to Chat Control and the ProtectEU / VPN-restriction agenda in a way that constitutes a regime change in how Europeans use the internet. This report argues for a different answer: keep age verification narrow, and fix the algorithmic and game-design harm at its source.


### The thesis in two sentences

> **Track 1 — Age verification stays in the red-light district of the internet.** Pornography and online gambling, plus the existing 18+ categories with online analogues (alcohol, tobacco, vape, certain medications). Narrow scope. Best-in-class architecture (EUDI mini-wallet done properly, France's double-anonymity as the hard floor). Statutory firewalls against scope creep, against Chat Control reuse, and against VPN restrictions justified on age-verification grounds.

> **Track 2 — For social media, games, and the rest of the open internet, no age verification at all but a ban on addictive design.** Enforce the legislation Europe already has. The Digital Services Act prohibits dark patterns (Article 25), demands recommender opt-out (Article 38), requires protection of minors (Article 28). The AI Act prohibits manipulative techniques (Article 5). The Unfair Commercial Practices Directive bars aggressive interface design. Belgium's Gaming Commission has held since 2018 that loot boxes are gambling. These tools exist; the gap is enforcement. Banish addictive design (e.g. engagement-maximising recommenders, infinite scroll, autoplay, streak gamification, public-by-default profiles, notification re-engagement loops, loot boxes and gacha mechanics, daily-login streaks, energy and stamina systems, pay-to-progress aimed at minors) until the platforms fix it. The mechanism is already in the DSA: interim measures (Article 73), fines up to 6% of global turnover (Article 74), and temporary access restrictions (Article 76) for persistent serious breach. The result is an internet that is better for everyone, including adults, and no European has to identify themselves to read, post, or play.

### Why this division is the right one

Porn and gambling are content-bounded categories in a specific 'corner' of the internet, you don't need those in daily life. There is no specific design choice that makes them harmful. They just are. Full stop. Social media and games are different in the sense that they are used as a general-purpose news and communication platforms by anyone. However, there is no need for an addictive algorithm. The harm to a fourteen-year-old is overwhelmingly the same harm an adult experiences, only acquired faster and on a more vulnerable brain. **The harm is in the design, not in the existence of the service. Regulating the design protects everyone; gating access by identity protects no one fully and can very easily lead to an internet which is censored and controlled, destroying freedom of speech. In fact, the § 188 StGB legislation in Germany is a prime example.**

### What this approach gets that the current trajectory does not

- **Children get more protection, not less.** The features that addict them are removed for everyone. Identifying children and walling them off is ineffective (sibling devices, shared accounts, school Wi-Fi, public computers, parents' phones) and intrusive. 
- **Adults are also protected.** Algorithmic addiction is not an under-18 disease. The current debate ignores adult harm because age verification is the only tool on the table.
- **No mass identification.** Pseudonymous browsing, anonymous reading, journalist source protection, abuse-survivor anonymity, LGBTQ+ youth in hostile households, ordinary political speech — all preserved.
- **No encryption back door.** Chat Control's premise (the device is a state enforcement point) is decoupled from the social-media question.
- **No VPN restriction.** There is no bypass to close because there is no identity check on social media. The May 2026 Virkkunen statement and the EPRS "loophole" framing lose their argumentative ground.
- **No Linux exclusion.** The Play Integrity / App Attest duopoly dependency is irrelevant for social media; a Linux desktop user remains a first-class citizen of the European internet. For Track 1, a separate non-eID adult escape hatch is required regardless.
- **Mostly no new regulation.** The DSA exists. The AI Act exists. The UCPD exists. The EDPB has spoken. The IEEE 2089.1 / 5Rights / ICO Age-Appropriate Design Code framework already operationalises this. The bottleneck is enforcement, not legislation.
- **Reversibility.** If after five years the evidence shows design regulation has not reduced minor harm, the regime can be tightened. The age-verification regime is much harder to roll back, both technically (the credentials exist) and politically (no government wants to be seen unprotecting children).
- **The Brussels Effect works for us.** Platforms tend to comply globally with the strictest mandatory jurisdiction; mandatory addictive-design defaults in the EU often become the global product.

---

## 1. The legal landscape (Europe, May 2026)

Across Europe, age verification has moved from policy debate to live infrastructure in eighteen months. The UK Online Safety Act enforcement turned on in summer 2025. France enforces a "double anonymity" standard for porn sites since April 2025. Germany began payment-blocking enforcement on 1 December 2025. The European Commission's age-verification "mini-wallet" became feature-ready on 15 April 2026 and was bypassed in under two minutes by a security researcher days later. Member States are told to roll the wallet out by the end of 2026.

| Jurisdiction | Instrument | What it requires | Status |
|---|---|---|---|
| EU-wide | DSA Art. 28 + Commission guidelines (14 July 2025) | "Effective age assurance" for platforms accessible to minors | In force |
| EU-wide | EU age-verification mini-wallet + Recommendation (29 April 2026) | Member States to roll out by end of 2026 | Feature-ready 15 April 2026; already bypassed |
| EU-wide | EUDI Wallet (eIDAS 2.0 / Reg. EU 2024/1183) | National digital identity wallets with selective disclosure | Rollout deadline end of 2026 |
| France | SREN Law (May 2024) + ARCOM standard (Oct 2024) | "Double anonymity" required from 11 April 2025 | Enforced |
| Germany | JMStV / 6th Interstate Amendment | KJM-certified AVS required; payment-blocking from 1 Dec 2025 | Active |
| UK | Online Safety Act 2023 | "Highly effective" age verification for adult content | Enforced from 25 July 2025 |
| Italy | AGCOM Resolution 96/25/CONS; Piracy Shield extension | Age verification for porn / certain social platforms; DNS + VPN block within 30 minutes | Active |
| EU Parliament | Resolution (Nov 2025) | "Digital age of majority" of 16 for social media, video-sharing, AI companions | Non-binding signal |

The EU does not need a new horizontal age-verification regulation to make age verification universal. The DSA, AVMSD, eIDAS, GDPR Article 8 and national laws already do that work. What is missing is a sensible scoping of where verification belongs and a serious enforcement of the design rules that already apply elsewhere — which is the argument of this report.

---

## 2. The three architectures

Every age-verification proposal in Europe fits, in some combination, into three architectures: at the provider, on the device, or via a government-issued credential. They differ in who holds identity data, who sees the verification result, and what is linkable to what.

### 2.1 Provider-side

The website or a vendor it pays checks the user's age. **Document upload** (Onfido, Veriff, Yoti, Jumio, AU10TIX, Persona) is the worst privacy profile — a mass database of identity documents linked to platform accounts, with verified incidents (AU10TIX 2024; Discord vendor 70k IDs in 2025; Acuant 2021). **Facial age estimation** (Yoti, Privately, Incode) processes biometric data under GDPR Article 9, has documented demographic accuracy gaps, and pushes false-negative cost onto adults via 23+ buffers. **Credit-card and open-banking checks** are weak proxies in the EU and exclude the unbanked. **France's double-anonymity standard** (SREN, ARCOM-supervised from April 2025) — two-vendor split, issuer blind to the site, site blind to the user, fresh single-use tokens, no retention — is the strongest provider-side architecture available today, and a real improvement over the US model.

### 2.2 Device- and OS-side

Apple's Declared Age Range API (iOS 18.4, expanded with UK-mandated 18+ at the device level in iOS 26.4), Google Play Age Signals, and Microsoft Family return an opaque age band to apps. From a privacy standpoint these are clean — no identity data leaves the device — but they privatise a public-policy function into the Apple/Google/Microsoft duopoly, fail on shared family devices, and exclude any OS not blessed by Google or Apple. Google Wallet's identity verification with ZKP age tokens (mid-2025, building on ISO 18013-7 mDocs) is, in production-engineering terms, ahead of the EU mini-wallet — and ships globally on Google-attested Android. Awkward for the sovereignty argument.

### 2.3 Government-issued credentials (the EUDI mini-wallet)

The headline EU bet: the mini-wallet released 15 April 2026 and the broader EUDI Wallet ecosystem due by the end of 2026. The intended design is the right cryptography for the problem — Boolean age predicate, selective disclosure, batch issuance, zero-knowledge proofs, unlinkability against colluding relying parties, no central register. What shipped in April 2026 falls short on multiple dimensions:

- **Issuer-verifier collusion.** The EUDI Architecture Reference Framework (ARF) only formally protects unlinkability against colluding relying parties via batch issuance, not against an issuer-verifier coalition (ARF issue #305). The state, in principle, could later be compelled to log who requested an 18+ proof when.
- **Same-site session linkability.** SD-JWT and mDoc credentials contain values unique to each attestation (signatures, salts, timestamps); same-site presentations of the same credential look identical. EUDI ARF labels these risks TR36 and TR39. ZKPs mitigate; on iOS, ZKPs are "still being implemented"; the shipped iOS path uses batch tokens only.
- **Production maturity.** Security researcher Paul Moore demonstrated a full bypass within a week of launch by toggling a boolean in a config file; facial images were stored unencrypted; PIN and biometric checks were trivially bypassable on rooted devices. "Highest privacy standards in the world" is a claim, not a fact.
- **Platform exclusion.** The white-label app is Android and iOS only. Production deployments use Google Play Integrity and Apple App Attest. GrapheneOS passes basicIntegrity but fails ctsProfileMatch; LineageOS fails verified boot; Sailfish OS users have documented the system breaking on non-Google ROMs. No desktop client; no AOSP roadmap. See §4 for the full impact.
- **The credential-lending dilemma.** Strict unlinkability makes the system impossible to defraud individually but also impossible to defend against an adult issuing fifty age proofs a day for fifty minors. The political response to the first scaled-up demonstration of this will likely be to add a per-user identifier, which destroys the cryptographic property the EU spent five years designing. "Either anonymous or enforceable, pick one."

---

## 3. Privacy and cybersecurity implications

### 3.1 What each model exposes

- **Provider-side, document upload:** full identity, full document image, biometric (face), permanent identifiers; visible to platform and verifier; linked to platform account; verified breach history.
- **Provider-side, biometric age estimation:** face image; in principle ephemeral but not user-verifiable; GDPR Article 9.
- **French double-anonymity:** if implemented with fresh per-request tokens, sound; if with long-lived signed credentials, linkable.
- **Device-side OS signals:** opaque age band; visible to OS vendor; locks the EU into the Apple/Google duopoly.
- **EUDI mini-wallet (as designed):** over-18 predicate, ZKP-presented, no issuer visibility at use time, unlinkable across relying parties.
- **EUDI mini-wallet (April 2026, as shipped):** batch tokens without ZKP on iOS; SD-JWT/mDoc signatures that enable same-site linking; plaintext biometric storage in pilot app; trivially bypassable.

### 3.2 Aggregate-data risk and special categories

Every provider-side scheme creates a database — somewhere — of "people who proved they were 18 to site X." The only data that cannot leak is the data that does not exist. Biometric identification combined with a sexual context is the highest-risk GDPR Article 9 stack the regulation contemplates; Charter-of-Fundamental-Rights challenges are likely within five years. Even the EUDI ZKP design, in principle privacy-preserving, has been undermined in practice by the platform-exclusion / OS-attestation problem (§4).

### 3.3 Cybersecurity: honeypots, breaches, pilot failures

AU10TIX (2024, exposing TikTok / Uber / Coinbase / X verification flows); Discord vendor (2025, ~70k government IDs and selfies); Acuant (2021); Optus (2022); Latitude Financial (2023). Phishing flows are trivial once users are habituated to identity-upload screens. Replay and credential-theft risks shift to wallet-side schemes. And the Commission's own pilot app failed a basic security review one week after launch. This is the baseline maturity of the EU stack.

---

## 4. The exclusion problem — Linux, open-source, desktop, the unbanked

Every implementation actually being deployed in Europe in 2026, outside France's double-anonymity model, depends on hardware-attested American mobile-OS infrastructure. The EU is shipping its flagship identity gate on top of two US proprietary attestation services, while spending separate billions on open-source as a strategic-autonomy priority.

### 4.1 What the shipped system requires

The white-label app is Android and iOS only. The technical-specification issue tracker confirms desktop is out of scope (issue #22). Production Android apps will use Play Integrity and Hardware Key Attestation; iOS apps use App Attest. Google's attestation chain rejects degoogled Android out of the box: GrapheneOS passes basicIntegrity but fails ctsProfileMatch; LineageOS fails verified boot entirely; Sailfish OS users have already documented the breakage.

### 4.2 Who that excludes

- **Linux desktop users.** No first-party client. A Belgian, German, or French Linux resident cannot present a valid wallet attestation from their primary computer.
- **Degoogled or alternative Android (GrapheneOS, /e/OS, LineageOS, CalyxOS, iodéOS).** Play Integrity rejects these by design.
- **European mobile OS efforts (Sailfish, Volla, Murena, future EU-funded).** Same problem.
- **Users without smartphones.** Older Europeans, low-income users, those who deliberately avoid smartphones for security or wellbeing. No browser-only, smart-card, or kiosk path that does not route through the duopoly.
- **Adults without an eID.** Residents with irregular status, refugees, asylum seekers, recently naturalised residents, citizens of low-eID-coverage Member States.
- **Cross-border travellers.** Member-State-specific verifier integrations not yet wired across schemes.

### 4.3 Why this is a digital-sovereignty problem

Linux is the platform on which most European public-sector, scientific, and small-business infrastructure runs. The EU has spent a decade promoting open-source as a sovereignty lever — Gendarmerie Nationale on Ubuntu/GendBuntu, Munich's LiMux history, Schleswig-Holstein's 2024 migration to Linux and LibreOffice, the Commission's own Open Source Strategy 2020–2023, the Cyber Resilience Act explicitly carving out open-source stewards in 2024. An age-verification regime that requires Google Play Integrity or Apple App Attest to function is not neutral between Big Tech and European open-source — it makes the latter structurally unable to comply. The cleanest description is the bluntest: under access gating with the currently shipping wallet, a Linux user is locked out. Not "degraded," not "requires extra steps" — fail closed.

---

## 5. Slippery slope: Chat Control, ProtectEU, and the VPN pivot

Three adjacent EU files — Chat Control (the CSA Regulation), ProtectEU / data-retention, and the emerging VPN-restriction agenda — are advancing in parallel. Considered separately, each has a justification. Considered together, they form an integrated identification-and-monitoring architecture in which every access is identified, every message can be scanned, and the tools that resist either are constrained. Age verification is the foundation stone of that stack — which is why the scoping question this report addresses is consequential.

### 5.1 Chat Control

Proposed in May 2022; would oblige messaging providers to detect known and unknown CSAM and grooming, in practice via client-side scanning on the device before encryption. After three years of successive presidencies, the November 2025 Council position dropped mandatory detection but kept "voluntary" scanning permanent and added a review clause to reassess detection obligations within three years. Patrick Breyer warned the language obliging providers to take "all appropriate risk mitigation measures" effectively reintroduces a scanning duty without naming it. The file is alive, in trilogue, in vague phrasing.

> **Why this matters for age verification:** client-side scanning and on-device age attestation share the same architectural premise — that the device is a trusted enforcement point for the state. Once you accept that premise for one purpose, you have it for the other.

### 5.2 ProtectEU and the Going-Dark / data-retention agenda

The Commission's ProtectEU strategy (1 April 2025) committed to a Technology Roadmap on encryption in 2026 to identify "solutions that enable lawful access to encrypted data," to funding Europol next-generation decryption capability from 2030, and to a wider data-retention framework expected mid-2026. The High-Level Group on Access to Data (whose membership the Commission redacted when Patrick Breyer requested it) published 42 recommendations in May 2024 covering "lawful access" for VPN, proxy and anonymisation providers (Recs 22–23). A leaked Council document under the Danish Presidency (27 November 2025) shows Member States want VPN providers, messaging apps, cloud, file-sharing and OTT services forced to log IP, time, location and traffic — retained for at least one year. Mullvad has stated publicly that if the law passes as drafted, it will exit the EU rather than start logging. The same dilemma applies to Proton, IVPN, AirVPN — the result is not "no VPNs" but "only big providers willing to log everything."

### 5.3 The age-verification → VPN-restriction pivot

- **May 2026 — Commission EVP Henna Virkkunen** said publicly the EU may need to address VPN use to bypass age verification.
- **May 2026 — EPRS briefing** labelled VPN use "a loophole in the legislation that needs closing." UK VPN downloads rose 1,800% after Online Safety Act enforcement; Florida +1,150%, Utah +967% after Pornhub blocks.
- **January 2026 — UK House of Lords** voted 207–159 to ban VPN services for under-18s.
- **6 May 2026 — Utah SB 73** became the first US jurisdiction to write VPNs into age-verification law.
- **2024 — Italy Piracy Shield** extended to oblige DNS resolvers and VPN providers to block listed IPs within 30 minutes, no judicial review.

> **The categorical reframe.** A VPN ban is sometimes presented as "banning a way to bypass age verification." It is more accurately described as removing the last consumer-grade tool that lets an ordinary person separate their network identity from their legal identity. Once that is gone — and once Chat Control's voluntary scanning and a renewed encryption-access push are layered on — the architecture for casual mass surveillance is essentially complete, regardless of whether any single law in the package is justified on its own terms. The principal way to avoid this is the policy choice this report advocates: do not extend age verification beyond the narrowest categories. Without universal age verification, there is no "bypass loophole" to close.

---

## 6. The two-track answer

### 6.1 Why the division

The dominant European debate has run age verification and social-media regulation together — same instruments, same architectures, same arguments. This is a category error.

**Pornography and gambling** plus the existing 18+ categories with online analogues (alcohol, tobacco, vape, certain medications) are bounded, clearly definable, content-defined domains. Narrow scope. Best-in-class architecture (EUDI mini-wallet done properly, France's double-anonymity as the hard floor). The legal categories are stable, the offline analogues are well-established (you cannot buy a bottle of vodka or place a bet without proving you are an adult), and the digital boundary should match the physical one.

**Social media is different.** The harm from a teenager scrolling Instagram for ninety minutes is not in the existence of the platform or in the messages exchanged with friends. It is in the design: infinite scroll, autoplay, engagement-maximising recommendation, public-by-default exposure, streak gamification, notification-driven re-engagement loops, body-image-amplifying ranking. Those features are designed to be compulsive, and they are compulsive across age groups. The fourteen-year-old and the thirty-four-year-old experience the same harm; the younger brain just acquires the addiction faster and recovers from it more slowly. Removing the design features works against the actual harm. Identifying the user does not.

**Games sit in the same category as social media for this purpose.** The harm in a free-to-play mobile game or a live-service title is not in the play itself; it is in the deliberately compulsive monetisation and retention design that has converged across the industry: loot boxes and gacha pulls (random-reward variable-ratio reinforcement, well-understood as one of the most addictive behavioural patterns there is), daily-login streaks with breakage penalties, FOMO-driven limited-time events, energy and stamina systems that ration play to engineer return visits, pay-to-progress and pay-to-skip mechanics, predatory ad placements aimed at younger players, and (in the most aggressive cases) systems that escalate offers and prices for spenders profiled as susceptible. Belgium's Gaming Commission held in 2018 that loot boxes constitute gambling under national law and effectively banned them; the Netherlands' KSA reached a similar conclusion. The EU has not generalised that finding. The same logic that applies to social-media engagement maximisation applies to game engagement maximisation, and the same regulatory tools — DSA Article 25 dark patterns, AI Act Article 5 manipulative techniques, UCPD aggressive practices, plus Member-State gambling-law extensions for loot boxes — already exist.

So separate them. Different problems, different tools. The EU's existing legal architecture already supports this division — it just has not been applied that way.

### 6.2 Track 1 — Narrow age verification for porn and gambling

Yes to age verification for pornography and online gambling, plus the existing 18+ offline categories with online analogues: online sales of alcohol, tobacco, vape, fireworks, and certain medications. The digital boundary should match the physical one. Everything else: no age verification at all.

**Architectural floor (seven conditions, non-negotiable)**

1. **Legal floor.** Age verification only via methods that satisfy formal unlinkability against issuer-verifier collusion. France's double-anonymity standard as a hard minimum; the EUDI mini-wallet's stated design (Boolean ZKP attestation, batch tokens, no central register) as the going-forward standard. Anything weaker than the mini-wallet's stated guarantees is not permitted to launch.
2. **No central register, by law.** Statutory ban on logging which sites a citizen presents an age proof to. The wallet must be technically incapable of producing such a log.
3. **Open-source, externally audited, reproducible builds.** Source code public, build reproducible from source, annual public audits, mandatory bug-bounty. The April 2026 bypass is the last time this is acceptable.
4. **Statutory firewall against reuse.** No reuse of age-verification infrastructure for Chat Control, ProtectEU, law-enforcement access, or any purpose beyond gating access to the specifically scoped Track-1 categories.
5. **No VPN or anonymity-tool restrictions justified by age verification.** Track 1 cannot be the policy hook that brings the VPN-restriction agenda over the line.
6. **Triple anonymity.** Relying site blind to user identity; issuer blind to relying site; device OS vendor blind to verification flow. Play Integrity / App Attest may be one accepted authenticator, not the floor. Open-source mobile OSes and Linux desktops remain first-class citizens.
7. **A non-eID adult escape hatch.** Cash purchase of single-use age tokens at PostNL / Bpost / Deutsche Post counters, time-limited per-device adult opt-outs verifiable by an adult-only ISP attestation, or other low-tech alternatives. The state must not make wallet-mediated identity the only path.

**Scope boundary, written into the regulation**

- Covered services explicitly limited to: pornography sites; online gambling operators; online sale of alcohol, tobacco and vape products; online sale of fireworks; online sale of age-restricted medications.
- A separate amending act required for any scope extension. No delegated-act expansion.
- Specifically excluded from Track 1: social media, video-sharing of non-pornographic content, news sites, search, productivity tools, e-commerce in non-age-restricted goods, messaging, gaming, dating, encyclopaedias, AI assistants, app stores.
- Sunset clause: five years, with mandatory evidence-based renewal vote.
- Charter-of-Fundamental-Rights compatibility assessment before deployment.

### 6.3 Track 2 — Design regulation, not identity regulation, for social media and games

No to age verification for social media or games. The harms that motivate it are real; the tool is wrong. Instead, enforce the design constraints that already exist in EU law, and use the DSA's existing escalation ladder against platforms and publishers that refuse to comply.

The reframe: the harm caused by social media and games to minors is overwhelmingly caused by features that also harm adults. Engagement-maximising recommenders, dark patterns, public-by-default exposure, notification-driven re-engagement, streak gamification, infinite scroll, autoplay, loot boxes, gacha pulls, daily-login streaks, FOMO event mechanics, energy and stamina systems, and pay-to-progress are not problems specific to minors. They are compulsion-by-design systems aimed at any user. Regulating them improves the internet for everyone, removes the harm at its source, and does not require identifying any user.

**What gets banned (social media)**

The following are required defaults (or required absences) on any platform operating in the EU and within the DSA's scope, enforced under existing DSA Articles 25, 27, 28, 34 and 38, the AI Act Article 5 and the Unfair Commercial Practices Directive:

- **No engagement-maximising recommender by default.** Chronological / friends-only feed is the default. Recommender opt-in, persistent across sessions, no re-prompting after dismissal. (DSA Article 38 already requires an opt-out from profile-based recommendation — make it default-off.)
- **No infinite scroll.** Pagination at a defined limit (e.g., twenty items). An explicit confirmation tap to continue.
- **No autoplay.** Each video plays on tap; no default auto-progression to the next item.
- **No streak counters or "your friend is waiting" notifications.** No daily-engagement gamification.
- **No public-by-default profiles or friend lists.** Profile visibility is private by default for all users; explicit opt-in to public.
- **Notification batching enforced.** Notifications batched (e.g., every 30 minutes); default-on quiet schedule overnight; per-app notification budget limits.
- **No engagement or time-on-platform as a maximisation target.** If the platform can be shown to optimise its recommender or interface for time-on-platform, that is an Article 25 dark-pattern breach.
- **No psychological-profile-based ad targeting.** Already prohibited for minors under the DSA; make universal.
- **No dark patterns in account creation, deletion or settings.** DSA Article 25 already prohibits; enforce concretely.

**Game-specific design constraints**

Games published in or accessible from the Union, regardless of platform (PC, console, mobile, web), and especially free-to-play and live-service titles:

- **Loot boxes and gacha mechanics treated as gambling.** Belgium and the Netherlands have already taken this position under national law; generalise to the Union. Any randomised-reward purchase with real-money or real-money-convertible value is a gambling product, falls under Track 1, and is prohibited for minors. Adults can access it under Track 1 age verification, with mandatory cool-down periods and deposit limits.
- **No daily-login streaks with breakage penalties.** Reward systems that punish missing a day (loss of streak bonus, reset of progression, loss of in-game currency) are compulsion-by-design and prohibited.
- **No artificial energy / stamina systems with paid bypass.** A game may have play-time mechanics for design reasons. A game may not ration play via an energy meter whose primary purpose is to either generate return visits or sell skip-tokens. The two are easily distinguished by whether the system has a real-money bypass.
- **No FOMO event mechanics.** Limited-time exclusive content priced for impulse purchase, with countdown timers and scarcity messaging, is an aggressive commercial practice under the UCPD. Banned for minor accounts, restricted for adults (mandatory cool-down, no countdown urgency).
- **No pay-to-progress, pay-to-win, or pay-to-skip aimed at minors.** Distinguishing competitive imbalance and engineered frustration-buy is genuinely hard, but the operative test is: does the design deliberately impose frustration that the same publisher offers to remove for money? If so, the design is the problem.
- **Statutory transparency on monetisation.** Drop rates, expected-value calculations, total spend by user-cohort, and time-investment-versus-cash-investment tradeoffs published in a standard format. The same principle the gambling industry already has to comply with.
- **No psychological-profile-based offer escalation.** Systems that profile players for susceptibility to spending and escalate offers accordingly — already widely deployed by the largest free-to-play publishers — are an AI Act Article 5 manipulative-technique violation. Prohibit.
- **No in-game advertising aimed at minors.** Same standard as elsewhere in EU law: no behavioural targeting of minors; no manipulative formats.
- **Hard caps on daily and monthly spend for minor accounts.** Where a publisher knows or should know that an account is operated by a minor, hard caps in line with average pocket money — not "parental controls available if you find the setting in the right submenu."

These are not novel asks. The PEGI rating system, Belgium's 2018 loot-box position, the Netherlands' KSA decisions on EA's FIFA, the UK's CMA work on in-game purchases, the Norwegian Consumer Council's "Insert Coin" report on game design dark patterns, and academic literature on variable-ratio reinforcement in mobile games all converge on this checklist. The Commission can codify it in DSA enforcement guidance alongside the social-media checklist, or in a horizontal Consumer Protection Cooperation enforcement action.

Taken together, the social-media and game design constraints above are not novel: they are the operational checklist that 5Rights, IEEE 2089.1-2024, the ICO Age Appropriate Design Code, EDPB Statement 1/2025, DSA Observatory reporting, the Belgian and Dutch loot-box decisions, and the Norwegian Consumer Council have already converged on. The Commission can codify them in DSA enforcement guidance — and should.

### 6.4 What "banish addictive design until they fix it" means operationally

"Banish" is not rhetorical. The DSA already has the legal mechanism. Specifically:

- **DSA Article 25 (dark patterns)** — prohibits manipulative interface design that distorts or impairs the recipient's ability to make free and informed decisions. Engagement-maximising recommenders and infinite scroll meet that test.
- **DSA Article 27 (recommender transparency)** — platforms must disclose the parameters of their recommenders. Few comply meaningfully; the DSA Observatory has documented the gap.
- **DSA Article 28 (protection of minors)** — online platforms must put in place appropriate and proportionate measures to ensure a high level of privacy, safety and security of minors.
- **DSA Article 34 (systemic risk assessment)** — VLOPs must assess systemic risks including the protection of minors and the user's mental and physical well-being. The risk of addiction-by-design is in scope.
- **DSA Article 38 (recommender opt-out)** — VLOPs must offer a non-profile-based alternative. They do; few users find or use it. Default-off would change that.
- **DSA Article 73 (interim measures)** — the Commission can adopt interim measures while an investigation is ongoing, including requiring cessation of specific functionalities.
- **DSA Article 74 (fines)** — up to 6% of global annual turnover.
- **DSA Article 76 (temporary access restrictions)** — in case of persistent serious breach causing serious harm, the Commission may request temporary access restrictions, i.e. suspension of the service in the Union, until compliance is achieved.
- **AI Act Article 5** — prohibits AI systems that deploy subliminal techniques beyond a person's consciousness or purposefully manipulative or deceptive techniques. Engagement-maximising recommenders are squarely in scope.
- **UCPD (Directive 2005/29/EC)** — prohibits unfair commercial practices including aggressive or misleading interface design. Concurrent Member-State enforcement available.
- **DMA Article 30 (gatekeeper fines)** — up to 10% of global turnover, doubling for repeat offences, applies to the largest platforms.

Combined, this is one of the strongest regulatory toolkits in the world. The bottleneck is enforcement, not legislation.

### 6.5 The DSA enforcement ladder, and why it is mostly unused

The DSA's escalation ladder is intentionally graduated: investigation, request for information, dark-pattern finding, interim measure, fine, repeated fine, temporary access restriction. As of mid-2026 the Commission has opened formal proceedings against Meta (twice), X, TikTok and AliExpress — but actual interim measures targeting addictive features are vanishingly rare, and Article 76 access restrictions have never been used. The April 2026 preliminary DSA finding against Meta concluded that its self-declared age gate was non-compliant; the operational consequences are still in negotiation. The current trajectory is years of negotiation per platform, per feature.

What "banish addictive design until they fix it" asks for is to skip several rungs of that ladder and use the tools the regulation explicitly provides. Specifically:

- Commission interim measures (Article 73) imposed in parallel against the engagement-maximising features of all VLOPs simultaneously — same regulatory action, same standard, same timeline — rather than negotiated per platform.
- Public, transparent enforcement thresholds: a platform that has not, by date X, shifted to default-off engagement-maximisation faces an Article 76 access restriction.
- Member-State parallel enforcement under UCPD, with Digital Services Coordinators in France (ARCOM), Germany (BNetzA), Italy (AGCOM), Ireland (Coimisiún na Meán) acting in concert.
- An EDPB-issued, ENISA-supported technical standard codifying the design checklist in §6.3 above, so platforms have unambiguous compliance criteria and regulators have unambiguous enforcement criteria.

This is the same playbook the Commission used to bring USB-C to the smartphone industry, mandate detachable batteries, demand interoperability of messengers under the DMA, and impose right-to-repair on appliances. The platforms know the playbook. They will lobby aggressively against it — which is, itself, evidence that they expect it to work.

### 6.6 Counter-arguments

**"Platforms will leave Europe."** Some might. The ones that do not will comply. The DSA's enforcement teeth are real, the European market is large, and the platforms have already shown — under GDPR, under the DMA, under USB-C, under right-to-repair — that they comply rather than withdraw. If Meta or TikTok genuinely chose to exit a 450-million-person market rather than disable infinite scroll, that would be evidence the addictive design is the product, in which case the policy is well-targeted.

**"Adults want infinite scroll."** If they want it, they can opt in. The current default is that they did not opt in, they did not consent, and the manipulation is the harm. Default-off, opt-in available is not paternalism; it is informed consent applied to interface design — the same principle the GDPR applies to data processing.

**"How do you define addictive design?"** The frameworks exist. 5Rights' Age Assurance as a Spectrum (February 2026), IEEE 2089.1-2024, the ICO Age Appropriate Design Code, EDPB Statement 1/2025, DSA Observatory's reporting under DSA Article 25, the work of CHAI (Center for Humane Tech), and the academic literature on dark patterns (Mathur et al.; Gray et al.) all converge. The Commission can codify the operational checklist in DSA enforcement guidance; this is a craft problem, not a conceptual one.

**"This won't protect children from pornography."** Correct. That is what Track 1 is for. The two tracks together cover the harm space; either alone does not.

**"Restricting recommender systems is industrial policy / censorship."** It is consumer protection — the same logic that allowed the EU to mandate detachable batteries, USB-C, repairability, GDPR consent, and right-to-repair. Manipulative product design has a long regulatory history; this is its digital application. It does not restrict any user's ability to post any content. It restricts the platform's ability to algorithmically funnel a non-consenting user into content they did not choose.

**"Engagement maximisation is the business model."** It is the platforms' business model. It is not the EU's job to preserve a business model that produces measurable mental-health harm. The platforms can build sustainable products with subscriptions, less aggressive advertising, chronological-feed defaults, and restrained engagement targets. Several smaller platforms already do. Or they can lose European market access.

**"This will destroy the games industry."** It will reshape the monetisation layer of part of the games industry. The premium-game segment (one-off purchase, content updates, optional cosmetics) is unaffected; that is most of the industry by revenue and almost all of it by acclaim. What is affected is the free-to-play / live-service segment that has converged on variable-ratio reinforcement (loot boxes, gacha) as its primary monetisation. Belgium and the Netherlands have already constrained that segment; the sky did not fall, the games adapted (FIFA Ultimate Team packs were removed from Belgium; the publisher continued selling the game). Generalising that approach gives EU consumers the same protection EU gamblers already have, and ends an industry-wide arms race over how much psychological manipulation a publisher can deploy before regulators notice.

**"Member States and the Commission will not have the courage to use Article 76."** Then the law is fictional. If Article 76 is unusable, it should be repealed; if it is usable, it should be used. The credible threat is a precondition of the credible policy.

**"This is just regulation of speech."** No. It is regulation of the design of an interface that ranks, recommends, and amplifies. Every user remains free to post, read, and share. What changes is whether the platform is allowed to algorithmically maximise their compulsion. The European Court of Human Rights and the CJEU have both repeatedly held that interface and design rules are not speech regulation.

### 6.7 Practical asks for European policy-makers

- Adopt a horizontal Age Verification Scope Regulation that limits mandatory age verification to: pornography sites, online gambling, online sale of alcohol/tobacco/vape/fireworks/restricted medications. No other category, no delegated-act extension.
- Write the seven architectural conditions in §6.2 into the regulation itself, not into delegated acts.
- Withdraw Chat Control in its current form. Replace with targeted, judicially supervised, suspect-specific measures.
- Take VPNs and anonymising tools off the lawful-access roadmap. The Track 2 approach removes the rhetorical basis for a "bypass loophole."
- Issue Commission DSA Enforcement Guidance codifying the addictive-design checklist in §6.3 (both the social-media and game-specific sections), with explicit Article 25 / 28 / 38 compliance criteria.
- Generalise the Belgian and Dutch loot-box position across the Union: randomised-reward purchases with real-money or real-money-convertible value are gambling products, falling under Track 1 verification (adults only, with cool-down and deposit limits) and prohibited for minors.
- Impose Article 73 interim measures against engagement-maximising recommenders across all VLOPs simultaneously, with a defined compliance window.
- Publicly announce the Article 76 access-restriction threshold. Use it if the threshold is missed.
- Coordinate Member-State DSCs (ARCOM, BNetzA, AGCOM, Coimisiún na Meán) on parallel UCPD enforcement.
- Mandate a Charter-of-Fundamental-Rights compatibility assessment for any future age-verification scope extension.
- Mandate desktop and AOSP-compatible reference implementations of the mini-wallet before any Member State is allowed to make wallet-mediated verification the only path even within Track 1.
- Sunset clauses (five years) on all age-verification mandates, with mandatory evidence-based renewal vote.

---

## 7. Bottom line

The Union's instinct on age verification is right: children should not stumble into hardcore pornography; algorithmic addiction in minors is a real harm. The Union's chosen tool — universal identification, dependent on Google and Apple attestation chains, expanding into social media, stacked next to Chat Control and the VPN-restriction agenda — is the wrong tool, badly built, in a regulatory environment that turns it into surveillance infrastructure.

The right answer is to do two different things for two different problems. For pornography and gambling — the red-light district of the internet — yes to age verification, narrowly scoped, with the EUDI mini-wallet design taken seriously (ZKPs everywhere, no central register, triple anonymity, non-eID adult path), with statutory firewalls against scope creep and against Chat Control / ProtectEU reuse. For social media, games and everything else, no to age verification. Instead, enforce the design constraints already in the DSA, the AI Act, the UCPD, and the rest of the existing legal architecture. Default-off engagement maximisation. No infinite scroll. No autoplay. No streak gamification. No public-by-default exposure. No psychological ad targeting. No loot boxes for minors. No FOMO event mechanics or daily-login penalties. And, for platforms and publishers that refuse, the DSA's existing escalation ladder up to and including Article 76 temporary access restrictions — banish addictive design until they fix it.

This is not a softer policy. It is a tougher one — harder on the platforms, gentler on users. Children are protected better, because the features that harm them are removed for everyone rather than walled off behind an identity check that does not work. Adults are protected too, because the same features harm them. Pseudonymous browsing, journalist source protection, abuse-survivor anonymity, Linux desktop use, VPN use, encrypted messaging — all preserved. The Union spends less of its political capital trying to ban privacy tools that protect ordinary people, and more on the underlying business model that produces measurable mental-health harm in its citizens.

The current trajectory is large, soft-edged, and self-extending. The trajectory this report recommends is small, hard-edged, and reversible. The first is the architecture of a surveillance state built one child-safety measure at a time. The second is the European Union doing what it has historically done best: regulating product design for consumer safety, on the side of the user, against the manufacturer.

---

## 8. Sources and further reading

*Selective list. Full citations available on request.*

### EU primary law and Commission documents

- Regulation (EU) 2022/2065 — Digital Services Act, in particular Articles 25, 27, 28, 34, 38, 73, 74, 76.
- Regulation (EU) 2024/1689 — AI Act, Article 5 (prohibited practices).
- Regulation (EU) 2022/1925 — Digital Markets Act, Article 30 (fines).
- Directive 2005/29/EC — Unfair Commercial Practices Directive.
- Directive (EU) 2018/1808 — Audiovisual Media Services Directive, Article 28b.
- Regulation (EU) 2024/1183 — eIDAS 2.0 / European Digital Identity Framework.
- Regulation (EU) 2016/679 — GDPR, Articles 8, 9, 22, 35.
- Commission proposal COM(2022) 209 — CSA Regulation (Chat Control); November 2025 Council position.
- Commission Communication, ProtectEU — European Internal Security Strategy (1 April 2025).
- Commission, Roadmap for lawful and effective access to data (24 June 2025).
- Commission, European age verification app announcement (15 April 2026).
- Commission, Guidelines on the protection of minors under DSA Article 28 (14 July 2025).
- High-Level Group on Access to Data, Final Report and 42 Recommendations (May 2024).
- Danish Presidency Council document on metadata logging (27 November 2025; leaked).

### National measures

- France — Loi n° 2024-449 (SREN), May 2024; ARCOM technical referential (Oct 2024); January 2026 under-15 access law.
- United Kingdom — Online Safety Act 2023; Ofcom guidance (Jan 2025); House of Lords vote on under-18 VPN ban (Jan 2026).
- Germany — JMStV / 6th Interstate Amendment; KJM certification; payment-blocking enforcement from 1 Dec 2025; Chancellor Merz on anonymity (Feb 2026).
- Italy — AGCOM Resolution 96/25/CONS (Jan 2025); Piracy Shield extension (2024) to DNS and VPN providers.
- Spain — Cartera Digital Beta age-verification pilot (2024–2025).
- Australia (precedent) — Online Safety Amendment (Social Media Minimum Age) Bill, effective 10 December 2025.

### Technical and breach

- EUDI ARF — issue #305 (unlinkability); Privacy risks and mitigations (TR36, TR39); av-doc-technical-specification issue #22; av-app-android-wallet-ui issue #38.
- BiometricUpdate — Breaking down the EC's white-label AV app; Double-blind age assurance in France.
- Tom's Hardware — EU mini-wallet bypass (April 2026); EPRS labels VPNs a loophole (May 2026).
- TechRadar — EU prepares ground for wider data retention; EU age-verification app has a privacy problem.
- Sailfish OS forum — EU age verification forcing Google Play Integrity check.
- Google — Open-source ZK proof toolkit for age assurance; Google Wallet identity verification developer documentation.
- Apple — Declared Age Range API; iOS 26.4 device-level 18+ verification.
- AU10TIX breach (2024); Discord verification vendor breach (~70k IDs, 2025); Acuant (2021); Optus (2022); Latitude Financial (2023).
- Paul Moore — EU age-verification mini-wallet bypass demonstration (April 2026).

### Civil society and design frameworks

- EDPB Statement 1/2025 on age assurance; EDPB/EDPS Joint Opinion 4/2022 on Chat Control.
- EFF — Age Verification Threats Across the Globe 2025; 10 (Not So) Hidden Dangers; AU10TIX hack; Lawmakers Want to Ban VPNs.
- EDRi — Going Dark: a mission failure; Chat Control: what is actually going on.
- Global Encryption Coalition — Joint letter on ProtectEU (May 2025).
- Mullvad — Chat Control & Going Dark position.
- 5Rights Foundation — Age Assurance as a Spectrum (February 2026); Age-Appropriate Design.
- IEEE 2089.1-2024 — Standard for Online Age Verification.
- ICO — Age Appropriate Design Code (UK Children's Code).
- DSA Observatory — Platforms still use manipulative design despite DSA rules (Aug 2025).
- Mathur, A. et al., "Dark Patterns at Scale" (2019); Gray, C. et al., on dark-pattern taxonomy.
- Belgian Gaming Commission — Research report on loot boxes (April 2018, finding loot boxes constitute gambling).
- Netherlands Kansspelautoriteit (KSA) — Decisions on EA's FIFA Ultimate Team packs (2019–2022).
- UK Competition and Markets Authority — In-game purchases enforcement work.
- Norwegian Consumer Council (Forbrukerrådet) — "Insert Coin" report on game design dark patterns (May 2022).
- PEGI — Pan-European Game Information rating system; in-game-purchase descriptor since 2020.
- CJEU case law — Digital Rights Ireland (C-293/12); Tele2/Watson (C-203/15); La Quadrature du Net (C-511/18); Privacy International (C-623/17); Schrems II (C-311/18).

---

