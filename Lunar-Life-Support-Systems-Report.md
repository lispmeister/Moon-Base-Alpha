# Lunar Habitat Life Support Systems: Atmospheric Control & CO₂ Scrubbing

## A Comprehensive Research Report — February 2026

-----

## Executive Summary

The race to establish permanent human presence on the Moon is driving a generational shift in Environmental Control and Life Support Systems (ECLSS). While the ISS has served as the proving ground for current-generation CO₂ removal technology — primarily zeolite-based adsorption systems like the CDRA — the demands of lunar surface habitats are fundamentally different: higher crew counts, longer durations, no easy resupply, the need for gravity-compatible systems, and extreme thermal environments. This report maps the key companies, emerging technologies, scalability efforts, HVAC adaptation strategies, and the full supply chain for atmospheric control systems targeting the upcoming generation of lunar stations.

-----

## 1. The Current State of the Art: ISS Heritage Systems

### 1.1 Carbon Dioxide Removal Assembly (CDRA)

The CDRA, built by Honeywell Aerospace, has been the primary CO₂ removal system for the U.S. segment of the ISS since February 2001. It operates as a dual-bed, zeolite-based temperature-swing adsorption (TSA) system. Two sets of desiccant/adsorbent bed pairs alternate between adsorbing CO₂ from cabin air and desorbing it into space vacuum. The system supports a crew of up to six at approximately 0.4% CO₂ concentration.

The CDRA has suffered from persistent reliability issues — most notably zeolite pellet dust contaminating downstream components, degraded seals, and filter clogging — making it a high-maintenance system requiring regular crew intervention. ACE Clearwater Enterprises has manufactured replacement inner chambers, end caps, and specialized filters for the CDRA in partnership with Honeywell and NASA.

### 1.2 The 4-Bed CO₂ Scrubber (4BCO₂)

The 4BCO₂ is NASA Marshall Space Flight Center’s evolution of the CDRA, developed with collaboration from NASA Johnson. It incorporates lessons from CDRA’s failure modes: cylindrical beds replace rectangular ones, redesigned heater cores eliminate void spaces, new dust filters capture sorbent particles, and improved valves extend operating lifetimes. The sorbent selection process evaluated BASF 13X and Grace MS544 C 13X zeolites, both proven robust under humid and dry conditions. The goal is continuous, failure-free operation for nearly 20,000 hours.

### 1.3 Russian Vozdukh System

The Vozdukh system on the ISS Russian segment uses a 3-bed amine-based adsorbent rather than zeolite, supporting a crew of six and removing approximately 120 liters of CO₂ per hour. It operated effectively for years, though gradual degradation of its functional capacity eventually led to the CDRA assuming primary CO₂ removal duties for the entire station.

-----

## 2. Top Companies Working on Next-Generation Lunar Life Support

### 2.1 Honeywell Aerospace — The ECLSS Prime

**Role:** Industry leader and legacy provider of ISS CDRA systems; developer of next-generation CDRILS technology.

Honeywell is developing the **Carbon Dioxide Removal by Ionic Liquid Sorbent (CDRILS)** system, which represents a paradigm shift from solid sorbent to liquid absorbent CO₂ removal. CDRILS uses an ionic liquid mixture containing 1-ethyl-3-methylimidazolium acetate (EMIM[Ac]) with hollow fiber membrane contactors for continuous CO₂ absorption and desorption. The system has been in development with NASA since 2018 and has progressed from breadboard to brassboard to a full-scale four-crew prototype. A flight demonstration on the ISS is targeted for 2028.

Key advantages of CDRILS over the CDRA include:

- Continuous flow processing (no batch cycling between beds)
- Can maintain CO₂ partial pressure below 2 mmHg — half that of CDRA
- Eliminates the need for a CO₂ compressor and accumulator (saving 291.1 kg of equivalent system mass)
- Can also handle humidity control and significant trace contaminant removal
- Lower volume, mass, power, and cooling requirements

