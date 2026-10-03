# Sub-Module 1.3: Mechanical Properties

Module 3: Dental Materials & Material Science | Sub-Module 1.3

### Note on Sources

Sources used in this document: [1] Philips' Science of Dental Materials (13th ed.) — primary source; its Chapter 4 ("Mechanical Properties of Dental Materials") and Chapter 11 ("Abrasion, Erosion, and Wear") cover this sub-module's entire scope in exhaustive, dentistry-specific detail, including real worked stress-strain examples; [2] Craig's Restorative Dental Materials (14th ed.) — used specifically for its direct comparative elastic-modulus table across dental material classes, and for the burnishing-index concept (ductility/yield strength), both genuinely complementary to Philips' single-material worked examples. [3] McCabe JF, Walls AWG. Applied Dental Materials (9th ed.) — a real Vickers-hardness comparison table and the mechanistic explanation of what a hardness test physically measures (tied to the elastic limit), not previously covered. [4] van Noort R, Barbour M. Introduction to Dental Materials (4th ed.) — creep and fatigue, two time-dependent mechanical behaviors the outline's static stress/strain framing does not cover, plus a broad comparative fracture-toughness table. [5] Powers JM, Wataha JC. Dental Materials: Properties and Manipulation (10th ed.) — resilience and toughness as distinct energy-based mechanical properties, with a real quantified composite-vs-acrylic comparison, not previously covered. [6] Craig RG, ed. Restorative Dental Materials (11th ed., University of Michigan). A fifth new textbook the user supplied — real dynamic modulus/dynamic resilience data, the pendulum impact-strength test methodology, and nanoindentation (with real enamel/dentin/DEJ comparative data), none previously covered.

Per the standing skill rule, every extracted textbook was grepped for this sub-module's key terms (elastic modulus, yield strength, flexural strength, Knoop hardness, brittle, ductile, proportional limit, compressive/shear strength, wear resistance) before finalizing sources. McCabe's, Sturdevant's, Summitt's, Marzouk's, and Sikri's all returned substantial hit counts but were checked and found to be either clinical-application-specific content already covered in Module 1's material sub-modules, or fully redundant with the fundamentals-level treatment Philips'/Craig's already provide here.

**Revision note:** the user asked whether McCabe's — on the standing Module 3 secondary source list — had been checked for this sub-module; it had not been. It gives a real Vickers hardness comparison table and a genuinely precise mechanistic account of what a hardness indentation test actually measures (the point at which the indentor's applied stress equals the material's elastic limit), plus a practical elastic-recovery measurement caveat. Added below.

**Third revision note:** the user supplied a fifth new textbook, Restorative Dental Materials (Craig, ed., 11th ed., University of Michigan) — an older, distinct multi-author Craig text, not to be confused with the 14th-edition Craig's Restorative Dental Materials (Sakaguchi/Ferracane/Powers) already used throughout this module. It has three genuinely new mechanical-property topics this sub-module had not covered: dynamic modulus/dynamic resilience (real elastomer data), impact strength with real pendulum-test methodology, and nanoindentation (with real comparative enamel/dentin/DEJ data). Added below as a new Section 1.3.6.

**Second revision note:** the user supplied a fourth new textbook, Dental Materials: Properties and Manipulation (Powers & Wataha, 10th ed.), once OCR'd. It covers resilience and toughness — two genuine mechanical properties, based on the AREA under the stress-strain curve rather than a single point on it, that this sub-module had not yet covered. Added below as new content within Section 1.3.2.

**Revision note:** the user supplied additional textbooks including van Noort's Introduction to Dental Materials. It covers two genuinely important mechanical behaviors this sub-module's outline does not explicitly list but that are standard dental-materials-science content: creep (permanent deformation under sustained load below the elastic limit) and fatigue (failure from cyclic loading below the yield stress) — both with direct dental clinical relevance (amalgam creep; Ni-Ti endodontic file fatigue fracture). A new Section 1.3.5 is added below rather than omitting this real, standard content on a technicality of outline wording.

**A note on a likely outline transcription issue:** the Module 3 outline's Sub-Module 1.2 (Physical Properties, delivered previously) listed an approximate dentin CTE of "~17 ppm/°C." Craig's real data (Table 4.1, used below) gives dentin's ELASTIC MODULUS as 17 GPa — a different property entirely, but the same number. This strongly suggests the outline's CTE figure for dentin was a transcription mix-up with the modulus value, not a genuine alternate CTE source. Flagging this here since it only became clear once this sub-module's modulus data was pulled.

