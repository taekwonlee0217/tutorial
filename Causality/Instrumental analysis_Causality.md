## 1. Chromatography: why separation occurs

1. {Why was chromatography developed?} : {Mixtures often contain substances that cannot be identified or measured reliably together. Chromatography exploits differences in their interactions with two phases, turning a complex mixture into separated zones that can be examined individually.}
    
2. {Why does chromatography require both a mobile phase and a stationary phase?} : {The mobile phase transports analytes, while the stationary phase delays them selectively. Separation arises because different analytes spend different proportions of their journey associated with each phase. Without differential delay, they would travel together.}
    
3. {Why do different substances move through a chromatographic system at different speeds?} : {Their molecular properties produce different partitioning, adsorption, electrostatic, or recognition interactions. A substance that spends more time in the stationary phase has a lower average migration velocity and generally elutes later.}
    
4. {Why is the distribution coefficient useful?} : {The distribution coefficient, K = Cₛ/Cₘ, expresses an analyte’s relative preference for the stationary and mobile phases under specified conditions. A larger K generally means stronger retention, although the amount of each phase also matters.}
    
5. {Why is the retention factor different from the distribution coefficient?} : {K compares concentrations, whereas the retention factor k compares amounts in the two phases. For a simple partition system, k = K(Vₛ/Vₘ). Therefore, changing stationary-phase volume can change retention even when the underlying chemical preference remains unchanged.}
    
6. {Why must retention time be corrected for the mobile-phase transit time?} : {Every analyte needs time to travel through the column, even without retention. Subtracting the hold-up time tₘ gives adjusted retention time t′ᵣ = tᵣ − tₘ, isolating the delay associated with retention.}
    
7. {Why is the retention factor more informative than retention time alone?} : {The expression k = (tᵣ − tₘ)/tₘ normalizes retention against the transit time. Retention time changes with flow rate and column dimensions, whereas k better represents retention chemistry under fixed phase composition and temperature.}
    
8. {Why does thin-layer chromatography move solvent upward without a pump?} : {Capillary forces draw solvent through the narrow spaces within the stationary-phase layer. The solvent transports analytes, while their interactions with the layer determine how far they move relative to the solvent front.}
    
9. {Why do high TLC Rf values usually correspond to short column retention under comparable conditions?} : {A high Rf means an analyte travels readily with the mobile phase and experiences relatively little retention. The same preference generally causes early elution in a column using comparable stationary and mobile phases.}
    
10. {Why cannot an Rf value or retention time alone prove a substance’s identity?} : {Different substances can have similar migration behavior, and experimental conditions affect that behavior. Matching a standard supports identification, but additional evidence, such as a spectrum or a second separation condition, increases confidence.}
    

## 2. Peak broadening, efficiency, and resolution

11. {Why does an initially narrow sample zone become a broader chromatographic peak?} : {Individual molecules experience different paths, diffusion histories, and rates of exchange between phases. Their arrival times spread out, creating a peak rather than a single instantaneous signal.}
    
12. {Why are chromatographic peaks often approximately Gaussian?} : {Many small, partly independent variations in molecular migration combine into an approximately normal distribution of arrival times. Strong adsorption heterogeneity, overloading, or other nonideal effects can instead produce asymmetric peaks.}
    
13. {Why was the theoretical-plate model introduced?} : {It simplifies continuous migration into a sequence of hypothetical equilibration steps. This provides a practical way to describe column efficiency, although a real column contains no physical plates and does not repeatedly stop flowing.}
    
14. {Why does a higher theoretical plate number indicate greater efficiency?} : {A higher N means less relative band spreading during migration. For approximately Gaussian peaks, N = 16(tᵣ/w)² or N = 5.54(tᵣ/w₁/₂)², with retention time and peak width expressed in matching units.}
    
15. {Why is a smaller plate height desirable?} : {Plate height H = L/N expresses band broadening per unit column length. A smaller H means a given column length produces more theoretical plates, allowing efficient separation without necessarily requiring a longer column.}
    
16. {Why does packing cause eddy dispersion?} : {Molecules travel through different channels around particles. These channels differ in length and local velocity, so molecules that started together reach the column outlet at different times. This contribution is represented by the A term.}
    
17. {Why does longitudinal diffusion become more important at low flow velocity?} : {Diffusion moves molecules from the concentrated center of a band toward its less concentrated edges. Slow transport gives diffusion more time to act, which explains the B/u contribution to plate height.}
    
18. {Why does mass-transfer resistance become more important at high flow velocity?} : {Exchange between phases requires finite time. At high velocity, some molecules are carried forward before equilibration occurs, while others remain delayed. The resulting migration differences increase band spreading, represented approximately by Cu.}
    
19. {Why does the van Deemter equation predict an optimum velocity?} : {H = A + B/u + Cu combines broadening that decreases with velocity and broadening that increases with velocity. Their competition produces a minimum. In the simplified equation, the optimum is uₒₚₜ = √(B/C).}
    
20. {Why do smaller stationary-phase particles improve efficiency?} : {They shorten diffusion distances and can make flow paths more uniform, reducing mass-transfer and eddy-dispersion contributions. This allows narrower peaks and efficient operation at higher velocities, provided the instrument can supply the required pressure.}
    
21. {Why does improving efficiency increase resolution only gradually?} : {Resolution depends approximately on √N. Doubling resolution through efficiency alone therefore requires roughly four times as many plates, assuming selectivity and retention remain unchanged. This makes efficiency-only optimization costly in time or pressure.}
    
22. {Why is changing selectivity often more effective than increasing column length?} : {Selectivity α = k₂/k₁ describes the difference between two analytes’ retention. If α is close to one, their peaks overlap even on an efficient column. Changing phase chemistry can separate their positions directly.}
    
23. {Why does increasing retention eventually give diminishing improvements in resolution?} : {A common resolution relationship contains k₂/(1 + k₂), which approaches one as retention increases. Stronger retention therefore eventually adds substantial analysis time while producing relatively little additional separation.}
    
24. {Why must resolution, peak capacity, and peak symmetry be considered separately?} : {Resolution describes separation between a particular pair; peak capacity estimates how many peaks can fit within a separation window; symmetry describes peak shape. A column can perform well by one measure while still failing for a specific sample.}
    

## 3. Why HPLC instrumentation developed

25. {Why did liquid chromatography evolve toward high-pressure instrumentation?} : {Smaller particles improve efficiency but strongly resist liquid flow. High-pressure pumps, reliable seals, and strong columns made it possible to use these particles while maintaining useful flow rates.}
    
26. {Why did UHPLC develop beyond conventional HPLC?} : {Particles around two micrometers or smaller can provide efficient separation at higher velocities or in shorter columns. UHPLC instruments were developed to tolerate the resulting pressure and minimize broadening outside the column.}
    
27. {Why does reducing particle size sharply increase pressure requirements?} : {Smaller particles create narrower flow passages. Under otherwise comparable conditions, pressure drop increases approximately with the inverse square of particle diameter. Halving particle diameter can therefore require about four times the pressure.}
    
28. {Why are core-shell particles useful?} : {Their thin porous outer layer shortens diffusion paths, while the solid core avoids a large internal pore network. They can provide high efficiency with less pressure than some fully porous particles of much smaller overall diameter.}
    
29. {Why were monolithic columns developed?} : {A continuous porous structure can combine large flow channels with smaller pores that provide surface area. This offers a way to achieve useful mass transfer and relatively low flow resistance without a conventional packed particle bed.}
    
