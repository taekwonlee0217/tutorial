## 1. Theory of chromatography

### 1.1. Basic principles and thin-layer chromatography

1. {What is chromatography?} : {Chromatography separates the components of a mixture because they distribute differently between a moving mobile phase and a stationary phase, causing them to travel at different rates.}
    
2. {Which types of mobile and stationary phases can be used in chromatography?} : {The mobile phase can be a liquid, gas, or supercritical fluid, while the stationary phase can be a solid surface or an immobilized liquid or polymer.}
    
3. {Which interactions can cause chromatographic retention?} : {Retention can arise from partitioning, adsorption, ion exchange, affinity binding, and other interactions that cause an analyte to spend time in or on the stationary phase.}
    
4. {What is a chromatogram?} : {A chromatogram plots detector response against time or mobile-phase volume, with separated analytes generally appearing as peaks.}
    
5. {How is thin-layer chromatography performed?} : {In thin-layer chromatography, sample and standard solutions are applied near the bottom of a coated plate, which is placed in a development chamber so that the solvent rises by capillary action and separates the components.}
    
6. {What is the retention factor Rf in thin-layer chromatography?} : {The TLC retention factor is Rf = distance travelled by the centre of the analyte spot divided by distance travelled by the solvent front, with both distances measured from the starting line.}
    
7. {What information does a TLC Rf value provide?} : {An Rf value supports comparison with standards and interpretation of retention behaviour, but identification requires comparable experimental conditions because Rf depends on the stationary phase, solvent, and other operating conditions.}
    
8. {How do TLC migration distances relate to column chromatography?} : {Under comparable separation conditions, an analyte with a high TLC Rf value interacts less strongly with the stationary phase and generally has a shorter retention time in column chromatography.}
    
9. {What is the difference between volumetric flow rate and linear velocity?} : {Volumetric flow rate F describes the volume of mobile phase passing per unit time, whereas linear velocity u describes the distance travelled by the mobile phase per unit time.}
    
10. {What are retention time and retention volume?} : {Retention time tR is the time between injection and the analyte peak maximum, while retention volume VR is the mobile-phase volume required for elution and equals F × tR at constant flow.}
    
11. {What is the hold-up time or dead time?} : {The hold-up time tM is the time required for an unretained species to pass through the chromatographic system and represents the mobile-phase transit time.}
    
12. {What is adjusted retention time?} : {Adjusted retention time is t′R = tR − tM and describes the additional delay caused by retention in the stationary phase.}
    
13. {What is the partition coefficient K?} : {The partition coefficient is K = CS/CM, where CS and CM are the equilibrium analyte concentrations in the stationary and mobile phases.}
    
14. {How is the column retention factor k related to phase distribution?} : {The retention factor is k = KVS/VM, where VS and VM are the stationary- and mobile-phase volumes, and it represents the equilibrium ratio of analyte amounts in the two phases.}
    
15. {How is the retention factor calculated from a chromatogram?} : {The retention factor is k = (tR − tM)/tM, so the retention time can also be expressed as tR = tM(1 + k).}
    
16. {What does a retention factor of three mean?} : {A retention factor of three means that the analyte amount in the stationary phase is three times that in the mobile phase at equilibrium and that its retention time is four times the hold-up time.}
    
17. {What is the separation factor or selectivity factor α?} : {For two analytes ordered so that the second is more retained, the selectivity factor is α = k2/k1 = t′R2/t′R1 and indicates how differently the system retains them.}
    

### 1.2. Peak broadening and column efficiency

18. {Which two features determine how well chromatographic peaks are separated?} : {Peak separation depends on the difference between their retention times and their widths, because peaks can overlap even when their maxima occur at different times.}
    
19. {Why does an injected sample band broaden during chromatography?} : {A sample band broadens because analyte molecules follow different paths, diffuse along the column, and transfer between phases at finite rates.}
    
20. {How are Gaussian peak widths related to standard deviation?} : {For an ideal Gaussian peak, the baseline width is approximately 4σ and the full width at half maximum is approximately 2.355σ.}
    
21. {What is a theoretical plate?} : {A theoretical plate is a conceptual section of a column in which the analyte is assumed to establish equilibrium between the mobile and stationary phases.}
    
22. {What does the number of theoretical plates N describe?} : {The plate number N describes column efficiency, with a larger value indicating narrower peaks relative to their retention times.}
    
23. {How is plate number calculated using baseline peak width?} : {Plate number is calculated as N = 16(tR/w)², where tR and the baseline peak width w must use the same time units.}
    
24. {How is plate number calculated using half-height peak width?} : {Plate number is calculated as N = 5.54(tR/w½)², where w½ is the full peak width at half maximum.}
    
25. {What is the height equivalent to a theoretical plate?} : {Plate height H, also called HETP, equals L/N, where L is column length, and a smaller value indicates greater efficiency per unit length.}
    
26. {How does increasing column length affect efficiency?} : {Increasing column length increases plate number when plate height remains constant, but also increases analysis time and the pressure required to maintain the same flow.}
    

### 1.3. The van Deemter equation

27. {What is the van Deemter equation?} : {The van Deemter equation is H = A + B/u + Cu, which relates plate height to eddy dispersion, longitudinal diffusion, and resistance to mass transfer.}
    
28. {What causes the A term?} : {The A term represents eddy dispersion caused by different flow paths through a packed column, with more uniform packing and smaller particles generally reducing this contribution.}
    
29. {What causes the B/u term?} : {The B/u term represents longitudinal diffusion from the concentrated centre of a band toward its less concentrated edges, which becomes more important at low mobile-phase velocity.}
    
30. {How is the longitudinal diffusion coefficient related to the B term?} : {The B coefficient is commonly expressed as B = 2γD, where D is the analyte diffusion coefficient and γ accounts for obstruction by the column structure.}
    
31. {What causes the Cu term?} : {The Cu term represents delayed equilibration between phases, which increases at higher velocity because analytes have less time to diffuse and establish equilibrium.}
    
32. {Which processes contribute to resistance to mass transfer?} : {Mass-transfer resistance includes diffusion through the flowing mobile phase, stagnant liquid in particle pores, and the stationary-phase film.}
    
33. {Why do smaller particles and thinner stationary-phase films improve efficiency?} : {Smaller particles and thinner films shorten diffusion distances and reduce the time required for analytes to transfer between phases.}
    
34. {Why is there an optimum mobile-phase velocity?} : {An optimum velocity exists because increasing velocity reduces longitudinal diffusion but increases mass-transfer broadening.}
    
35. {How is the optimum velocity obtained from the simplified van Deemter equation?} : {For H = A + B/u + Cu, the minimum occurs at uopt = √(B/C), giving Hmin = A + 2√(BC).}
    
36. {Why is longitudinal diffusion generally more important in GC than in HPLC?} : {Longitudinal diffusion is generally more important in GC because analytes diffuse much faster in gases than in liquids.}
    

### 1.4. Resolution, peak capacity, and peak shape

37. {How is chromatographic resolution calculated?} : {Resolution is RS = 2(tR2 − tR1)/(w1 + w2), where w1 and w2 are the baseline widths of the two peaks.}
    
38. {What resolution is commonly associated with baseline separation?} : {A resolution of approximately 1.5 commonly indicates baseline separation for similarly sized Gaussian peaks, although unequal peak sizes and nonideal shapes can require greater resolution.}
    
39. {Which three main parameters control resolution?} : {Resolution depends primarily on efficiency N, selectivity α, and retention k.}
    
40. {What equation illustrates the contributions of efficiency, selectivity, and retention?} : {For approximately equal peak efficiencies, a commonly used expression is RS ≈ (√N/4)[(α − 1)/α][k2/(1 + k2)].}
    
41. {Why does increasing efficiency give diminishing improvements in resolution?} : {Resolution increases approximately with √N, so doubling resolution through efficiency alone requires approximately four times as many theoretical plates.}
    
42. {Why is changing selectivity often an effective way to improve a separation?} : {Changing stationary-phase chemistry, solvent composition, or analyte ionization can alter relative retention and separate peaks that remain close together despite high efficiency.}
    
43. {Why does increasing retention eventually provide little improvement?} : {The retention contribution approaches a limiting value as k increases, while analysis time continues to grow.}
    
44. {What is chromatographic peak capacity?} : {Peak capacity is the maximum number of peaks that could theoretically fit within a specified separation interval at a defined resolution.}
    
45. {How is peak capacity expressed in the slide’s isocratic model?} : {The model gives np = 1 + [√N/(4RS)]ln[(1 + klast)/(1 + kfirst)], showing its dependence on efficiency, required resolution, and the retention range.}
    
46. {Why can multidimensional chromatography increase peak capacity?} : {Two sufficiently independent separation dimensions can produce an overall peak capacity approaching the product of their individual capacities, although correlation and transfer losses reduce the practical gain.}
    
47. {What is the USP tailing factor?} : {The USP tailing factor is T = W0.05/(2f), where W0.05 is the peak width at 5% height and f is the distance from the leading edge to the peak centre at that height.}
    
48. {What does a tailing factor indicate?} : {A factor near one indicates a symmetrical peak, a value above one indicates tailing, and a value below one indicates fronting.}
    

## 2. High-performance liquid chromatography

### 2.1. HPLC, UHPLC, and instrument layout

49. {Why does HPLC use small stationary-phase particles?} : {Small particles reduce eddy dispersion and mass-transfer distances, producing efficient separations but requiring high pressure to force liquid through the column.}
    
50. {How does UHPLC differ from conventional HPLC?} : {UHPLC commonly uses particles around 2 µm or smaller and equipment capable of higher pressures, allowing faster separations or higher efficiency.}
    
51. {How does particle size affect column backpressure?} : {At comparable conditions, backpressure increases approximately with the inverse square of particle diameter, making very small particles demanding on pumps and connections.}
    
52. {What does the ratio L/dp describe?} : {The ratio of column length L to particle diameter dp provides a useful approximate measure of resolving potential when packing quality and operating conditions are comparable.}
    
53. {What are the main components of an HPLC instrument?} : {An HPLC instrument contains mobile-phase reservoirs, a degasser, pumps, an injector or autosampler, a temperature-controlled column compartment, a detector, and a data system.}
    
54. {What is isocratic elution?} : {Isocratic elution uses a constant mobile-phase composition throughout the chromatographic run.}
    
55. {What is gradient elution?} : {Gradient elution changes mobile-phase composition during the run, usually increasing solvent strength to elute strongly retained analytes more quickly.}
    
56. {How does low-pressure gradient mixing work?} : {Low-pressure mixing proportions solvents before a common pump pressurizes the resulting mixture.}
    
57. {How does high-pressure gradient mixing work?} : {High-pressure mixing uses separate pumps to pressurize individual solvents before combining them in a mixer.}
    

### 2.2. Degassing, pumps, injection, and columns

58. {Why must HPLC mobile phases be degassed?} : {Degassing prevents dissolved gases from forming bubbles that can disrupt pumping, flow stability, and detector response.}
    
59. {How does an online membrane degasser work?} : {An online degasser passes the liquid through gas-permeable tubing inside a reduced-pressure chamber so that dissolved gases leave the mobile phase.}
    
60. {How can mobile phases alternatively be degassed?} : {Helium purging removes dissolved gases by passing helium through the solvent reservoir.}
    
