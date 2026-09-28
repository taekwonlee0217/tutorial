# Instrumental Analysis WS24/25 - Core Questions and Answers

## 1. Theory of Chromatography

1. {What is chromatography?} : {Chromatography separates mixture components through their different distributions between a mobile phase and a stationary phase.}
2. {Which physical states can serve as mobile phases?} : {A mobile phase may be a gas, a supercritical fluid, or a liquid.}
3. {What forms can a stationary phase take?} : {A stationary phase is usually a solid or nonvolatile liquid polymer coated on or packed into a column, except in planar methods such as TLC.}
4. {Which interactions can cause chromatographic retention?} : {Important retention mechanisms include partition, adsorption, ion exchange, size exclusion, affinity, and related selective interactions.}
5. {How is a thin-layer chromatography experiment performed?} : {A small sample is spotted on a thin stationary layer and carried upward by capillary flow of the mobile phase so its components migrate to different positions.}
6. {How is the TLC retention factor calculated?} : {The TLC retention factor is Rf = distance traveled by the analyte spot divided by distance traveled by the solvent front.}
7. {What information does an Rf value provide?} : {An Rf value can support limited identification against standards and gives an indication of analyte polarity under fixed conditions.}
8. {How are TLC migration and column-LC retention related?} : {A high TLC Rf corresponds to a short column-LC retention time, and the TLC solvent front corresponds to the column dead time tm.}
9. {How do volumetric and linear mobile-phase flow differ?} : {Volumetric flow F is expressed as volume per time, whereas linear flow u is expressed as distance per time.}
10. {Which quantities describe analyte retention in a column?} : {Retention can be described by retention time tr, retention volume Vr = Ftr, or retention factor k.}
11. {What is the partition coefficient K?} : {The partition coefficient is K = Cs/Cm, the ratio of analyte concentration in the stationary phase to that in the mobile phase.}
12. {How is the retention factor related to partitioning?} : {The retention factor is k = K(Vs/Vm), which is also the ratio of analyte moles in the stationary and mobile phases.}
13. {How is retention factor calculated from time measurements?} : {The retention factor is k = (tr - tm)/tm = tr'/tm, so tr = tm(1 + k).}
14. {What is chromatographic selectivity?} : {The separation factor is alpha = k2/k1 = tr2'/tr1' for two compounds ordered so that the second is more strongly retained.}
15. {Which two peak properties principally determine separation quality?} : {Separation quality depends on the difference in retention times and the widths of the peaks.}
16. {How are ideal chromatographic peak widths related to standard deviation?} : {For a Gaussian peak, the baseline width is approximately 4 sigma and the half-height width is approximately 2.35 sigma.}
17. {What does the theoretical-plate model represent?} : {The theoretical-plate model treats a column as successive equilibrium segments in which analyte repartitions between mobile and stationary phases.}
18. {How do column length and plate height affect plate number?} : {Increasing column length or decreasing the height required to establish equilibrium increases the number of theoretical plates.}
19. {What are N and HETP?} : {N is the number of theoretical plates and HETP is the height equivalent to one theoretical plate, with HETP = L/N.}
20. {How is plate number calculated from a chromatographic peak?} : {Plate number is N = 16(tr/w)^2 using baseline width or N = 5.54(tr/w1/2)^2 using half-height width.}
21. {What does a high plate number mean?} : {A high N indicates high column efficiency and narrow peaks.}
22. {What are the three major causes of chromatographic peak broadening?} : {Peak broadening arises mainly from eddy dispersion, longitudinal diffusion, and resistance to mass transfer.}
23. {What causes eddy dispersion?} : {Eddy dispersion results from molecules taking different paths through a packed bed and contributes an approximately flow-independent A term proportional to particle size.}
24. {What causes longitudinal diffusion?} : {Longitudinal diffusion spreads solute from the concentrated band center toward its dilute edges and contributes B/u, where B is related to diffusion coefficient.}
25. {What causes resistance-to-mass-transfer broadening?} : {Finite transport between phases, within stationary-phase films, or through stagnant pore liquid causes a Cu contribution that grows with flow velocity.}
26. {What is the van Deemter equation?} : {The van Deemter equation is HETP = A + B/u + Cu and predicts an optimum linear velocity at minimum plate height.}
27. {How is resolution between two peaks calculated?} : {Resolution is R = 2(tr2 - tr1)/(w1 + w2), where w1 and w2 are baseline peak widths.}
28. {What do resolution, peak capacity, and tailing factor describe?} : {Resolution rises with efficiency N, selectivity alpha, and suitable retention k; peak capacity counts resolvable peaks in a window; and the USP tailing factor is AB/(2AC) at 5% peak height.}

## 2. High-Performance Liquid Chromatography

29. {Why does HPLC use small stationary-phase particles?} : {Small particles reduce eddy dispersion and mass-transfer distance, increasing efficiency but requiring much higher pressure.}
30. {How does UHPLC differ from conventional HPLC?} : {UHPLC uses particles about 2 micrometers or smaller and higher pressure to achieve faster or more efficient separations.}
31. {What is column resolving power in relation to particle size?} : {Column resolving power is associated with the length-to-particle-diameter ratio L/dp.}
32. {What are the principal modules of an HPLC system?} : {An HPLC system contains solvent reservoirs, online degassing, pumps, an injector or autosampler, a column compartment, a detector, and data acquisition.}
33. {What distinguishes isocratic from gradient HPLC?} : {Isocratic HPLC keeps mobile-phase composition constant, whereas gradient HPLC changes solvent composition during the run.}
34. {How do low-pressure and high-pressure gradient mixing differ?} : {Low-pressure mixing combines solvents before one pump, whereas high-pressure mixing uses separate pumps and mixes their pressurized streams.}
35. {Why is online degassing used in HPLC?} : {Online degassing removes dissolved gases that could form bubbles, disturb pumping, or create detector noise.}
36. {How do modern dual-piston HPLC pumps reduce flow pulsation?} : {A large and small piston operate out of phase so one draws solvent while the other delivers it and is refilled during the stroke change.}
37. {How should injection volume be chosen?} : {Injection volume must be matched to stationary-phase volume, with smaller volumes used for narrow-bore columns and larger volumes requiring larger columns.}
38. {What are typical HPLC column characteristics?} : {Typical HPLC columns are 3-25 cm long, 0.5-5 mm in internal diameter, and packed with roughly 1.5-5 micrometer particles or formed as monoliths.}
39. {Why is a guard column used?} : {A guard column protects the analytical column from contaminants and strongly retained sample components.}
40. {Which criteria are used to evaluate HPLC detectors?} : {Important criteria include detection limit, sensitivity, linearity, selectivity, gradient compatibility, response type, robustness, price, and acquisition speed.}
41. {Why must detector acquisition rate match chromatographic speed?} : {The acquisition rate must be high enough to record sufficient points across the narrowest peak without distorting its shape or losing resolution.}
42. {Which detector types are commonly used in HPLC?} : {Common detectors include UV-visible, fluorescence, refractive index, ELSD, CAD, electrochemical, conductivity, post-column-reaction, and mass-spectrometric detectors.}
43. {How does a UV-visible HPLC detector respond?} : {A UV-visible detector measures solute-dependent absorption at selected wavelengths and is a concentration-sensitive solute-property detector.}
44. {What is the main advantage of fluorescence detection?} : {Fluorescence detection offers very high sensitivity and selectivity for naturally fluorescent or derivatized analytes.}
45. {What limitation makes refractive-index detection unsuitable for many gradients?} : {Because it measures a bulk refractive-index difference between sample and mobile phase, changing solvent composition produces a large baseline shift.}
46. {How does an evaporative light-scattering detector work?} : {ELSD nebulizes the eluent, evaporates volatile mobile phase, and measures light scattered by the remaining nonvolatile analyte particles.}
47. {How does a charged aerosol detector work?} : {CAD evaporates mobile phase, charges the remaining analyte aerosol, and measures the resulting electrical signal for many nonvolatile compounds.}
48. {Which analytes are suitable for amperometric detection?} : {Analytes that can be oxidized or reduced are detected through current generated at a controlled working-electrode potential.}
49. {Why is pulsed amperometric detection useful?} : {PAD intersperses detection with cleaning potentials to prevent electrode fouling and is especially useful for sugars and polyalcohols.}
50. {What physical forms can HPLC stationary phases have?} : {HPLC stationary phases are commonly porous particles and less commonly monoliths containing interconnected macropores and micropores.}
51. {Which particle properties govern HPLC performance?} : {Performance depends on particle diameter, narrow size distribution, spherical shape, porosity, pore size, surface area, pressure stability, and chemical stability.}
52. {What is the advantage of core-shell particles?} : {Core-shell particles provide short diffusion paths and high efficiency resembling very small particles while keeping back pressure more manageable.}
53. {Which major separation modes are used in HPLC?} : {Major modes include normal phase, HILIC, reversed phase, size exclusion, ion exchange, ion pair, ion exclusion, affinity, chiral, and hydrophobic-interaction chromatography.}
54. {What are the phases and retention trend in normal-phase HPLC?} : {Normal-phase HPLC uses a polar stationary phase and nonpolar mobile phase, so retention generally increases with analyte polarity.}
55. {How does mobile-phase polarity affect normal-phase retention?} : {Increasing mobile-phase polarity raises elution strength and decreases analyte retention.}
56. {Which stationary phases are used in normal-phase HPLC?} : {Normal-phase stationary phases include silica, alumina, and silica modified with diol, cyano, or amino groups.}
57. {What is an eluotropic series?} : {An eluotropic series ranks solvents by their relative ability to elute analytes from a particular stationary phase.}
58. {What is HILIC?} : {Hydrophilic-interaction liquid chromatography is a normal-phase-like mode using a polar stationary phase and a water-organic mobile phase, often rich in acetonitrile.}
59. {What is the HILIC elution order?} : {The least polar analytes elute first, while polar analytes interact more strongly with the stationary phase or its water-rich interfacial layer.}
60. {What are the phases and retention trend in reversed-phase HPLC?} : {Reversed-phase HPLC uses a nonpolar stationary phase and polar mobile phase, so more hydrophobic analytes are usually retained more strongly.}
61. {Which stationary phases are common in reversed-phase HPLC?} : {Common phases include C8, C18, phenyl, pentafluorophenyl, cyano, polymeric styrene-divinylbenzene, and porous graphite.}
62. {What is endcapping in bonded-silica columns?} : {Endcapping reacts residual silanol groups with a small reagent such as trimethylchlorosilane to reduce unwanted polar interactions.}
63. {How is a reversed-phase gradient commonly produced?} : {The proportion of stronger organic solvent in an aqueous-organic mobile phase is increased over time.}
64. {What roles do water percentage and organic-solvent identity play in RP-HPLC optimization?} : {Water percentage mainly controls elution strength and k, whereas organic-solvent identity changes selectivity alpha through different intermolecular interactions.}
65. {What is the principle of size-exclusion chromatography?} : {SEC separates high-molecular-mass analytes by their ability to enter pores of defined size without intended chemical interaction with the packing.}
66. {Which molecules elute first in SEC?} : {Large molecules excluded from pores elute first, whereas smaller molecules enter more pore volume and elute later.}
67. {How is SEC retention volume expressed?} : {SEC retention volume is VR = VI + KSEC VP, where VI is interstitial volume, VP is pore volume, and normally 0 < KSEC < 1.}
68. {What does KSEC greater than one indicate?} : {A KSEC value above one indicates unintended adsorption to stationary-phase sites.}
69. {What is gel permeation chromatography?} : {GPC is SEC, with the name often reserved for technical polymers that may require high-temperature dissolution and separation.}
70. {How are number-average and weight-average molecular masses calculated?} : {Mn = sum(xiMi) and Mw = sum(wiMi), with wi = xiMi/Mn.}
71. {What do the polydispersity index and degree of polymerization express?} : {Polydispersity is Mw/Mn, while average degree of polymerization is Dp = Mn divided by repeat-unit molar mass.}
72. {How does ion-exchange chromatography retain ions?} : {Charged analytes reversibly replace mobile-phase counterions on oppositely charged fixed groups of a polymeric stationary phase.}
73. {Which factors increase ion-exchange retention?} : {Retention increases with lower eluent-ion concentration, higher exchanger capacity, and a larger analyte selectivity constant.}
74. {What is suppressed ion chromatography?} : {Suppressed IC separates small ions and then converts a conductive eluent into a low-conductivity form while converting analyte salts into more strongly conducting species.}
75. {How does ion-pair chromatography retain ionic analytes on reversed-phase media?} : {A hydrophobic counterion in the mobile phase associates with the analyte or stationary phase so the ionic analyte can interact with nonpolar packing.}
76. {What are affinity, chiral, and supercritical-fluid chromatography used for?} : {Affinity chromatography exploits specific biological binding, chiral chromatography resolves enantiomers with chiral selectors, and SFC uses a supercritical mobile phase such as CO2 for efficient, easily recoverable separations.}

## 3. Gas Chromatography

77. {What are the mobile and stationary phases in gas chromatography?} : {GC uses He, N2, or H2 as gaseous mobile phase and either a nonvolatile liquid polymer or solid adsorbent as stationary phase.}
78. {Which samples are suitable for GC?} : {GC analytes must be volatile enough to vaporize and sufficiently thermally stable for injection and separation.}
79. {What is temperature programming in GC?} : {Temperature programming raises oven temperature during the run to elute compounds spanning a wide volatility range with useful peak widths and run time.}
80. {What is a WCOT column?} : {A wall-coated open-tubular column is a capillary whose inner wall carries a thin liquid or polymeric stationary-phase film and is the most important GC column type.}
81. {What is a PLOT column?} : {A porous-layer open-tubular column has a layer of porous solid particles on the capillary wall and is useful for gases and very volatile compounds.}
82. {What are typical dimensions of fused-silica GC capillaries?} : {Fused-silica capillaries are roughly 10-100 m long, have 0.10-0.53 mm internal diameters, and carry a protective polyimide coating.}
83. {How do capillary diameter and film thickness affect GC efficiency and capacity?} : {Smaller diameter and thinner film improve efficiency but reduce capacity, whereas larger diameter and thicker film increase capacity.}
84. {How does stationary-phase film thickness affect GC retention?} : {A thicker film increases stationary-phase volume and retention factor but may worsen mass-transfer broadening.}
85. {How does temperature affect retention in gas-liquid chromatography?} : {Retention depends strongly on analyte vapor pressure, so increasing temperature generally decreases k and accelerates elution.}
86. {Why may GC carrier gas require purification?} : {Molecular sieves remove water, carbon removes hydrocarbons, and metallic copper removes oxygen that could damage columns or degrade analyses.}
87. {What linear carrier-gas velocity is a useful GC benchmark?} : {The lecture gives an optimum linear velocity of approximately 30 cm/s, with the exact optimum depending on gas and column.}
88. {How is a liquid stationary phase selected for GC?} : {A stationary phase is chosen to match analyte polarity according to the like-dissolves-like principle.}
89. {Which liquid stationary-phase families are common in WCOT columns?} : {Common phases include polysiloxanes with varying methyl, phenyl, or cyanopropyl content and polar polyethylene-glycol phases.}
90. {Which solid phases and applications are common in PLOT columns?} : {Alumina, silica, porous polymers, molecular sieves, and graphitized carbon separate permanent gases, sulfur gases, halocarbons, and very volatile hydrocarbons.}
91. {Which GC inlet and sampling methods are emphasized?} : {Methods include split/splitless, programmed-temperature vaporization, cold on-column injection, headspace, SPME, thermal desorption, purge-and-trap, and pyrolysis.}
92. {How does split injection work?} : {A small sample is rapidly vaporized in a hot inlet and most vapor exits through the split vent so only a controlled fraction reaches the column.}
93. {What is a major risk of split injection?} : {Differential vaporization or transfer can cause discrimination and change the sample composition entering the column.}
94. {How does splitless injection work?} : {The split valve remains closed for about 30-90 seconds so most vapor enters a cool column, after which the valve opens and temperature programming begins.}
95. {How are analytes focused during splitless injection?} : {Solvent trapping and cold trapping concentrate the injected band at the column head, often aided by an uncoated retention gap.}
96. {What is programmed-temperature-vaporization injection?} : {PTV first removes solvent at low temperature and then heats the inlet under control to transfer analytes to the column.}
97. {What are the advantages and drawback of PTV injection?} : {PTV reduces discrimination and decomposition, accepts larger volumes, and suits trace work, but costs more and requires experienced parameter optimization.}
98. {Why is cold on-column injection used?} : {It places sample directly into a relatively cool column and minimizes thermal decomposition and inlet discrimination for labile analytes.}
99. {What is static headspace analysis?} : {A sealed sample equilibrates at constant elevated temperature and an aliquot of gas phase, whose volatile-analyte concentration reflects the sample, is injected.}
100. {What is dynamic headspace analysis?} : {Purge gas sweeps headspace analytes to a cooled trap, which is rapidly heated to transfer the concentrated analytes to the GC column.}
101. {How does solid-phase microextraction sample analytes?} : {An absorbent-coated fiber, often PDMS, extracts analytes from headspace or liquid and then thermally desorbs them in the inlet.}
102. {How does thermal-desorption analysis work?} : {Heating a solid or sorbent tube under inert gas transfers trapped volatiles to a cryotrap that is rapidly heated into the GC column.}
103. {What is an important application of sorbent-tube thermal desorption?} : {It is widely used to collect and analyze volatile organic compounds from indoor or ambient air.}
104. {How does purge-and-trap differ from headspace sampling?} : {An inert gas is bubbled through a liquid sample and swept analytes are trapped on a sorbent before thermal desorption.}
105. {What is pyrolysis GC?} : {Pyrolysis GC decomposes polymers at temperatures above about 1000 degrees Celsius in inert gas and separates the resulting diagnostic fragments.}
106. {How does a flame-ionization detector work?} : {An eluting organic compound forms ions in a hydrogen-air flame and the collected ion current produces the signal.}
107. {What are the main characteristics of FID?} : {FID is a destructive, broadly carbon-sensitive detector with a wide linear range near 10^7 and low-picogram detection limits for hydrocarbons.}
108. {How does an electron-capture detector work?} : {A radioactive source such as 63Ni generates electrons in makeup gas, and electron-capturing analytes reduce the current or increase the pulse frequency needed to maintain it.}
109. {Which compounds are especially suited to ECD?} : {ECD is highly sensitive to electron-absorbing compounds, especially halogenated analytes.}
110. {How does a thermal-conductivity detector work?} : {Eluting compounds change filament heat loss relative to pure carrier gas, altering resistance and the bridge voltage.}
111. {What is a principal application of TCD?} : {TCD is a universal, nondestructive detector used particularly for permanent and other gas samples.}
112. {Which element-selective spectroscopic GC detectors were mentioned?} : {The lecture mentions flame photometric detection for sulfur and phosphorus, atomic-emission detection, chemiluminescence, and infrared absorption.}
113. {What is two-dimensional GC?} : {GCxGC transfers fractions from a first column to an orthogonal second column for much greater separation capacity.}
114. {What stationary-phase arrangement is common in GCxGC?} : {The two columns usually have different selectivities, commonly a long nonpolar first column followed by a short polar second column.}
115. {What is the difference between heart-cutting and comprehensive 2D GC?} : {Heart-cutting sends selected first-dimension regions to the second column, whereas comprehensive GCxGC repeatedly transfers the entire first-dimension effluent.}
116. {How does cryogenic modulation operate in comprehensive GCxGC?} : {Alternating cold and hot jets focus first-dimension effluent into narrow packets and then release each packet rapidly into the second column.}
117. {What timing requirement governs comprehensive GCxGC?} : {Each second-dimension separation must finish while the next first-dimension fraction is being focused so the first-dimension information can be reconstructed.}

## 4. Electrophoresis

118. {What is the basis of electrophoretic separation?} : {Electrophoresis separates charged analytes through differences in their migration in an electric field.}
119. {Where can electrophoretic separations be performed?} : {They can be carried out in free buffered solution, as in capillary electrophoresis, or in buffered gel or another anticonvective support.}
120. {Which principal electrophoretic modes are covered?} : {The lecture covers capillary zone electrophoresis, capillary gel electrophoresis, isoelectric focusing, and supported gel electrophoresis, while listing several additional capillary modes.}
121. {What components make up a CZE instrument?} : {A CZE instrument uses buffer and sample vials, a high-voltage supply up to roughly 30 kV, a fused-silica capillary, and a detector.}
122. {What are typical dimensions of a CZE capillary?} : {A fused-silica capillary is about 30-100 cm long, 25-100 micrometers in internal diameter, and protected externally by polyimide.}
123. {What is chip electrophoresis?} : {Chip electrophoresis performs capillary-scale electrophoretic operations in miniaturized microfluidic channels.}
124. {Which forces determine electrophoretic velocity?} : {Electrical acceleration zeE is balanced at steady state by Stokes friction 6pi eta r vep.}
125. {How is electrophoretic mobility defined?} : {Electrophoretic mobility is mu_ep = vep/E and for a spherical ion is proportional to charge divided by viscosity and ionic radius.}
126. {Why does electroosmotic flow arise in bare fused silica?} : {Above about pH 3, deprotonated silanol groups create a mobile counterion layer that moves toward the cathode and drags the electrolyte.}
127. {How are electroosmotic velocity and mobility related?} : {Electroosmotic velocity is veo = mu_eo E, with mobility influenced by zeta potential, permittivity, and viscosity.}
128. {Why does electroosmotic flow cause relatively little peak broadening?} : {EOF has an approximately plug-like profile instead of the parabolic profile of pressure-driven laminar flow.}
129. {How can electroosmotic flow be changed?} : {Higher ionic strength and organic solvent usually reduce EOF, while surface-active modifiers can reduce or even reverse its direction.}
130. {How are apparent analyte mobility and velocity defined in CZE?} : {Apparent mobility is mu_app = mu_ep + mu_eo and apparent velocity is vapp = vep + veo, with signs determined by direction.}
131. {How is apparent mobility obtained from migration time?} : {Apparent mobility is calculated from capillary lengths, migration time, and voltage as mu_app = LdLt/(Vt).}
132. {Which two principal sample-injection methods are used in CZE?} : {Samples are introduced by pressure or electrokinetically, often at volumes near the nanoliter scale.}
133. {Why is electrokinetic injection selective?} : {Applied voltage preferentially draws ions of the favored charge and mobility into the capillary while EOF also transports bulk solution.}
134. {How can electrokinetic injection enrich an analyte?} : {Its charge and mobility discrimination can introduce many more target ions than simple pressure injection under suitable conditions.}
135. {Which detectors are used for capillary electrophoresis?} : {Common CE detectors include direct or indirect UV absorbance, fluorescence, conductivity, and mass spectrometry.}
136. {How do direct and indirect UV detection differ in CE?} : {Direct detection measures absorption by a UV-active analyte, whereas indirect detection measures displacement of a UV-active background-electrolyte ion by a UV-inactive analyte.}
137. {What determines separation in CZE?} : {CZE separates analytes mainly by electrophoretic mobility and therefore by their charge-to-size relationship.}
138. {How can CZE selectivity be optimized?} : {Changing pH alters analyte ionization, while complexing agents alter effective charge, size, or both.}
139. {How are enantiomers separated by CZE?} : {A chiral selector such as a cyclodextrin forms transient diastereomeric complexes with different mobilities.}
140. {What is the separation mechanism in capillary gel electrophoresis?} : {A polymeric gel or solution provides a molecular-sieving matrix that separates macromolecules primarily by size.}
141. {How is DNA separated by capillary gel electrophoresis?} : {Negatively charged DNA fragments migrate through a sieving matrix, with smaller fragments moving more readily than larger ones.}
142. {Why is SDS used in protein capillary gel electrophoresis?} : {SDS forms negatively charged protein complexes with a nearly constant charge-to-mass ratio so separation reflects molecular size.}
143. {What is isoelectric focusing?} : {Ampholytic analytes migrate through an ampholyte-generated pH gradient until reaching the pH equal to their isoelectric point, where net charge becomes zero.}
144. {What is the role of an anticonvective support in gel electrophoresis?} : {Polyacrylamide, agarose, or cellulose acetate immobilizes buffer and suppresses convection while analytes separate under high voltage.}
145. {How does two-dimensional protein gel electrophoresis separate proteins?} : {Proteins are first separated by isoelectric point using IEF and then by molecular size using SDS-PAGE.}

## 5. Infrared and Raman Spectroscopy

146. {How does radiation energy determine spectroscopic information?} : {Different energies induce nuclear-spin, electron-spin, rotational, vibrational, valence-electron, inner-shell-electron, or nuclear transitions.}
147. {What distinguishes absorption from emission spectroscopy?} : {Absorption methods measure radiation removed during excitation, whereas emission methods measure radiation released as an excited species relaxes.}
148. {Which other radiation interactions can be measured spectroscopically?} : {Analytical methods also exploit scattering or diffraction, reflectance, refraction, and changes in polarization.}
149. {What molecular process is primarily probed by IR spectroscopy?} : {IR radiation excites molecular vibrations, often together with rotational structure.}
150. {What are the approximate near-, mid-, and far-IR ranges?} : {NIR spans about 14,000-4,000 cm^-1, MIR 4,000-200 cm^-1, and FIR 200-20 cm^-1.}
151. {How are photon energy, frequency, wavelength, and wavenumber related?} : {They are related by E = hnu = hc/lambda = hc times wavenumber.}
152. {How did dispersive and FT-IR instruments traditionally differ in beam design?} : {Dispersive MIR instruments commonly used dual beams and gratings, while modern FT-IR instruments are usually single-beam interferometer systems.}
153. {What is the advantage of dual-beam IR measurement?} : {It permits simultaneous sample and background measurement and continuous compensation for solvent or background absorption.}
154. {What are the main disadvantages of dispersive IR instruments?} : {They scan slowly, lose radiation through slits, do not readily accumulate spectra, and do not maintain constant resolution across the range.}
155. {Which radiation sources are used in MIR?} : {A robust but less intense silicon-carbide Globar or a more intense but less robust rare-earth-oxide Nernst glower can be used.}
156. {Which radiation sources are used in NIR?} : {Quartz-halogen and tungsten lamps are common NIR sources.}
157. {Which wavelength-selection devices are used for IR?} : {IR instruments can use gratings, interferometers, or, in NIR, diode arrays.}
158. {What is the operating principle of a Michelson interferometer?} : {A beam splitter sends light to fixed and moving mirrors, and their path difference produces wavelength-dependent constructive and destructive interference.}
159. {What is an interferogram?} : {An interferogram records total detector intensity as a function of moving-mirror position and contains information from all measured frequencies.}
160. {Why is Fourier transformation required in FT-IR?} : {Fourier transformation converts the time- or path-domain interferogram into the conventional intensity-versus-wavenumber spectrum.}
161. {What is apodization in FT spectroscopy?} : {Apodization smooths the truncation of a finite interferogram to reduce spectral ringing at the cost of some resolution.}
162. {What are the principal advantages of FT-IR?} : {FT-IR measures all wavenumbers together, is fast, maintains constant resolution, uses more radiation, and allows signal averaging to improve signal-to-noise ratio.}
163. {How do common IR detector classes differ?} : {Pyroelectric DTGS detectors are less sensitive but operate at room temperature, while photovoltaic detectors are more sensitive but often require liquid-nitrogen cooling.}
164. {What is the reduced mass of a diatomic oscillator?} : {The reduced mass is mu = m1m2/(m1 + m2).}
165. {What does the harmonic-oscillator model assume?} : {It models a bond as a spring obeying Hooke's law F = -ky with a parabolic potential E = ky^2/2.}
166. {What determines the harmonic vibrational frequency?} : {The frequency is nu = (1/2pi)sqrt(k/mu), so stronger bonds and smaller reduced masses vibrate at higher frequency.}
167. {How are harmonic-oscillator energy levels quantized?} : {Allowed levels are E = hnu(v + 1/2), where v is the vibrational quantum number.}
168. {What is the harmonic vibrational selection rule?} : {The allowed fundamental transition has Delta v = plus or minus 1.}
169. {Why does the anharmonic-oscillator model better describe real bonds?} : {Real bonds dissociate, have progressively closer energy levels, and permit weak overtone transitions such as Delta v = 2 or 3.}
170. {How do rotational and vibrational energies compare?} : {A rotational excitation requires roughly one-thousandth of a vibrational excitation, while valence-electron excitation requires roughly one thousand times more than vibration.}
171. {How are rigid-rotor energy levels expressed?} : {For moment of inertia I = mu r0^2, rotational levels are Erot = hcB J(J + 1) with Delta J = plus or minus 1.}
172. {When is discrete rotational structure observed in IR?} : {Discrete rotational lines are resolved mainly for gases, while condensed-phase interactions merge them into broader vibrational bands.}
173. {What spectral features dominate MIR and NIR?} : {MIR mainly shows fundamental vibrations, whereas NIR mainly shows overtones and combination bands.}
174. {What is the IR vibrational selection requirement?} : {A vibration is IR-active only if it changes the molecular dipole moment.}
175. {How do bond strength and atomic mass affect IR band position?} : {Stronger bonds raise wavenumber, while larger reduced mass lowers it, as illustrated by C-H bands lying above C-D bands.}
176. {Which IR sampling methods are used for solids, liquids, and gases?} : {Solids use KBr pellets, reflectance, or ATR; liquids use solutions, films, or ATR; and gases use gas cells.}
177. {How does attenuated total reflectance sample a material?} : {An evanescent wave from internal reflection in a high-index ZnSe or diamond crystal penetrates the contacting sample and is selectively absorbed.}
178. {How are transmittance and absorbance related?} : {Transmittance is T = I/I0 and absorbance is A = -log T = log(I0/I).}
179. {How do the main analytical uses of MIR and NIR differ?} : {MIR is mainly qualitative for functional-group and structural identification, whereas NIR is widely quantitative and process-oriented but usually requires chemometrics.}
180. {How does Raman spectroscopy differ fundamentally from IR spectroscopy?} : {Raman detects changes in polarizability through inelastic scattering, allowing vibrations that may be inactive in IR because they do not change dipole moment.}

## 6. Raman Spectroscopy

181. {Which sources and detectors can be used in Raman spectroscopy?} : {Sources include mercury, Nd:YAG, and argon lasers, while silicon or InGaAs diodes can detect scattered light in suitable ranges.}
182. {What happens when laser light interacts with molecules in Raman spectroscopy?} : {Most light passes through, about 10^-4 is elastically Rayleigh-scattered, and only about 10^-8 is inelastically Raman-scattered.}
183. {What are Stokes and anti-Stokes Raman scattering?} : {Stokes photons lose energy to molecular vibration, whereas anti-Stokes photons gain energy from initially excited molecules.}
184. {What is Raman shift?} : {Raman shift is the wavenumber difference between laser and scattered light, Delta nu_Raman = nu_laser - nu_scattered.}
185. {Why can IR and Raman spectra be complementary?} : {IR activity requires a dipole-moment change, whereas Raman activity requires a polarizability change, so their selection rules emphasize different vibrations.}

## 7. Mass Spectrometry

### 7.1 Ionization Sources

186. {What are the principal analytical uses of mass spectrometry?} : {Mass spectrometry supports structural elucidation, detection after GC, HPLC, or CE, and quantitative mixture analysis.}
187. {What quantity is actually measured in a mass spectrum?} : {A mass spectrometer measures mass-to-charge ratio m/z and displays ion abundance versus m/z.}
188. {What is the purpose of an MS ion source?} : {The ion source converts analyte molecules into gas-phase ions that can be transferred to a mass analyzer.}
189. {What distinguishes hard from soft ionization?} : {Hard ionization produces extensive fragmentation, whereas soft ionization preserves more intact molecular or protonated-molecular ions.}
190. {Which analytes are suitable for electron ionization?} : {EI is suited to volatile, thermally stable compounds generally below about 1000 Da that can be vaporized under vacuum.}
191. {How does electron ionization form ions?} : {Energetic electrons, conventionally about 70 eV, remove an electron from a gas-phase molecule to form an energetic radical cation that fragments.}
192. {Why is EI fragmentation analytically useful?} : {Reproducible fragment patterns provide structural information and enable library identification with databases such as NIST or Wiley.}
193. {How does chemical ionization differ from EI?} : {CI first ionizes excess reagent gas such as methane, isobutane, or ammonia and then transfers a proton or charge to the analyte.}
194. {What are the main advantages and limitations of CI?} : {CI gives less fragmentation and a prominent [M+H]+ ion but still requires volatile, thermally stable analytes similar to EI.}
195. {Which atmospheric-pressure ionization methods are emphasized?} : {The lecture emphasizes electrospray ionization, atmospheric-pressure chemical ionization, and atmospheric-pressure photoionization.}
196. {Which analytes and mass range are typical for ESI?} : {ESI is a soft method for polar, nonvolatile molecules such as peptides and proteins and can handle masses up to roughly 200,000 Da through multiple charging.}
197. {How is electrospray generated?} : {Several kilovolts at a capillary create charged droplets, with nitrogen-assisted nebulization used at normal HPLC flow rates.}
198. {What happens when an ESI droplet reaches the Rayleigh limit?} : {Coulomb repulsion exceeds surface tension and the droplet undergoes Coulomb fission into smaller charged droplets.}
199. {Which models explain final ion formation in ESI?} : {The charged-residue model is favored for large molecules, while the ion-evaporation model explains ejection of small ions from droplets.}
200. {Why are multiply charged ions common in ESI?} : {Large biomolecules can accept or lose many protons, bringing very high molecular masses into a moderate measurable m/z range.}
201. {Which analytes are suitable for APCI?} : {APCI is a soft atmospheric-pressure method for relatively small, less polar compounds, typically up to about 1200 Da.}
202. {How does APCI ionize an analyte?} : {The vaporized mobile phase is ionized in a plasma or corona region and reagent ions transfer charge, commonly producing [M+H]+ in the gas phase.}
203. {How do ESI and APCI differ in charging behavior?} : {ESI frequently produces multiply charged ions, especially for biomolecules, whereas APCI usually produces singly charged ions.}
204. {How does MALDI prepare and ionize a sample?} : {The analyte is co-crystallized in a light-absorbing solid matrix, and a laser pulse desorbs material before gas-phase proton-transfer ionization.}
205. {What are the major characteristics and applications of MALDI?} : {MALDI is a soft, usually low-charge method for peptides, proteins, and nucleotides up to roughly 500,000 Da and can image lateral analyte distributions pixel by pixel.}

### 7.2 Mass Analyzers

206. {Which parameters characterize a mass analyzer?} : {Key parameters are m/z range, resolving power, mass accuracy, sensitivity, speed, and ability to perform tandem or multistage MS.}
207. {How is mass error expressed in parts per million?} : {Error_ppm = [(m/z_exp - m/z_theor)/(m/z_theor)] times 10^6.}
208. {What are the general strengths and limitations of a single quadrupole?} : {It is compact, inexpensive, and easy to operate but typically has resolution near 1000, range below m/z 2000, and mass error above 100 ppm.}
209. {How does a quadrupole filter ions?} : {Combined radio-frequency and direct-current potentials stabilize the trajectories of only selected m/z values through four rods.}
210. {What happens when quadrupole U and V are scanned at constant ratio?} : {The stable m/z window moves through the spectrum, whereas changing U/V changes window width and U = 0 makes the device an ion guide.}
211. {What is quadrupole scan mode?} : {Scan mode varies the quadrupole potentials sequentially so a spectrum across many m/z values is recorded.}
212. {What is selected-ion monitoring?} : {SIM fixes the quadrupole to selected m/z values for sensitive and selective quantitation but provides little structural information.}
213. {Why can a single quadrupole fail to distinguish isobaric molecules after soft ionization?} : {Isobars can produce the same intact-ion m/z without a diagnostic fragmentation pattern.}
214. {What are the functions of Q1, q2, and Q3 in a triple quadrupole?} : {Q1 selects a precursor, q2 collisionally fragments it, and Q3 analyzes or selectively transmits product ions.}
215. {What is a product-ion scan?} : {Q1 transmits one precursor while Q3 scans all products formed by collision-induced dissociation.}
216. {What is multiple-reaction monitoring?} : {MRM fixes Q1 and Q3 on a specific precursor-to-product transition for highly sensitive, selective, and wide-range quantitation.}
217. {How does tandem MS in a triple quadrupole differ from an ion trap?} : {A triple quadrupole performs MS/MS in space as ions pass through successive regions, whereas an ion trap performs MSn sequentially in time.}
218. {How does an ion trap conduct an MSn experiment?} : {It accumulates ions, isolates a precursor by ejecting other masses, fragments the precursor, stores products, and can repeat isolation and fragmentation before detection.}
219. {What are the strengths and limitations of an ion trap?} : {Ion accumulation gives high scan sensitivity and MSn capability, but space-charge effects impair quantitation, resolution, and mass accuracy at high ion load.}
220. {What are typical ion-trap performance values?} : {The lecture gives resolution near 2000, mass range below m/z 4000, and mass error above 100 ppm.}
221. {How does an Orbitrap determine m/z?} : {It measures ion oscillation frequency in an electrostatic field, with frequency proportional to the square root of an instrumental constant divided by m/z.}
222. {What controls Orbitrap resolution?} : {Resolution depends mainly on transient measuring time and the instrument model.}
223. {What are typical Orbitrap capabilities?} : {Orbitraps provide good sensitivity, resolution up to roughly 500,000, range below about m/z 4000, and mass error below 2 ppm.}
224. {Why are electrostatic and magnetic sectors combined in double-focusing instruments?} : {Combining them corrects energy and directional dispersion to achieve resolution above 10,000 and improved mass accuracy.}
225. {Where are double-focusing sector instruments still especially important?} : {Their remaining major applications include isotope-ratio MS and high-resolution ICP-MS.}
226. {What is the operating principle of time-of-flight MS?} : {Equally accelerated ions traverse a field-free tube with flight time t = L sqrt[m/(2zV)], so lighter m/z ions arrive first.}
227. {Why is a reflectron used in TOF-MS?} : {It compensates kinetic-energy differences by making faster ions penetrate farther and travel longer paths, thereby improving resolution.}
228. {What are typical reflectron-TOF capabilities?} : {Reflectron TOF commonly provides resolution around 40,000, mass error below 2 ppm, rapid acquisition, and a theoretically unlimited mass range.}
229. {What is a hybrid mass spectrometer?} : {A hybrid combines analyzers with different operating principles, such as Q-TOF or a quadrupole or ion trap coupled to an Orbitrap.}

### 7.3 Detectors and Hyphenated Methods

230. {Which detectors are used with quadrupoles, ion traps, and sector instruments?} : {Secondary-electron multipliers with discrete dynodes and channel-electron multipliers with continuous dynodes convert ion impacts into amplified electrical signals.}
231. {Why are microchannel plates used in TOF-MS?} : {A microchannel plate is an array of channel multipliers that provides fast, position-wide ion detection suitable for pulsed TOF ion packets.}
232. {How does an FT-based MS detector work?} : {Oscillating ions induce an image current in an external electrode, and Fourier transformation converts the transient into frequencies and m/z values.}
233. {What information does a hyphenated GC-MS dataset provide?} : {It provides a total-ion chromatogram and a mass spectrum at each retention time or chromatographic peak.}
234. {Why is GC easily coupled to EI or CI mass spectrometry?} : {The gaseous GC effluent is readily pumped into vacuum and matches the gas-phase requirements of EI and CI.}
235. {Why does HPLC-MS require atmospheric-pressure ionization and volatile mobile phases?} : {The liquid effluent must be nebulized and desolvated before vacuum entry, so ESI or APCI is used and nonvolatile buffers such as phosphate are avoided.}
236. {Why must MS acquisition be fast in LC-MS?} : {A sufficiently high sampling rate is needed to record narrow chromatographic peaks without losing their separation, making fast analyzers such as TOF advantageous.}
237. {What interface is commonly used for CE-MS?} : {CE is commonly coupled to MS through an electrospray interface that transfers the low-flow capillary effluent into high vacuum.}

### 7.4 Information from Mass Spectra and Protein Identification

238. {What information can be obtained from a mass spectrum?} : {Isotope patterns reveal elemental composition and charge, accurate mass suggests formulas, and fragmentation reveals structural or sequence information.}
239. {How do chlorine and bromine isotope patterns aid identification?} : {Their characteristic M and M+2 abundance ratios, about 3:1 for chlorine and nearly 1:1 for bromine, reveal the number and type of halogen atoms.}
240. {How does the first 13C isotope peak relate to carbon count?} : {Its abundance relative to the monoisotopic peak increases roughly in proportion to the number of carbon atoms.}
241. {How can isotope spacing reveal charge state?} : {The spacing between the monoisotopic and first isotope peak is approximately 1/z, giving 1, 0.5, and 0.33 m/z for charges +1, +2, and +3.}
242. {How do nominal, monoisotopic, and molar mass differ?} : {Nominal mass sums integer isotope masses, monoisotopic mass sums exact masses of selected principal isotopes, and molar mass uses abundance-weighted atomic masses.}
243. {How does mass accuracy vary among common analyzers?} : {Ion traps and quadrupoles often exceed 100 ppm error, reflectron TOF reaches about 1-5 ppm, Orbitrap about 1 ppm, and FT-ICR below 1 ppm.}
244. {Why is accurate mass valuable for formula determination?} : {Lower mass error greatly reduces the number of elemental formulas consistent with a measured monoisotopic mass.}
245. {What can ultrahigh resolution reveal within an apparent isotope peak?} : {At resolution near 8 million it can separate different isotope combinations, such as 13C, 18O, 15N, and 34S substitutions with nearly equal nominal shifts.}
246. {How is the neutral mass of a multiply protonated ESI ion calculated?} : {For charge z, neutral mass is M = z[(m/z) - H], where H is the proton mass.}
247. {How can neighboring ESI charge states be deconvoluted?} : {Their m/z values are used to calculate the integer charge and then transform the charge envelope into a neutral-mass spectrum.}
248. {What are the two main MS strategies for identifying a protein after digestion?} : {Peptide-mass fingerprinting compares intact digest-peptide masses with database predictions, while tandem MS compares peptide fragment spectra or sequences.}
249. {What are the essential steps of tandem-MS protein identification?} : {A protein is enzymatically digested, peptide ions are measured, a precursor is selected and fragmented, and the product-ion pattern is searched or sequenced.}
250. {What are b and y peptide fragment ions?} : {Backbone cleavage produces N-terminal b ions and C-terminal y ions whose mass differences reveal amino-acid residue masses.}
251. {Why is residue mass smaller than free amino-acid mass?} : {In a peptide, residue mass equals amino-acid mass minus the elements of water lost during peptide-bond formation.}
252. {How does de novo peptide sequencing use a product-ion spectrum?} : {Successive differences within b- or y-ion series are matched to amino-acid residue masses to read the sequence from an end.}

## 8. Inductively Coupled Plasma Spectroscopy

253. {Why is ICP advantageous for elemental analysis?} : {Its very high temperature excites and ionizes nearly all elements, enabling sensitive multielement analysis unlike sequential single-element AAS.}
254. {How is an inductively coupled plasma generated?} : {Argon flows through concentric quartz tubes, a high-voltage spark supplies electrons, and an RF electromagnetic field accelerates them to sustain ionizing collisions.}
255. {What happens to a sample introduced into an ICP?} : {The plasma desolvates, atomizes, excites, and ionizes the sample so optical emission or mass-spectrometric detection can be used.}
256. {What are the main strengths and limitation of ICP-AES or ICP-OES?} : {It performs multielement analysis, but needs excellent wavelength dispersion and interference-free emission lines and is less sensitive than graphite-furnace AAS.}
257. {Why is wavelength choice critical in ICP-OES?} : {Emission lines from abundant matrix elements can overlap the analyte line, so an alternative wavelength may be required to avoid spectral interference.}
258. {How do flame AAS and graphite-furnace AAS compare?} : {Flame AAS is inexpensive but less sensitive and sample-intensive, whereas graphite-furnace AAS is sensitive and low-volume but usually measures one element at a time.}
259. {How do ICP-OES and ICP-MS compare?} : {ICP-OES offers lower-cost multielement measurement but needs more sample, whereas ICP-MS is costlier but provides much higher sensitivity and generally fewer spectral problems.}
260. {What role does ICP play in ICP-MS?} : {ICP acts as a powerful elemental ion source whose ions are extracted into a mass analyzer.}
261. {Which polyatomic interferences are typical in ICP-MS?} : {Examples include 40Ar16O+ on 56Fe+, 38ArH+ on 39K+, 40Ar+ on 40Ca+, 40Ar35Cl+ on 75As+, and chlorine-oxygen species on chromium or vanadium.}
262. {How can high-resolution ICP-MS handle spectral interferences?} : {Sufficient resolving power separates analyte and interfering ions that share nominal mass but differ in exact mass.}
263. {How does collision or reaction cell technology remove ICP-MS interferences?} : {A gas such as H2 or NH3 selectively reacts with or neutralizes polyatomic interferences while leaving the target elemental ion available for measurement.}
264. {What is laser-ablation ICP-MS?} : {A pulsed laser removes solid material, carrier gas transports the aerosol to the ICP, and MS measures its elemental composition.}
265. {How does laser ablation enable imaging and depth profiling?} : {Scanning across a surface maps lateral elemental intensity, while repeated pulses at one position measure composition with depth.}