Honeywell has also integrated a **Precision Combustion Inc. (PCI) Sabatier reactor** directly into the CDRILS flight demonstration unit, combining CO₂ removal and oxygen recovery into a single half-rack package. The Honeywell **Methane Pyrolysis Reactor** can recover up to 95% of oxygen from CO₂, far exceeding the ISS’s 50% recovery rate. The carbon byproduct is deposited as a clean, non-sooty material that could potentially serve as a building material on the Moon.

Honeywell is also exploring **CDRILS-M** (CDRILS for Mobility) — a variant tailored for Mars exploration spacesuits (mxEMU), providing CO₂ and humidity control in the suit ventilation loop while minimizing losses to the environment.

### 2.2 Paragon Space Development Corporation — The Systems Integrator

**Role:** ECLSS designer for NASA Lunar Gateway HALO module; specialist in life support, thermal control, and ISRU.

Paragon is responsible for the design and implementation of the HALO (Habitation and Logistics Outpost) ECLSS for the Lunar Gateway, under a ~$100M subcontract from Northrop Grumman (awarded May 2021). The HALO ECLSS maintains safe levels of oxygen, CO₂, humidity, and trace contaminants for visiting crew during stays of up to 90 days.

Paragon brings a distinctive portfolio of patented technologies:

- **Ionomer-membrane Water Processing (IWP)** — used on Boeing’s CST-100 Starliner for humidity control with no moving parts
- **Brine Processor Assembly (BPA)** — launched to ISS in February 2021, increasing water loop closure from 93% to over 98%
- **Primary Urine Processor (PUP)** — designed to replace two ISS systems with one compact unit
- **Atmospheric Monitoring System (AMS)** — detects harmful gases with integrated microgravity smoke detection

Paragon has also been developing lunar thermal control systems under a NASA Tipping Point contract, leading a team including Boeing, Texas A&M, NASA Glenn, and NASA Johnson to maintain acceptable operating temperatures through the full lunar day/night cycle. Their “Common ECLSS” design philosophy allows systems to work across multiple vehicles and mission types.

In ISRU, Paragon’s **IHOP** system (funded by NASA NextSTEP-2) combines water purification and electrolysis for lunar water processing — directly relevant to oxygen generation for life support.

### 2.3 Collins Aerospace (RTX Corporation)

**Role:** ECLSS provider for commercial orbital habitats; legacy Apollo and ISS spacesuit life support.

Collins Aerospace was awarded a $2.6M contract in 2021 for ECLSS supporting a privately owned orbital outpost in LEO. Their offering includes air revitalization and pressure control (cabin fans, heat exchangers, CO₂ removal, trace contaminant control, valves, regulators, smoke detection) and active thermal control. Collins also provides the Sabatier CO₂ reduction system currently operational on the ISS.

Collins has extensive heritage from the Apollo era through the current ISS EMU spacesuits, though they exited NASA’s next-generation spacesuit (xEVAS) contract in 2024 due to schedule and cost challenges. They continue supporting the existing ISS EMU under the Extravehicular Space Operations Contract.

### 2.4 Precision Combustion, Inc. (PCI)

**Role:** Sabatier reactor specialist; catalytic systems for CO₂ conversion.

PCI has developed a compact 4-crew Sabatier reactor that integrates directly with Honeywell’s CDRILS system, converting captured CO₂ and hydrogen into water and methane. The reactor’s waste heat is repurposed to heat the ionic liquid in the CDRILS system, saving approximately 72.5–145 W. PCI is a key member of the Honeywell-led Commercial ECLSS team.

### 2.5 Giner Labs (now Giner ELX / Plug Power)

**Role:** Oxygen generation via electrolysis.

Giner contributes advanced water electrolysis technology to the Commercial ECLSS team, generating oxygen from water produced by the Sabatier reactor. This closes the oxygen loop — a critical capability for lunar habitats where resupply is costly and infrequent.

### 2.6 Thales Alenia Space

**Role:** Prime contractor for ESA’s Lunar I-Hab module and Italy’s Lunar Multi-Purpose Habitat.

Thales Alenia Space in Turin is building the primary structure for the Lunar I-Hab module (launching on Artemis IV circa 2028), with JAXA providing the ECLSS, batteries, and thermal control. The I-Hab provides approximately 10 m³ of habitable volume for up to four astronauts for 30–90 day stays.