61. {How do reciprocating-piston HPLC pumps maintain flow?} : {Coordinated pistons alternately draw in and deliver solvent, with auxiliary pumping and control reducing pulsation during the refill cycle.}
    
62. {How does a loop injector introduce a sample?} : {A switching valve first fills a sample loop and then connects it to the high-pressure mobile-phase stream, which carries the sample onto the column.}
    
63. {Why must injection volume match column dimensions?} : {An injection that is too large relative to column volume can broaden peaks, distort retention, and overload the separation.}
    
64. {What column dimensions are described in the lecture?} : {The lecture describes analytical HPLC columns approximately 3–25 cm long and 0.5–5 mm in internal diameter, commonly packed with particles around 1.5–5 µm.}
    
65. {How does column diameter affect the required flow rate?} : {At equal linear velocity, volumetric flow scales approximately with the square of internal diameter, so narrow columns require substantially lower flow rates.}
    
66. {Why is a guard column used?} : {A guard column protects the analytical column by retaining contaminants and strongly retained sample components before they damage or foul the main packing.}
    
67. {Why is column temperature controlled?} : {Temperature control improves reproducibility because temperature affects solvent viscosity, pressure, analyte retention, and separation selectivity.}
    

### 2.3. Detector characteristics

68. {Which characteristics are important when selecting an HPLC detector?} : {Detector selection considers detection limit, sensitivity, linear range, selectivity, gradient compatibility, response speed, robustness, and cost.}
    
69. {What is detector sensitivity?} : {Sensitivity is the change in detector response per change in analyte concentration or amount and is represented by the slope of the calibration relationship.}
    
70. {What is the detection limit?} : {The detection limit is the smallest analyte level distinguishable from background noise under defined conditions, with a signal-to-noise ratio of about three used as a common practical criterion.}
    
71. {How do concentration-sensitive and mass-flow-sensitive detectors differ?} : {A concentration-sensitive detector responds to analyte concentration in the detector cell, whereas a mass-flow-sensitive detector responds to the analyte mass reaching it per unit time.}
    
72. {How do bulk-property and solute-property detectors differ?} : {A bulk-property detector measures a change in a property of the entire eluent, while a solute-property detector measures a property associated primarily with the analyte.}
    
73. {Why must detector acquisition be fast enough?} : {The detector must record enough measurements across the narrowest peak to preserve its shape and allow reliable integration.}
    

### 2.4. HPLC detector types

74. {How does a UV-visible absorbance detector work?} : {A UV-visible detector measures light absorbed by analytes in a flow cell, with absorbance related to concentration through A = εbc within the valid Beer–Lambert range.}
    
75. {What is the advantage of a diode-array detector?} : {A diode-array detector records multiple wavelengths simultaneously, allowing spectral comparison, wavelength selection, and assessment of spectral consistency across a peak.}
    
76. {How does flow-cell path length affect UV detection?} : {A longer optical path increases absorbance sensitivity, but an excessively large cell volume can broaden chromatographic peaks.}
    
77. {How does a fluorescence detector work?} : {A fluorescence detector excites suitable analytes at one wavelength and measures their emitted light at another, often providing high sensitivity and selectivity.}
    
78. {Which analytes can be measured by fluorescence detection?} : {Fluorescence detection measures naturally fluorescent analytes or analytes converted into fluorescent derivatives.}
    
79. {How does a refractive-index detector work?} : {A refractive-index detector measures differences between the refractive index of the column effluent and that of a reference mobile phase through changes in refraction or reflected intensity.}
    
80. {Why is refractive-index detection poorly suited to gradients?} : {Changing solvent composition changes the bulk refractive index and creates a large background response that can obscure analyte signals.}
    
81. {How does an evaporative light-scattering detector work?} : {An ELSD nebulizes the effluent, evaporates the mobile phase, and measures light scattered by the remaining analyte particles.}
    
82. {What conditions are required for ELSD detection?} : {The mobile phase must be sufficiently volatile and the analytes must remain as particles after evaporation, making nonvolatile additives unsuitable.}
    
83. {How does a charged-aerosol detector work?} : {A CAD nebulizes and dries the effluent, transfers charge from ionized gas to analyte particles, and measures the collected particle charge.}
    
84. {Why are ELSD and CAD useful for compounds without chromophores?} : {ELSD and CAD detect particle formation rather than UV absorption, allowing measurement of many nonvolatile compounds without suitable chromophores.}
    
85. {How does amperometric detection work?} : {Amperometric detection applies a controlled electrode potential and measures the current produced when electroactive analytes are oxidized or reduced.}
    
86. {What are the roles of the working, reference, and auxiliary electrodes?} : {The working electrode supports the analyte reaction, the reference electrode provides a stable potential reference, and the auxiliary electrode completes the current circuit.}
    
87. {How does electrode potential influence selectivity?} : {Adjusting electrode potential can favour the analyte reaction while limiting oxidation or reduction of interfering substances.}
    
88. {How does coulometric detection differ from ordinary amperometric detection?} : {Coulometric detection aims to convert a large fraction of the analyte electrochemically and relates the transferred charge to analyte amount.}
    
89. {Why is pulsed amperometric detection used?} : {Pulsed amperometric detection alternates measurement and cleaning potentials to restore electrode surfaces that would otherwise become fouled by compounds such as sugars and polyalcohols.}
    
90. {How does post-column reaction detection work?} : {Post-column reaction detection mixes separated analytes with a reagent to form products that can be detected more sensitively or selectively.}
    

### 2.5. Stationary-phase properties

91. {Which physical properties of HPLC particles influence performance?} : {Important properties include particle diameter, size distribution, shape, porosity, pore diameter, surface area, and pressure resistance.}
    
92. {Why are narrow particle-size and pore-size distributions desirable?} : {Uniform particles and pores improve consistency of flow, diffusion, and analyte accessibility across the column.}
    
93. {What are core-shell particles?} : {Core-shell particles consist of a nonporous core surrounded by a porous layer, shortening diffusion paths while providing useful surface area and moderate backpressure.}
    
94. {What is a monolithic column?} : {A monolithic column contains a continuous porous stationary-phase structure rather than individual packed particles, with large flow channels and smaller pores providing surface area.}
    
95. {Why must stationary-phase chemical stability be considered?} : {The stationary phase must tolerate the mobile-phase pH, solvents, and operating conditions without dissolution or chemical degradation.}
    

### 2.6. Normal-phase HPLC and HILIC

96. {What defines normal-phase HPLC?} : {Normal-phase HPLC uses a polar stationary phase and a relatively nonpolar mobile phase, generally retaining more polar analytes more strongly.}
    
97. {Which stationary phases are used in normal-phase HPLC?} : {Typical phases include silica, alumina, and silica modified with polar groups such as diol, amino, or cyanopropyl groups.}
    
98. {How does increasing mobile-phase polarity affect normal-phase retention?} : {Increasing mobile-phase polarity generally increases elution strength because the solvent competes more effectively with analytes for polar stationary-phase sites.}
    
99. {What is an eluotropic series?} : {An eluotropic series ranks solvents according to their ability to elute analytes from a specified stationary phase.}
    
100. {Why are silanol groups important in silica chromatography?} : {Surface silanol groups provide polar adsorption sites that interact with analytes and solvents.}
    
101. {What is hydrophilic interaction liquid chromatography?} : {HILIC separates polar analytes on a polar stationary phase using an organic-rich mobile phase containing water, with retention involving a water-rich surface layer and additional interactions.}
    
102. {How is gradient elution commonly performed in HILIC?} : {HILIC gradients commonly increase the water fraction, strengthening elution and reducing retention of polar analytes.}
    

### 2.7. Reversed-phase HPLC

103. {What defines reversed-phase HPLC?} : {Reversed-phase HPLC uses a relatively nonpolar stationary phase and a polar mobile phase, commonly water or aqueous buffer mixed with an organic solvent.}
    
104. {Which stationary phases are used in reversed-phase HPLC?} : {Typical phases include C18, C8, phenyl, pentafluorophenyl, and other modified silica materials, as well as polymeric phases and porous graphitic carbon.}
    
105. {How does analyte polarity affect reversed-phase retention?} : {More hydrophobic analytes generally show stronger retention, while more polar or ionized analytes often elute earlier.}
    
106. {How does organic-solvent content affect reversed-phase retention?} : {Increasing the organic-solvent fraction generally increases elution strength and decreases retention.}
    
107. {How is a reversed-phase gradient commonly performed?} : {A reversed-phase gradient commonly increases the organic-solvent percentage over time to elute increasingly hydrophobic compounds.}
    
108. {Why does organic-solvent identity affect selectivity?} : {Different organic solvents provide different hydrogen-bonding and dipolar interactions, which can change the relative retention of analytes.}
    
109. {What is endcapping?} : {Endcapping reacts small silanizing reagents with residual silanol groups to reduce unwanted interactions after the main bonded phase has been attached.}
    
110. {Why can residual silanol groups cause problems?} : {Residual silanols can interact strongly with some analytes, particularly basic compounds, and cause tailing or altered selectivity.}
    
111. {Why are polymeric reversed-phase materials useful?} : {Polymeric materials such as polystyrene-divinylbenzene can provide broader pH tolerance than conventional silica-based phases.}
    
112. {How does mobile-phase pH affect reversed-phase separation?} : {Mobile-phase pH changes analyte ionization and can therefore alter retention, selectivity, and peak shape.}
    
113. {What is hydrophobic interaction chromatography?} : {Hydrophobic interaction chromatography retains biomolecules through hydrophobic interactions in aqueous high-salt conditions and commonly elutes them by lowering salt concentration.}
    

### 2.8. Size-exclusion chromatography and polymer analysis

114. {What is the principle of size-exclusion chromatography?} : {SEC separates analytes by their access to stationary-phase pores, ideally without adsorption or other specific interactions.}
    
115. {Why do large molecules elute first in SEC?} : {Large molecules enter fewer pores and therefore travel through a smaller accessible liquid volume than smaller molecules.}
    
116. {What equation describes SEC retention volume?} : {SEC retention follows VR = VI + KSEC VP, where VI is interstitial volume, VP is pore volume, and KSEC describes the fraction of pore volume accessible to the analyte.}
    
117. {What do KSEC values of zero and one indicate?} : {KSEC = 0 indicates complete exclusion from the pores, while KSEC = 1 indicates access to the full pore volume.}
    
118. {What can an apparent KSEC above one indicate?} : {An apparent KSEC above one can indicate additional retention through adsorption or other interactions that violate ideal size-exclusion behaviour.}
    
119. {How is molecular mass estimated by SEC?} : {Molecular mass is commonly estimated from a calibration of retention volume against log molecular mass, but the result depends on hydrodynamic size and similarity between samples and standards.}
    
120. {How are SEC, GPC, and gel filtration related?} : {SEC is the general term, GPC is commonly used for synthetic polymers in organic solvents, and gel filtration is commonly used for biomolecules in aqueous solutions.}
    
121. {Why may polymer GPC require high temperatures?} : {Some polymers dissolve only at elevated temperatures, as illustrated by polypropylene analysis in hot trichlorobenzene.}
    
122. {What is number-average molar mass Mn?} : {Number-average molar mass is Mn = ΣxiMi, where xi is the number fraction of chains with molar mass Mi.}
    