30. {Why must mobile phases be degassed?} : {Dissolved gases can form bubbles when pressure or temperature changes. Bubbles disturb pumping and detector measurements, causing unstable flow, baseline noise, or signal spikes. Degassing reduces these problems.}
    
31. {Why do online degassers use gas-permeable tubing under vacuum?} : {Dissolved gases diffuse through the tubing into the low-pressure surroundings, while liquid remains inside. This continuously removes gas before the mobile phase enters the pump.}
    
32. {Why do HPLC pumps use coordinated piston movements?} : {A piston alternates between filling and delivering solvent. Coordinating multiple pistons reduces interruptions and pulsation, helping maintain stable flow and reproducible retention times.}
    
33. {Why were both low-pressure and high-pressure gradient mixing developed?} : {Low-pressure mixing proportions solvents before a shared pump, offering flexible solvent selection. High-pressure mixing combines streams delivered by separate pumps, offering different control of composition and gradient delivery. Their practical differences include mixing volume and gradient delay.}
    
34. {Why does gradient delay volume matter?} : {A programmed solvent change must travel from its mixing point to the column. This delay shifts the gradient experienced by analytes and can alter retention, particularly when transferring methods between instruments.}
    
35. {Why are valve-and-loop injectors used?} : {They introduce a defined sample volume into the flowing mobile phase while maintaining a sealed high-pressure system. This improves reproducibility and avoids repeatedly opening the flow path.}
    
36. {Why must injection volume match column dimensions and sample solvent?} : {A large sample plug broadens the initial zone, especially in small columns. A sample solvent that is too strong can also prevent focusing at the column inlet, causing distorted peaks even when the injected amount is modest.}
    
37. {Why are temperature control, guard columns, and low-volume connections important?} : {Temperature affects viscosity and retention; guard columns intercept contaminants that damage the analytical column; small connecting volumes limit extra-column broadening. Together, these preserve the separation the column is capable of producing.}
    

## 4. Why different HPLC detectors exist

38. {Why is there no single ideal HPLC detector?} : {Analytes differ in optical, electrical, and physical properties. Detectors also differ in sensitivity, selectivity, gradient compatibility, and response speed. The best choice depends on which property can be measured reliably for the target analytes.}
    
39. {Why must detector acquisition be fast enough for the narrowest peak?} : {Too few measurements across a peak distort its height, shape, and integrated area. Faster separations therefore require sufficiently rapid sampling and appropriate detector response settings.}
    
40. {Why are sensitivity and detection limit different concepts?} : {Sensitivity describes how strongly the signal changes with concentration, commonly the calibration slope. Detection limit also depends on noise. A detector with a steep calibration slope may still have poor detection limits if its baseline is unstable.}
    
41. {Why are UV-visible absorbance detectors widely used?} : {Many compounds contain chromophores that absorb UV or visible light. Absorbance can be related to concentration, and suitable solvents provide low background at the selected wavelength. The method is convenient and compatible with many gradients.}
    
42. {Why were diode-array detectors developed?} : {They collect absorbance information at many wavelengths simultaneously. This permits wavelength selection after acquisition, provides spectra across peaks, and helps assess whether changing spectral composition suggests coelution. Spectral consistency alone does not prove peak purity.}
    
43. {Why can a longer absorbance-cell path improve sensitivity but harm chromatographic performance?} : {Absorbance increases with optical path length. However, a larger flow-cell volume can broaden peaks. Detector-cell design therefore balances optical sensitivity against the need to preserve narrow chromatographic zones.}
    
44. {Why can fluorescence detection be more selective and sensitive than absorbance detection?} : {A fluorescent analyte is selected through both excitation and emission wavelengths. Measuring emitted light against a relatively low background can improve detection, but only naturally fluorescent or appropriately derivatized compounds respond well.}
    
45. {Why is refractive-index detection useful for compounds without chromophores?} : {It measures the difference between the refractive index of the column effluent and a reference. Many compounds alter this bulk property even when they do not absorb useful UV wavelengths.}
    
46. {Why is refractive-index detection poorly suited to solvent gradients?} : {Changing solvent composition changes refractive index directly. This large background change can overwhelm the much smaller contribution from analytes, making stable measurement difficult.}
    
47. {Why were evaporative light-scattering detectors developed?} : {Some analytes lack useful optical or electrochemical responses. ELSD nebulizes the effluent, evaporates the mobile phase, and detects light scattered by remaining analyte particles. It requires analytes less volatile than the mobile phase and generally needs nonlinear calibration.}
    
48. {Why were charged-aerosol detectors developed?} : {After solvent evaporation, analyte particles acquire charge from a charged gas and are measured electrically. This gives broad detection of many nonvolatile analytes, although response still depends on operating conditions and is not perfectly identical for every substance.}
    
49. {Why are electrochemical, pulsed-amperometric, and post-column reaction detectors useful?} : {Electrochemical detectors exploit oxidation or reduction. Pulsed potentials also clean electrode surfaces that analytes would foul. Post-column reactions create a detectable product after separation, extending measurement to compounds with weak native responses.}
    

## 5. Why different liquid-chromatography modes evolved

50. {Why does normal-phase chromatography retain polar analytes strongly?} : {Its polar stationary phase interacts with polar functional groups through mechanisms such as hydrogen bonding and dipolar interactions. A relatively nonpolar mobile phase competes weakly for these interactions, allowing substantial retention.}
    
51. {Why does increasing mobile-phase polarity often accelerate normal-phase elution?} : {A more strongly interacting solvent competes with analytes for stationary-phase sites and better stabilizes them in the mobile phase. This shifts the balance away from retention.}
    
52. {Why is an eluotropic series useful?} : {It ranks solvents by their elution strength for a specified chromatographic system. This helps select solvents that change retention predictably, although solvent strength is dependent on stationary-phase chemistry and is not a universal property.}
    
53. {Why did reversed-phase chromatography become so widely used?} : {Its nonpolar stationary phase and aqueous-organic mobile phase accommodate many organic analytes and samples. Retention can be adjusted conveniently through organic-solvent proportion, solvent identity, pH, and stationary-phase chemistry.}
    
54. {Why are hydrophobic analytes often retained longer in reversed-phase chromatography?} : {They associate more favorably with the nonpolar stationary phase than with a strongly aqueous mobile phase. Increasing hydrophobic surface area often increases retention, although specific interactions and ionization can modify this trend.}
    
55. {Why does increasing organic solvent usually accelerate reversed-phase elution?} : {The mobile phase becomes better able to accommodate hydrophobic analytes, reducing their preference for the stationary phase. This lowers retention factors and elutes strongly retained compounds sooner.}
    
56. {Why can changing solvent identity change selectivity even at similar overall elution strength?} : {Solvents differ in hydrogen-bond donation, hydrogen-bond acceptance, and dipolar interactions. Two solvents that produce similar average retention can affect individual analytes differently and therefore change their separation.}
    
57. {Why does pH strongly affect reversed-phase retention of acids and bases?} : {pH changes their degree of ionization. Charged forms are generally more compatible with the aqueous mobile phase and less retained by a nonpolar phase than neutral forms. Controlling pH therefore improves both selectivity and reproducibility.}
    
58. {Why are bonded silica phases endcapped?} : {Residual silanol groups can interact strongly with some analytes, particularly bases, producing unwanted retention and tailing. Small endcapping reagents reduce access to these sites.}
    
59. {Why were polymeric and modified silica phases developed?} : {Conventional silica phases have chemical-stability and interaction limitations. Polymeric materials can offer broader pH tolerance, while modified silica surfaces provide alternative selectivity or better compatibility with highly aqueous mobile phases.}
    