Thales is also leading an Italian industrial consortium for the Lunar Multi-Purpose Habitat, which requires cutting-edge life support solutions for the inhospitable lunar environment, including protection from regolith and survival of cold lunar nights.

### 2.7 Airbus Defence and Space

**Role:** ECLSS design for Starlab commercial space station; ISS Columbus module heritage.

Airbus is providing technical design and engineering for the Starlab station’s ECLSS, which leverages over 30 years of NASA and ESA investment in life support and thermal control. As presented at ICES 2025 in Prague, Starlab’s ECLSS uses modern implementations of ISS-proven technologies with exceptions for obsolete or significantly improved systems. The station targets a loop closure greater than 90%, with a continuous crew of four (up to eight temporarily) in a 450 m³ pressurized volume.

The Starlab team — Voyager Space, Airbus, Mitsubishi, MDA Space — is moving toward a Critical Design Review in late 2025, with launch planned on SpaceX’s Starship in 2028–2029. Barry Finger of Starlab Space and Onyx Aerospace are leading ECLSS architecture decisions.

### 2.8 Vast (Haven Stations)

**Role:** In-house ECLSS development for commercial space stations with iterative approach.

Vast is developing its own life support systems in-house at its Long Beach headquarters. Haven-1 (expected Q1 2027 launch) uses a simple open-loop ECLSS architecture suited to short-duration crewed missions. However, Vast is flying closed-loop ECLSS experiments on every Haven-1 mission to enable rapid iteration. As Vast’s Kris Young stated, the company expects to be on a 5th-generation ECLSS system by the time Haven-2 launches to support continuous human presence.

### 2.9 Blue Origin & Sierra Space (Orbital Reef)

**Role:** Developing the Orbital Reef commercial station targeting a crew of 10.

As of late 2024, Blue Origin and Sierra Space had demonstrated water recycling from urine and contaminant identification. Sierra’s VP Shawn Buckley has stated these systems are designed with deep-space and Mars extensibility in mind. Assembly was planned to begin in 2027.

-----

## 3. Beyond ISS Scale: Who Is Working on Larger Systems?

### 3.1 The Scale Challenge

The ISS has approximately 900 m³ of pressurized volume and supports a crew of typically 6–7. Current ECLSS is sized for this: each CDRA unit handles approximately 4 crew members’ worth of CO₂. The question of whether anyone is designing significantly larger-scale, more robust systems — capable of supporting larger crews in lunar base scenarios — reveals an important gap in the current landscape.

### 3.2 Starlab: The Single-Launch Approach

Starlab’s 450 m³ pressurized volume in a single 8-meter-diameter module represents the most ambitious near-term step. While designed for 4 continuous crew (up to 8), the single-module approach with a 30-year design life means its ECLSS must be significantly more robust than ISS-era systems. The design leverages the newer capabilities of commercial hardware suppliers that NASA’s and ESA’s investments enabled, with Onyx Aerospace contributing alongside Airbus.

### 3.3 China’s ILRS and Yuegong-1: The Only True Large-Scale Demonstrator

The most advanced large-scale life support demonstration belongs to China. The **Yuegong-1 (Lunar Palace 1)** at Beihang University in Beijing is a 500 m³, 160 m² bioregenerative life support system (BLSS) that successfully sustained a crew of four for 370 days in 2017–2018 — the world record for the longest stay in a self-contained laboratory. The facility includes two plant cultivation cabins (58 m²), a living area (42 m²) with bedrooms, dining room, bathroom, and waste disposal.

Yuegong-1 demonstrated 100% atmospheric regeneration through plants and microalgae, with 55% food self-sufficiency. The CNSA has adopted a phased approach for the International Lunar Research Station (ILRS): construction beginning in the 2030s with a vision of large-scale replenishment of survival materials by around 2040.

A critical August 2025 paper in *npj Microgravity* warns that NASA has fallen behind China in bioregenerative life support capabilities. The CNSA has successfully demonstrated closed-system operations for atmosphere, water, and nutrition while sustaining a crew of four for a full year — while no other official programs are pursuing fully integrated, closed-loop bioregenerative architecture for lunar habitats.