123. {What is weight-average molar mass Mw?} : {Weight-average molar mass is Mw = ΣwiMi = ΣxiMi²/ΣxiMi, which gives greater weighting to heavier polymer chains.}
    
124. {How are number fraction and mass fraction related?} : {The mass fraction is wi = xiMi/Mn, allowing number-based distributions to be converted into mass-based distributions.}
    
125. {What is polymer dispersity?} : {Dispersity is Đ = Mw/Mn and describes the breadth of a molar-mass distribution, with a value of one corresponding to identical chain molar masses.}
    
126. {What does the lecture’s polymer-distribution example show?} : {The example gives Mn = 47.7 kg/mol and Mw = 53.9 kg/mol, producing a dispersity of approximately 1.13.}
    
127. {How is number-average degree of polymerization estimated?} : {The number-average degree of polymerization is approximately DPn = Mn/Mrepeat, so 47,700 g/mol divided by 62 g/mol gives about 769 repeating units per chain when end-group contributions are neglected.}
    

### 2.9. Ion exchange and ion chromatography

128. {What is the principle of ion-exchange chromatography?} : {Ion-exchange chromatography separates charged analytes through reversible attraction to oppositely charged groups on the stationary phase.}
    
129. {How do anion and cation exchangers differ?} : {Anion exchangers contain positively charged groups that retain anions, whereas cation exchangers contain negatively charged groups that retain cations.}
    
130. {Which groups are used in strong and weak ion exchangers?} : {Common groups include quaternary ammonium for strong anion exchange, protonatable amines for weak anion exchange, sulfonate for strong cation exchange, and carboxylate for weak cation exchange.}
    
131. {What distinguishes strong and weak ion exchangers?} : {Strong exchangers remain charged over a broad pH range, whereas the charge of weak exchangers changes substantially with pH.}
    
132. {How do mobile-phase ions affect analyte retention in ion exchange?} : {Mobile-phase ions compete with analytes for exchange sites, so increasing their concentration generally reduces analyte retention.}
    
133. {How is gradient elution performed in ion exchange?} : {Ion-exchange gradients commonly increase competing-ion concentration or change pH to weaken analyte binding.}
    
134. {What is ion-exchange capacity?} : {Ion-exchange capacity is the amount of exchangeable charge on the stationary phase, commonly expressed as millimoles or equivalents per mass of material.}
    
135. {What is ion chromatography in the lecture’s context?} : {Ion chromatography is the separation of small ions by ion exchange, commonly followed by conductivity detection.}
    
136. {How does conductivity detection measure ions?} : {Conductivity detection measures changes in the electrical conductivity of the eluent caused by the ions passing through the detector.}
    
137. {Why can nonsuppressed conductivity detection have poor sensitivity?} : {A highly conductive eluent creates a large background, and an analyte may produce little change if its conductivity contribution resembles that of the displaced eluent ion.}
    
138. {What does a suppressor do in anion chromatography?} : {A suppressor lowers eluent conductivity while converting analyte salts into more strongly conducting acid forms.}
    
139. {How does suppression work with sodium hydroxide eluent?} : {Replacing sodium ions with hydrogen ions converts sodium hydroxide into water and sodium analyte salts into their corresponding acids.}
    
140. {How does suppression work with carbonate eluent?} : {Replacing sodium ions with hydrogen ions converts carbonate and bicarbonate into weakly conducting carbonic acid species while enhancing the response of many analyte anions.}
    
141. {How is a membrane suppressor regenerated electrolytically?} : {Water electrolysis continuously generates the ions needed to regenerate the suppressor, reducing the need for separately supplied regenerant solutions.}
    
142. {How can indirect UV detection be used in ion chromatography?} : {A UV-absorbing eluent ion produces a background signal that changes when a nonabsorbing analyte ion displaces it.}
    
143. {What is ion-exclusion chromatography?} : {Ion-exclusion chromatography separates substances partly through electrostatic exclusion of similarly charged ions from a resin’s pore liquid, while neutral or weakly ionized species can gain greater access.}
    

### 2.10. Ion pairing, affinity, chirality, and two-dimensional LC

144. {What is ion-pair chromatography?} : {Ion-pair chromatography improves retention of ionic analytes on reversed-phase materials by adding hydrophobic counterions to the mobile phase.}
    
145. {Which ion-pair reagents are used for anionic and cationic analytes?} : {Hydrophobic alkylammonium ions are commonly used for anions, while alkylsulfonate ions are commonly used for cations.}
    
146. {How can ion-pair retention be explained?} : {Retention can involve formation of hydrophobic ion pairs in solution or adsorption of the reagent onto the stationary phase followed by ion-exchange-like interactions.}
    
147. {What is affinity chromatography?} : {Affinity chromatography selectively retains analytes through specific biological recognition, such as antibody–antigen, receptor–ligand, or enzyme–ligand interactions.}
    
148. {How are analytes eluted from an affinity column?} : {Bound analytes are released by changing conditions such as pH, ionic strength, or temperature, or by adding a competing ligand.}
    
149. {Why do enantiomers require a chiral separation environment?} : {Enantiomers interact identically with an ideal achiral environment but can form differently stable diastereomeric interactions with a chiral selector.}
    
150. {How does a chiral stationary phase separate enantiomers?} : {A chiral stationary phase binds the two enantiomers differently, producing different retention times.}
    
151. {What is two-dimensional liquid chromatography?} : {Two-dimensional LC combines two separation mechanisms by transferring fractions from a first column to a second column for further separation.}
    
152. {How do heart-cutting and comprehensive two-dimensional LC differ?} : {Heart-cutting transfers selected fractions, whereas comprehensive two-dimensional LC repeatedly transfers fractions across the full first-dimension separation.}
    
153. {How do alternating loops support two-dimensional LC?} : {One loop collects first-column effluent while the contents of the other loop are transferred to the second column, after which their roles switch.}
    
154. {Why must second-dimension LC separations be fast?} : {The second-dimension separation must finish quickly enough to process incoming fractions without losing the separation achieved in the first dimension.}
    

### 2.11. Supercritical fluid chromatography

155. {What is supercritical fluid chromatography?} : {SFC uses a pressurized fluid, commonly carbon dioxide with an organic modifier, as the mobile phase under conditions near or above its critical region.}
    
156. {What are the approximate critical conditions of carbon dioxide?} : {Carbon dioxide becomes supercritical above approximately 31 °C and 74 bar.}
    
157. {Why can SFC operate efficiently at high velocity?} : {Its relatively low viscosity and favourable diffusion characteristics permit rapid mobile-phase flow with less mass-transfer broadening than is typical in liquid chromatography.}
    
158. {What are the main instrumental requirements for SFC?} : {SFC requires controlled delivery of pressurized carbon dioxide and modifiers, suitable column temperature control, and a backpressure regulator.}
    
159. {Why is SFC useful for preparative chromatography?} : {Depressurization removes most of the carbon dioxide as gas, simplifying analyte recovery and reducing the amount of liquid solvent requiring evaporation.}
    

## 3. Gas chromatography

### 3.1. Principles, columns, and carrier gases

160. {What is gas chromatography?} : {GC separates vaporized analytes using a gaseous mobile phase and a liquid-polymer or solid stationary phase.}
    
161. {Which analytes are suitable for GC?} : {Suitable analytes must be sufficiently volatile and thermally stable under injection and separation conditions, or be converted into suitable derivatives.}
    
162. {How do gas–liquid and gas–solid chromatography differ?} : {Gas–liquid chromatography relies mainly on partitioning into an immobilized liquid or polymer, whereas gas–solid chromatography relies mainly on adsorption onto a solid.}
    
163. {What is a WCOT column?} : {A wall-coated open-tubular column has a thin stationary-phase film on the inner wall of an otherwise open capillary.}
    
164. {What is a PLOT column?} : {A porous-layer open-tubular column has a porous solid layer on its inner wall and is especially useful for gases and very volatile compounds.}
    
165. {What dimensions are typical of capillary GC columns in the lecture?} : {The lecture describes fused-silica columns approximately 10–100 m long, with internal diameters around 0.10–0.53 mm and stationary-phase films around 0.1–5 µm.}
    
166. {Why does a small capillary diameter improve efficiency?} : {A small diameter shortens radial diffusion distances between the mobile phase and stationary phase, reducing mass-transfer broadening.}
    
167. {How does stationary-phase film thickness affect retention and capacity?} : {A thicker film increases stationary-phase volume, retention, and sample capacity, but also increases the distance over which analytes must diffuse.}
    
168. {What is the tradeoff between narrow thin-film columns and wider thick-film columns?} : {Narrow thin-film columns favour efficiency and speed, whereas wider thick-film columns accommodate larger sample amounts and retain very volatile analytes more effectively.}
    
169. {Which carrier gases are used in GC?} : {Common carrier gases are helium, hydrogen, and nitrogen, selected according to efficiency, operating velocity, detector compatibility, and practical requirements.}
    
170. {How do carrier gases differ in their useful velocity ranges?} : {Hydrogen generally maintains efficiency across a broad high-velocity range, helium provides an intermediate range, and nitrogen has a narrower optimum at lower velocity.}
    
171. {Why are carrier-gas purification systems used?} : {Purification systems remove water, oxygen, and hydrocarbons that can damage stationary phases, increase background, or interfere with detection.}
    
172. {Which materials remove common carrier-gas impurities?} : {Molecular sieves remove water, carbon-based traps remove hydrocarbons, and suitable metal-containing traps remove oxygen.}
    

### 3.2. Temperature and stationary phases

173. {Why does temperature strongly affect GC retention?} : {Temperature changes analyte vapour pressure and phase distribution, with higher temperatures generally decreasing retention.}
    
174. {Why is temperature programming useful?} : {Temperature programming preserves separation of early volatile compounds at low temperature and then accelerates elution of less volatile compounds by heating the column.}
    
175. {What problems arise from using a single low temperature?} : {A low constant temperature can give good separation of volatile compounds but excessively long retention and broad peaks for less volatile compounds.}
    
176. {What problems arise from using a single high temperature?} : {A high constant temperature can elute less volatile compounds quickly but provide insufficient retention and separation for the most volatile components.}
    
177. {Which liquid-polymer stationary phases are used in GC?} : {Common phases include methyl polysiloxanes, phenyl- or cyanopropyl-containing polysiloxanes, polyethylene glycol, and specialized ionic-liquid phases.}
    
178. {How does stationary-phase polarity influence GC selectivity?} : {Increasing phase polarity strengthens interactions with suitably polar analytes and changes their retention relative to less polar compounds.}
    
179. {Which solid phases are used in PLOT columns?} : {Solid phases include alumina, silica, porous organic polymers, molecular sieves, and graphitized carbon.}
    
180. {Why are molecular-sieve GC columns useful?} : {Molecular-sieve columns separate small gases such as hydrogen, oxygen, nitrogen, methane, and carbon monoxide through selective adsorption.}
    

### 3.3. Injection methods and sample introduction

181. {What is the function of a split/splitless injector?} : {A split/splitless injector vaporizes a liquid sample and controls the fraction of vapour carried onto the capillary column.}
    
182. {How does split injection work?} : {Split injection keeps the split outlet open so that most vaporized sample leaves the injector and only a small fraction enters the column.}
    
