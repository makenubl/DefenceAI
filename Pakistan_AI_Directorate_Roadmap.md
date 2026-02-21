# Pakistan Military AI Directorate — Practical Roadmap
**Prepared for:** Army AI Directorate Planning (PAF integration consideration)
**Date:** February 2026
**Classification:** INTERNAL PLANNING DOCUMENT

---

## EXECUTIVE SUMMARY

This document presents a practical, phased roadmap for establishing an AI Directorate within the Pakistan Army (with parallel track for PAF). It draws on:
- Proven patterns from 12 militaries that have deployed AI at scale
- Pakistan's actual current capabilities, talent base, and infrastructure
- Honest assessment of what is realistic vs. aspirational in each timeframe

**The core finding:** Pakistan should NOT start with autonomous weapons or battlefield AI. The highest-value, lowest-risk, fastest-to-deploy applications are in **logistics, ISR image analysis, predictive maintenance, and cybersecurity** — and Pakistan has enough talent and infrastructure to begin all four within 12 months.

---

## PART 1: LESSONS FROM GLOBAL MILITARY AI

### 1.1 United States — The Pioneer With Painful Lessons

**What they built:**
- **JAIC (Joint AI Center, 2018–2022):** The first dedicated military AI organization. Key program: **Project Maven** — computer vision to analyze drone ISR footage, reducing analyst workload from hours to minutes per sortie. Operational in Afghanistan and Iraq by 2019.
- **CDAO (Chief Digital and AI Officer, est. 2022):** Replaced JAIC; broader mandate covering data, analytics, and AI across all DoD.
- **Task Force Lima (2023):** Focused on generative AI and LLMs for intelligence summarization, logistics planning, and staff work automation.
- **JADC2 (Joint All-Domain Command and Control):** Ambitious network to fuse all sensor data with AI-assisted decision support. Still partially delivered as of 2025.