## 1.3.1 Stress & Strain

Strength, in the general mechanical sense, is a material's ability to resist induced stress without fracturing or undergoing permanent (plastic) deformation. Plastic deformation specifically occurs once the elastic stress limit — the proportional limit — of the material is exceeded. [1, p.49]

**The physical basis of stress — Newton's third law:** when an external force acts on a solid, an equal-and-opposite reaction force opposes it. The stress produced within the material equals the applied force divided by the area over which it acts. The direction of the applied force determines the stress type: a tensile force produces tensile stress, a compressive force produces compressive stress, and a shear force produces shear stress. [1, p.49]

**Elastic vs. plastic strain — the proportional limit as the dividing line:** when a force acts on an elastic solid, its atoms/molecules respond by shifting position; if the stress stays below the proportional limit, this deformation is fully reversible (elastic) and disappears once the force is removed. Stress above the proportional limit instead causes permanent (plastic) deformation, and — if high enough — fracture. Brittle dental materials (a category covered in depth in Section 4 below) exhibit ONLY this elastic behavior; they do not plastically deform at all, so stress at or slightly above the proportional limit goes straight to fracture with no intervening plastic-deformation warning. [1, p.49]

## 1.3.2 Strength & Elastic Modulus

### A Real Worked Stress-Strain Curve

Philips' gives a fully worked example using a stainless steel orthodontic wire under tension, illustrating every key term in one dataset: [1, p.53]

| Property | Value |
|---|---|
| Proportional limit (PL) | 1020 MPa |
| Yield strength (YS), 0.2% offset | 1536 MPa |
| Ultimate tensile strength (UTS) | 1625 MPa |
| Elastic modulus (E), from slope of elastic region | 192,000 MPa (192 GPa) |

The elastic modulus is a constant that describes a material's relative stiffness, derived from the slope of the elastic (straight-line) portion of its stress-strain graph — it compensates for differences in specimen cross-sectional area and length by plotting stress (force per unit area) against strain (relative change in length). [1, p.54]

### The 0.2% Offset Method — Why Yield Strength Exists as a Separate Measure

For some materials, the exact point where the stress-strain curve deviates from a straight line (the true proportional limit) cannot be determined with sufficient accuracy. Yield strength solves this by defining the stress at which a small, specific amount of plastic strain (conventionally 0.1% or 0.2%) has occurred — the "percent offset." A line is drawn parallel to the elastic (straight-line) region, starting from 0.002 (0.2%) along the strain axis, and extended until it intersects the actual stress-strain curve; the stress at that intersection point is the yield strength. A material has NOT fractured at its yield strength — it is intact but has sustained that specific small amount of permanent deformation. Comparing yield strengths across two materials is only valid if both were measured using the same percent offset. [1, p.58]

For brittle materials such as dental ceramics, this entire offset method becomes moot: their stress-strain plot is a straight line with essentially no plastic region at all, so there is no meaningful "yield point" distinct from fracture itself. [1, p.58]

### Comparative Elastic Modulus Across Dental Material Classes

Real measured elastic modulus values, spanning nearly five orders of magnitude across the materials used in dentistry: [2, p.36]

| Material | Elastic modulus (GPa) |
|---|---|
| Silicone elastomer (maxillofacial prosthesis) | 0.002–0.003 |
| Poly(methyl methacrylate) | 2.4 |
| Resin composite with hybrid filler | 17–21 |
| Dentin | 17 |
| Amalgam | 28–59 |
| Feldspathic porcelain | 69–70 |
| Enamel | 84 |
| Gold (Type IV) alloy | 90–95 |
| Cobalt-chromium RPD alloy | 218–224 |

This single table directly grounds the outline's qualitative claims in real numbers: amalgam and ceramic are genuinely "high modulus" only relative to composite and resin — amalgam's modulus (28-59 GPa) still sits well below gold's (90-95) and Co-Cr's (218-224), and dentin itself (17 GPa) is closer in stiffness to resin composite (17-21 GPa) than to enamel (84 GPa) — a mismatch that matters directly for how a composite restoration and the surrounding dentin co-flex under occlusal load, versus how enamel (much stiffer) behaves independently at the same load. [2, p.36]