183. {When is split injection useful?} : {Split injection is useful for relatively concentrated samples because it prevents overload and introduces a narrow sample band.}
    
184. {What is discrimination in split injection?} : {Discrimination occurs when compounds are transferred to the column in unequal proportions because of differences in vaporization, transport, or interactions in the injector.}
    
185. {How does splitless injection work?} : {Splitless injection initially closes the split outlet to transfer much more of the sample onto the column, then opens it to remove remaining solvent vapour and clear the injector.}
    
186. {Why is splitless injection useful for trace analysis?} : {Splitless injection increases the analyte amount entering the column, improving detection of low-concentration components.}
    
187. {Why is focusing needed during splitless injection?} : {The relatively slow transfer creates a broad initial band that must be concentrated at the column entrance to preserve separation efficiency.}
    
188. {What is solvent trapping?} : {Solvent trapping focuses analytes in a condensed solvent film near the column entrance before heating releases them into the separation.}
    
189. {What is cold trapping?} : {Cold trapping focuses analytes at a sufficiently cool column entrance by strongly retaining or condensing them until the temperature rises.}
    
190. {What is a retention gap?} : {A retention gap is a deactivated uncoated capillary placed before the analytical column to assist sample focusing and protect the stationary phase.}
    
191. {What is programmed-temperature vaporization injection?} : {PTV injection introduces the sample into a temperature-controlled inlet and uses programmed heating to remove solvent and transfer analytes to the column.}
    
192. {What advantages can PTV injection provide?} : {With suitable conditions, PTV injection can reduce discrimination and thermal stress, permit larger sample volumes, and improve trace analysis by selectively venting solvent.}
    
193. {What limitations does PTV injection have?} : {PTV injection requires additional equipment and careful adjustment because solvent venting or inappropriate temperature settings can cause analyte losses.}
    
194. {How does cold on-column injection work?} : {Cold on-column injection places the liquid sample directly into the column at a low starting temperature, reducing exposure to a hot vaporizing inlet.}
    
195. {What is static headspace analysis?} : {Static headspace analysis samples the gas above a sample after controlled equilibration, with the gas-phase analyte concentration related to its concentration and partitioning in the sample.}
    
196. {Why must headspace conditions be controlled?} : {Temperature, equilibration time, sample composition, and phase volumes affect partitioning and therefore the amount of analyte measured.}
    
197. {What is dynamic headspace analysis?} : {Dynamic headspace analysis sweeps volatile analytes from the headspace into a trap, concentrates them, and thermally releases them for GC analysis.}
    
198. {What is solid-phase microextraction?} : {SPME extracts analytes onto a coated fibre exposed to the sample liquid or headspace, after which the fibre is inserted into the GC inlet for thermal desorption.}
    
199. {Why is fibre coating important in SPME?} : {The coating controls extraction selectivity and capacity through its interactions with the analytes, with PDMS providing a common hydrophobic extraction phase.}
    
200. {How does thermal-desorption analysis work?} : {Thermal desorption heats a sample or loaded sorbent tube under carrier gas and transfers released analytes through a focusing trap onto the GC column.}
    
201. {How can thermal desorption be used for air analysis?} : {A measured air volume is drawn through a sorbent tube to collect volatile organic compounds, which are later thermally desorbed for GC analysis.}
    
202. {What is purge-and-trap analysis?} : {Purge-and-trap analysis bubbles inert gas through a liquid to remove volatile analytes, captures them on a sorbent, and thermally desorbs them into the GC system.}
    
203. {What is pyrolysis GC?} : {Pyrolysis GC thermally decomposes nonvolatile materials under controlled conditions and separates the resulting volatile products to obtain information about the original material.}
    
204. {Why is pyrolysis GC-MS useful for polymers and microplastics?} : {Their characteristic decomposition products provide chemical fingerprints that help identify polymer types.}
    

### 3.4. GC detectors

205. {How does a flame-ionization detector work?} : {An FID burns the column effluent in a hydrogen–air flame and measures the current generated by ions formed from suitable organic compounds.}
    
206. {What are the main strengths of FID detection?} : {FID provides high sensitivity for many organic compounds, a wide linear range, and a response broadly related to combustible carbon entering the detector.}
    
207. {What are the main limitations of FID detection?} : {FID destroys the sample and responds poorly or negligibly to many permanent gases and highly oxidized inorganic carbon compounds.}
    
208. {How does an electron-capture detector work?} : {An ECD generates a background electron current and measures its decrease when electron-capturing analytes remove free electrons.}
    
209. {Which analytes are especially suitable for ECD detection?} : {ECD is particularly sensitive to strongly electron-capturing compounds such as many halogenated substances.}
    
210. {How does pulsed ECD operation produce a signal?} : {The instrument adjusts pulse frequency to maintain a controlled current, and the required frequency changes with the concentration of electron-capturing analytes.}
    
211. {How does a thermal-conductivity detector work?} : {A TCD detects changes in heat loss from heated filaments when the thermal conductivity of the column effluent differs from that of pure carrier gas.}
    
212. {Why is a TCD useful for gas analysis?} : {A TCD can detect many compounds, including permanent gases that produce little or no FID response.}
    
213. {Which additional spectroscopic GC detectors are mentioned?} : {The lecture mentions flame-photometric detection for sulfur and phosphorus, chemiluminescence detection, atomic-emission detection, and infrared absorption detection.}
    

### 3.5. Two-dimensional GC

214. {What is comprehensive two-dimensional GC?} : {GC×GC repeatedly transfers fractions from a first column into a second column with different selectivity, providing two retention coordinates for each analyte.}
    
215. {Why are nonpolar and polar columns often combined?} : {Combining different polarities provides complementary separation mechanisms and can resolve compounds that overlap in one dimension.}
    
216. {What does a cryogenic modulator do?} : {A cryogenic modulator traps and focuses first-column effluent with cold jets and then releases narrow bands with hot jets into the second column.}
    
217. {Why is the second GC×GC column usually shorter?} : {The second column must complete each separation within the modulation interval while the next fraction is being collected.}
    
218. {How is a GC×GC chromatogram reconstructed?} : {The repeated second-dimension chromatograms are arranged according to first-dimension retention time to create a two-dimensional signal map.}
    
219. {Why can one compound appear in several modulation slices?} : {A first-dimension peak can span several collection intervals, causing portions of the same compound to enter successive second-dimension separations.}
    

## 4. Electrophoresis

### 4.1. Principles and CZE instrumentation

220. {What is electrophoresis?} : {Electrophoresis separates charged analytes through differences in their migration velocities in an electric field.}
    
221. {How do free-solution and supported electrophoresis differ?} : {Free-solution electrophoresis occurs in a liquid electrolyte, whereas supported electrophoresis uses a gel or similar matrix that suppresses convection and may provide molecular sieving.}
    
222. {What are the main components of a CZE instrument?} : {A CZE instrument contains electrolyte reservoirs, sample vials, a fused-silica capillary, a high-voltage supply, temperature control, and a detector.}
    
223. {What capillary dimensions are described in the lecture?} : {The lecture describes capillaries approximately 30–100 cm long and 25–100 µm in internal diameter, usually protected by an external polyimide coating.}
    
224. {Why are narrow capillaries advantageous?} : {Narrow capillaries dissipate heat efficiently and suppress convection, allowing high electric fields and efficient separations.}
    
225. {What is chip electrophoresis?} : {Chip electrophoresis performs separations in miniature channels fabricated on a small device, reducing sample volumes and often shortening analysis time.}
    

### 4.2. Electrophoretic mobility and electroosmotic flow

226. {What determines electrophoretic velocity?} : {Electrophoretic velocity follows vep = µepE, where µep is electrophoretic mobility and E is electric-field strength.}
    
227. {How is electric-field strength calculated?} : {For an approximately uniform field, E = V/Lt, where V is applied voltage and Lt is total capillary length.}
    
228. {How does the simple spherical-ion model describe mobility?} : {Balancing electrical force with Stokes friction gives µep = ze/(6πηr), showing that mobility depends on charge, viscosity, and effective ion radius.}
    
229. {How does ion charge affect migration?} : {A greater charge magnitude generally increases electrophoretic mobility when size and solution conditions are comparable, while charge sign determines migration direction.}
    
230. {What is electroosmotic flow?} : {EOF is bulk liquid movement caused by an electric field acting on mobile ions in the electrical double layer near a charged capillary wall.}
    
231. {Why does bare fused silica usually produce EOF toward the cathode?} : {Deprotonated silanol groups create a negatively charged wall whose nearby mobile cations migrate toward the cathode and drag the liquid with them.}
    
232. {How does pH influence EOF?} : {Increasing pH generally increases silica-surface deprotonation and strengthens cathodic EOF, while low pH reduces the wall charge and weakens EOF.}
    
233. {How does electroosmotic mobility depend on solution properties?} : {Its magnitude is approximately proportional to permittivity and zeta potential and inversely proportional to viscosity.}
    
234. {Why does EOF usually cause less flow-related broadening than pressure-driven flow?} : {EOF has an approximately plug-like velocity profile, whereas pressure-driven flow has a parabolic profile with different velocities across the capillary.}
    
235. {Does EOF necessarily produce triangular peaks?} : {EOF does not necessarily produce triangular peaks, because actual peak shape also depends on diffusion, injection, adsorption, and electrolyte conditions.}
    
236. {How can EOF be modified?} : {EOF can be altered by changing pH, ionic strength, solvent composition, wall coatings, or electrolyte additives.}
    
237. {How can a cationic surfactant reverse EOF?} : {Adsorption of a cationic surfactant can reverse the effective wall charge, causing the electroosmotic liquid movement to reverse direction.}
    
238. {What is apparent analyte mobility?} : {Apparent mobility is µapp = µep + µeo, using signed mobilities to account for electrophoretic motion and bulk electroosmotic transport.}
    
239. {How is apparent mobility calculated from migration time?} : {Apparent mobility is µapp = LdLt/(Vt), where Ld is the distance to the detector, Lt is total capillary length, V is voltage, and t is migration time under the chosen sign convention.}
    
240. {In what order can cations, neutrals, and anions reach a cathodic detector?} : {With sufficiently strong cathodic EOF, cations generally arrive before neutral EOF markers, followed by anions whose electrophoretic motion opposes EOF.}
    
241. {Why are neutral compounds not separated by ordinary CZE?} : {Neutral compounds have no electrophoretic mobility and therefore travel together with the EOF unless an additional separation mechanism is introduced.}
    

### 4.3. Injection, detection, and selectivity

242. {How does pressure injection work in CZE?} : {Pressure injection introduces a small sample volume by applying a pressure difference across the capillary for a controlled time.}
    
243. {How does electrokinetic injection work?} : {Electrokinetic injection applies voltage while the inlet is in the sample, allowing electrophoretic migration and EOF to introduce analytes.}
    
244. {Why can electrokinetic injection bias sample composition?} : {Analytes with different mobilities and charge states enter at different rates, so the injected mixture may not preserve the composition of the original sample.}
    
245. {How can electrokinetic injection enrich an analyte?} : {Appropriate voltage, polarity, and electrolyte conditions can preferentially introduce selected ions and increase their amount in the capillary.}
    