### 3.4 ESA’s MELiSSA Programme

ESA’s Micro-Ecological Life Support System Alternative (MELiSSA) has been developing bioregenerative component technologies for decades but has never approached closed-systems human testing. MELiSSA focuses on using biological loops (algae, bacteria, higher plants) to regenerate atmosphere and water but remains at the component research level.

### 3.5 The Honeywell-Paragon Commercial ECLSS: Scalable by Design

The Commercial ECLSS architecture developed by Honeywell, Paragon, PCI, and Giner is designed to be mission-adaptable. The CDRILS system, for instance, can be configured for open-loop (CO₂ removal and humidity control with overboard venting) or closed-loop (CO₂ removal, reduction via Sabatier, and oxygen recovery). For a Mars transit mission or a large lunar base, the system’s modular design would allow multiple units to scale to larger crew sizes, with equivalent system mass (ESM) significantly lower than the ISS ECLSS for both LEO and Mars transit configurations.

-----

## 4. CO₂ Capture Technologies: A Comparative Analysis

### 4.1 Temperature-Swing Adsorption (TSA) — Zeolite-Based

**How it works:** Air passes through beds of zeolite molecular sieve pellets (typically 5A or 13X types). CO₂ molecules are selectively adsorbed onto the zeolite surface. When a bed is saturated, it is heated to desorb the CO₂, which is vented to space or routed to a Sabatier reactor. Two or more beds alternate between adsorption and desorption.

**Current systems:** CDRA, 4BCO₂

**Advantages:** Flight-proven, well-understood, no expendable chemicals
**Disadvantages:** Batch operation (cycling between beds), zeolite dust generation, maintenance-intensive, less efficient at lower CO₂ partial pressures, requires vacuum for desorption

### 4.2 Amine-Based Adsorption

**How it works:** Similar to zeolite TSA but uses amine-functionalized sorbents. The Russian Vozdukh system used a 3-bed amine configuration.

**Advantages:** Effective at higher crew loads, proven on ISS Russian segment
**Disadvantages:** Amine degradation over time, system complexity

### 4.3 Ionic Liquid Absorption (CDRILS)

**How it works:** Air contacts an ionic liquid mixture (EMIM[Ac] with promoter and water) in a hollow fiber membrane scrubber. The ionic liquid selectively absorbs CO₂ and is continuously pumped to a separate hollow fiber membrane stripper where heat (~60°C) and vacuum desorb the CO₂ for downstream processing. The regenerated ionic liquid recirculates.

**Current systems:** CDRILS (Honeywell/NASA, ISS flight demo 2028)

**Advantages:** Continuous flow (no batch cycling), lower CO₂ partial pressure achievable (2 mmHg vs 4 mmHg), combines CO₂ removal with humidity and trace contaminant control, eliminates need for compressor/accumulator, lower SWAP (size, weight, and power)
**Disadvantages:** Ionic liquid degrades at regeneration temperatures over 2+ years (though operating volume can be oversized to accommodate), hollow fiber membranes need qualification for long-duration spaceflight, liquid management in microgravity requires careful engineering

### 4.4 CO₂ Deposition (CDep) — Cryogenic Capture

**How it works:** NASA Ames Research Center’s CDep system uses Stirling cryocoolers to generate cold surfaces below 142K (-131°C). At this temperature, CO₂ directly deposits as dry ice from the cabin air onto the cold surface — a phase change from gas to solid without passing through a liquid state. The system cycles between deposition mode (capturing CO₂) and sublimation mode (recovering pure CO₂ gas). An ionic liquid dehumidification stage upstream removes 96% of humidity to reduce power draw and improve CO₂ purity.

A full-scale 4-crew CDep system at Ames requires approximately 83W for the deposition stage at 130K and 44W for precooling at 190K. The air flow rate for 4-crew at 2 mmHg CO₂ partial pressure is 26 SCFM.