### Resilience and Toughness — Energy-Based Properties, Not Just Stress or Strain Alone (Powers & Wataha)

Every property covered so far (proportional limit, yield strength, UTS, elastic modulus) relates to stress OR strain individually. Resilience and toughness are different in kind: both are measured by the AREA under the stress-strain curve up to a specified point — meaning their value is a genuine product of stress and strain together, not either alone. [5, p.20]

**Precise definitions:** resilience is the energy absorbed up to the PROPORTIONAL LIMIT — a measure of the material's resistance to permanent deformation. Toughness is the energy absorbed up to the ULTIMATE STRENGTH (fracture) — a measure of resistance to fracture under impact. Both relate directly to how a material behaves under a sudden impact load, not just a slow, steady one. [5, p.20]

**Why these are genuinely more complex than strength or elongation alone — a real worked comparison:** two materials can have the SAME resilience through entirely different stress-strain profiles — one with high yield strength and low corresponding strain, another with lower yield strength but higher corresponding strain. Composite resin and unfilled acrylic are the concrete dental example: both have a resilience of approximately 7 cm-kg/cm3, DESPITE composite having a considerably higher yield strength than unfilled acrylic. The two materials simply reach that same resilience value by different stress/strain combinations. [5, p.20]

**Toughness can invert the naive expectation entirely:** although composite has a considerably HIGHER yield strength than unfilled acrylic, unfilled acrylic can deform so much more before rupture that it is actually TOUGHER than composite — a genuinely counter-intuitive result if one assumes "stronger" automatically means "tougher." This is a direct, concrete illustration of why strength, resilience, and toughness are three genuinely separate properties that must each be considered on their own terms rather than inferred from one another. [5, p.20]

**A related honest caveat about hardness (bridging directly into Section 1.3.3 below):** one might reasonably expect hardness to correlate with yield strength and wear resistance — but in general, NO direct relationship exists between hardness and these two properties. The one real exception is when comparing materials of the SAME general type (e.g. a series of similar gold alloys), where hardness does track reasonably well with these other properties. Across different material classes, though, hardness comparisons alone cannot be used to infer strength or wear behavior. [5, p.20]

## 1.3.3 Hardness & Wear Resistance

### What "Hardness" Actually Measures

Hardness is genuinely difficult to define outside of comparison between materials. In metallurgy and most other disciplines, the generally accepted definition is "resistance to indentation," and it is this principle that most modern hardness tests are built around. An indentation results from the interaction of several other material properties simultaneously — compressive strength, proportional limit, and ductility all contribute to what a hardness test actually measures. [1, p.63]

### The Four Main Hardness Tests — and Why the Choice Matters

| Test | Indenter / method | Key limitation or use-case |
|---|---|---|
| Brinell (BHN/HB) | Hardened steel ball pressed into the surface; load / projected indentation area | Extensively used for metals; related to proportional limit and UTS of gold alloys; NOT suitable for brittle materials |
| Rockwell (RHN) | Direct reading of indentation depth | Convenient, widely used in industry; NOT suitable for brittle materials |
| Vickers (HV/VHN) | Square-based diamond pyramid; same load/area principle as Brinell | IS suitable for brittle materials; used in standard testing of dental casting gold alloys and other cast dental alloys, and for tooth structure itself |
| Knoop (HK/KHN) | Diamond tool producing a rhombic (elongated) impression; longest diagonal measured | Named test most frequently cited for dental material hardness comparisons |

The practical takeaway: neither Brinell nor Rockwell testing works for brittle dental materials (ceramics, for instance) — Vickers and Knoop testing exist specifically to fill that gap, which is why dental-materials literature reports Knoop or Vickers hardness for ceramics and ADA/ISO gold alloy specifications almost universally, rather than Brinell or Rockwell. [1, p.64]

### What a Hardness Test Actually Measures (McCabe's)

Beyond simply naming the four tests, it's worth understanding what physically happens during one. Vickers and Knoop tests use pyramidal diamond indentors; on initial contact with the test material, the contact stress is very high. As the indentor penetrates further, the applied load spreads over a progressively larger area and the stress correspondingly drops — the indentor comes to rest at the exact point where the applied stress equals the material's ELASTIC LIMIT. This means a hardness measurement is fundamentally an indirect measurement of a material's yield/elastic-limit behavior, not an arbitrary separate property. [3, p.13]