246. {Which detectors are used in capillary electrophoresis?} : {Common detectors include UV absorbance, fluorescence, conductivity, and mass spectrometry.}
    
247. {How does direct UV detection work in CZE?} : {Direct UV detection measures the absorbance of analytes in an otherwise sufficiently transparent background electrolyte.}
    
248. {How does indirect UV detection work in CZE?} : {Indirect UV detection uses an absorbing background electrolyte and measures the signal change when a nonabsorbing analyte displaces absorbing ions.}
    
249. {Why can indirect UV peaks appear negative?} : {A nonabsorbing analyte can reduce background absorbance as it passes the detector, producing a downward peak that software may invert for display.}
    
250. {How can CZE selectivity be optimized?} : {Selectivity can be changed through pH-dependent analyte ionization or addition of complexing agents that alter effective charge, size, and mobility.}
    
251. {How are enantiomers separated by CZE?} : {Chiral selectors such as cyclodextrins form differently stable complexes with enantiomers, producing different effective mobilities.}
    
252. {Why do cyclodextrin derivatives give different chiral selectivities?} : {Changes in cavity size, substituents, and selector charge alter binding and the mobility of the resulting analyte–selector complexes.}
    
253. {Which other capillary-electrophoresis modes are listed?} : {The lecture lists micellar electrokinetic chromatography, microemulsion electrokinetic chromatography, capillary electrochromatography, and isotachophoresis without developing them in detail.}
    

### 4.4. Gel electrophoresis and isoelectric focusing

254. {What is capillary gel electrophoresis?} : {CGE uses a sieving matrix inside a capillary to separate analytes according to their movement through the matrix, often with size as the main distinguishing property.}
    
255. {Why is a sieving matrix needed for DNA size separation?} : {DNA fragments have similar charge-to-mass ratios, so a matrix is needed to produce size-dependent differences in migration.}
    
256. {How does SDS enable protein size separation?} : {SDS denatures proteins and gives them an approximately uniform negative charge-to-mass ratio, allowing gel sieving to separate them mainly by size.}
    
257. {What is isoelectric focusing?} : {IEF separates amphoteric analytes in a pH gradient by allowing each to migrate until it reaches the pH corresponding to its isoelectric point.}
    
258. {What is the isoelectric point pI?} : {The pI is the pH at which an analyte has zero net charge under the specified conditions.}
    
259. {Why does IEF concentrate proteins into narrow zones?} : {A protein displaced from its pI acquires a charge that drives it back toward its pI position, producing a focusing effect.}
    
260. {What roles do ampholytes play in IEF?} : {Ampholytes establish and stabilize a pH gradient when subjected to an electric field.}
    
261. {Which supports are used in slab electrophoresis?} : {Common anticonvective supports include polyacrylamide, agarose, and cellulose acetate.}
    
262. {What is two-dimensional protein electrophoresis?} : {Two-dimensional protein electrophoresis separates proteins first by pI using IEF and then by size using SDS-PAGE.}
    
263. {Is SDS-PAGE alone a two-dimensional method?} : {SDS-PAGE alone is normally a one-dimensional size separation and becomes part of a two-dimensional method when combined with a separate first dimension such as IEF.}
    
264. {What is Western blotting?} : {Western blotting transfers separated proteins from a gel to a membrane and detects selected proteins using specific antibodies, often with labelled secondary antibodies.}
    

## 5. Infrared spectroscopy

### 5.1. General spectroscopy and IR regions

265. {What relationship connects photon energy, frequency, wavelength, and wavenumber?} : {Photon energy follows E = hν = hc/λ = hcṽ, where h is Planck’s constant, ν is frequency, λ is wavelength, and ṽ is wavenumber.}
    
266. {How do wavelength and wavenumber relate?} : {Wavenumber is the reciprocal of wavelength, so ṽ in cm⁻¹ equals 1/λ when wavelength is expressed in centimetres.}
    
267. {Which molecular processes are associated with different spectral regions?} : {Radiofrequency radiation can probe nuclear-spin transitions, microwaves probe rotations, IR probes vibrations, UV-visible radiation probes electronic transitions, and higher-energy radiation probes core-electron or nuclear processes.}
    
268. {How do absorption and emission spectroscopy differ?} : {Absorption spectroscopy measures radiation removed by a sample, whereas emission spectroscopy measures radiation produced when excited species relax.}
    
269. {Which other optical measurement principles are mentioned?} : {The lecture also mentions scattering, diffraction, reflection, refraction, and changes in polarization.}
    
270. {What is the basis of infrared spectroscopy?} : {IR spectroscopy measures absorption associated with molecular vibrational transitions and, where resolved, accompanying rotational transitions.}
    
271. {What IR regions are defined in the lecture?} : {The lecture divides IR into NIR at approximately 14,000–4,000 cm⁻¹, MIR at 4,000–200 cm⁻¹, and FIR at 200–20 cm⁻¹, although boundary conventions vary.}
    
272. {Why is the mid-infrared region especially useful for structural analysis?} : {MIR contains many fundamental molecular vibrations whose positions and intensities provide information about functional groups and molecular structure.}
    

### 5.2. IR instrumentation

273. {How does a dispersive IR instrument work?} : {A dispersive instrument uses a wavelength-selecting element such as a grating to measure successive parts of the IR spectrum.}
    
274. {What is the benefit of a dual-beam dispersive arrangement?} : {A dual-beam arrangement compares sample and reference paths to compensate for background contributions such as solvent absorption.}
    
275. {What limitations of dispersive IR instruments are described?} : {The lecture highlights slow spectral acquisition, reduced light throughput from slits, and variation in resolution across the measured range.}
    
276. {Which radiation sources are used for MIR spectroscopy?} : {MIR sources include the silicon-carbide Globar and the Nernst glower made from zirconia and other metal oxides.}
    
277. {Which sources are used for NIR spectroscopy?} : {NIR instruments commonly use tungsten or quartz-halogen lamps.}
    
278. {What is the main optical component of an FTIR instrument?} : {An FTIR instrument uses an interferometer, commonly a Michelson interferometer, to encode spectral information into an interferogram.}
    
279. {How does a Michelson interferometer work?} : {A beam splitter directs light toward fixed and moving mirrors and recombines the returning beams, producing interference that changes with optical path difference.}
    
280. {Why does mirror movement change interference?} : {Moving one mirror changes its round-trip optical path by twice the mirror displacement, changing the phase difference between the returning beams.}
    
281. {What is an interferogram?} : {An interferogram is the recorded intensity as a function of optical path difference and contains contributions from all measured wavelengths.}
    
282. {How is an FTIR spectrum obtained from an interferogram?} : {A Fourier transform converts the interferogram into a spectrum of intensity against frequency or wavenumber.}
    
283. {What determines FTIR spectral resolution?} : {Spectral resolution is mainly determined by the maximum measured optical path difference, with a longer scan permitting finer resolution.}
    
284. {What is apodization?} : {Apodization applies a weighting function to the finite interferogram to reduce truncation-related side lobes, usually at some cost to resolution.}
    
285. {Why can FTIR improve signal-to-noise ratio through averaging?} : {Rapid repeated scans can be accumulated, reducing random noise approximately in proportion to the square root of the number of independent scans.}
    
286. {Why are background and sample measurements needed in single-beam FTIR?} : {Separate background and sample measurements allow correction for the source, instrument response, atmosphere, and other contributions not belonging to the sample.}
    
287. {What is a DTGS detector?} : {A deuterated triglycine sulfate detector is a pyroelectric detector that responds to changes in absorbed radiation and can operate near room temperature.}
    
288. {Why are cooled semiconductor IR detectors used?} : {Detectors such as cooled mercury cadmium telluride provide high sensitivity, while cooling reduces thermal noise.}
    
289. {Why must detector material match the spectral range?} : {Different materials have different wavelength responses, so detector choice determines which spectral region can be measured effectively.}
    

### 5.3. Harmonic and anharmonic vibrations

290. {How is a diatomic vibration modelled as a harmonic oscillator?} : {The two atoms are treated as masses connected by a spring whose restoring force is proportional to displacement from equilibrium.}
    
291. {What is the reduced mass of a diatomic molecule?} : {Reduced mass is µ = m1m2/(m1 + m2), which replaces the two-body motion with an equivalent single-mass oscillator.}
    
292. {What is Hooke’s law for the harmonic oscillator?} : {Hooke’s law is F = −κx, where κ is the force constant and x is displacement from equilibrium.}
    
293. {What is the harmonic oscillator’s potential energy?} : {Its potential energy is V(x) = ½κx², producing a parabolic potential-energy curve.}
    
294. {What determines vibrational frequency?} : {The harmonic frequency is ν = (1/2π)√(κ/µ), so stronger bonds and lower reduced masses produce higher frequencies.}
    
295. {How is vibrational wavenumber expressed?} : {Vibrational wavenumber is ṽ = (1/2πc)√(κ/µ), connecting IR band position to bond strength and atomic masses.}
    
296. {What are the quantized harmonic vibrational energies?} : {The permitted energies are Ev = hν(v + ½), where v is a nonnegative integer vibrational quantum number.}
    
297. {What is zero-point energy?} : {Zero-point energy is the ground-state vibrational energy ½hν, meaning that the molecule retains vibrational energy even at its lowest allowed level.}
    
298. {What is the harmonic vibrational selection rule?} : {For the ideal harmonic model, allowed vibrational transitions have Δv = ±1.}
    
299. {Why is the anharmonic oscillator more realistic?} : {Anharmonicity accounts for unequal level spacing, asymmetric bond stretching, and eventual bond dissociation.}
    
300. {How does anharmonicity change vibrational level spacing?} : {Energy levels become progressively closer together as vibrational excitation increases toward dissociation.}
    
301. {Why are overtones observed?} : {Anharmonicity permits weak transitions with Δv greater than one, producing overtones at frequencies somewhat below exact integer multiples of the fundamental.}
    
302. {What are combination bands?} : {Combination bands arise when a transition excites more than one vibrational mode simultaneously.}
    
303. {Why are overtones and combination bands important in NIR?} : {These transitions account for many NIR absorptions, particularly those involving O–H, N–H, and C–H bonds.}
    
304. {How does isotopic substitution affect a vibration?} : {Replacing an atom with a heavier isotope increases reduced mass and lowers the vibrational frequency, explaining the lower frequency of C–D relative to C–H stretching.}
    

### 5.4. Rotations and specific vibrations

305. {What is the rigid-rotor model?} : {The rigid-rotor model treats a diatomic molecule as two masses rotating at a fixed internuclear distance.}
    
306. {What is the moment of inertia of a diatomic rigid rotor?} : {The moment of inertia is I = µre², where µ is reduced mass and re is equilibrium bond length.}
    
307. {What are the rigid-rotor energy levels?} : {Rotational energy follows EJ = hcBJ(J + 1), where J is the rotational quantum number and B = h/(8π²cI).}
    
308. {What is the pure rotational selection rule?} : {For electric-dipole rotational transitions in the simple diatomic model, ΔJ = ±1 and the molecule must have a permanent dipole moment.}
    
309. {Why are pure rotational lines equally spaced in the rigid-rotor approximation?} : {Their wavenumbers follow 2B(J + 1), giving a constant spacing of 2B.}
    