**Advantages:** No expendable materials whatsoever, no vacuum required, minimal moving parts, high reliability, dormancy-resilient (important for intermittently crewed lunar habitats), also removes trace contaminants, produces pressurized pure CO₂ directly (no compressor needed), can leverage deep-space radiative cooling on the lunar surface
**Disadvantages:** Power-intensive due to cryocooler requirements, thermal management complexity, still at prototype stage (not yet flight-demonstrated), requires robust cryocooler reliability for multi-year missions

A CDep VOC variant is also under development for separating volatile organic contaminants from captured CO₂ before it enters a Sabatier reactor, as presented at ICES 2025 in Prague.

### 4.5 Liquid Amine CO₂ Removal (LACR)

Also under development at NASA Ames, LACR uses capillary forces to let liquid sorbents and air interact without mixing in microgravity. This is another non-zeolite approach being evaluated for next-generation air revitalization.

### 4.6 Bioregenerative (Plant/Algae-Based)

**How it works:** Higher plants, microalgae (such as Chlorella or Limnospira/Spirulina), and other photosynthetic organisms absorb CO₂ and produce O₂ through photosynthesis. In integrated systems like Yuegong-1 or MELiSSA, this is combined with food production and water recycling.

**Advantages:** Multi-functional (atmosphere, food, water, psychological wellbeing), sustainable for very long-duration missions, potential for near-complete loop closure
**Disadvantages:** Slow response to transient CO₂ spikes, large volume and mass requirements, susceptibility to biological contamination and disease, requires radiation shielding on the lunar surface, decades of development still needed for operational maturity

-----

## 5. HVAC Adaptation for Lunar Environments

### 5.1 Why Terrestrial HVAC Matters

No company is directly “adapting” a commercial building HVAC system for the Moon in the way one might adapt a product for a new market. However, the convergence is real and accelerating in several areas.

### 5.2 Honeywell’s Cross-Industry Approach

Honeywell — a dominant player in both building HVAC/IAQ systems and space ECLSS — explicitly states they are “leveraging newer technologies and components from aerospace and other industries.” The CDRILS concept draws directly from terrestrial industrial gas-liquid contacting technology (hollow fiber membrane contactors are widely used in industrial CO₂ capture). The thermal swing principles, heat exchanger designs, and fan/blower systems in space ECLSS share engineering DNA with terrestrial HVAC.

### 5.3 Thermal Control on the Lunar Surface

The lunar environment presents thermal challenges far beyond LEO. Surface temperatures range from approximately -173°C during lunar night to +127°C during lunar day at the equator, with the south pole (the target for Artemis) experiencing more moderate but still extreme variations. Paragon’s NASA Tipping Point thermal control program (with Boeing and Texas A&M) is specifically designing systems to maintain acceptable temperatures through this cycle — essentially an extreme-environment HVAC problem.

### 5.4 Starlab’s Terrestrial Heritage

Starlab’s ECLSS development explicitly leverages 30+ years of NASA and ESA investment while using “modern implementations” — meaning commercially available components wherever possible. The habitat’s single 8-meter-diameter module with 450 m³ volume is closer to a small building than a spacecraft in scale, pushing ECLSS toward architectural-scale environmental control.

### 5.5 Hilton’s Involvement

Hilton’s partnership with Starlab — designing crew suites and communal areas leveraging their “100-year legacy of innovation in hospitality” including in-room air conditioning — represents a unique convergence of hospitality HVAC expertise with space habitat design, even if the ECLSS itself remains aerospace-grade.

-----

## 6. Supply Chain Breakdown

The life support supply chain for lunar habitats is a multi-tiered ecosystem spanning raw materials, specialized components, system integrators, and prime contractors.

### Tier 1: Raw Materials & Sorbents