60. {Why was HILIC developed for highly polar analytes?} : {Very polar compounds often show insufficient reversed-phase retention. HILIC uses a polar stationary phase and an organic-rich mobile phase, allowing retention through partitioning into a water-rich surface layer and other polar interactions.}
    
61. {Why does increasing water content commonly strengthen HILIC elution?} : {Water improves solvation of polar analytes in the mobile phase and competes for stationary-phase interactions. This reduces their preference for the retained water-rich region and generally lowers retention.}
    
62. {Why does size-exclusion chromatography separate large molecules first?} : {Large molecules cannot enter many stationary-phase pores and therefore access less liquid volume. Smaller molecules enter more pores and spend longer traversing the column, so they elute later.}
    
63. {Why should SEC avoid adsorption and other chemical interactions?} : {The intended separation depends on access to pores rather than binding. Adsorption adds an independent retention mechanism and can make molecular-size interpretation misleading. Suitable solvent and surface chemistry minimize these interactions.}
    
64. {Why does SEC require carefully chosen pore sizes and calibration standards?} : {Molecules that are all excluded, or all fully included, have little separation. Within the useful range, retention reflects hydrodynamic size rather than mass alone, so standards with different shapes can produce biased molecular-mass estimates.}
    
65. {Why do polymers require number-average and weight-average molecular masses?} : {A polymer sample contains a distribution of chain lengths. Mₙ = ΣxᵢMᵢ weights each chain equally, whereas M𝑤 = ΣwᵢMᵢ gives heavier chains more influence. Their ratio describes dispersity, and Mₙ divided by repeat-unit mass approximates average polymerization degree.}
    
66. {Why does ion-exchange chromatography separate charged analytes?} : {Fixed stationary-phase charges bind oppositely charged analytes in competition with mobile-phase counterions. Retention depends on charge, interaction strength, exchange capacity, and the concentrations of competing ions.}
    
67. {Why do increasing salt concentration or changing pH elute analytes from ion exchangers?} : {More competing ions displace retained analytes. Changing pH can alter analyte charge or the charge of weak exchange groups. Both approaches weaken the interaction responsible for retention.}
    
68. {Why was suppressed-conductivity ion chromatography developed?} : {The ionic eluent can create a large conductivity background. A suppressor converts it into less conductive species while often enhancing analyte response; for example, an anion suppressor converts sodium hydroxide largely into water and analyte salts into their corresponding acids.}
    
69. {Why were ion-pair, affinity, and chiral chromatography developed?} : {Ion-pair methods improve retention of ionic analytes on reversed-phase materials. Affinity methods exploit specific recognition to isolate targets. Chiral phases create different interactions with enantiomers, which otherwise behave identically in an achiral separation environment.}
    

## 6. Multidimensional LC and supercritical-fluid chromatography

70. {Why was two-dimensional liquid chromatography developed?} : {Complex samples can exceed the resolving capacity of one separation mechanism. A second dimension separates compounds that overlap in the first, particularly when the two dimensions have substantially different selectivities.}
    
71. {Why must transfer between LC dimensions be carefully controlled?} : {Fractions from the first column must reach the second without excessive dilution or loss. Alternating loops can collect one fraction while another is analyzed. The second separation must be fast enough to keep pace with fraction collection.}
    
72. {Why was supercritical-fluid chromatography developed?} : {Supercritical fluids offer relatively low viscosity and favorable mass transfer while retaining useful solvent power. This allows rapid separation and provides an alternative for analytes and selectivities that benefit from these fluid properties.}
    
73. {Why is carbon dioxide useful in preparative SFC?} : {Its solvent strength can be controlled through pressure, temperature, and modifiers. After collection, depressurization removes much of the CO₂ as gas, reducing the liquid-solvent burden, although any added organic modifier may still require removal.}
    

## 7. Why gas chromatography works

74. {Why must GC analytes be volatile and sufficiently thermally stable?} : {They must enter the column as vapor and survive the injector and oven conditions. Compounds that decompose before vaporization cannot be measured as intact molecules by ordinary GC without modification or another approach.}
    
75. {Why does GC use a gas rather than a liquid mobile phase?} : {The carrier gas transports vaporized analytes through the column. Its low viscosity permits long capillary columns, and rapid gas-phase diffusion supports fast exchange with the stationary phase.}
    
76. {Why did open-tubular columns become important in GC?} : {They avoid the multiple flow paths found in packed beds, largely eliminating eddy dispersion. Their narrow diameter also limits mass-transfer distances, enabling high efficiency over long column lengths.}
    
77. {Why are fused-silica capillaries used?} : {They provide narrow, reproducible internal dimensions and can be manufactured as long flexible columns. An external protective coating improves mechanical durability, while internal treatment reduces unwanted surface interactions.}
    
78. {Why do WCOT and PLOT columns serve different applications?} : {WCOT columns use a thin liquid or polymer film for partitioning. PLOT columns use porous solid layers that can retain very volatile compounds and permanent gases more effectively through adsorption.}
    
79. {Why do narrower GC columns generally improve efficiency?} : {They shorten the distance molecules must diffuse across the mobile phase to reach the stationary phase. This reduces mass-transfer broadening, but narrower columns also have lower sample capacity and greater flow resistance.}
    
80. {Why does a thicker GC stationary-phase film increase retention and capacity?} : {It increases stationary-phase volume and provides more material into which analytes can partition. This is useful for very volatile analytes, but diffusion through the thicker film can increase mass-transfer broadening.}
    
81. {Why must GC stationary-phase polarity be matched to the separation problem?} : {Analytes interact differently with phases having different polarity and functional groups. A phase that distinguishes their intermolecular interactions changes selectivity; “like dissolves like” is a useful starting point rather than a complete separation rule.}
    
82. {Why does increasing oven temperature generally decrease GC retention?} : {Higher temperature favors analyte presence in the gas phase and commonly lowers its partition coefficient into the stationary phase. Analytes therefore spend less time retained and elute sooner.}
    
83. {Why was temperature programming developed?} : {A low temperature separates volatile compounds but excessively retains less volatile ones. A high temperature elutes heavy compounds quickly but can compress early peaks. A rising temperature balances these competing requirements within one run.}
    
84. {Why does carrier-gas identity affect the optimum flow velocity?} : {Analyte diffusion coefficients differ in nitrogen, helium, and hydrogen. These differences change longitudinal diffusion and mass-transfer contributions, producing different efficiency-versus-velocity curves.}
    
85. {Why can hydrogen support fast GC separations?} : {Its favorable diffusion and viscosity characteristics allow efficient operation over a relatively broad range of high velocities. Actual performance still depends on column dimensions, analytes, temperature, and instrument conditions.}
    
86. {Why must carrier gas be purified and flow carefully controlled?} : {Water, oxygen, and hydrocarbons can damage phases or raise background signals. Flow changes alter transit times and efficiency. Clean, stable carrier gas therefore supports reproducible retention and reliable detection.}
    

## 8. Why GC injection and extraction methods evolved

87. {Why is split injection useful for concentrated samples?} : {Capillary columns have limited sample capacity. Venting most of the vaporized sample prevents overloading while rapidly delivering a small fraction to the column, helping create a narrow initial zone.}
    
88. {Why can split injection distort sample composition?} : {Compounds may vaporize or transfer at different rates because of differences in volatility and interaction with the inlet. Consequently, the fraction reaching the column may not represent every analyte equally.}
    
89. {Why was splitless injection developed for trace analysis?} : {Closing the split outlet temporarily transfers a much larger fraction of the sample to the column. This improves detectability for dilute analytes that would be lost through the split vent.}
    