310. {Why is rotational structure more visible in gas-phase IR spectra?} : {Gas-phase molecules rotate more freely, whereas interactions in liquids and solids broaden and obscure individual rotational transitions.}
    
311. {What are the P and R branches of a simple rovibrational spectrum?} : {The P branch contains transitions with ΔJ = −1 and the R branch contains transitions with ΔJ = +1 around the vibrational transition.}
    
312. {What makes a vibration IR-active?} : {A vibration is IR-active when it changes the molecular dipole moment during the motion.}
    
313. {What is the difference between stretching and bending vibrations?} : {Stretching changes bond lengths, while bending changes bond angles or the orientation of groups.}
    
314. {How do symmetric and antisymmetric stretching differ?} : {Symmetric stretching moves related bonds in phase, whereas antisymmetric stretching lengthens one bond while another shortens.}
    
315. {Which bending motions are illustrated for CH2 groups?} : {The illustrated bending motions are scissoring, rocking, wagging, and twisting.}
    
316. {How does bond order affect stretching frequency?} : {Higher bond order generally increases the force constant, so comparable triple bonds absorb at higher wavenumber than double bonds and single bonds.}
    

### 5.5. Sampling and interpretation

317. {How are solid samples measured by transmission IR?} : {A finely divided solid can be mixed with an IR-transparent material such as dry KBr and pressed into a pellet for transmission measurement.}
    
318. {How can liquids be measured by transmission IR?} : {Liquids can be measured as thin films or as solutions in suitable solvents using cells with IR-transparent windows.}
    
319. {How are gases measured by IR spectroscopy?} : {Gases are measured in gas cells with suitable windows and path lengths, sometimes with heating to maintain vapour-phase samples.}
    
320. {What is attenuated total reflection spectroscopy?} : {ATR measures sample absorption through an evanescent field created when IR radiation undergoes total internal reflection inside a high-refractive-index crystal.}
    
321. {Which ATR crystal materials are mentioned?} : {The lecture mentions diamond and zinc selenide crystals.}
    
322. {What determines ATR penetration depth?} : {Penetration depth depends on wavelength, incidence angle, and the refractive indices of the crystal and sample, generally increasing at longer wavelength.}
    
323. {Why is good sample contact important in ATR?} : {The sample must contact the crystal closely because the evanescent field extends only a short distance beyond its surface.}
    
324. {What is the main practical advantage of ATR?} : {ATR allows many solids, liquids, and irregular samples to be analysed with little preparation.}
    
325. {How do diffuse and specular reflection differ?} : {Diffuse reflection collects radiation scattered from rough or powdered samples, while specular reflection measures mirror-like reflection from smoother surfaces.}
    
326. {How are transmittance and absorbance related?} : {Transmittance is T = I/I0 and absorbance is A = −log10T, so stronger absorption produces a transmission minimum and an absorbance maximum.}
    
327. {What is the fingerprint region?} : {The fingerprint region, commonly below approximately 1,500 cm⁻¹, contains a complex pattern of vibrations useful for comparing molecular identities.}
    
328. {How are functional-group bands used in IR interpretation?} : {Characteristic bands support identification of groups such as O–H, N–H, C–H, carbonyl, and nitrile, but assignments should be checked against the full spectrum.}
    
329. {Why are NIR spectra often interpreted using chemometrics?} : {Their overlapping overtone and combination bands are difficult to assign individually, so multivariate methods extract useful identification or concentration information.}
    
330. {How can NIR be used quantitatively?} : {NIR quantitation uses spectra from samples of known composition to build a calibration model that predicts concentrations in comparable unknown samples.}
    
331. {What applications distinguish MIR and NIR in the lecture?} : {MIR is emphasized for functional-group and structural analysis, whereas NIR is emphasized for identification, quantitative analysis, and online process monitoring.}
    

## 6. Raman spectroscopy

### 6.1. Scattering principles

332. {What is Raman spectroscopy?} : {Raman spectroscopy measures inelastically scattered light whose energy shifts reveal molecular vibrational transitions.}
    
333. {How does Rayleigh scattering differ from Raman scattering?} : {Rayleigh scattering preserves photon energy, whereas Raman scattering changes photon energy through exchange with molecular motion.}
    
334. {What is Stokes Raman scattering?} : {Stokes scattering occurs when the molecule gains vibrational energy and the scattered photon has lower energy than the incident photon.}
    
335. {What is anti-Stokes Raman scattering?} : {Anti-Stokes scattering occurs when an initially excited molecule loses vibrational energy and the scattered photon has higher energy than the incident photon.}
    
336. {Why are Stokes signals usually stronger than anti-Stokes signals?} : {At ordinary temperatures, more molecules occupy the vibrational ground state than excited vibrational states.}
    
337. {What is Raman shift?} : {Raman shift is the difference between incident and scattered wavenumbers and represents the energy exchanged with the molecular vibration.}
    
338. {What makes a vibration Raman-active?} : {A vibration is Raman-active when it changes molecular polarizability during the motion.}
    
339. {Why are IR and Raman complementary?} : {IR intensity depends on changes in dipole moment, whereas Raman intensity depends on changes in polarizability, so the two techniques emphasize different vibrations.}
    
340. {Does Raman activity require that the dipole moment remain unchanged?} : {Raman activity requires a polarizability change, and a vibration can be both Raman-active and IR-active if it also changes the dipole moment.}
    

### 6.2. Instrumentation and measurement

341. {What are the main components of a Raman spectrometer?} : {A Raman spectrometer contains an excitation source, focusing and collection optics, filters to reject intense elastic scattering, a wavelength-separating element, and a detector.}
    
342. {Why are lasers useful as Raman sources?} : {Lasers provide intense narrow-band excitation needed to detect the very weak Raman-scattering signal.}
    
343. {Which Raman sources are listed in the lecture?} : {The lecture lists mercury-vapour excitation, an argon laser around 488 nm, and a Nd:YAG laser around 1,064 nm.}
    
344. {Which detectors are mentioned for Raman spectroscopy?} : {The lecture mentions silicon and indium gallium arsenide detectors, selected according to the wavelength range.}
    
345. {Why must Rayleigh-scattered light be removed?} : {Rayleigh scattering is much stronger than Raman scattering and can overwhelm the detector unless suitable filters reject it.}
    
346. {What common effect can interfere with Raman spectra?} : {Sample fluorescence can produce a strong background that obscures the weaker Raman bands.}
    

## 7. Mass spectrometry

### 7.1. Basic concepts and ionization

347. {What does mass spectrometry measure?} : {Mass spectrometry measures ions according to their mass-to-charge ratio m/z and records their relative abundance.}
    
348. {What are the main components of a mass spectrometer?} : {A mass spectrometer contains a sample-introduction system, an ion source, ion optics, a mass analyser, a detector, and a vacuum system.}
    
349. {Why must analytes be ionized?} : {Mass analysers manipulate charged particles using electric or magnetic fields, so neutral analytes must first be converted into ions.}
    
350. {What are the main applications of mass spectrometry?} : {Applications include molecular identification, structural analysis, quantitative determination, protein characterization, and detection after chromatographic or electrophoretic separation.}
    
351. {How do hard and soft ionization differ?} : {Hard ionization commonly produces extensive fragmentation, whereas soft ionization tends to preserve more intact molecular or quasi-molecular ions.}
    
352. {What is the difference between a molecular ion and a protonated molecule?} : {A molecular radical cation M⁺• results from electron removal, whereas a protonated molecule [M + H]⁺ results from addition of a proton.}
    

### 7.2. Electron and chemical ionization

353. {How does electron ionization work?} : {EI bombards gas-phase molecules with energetic electrons, removing an electron to form molecular radical cations that may fragment.}
    
354. {Which analytes are suited to EI?} : {EI is particularly suited to relatively small compounds that can be vaporized without unacceptable decomposition.}
    
355. {Why is EI fragmentation analytically useful?} : {Reproducible fragment patterns provide structural information and support comparison with spectral libraries.}
    
356. {Why are many EI library spectra recorded at 70 eV?} : {Using a standard electron energy of 70 eV improves comparability of fragmentation patterns across instruments and library measurements.}
    
357. {What is a limitation of EI for molecular-mass determination?} : {Extensive fragmentation can make the molecular-ion signal weak or absent, complicating determination of the intact molecule’s mass.}
    
358. {How does chemical ionization work?} : {CI first ionizes an excess reagent gas, whose ions then react with analyte molecules through processes such as proton transfer.}
    
359. {Which reagent gases are commonly used for CI?} : {Common reagent gases include methane, isobutane, and ammonia.}
    
360. {Why is CI considered softer than EI?} : {CI often transfers less excess energy to analytes and produces stronger quasi-molecular ions such as [M + H]⁺ with less fragmentation.}
    
361. {What sample limitation do EI and CI share?} : {Both normally require gas-phase analytes, so volatility and thermal stability constrain their use.}
    

### 7.3. Atmospheric-pressure ionization

362. {Why are atmospheric-pressure sources useful for LC-MS?} : {They convert analytes arriving in liquid effluent into gas-phase ions while allowing most solvent and gas to be removed before the ions enter high vacuum.}
    
363. {How does electrospray ionization work?} : {ESI applies high voltage to a liquid at a spray tip, producing charged droplets that lose solvent and ultimately release analyte ions.}
    
364. {Why is nebulizing gas used in many ESI interfaces?} : {At ordinary LC flow rates, nebulizing gas helps form and disperse droplets, whereas very low-flow nanospray can operate with less gas assistance.}
    
365. {What is the Rayleigh limit in ESI?} : {The Rayleigh limit is the maximum charge a droplet can support before electrostatic repulsion overcomes surface tension and causes droplet fission.}
    
366. {Why does solvent evaporation encourage droplet fission?} : {Evaporation reduces droplet radius and increases charge density, bringing the droplet closer to its stability limit.}
    
367. {What is the charged-residue model?} : {The charged-residue model describes ion formation when a small charged droplet loses its remaining solvent and leaves a charged analyte behind.}
    
368. {What is the ion-evaporation model?} : {The ion-evaporation model describes direct emission of ions from highly charged droplet surfaces under a strong electric field.}
    
369. {Why is ESI useful for proteins and other large biomolecules?} : {ESI can ionize nonvolatile biomolecules from solution and produce multiple charges that bring high molecular masses into an accessible m/z range.}
    
370. {How does atmospheric-pressure chemical ionization work?} : {APCI nebulizes and vaporizes the LC effluent, uses a corona discharge to generate reagent ions, and ionizes analytes through gas-phase reactions.}
    
371. {How does APCI differ from ESI?} : {APCI relies on vaporization and gas-phase ion chemistry and commonly forms singly charged ions, while ESI is particularly suited to polar and readily charged molecules in solution.}
    
372. {What is atmospheric-pressure photoionization?} : {APPI uses photons to initiate gas-phase ionization, directly or through a dopant, and can be useful for relatively nonpolar compounds.}
    

### 7.4. MALDI and source selection

373. {How does MALDI work?} : {MALDI embeds analytes in an absorbing matrix and uses laser pulses to desorb material and generate analyte ions with relatively limited fragmentation.}
    
374. {What is the role of the MALDI matrix?} : {The matrix absorbs laser energy, assists desorption, and supports ion-forming reactions while limiting direct damage to analytes.}
    
