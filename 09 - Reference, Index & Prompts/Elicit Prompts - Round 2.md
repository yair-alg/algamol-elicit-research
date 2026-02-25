---
title: "Elicit Prompts - Round 2"
source: Algamol Internal
type: prompt-engineering
date_created: 2026-02-12
status: ready-to-run
tags:
  - elicit
  - biosorption
  - ndfeb
  - defense-magnets
  - waste-treatment
  - compliance
  - magnet-manufacturing
---

# Elicit Prompts - Round 2

> Three extended research prompts designed for maximum Elicit output. Each targets a critical knowledge gap identified from the existing 60-note research vault. Prompts follow the systematic review structure that produced the best results in Round 1 (500 papers screened, 427 passed abstract, 40 extracted per report).

---

## Prompt 1: Microalgae Bioabsorption of Magnet Leachate Contaminants for Wastewater Regulatory Compliance

**Scope: This is exclusively about the wastewater treatment step. Not recovery. Not refinement. Only bioabsorption to bring leachate into regulatory discharge compliance.**

---

Run a structured literature review on the bioabsorption and biosorption performance of microalgae when exposed to the full chemical composition of NdFeB permanent magnet manufacturing waste leachates, with specific focus on regulatory wastewater compliance (not metal recovery or downstream refinement).

CONTEXT AND FRAMING:
NdFeB magnet manufacturing produces multiple waste streams (grinding sludge, polishing slurry, sintering residues, cutting swarf, coolant runoff, cleaning agent waste) that are leached or dissolved before discharge. The leachate contains not only target rare earth elements (Nd, Dy, Pr, Tb, Sm) but also high concentrations of iron (Fe), boron (B), cobalt (Co), copper (Cu), nickel (Ni), aluminum (Al), and residual process chemicals including cooling agents (water-soluble oils, synthetic coolants, semi-synthetic emulsions, mineral oil-based fluids), cleaning agents (alkaline degreasers, acid pickling solutions, surfactants, chelating agents like EDTA and NTA), and anti-corrosion additives. The research question is: how does each of these contaminant classes individually and collectively affect microalgae biosorption capacity, and can microalgae-based treatment bring complex magnet waste leachates into compliance with discharge limits (EU BAT-AEL for NFM and STM BREFs, US EPA NPDES permit limits, or equivalent national standards)?

INCLUSION CRITERIA:
- Microalgae species used as biosorbents or bioaccumulators in wastewater treatment applications
- Studies using real industrial effluents or synthetic multi-metal solutions that replicate magnet manufacturing leachate composition (Fe-dominant matrix with REE, Co, Cu, Ni, B, Al)
- Studies examining the effect of co-contaminants (cooling fluids, surfactants, organic carbon load, oils, chelating agents) on biosorption performance
- Studies reporting regulatory compliance metrics (final effluent concentration vs. discharge limits, not just % removal)
- Studies on iron interference with REE biosorption (competitive binding, precipitation masking, co-sorption)
- Studies on boron removal or tolerance by microalgae (boron is a persistent contaminant in NdFeB waste and has strict discharge limits in many jurisdictions)
- Publication date: 2010-2026, peer-reviewed journal articles and government/regulatory technical reports
- Laboratory, pilot, and commercial scale all included

EXCLUSION CRITERIA:
- Studies focused exclusively on metal recovery/refinement from loaded biomass (desorption step)
- Studies using only single-metal synthetic solutions with no relevance to multi-component waste
- Studies on macroalgae-only systems (include if compared to microalgae)
- Studies on non-aqueous waste treatment

DATA EXTRACTION TEMPLATE (for each qualifying study):

1. WASTE STREAM CHARACTERIZATION
   - Source type: grinding sludge leachate, polishing slurry, coolant waste, cleaning agent waste, mixed process water, synthetic analog
   - Full chemical composition of the leachate tested (all metals with concentrations in mg/L or g/L)
   - pH of raw leachate
   - Organic carbon load (COD, BOD, TOC if reported)
   - Presence and concentration of cooling agents, surfactants, oils, chelating agents
   - Temperature of waste stream