**What worked:**
- Project Maven — immediate, measurable value. Reduced image analyst workload ~50%. Led to targeting improvements.
- AI-enabled predictive maintenance in USAF — F-35 engine sensor monitoring, reduced unscheduled depot maintenance by ~20%.
- AI-assisted logistics forecasting (Army Logistics) — demand prediction for spare parts.
- AI in wargaming and training simulations (DARPA's ALPHADOG fighter AI beat human F-16 pilot in 2020 DARPA simulation).

**What failed or was delayed:**
- JADC2 — enormously complex; data standards and service-branch politics slowed it more than technology.
- Algorithmic warfare ambitions outpaced data infrastructure. Lesson: the bottleneck is always **data quality and labeling**, not AI models.
- Project Maven faced contractor backlash (Google withdrew in 2018 after employee protest) — organizational and ethical governance matters.
- Multiple AI programs procured without deployment pathways — "PowerPoint AI" that never reached operators.

**Key lesson for Pakistan:** Start with data infrastructure and mundane automation. Glamorous autonomous systems come last, not first.

---

### 1.2 Israel — The Most Operationally Advanced

**What they built:**
- **"Gospel" System (IDF, 2021–present):** AI system for generating airstrike target recommendations. In the 2021 Gaza conflict and 2023–2024 operations, it reportedly produced targets at a rate previously requiring weeks of human analysis — compressed to minutes.
- **"Lavender" System:** Reported AI system for identifying human targets (Hamas operatives) using pattern-of-life analysis.
- **Iron Dome fire control:** AI-assisted intercept trajectory calculation (has operated since 2011 — longest operationally proven military AI system in combat).
- **Unit 8200 (SIGINT/Cyber):** Deploys ML extensively for signals intelligence — language processing, pattern recognition in communications intercepts.
- **Harop loitering munition:** Man-in-the-loop autonomous engagement capability; exported to multiple countries including Azerbaijan.

**What worked:**
- AI-accelerated target generation is real and operational.
- Iron Dome's AI intercept calculation is the world's most battle-tested military AI.
- Unit 8200 alumni created the global intelligence-AI ecosystem (many Israeli AI startups like Palantir's rivals).

**What failed or created problems:**
- Gospel/Lavender created enormous controversy over AI in lethal targeting — legal, ethical, and reputational costs.
- Over-reliance on AI targeting in dense urban environments created strategic blowback.

**Key lesson for Pakistan:** AI for ISR analysis and decision support is proven. AI for autonomous lethal targeting requires human-machine teaming frameworks and legal frameworks first — don't rush that step.

---

### 1.3 China — Military-Civil Fusion at Scale

**What they built:**
- **Military-Civil Fusion (MCF) doctrine:** Explicitly mandated that commercial AI companies (Baidu, Alibaba, Tencent, Huawei, SenseTime) contribute to PLA AI development. This is the most important structural decision — not a program, but a policy.
- **AI in C2 (Command and Control):** PLA has been integrating AI into its joint operations command system since 2017 military reform. Focus on rapid data fusion across services.
- **Autonomous drone swarms:** CASC (China Aerospace Science and Technology Corporation) has demonstrated fixed-wing swarms of 200+ UAVs with autonomous coordination. CHD (China Heli Design) tested rotary-wing swarms.
- **BeiDou + AI:** GPS-independent precision guidance integrated with AI target recognition in cruise missiles and UCAVs.
- **AI in information operations:** Natural language processing for social media influence operations, deepfake generation, automated propaganda.

**What worked:**
- MCF model — leveraging Huawei, SenseTime, DJI talent and technology for military use is extremely effective.
- AI surveillance at scale (Xinjiang as testing ground for AI-enabled population monitoring, now transferable to military ISR).
- Drone swarm demonstrations show genuine technical progress.

**What failed or is unknown:**
- Actual combat performance is unproven — PLA has not fought a peer conflict since 1979.
- Chinese AI chips lag US NVIDIA equivalents by 2-3 generations, limiting some capabilities.

**Key lesson for Pakistan:** The MCF model is directly applicable — Pakistan should formally mobilize NUST, FAST, and the commercial IT sector (10Pearls, Arbisoft, etc.) for defense AI, with clear engagement frameworks.

---

### 1.4 Turkey — The Affordable Drone Power Model

**What they built:**
- **Bayraktar TB2:** Armed UCAV with AI-assisted target acquisition and laser-guided munitions. Combat-proven in Syria, Libya (2019–2020), Nagorno-Karabakh (2020 — decisive effect), and Ukraine (2022). Cost ~$5M per airframe — fraction of US MQ-9 Reaper.
- **Kargu-2 Autonomous Loitering Munition:** UN report (2021) documented first confirmed autonomous lethal engagement (Libya) — AI-based facial recognition to engage targets without human command link.
- **AKINCI UCAV:** Larger platform with AI-assisted multi-sensor fusion.
- **Bayraktar Kızılelma:** Unmanned combat jet currently in development.

**What worked:**
- TB2 proved that affordable, AI-assisted drones can achieve strategic effects previously requiring expensive manned aircraft.
- Loitering munitions (kamikaze drones) are tactically transformative and low-cost.
- Turkish defense industry (Baykar, Roketsan, Aselsan) built this from near-zero in 15 years using a **domestic first** procurement policy.

**Key lesson for Pakistan:** Pakistan has Shahpar and TB2 in inventory. The Turkey model is the most directly replicable — domestically developed AI-enabled UAVs with export potential. Pakistan already exports Shahpar to Azerbaijan (who bought TB2 from Turkey — the same customer).

---

### 1.5 India — The Structural Comparison

**What they built:**
- **iDEX (Innovations for Defence Excellence):** Startup-military bridge — gives startups defense contracts up to ₹1.5 crore to solve specific military problems. Over 300 startups engaged, ~50 contracts awarded.
- **DRDO AI Roadmap:** Focuses on AI in missile guidance, autonomous underwater vehicles, AI in EW.
- **Integrated Theatre Commands:** Planned joint command structure enabling AI-fused C2.
- **Border AI surveillance:** AI-enabled cameras with thermal imaging along LAC and LoC.
- **SMART torpedo:** Some AI in terminal guidance for lightweight torpedo.

**What worked:**
- iDEX model is generating rapid low-cost prototypes. Some have reached operational testing within 18 months.
- AI surveillance systems along border — commercially procured Israeli and domestic cameras with AI analytics.

**What is struggling:**
- Theatre commands have faced inter-service resistance (sound familiar?).
- DRDO's internal AI development is slow compared to iDEX startup track.

**Key lesson for Pakistan:** iDEX model should be studied carefully — it's a fast-procurement mechanism for AI startups that bypasses slow defense procurement. Pakistan needs this.

---

### 1.6 UAE — The Accelerated Buyer Model

**What they built:**
- **EDGE Group (2019):** Consolidated 25 defense entities into one; explicitly mandated AI integration across all product lines within 5 years.
- **AI in C4ISR:** AI-assisted fusion of radar, AEW, EO/IR imagery at national level.
- **Calidus armed drone:** UAE-developed UCAV with AI targeting.
- **Bayanat AI:** Commercial/defense geospatial AI analytics — satellite imagery analysis with AI.

**Key lesson for Pakistan:** The EDGE consolidation model — merging NESCOM, ARL, AWC, POF under one AI-mandate entity — would dramatically accelerate Pakistan's defense AI. Currently these organizations operate in silos.

---

## PART 2: PAKISTAN'S CURRENT BASELINE ASSESSMENT

### 2.1 Strengths (What Pakistan Already Has)

| Asset | Current State | AI Readiness |
|-------|--------------|-------------|
| JF-17 Block III | ~50 aircraft, KLJ-7A AESA radar | MEDIUM — Chinese AI in radar firmware |
| Shahpar-II UAV | Operational ISR, exported | LOW-MEDIUM — waypoint nav, manual image analysis |
| Bayraktar TB2 | ~6-12 aircraft reportedly acquired | MEDIUM — AI-assisted targeting (Turkish) |
| Burraq UCAV | Operational, combat-tested in CT | LOW — pre-programmed, no onboard ML |
| Wing Loong I/II | Reportedly in service | MEDIUM — Chinese AI features |
| Saab-2000 Erieye AEW&C | 4 aircraft, operational | MEDIUM — automated track management |
| PRSS-1 Satellite | 1m resolution optical, operational | LOW — imagery analyzed manually |
| HQ-9/LY-80 SAM | Operational air defense | MEDIUM — automated engagement, Chinese AI |
| Safe City Systems | Lahore, Peshawar deployed | HIGH — deployed Chinese facial recognition AI |
| NUST/FAST Talent | ~5,000-8,000 AI/ML professionals | DEPLOYABLE — needs defense tasking |

### 2.2 Critical Gaps

1. **No defense AI strategy** — National AI Policy (2023) is civilian-only; no defense AI roadmap exists
2. **Data desert** — Military operational data (maintenance logs, ISR footage, logistics records) is not digitized or structured for ML training
3. **No GPU compute** — No domestic high-performance compute for AI model training; dependent on China or commercial cloud (security risk)
4. **No talent pipeline** — NUST/FAST graduates go to commercial sector or emigrate; no mechanism to bring them into defense work
5. **No fast-procurement mechanism** — Contracting startups for defense AI takes years under current rules
6. **Siloed organizations** — NESCOM, ARL, AWC, PAC work independently; no joint AI development

### 2.3 What Pakistan Is "Almost Ready" to Do

These are areas where **the enabling conditions already exist** and deployment can begin in 12-18 months:

1. **ISR Imagery Analysis** — Shahpar and PRSS-1 generate imagery; NUST SEECS has computer vision expertise; this can be operationalized NOW
2. **Predictive Maintenance** — Aging fleet (Mirage, F-7) has high maintenance costs; sensor data + ML = immediate savings
3. **Logistics AI** — Army supply chain is paper-heavy; demand forecasting ML is well within domestic capability
4. **AI-Enhanced Cyber Defense** — APT attacks on military networks are ongoing; ML-based anomaly detection is urgently needed and achievable
5. **Training Simulator AI** — PAF has existing simulators; AI-driven adversarial red force behavior improves training quality

---

## PART 3: THE ROADMAP

### PHASE 1 — SHORT TERM (Months 1–18): FOUNDATION

**Objective:** Build the organizational structure, data infrastructure, and deliver 3-5 visible AI applications that demonstrate value to leadership.

#### 3.1 Organizational Setup (Months 1–6)

**Establish the AI Directorate**
- Recommended placement: Under DGMO (Director General Military Operations) or directly under VCOAS — needs to be high enough for cross-service authority
- Initial size: 30-50 people (not 500 — start lean)
- Structure:
  - **Director AI** (Brigadier rank) — must be STEM background, not just seniority
  - **AI Research Cell** (12 people) — embedded NUST/FAST PhD researchers on secondment
  - **Data Engineering Cell** (8 people) — responsible for data pipelines, not AI models
  - **Applications Cell** (10 people) — deploying and maintaining AI systems
  - **Policy & Governance Cell** (5 people) — AI ethics, oversight framework, international law compliance
  - **PAF Liaison** (2-3 officers) — if joint Army-Air Force mandate

**Parallel: Establish AI Directorate Charter**
- Formal authority to contract universities and private firms for AI development
- Fast-procurement rules: contracts under Rs. 50 million can be awarded within 60 days (equivalent of iDEX mechanism)
- Security clearance fast-track for civilian AI researchers

#### 3.2 Data Infrastructure (Months 1–12)

This is the most important and most unglamorous work. Without data, AI is impossible.

**Priority data digitization:**
1. **Maintenance records** — All Mirage, F-7PG, PAF fleet maintenance logs digitized and structured. Target: 5 years of historical data.
2. **Logistics data** — Army supply chain transactions (POL, ammunition, rations, spares) into a structured database.
3. **ISR imagery archive** — Shahpar-I/II and PRSS-1 imagery catalogued, geotagged, timestamped.
4. **Network/cybersecurity logs** — Military network traffic logs structured for ML ingestion.

**Infrastructure:**
- Procure 2-4 air-gapped GPU servers (NVIDIA A100 or H100 equivalent — or Chinese Biren BR100 if US chips unavailable). Budget: ~$2-4M. Deploy at Rawalpindi AI lab.
- Establish secure data lake — physically isolated, encrypted, access-controlled.
- Train 20 military "data engineers" (6-month course, can be run by NUST).

#### 3.3 Short-Term AI Applications (Months 6–18)

**Application 1: ISR Image Analysis System**
- **What it does:** Automatically analyzes Shahpar and PRSS-1 imagery — vehicle counting, change detection, pattern-of-life, facility monitoring along borders.
- **Who builds it:** NUST SEECS computer vision team (contract to university, 6-month development + 6-month deployment).
- **What's needed:** Labeled training data (annotate 50,000 historical imagery patches — 3 months of analyst time), GPU compute, air-gapped deployment.
- **Expected impact:** Reduce ISR analyst workload from 8 hours/sortie to <1 hour. Increase coverage analysis from 10% to 80% of collected imagery.
- **Budget estimate:** Rs. 40-60 million (~$140K-210K USD)
- **Risk:** LOW — this technology is 10 years mature; commercial equivalents exist (Planet Analytics, Maxar, etc.)

**Application 2: Predictive Maintenance — PAF Fleet**
- **What it does:** Analyzes engine sensor data, maintenance logs, and flight hours to predict component failure before it occurs.
- **Start with:** Mirage V fleet and JF-17 Block I/II engines (CFM56 or WS-13).
- **Who builds it:** 10Pearls or Arbisoft (experienced Pakistani IT firms) under defense contract.
- **Expected impact:** 15-25% reduction in unscheduled maintenance events. Significant cost savings on a fleet already expensive to maintain.
- **Budget estimate:** Rs. 30-50 million for development; savings of 10x in first year.
- **Risk:** LOW-MEDIUM — requires good sensor data; some Mirage platforms may lack sensors (retro-fitting needed on some aircraft).

**Application 3: Logistics Demand Forecasting**
- **What it does:** Predicts demand for critical spares, fuel, ammunition, and rations at division/corps level. Replaces manual estimation.
- **Who builds it:** Pakistan logistics AI is within capability of even mid-tier software firms.
- **Expected impact:** Reduce wastage (estimated 20-30% of logistics budget lost to over/under-ordering), improve readiness.
- **Budget estimate:** Rs. 20-35 million.
- **Risk:** VERY LOW — this is standard supply chain ML; no security sensitivity issues.

**Application 4: AI Cyber Threat Detection**
- **What it does:** ML-based anomaly detection on military network traffic; flags APT-style intrusions (Sidewinder and similar groups actively targeting Pakistani military networks).
- **Who builds it:** Netsol Technologies or Folio3 (Pakistani firms with security product experience) in partnership with NITB (National Information Technology Board) or existing cyber units.
- **Expected impact:** Earlier detection of intrusions; dramatically reduces dwell time of adversary presence in networks.
- **Budget estimate:** Rs. 50-80 million (includes hardware).
- **Risk:** MEDIUM — requires careful vendor vetting given Chinese hardware presence in some networks.

**Application 5: AI Training Simulator — JF-17/F-16 Red Force**
- **What it does:** AI-driven adversarial aircraft behavior in PAF's existing simulators. Current simulators use scripted, predictable Red Force — AI makes them adaptive and unpredictable.
- **Who builds it:** PAF's existing simulator team + NUST AI researchers (6-month collaboration).
- **Expected impact:** Higher quality BVR and WVR combat training; pilots encounter tactics they haven't memorized from manuals.
- **Budget estimate:** Rs. 25-40 million (software only; uses existing simulator hardware).
- **Risk:** LOW — this is gaming AI applied to simulators; no operational data sensitivity.

#### 3.4 Institutional Foundations (Months 1–18)

- **AI Ethics and Governance Framework** — Define when AI recommendations require human decision, what AI is never authorized to do autonomously. Based on DoD AI Ethics Principles (deconflict with Islamic jurisprudence on proportionality and discrimination in warfare — this is genuinely important and differentiates Pakistan's framework).
- **NUST-Army Defense AI Lab** — Formal joint lab with dedicated faculty positions, PhD scholarships funded by Army, research agenda set by Directorate.
- **Talent retention mechanism** — "Army AI Reserve" program: NUST/FAST AI graduates can serve 3 years in AI Directorate at competitive salaries (Rs. 400,000-600,000/month) while retaining option to return to civilian careers. This is the key to beating brain drain.
- **Classification of AI research** — Framework for what AI research is Secret vs. what can be published (publishing maintains talent pipeline and international credibility).

---

### PHASE 2 — MEDIUM TERM (Months 18–48): OPERATIONAL AI

**Objective:** Deploy AI systems that directly enhance combat effectiveness, establish joint Army-PAF AI infrastructure, and begin indigenous AI hardware development.

#### 3.5 Advanced ISR and Intelligence AI (Months 18–36)

**Multi-Source Intelligence Fusion**
- Integrate Shahpar imagery + PRSS-1 satellite + AEW&C radar tracks + SIGINT inputs into a single AI-assisted picture.
- Build on Phase 1 ISR system. Add data links and fusion algorithms.
- This is Pakistan's path toward a modest version of US JADC2 — a "National Intelligence Picture" dashboard with AI-generated threat assessments.
- **Requires:** Data link investments, hardware at corps-level ISR centers, 2-3 years of development.

**AI-Assisted HUMINT and OSINT**
- Natural language processing in Urdu, Pashto, Dari, Arabic, English — automated monitoring and analysis of open-source information (social media, news, communications) for intelligence indicators.
- Directly applicable to counter-terrorism operations and strategic warning.
- **Who builds it:** A specialized NLP team (8-10 people) at AI Directorate with FAST NLP faculty.
- **Budget estimate:** Rs. 80-120 million over 18 months.

**Counter-UAV AI (C-UAV)**
- AI-based radar and EO/IR system to detect, classify, and track small UAVs.
- Critically needed given Indian acquisition of Predator drones, proliferation of commercial drones used by non-state actors.
- Detection AI is proven (Israeli Drone Dome, US counter-UAS systems); Pakistan can develop domestic version.
- **Integrate with:** Existing radar networks and HQ-9/LY-80 for intercept recommendations.
- **Budget estimate:** Rs. 200-300 million for prototype C-UAV AI system.

#### 3.6 AI-Enhanced Platforms (Months 24–48)

**Shahpar-III: AI-Native UAV**
- Design requirement: Onboard Nvidia Jetson or equivalent edge AI processor.
- Capabilities to add: Autonomous target detection and classification (human remains in loop for engagement), automatic track following, terrain avoidance.
- Work with ARL — this is an achievable platform upgrade, not a new program.
- This positions Shahpar-III as a competitive export product with AI features (Azerbaijan, Saudi Arabia, Nigeria are potential buyers).

**JF-17 Block III AI Integration**
- Work with Chinese partners at CAC to access KLJ-7A radar AI algorithms.
- Goal: AI-assisted threat prioritization in contested airspace, sensor fusion from MAWS + radar + EW.
- Requires: Access to Chinese firmware (diplomatic/commercial negotiation) + NUST DSP team.
- **Risk:** Chinese willingness to share algorithm source code is uncertain — may need to work at integration level only.

**Loitering Munition Program**
- Turkey's Kargu-2 and Bayraktar TB2 experience shows loitering munitions are the highest-value AI weapon system at lowest cost.
- Pakistan should develop a domestic loitering munition with AI-assisted target seeker (based on EO/IR image recognition).
- ARL/NESCOM lead; NUST computer vision team for seeker AI.
- **Target:** 40 km range, 15 kg warhead, AI target recognition from database of vehicle silhouettes.
- **Budget estimate:** Rs. 1.5-2.5 billion for development program.
- **Timeline:** 36-48 months to prototype.

#### 3.7 Cybersecurity and Information Warfare AI (Months 18–42)

**Offensive OSINT and Information Operations**
- AI-generated content in Urdu/Pashto/Hindi for information operations (completely within legal bounds in peacetime — psychological operations, strategic communications).
- AI-assisted analysis of adversary decision-making patterns from open sources.

**Defensive Cyber AI — Hardening**
- Automated patch management and vulnerability scanning across military networks.
- AI-based deception (honeypots that adapt to attacker behavior).
- Specifically defend against Sidewinder/Rattlesnake APT tactics documented against Pakistani targets.

#### 3.8 Organizational Scaling (Months 18–48)

- **Expand AI Directorate** to 150-200 people.
- **Establish Corps-Level AI Cells** — Each corps HQ has a 5-person AI cell that operationalizes Directorate-developed tools at their level.
- **Defense AI Fund** — Rs. 2-3 billion annual dedicated budget (currently no line item exists).
- **PAF AI Directorate** — If PAF joins the initiative, establish parallel structure with shared data infrastructure but separate applications development. Key PAF applications: flight ops AI, air defense AI, EW signal classification.
- **Pakistan Defense AI Policy** — Publish (at unclassified level) a defense AI strategy document. This builds international credibility and signals to adversaries Pakistan's AI posture.

---

### PHASE 3 — LONG TERM (Years 4–10): STRATEGIC AI

**Objective:** Achieve indigenous AI capabilities that reduce dependence on China, develop Pakistan-specific AI advantages, and potentially become a regional AI defense exporter.

#### 3.9 Strategic AI Capabilities (Years 4–7)

**Integrated Battlefield Management System (IBMS-AI)**
- Pakistani-designed, AI-assisted joint operations command and control.
- Fuses: ground radar, UAV feeds, satellite imagery, EW intercepts, SIGINT, unit reports into single operational picture.
- AI generates course-of-action recommendations for commanders (humans decide and execute).
- This is Pakistan's own version of JADC2 — scaled to Pakistani theater and threat environment.
- **Critical enabler:** Secure tactical communications network (requires significant investment in encrypted tactical data links — LINK-17P equivalent for JF-17 and ground forces).

**AI in Strategic Systems**
- Navigation AI for cruise missiles (Babur series) — AI-assisted TERCOM/DSMAC that adapts to degraded GPS or adversary jamming.
- NESCOM-led; classified program.
- China already has this capability on their cruise missiles; Pakistan can develop domestically given existing TERCOM experience.

**Hypersonic Weapons with AI Guidance**
- Long-range goal; 7-10 years. Requires significant aerodynamics and AI-guidance investment.
- China's DF-17 uses AI guidance for terminal phase maneuvering. Pakistan can study architecture.

**AI for Nuclear Safety (Non-Lethal, Critical)**
- AI for safety monitoring of nuclear storage and transport (environmental sensors, anomaly detection).
- Reduces human error risk. Internationally constructive framing (reduces miscalculation risk).
- SPD-led, highest classification. But extremely high value.

#### 3.10 Reducing Chinese Dependency (Years 3–8)

This is a strategic imperative. Current AI-enabled capabilities are almost entirely Chinese-supplied, creating:
- Potential for capability denial in conflict
- Intelligence exposure via Chinese hardware
- Limited ability to export AI-enabled systems (China restricts re-export of military technology)

**Path to reduced dependency:**
1. **Domestic GPU compute** — Partner with UAE (G42), Saudi Arabia (NEOM), or South Korea (Samsung) for chip supply or foundry access. Pakistan needs ~$50-100M in compute infrastructure over 5 years.
2. **Open-source AI stack** — Build military AI on open-source models (Meta's LLaMA, Mistral) rather than Chinese or US proprietary models. These can be air-gapped, fine-tuned on domestic data, and controlled entirely by Pakistan.
3. **Turkey partnership** — Baykar (Bayraktar manufacturer) is willing to co-develop with allies. A Pakistan-Turkey joint AI-UAV development agreement would bring Turkish AI algorithms (Kargu-2's seeker AI) to Pakistan.
4. **Ukraine connection** — Ukraine has developed significant drone AI under combat conditions and is open to partnerships. Ukrainian AI engineers are available for defense contracts. Unconventional but high value.

#### 3.11 Export and Strategic Positioning (Years 5–10)

**Pakistan as regional defense AI exporter:**
- Shahpar already exports to Azerbaijan.
- AI-enhanced Shahpar-III with Pakistani AI seeker would be competitive in: Azerbaijan, Saudi Arabia, UAE, Nigeria, Turkey (for niche applications), Central Asian states.
- Pakistan loitering munition with AI — competitive in same markets at lower price than Israeli or Turkish equivalents.
- AI surveillance systems (built on Shahpar + PRSS-1 analytics) — could be packaged for export to African and Middle Eastern militaries.

**The competitive advantage Pakistan can develop:** AI systems tuned for specific threat environments (mountainous terrain, high-altitude operations, Urdu/Pashto language processing) that no other country prioritizes.

---

## PART 4: BUDGET FRAMEWORK

### Phase 1 (Years 1-1.5): Rs. 500-700 million (~$1.7-2.5M USD)

| Item | Budget (Rs. Million) |
|------|---------------------|
| AI Directorate setup (salaries, facility, admin) | 120 |
| GPU compute infrastructure (air-gapped servers) | 150 |
| Data digitization program | 80 |
| ISR Image Analysis System | 60 |
| Predictive Maintenance System | 50 |
| Logistics AI | 35 |
| Cyber AI | 80 |
| Training Simulator AI | 40 |
| NUST-Army AI Lab establishment | 100 |
| Talent retention (Army AI Reserve salaries premium) | 80 |
| **Total Phase 1** | **795** |

### Phase 2 (Years 1.5-4): Rs. 3-5 billion (~$10-18M USD)

| Item | Budget (Rs. Billion) |
|------|---------------------|
| Multi-source intelligence fusion system | 0.3 |
| Counter-UAV AI system (prototype) | 0.3 |
| Loitering munition AI program | 2.0 |
| Shahpar-III AI platform upgrades | 0.5 |
| Cybersecurity AI (offensive + defensive) | 0.4 |
| AI Directorate expansion (personnel, 3 years) | 0.6 |
| Corps-level AI cell equipment | 0.3 |
| OSINT/HUMINT AI system | 0.2 |
| **Total Phase 2** | **4.6** |

### Phase 3 (Years 4-10): Rs. 15-30 billion (~$50-110M USD)

| Item | Budget |
|------|--------|
| IBMS-AI (Integrated Battlefield Management) | Rs. 8-12B |
| Domestic GPU compute infrastructure | Rs. 3-5B |
| Strategic systems AI (NESCOM programs) | Rs. 5-8B (classified) |
| Export program development | Rs. 2-3B |
| **Total Phase 3** | **Rs. 18-28B** |

**Total 10-year program cost: ~Rs. 24-34 billion (~$85-120M USD)**

This is *remarkably affordable* by defense program standards. For comparison: one F-16 Block 52 costs ~$30M. This entire 10-year AI program costs less than 4 F-16s.

---

## PART 5: RISK REGISTER

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|-----------|
| Chinese AI systems have backdoors/killswitches | HIGH | CRITICAL | Phase 2 diversification; open-source stack; domestic development |
| Brain drain — AI talent leaves for Gulf/US | HIGH | HIGH | Army AI Reserve program; competitive salaries; NDAs with defense industry |
| Data quality too poor to train effective models | MEDIUM | HIGH | Phase 1 data engineering investment before AI development |
| Inter-service rivalry blocks joint AI infrastructure | MEDIUM | HIGH | Direct CJCSC mandate for AI Directorate; clear TORs |
| APT adversaries compromise AI training data (data poisoning) | MEDIUM | CRITICAL | Air-gapped training infrastructure; data provenance tracking |
| AI ethics/autonomy controversy (political or religious) | LOW-MEDIUM | MEDIUM | Pre-publish AI governance framework; engage NCHR; Islamic jurisprudence consultation |
| Budget cuts in Year 2-3 | MEDIUM | HIGH | Early wins in Phase 1 that demonstrate ROI before budget review |
| Vendor lock-in (single Chinese or domestic supplier) | MEDIUM | MEDIUM | Multi-vendor strategy from Phase 1 |

---

## PART 6: IMMEDIATE NEXT STEPS (First 90 Days)

1. **Appoint Director AI** — Senior Brigadier with STEM background and authority to hire civilians. This appointment defines the program's credibility.
2. **Commission NUST assessment** — Task NUST SEECS to provide a 30-day assessment of: what AI capabilities they can deliver, on what timeline, at what cost. Establish formal working relationship.
3. **Data audit** — Select one Corps HQ and one PAF Base. Audit all digital records: what data exists, in what format, how complete. This takes 30 days and will shape Phase 1 priorities.
4. **Draft the Directorate Charter** — Legal authority, budget lines, procurement fast-track rules. Submit for COAS/CAS approval.
5. **Benchmark visit** — Send a 3-person team (Director AI + 2 technical officers) to Turkey (Baykar, Aselsan, TUBITAK) and UAE (EDGE Group) to study their organizational models. These are the most replicable for Pakistan.
6. **Identify Phase 1 contractors** — Issue RFPs to: NUST SEECS (ISR AI), 10Pearls or Arbisoft (Logistics AI), Folio3 or Netsol (Cyber AI). RFPs out within 45 days.
7. **GPU procurement** — Identify source for 2-4 air-gapped GPU servers. Options: commercial servers with NVIDIA A100 (if US export license available), Chinese Biren BR100, or second-hand data center hardware from UAE.

---

## APPENDIX A: WHAT OTHER MILITARIES WISH THEY'D DONE EARLIER

1. **Start with data, not algorithms.** Every major military AI program hit data walls first. The US spent 3 years trying to build Project Maven before realizing analysts hadn't labeled the training data properly.
2. **Keep humans in the loop — on paper and in practice.** Israel's Gospel system controversy cost more in international legitimacy than it gained. Pakistan's strategic environment (nuclear-armed neighbors, international scrutiny) makes AI ethics governance a real strategic asset, not bureaucratic overhead.
3. **Don't build what you can buy.** Logistics AI, predictive maintenance AI, and cyber AI are commercial problems with commercial solutions. Military-specific versions of commercial AI are rarely worth the effort. Buy adapted commercial solutions; only develop custom AI where genuinely classified requirements exist.
4. **AI in training before AI in operations.** Every military that deployed AI in training first had smoother operational deployments. The learning curve is painful and should be taken in simulators.
5. **The organizational problem is harder than the technical problem.** The US JADC2 program was technically feasible by 2021. The reason it isn't fully deployed in 2025 is because Army, Navy, Air Force, and Marines couldn't agree on data standards and command relationships. Define the organizational architecture before the technical architecture.

---

## APPENDIX B: RECOMMENDED READING FOR DIRECTORATE LEADERSHIP

- *DoD AI Ethics Principles* (US, 2020) — best publicly available AI governance framework for military
- *CDAO AI Strategy 2023* — US implementation guide
- *UK MOD AI Strategy 2022* — more applicable to smaller militaries than US model
- *IISS Report: "AI and Military Effectiveness"* (2023) — balanced assessment of what AI actually delivers
- *RAND: "Implications of Artificial Intelligence for Nuclear-Armed Adversaries"* — essential for Pakistan's nuclear context
- *PAF Journal* archives on JF-17 Block III — understanding current platform capabilities
- *NUST SEECS research papers* on computer vision and signal processing — know what your talent can already do

---

*This document will require revision as the Directorate becomes operational and as Pakistan's threat environment and technology access evolve. It should be reviewed at 12-month intervals.*

*Next update recommended: February 2027.*