375. {How do charge states commonly differ between MALDI and ESI?} : {MALDI commonly produces mainly singly charged ions, whereas ESI often produces multiple charge states for large biomolecules.}
    
376. {Which analytes are commonly measured by MALDI?} : {MALDI is widely used for peptides, proteins, nucleic-acid-related compounds, and other large molecules with suitable matrices.}
    
377. {What is MALDI imaging?} : {MALDI imaging records spectra at successive surface positions and maps selected m/z signals to show the spatial distribution of analytes.}
    
378. {How should an ionization method be selected?} : {Selection considers analyte polarity, volatility, thermal stability, molecular size, required fragmentation, and compatibility with the sample-introduction method.}
    
379. {How should the ion-source mass ranges shown in the lecture be interpreted?} : {The listed ranges illustrate typical applications and should not be treated as universal limits because performance depends on the source, analyser, and sample.}
    

### 7.5. Mass-analyser performance and quadrupoles

380. {What is mass resolving power?} : {Resolving power is R = m/Δm, where Δm is defined using a stated peak-width or separation criterion.}
    
381. {What is mass accuracy?} : {Mass accuracy describes how closely the measured m/z agrees with the correct or theoretical value.}
    
382. {How is mass error expressed in ppm?} : {Mass error is [(measured m/z − theoretical m/z)/(theoretical m/z)] × 10⁶.}
    
383. {How do resolving power and mass accuracy differ?} : {Resolving power describes separation of nearby signals, while mass accuracy describes agreement between a measured signal position and its correct value.}
    
384. {How does a quadrupole mass analyser work?} : {A quadrupole applies radiofrequency and direct-current voltages to four rods so that only ions in a selected m/z interval have stable trajectories through the device.}
    
385. {How is a quadrupole scanned?} : {Its radiofrequency and direct-current amplitudes are varied together so that different m/z values become stable and reach the detector sequentially.}
    
386. {How does an RF-only quadrupole function?} : {Without the mass-selecting DC component, an RF-only quadrupole acts mainly as an ion guide over a useful m/z range.}
    
387. {What is selected-ion monitoring?} : {SIM records one or several selected m/z values rather than scanning a broad spectrum, allowing more measurement time for the chosen ions.}
    
388. {Why can SIM improve sensitivity?} : {Concentrating acquisition time on selected ions improves their signal statistics and reduces contributions from unrelated masses.}
    
389. {What is a limitation of a single quadrupole using soft ionization?} : {Compounds giving the same precursor m/z can remain indistinguishable without additional chromatographic or fragmentation information.}
    

### 7.6. Triple quadrupoles and ion traps

390. {How is a triple-quadrupole instrument arranged?} : {A triple quadrupole contains a first mass filter Q1, a collision cell q2, and a second mass filter Q3.}
    
391. {What is collision-induced dissociation?} : {CID fragments ions by allowing accelerated precursor ions to collide with a gas and convert part of their kinetic energy into internal energy.}
    
392. {How is a product-ion scan performed?} : {Q1 selects a precursor ion, q2 fragments it, and Q3 scans the resulting product ions.}
    
393. {What is multiple-reaction monitoring?} : {MRM measures selected precursor-to-product transitions by fixing Q1 and Q3 to specified m/z values and switching between transitions as required.}
    
394. {Why is MRM effective for quantitative analysis?} : {Requiring both a selected precursor and a characteristic product ion gives high selectivity and allows substantial measurement time on target transitions.}
    
395. {How does an ion-trap analyser work?} : {An ion trap confines ions in an oscillating electric field and selectively ejects them for detection according to m/z.}
    
396. {How does an ion trap perform tandem mass spectrometry?} : {It accumulates ions, isolates a precursor, fragments it, and measures the products within successive stages of a trapping cycle.}
    
397. {What does MSn mean?} : {MSn describes repeated stages of precursor selection and fragmentation, such as selecting an MS² product ion for a further MS³ experiment.}
    
398. {How do tandem experiments in space and time differ?} : {Triple quadrupoles perform stages in separate physical regions, whereas ion traps can perform them sequentially in the same trapping region.}
    
399. {What are space-charge effects?} : {Space-charge effects arise when stored ions repel one another strongly enough to distort their motion, degrading mass measurement, resolution, or quantitative response.}
    

### 7.7. Orbitrap, magnetic-sector, TOF, and hybrid instruments

400. {How does an Orbitrap analyse ions?} : {An Orbitrap confines ions electrostatically around a central electrode and determines m/z from their axial oscillation frequencies.}
    
401. {How does Orbitrap frequency relate to m/z?} : {The oscillation frequency is proportional to 1/√(m/z), so lower-m/z ions oscillate faster.}
    
402. {How is the Orbitrap signal detected?} : {Ion motion induces an image current in the electrodes, and a Fourier transform converts its frequency components into a mass spectrum.}
    
403. {Why does Orbitrap measurement time influence resolution?} : {A longer recorded transient permits more precise separation of nearby frequencies and therefore higher resolving power.}
    
404. {What are the main advantages of Orbitrap instruments?} : {Orbitrap instruments provide high resolving power and good mass accuracy and can be combined with other devices for precursor selection and fragmentation.}
    
405. {How does a magnetic-sector mass analyser work?} : {A magnetic field bends accelerated ion trajectories, with the curvature depending on ion momentum and charge.}
    
406. {What is double focusing?} : {Double focusing combines electrostatic and magnetic sectors to compensate for energy and directional differences among ions and improve resolution.}
    
407. {Which applications of sector instruments are emphasized?} : {The lecture emphasizes isotope-ratio measurements and high-resolution elemental analysis as important applications.}
    
408. {How does a time-of-flight analyser work?} : {A TOF analyser accelerates ions and determines m/z from their travel time through a known flight path, with lighter ions arriving sooner at equal charge and acceleration conditions.}
    
409. {What is the basic TOF flight-time equation?} : {For acceleration voltage V, flight length L, ion mass m, and charge ze, the ideal flight time is t = L√[m/(2zeV)].}
    
410. {Why can equal-m/z ions arrive at different times?} : {Differences in starting position, initial velocity, or kinetic energy can broaden their arrival-time distribution.}
    
411. {How does a reflectron improve TOF resolution?} : {A reflectron makes higher-energy ions penetrate farther and travel a longer path, compensating for part of their earlier arrival.}
    
412. {What unit correction is needed for the lecture’s TOF examples?} : {The illustrated flight times are on the microsecond scale, so the approximately 27.68 value for the 721 Da ion should be interpreted as µs rather than ms.}
    
413. {What is a hybrid mass spectrometer?} : {A hybrid instrument combines different analyser principles, such as quadrupole–TOF or quadrupole–Orbitrap, to unite selective isolation and fragmentation with high-resolution detection.}
    

### 7.8. Mass-spectrometric detectors and coupled methods

414. {How does a discrete-dynode secondary-electron multiplier work?} : {An incoming ion initiates electron emission and successive dynodes multiply the electrons into a measurable electrical signal.}
    
415. {How does a channel electron multiplier differ?} : {A channel electron multiplier amplifies electrons along a continuous curved channel rather than across separate dynodes.}
    
416. {What is a microchannel plate?} : {A microchannel plate is an array of small electron-multiplying channels that provides fast detection suitable for TOF ion packets.}
    
417. {How does image-current detection differ from electron-multiplier detection?} : {Image-current detection measures electrical signals induced by moving trapped ions rather than relying on ions striking a surface to initiate electron multiplication.}
    
418. {Why are separation methods coupled to MS?} : {Coupling separates mixture components before MS measurement and adds mass and fragmentation information to retention or migration behaviour.}
    
419. {What is a total-ion chromatogram?} : {A total-ion chromatogram plots the summed recorded ion signal from each mass spectrum against time.}
    
420. {What is an extracted-ion chromatogram?} : {An extracted-ion chromatogram plots the signal within a selected m/z interval against time to highlight ions of interest.}
    
421. {Why is GC conveniently coupled to EI or CI?} : {GC already delivers vaporized analytes in a gas stream, which can be transferred through a heated interface into a vacuum ion source.}
    
422. {Why are ESI and APCI common in LC-MS?} : {They handle analytes arriving in liquid effluent and form ions before a staged interface transfers them into vacuum.}
    
423. {Why must LC-MS mobile phases be volatile?} : {Volatile solvents and additives are removed more readily, while nonvolatile salts can contaminate the source and suppress ionization.}
    
424. {Why are phosphate buffers generally unsuitable for routine LC-MS?} : {Phosphate is nonvolatile and can produce deposits, ion suppression, and persistent contamination.}
    
425. {Why must MS acquisition speed match chromatographic speed?} : {The instrument must collect enough spectra or transition measurements across each peak to preserve separation information and quantitative accuracy.}
    
426. {How can capillary electrophoresis be coupled to MS?} : {CE-MS commonly transfers capillary effluent into an electrospray interface that maintains the electrical connection and forms ions, although this coupling is listed rather than developed in the slides.}
    

### 7.9. Isotope patterns and exact mass

427. {Why do isotope peaks appear in mass spectra?} : {Naturally occurring isotopes create ions with the same elemental composition but different masses.}
    
428. {What chlorine isotope pattern is expected for one chlorine atom?} : {One chlorine atom produces an approximate M:M + 2 intensity ratio of 3:1 because ³⁵Cl is more abundant than ³⁷Cl.}
    
429. {What bromine isotope pattern is expected for one bromine atom?} : {One bromine atom produces an approximate M:M + 2 ratio of 1:1 because ⁷⁹Br and ⁸¹Br have similar abundances.}
    
430. {How are isotope patterns calculated for multiple halogen atoms?} : {The abundances of all isotope combinations are multiplied and summed for each mass, producing a combinatorial isotope distribution.}
    
431. {What isotope pattern is calculated for the lecture’s Cl2Br example?} : {Using the slide’s relative abundances, the approximate M:M + 2:M + 4:M + 6 pattern is 1:1.62:0.72:0.10.}
    
432. {How can the M + 1 signal estimate carbon number?} : {For a small molecule whose M + 1 signal is dominated by ¹³C, its intensity is approximately 1.1% of M per carbon atom, with corrections needed for other isotope contributions.}
    
433. {How can isotope spacing reveal charge state?} : {The spacing between adjacent carbon-isotope peaks is approximately 1.00335/z in m/z, giving about 1.00, 0.50, or 0.33 for charge states one, two, or three.}
    
434. {What is nominal mass?} : {Nominal mass is the sum of the integer mass numbers assigned to the atoms in a molecule.}
    
435. {What is monoisotopic mass?} : {Monoisotopic mass is the sum of the exact masses of the specified principal isotopes used to define the monoisotopic composition.}
    
436. {How does average molar mass differ from monoisotopic mass?} : {Average molar mass uses isotope-abundance-weighted atomic masses, while monoisotopic mass refers to one particular isotopic composition.}
    
437. {Why can the monoisotopic peak differ from the most intense isotope peak?} : {For larger molecules, combinations containing heavier isotopes can become more probable than the all-principal-isotope composition.}
    
438. {Why does accurate mass help determine molecular formula?} : {Different elemental compositions can have the same nominal mass but different exact masses, so a small mass error excludes many candidate formulas.}
    