**A real measurement caveat worth knowing before reading a hardness value off a microscope:** any deformation beyond the elastic limit is recorded as part of the hardness measurement, but purely elastic deformation is NOT — and elastic recovery can actually occur before the indentation is measured under the microscope, causing the indentation to visibly shrink. When this happens, it is important to let the indentation size stabilize before taking the measurement; methods that measure indentation DEPTH directly (like Rockwell) can be harder to interpret for this reason, since separating the elastic and plastic components of the deformation is not always straightforward. [3, p.14]

Real comparative Vickers hardness numbers (VHN) for common dental materials: [3, p.13]

| Material | Vickers Hardness Number (VHN) |
|---|---|
| Acrylic resin | 20 |
| Dentine | 60 |
| Dental amalgam | 100 |
| Enamel | 350 |
| Co/Cr alloys | 420 |
| Porcelain | 450 |

Two practical corollaries of hardness worth connecting to earlier sections: harder materials are correspondingly MORE difficult to polish by mechanical means (acrylic, at VHN 20, is easily scratched; Co/Cr alloys at VHN 420 are not) — and hardness is also used as a general (imperfect) proxy for a material's abrasion resistance, though McCabe's own view is that well-controlled CLINICAL trial data, not hardness numbers alone, gives the most reliable comparative abrasion information. [3, p.14]

### Wear Mechanisms — Two-Body vs. Three-Body Abrasion

Wear is material removal that occurs whenever surfaces slide against each other; the abrading surface/particle is the "abrasive," and the material being worn is the "substrate." **Two-body abrasion** occurs when abrasive particles are firmly bonded to the abrading instrument's surface and no other loose particles are involved — a diamond bur cutting a tooth is the textbook dental example. **Three-body abrasion** occurs when abrasive particles are free to translate and rotate between two surfaces — a dental prophylaxis paste, with loose abrasive particles carried in a rotating rubber cup against the tooth, is the clinical example. [1, p.237]

**The two mechanisms are not mutually exclusive — a genuinely useful clinical nuance:** diamond particles can debond from a bur mid-procedure and start behaving as three-body wear; conversely, abrasive particles from a paste can become trapped in a rubber cup's surface and start acting as two-body wear. Lubricants (water, glycerin, silicone; a water-soluble lubricant is preferred intraorally) are used specifically to minimize this unintentional shift between mechanisms — though the amount matters in both directions: too much lubricant reduces cutting efficiency by reducing abrasive-substrate contact, while too little increases heat generation and ALSO reduces cutting efficiency. [1, p.237]

**Erosion, as a third, distinct wear category:** erosive wear results from hard particles impacting a surface while carried by a stream of liquid or air, as in sandblasting — a chemically/mechanically distinct process from the direct-contact sliding wear of abrasion. [1, p.237]

**A specific, teachable clinical instrumentation detail:** a rotary bur's cutting action is direction-dependent. Moving the handpiece and bur opposite to the bur's own rotational direction at the point of contact produces a smoother, more controlled grinding action. Moving it in the SAME direction as bur rotation causes the bur to "run away" from the substrate, producing rougher, less controlled cutting. [1, p.237]

## 1.3.4 Brittleness & Ductility

### Why Brittle Materials Fail in Tension, Specifically

Very brittle materials have a tensile strength markedly lower than their compressive strength, because they cannot plastically deform to relieve tensile stress concentrated at flaw tips the way a ductile material can. This is true across the whole family of brittle dental materials — amalgams, composites, cements, ceramics, and some base-metal alloys — and their clinical failures are most often traced specifically to low tensile strength combined with a flaw sitting in a tensile-stress region, not to a general lack of strength. [1, p.62]

Brittleness itself is formally defined as the relative inability of a material to sustain plastic deformation before fracturing — a brittle material fractures at or very near its proportional limit, with little or no plastic strain in between (in direct contrast to the ductile stainless-steel wire example in Section 2, which showed a substantial gap between its proportional limit of 1020 MPa and its eventual fracture at 1625 MPa UTS). Amalgams, ceramics, and composites are all brittle specifically at oral temperatures (5-55°C), the clinically relevant range. [1, p.62]