90. {Why does splitless injection require focusing at the column entrance?} : {Sample transfer is slower and can produce a broad initial zone. Solvent trapping or cold trapping concentrates analytes near the column head before temperature programming begins their separation.}
    
91. {Why is the split outlet reopened after a splitless transfer period?} : {Most useful analyte transfer has occurred by then. Opening the outlet removes residual solvent and inlet vapors, reducing contamination and preventing prolonged transfer that would broaden the separation.}
    
92. {Why are retention gaps sometimes used?} : {An uncoated capillary section can accommodate solvent spreading and support focusing before analytes enter the coated analytical column. It also helps manage difficult injections without directly overloading the separation phase.}
    
93. {Why was programmed-temperature vaporization developed?} : {A cool initial inlet can accept sample with less immediate discrimination or degradation. Controlled heating then removes solvent and transfers analytes. This enables larger-volume injections and improves flexibility, although careful optimization remains necessary.}
    
94. {Why is cold on-column injection useful for thermally sensitive analytes?} : {It introduces sample directly into a relatively cool column, avoiding a hot vaporizing inlet. This reduces inlet-related decomposition and discrimination, but the sample must be sufficiently clean to protect the column.}
    
95. {Why was static headspace analysis developed?} : {Volatile analytes partition into the gas above a sample. Sampling this gas avoids injecting much of the nonvolatile matrix, reducing contamination and simplifying analysis of volatile components.}
    
96. {Why must headspace temperature and equilibration conditions be controlled?} : {Gas-phase concentration depends on the partition coefficient, sample volume, headspace volume, and temperature. Reproducible equilibration is essential because a change in these conditions can change the measured signal without changing sample concentration.}
    
97. {Why does dynamic headspace provide enrichment?} : {A gas stream repeatedly removes volatile analytes from the headspace and carries them to a trap. Collecting analytes over time concentrates more material than a single static headspace injection.}
    
98. {Why was solid-phase microextraction developed?} : {A coated fiber accumulates analytes from a liquid or its headspace and then releases them into the GC inlet. It combines sampling and enrichment with little solvent use, but extraction depends on coating selectivity and controlled conditions.}
    
99. {Why do thermal desorption and purge-and-trap methods improve trace analysis?} : {They collect analytes from a larger sample volume onto a sorbent or cold trap, then release them in a short pulse. Thermal desorption often handles air samples or solids; purge-and-trap strips volatile analytes from liquids.}
    
100. {Why was pyrolysis-GC developed for polymers?} : {Intact polymers are generally too large and nonvolatile for ordinary GC. Controlled thermal decomposition generates smaller characteristic products that can be separated and identified, allowing inference about polymer composition.}
    

## 9. GC detection and two-dimensional separation

101. {Why is the flame-ionization detector especially effective for hydrocarbons?} : {Hydrocarbon combustion in a hydrogen-air flame generates charged species that produce an electrical current. The response is strong for many organic compounds, while carrier gases and several common inorganic substances give little response.}
    
102. {Why is FID considered destructive?} : {Analytes are burned during detection. The original molecules therefore cannot be recovered downstream, unlike with some detectors that measure a property without consuming the sample.}
    
103. {Why is FID useful for quantitative work but insufficient for identification?} : {It provides sensitive response and a broad linear range for many organic analytes. However, a current peak contains little structural information, so identity requires standards or complementary detection.}
    
104. {Why was the electron-capture detector developed?} : {Electronegative compounds, including many halogenated substances, efficiently capture electrons. Measuring their effect on an electron population provides highly selective detection for compounds that may occur at very low concentrations.}
    
105. {Why does an electron-capturing analyte reduce ECD current?} : {Electron capture converts highly mobile free electrons into less mobile negative ions, reducing charge transport under the detector’s operating conditions. Some instruments measure the pulse-frequency adjustment needed to maintain a specified current.}
    
106. {Why is the thermal-conductivity detector useful for permanent gases?} : {It measures how an analyte-containing stream changes heat loss from a heated element relative to carrier gas. Permanent gases that respond poorly to FID can still produce a measurable thermal-conductivity difference.}
    
107. {Why do element-selective GC detectors exist?} : {Some analytical problems concern compounds containing particular elements rather than all compounds. Flame-photometric or atomic-emission detection can preferentially reveal sulfur, phosphorus, or other elements, reducing interference from unrelated components.}
    
108. {Why was comprehensive two-dimensional GC developed?} : {Complex mixtures such as petroleum contain more components than one column can resolve. Repeatedly transferring the first-column effluent to a second column with different selectivity expands the separation space.}
    
109. {Why does GC×GC require a modulator and a fast second column?} : {The modulator collects and refocuses successive fractions into narrow pulses. The second dimension must separate each pulse before the next arrives, otherwise fractions overlap and the first-dimension information becomes difficult to preserve.}
    
110. {Why do two-dimensional peak capacities multiply only approximately?} : {The potential gain depends on independent selectivities, effective transfer, adequate sampling, and sufficiently fast detection. Correlated retention, band broadening, or undersampling means the practical separation space can be much smaller than the theoretical product.}
    

## 10. Electrophoresis: why electric fields separate analytes

111. {Why was electrophoresis developed as an alternative separation approach?} : {Charged analytes respond directly to an electric field. Differences in charge and friction create different migration velocities, allowing separation without relying on repeated binding to a stationary phase.}
    
112. {Why does electrophoretic mobility depend on charge and size?} : {Electrical force increases with charge, while friction increases with hydrodynamic size and viscosity. In a simple spherical model, μₑₚ = ze/(6πηr), so highly charged, small ions generally move faster.}
    
113. {Why does increasing electric-field strength accelerate migration?} : {Electrophoretic velocity is vₑₚ = μₑₚE. A stronger field increases the electrical driving force, although heating and changes in solution properties limit how far voltage can be increased usefully.}
    
114. {Why were narrow capillaries adopted for electrophoresis?} : {They dissipate heat efficiently because of their high surface-area-to-volume ratio. This permits strong electric fields while reducing thermal gradients and convection that would disrupt separation.}
    
115. {Why does Joule heating impair electrophoretic separation?} : {Electrical current heats the electrolyte. Temperature gradients change viscosity and mobility across the capillary, producing migration differences and band broadening. Excessive heating can also destabilize the system.}
    
116. {Why does electroosmotic flow arise in a silica capillary?} : {Deprotonated silanol groups make the wall negatively charged. An excess of mobile cations develops near the wall; when these ions move under an electric field, they drag the surrounding liquid, producing bulk flow.}
    
117. {Why does electroosmotic flow commonly increase as silica-surface pH rises?} : {Higher pH generally deprotonates more silanol groups, increasing surface charge and altering the electrical double layer. This commonly increases electroosmotic mobility, although the relationship depends on electrolyte composition and surface condition.}
    
118. {Why can electroosmotic flow reduce broadening compared with pressure-driven flow?} : {Its velocity profile is approximately flat through most of the capillary, whereas pressure-driven flow is parabolic. A flatter profile reduces differences in transit time across the capillary. It does not inherently require triangular analyte peaks.}
    
119. {Why can cations, neutral molecules, and anions all reach one detector?} : {Observed motion combines electrophoretic migration and electroosmotic transport. If cathodic EOF is strong enough, it carries neutral molecules and even anions toward a cathodic detector despite the anions’ opposing electrophoretic motion.}
    
120. {Why are ordinary neutral analytes not separated from one another by CZE?} : {They have essentially no electrophoretic mobility and therefore travel together with EOF. Distinguishing them requires an additional interaction mechanism, such as partitioning into a suitable pseudostationary phase.}
    