2. IRON AND BORON EFFECTS
   - Iron concentration in feed (mg/L)
   - Iron speciation (Fe2+, Fe3+, colloidal, precipitated)
   - Effect of iron on REE biosorption capacity (quantitative: % reduction in Nd/Dy/Pr capacity at given Fe:REE ratio)
   - Iron co-precipitation effects (does Fe(OH)3 formation at pH >3 mask or co-precipitate REEs?)
   - Boron concentration in feed (mg/L)
   - Boron removal efficiency by microalgae (%, final concentration achieved)
   - Boron discharge limits referenced (jurisdiction, limit value)

3. COOLING AND CLEANING AGENT EFFECTS
   - Type of cooling agent tested (water-soluble oil, synthetic coolant, semi-synthetic emulsion, mineral oil, specific brand/formulation if named)
   - Concentration of cooling agent in leachate (%, v/v, or mg/L)
   - Effect on microalgae viability (toxicity threshold, LC50 if reported)
   - Effect on biosorption capacity (% change in metal uptake compared to clean solution)
   - Type of cleaning agent tested (alkaline degreaser, acid pickle, surfactant, chelating agent)
   - Chelating agent interaction: does EDTA/NTA compete with biomass for metal binding? At what concentration does chelation overwhelm biosorption?
   - Oil and grease interference: does emulsified oil coat biomass surfaces and reduce adsorption sites?

4. BIOSORPTION PERFORMANCE IN MULTI-METAL SYSTEM
   - Microalgae species (genus, species, strain if available)
   - Biomass form (living, dried, immobilized, pre-treated)
   - For each metal in the leachate: removal efficiency (%), final concentration (mg/L), adsorption capacity (mg/g dry biomass)
   - Selectivity order: which metals are preferentially absorbed from the complex mixture?
   - Competing ion effects: quantitative data on how presence of Fe, Cu, Ni, Co affects REE uptake
   - pH optimization: what pH achieves maximum simultaneous compliance for all regulated metals?
   - Contact time to reach discharge-compliant concentration
   - Biomass dosage required (g/L) for compliance
   - Kinetic model fit (pseudo-first-order, pseudo-second-order, rate constants)
   - Isotherm model fit in multi-metal system (Langmuir, Freundlich, competitive Langmuir parameters)

5. REGULATORY COMPLIANCE ASSESSMENT
   - Regulatory framework referenced (EU BAT-AEL NFM/STM BREF, US EPA NPDES, national standards)
   - Specific discharge limits cited for each metal (mg/L)
   - Which metals in the leachate reached compliance after microalgae treatment?
   - Which metals did NOT reach compliance (residual concentration vs. limit)?
   - Was a polishing step required after biosorption (activated carbon, ion exchange, chemical precipitation)?
   - Sludge classification: is the metal-loaded biomass classified as hazardous waste? Under which framework?
   - Comparison to conventional treatment: how does microalgae performance compare to chemical precipitation + clarification for achieving the same discharge limits?

6. PROCESS CONFIGURATION
   - Reactor type (batch, continuous stirred-tank, packed column, biofilm reactor, raceway pond)
   - Hydraulic retention time (HRT)
   - Volumetric throughput (L/h, m3/day)
   - Biomass harvesting method (settling, centrifugation, filtration, flocculation)
   - Number of treatment stages (single-pass vs. multi-stage cascade)
   - Pre-treatment of leachate before biosorption (pH adjustment, oil skimming, filtration)

PRIORITIZE:
- Studies using real NdFeB manufacturing waste over synthetic solutions
- Studies that explicitly measure final effluent against discharge limits (not just % removal)
- Studies that test the effect of cooling agents, cleaning agents, or high iron concentrations on biosorption
- Multi-metal competitive biosorption data over single-metal studies
- Any pilot-scale (>10 L) or industrial demonstration
- Studies identifying which contaminants are the hardest to bring into compliance using biological treatment

EXPLAIN VARIABILITY:
- When biosorption performance varies widely across studies, interpret the cause: is it species-dependent, pH-dependent, iron-interference-dependent, or organic-contamination-dependent?
- Identify the rate-limiting contaminant for regulatory compliance (the metal or parameter that is hardest to treat to discharge levels)