### The Critical Distinction: Brittle Does NOT Mean Weak

This is easy to conflate, and Philips' gives three concrete counter-examples worth memorizing precisely because they contradict the intuitive assumption: [1, p.63]

- A cobalt-chromium removable partial denture alloy: percent elongation under 1.5% (essentially no ductility) — yet an ultimate tensile strength of 870 MPa, a genuinely high strength value.
- A glass-infiltrated alumina core ceramic (In-Ceram Alumina): 0% elongation (perfectly brittle) — yet a moderately high tensile strength of 450 MPa.
- A glass fiber, drawn with very smooth surfaces and minimal internal flaws: 0% elongation (no ductility whatsoever) — yet a tensile strength as high as 2800 MPa (400,000 psi), higher than most metals used in dentistry.

The clinical consequence that follows directly from this: dental materials with low or zero percent elongation — amalgams, composites, ceramics, and nonresin luting agents — have little or no burnishability, because burnishing IS a form of intentional plastic deformation, and these materials simply have no plastic-deformation capacity to draw on regardless of how strong they are. [1, p.63]

### Measuring Ductility — Three Real Methods

| Method | How it works |
|---|---|
| Percent elongation (most common) | Two marks placed a fixed "gauge length" apart (51 mm is the dental standard) on a wire/rod; pulled to fracture; fractured ends refitted and gauge length re-measured. % elongation = (increase in length / original gauge length) x 100 — this IS the quantitative measure of ductility. |
| Relative reduction in area | After tensile fracture, a ductile metal wire shows "necking" (a cone-shaped constriction) at the break point; the percent decrease in cross-sectional area there, versus the original area, is measured. |
| Cold bend test | Material clamped in a vise and bent around a mandrel of specified radius; first bend at 90°, all subsequent bends at 180°; the number of bends survived before fracture is counted — more bends means greater ductility. |

*Source: [1, p.63]*

### Cold Working and the Embrittlement Risk of Repeated Adjustment (Clinical Application)

When a metal alloy is stressed beyond its proportional limit, hardness and strength increase at the deformed area, but ductility DEcreases — a direct consequence of dislocations moving and piling up along grain boundaries (the grain-boundary mechanics introduced in Sub-Module 1.1), which makes further plastic deformation in that same area progressively harder. [1, p.58]

**This has a direct, named clinical consequence:** repeated plastic deformation of the same area — such as repeatedly bending an orthodontic wire, or repeatedly adjusting a removable partial denture's clasp arm — progressively embrittles that specific spot, and it can eventually fracture when yet another adjustment is attempted, even though the same alloy elsewhere remains fully ductile. The elastic modulus itself stays constant throughout this process; what changes is that the plastic-deformation portion of the stress-strain curve shrinks with each successive bend. The practical mitigation is to deform the metal in small increments rather than one large adjustment, specifically to avoid triggering this embrittlement cascade. [1, p.58]

### The Burnishing Index (Craig's)

Ductility is directly tied to a metal's workability in the mouth — for example, the ability to adjust (burnish) a casting's margins. But ductility (elongation) alone does not fully predict how easy an alloy is to burnish, because the FORCE required to cause that permanent deformation also matters. Craig's defines a burnishing index specifically to capture both factors together: burnishing index = ductility (percent elongation) / yield strength. A material can have respectable elongation and still burnish poorly if its yield strength is high enough to demand excessive force — meaning ductility and burnishability, while related, are not interchangeable properties for material-selection purposes. [2, p.37]

## 1.3.5 Time-Dependent Mechanical Behavior — Creep & Fatigue (van Noort's)

### Creep — Deformation Below the Elastic Limit, Given Enough Time

Under a CONSTANT stress applied for a long period, a material can deform permanently even when that stress stays below its elastic limit — this time-dependent permanent deformation is creep, and if left unchecked it will eventually lead to fracture. [4, p.36]

**When creep matters most — a temperature rule of thumb:** creep becomes particularly significant when a material is used at a temperature above roughly HALF of its melting or softening point — some amalgam phases and many plastics fall into this regime at mouth temperature. Conversely, at temperatures 40-50% below the material's absolute melting point, creep is negligible. This single rule of thumb explains why creep is a genuine, named clinical concern for amalgam (whose weaker γ2 phase has a comparatively low melting point relative to body temperature) but is not a practical concern for most high-melting-point metals and ceramics used in the mouth. [4, p.36]