|Material                      |Function                      |Key Suppliers                                                            |
|------------------------------|------------------------------|-------------------------------------------------------------------------|
|Zeolite 5A, 13X               |CO₂ adsorption (CDRA, 4BCO₂)  |BASF, Grace (MS544 C), Arkema (Siliporite), Zeochem, UOP (Honeywell)     |
|EMIM[Ac] ionic liquid         |CO₂ absorption (CDRILS)       |Specialty chemical suppliers (IoLiTec, Sigma-Aldrich/Merck)              |
|LiOH (Lithium Hydroxide)      |Emergency/backup CO₂ scrubbing|Albemarle, Livent (Arcadium Lithium), SQM                                |
|Activated carbon/alumina      |Trace contaminant control     |Cabot, Calgon Carbon, BASF                                               |
|Ionomer membranes (Nafion)    |Water processing (IWP)        |Chemours (formerly DuPont)                                               |
|Hollow fiber membranes        |Gas-liquid contacting (CDRILS)|Celgard (Polypore/Asahi Kasei), Pall Corporation, Honeywell (proprietary)|
|Stirling cryocooler components|Cold surface generation (CDep)|Sunpower (Ametek), Lockheed Martin, Thales Cryogenics                    |
|Catalysts (Ru, Ni on Al₂O₃)   |Sabatier CO₂ reduction        |Johnson Matthey, BASF, PCI (proprietary formulations)                    |

### Tier 2: Component Manufacturers

|Component                  |Function              |Key Suppliers                                                   |
|---------------------------|----------------------|----------------------------------------------------------------|
|Blowers/fans               |Air circulation       |Honeywell, Micronel, EBM-Papst (adapted for space)              |
|Heat exchangers            |Thermal management    |Honeywell, Meggitt (Parker), Collins Aerospace                  |
|Water electrolyzers        |O₂ generation         |Giner ELX (Plug Power), Proton OnSite (Nel)                     |
|Sensors (CO₂, O₂, humidity)|Atmospheric monitoring|Paragon (AMS), Honeywell Analytics, SST Sensing                 |
|Valves & regulators        |Pressure control      |Moog, Parker Hannifin, Cobham                                   |
|HEPA/ULPA filters          |Particulate removal   |Pall, Donaldson, BASF                                           |
|Sabatier reactor assemblies|CO₂ → H₂O + CH₄       |Precision Combustion Inc. (PCI)                                 |
|Precision machined housings|CDRA/4BCO₂ tanks      |ACE Clearwater Enterprises                                      |
|Solar arrays               |Power for ECLSS       |DHV Technology (Vast), Spectrolab (Boeing), SolAero (Rocket Lab)|

### Tier 3: Subsystem Integrators

|Company                  |Subsystems                                             |Programs                                     |
|-------------------------|-------------------------------------------------------|---------------------------------------------|
|Honeywell Aerospace      |CO₂ removal (CDRA, CDRILS), thermal control            |ISS, Commercial ECLSS, Exploration ECLSS     |
|Paragon Space Development|Full ECLSS integration, water recovery, thermal control|Gateway HALO, Axiom AxEMU, Starliner, StratEx|
|Collins Aerospace        |Air revitalization, pressure control, Sabatier         |Commercial LEO stations, ISS heritage        |
|Onyx Aerospace           |ECLSS architecture                                     |Starlab                                      |
|Airbus Defence & Space   |Habitat ECLSS design & manufacturing                   |Starlab, Columbus, ATV heritage              |
|JAXA                     |ECLSS, batteries, thermal control                      |Lunar I-Hab (Gateway)                        |

### Tier 4: Prime Contractors / Habitat Builders

|Company                   |Program                                                   |ECLSS Provider                 |
|--------------------------|----------------------------------------------------------|-------------------------------|
|Northrop Grumman          |HALO (Gateway)                                            |Paragon                        |
|Thales Alenia Space       |Lunar I-Hab (Gateway), Italian Lunar Multi-Purpose Habitat|JAXA (ECLSS), ESA contributions|
|Lockheed Martin           |Lunar inflatable habitat concepts, Orion                  |Internal + heritage systems    |
|Starlab Space LLC         |Starlab commercial station                                |Airbus/Onyx Aerospace          |
|Vast                      |Haven-1, Haven-2                                          |In-house                       |
|Blue Origin / Sierra Space|Orbital Reef                                              |Internal development           |
|Axiom Space               |Axiom Station                                             |Internal + subcontractors      |
|CNSA / Beihang University |Yuegong / ILRS                                            |Internal (Lunar Palace team)   |