OUTPUT FORMAT:
- Summary table: species vs. waste type vs. metals vs. removal efficiency vs. final concentration vs. compliance status vs. limiting factor
- Narrative synthesis: what is the current state of evidence for using microalgae as a compliance treatment step for magnet manufacturing leachate?
- Gap identification: what specific experiments or data are missing to validate this application?

---

## Prompt 2: High-Temperature Permanent Magnets in the Defense and Security Industry -- Manufacturing, Supply Chain, and Competitive Landscape

**Scope: How are high-temperature magnets manufactured, sold, and delivered to defense/security sector clients? What does the supply chain actually look like from raw material to installed component?**

---

Run a structured review of the manufacturing processes, supply chain logistics, and competitive landscape for high-temperature permanent magnets (SmCo and high-coercivity NdFeB grades) used specifically in defense and security applications, including guided munitions, radar systems, electronic warfare, satellite actuators, military-grade motors, and other high-reliability systems requiring operation above 150C.

CONTEXT AND FRAMING:
The defense and security sector requires permanent magnets that operate reliably at elevated temperatures (150C to 550C), withstand radiation, vibration, and thermal cycling, and meet strict supply chain traceability and domestic sourcing requirements (ITAR, DFARS, EU defense procurement rules). These are primarily SmCo (samarium-cobalt) magnets in grades like SmCo5 and Sm2Co17, and specialized high-coercivity NdFeB grades with heavy rare earth additions (Dy, Tb) or grain boundary diffusion treatments. This review should map the entire value chain from raw material sourcing through magnet block production, machining/cutting to final dimensions, magnetization, coating, qualification testing, and delivery to the defense integrator or OEM.

INCLUSION CRITERIA:
- Manufacturing processes for SmCo and high-temperature NdFeB magnets (powder metallurgy, sintering, hot pressing, die pressing, isostatic pressing)
- Supply chain structure for defense-grade magnets (who makes the blocks, who cuts them, who magnetizes, who qualifies, who delivers to the defense prime)
- Competitive landscape of magnet suppliers serving the defense sector (company names, locations, capabilities, certifications)
- Defense-specific qualification and testing requirements (MIL-STD, AS9100, ITAR compliance, DFARS 252.225-7014 domestic sourcing)
- Format in which magnets are sold: are they delivered as sintered blocks and cut/ground at the customer site, or delivered as finished-to-print components?
- Machining and finishing processes: wire EDM, surface grinding, slicing, lapping, tolerances achieved
- Waste generation during machining: what fraction of the block becomes waste (kerf loss, grinding sludge, broken/rejected pieces)?
- Publication date: 2010-2026, including peer-reviewed journals, defense industry reports, trade publications (Magnetics Magazine, Arnold Magnetic Technologies white papers, Vacuumschmelze technical notes), government procurement reports, and Congressional Research Service or equivalent defense supply chain analyses

EXCLUSION CRITERIA:
- Consumer-grade NdFeB magnets (standard temperature grades operating below 80C)
- Non-defense applications unless directly comparable in manufacturing process
- Pure materials science studies with no process or supply chain information

DATA EXTRACTION TEMPLATE:

1. MAGNET TYPES AND GRADES FOR DEFENSE
   - SmCo grades: SmCo5, Sm2Co17, with specific magnetic properties (BHmax, Hci, Br, Tc)
   - Maximum operating temperature for each grade (C)
   - NdFeB high-temperature grades: grade designations (e.g., N35UH, N38EH, N42AH), with Dy/Tb content (wt%)
   - Grain boundary diffusion treated NdFeB: process description, performance improvement, cost premium
   - Radiation tolerance specifications
   - Thermal cycling endurance (number of cycles, temperature range, property degradation %)
   - Defense applications by magnet type: which applications use SmCo vs. high-temp NdFeB and why?

2. MANUFACTURING PROCESS CHAIN
   - Raw material form: oxide, metal ingot, alloy strip, pre-alloyed powder
   - Powder production: jet milling, hydrogen decrepitation (HD), strip casting + jet milling
   - Powder particle size distribution specifications (microns)
   - Pressing method: die pressing (axial, transverse), isostatic pressing (CIP, HIP), injection molding
   - Alignment field strength (Tesla) and method (pulse, static, opposing die)
   - Sintering: temperature (C), atmosphere (Ar, vacuum), hold time (hours), cooling rate
   - Post-sinter heat treatment: temperature, duration, purpose (coercivity optimization)
   - Density achieved (g/cm3) vs. theoretical density
   - Typical block dimensions after sintering (mm): what size blocks are standard?
   - Surface treatments/coatings: Ni-Cu-Ni, epoxy, parylene, aluminum, passivation -- which for defense?