A full creep curve shows four distinguishable stages: initial elongation from the load's application, transient (primary) creep — typically the largest single contributor, steady-state (secondary) creep, and finally tertiary creep, which precedes fracture. [4, p.36]

### Fatigue — Failure Well Below the Yield Stress, From Repeated Cycling

Fatigue is the gradual accumulation of minute amounts of plastic strain produced by each cycle of a FLUCTUATING (not constant) stress. Critically, fatigue can cause failure at stresses well BELOW the material's yield stress — a material that comfortably withstands a given load once, or even many times under STATIC conditions, can still fail from that same load if it is applied and released repeatedly. [4, p.36]

**A direct, named dental clinical example:** Ni-Ti (nickel-titanium) files used in endodontics are specifically flagged as a clinical situation where fatigue failure occurs — repeated flexure as the file negotiates a curved root canal accumulates fatigue damage cycle by cycle, and separation can occur even though the file was never subjected to a single overloading event beyond its rated strength. [4, p.36]

**The S-N curve and the endurance limit — a genuine either/or in material behavior:** fatigue testing plots stress against the LOGARITHM of the number of cycles to failure (an S-N curve). Two distinct behaviors are observed across different materials: for some, allowable stress simply keeps decreasing as cycle count increases; for others, there is a genuine ENDURANCE LIMIT — a stress level below which the material can be cycled indefinitely without ever fracturing. Knowing which behavior a given material shows matters enormously for a component (like an endodontic file or an orthodontic wire) expected to survive a very large number of loading cycles. [4, p.36]

**What actually shifts the S-N curve — two real, controllable variables:** fatigue strength is very dependent on surface characteristics — improving surface finish, or inducing surface COMPRESSIVE stresses (mechanically or chemically), raises the S-N curve (i.e., improves fatigue resistance), since fatigue cracks characteristically initiate at surface defects. The testing/service ENVIRONMENT also has a profound effect: corrosive environments specifically LOWER fatigue strength — directly relevant to any metal restoration or endodontic instrument operating in the chemically active, moist oral/intracanal environment rather than in dry laboratory air. [4, p.36]

### A Broader Comparative Fracture Toughness Table

Extending the ceramic-specific fracture toughness data already covered in this module's Sub-Module 2.2, van Noort's gives a much broader material-class comparison, showing just how extreme the ductile-metal-to-ceramic gap really is: [4, p.34]

| Material | K1c (MPa·m0.5) |
|---|---|
| Ductile metals | 100–350 |
| High-strength steels | 50–154 |
| Aluminium alloys | 23–45 |
| Wood | 11–13 |
| Nylon | 3 |
| Porcelain | 1 |

Porcelain's fracture toughness (as low as 1 MPa·m0.5) sits at the very bottom of this entire cross-material range — up to 350-fold below a ductile metal's — putting this module's earlier ceramic-specific toughness data (feldspathic porcelain 0.78, rising through leucite/lithium-disilicate/zirconia in Sub-Module 2.2) into a genuinely broader material-science perspective: even the WEAKEST metals in this table dramatically outperform even the STRONGEST ceramics on pure fracture toughness — which is precisely why ceramic restoration DESIGN (adequate bulk, avoiding thin unsupported sections, full-coverage margins) matters so much more for ceramics than for metal restorations of comparable size.

## 1.3.6 Dynamic and Microscale Mechanical Testing (Restorative Dental Materials, Michigan)

### Dynamic Modulus and Dynamic Resilience

Beyond the static (single-load) properties covered so far, some dental materials — particularly elastomers used in athletic mouth protectors and maxillofacial prostheses — are better characterized by DYNAMIC properties, measured under oscillating rather than static load. Dynamic resilience is the ratio of energy LOST to energy EXPENDED during a loading cycle, calculated from the material's internal friction. [6, p.99]