### Critical Supply Chain Risks

**Zeolite obsolescence:** The sorbent used in the original CDRA became commercially unavailable, forcing the 4BCO₂ redesign to evaluate new zeolite candidates. This single-source vulnerability is a recurring concern.

**Ionic liquid maturity:** EMIM[Ac] degrades at CDRILS operating temperatures after approximately two years of continuous exposure. While the system can be oversized to compensate, ionic liquid stability and sourcing for multi-year lunar missions remains a development risk.

**Stirling cryocooler availability:** The CDep system depends on flight-proven Stirling coolers. While these are available from suppliers like Sunpower/Ametek and have satellite heritage, scaling to the reliability demands of a continuously crewed lunar habitat is untested.

**Geopolitical fragmentation:** The ISS ECLSS benefited from US-Russian collaboration (CDRA + Vozdukh). With no future US-Russian cooperation planned beyond ISS obligations, and the CNSA-Russia ILRS proceeding separately from the US-led Artemis Accords (55 signatories as of June 2025), the supply chain is splitting along geopolitical lines.

-----

## 7. Key Observations and Gaps

**No one is building a lunar-base-scale ECLSS today.** All current programs — Gateway HALO, Lunar I-Hab, Artemis Surface Habitat — are designed for 4 crew for 30–90 day stays. The Artemis Surface Habitat reference design uses Collins Pallet-based ECLSS subsystems constrained to fit through a standard NASA hatch (30.19” cross-section). True settlement-scale life support (8–12+ crew, continuous habitation for months or years) remains a paper exercise outside of China’s Yuegong program.

**CDep is the most promising breakthrough for lunar surface application.** The ability to leverage the Moon’s cold environment (permanently shadowed craters near the south pole reach approximately 40K) for radiative cooling could dramatically reduce the power requirements of cryogenic CO₂ capture, potentially making CDep more efficient on the lunar surface than in LEO.

**The CDRILS ISS flight demo in 2028 is a pivotal milestone.** If it succeeds, it could become the baseline air revitalization technology for all post-ISS crewed habitats, displacing zeolite-based systems.

**Bioregenerative systems are decades away from operational readiness.** Despite China’s lead, no BLSS is mature enough to significantly increase the autonomy of even a small lunar base. Physico-chemical ECLSS will remain the primary life support backbone for the foreseeable future, with biological systems supplementing gradually.

**The commercial space station race is driving ECLSS innovation faster than government programs.** Vast, Starlab, Orbital Reef, and Axiom are all investing in ECLSS as a competitive differentiator, with NASA’s 2030 ISS retirement deadline creating urgency. These LEO systems will inform the technology baseline for lunar surface habitats.

-----

## 8. Summary Technology Comparison

|Technology              |TRL            |Crew Scale           |Power (4-crew)    |Consumables            |Lunar Suitability                      |
|------------------------|---------------|---------------------|------------------|-----------------------|---------------------------------------|
|CDRA (Zeolite TSA)      |9 (operational)|4–6                  |~500W             |Zeolite replacement    |Moderate — proven but high maintenance |
|4BCO₂ (Improved Zeolite)|7–8            |4–6                  |~400W             |Improved zeolites      |Moderate — addresses CDRA failure modes|
|CDRILS (Ionic Liquid)   |5–6            |4 (prototype)        |~300W est.        |IL replenishment (~2yr)|High — continuous flow, low maintenance|
|CDep (Cryogenic)        |4–5            |4 (full-scale ground)|~130W (deposition)|None                   |Very High — leverages lunar cold       |
|Vozdukh (Amine TSA)     |9 (operational)|6                    |~400W             |Amine replacement      |Moderate — degradation concerns        |
|BLSS (Bioregenerative)  |3–4            |4 (ground demo)      |High (lighting)   |Biological inputs      |Future — 2040s for operational systems |

-----

*Sources: NASA Technical Reports Server, International Conference on Environmental Systems (ICES) proceedings 2018–2025, Honeywell Aerospace, Paragon Space Development Corporation, ESA, npj Microgravity (August 2025), Tech Briefs, SpaceNews, Aerospace America (July 2025).*