3. MACHINING, CUTTING, AND FINISHING
   - Do magnet manufacturers deliver finished-to-print parts, or deliver blocks/blanks that the defense prime (or a machine shop) cuts to final dimensions?
   - Cutting methods: wire EDM, ID saw, OD grinding, surface grinding, laser cutting
   - Tolerances achievable (mm or microns) for each cutting method
   - Surface finish requirements (Ra in microns)
   - Kerf loss per cut (mm) and total material waste from machining (% of starting block)
   - Grinding sludge composition: what is in the slurry? (metal particles, coolant, abrasive, water)
   - Broken/chipped/rejected parts rate (% scrap from machining fragility)
   - Magnetization step: when in the process chain does it happen? Before or after final machining?
   - Magnetization methods: pulse magnetizer, electromagnet, field strength required (Tesla)

4. SUPPLY CHAIN STRUCTURE AND LOGISTICS
   - Tier structure: who are the Tier-1 magnet suppliers to defense primes? (e.g., Arnold Magnetic Technologies, Vacuumschmelze, Shin-Etsu, TDK, Hitachi Metals, Bunting Magnetics, Electron Energy Corp, Star Magnetics, Dexter Magnetic Technologies)
   - Vertical integration: do any suppliers control the full chain from SmCo alloy to finished magnet?
   - Geographic concentration: what % of SmCo magnet manufacturing is in China vs. US vs. Europe vs. Japan?
   - ITAR-compliant supply chain: which suppliers have ITAR registration and can handle classified programs?
   - DFARS domestic sourcing: what happens when a defense prime needs magnets but the alloy or powder comes from China?
   - Lead times: from order placement to delivery of qualified defense-grade magnets (weeks/months)
   - Lot qualification: what testing is done per lot (magnetic property measurement, dimensional inspection, coating adhesion, environmental testing)?
   - Minimum order quantities and pricing structure (per piece, per kg, volume tiers)

5. COMPETITIVE LANDSCAPE -- DEFENSE MAGNET SUPPLIERS
   - Company name, headquarters location, manufacturing locations
   - Magnet types produced (SmCo, NdFeB, both)
   - Defense certifications held (AS9100, ITAR, NADCAP, ISO 9001 with defense supplement)
   - Key defense programs supplied (if public: missile systems, radar, satellite, EW, UAV, naval)
   - Revenue or market share estimates (if available)
   - Capacity (tonnes/year of sintered magnets)
   - Differentiation: what makes each supplier unique (proprietary grades, machining capability, integrated coating, vertically integrated supply)
   - Recent investments, expansions, or acquisitions (2020-2026)
   - Dependency on Chinese raw materials or semi-finished goods

6. DEFENSE-SPECIFIC REQUIREMENTS
   - MIL-STD specifications referenced for permanent magnets (MIL-M-38510, MIL-PRF-xxxxx, or current equivalents)
   - Qualification testing protocols: thermal aging, salt spray, vibration, shock, altitude, humidity
   - Traceability requirements: lot tracking, material certificates, country-of-origin documentation
   - Obsolescence management: what happens when a qualified magnet grade is discontinued?
   - Second-source qualification: how long and how expensive to qualify an alternative supplier?
   - Export control: are certain magnet grades or compositions controlled under EAR/ITAR?