**A real, clinically anchored example — athletic mouth protectors:** dynamic resilience directly measures a mouth protector's ability to absorb energy from a blow and thereby protect the oral structures — precisely the property that matters in the actual use-case. Temperature has a measurable effect on these properties for some maxillofacial elastomers (plasticized polyvinylchloride, polyurethane) but comparatively little effect for silicones — and across the range tested (-15°C to 37°C), dynamic modulus DECREASES while dynamic resilience INCREASES as temperature rises. A further real, practical finding: a mouth protector's dynamic properties measurably DETERIORATE once the appliance has actually been worn — meaning a protector's true protective performance is not fixed at the moment of fabrication, but declines with use. [6, p.99]

### Impact Strength — Why Static Strength Values Alone Can Mislead

A material can show perfectly reasonable static strength values — compressive, tensile, shear — and even reasonable elongation, yet still FAIL when loaded by a sudden IMPACT rather than a slowly applied load. Fused glasses, cements, amalgam, and some plastics specifically show low resistance to impact breakage despite adequate static strength — a genuine, separate failure mode from anything captured by the stress-strain-curve properties covered earlier in this sub-module. [6, p.99]

**The real clinical scenario this predicts:** a sudden blow corresponding to the energy of an accidental impact to a patient wearing a restoration, or a restoration being dropped on the floor before placement — both genuinely relevant, everyday clinical and laboratory scenarios, not just an abstract materials-testing concept. [6, p.99]

**The actual test method:** impact resistance is determined from the TOTAL ENERGY absorbed before fracture when a specimen is struck by a sudden blow. A bar of the material is supported as a beam and struck — at one end or in the middle — with a weighted pendulum; the energy absorbed is calculated from the REDUCTION in the pendulum's swing compared with its swing with no specimen present. Results are reported in joules (1 J = 1 N·m) for a specimen of specified shape and dimensions. [6, p.99]

### Nanoindentation — Resolving What Traditional Hardness Tests Cannot

Traditional hardness tests (Section 1.3.3 above) use loads as high as several kilograms, producing indentations as large as 100 μm — genuinely useful for screening and comparing materials, but limited when the microstructural feature of interest is SMALLER than the indenter itself. Many dental materials have microstructural constituents at exactly this problem scale — the filler particles in a microfilled composite, for instance, are often substantially smaller than a conventional Vickers or Knoop indentation. [6, p.107]

**How nanoindentation solves this:** nanoindentation applies loads in the range of 0.1 to 5000 mg — several orders of magnitude below conventional hardness testing — producing indentations of approximately 1 μm, small enough to probe individual microstructural phases with spatial control over indentation location. Indentation DEPTH is continuously monitored during the test itself, which removes the need to optically image the indentation afterward to compute mechanical properties — a genuine methodological advantage over the conventional hardness tests covered earlier, which require post-hoc microscopic measurement. Beyond hardness, nanoindentation can also measure elastic modulus, and — for brittle materials — yield strength and fracture toughness. [6, p.107]

**Real comparative data — and a genuine discrepancy worth knowing:** nanoindentation of dentin gives a nano-hardness of 71 kg/mm2, which agrees well with the conventional Knoop hardness value of 68 kg/mm2 already covered in Section 1.3.3 — good cross-method agreement. Enamel, however, shows a nano-hardness of 457 kg/mm2, considerably HIGHER than its Knoop hardness value of 343 kg/mm2 (also from Section 1.3.3) — a real, non-trivial discrepancy between the two measurement techniques for the SAME tissue. Nanoindentation additionally makes it possible to measure the dentin-enamel junction (DEJ) itself as its own distinct region, with its own measurable nano-hardness and elastic modulus — a microstructural zone too thin and too transitional for conventional hardness testing to characterize at all. [6, p.107]

## References

1. Anusavice KJ, Shen C, Rawls HR, eds. Philips' Science of Dental Materials. 13th ed. St. Louis: Elsevier; 2013.

2. Sakaguchi RL, Ferracane JL, Powers JM. Craig's Restorative Dental Materials. 14th ed. St. Louis: Elsevier; 2019.

3. McCabe JF, Walls AWG. Applied Dental Materials. 9th ed. Oxford: Blackwell Publishing; 2008.

4. van Noort R, Barbour M. Introduction to Dental Materials. 4th ed. Edinburgh: Mosby Elsevier; 2013.

5. Powers JM, Wataha JC. Dental Materials: Properties and Manipulation. 10th ed. St. Louis: Elsevier Mosby; 2013.