121. {Why is apparent mobility the sum of electrophoretic and electroosmotic mobilities?} : {An analyte moves relative to the liquid while the liquid itself moves relative to the capillary. Using a consistent direction convention, μₐₚₚ = μₑₚ + μₑₒ. The signs determine whether the motions reinforce or oppose each other.}
    
122. {Why must total capillary length and detector distance be distinguished?} : {The electric field depends on the full length between reservoirs, but measured migration time covers only the distance to the detector. Thus μₐₚₚ = L𝑑Lₜ/(Vt), where L𝑑 is the effective detection length.}
    
123. {Why can electrolyte composition modify or reverse EOF?} : {Ionic strength changes the electrical double layer, solvents alter viscosity and permittivity, and adsorbing modifiers change surface charge. A cationic surface coating can even reverse the usual direction of electroosmotic transport.}
    
124. {Why does changing pH alter CZE selectivity?} : {Acids and bases change charge as pH changes. Their electrophoretic mobilities therefore change by different amounts. pH also affects EOF, so it influences both separation selectivity and overall migration.}
    
125. {Why can complex-forming agents improve electrophoretic separation?} : {Complexation changes an analyte’s effective charge, size, or both. Different binding strengths then produce different average mobilities, helping separate analytes with otherwise similar behavior.}
    
126. {Why is pressure injection generally less compositionally selective than electrokinetic injection?} : {Pressure introduces a liquid volume largely independently of analyte mobility. Electrokinetic injection favors species that migrate efficiently under the injection field and is also influenced by EOF and sample conductivity.}
    
127. {Why can electrokinetic injection enrich analytes but bias quantification?} : {Selected ions enter the capillary faster than less mobile species, producing enrichment. The injected composition can therefore differ from the sample, making signal depend on injection conditions as well as concentration.}
    
128. {Why is indirect UV detection useful in electrophoresis?} : {A UV-absorbing background electrolyte provides a measurable baseline. Nonabsorbing analytes displace absorbing ions and produce decreases in absorbance, enabling detection without giving each analyte its own chromophore.}
    
129. {Why do cyclodextrins permit chiral electrophoretic separation?} : {Enantiomers form diastereomeric complexes with a chiral selector. Different complex stability or mobility creates different average migration rates, allowing separation even when the uncomplexed enantiomers have identical mobility.}
    
130. {Why are gels or polymer solutions needed to separate DNA fragments and SDS-treated proteins by size?} : {DNA fragments have broadly similar charge-to-mass ratios, and SDS makes protein charge-to-mass ratios more uniform. A sieving matrix introduces size-dependent resistance, allowing smaller species to migrate more readily.}
    
131. {Why does isoelectric focusing create narrow protein bands, and why combine it with SDS-PAGE?} : {Proteins migrate toward the pH at which their net charge is zero. If they diffuse away, they regain charge and migrate back. Combining this pI separation with SDS-PAGE separates by two different properties; SDS-PAGE alone is not inherently two-dimensional.}
    

## 11. Infrared spectroscopy: why molecules absorb specific frequencies

132. {Why does radiation energy determine which molecular process is observed?} : {A transition requires an appropriate energy difference. Because E = hν = hc/λ, different spectral regions access different processes: rotations, vibrations, electronic excitation, or spin transitions under suitable conditions.}
    
133. {Why is IR spectroscopy suited to studying molecular vibrations?} : {Many vibrational energy differences correspond to infrared photon energies. Absorption at those frequencies therefore reveals motions associated with particular bonds and molecular structures.}
    
134. {Why are IR spectra commonly plotted against wavenumber?} : {Wavenumber ṽ = 1/λ is directly proportional to frequency and photon energy. This makes comparisons between vibrational energies convenient and produces a practical scale expressed in cm⁻¹.}
    
135. {Why can a chemical bond be modeled as a spring?} : {Near its equilibrium length, stretching or compressing a bond produces an approximately proportional restoring force. This resembles Hooke’s law and explains the first approximation to vibrational frequency.}
    
136. {Why does bond strength affect vibrational frequency?} : {For a harmonic oscillator, ν = (1/2π)√(k𝑓/μ), where k𝑓 is the force constant. A stiffer bond has a stronger restoring force and therefore vibrates faster, all else being equal.}
    
137. {Why do heavier atoms lower vibrational frequency?} : {Increasing the reduced mass μ = m₁m₂/(m₁ + m₂) slows the oscillator. Isotopic substitution can therefore shift absorption bands without substantially changing the electronic nature of the bond.}
    
138. {Why does replacing hydrogen with deuterium shift stretching bands downward?} : {Deuterium increases the reduced mass of the bond. The frequency consequently decreases approximately according to the square-root mass relationship; many X–D stretches occur near 0.7 times the corresponding X–H frequency.}
    
139. {Why are molecular vibrational energies quantized?} : {The quantum-mechanical oscillator permits discrete energy states. In the harmonic approximation, Eᵥ = hν(v + ½), so absorption occurs between allowed levels rather than through any arbitrary energy increase.}
    
140. {Why does the harmonic model predict primarily fundamental transitions?} : {Its selection rule allows Δv = ±1 for the usual dipole interaction. Absorption from the ground state therefore mainly excites v = 0 to v = 1, with evenly spaced energy levels.}
    
141. {Why must real bonds be described as anharmonic?} : {Bond compression and stretching are not perfectly symmetric, and sufficiently large stretching causes dissociation. Real energy levels become closer together at higher energy, and weak overtone transitions become possible.}
    
142. {Why are overtone bands not exact integer multiples of the fundamental?} : {Anharmonicity reduces the spacing between successively higher vibrational levels. A transition spanning several levels therefore generally requires less energy than the corresponding integer multiple of the lowest fundamental transition.}
    
143. {Why is a dipole-moment change required for an IR-active vibration?} : {The radiation’s oscillating electric field must couple to the molecular motion. A vibration that changes molecular dipole moment provides that coupling; one that leaves it unchanged can be IR-inactive.}
    
144. {Why do stretching and bending vibrations appear at different frequencies?} : {Stretching changes bond lengths, while bending changes bond angles. Their effective restoring forces differ, and bending commonly requires less energy. Rocking, scissoring, wagging, and twisting are different bending motions.}
    
145. {Why does a molecule have many vibrational modes?} : {Atoms can move in multiple coordinated patterns. After removing overall translation and rotation, a nonlinear molecule has 3n − 6 normal modes and a linear molecule has 3n − 5, where n is atom count. Not every mode produces a distinct observable IR band.}
    
146. {Why can gas-phase IR spectra show rotational fine structure?} : {Gas molecules rotate relatively freely, and vibrational transitions can accompany changes in rotational state. In liquids and solids, interactions and collisions broaden or restrict these motions, usually obscuring individual rotational lines.}
    
147. {Why did dispersive IR instruments use sample and reference beams?} : {Comparing the two beams compensates for source intensity and absorption by solvent or background materials. Dispersive instruments select wavelengths sequentially, which makes a full spectral measurement comparatively slow.}
    
148. {Why did FTIR develop beyond dispersive IR?} : {An interferometer encodes many frequencies within one measurement, avoiding sequential wavelength selection and narrow monochromator slits. Rapid acquisition enables repeated scans and improved signal-to-noise under suitable noise conditions.}
    
149. {Why does a Michelson interferometer produce an interferogram?} : {A beam is divided between fixed and moving mirrors and then recombined. Changing optical path difference makes each frequency alternate between constructive and destructive interference, producing an intensity pattern containing spectral information.}
    