439. {Why is accurate mass alone not always sufficient for identification?} : {Different structures can share one formula, and formula assignment also depends on isotope patterns, chemical constraints, adduct identity, and calibration quality.}
    
440. {What is isotope fine structure?} : {At sufficiently high resolution, isotope peaks of the same nominal mass can split into signals from different combinations of isotopes such as ¹³C, ¹⁵N, ¹⁸O, and ³⁴S.}
    

### 7.10. Multiple charging and deconvolution

441. {How is the m/z of a multiply protonated molecule calculated?} : {For [M + zH]z⁺, m/z = (M + zmH)/z = M/z + mH, where mH is the proton mass.}
    
442. {How is neutral mass calculated from a known charge state?} : {Neutral mass is M = z[(m/z) − mH] when the ion’s charges arise from protonation.}
    
443. {What is charge deconvolution?} : {Charge deconvolution combines signals from multiple charge states and converts them into an estimated neutral-mass distribution.}
    
444. {How can adjacent charge-state peaks determine charge?} : {For higher m/z value x carrying charge z and lower value y carrying charge z + 1, z = (y − mH)/(x − y).}
    
445. {What does the lecture’s 1001 and 501 example illustrate?} : {Using a proton mass approximated as one, peaks at m/z 1001 and 501 correspond to singly and doubly protonated forms of a molecule with neutral mass 1000.}
    
446. {Why must deconvolution identify adducts correctly?} : {Sodium, potassium, solvent adducts, and unrelated overlapping ions can violate the proton-only model and lead to incorrect mass assignments.}
    

### 7.11. Protein identification and peptide sequencing

447. {What is the general bottom-up protein-identification workflow?} : {The protein is digested into peptides, the peptides are measured by MS or MS/MS, and the data are compared with predicted peptides from sequence databases.}
    
448. {What is peptide mass fingerprinting?} : {Peptide mass fingerprinting identifies a protein by matching the measured masses of its digestion products to a predicted peptide-mass set.}
    
449. {Why must database-search parameters be specified?} : {Enzyme specificity, missed cleavages, modifications, mass tolerance, and organism restrictions change the predicted matches and their statistical significance.}
    
450. {Why can a protein mixture complicate peptide mass fingerprinting?} : {Peptides from several proteins contribute to the same mass list, making assignment to one protein less straightforward.}
    
451. {How does peptide MS/MS improve identification?} : {Selecting and fragmenting individual peptides provides sequence-related information that can distinguish candidates with similar peptide masses.}
    
452. {What are amino-acid residue masses?} : {Residue masses are the masses of amino acids as incorporated into a peptide chain and equal the free amino-acid mass minus water.}
    
453. {How is the neutral mass of a linear peptide calculated?} : {Its neutral mass is the sum of residue masses plus one water molecule for the terminal groups.}
    
454. {What are b ions?} : {b ions are peptide fragments that retain the N-terminal portion after backbone cleavage.}
    
455. {What are y ions?} : {y ions are peptide fragments that retain the C-terminal portion after backbone cleavage.}
    
456. {How do consecutive b or y ions reveal sequence?} : {The mass difference between consecutive ions in a consistently assigned series corresponds to the residue added between them.}
    
457. {How are singly charged b-ion masses calculated?} : {A singly charged b ion has a mass approximately equal to the sum of its residue masses plus one proton.}
    
458. {How are singly charged y-ion masses calculated?} : {A singly charged y ion has a mass approximately equal to the sum of its residue masses plus water and one proton.}
    
459. {What does the lecture’s b3 calculation illustrate?} : {Using nominal residue masses, a Y–G–G b3 ion has m/z approximately 163 + 57 + 57 + 1 = 278.}
    
460. {What does the lecture’s y3 calculation illustrate?} : {Using nominal residue masses, an F–M–G y3 ion has m/z approximately 147 + 131 + 57 + 18 + 1 = 354.}
    
461. {What other backbone-fragment series are shown?} : {The slides also show a, c, x, and z series, which arise from cleavage at other positions in the peptide backbone.}
    
462. {What is de novo peptide sequencing?} : {De novo sequencing infers an amino-acid sequence directly from fragment masses without requiring an existing matching database sequence.}
    
463. {What can limit peptide sequencing from fragment masses?} : {Incomplete fragment series, overlapping ions, modifications, and residues with identical or similar masses can prevent an unambiguous sequence assignment.}
    

## 8. Inductively coupled plasma spectroscopy

### 8.1. Plasma formation and sample introduction

464. {What is an inductively coupled plasma?} : {An ICP is a hot ionized gas, commonly argon, sustained by energy transferred from a radiofrequency electromagnetic field.}
    
465. {How is an ICP initiated and maintained?} : {A spark creates initial electrons, which gain energy from the RF field and cause further collisions and ionization that sustain the plasma.}
    
466. {Why is an ICP useful for elemental analysis?} : {Its high temperature efficiently dries, vaporizes, dissociates, atomizes, excites, and ionizes many sample constituents.}
    
467. {How is a liquid sample introduced into an ICP?} : {A nebulizer converts the liquid into aerosol droplets, and a spray chamber preferentially sends the finer droplets into the plasma.}
    
468. {Why is a spray chamber used?} : {The spray chamber removes large droplets that would destabilize the plasma or reduce the reproducibility of sample introduction.}
    
469. {What temperatures are illustrated for the ICP?} : {The slides illustrate approximately 8,000 K in the hottest region and around 6,000 K in the sample channel, with actual temperatures depending on position and conditions.}
    

### 8.2. ICP-AES or ICP-OES

470. {What is ICP optical-emission spectroscopy?} : {ICP-OES, also called ICP-AES, determines elements from characteristic light emitted by excited atoms and ions in the plasma.}
    
471. {Why can ICP-OES measure many elements?} : {The plasma excites many elements simultaneously, and the optical system separates their characteristic emission wavelengths.}
    
472. {Why is wavelength resolution important in ICP-OES?} : {Closely spaced emission lines must be distinguished to avoid assigning an interfering element’s emission to the analyte.}
    
473. {How are spectral interferences reduced in ICP-OES?} : {Interferences are reduced by selecting suitable analytical lines, applying background correction, and using adequate optical resolution.}
    
474. {What does the phosphorus-in-copper example illustrate?} : {It illustrates that an analytical wavelength must be selected to avoid interference from nearby copper emission when measuring phosphorus.}
    

### 8.3. ICP-MS and interferences

475. {What is ICP-MS?} : {ICP-MS uses the plasma as an elemental ion source and measures the resulting ions by their mass-to-charge ratios.}
    
476. {How are ions transferred from the ICP to the mass spectrometer?} : {Sampling and skimmer cones extract part of the plasma ion population into progressively lower-pressure regions before ion optics guide it to the analyser.}
    
477. {Why does ICP-MS generally lose molecular structural information?} : {The hot plasma decomposes molecules and produces mainly elemental ions, so the signal indicates elemental content rather than intact molecular structure.}
    
478. {What are major strengths of ICP-MS?} : {ICP-MS provides sensitive multielement analysis and can measure isotope distributions or isotope ratios with suitable instrumentation.}
    
479. {What is a polyatomic interference?} : {A polyatomic interference occurs when an ion made from multiple atoms has the same nominal m/z as the analyte ion.}
    
480. {Which interference affects iron at nominal m/z 56?} : {The ⁴⁰Ar¹⁶O⁺ ion can interfere with measurement of ⁵⁶Fe⁺.}
    
481. {Which interference affects arsenic at nominal m/z 75?} : {The ⁴⁰Ar³⁵Cl⁺ ion can interfere with measurement of ⁷⁵As⁺.}
    
482. {Which interferences can affect chromium and vanadium?} : {⁴⁰Ar¹²C⁺ and ³⁵Cl¹⁶OH⁺ can interfere with ⁵²Cr⁺, while ³⁵Cl¹⁶O⁺ can interfere with ⁵¹V⁺.}
    
483. {How can high-resolution ICP-MS distinguish some interferences?} : {High resolving power separates analyte and interfering ions when their exact masses differ sufficiently despite identical nominal masses.}
    
484. {How can a collision cell reduce polyatomic interferences?} : {Collisions with an inert gas can reduce the kinetic energy of larger polyatomic ions more strongly, allowing suitable energy discrimination to suppress them.}
    
485. {How can a reaction cell remove interferences?} : {A reactive gas selectively converts interfering ions or analyte ions into different species, allowing the target signal to be measured with less overlap.}
    
486. {What does the ammonia reaction example demonstrate?} : {It demonstrates selective charge-transfer chemistry that can remove some argon-derived ions while leaving certain analyte ions largely unaffected.}
    
487. {Why are ionization energies relevant to reaction-cell chemistry?} : {Ionization energies help determine whether charge transfer between an ion and the reaction gas is energetically favourable.}
    
488. {Can all ICP-MS interferences be removed using one cell gas?} : {No single cell gas removes every interference because effectiveness depends on the analyte, interfering species, reaction chemistry, and operating conditions.}
    

### 8.4. Comparison of elemental-analysis methods

489. {What are the main advantages of flame AAS?} : {Flame AAS offers relatively simple operation and low cost for suitable elemental measurements.}
    
490. {What are the main limitations of flame AAS?} : {It generally has lower sensitivity than more advanced trace methods and commonly measures one element at a time.}
    
491. {What are the main advantages of graphite-furnace AAS?} : {Graphite-furnace AAS provides high sensitivity for many elements while requiring only a small sample volume.}
    
492. {What are the main limitations of graphite-furnace AAS?} : {It generally measures one element at a time and requires careful temperature programming and control of matrix effects.}
    
493. {What are the main advantages of ICP-OES compared with AAS?} : {ICP-OES offers rapid multielement analysis and broad analytical coverage without the sequential single-element limitation of conventional AAS.}
    
494. {What are the main advantages and limitations of ICP-MS?} : {ICP-MS offers very low detection limits and isotope information but has higher cost and requires effective control of spectral interferences and matrix effects.}
    
495. {Why should detection limits be compared element by element?} : {Relative performance depends on the element, analytical line or isotope, sample matrix, and instrument conditions rather than one universal sensitivity ranking.}
    
496. {Which factors guide selection of an elemental-analysis method?} : {Selection considers required detection limits, number of elements, sample volume, matrix complexity, throughput, isotope information, and available resources.}
    

### 8.5. Laser-ablation ICP-MS

497. {How does laser-ablation ICP-MS work?} : {A pulsed laser removes material from a solid surface, and carrier gas transports the resulting aerosol to the ICP for elemental ionization and MS detection.}
    
498. {Why is laser ablation useful for solid samples?} : {It allows localized elemental measurements with little bulk sample preparation and can avoid complete dissolution of the sample.}
    
499. {How does laser-ablation ICP-MS produce elemental images?} : {Measurements at successive surface positions are combined into maps showing the distribution of selected elements.}
    
500. {What does the rat-kidney imaging example show?} : {It shows separate copper and platinum intensity maps that reveal their differing spatial distributions in the tissue.}
    
501. {How is depth profiling performed by laser ablation?} : {Repeated pulses at the same location remove successive layers, allowing changes in elemental composition to be followed with increasing depth.}
    
502. {What is required for reliable quantitative laser-ablation analysis?} : {Reliable quantitation requires suitable calibration and control of differences in ablation, aerosol transport, and elemental response between standards and samples.}