6. Craig RG, ed. Restorative Dental Materials. 11th ed. St. Louis: Mosby; 2002.

<!-- related-notes -->
## Related Notes

**Restorative Forces, Marginal Integrity & Biomechanics** — hub: [[Dental Study Material/_Topic Hubs/Restorative Forces, Marginal Integrity & Biomechanics|Restorative Forces, Marginal Integrity & Biomechanics]]

- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_2.1_Principles_of_Tooth_Preparation|M1 · 2.1: Principles of Tooth Preparation]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_3.1_Restorative_Material_Categories|M1 · 3.1: Restorative Material Categories]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_5.2_Indirect_Restoration_Materials|M1 · 5.2: Indirect Restoration Materials]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_3.2_Adhesive_Systems_and_Bonding|M1 · 3.2: Adhesive Systems & Bonding]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_4.1_Composite_Restoration_Placement_Techniques|M1 · 4.1: Composite Restoration Placement Techniques]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_6.4_Non_Carious_Tooth_Structure_Loss|M1 · 6.4: Non-Carious Tooth Structure Loss]] *(other module)*
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_2.2_Ceramics_and_Glass_Materials|M3 · 2.2: Ceramics & Glass Materials]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_7.1_Material_Degradation_Mechanisms|M3 · 7.1: Material Degradation Mechanisms]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_3.1_Adhesion_Mechanisms|M3 · 3.1: Adhesion Mechanisms]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_8.4_Gypsum_Products|M3 · 8.4: Gypsum Products]]

**Ceramic & Indirect Restorations** — hub: [[Dental Study Material/_Topic Hubs/Ceramic & Indirect Restorations|Ceramic & Indirect Restorations]]

- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_5.2_Indirect_Restoration_Materials|M1 · 5.2: Indirect Restoration Materials]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_5.1_Types_of_Indirect_Restorations|M1 · 5.1: Types of Indirect Restorations]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_5.3_Indirect_Restoration_Preparation_and_Cementation|M1 · 5.3: Indirect Restoration Preparation & Cementation]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_6.3_Restoration_Longevity_and_Failure_Patterns|M1 · 6.3: Restoration Longevity & Failure Patterns]] *(other module)*
- [[Dental Study Material/Module 2 - Endodontics/SubModule_8.4_Restoration_of_the_Endodontically_Treated_Tooth|M2 · 8.4: Restoration of the Endodontically Treated Tooth]] *(other module)*
- [[Dental Study Material/Module 1 - Conservative and Restorative/SubModule_5.4_Occlusion_and_Indirect_Restoration_Planning|M1 · 5.4: Occlusion & Indirect Restoration Planning]] *(other module)*
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_2.2_Ceramics_and_Glass_Materials|M3 · 2.2: Ceramics & Glass Materials]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_7.1_Material_Degradation_Mechanisms|M3 · 7.1: Material Degradation Mechanisms]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_3.1_Adhesion_Mechanisms|M3 · 3.1: Adhesion Mechanisms]]
- [[Dental Study Material/Module 3 - Dental Materials and Material Science/SubModule_1.2_Physical_Properties|M3 · 1.2: Physical Properties]]

<!-- source-textbooks -->
## Source Textbooks (available in vault)

- [[Textbooks/Dental Materials/Philips_Science_of_Dental_Materials_12e_MD/00_INDEX|Phillips' Science of Dental Materials]]
- [[Textbooks/Dental Materials/Craig_Restorative_Dental_Materials_14e_MD/00_INDEX|Craig's Restorative Dental Materials (14e)]]
- [[Textbooks/Dental Materials/McCabe_Applied_Dental_Materials_Chapterwise/00_INDEX|McCabe — Applied Dental Materials]]
- [[Textbooks/Dental Materials/Introduction_to_Dental_Materials_4th_Edition_Chapterwise_MD/00_INDEX|van Noort — Introduction to Dental Materials (4e)]]
- [[Textbooks/Dental Materials/Dental_Materials_Chapterwise_MD_All/Dental_Materials_Properties_and_Manipulation_10e_MD/00_INDEX|Powers & Wataha — Dental Materials: Properties and Manipulation (10e)]]
- [[Textbooks/Dental Materials/Michigan_Restorative_Dental_Materials_Chapterwise/00_INDEX|Restorative Dental Materials (Craig, Michigan 11e)]]