150. {Why are Fourier transformation, sufficient mirror travel, and apodization needed?} : {Fourier transformation separates the encoded frequency contributions. Longer maximum optical path difference improves resolution. Finite measurement length creates spectral sidelobes, which apodization reduces at the cost of some peak broadening.}
    
151. {Why are background spectra, averaging, and suitable detectors essential in FTIR?} : {Background measurements correct source, optics, and atmospheric contributions. Averaging reduces random noise approximately with √n. Detector choice balances wavelength response, sensitivity, and cooling requirements; thermal detectors can be convenient while some semiconductor detectors offer greater sensitivity.}
    
152. {Why were different IR sampling methods, especially ATR, developed?} : {Transmission requires suitable path length and IR-transparent materials, so gases, liquid films, solutions, and KBr pellets need different arrangements. ATR uses an evanescent field at a high-index crystal surface, allowing many samples to be measured with little preparation. Good contact remains essential.}
    
153. {Why do MIR and NIR support different analytical approaches?} : {MIR contains many relatively interpretable fundamental bands and a structurally distinctive fingerprint region. NIR mainly contains overlapping overtone and combination bands, so quantitative and identification applications often require reference databases, multivariate calibration, and validation against independent samples.}
    

## 12. Raman spectroscopy: why scattered light reveals vibrations

154. {Why was Raman spectroscopy developed alongside IR spectroscopy?} : {Molecular vibrations can influence scattered light as well as absorb radiation. Raman provides another route to vibrational information, with selection rules that reveal some modes weak or absent in IR.}
    
155. {Why does Raman scattering change photon energy?} : {During inelastic scattering, energy is exchanged with a molecular vibration. The scattered photon can lose energy by exciting a vibration or gain energy from a molecule already in an excited vibrational state.}
    
156. {Why is Rayleigh scattering different from Raman scattering?} : {Rayleigh scattering is elastic, so the scattered photon retains its energy. Raman scattering is inelastic and produces an energy shift corresponding to a molecular transition.}
    