PRIORITIZE:
- Supply chain structure documentation (who makes what, who delivers to whom)
- Waste generation data from machining/cutting operations (this directly feeds Algamol's value proposition)
- Defense-specific qualification and testing requirements
- SmCo supply chain data (less documented than NdFeB, more critical for high-temperature defense applications)
- Any data on the fraction of magnet material lost as waste during defense-grade machining (tighter tolerances = more waste)

OUTPUT FORMAT:
- Supply chain flow diagram (text description): raw material -> alloy -> powder -> pressing -> sintering -> block -> machining -> coating -> magnetization -> qualification -> delivery
- Competitive matrix: supplier vs. capabilities vs. certifications vs. geography vs. magnet types
- Waste generation summary: what percentage of starting material becomes waste at each manufacturing step, and what form does it take?
- Gap identification: what is unknown about the defense magnet supply chain that matters for a wastewater treatment technology provider?

---

## Prompt 3: Engineering-Level Detail on Magnet Manufacturing Waste Generation, Disposal, and Current Treatment Processes

**Scope: Extreme technical detail on what waste is produced, how much, what it costs to get rid of it, and exactly what treatment processes are used today. Written for an experienced process engineer.**

---

Run a comprehensive technical review of the waste streams generated during NdFeB and SmCo permanent magnet manufacturing, with engineering-level detail on waste volumes, compositions, current treatment and disposal methods, associated costs, and regulatory requirements. This review should be written at the level of detail required by a senior process or environmental engineer designing a treatment system, including specific chemical names, concentrations, temperatures, densities, flow rates, equipment specifications, and process step sequences.

CONTEXT AND FRAMING:
A permanent magnet manufacturing facility (1,000-10,000 tonnes/year sintered magnet output) generates waste at every process step: powder handling, pressing, sintering, machining (cutting, grinding, lapping), surface treatment (cleaning, etching, coating), and quality rejection. The waste streams include metallic fines and sludge, spent coolants, cleaning solutions, coating bath drag-out, rinse waters, off-specification magnets, furnace residues, and air filtration dust. Each stream has a distinct composition, volume, hazard classification, and treatment pathway. This review should map every waste stream from generation point through collection, characterization, treatment, and final disposition (discharge, landfill, recycling, or hazardous waste facility).

INCLUSION CRITERIA:
- Peer-reviewed studies, government technical reports, environmental impact assessments, BREF documents, EPA technical guidance, and industry engineering handbooks covering magnet manufacturing waste
- Process engineering data: flow rates (L/h, m3/day), concentrations (mg/L, g/L, wt%), temperatures (C), pH, density (g/cm3, kg/m3), particle size distributions (microns)
- Treatment technology specifications: equipment types, dimensions, throughput capacity, chemical dosages, residence times, removal efficiencies per stage
- Cost data: CAPEX for treatment equipment, OPEX for chemicals/energy/labor/sludge disposal, per-unit costs (USD/m3 treated, USD/tonne waste disposed)
- Regulatory limits referenced with specific jurisdiction and numeric values
- Publication date: 2005-2026 (broader window to capture foundational engineering references)

EXCLUSION CRITERIA:
- Pure materials science studies with no process engineering or waste generation data
- End-of-life magnet recycling (this is about manufacturing waste only, not post-consumer scrap)
- Studies on waste from other industries unless directly analogous to magnet manufacturing waste composition

DATA EXTRACTION TEMPLATE:

1. WASTE STREAM INVENTORY BY PROCESS STEP

   A. POWDER HANDLING AND PRESSING
   - Waste type: oxidized powder, off-spec powder, press rejects, airborne fines (collected by dust extraction)
   - Composition: Nd2Fe14B alloy particles, Nd-rich grain boundary phase, surface oxides (Nd2O3, Fe2O3)
   - Particle size: typical range (microns) for jet-milled NdFeB powder and pressing dust
   - Volume generated: kg waste per tonne finished magnet (yield loss %)
   - Hazard classification: is NdFeB powder pyrophoric? At what particle size? What safety measures?
   - Current disposal: recycled back to melt? Sold as scrap? Landfilled? Sent to specialty recycler?

   B. SINTERING AND HEAT TREATMENT
   - Furnace residues: composition of furnace deposits, crucible/boat contamination, vacuum pump oil contamination
   - Off-gas composition: what volatilizes during sintering at 1050-1100C? (Nd vapor, Fe vapor, binder burnout products)
   - Rejects: magnets that fail density, dimensional, or magnetic property checks post-sinter
   - Volume: % of sintered output that fails QC
   - Disposition of rejects: re-processed (hydrogen decrepitation to reclaim powder), downgraded, or scrapped

   C. MACHINING (CUTTING, GRINDING, LAPPING)
   - This is the primary waste-generating step. Detailed breakdown required:
   - Wire EDM waste: wire material (brass, molybdenum), dielectric fluid (deionized water), metal particles in dielectric, filter cake composition
   - Grinding sludge/slurry:
     * Carrier fluid: water-based coolant, oil-based coolant, or semi-synthetic? Specific product names if available
     * Coolant composition: base fluid, emulsifiers, biocides, corrosion inhibitors, extreme-pressure additives, pH buffers
     * Metal content in sludge: Nd, Fe, B, Dy, Pr, Co, Cu, Ni concentrations (wt% in dried solite, mg/L in liquid phase)
     * Abrasive particles: diamond (for grinding), SiC, Al2O3, CBN (cubic boron nitride) -- which are used for NdFeB?
     * Particle size of metal swarf in sludge (microns)
     * Density of grinding sludge (g/cm3 or kg/m3, both as-generated slurry and dewatered cake)
     * Volume generated: liters of sludge per tonne of machined magnet; kg of dried solids per tonne
     * Temperature of coolant during grinding (C)
     * Coolant flow rate during grinding (L/min)
     * Coolant replacement frequency and spent coolant volume (L/year for a facility producing X tonnes/year)
   - Cutting (ID saw, OD saw):
     * Blade material and coolant used
     * Kerf width (mm) and material loss per cut
     * Swarf composition vs. grinding sludge composition (differences)
   - Lapping and polishing:
     * Abrasive slurry composition (diamond suspension, colloidal silica, alumina)
     * Slurry concentration and flow rate
     * Waste slurry metal content after lapping
   - TOTAL MATERIAL LOSS: what fraction of the sintered block ends up as waste after all machining steps? (Express as % for typical magnet geometries: disc, arc segment, block, ring)

   D. SURFACE TREATMENT AND COATING
   - Pre-treatment cleaning:
     * Alkaline degreasing bath: composition (NaOH concentration, surfactant type, temperature C, immersion time)
     * Acid pickling/etching: acid type (HNO3, HCl, H3PO4, citric acid), concentration (mol/L or wt%), temperature, immersion time
     * Rinse water: number of rinse stages, water volume per unit area (L/m2), metal drag-out concentration (mg/L)
   - Electroplating (Ni-Cu-Ni coating):
     * Nickel bath (Watts bath): NiSO4 concentration (g/L), NiCl2 (g/L), H3BO3 (g/L), pH, temperature (C), current density (A/dm2)
     * Copper bath: CuSO4 concentration (g/L), H2SO4 (g/L), brightener additives, temperature (C)
     * Drag-out: volume of plating solution carried out per batch (L/m2)
     * Rinse water contamination: Ni, Cu concentrations in spent rinse (mg/L)
     * Bath maintenance waste: carbon treatment sludge, anode sludge, filtered precipitates
     * Bath lifetime and replacement frequency
   - Alternative coatings:
     * Epoxy coating: solvent waste, overspray
     * Phosphate coating: bath composition, sludge generation
     * Aluminum sputtering or evaporation: target waste, chamber cleaning waste
   - TOTAL WASTEWATER from surface treatment: volume (m3/day) per 1,000 tonnes/year facility, approximate composition

   E. QUALITY REJECTION AND PACKAGING
   - Rejection rate at final inspection (%)
   - Disposition of rejected magnets: rework, scrap to recycler, landfill
   - Packaging waste (minimal but include if significant)

2. WASTE CHARACTERIZATION AND HAZARD CLASSIFICATION

   - For each waste stream above:
     * EU Waste Framework Directive classification (hazardous vs. non-hazardous, specific waste codes)
     * US EPA RCRA classification (characteristic hazardous waste: D004-D011 for metals, or listed waste)
     * Leachability (TCLP or equivalent test results for NdFeB sludge)
     * Flash point of oil-based sludge (if applicable)
     * Pyrophoricity of fine metal particles (spontaneous ignition risk at what particle size?)
     * Radioactivity (natural radioactivity of rare earth concentrates, if relevant)
   - Combined wastewater characterization:
     * pH range
     * Total suspended solids (TSS, mg/L)
     * Chemical oxygen demand (COD, mg/L)
     * Oil and grease (mg/L)
     * Total metals (by element, mg/L)
     * Boron (mg/L)
     * Fluoride (mg/L, if HF used in any step)
     * Temperature (C)

3. CURRENT TREATMENT PROCESSES -- STEP-BY-STEP ENGINEERING DETAIL

   A. WASTEWATER TREATMENT PLANT (conventional chemical treatment)
   - Process flow sequence, in order:
     * Step 1: Oil skimming or dissolved air flotation (DAF) -- equipment type, oil removal efficiency (%), operating parameters
     * Step 2: pH adjustment -- target pH, reagent (NaOH, Ca(OH)2, Na2CO3), dosage (g/L or kg/m3), mixing intensity (RPM, G-value)
     * Step 3: Chemical precipitation -- reagent type and dosage for each metal (lime, NaOH, Na2S, FeCl3 for co-precipitation), target pH for optimal precipitation of each metal, order of additions
     * Step 4: Coagulation/flocculation -- coagulant type (FeCl3, alum, PAC), flocculant type (anionic/cationic polyelectrolyte, specific product if named), dosage (mg/L), mixing time and intensity
     * Step 5: Clarification/settling -- clarifier type (circular, lamella plate, inclined plate), surface loading rate (m3/m2/h), sludge blanket depth, overflow rate
     * Step 6: Sludge dewatering -- method (filter press, belt press, centrifuge, drying beds), solids concentration of feed sludge (% w/w), cake solids achieved (% w/w), filtrate quality (mg/L metals), polymer dosage for conditioning (kg/tonne dry solids)
     * Step 7: Polishing (if required) -- sand filtration, activated carbon adsorption, ion exchange resin (type, capacity, regeneration cycle), membrane filtration (MF, UF, NF, RO -- pore size, flux, rejection %)
     * Step 8: Final effluent monitoring and discharge
   - For each step: residence time, equipment dimensions for a reference facility size (1,000 tonne/year magnet output), energy consumption (kWh/m3)

   B. SLUDGE MANAGEMENT
   - Dewatered sludge composition (wt% of each metal, moisture content)
   - Sludge volume generated: tonnes/year for a 1,000 tonne/year facility
   - Stabilization/solidification: is the sludge stabilized before disposal? Method (cement, pozzolanic, polymer)?
   - Transport: distance to disposal facility (typical range, km), transport cost (USD/tonne)
   - Disposal method: secure hazardous waste landfill, cement kiln co-processing, metals recycler, deep well injection
   - Disposal cost: USD/tonne or USD/m3 for each disposal pathway
   - Recycling option: is any facility currently recovering REE from magnet manufacturing sludge at commercial scale? If so: name, location, technology, throughput, cost

   C. COOLANT MANAGEMENT
   - Coolant lifecycle: fresh preparation (concentration, mixing), in-use monitoring (pH, concentration, bacteria count, tramp oil), rejection criteria (when is coolant replaced?)
   - Spent coolant treatment: cracking (acid, salt, or heat), oil/water separation, metal removal, biological treatment of organic fraction
   - Volume of spent coolant generated per year per facility
   - Disposal cost for spent coolant (USD/m3)
   - Coolant recycling: is on-site coolant recycling practiced? Equipment type (centrifugal separator, vacuum evaporator, membrane system), cost

   D. PLATING BATH AND RINSE WATER TREATMENT
   - Spent bath treatment: is it treated on-site or sent to hazardous waste facility?
   - Nickel recovery from spent Watts bath: electrolytic recovery, evaporative concentration
   - Rinse water treatment: drag-out reduction (counter-current rinsing stages), ion exchange for Ni/Cu recovery
   - Costs for plating waste treatment

4. COST STRUCTURE -- DETAILED BREAKDOWN

   For a reference facility producing 1,000 tonnes/year of sintered NdFeB magnets:

   A. WASTE GENERATION VOLUMES
   - Total wastewater generated (m3/year)
   - Total sludge generated (wet tonnes/year, dry tonnes/year)
   - Total spent coolant (m3/year)
   - Total spent plating chemicals (m3/year or tonnes/year)
   - Total solid scrap/rejects (tonnes/year)

   B. TREATMENT COSTS (CAPEX)
   - Wastewater treatment plant: construction cost (USD) for a system sized for the facility
   - Major equipment items: clarifier, filter press, chemical dosing systems, pumps, tanks, instrumentation
   - Sludge handling equipment: dewatering, storage, loading

   C. TREATMENT COSTS (OPEX, annual)
   - Chemicals: lime, NaOH, FeCl3, polymer, acid for pH adjustment -- USD/year
   - Energy: pumping, mixing, dewatering, air supply -- kWh/year and USD/year
   - Labor: operators, lab technicians, compliance reporting -- FTEs and USD/year
   - Maintenance: 3-5% of CAPEX annually
   - Monitoring and laboratory: effluent sampling, analysis, regulatory reporting -- USD/year
   - Sludge disposal: transport + landfill or recycler fee -- USD/year (this is often the largest single cost)
   - Spent coolant disposal: USD/year
   - Permitting and compliance: annual permit fees, reporting costs

   D. TOTAL COST OF WASTE MANAGEMENT
   - Total annual cost (USD/year) for the reference facility
   - Cost per tonne of magnet produced (USD/tonne)
   - Cost per m3 of wastewater treated (USD/m3)
   - Cost per tonne of sludge disposed (USD/tonne)
   - Breakdown: what % of total cost is chemicals, energy, labor, sludge disposal, compliance?

   E. VALUE OF METALS IN WASTE
   - Total REE content in annual sludge output (kg Nd, kg Dy, kg Pr, kg Tb, kg Sm)
   - Market value of REEs in sludge at current prices (USD)
   - Ratio: value of recoverable metals vs. cost of sludge disposal (is recovery economically motivated, or is compliance cost avoidance the primary driver?)
   - Iron content in sludge: is it economically recoverable or is it a diluent?
   - Boron content: any recovery value?

5. REGULATORY FRAMEWORK -- SPECIFIC LIMITS

   - EU: BAT-AEL from NFM BREF and STM BREF -- specific numeric limits for each metal in mg/L for direct discharge and indirect discharge (to municipal WWTP)
   - US: EPA Effluent Limitation Guidelines (ELG) for Metal Finishing (40 CFR 433) and Nonferrous Metals (40 CFR 421) -- daily maximum and monthly average for each metal
   - China: GB 25467-2010 (Emission Standard for Rare Earth Industry) -- specific limits
   - Japan: Water Pollution Control Act limits for rare earth processing
   - List the numerical discharge limit (mg/L) for: Nd, Dy, Pr (if regulated individually or as total REE), Fe, B, Cu, Ni, Co, Zn, total suspended solids, pH, COD, oil and grease
   - Which contaminant is typically the most difficult to meet discharge limits for in magnet manufacturing wastewater? Why?

6. PROCESS ALTERNATIVES AND EMERGING TECHNOLOGIES
   - Is anyone using biological treatment (biosorption, constructed wetlands, algae-based systems) for magnet manufacturing wastewater today?
   - Membrane-based treatment: any adoption of NF or RO for REE-containing wastewater?
   - Selective adsorbents: functionalized resins, MOFs, or chelating materials tested on magnet waste?
   - Zero-liquid-discharge (ZLD) systems: any magnet manufacturers operating ZLD? Equipment, cost, energy penalty?

PRIORITIZE:
- Quantitative data: concentrations, volumes, costs, temperatures, flow rates, dosages -- not qualitative descriptions
- Real facility data over theoretical calculations
- Cost data with clear basis (facility size, geographic location, year)
- Step-by-step process descriptions that an engineer could use to size equipment
- Sludge disposal costs (this is where the pain is for the customer)
- REE content in waste streams (this is where the value proposition lives)

OUTPUT FORMAT:
- Process flow diagram description (text): each step with inputs, outputs, operating conditions, equipment
- Waste stream inventory table: stream name, source, composition, volume, hazard class, treatment pathway, disposal cost
- Cost summary table: CAPEX, OPEX by category, total cost per tonne of magnet produced
- Metal mass balance: how much of each REE enters the facility as raw material, ends up in finished magnets, and is lost to waste streams?
- Engineering gaps: what data is missing that would be needed to design an alternative treatment system?