157. {Why is a polarizability change required for Raman activity?} : {The incident electric field induces a molecular dipole. A vibration must change how readily that dipole is induced to generate Raman scattering. A Raman-active mode does not universally have to be IR-inactive.} [Thermo Fisher Raman reference](https://assets.thermofisher.com/TFS-Assets/MSD/Reference-Materials/raman-spectroscopy-microscopy-and-imaging-bk56397-en.pdf)
    
158. {Why are Stokes signals usually stronger than anti-Stokes signals?} : {Most molecules occupy their vibrational ground state at ordinary temperatures. More molecules can therefore gain vibrational energy and produce Stokes scattering than can lose pre-existing vibrational energy and produce anti-Stokes scattering.}
    
159. {Why are intense lasers and strong rejection of Rayleigh light needed?} : {Raman scattering is intrinsically weak relative to transmitted and elastically scattered light. Intense, narrow-band excitation and optical filtering allow the small shifted signals to be measured.}
    
160. {Why are Raman spectra reported as shifts from the excitation frequency?} : {The shift represents the molecular vibrational energy difference. Using this relative scale permits comparison of vibrational features measured with different laser wavelengths.}
    
161. {Why do IR and Raman provide complementary evidence?} : {IR intensity depends on dipole-moment change, while Raman intensity depends on polarizability change. Their relative responses therefore emphasize different motions. For centrosymmetric molecules, the mutual-exclusion rule gives a particularly clear separation between IR-active and Raman-active fundamental modes.}
    

## 13. Mass spectrometry: why ionization methods evolved

162. {Why must a mass spectrometer form ions?} : {Its electric and magnetic fields manipulate charged particles. Neutral molecules cannot be controlled in the same way, so ionization converts analytes into species that can be transported, separated, and detected.}
    
163. {Why does mass spectrometry measure mass-to-charge ratio rather than mass directly?} : {Ion motion depends on both mass and charge. A doubly charged ion has approximately half the m/z of a singly charged ion of similar mass, making charge-state interpretation necessary.}
    
164. {Why do mass analyzers commonly operate under vacuum?} : {Collisions with gas molecules can scatter ions, change their energies, or cause reactions. Low pressure allows more controlled trajectories and preserves the relationship between ion motion and m/z.}
    
165. {Why were multiple ionization methods developed?} : {Analytes differ in volatility, polarity, molecular size, and thermal stability. Methods also differ in how much fragmentation they cause. Ionization must therefore be matched to both sample properties and the desired information.}
    
166. {Why does electron ionization cause extensive fragmentation?} : {Energetic electrons remove an electron from gas-phase molecules, forming radical cations with excess internal energy. These ions often break into smaller charged and neutral fragments.}
    
167. {Why is EI fragmentation analytically valuable?} : {Fragment patterns reflect molecular structure. Standardized operating conditions, commonly 70 eV, produce reproducible patterns that can be compared with spectral libraries and used to support identification.}
    
168. {Why can the molecular ion be weak or absent in EI?} : {Some radical cations fragment faster than they survive to detection. Their spectra can therefore contain abundant fragment ions but little signal representing the intact molecule.}
    
169. {Why was chemical ionization developed?} : {When intact molecular-mass information is difficult to obtain by EI, ionized reagent gas can transfer charge or a proton more gently. CI often produces strong quasi-molecular ions with less fragmentation.}
    
170. {Why does CI still require volatile, thermally suitable analytes?} : {The ion–molecule reactions occur in the gas phase. An analyte must still be vaporized without unacceptable decomposition, so CI does not solve the basic volatility limitations of gas-phase sample introduction.}
    
171. {Why was electrospray ionization important for biomolecular analysis?} : {It transfers many polar, nonvolatile molecules from solution into gas-phase ions without requiring bulk analyte vaporization. This enabled analysis of peptides, proteins, and other thermally fragile molecules.}
    
172. {Why does ESI generate charged droplets?} : {A high electric field at the liquid outlet concentrates charge and drives formation of a spray. Solvent evaporation reduces droplet size while retaining charge, preparing the droplets for further breakup and ion release.}
    
173. {Why do electrospray droplets undergo Coulomb fission?} : {As droplets shrink, charge repulsion becomes stronger relative to stabilizing surface tension. At the Rayleigh limit, instability causes the droplets to divide into smaller charged droplets.}
    
174. {Why are more than one ESI ion-release model needed?} : {Different analytes can leave droplets through different mechanisms. The charged-residue model describes ions remaining after extensive drying, while ion-evaporation models describe ion ejection from small droplets. A single mechanism does not explain every system.}
    
175. {Why does ESI often produce multiply charged proteins?} : {Proteins contain many sites that can carry charge. Multiple protonation places a very large molecular mass within a comparatively modest m/z range, allowing analyzers with limited m/z ranges to measure it.}
    
176. {Why can coeluting substances suppress ESI signals?} : {They compete for droplet charge or surface access and can alter evaporation and ion release. Signal therefore depends on the surrounding matrix as well as analyte concentration, motivating better separation and appropriate quantitative controls.}
    
177. {Why was APCI developed alongside ESI?} : {APCI vaporizes the effluent and uses discharge-generated reagent ions to ionize analytes in the gas phase. It is useful for many smaller, less polar compounds that ionize poorly by ESI, provided they tolerate vaporization.}
    
178. {Why was MALDI developed for large molecules?} : {An absorbing matrix takes up laser energy and assists analyte desorption and ionization. This allows many large biomolecules and polymers to enter the gas phase with limited fragmentation and commonly relatively low charge states.}
    
179. {Why can MALDI produce molecular images?} : {Spectra are acquired at known positions across a matrix-coated surface. Mapping the intensity of selected m/z values reconstructs spatial distributions, although matrix deposition, ion suppression, and laser spot size affect image quality and interpretation.}
    

## 14. Why different mass analyzers and detectors exist

180. {Why is a quadrupole useful as a mass filter?} : {Combined radio-frequency and direct-current fields permit stable trajectories only for selected m/z values. Other ions become unstable and fail to pass through, providing controllable mass selection in a compact device.}
    
181. {Why does quadrupole scanning provide a spectrum?} : {Changing the field settings successively transmits different m/z values. Recording signal during this sequence builds a mass spectrum, although measurement time is divided among the scanned masses.}
    
182. {Why does selected-ion monitoring improve targeted detection?} : {The instrument spends more time measuring selected ions instead of scanning a broad mass range. This increases useful sampling of known targets, but provides less information about unexpected compounds.}
    
183. {Why was the triple quadrupole developed?} : {A first quadrupole selects precursor ions, a collision cell generates fragments, and a final quadrupole measures product ions. This adds a second level of selection and enables sensitive, targeted tandem-MS measurements.}
    
184. {Why does collision-induced dissociation reveal structural information?} : {Collisions convert some ion kinetic energy into internal energy. Resulting bond cleavage generates product ions whose masses and relationships reveal parts of the original structure.}
    
185. {Why is multiple-reaction monitoring effective for quantitative analysis?} : {It monitors specified precursor-to-product transitions. Requiring both masses reduces unrelated background, while focused acquisition improves target measurement. Interfering compounds can still share a transition, so retention and additional transitions remain useful.}
    
186. {Why does a product-ion scan provide different information from MRM?} : {A product-ion scan records many fragments from one selected precursor, supporting structural interpretation. MRM measures selected fragments repeatedly, prioritizing targeted detection and quantification over a complete fragmentation spectrum.}
    
187. {Why were ion traps developed?} : {They store ions rather than immediately transmitting them. Accumulation improves full-scan sensitivity, and repeated isolation and fragmentation within the same device permits multistage MSⁿ experiments.}
    
188. {Why do space-charge effects limit ion-trap performance?} : {Stored ions repel one another and perturb the trapping field. Excess ion populations can shift apparent masses, reduce resolution, and distort quantitative response, so ion loading must be controlled.}
    
189. {Why were Orbitrap analyzers developed?} : {They determine m/z from ion oscillation frequencies in an electrostatic field, enabling high resolving power and accurate-mass measurement. This provides detailed composition information without requiring the superconducting magnet used in FT-ICR instruments.}
    
190. {Why does Orbitrap resolving power depend on measurement time?} : {Closely spaced frequencies require longer observation to distinguish them. Longer transients improve frequency discrimination but reduce the speed at which successive spectra can be acquired.}
    
191. {Why do magnetic-sector instruments separate ions?} : {A magnetic field bends ion trajectories according to momentum and charge. With controlled acceleration, ions of different m/z follow different radii, allowing spatial separation.}
    
192. {Why were double-focusing sector instruments developed?} : {Initial ion-energy and trajectory variations blur magnetic-sector separation. Combining electrostatic and magnetic focusing compensates for these spreads, improving resolving power and mass measurement.}
    
193. {Why does time-of-flight analysis separate ions by arrival time?} : {Ions accelerated through the same potential acquire kinetic energy proportional to charge. Their speeds therefore depend on m/z: lower-m/z ions arrive sooner, with flight time proportional to √(m/z) under ideal conditions.}
    
194. {Why were reflectrons added to TOF instruments?} : {Ions with the same m/z can leave the source with different kinetic energies. Faster ions penetrate farther into the reflectron and take a longer path, compensating arrival-time differences and improving resolution.}
    
195. {Why are TOF and hybrid instruments useful for rapid, information-rich analysis?} : {TOF records a broad mass range rapidly. Hybrid instruments combine complementary functions, such as quadrupole precursor selection with TOF or Orbitrap measurement, allowing both controlled fragmentation and detailed mass analysis.}
    
196. {Why are electron multipliers and microchannel plates used?} : {A small ion signal must be amplified. Electron multipliers generate cascades of secondary electrons, while microchannel plates provide many small multiplication channels and fast response suitable for time-resolved ion arrival.}
    
197. {Why do Fourier-transform analyzers use image-current detection?} : {Moving ion packets induce a small electrical signal in nearby electrodes without requiring immediate ion impact. Fourier transformation extracts oscillation frequencies, which are converted into m/z values.}
    

## 15. Coupling methods and interpreting mass spectra

198. {Why couple chromatography or electrophoresis to mass spectrometry?} : {Separation reduces sample complexity and distinguishes compounds before detection. MS then supplies mass and fragmentation information, combining separation behavior with evidence about molecular composition and structure.}
    
199. {Why is GC relatively straightforward to couple with EI-MS?} : {GC delivers gas-phase analytes in a comparatively small carrier-gas stream. Pumping removes much of that gas, allowing analytes to enter a vacuum ion source through a heated interface.}
    
200. {Why did LC-MS require specialized interfaces?} : {A liquid effluent creates a large solvent-vapor load incompatible with direct introduction into the analyzer vacuum. Atmospheric-pressure ionization and staged pumping allow solvent removal and selective transfer of ions.}
    
201. {Why should LC-MS mobile phases use volatile additives?} : {Nonvolatile salts can leave deposits, interfere with ion formation, and contaminate the interface. Volatile buffers and modifiers are more readily removed during desolvation.}
    
202. {Why is CE-MS coupling technically demanding?} : {CE uses very low flow rates and a high-voltage separation circuit, while MS requires stable ion production and transfer. The interface must maintain both electrical continuity for electrophoresis and suitable conditions for ionization.}
    
203. {Why must MS acquisition speed match chromatographic peak width?} : {A narrow peak lasts only a short time. Slow scans or too many monitored transitions provide too few measurements across it, impairing integration, peak-shape assessment, and recognition of coelution.}
    
204. {Why do total-ion and extracted-ion chromatograms provide different views?} : {A total-ion chromatogram combines signals across measured masses. An extracted-ion chromatogram follows a chosen m/z window, reducing unrelated signal and revealing compounds that may be obscured in the total trace.}
    
205. {Why do molecules produce isotope patterns?} : {Elements occur as isotopes with different masses. Molecules therefore exist as combinations of isotopes, producing several peaks whose spacing and intensities reflect isotope abundances and elemental composition.}
    
206. {Why are chlorine and bromine isotope patterns especially recognizable?} : {Their abundant heavy isotopes produce strong peaks roughly two mass units apart for singly charged ions. One chlorine commonly gives an M:M+2 ratio near 3:1, whereas one bromine gives approximately 1:1. Multiple atoms create more complex patterns.}
    
207. {Why does the M+1 peak often provide information about carbon count?} : {Each carbon atom offers a small probability of being ¹³C instead of ¹²C. For many modest-sized organic molecules, the first heavy-isotope contribution increases roughly with carbon count, though other isotopes also contribute.}
    
208. {Why does isotope spacing reveal charge state?} : {A fixed isotopic mass difference is divided by the ion’s charge number. A roughly 1 Da mass difference appears about 1 m/z apart for z = 1, 0.5 for z = 2, and 0.33 for z = 3.}
    
209. {Why must nominal, monoisotopic, and average mass be distinguished?} : {Nominal mass sums integer isotope mass numbers. Monoisotopic mass uses specified exact isotope masses, commonly the most abundant isotope of each element. Average mass includes abundance-weighted isotope contributions. Confusing them gives incorrect comparisons or formula assignments.}
    
210. {Why does high resolving power help distinguish ions with similar masses?} : {Different compositions can have the same nominal mass but slightly different exact masses. Narrower mass peaks reveal these differences. Resolving power is commonly expressed as m/Δm, with the peak-width convention specified.} [IUPAC resolving-power definition](https://goldbook.iupac.org/terms/view/R05321)
    
211. {Why are mass accuracy and resolving power different?} : {Resolving power describes the ability to distinguish nearby signals; accuracy describes agreement between measured and true mass. An instrument can produce narrow peaks at incorrectly calibrated positions. Mass error is commonly reported as [(measured − theoretical)/theoretical] × 10⁶ ppm.}
    
212. {Why does accurate mass constrain molecular formula without necessarily proving structure?} : {Elemental combinations have distinct exact masses, allowing many formulas to be excluded. However, constitutional isomers share a formula and exact mass, so fragmentation, separation, or other structural evidence is still required.}
    
213. {Why is charge deconvolution needed for ESI protein spectra?} : {One protein may produce many charge-state peaks. For a protonated ion, M = z[(m/z) − mₚ], where mₚ is proton mass. Assigning charges converts the envelope into a neutral-mass representation and avoids mistaking charge states for different proteins.}
    
214. {Why are proteins commonly digested before identification by MS?} : {Proteolysis creates smaller peptides that are easier to separate and fragment. Their measured masses or sequences can be compared with predicted peptides from protein databases, providing evidence for the parent protein.}
    
215. {Why does tandem-MS sequencing use differences between b and y ions?} : {Backbone cleavage commonly produces b ions retaining the N-terminus and y ions retaining the C-terminus. Differences between consecutive members of either series correspond to amino-acid residue masses, allowing sequence reconstruction.}
    
216. {Why must peptide interpretation consider water loss, charge, missing fragments, and ambiguity?} : {Residue masses differ from free amino-acid masses because peptide-bond formation eliminates water. Ion charge and terminal composition alter m/z; incomplete fragmentation leaves gaps; some residues, such as leucine and isoleucine, have identical masses. Identification therefore requires consistent evidence across multiple signals.}
    

## 16. Why ICP methods and elemental imaging evolved

217. {Why were ICP methods developed beyond conventional flame-based atomic methods?} : {Flames do not provide equally effective excitation for many elements. A hotter, energetic plasma atomizes, excites, and ionizes a broad range of elements, supporting efficient multielement analysis.}
    
218. {Why is argon commonly used for ICP?} : {It provides an inert environment and supports a stable plasma. Its chemical inactivity reduces unwanted reactions, although argon-derived ions can still create important spectral interferences in ICP-MS.}
    
219. {Why does an RF field sustain the plasma after ignition?} : {An initial spark supplies free electrons. The radio-frequency field transfers energy to charged particles, and collisions ionize and heat the gas, sustaining the plasma while power and gas flow are maintained.}
    
220. {Why are liquid samples nebulized before entering the plasma?} : {Fine droplets are easier to dry, vaporize, and atomize than a continuous liquid stream. A spray chamber removes many large droplets, making sample introduction more stable and reducing excessive solvent loading.}
    
221. {Why does the plasma largely destroy molecular information?} : {Its high energy decomposes molecules and produces atoms and ions. The resulting measurement therefore reveals elemental content rather than preserving the original molecular structure.}
    
222. {Why can the same ICP source support optical emission and mass-spectrometric detection?} : {The plasma produces excited atoms and ions. Optical emission measures photons released during relaxation, while ICP-MS extracts ions and distinguishes them by m/z. The two techniques measure different products of the same energetic source.}
    
223. {Why does ICP-OES require high-quality wavelength separation?} : {Many elements produce multiple emission lines, and nearby lines can overlap. Adequate spectral resolution and suitable line selection are necessary to distinguish the analyte from background and other elements.}
    
224. {Why is the strongest emission line not always the best analytical choice?} : {A strong line may overlap with another element or become unsuitable at high concentration. A weaker but cleaner line can provide more accurate measurement in the actual sample matrix.}
    
225. {Why does ICP-MS commonly offer very low elemental detection limits?} : {The plasma produces ions efficiently for many elements, and mass-selective detection can measure small ion populations against relatively low background. Actual detection limits depend on the element, isotope, matrix, contamination, and interference control.}
    
226. {Why does ICP-MS need a specialized atmospheric-pressure-to-vacuum interface?} : {The plasma operates near atmospheric pressure, whereas the mass analyzer requires vacuum. Sampling and skimmer cones, staged pumping, and ion optics extract a manageable ion beam while removing most gas.}
    
227. {Why do polyatomic interferences occur in ICP-MS?} : {Atoms from argon, solvent, and the sample matrix can form ions whose nominal m/z overlaps with an analyte. For example, ⁴⁰Ar¹⁶O⁺ interferes with ⁵⁶Fe⁺, and ⁴⁰Ar³⁵Cl⁺ interferes with ⁷⁵As⁺.}
    
228. {Why can high-resolution ICP-MS separate some spectral interferences?} : {An interfering molecular ion and an elemental ion can share nominal mass but differ in exact mass. Sufficient resolving power distinguishes them, although some overlaps demand impractical resolution or another correction approach.}
    
229. {Why were collision cells developed for ICP-MS?} : {Polyatomic ions can undergo more collisions and lose more energy than analyte ions. Energy discrimination after a helium collision cell can preferentially remove these interferences, allowing cleaner measurement without relying solely on high resolving power.} [Agilent ICP-MS primer](https://www.agilent.com/cs/library/primers/public/5989-1270EN-AGI_74_combined.pdf)
    
230. {Why were reaction cells developed alongside collision cells?} : {Selected gases react differently with analyte and interfering ions. They can remove an interference or shift an analyte to a cleaner product-ion mass. Gas selection must account for reaction selectivity and possible new interferences.} [Agilent comparison of ICP-MS configurations](https://www.agilent.com/en/product/atomic-spectroscopy/inductively-coupled-plasma-mass-spectrometry-icp-ms/comparing-single-triple-quadrupole-icp-ms)
    
231. {Why do matrix effects remain after spectral interferences are controlled?} : {Sample composition can alter nebulization, plasma conditions, ion formation, and ion transmission. Dilution, internal standards, matrix matching, or standard addition may therefore be needed to obtain reliable concentrations.}
    
232. {Why are flame AAS, graphite-furnace AAS, ICP-OES, and ICP-MS all still useful?} : {They offer different balances of cost, sample consumption, detection limit, matrix tolerance, and multielement capability. Flame AAS suits many routine measurements; graphite furnaces use small volumes; ICP-OES supports robust multielement work; ICP-MS provides sensitive elemental and isotope analysis.}
    
233. {Why was laser-ablation ICP-MS developed?} : {Some questions concern elemental distributions in solids rather than dissolved bulk composition. A laser removes small amounts of material, which a carrier gas transports to the plasma, allowing localized elemental analysis without dissolving the entire sample.}
    
234. {Why can laser ablation produce images and depth profiles?} : {Scanning across positions maps lateral elemental variation. Repeated pulses at one position remove successive layers, revealing changes with depth. Spatial resolution depends on crater dimensions, material response, transport, and measurement timing.}
    
235. {Why does reliable instrumental analysis require more than an advanced instrument?} : {The result depends on representative sampling, suitable preparation, appropriate separation or excitation, valid calibration, interference control, and correct interpretation. Methods evolved to solve particular limitations; understanding those limitations is what allows the instrument’s signal to become trustworthy chemical information.}