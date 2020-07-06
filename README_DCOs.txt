Description
README file for allDoubleCompactObjects_**.dat files of STROOPWAFEL publicly available data. 


Any work making use of these simulations should cite:

https://arxiv.org/abs/1905.00910
Broekgaarden et all. 2019

STROOPWAFEL: Simulating rare outcomes from astrophysical populations, 
with application to gravitational-wave sources. 
Authors: Floor S. Broekgaarden, Stephen Justham, Selma E. de Mink, Jonathan Gair, Ilya Mandel, Simon Stevenson, Jim W. Barrett, Alejandro Vigna-Gómez, Coenraad J. Neijssel

For any queries, email:

fsbroekgaarden@gmail.com
compas@star.sr.bham.ac.uk 

|------------------------------------------------------------------------------------------|
Content
allDoubleCompactObjects_**.dat

File headers
1st line:	dimension of quantity, e.g.: # for adimensional, AU for astronomical unit, etc.
2nd line:	type of variable, e.g.: int for integer, bool for boolen, etc.
3rd line:	name of the variable, e.g.: separationInitial for initial separation, stellarType1 for stellar type of the primary, etc.


XX) NAME			#-- type. Description [units]

01) ID						#-- int. Non unique identifier in COMPAS [adim]
02) seed					#-- int. Unique identifier in COMPAS [adim]
03) separationInitial		#-- float. ZAMS semi major axis [AU]
04) eccentricityInitial		#-- float. ZAMS eccentricity [adim]
05) separationPrior2ndSN	#-- float. Semi major axis at the moment of the second supernova [AU]
06) eccentricityPrior2ndSN	#-- float. Eccentricity at the moment of the second supernova [adim]
07) relativeVelocity2ndSN	#-- float. Relative orbital velocity at the moment of the second supernova in [km s^-1]
08) separationDCOFormation	#-- float. Semi major axis at double compact object formation in [AU]
09) eccentricityDCOFormation#-- float. Eccentricity at double compact object formation [adim]
10) Metallicity1			#-- float. Fractional metallicity 0.0 < Z < 1.0 of primary star. Zsol = 0.02 [adim]
11) Metallicity2			#-- float. Fractional metallicity 0.0 < Z < 1.0 of secondary star. Zsol = 0.02 [adim]
12) M1ZAMS                  #-- float. ZAMS mass of initially more massive star [Msol]
13) totalMassDCOFormation1	#-- float. Total mass of star 1 at DCO formation [Msol]
14) HeCoreMassDCOFormation1	#-- float. Helium core mass of star 1 at DCO formation [Msol]
15) COCoreMassDCOFormation1	#-- float. Carbon-Oxygen core mass of star 1 at DCO formation [Msol]
16) coreMassDCOFormation1	#-- float. core mass of star 1 at DCO formation [Msol]
17) HeCoreMassCE1			#-- float. Helium core mass of star 1 at common envelope [Msol]
18) COcoreMassCE1			#-- float. Carbon-Oxygen core mass of star 1 at common envelope [Msol]
19) coreMassCE1				#-- float. Core mass of star 1 at common envelope [Msol]
20) drawnKick1				#-- float. Kick velocity drawn at SN of star 1 [km s^-1]
21) thetaSupernova1			#-- float. Polar angle between the SN kick velocity of the primary and the pre-SN orbital plane [adim]
22) phiSupernova1			#-- float. Azimuthal angle between the between the pre-SN orbital velocity and the SN kick velocity of the primary [adim]	
23) M1						#-- float. Final compact object mass of initially more massive star in [Msol] 
24) stellarType1			#-- int. Final stellar type of initially more massive star (according to Hurley et al 2000). NS = 13, BH = 14 [adim]
25) M2ZAMS					#-- float. ZAMS mass of initially less massive star [Msol]
26) totalMassDCOFormation2	#-- float. Total mass of star 2 at DCO formation [Msol]
27) HeCoreMassDCOFormation2	#-- float. Helium core mass of star 2 at DCO formation [Msol]
28) COCoreMassDCOFormation2	#-- float. Carbon-Oxygen core mass of star 2 at DCO formation [Msol]
29) coreMassDCOFormation2	#-- float. core mass of star 2 at DCO formation [Msol]
30) HeCoreMassCE2			#-- float. Helium core mass at common envelope [Msol]
31) COCoreMassCE2			#-- float. Carbon-Oxygen core mass of star 2 at common envelope [Msol]
32) coreMassCE2				#-- float. core mass at common envelope [Msol]
33) drawnKick2				#-- float. Kick velocity drawn at SN of star 2 [km s^-1]
34) thetaSupernova2			#-- float. Polar angle between the SN kick velocity of the secondary and the pre-SN orbital plane [adim]
35) phiSupernova2			#-- float. Azimuthal angle between the between the pre-SN orbital velocity and the SN kick velocity of the secondary [adim]
36) M2						#-- float. Final compact object mass of initially less massive star [Msol]
37) stellarType2			#-- int. Final stellar type of initially less massive star (according to Hurley et al 2000). 13 = NS, 14 = BH [adim]
38) tc						#-- float. Coalescence time due to gravitational wave emission from time of double compact object formation [Myrs]
39) tform					#-- float. Time to formation of double compact object [Myrs]
40) flbv					#-- float. Multiplicative constant for Luminous Blue Variable (LBV) mass loss rates [adim]
41) sigmaKick				#-- float. 1D SN kick velocity dispersion hyper parameter [km s^-1]
42) CEalpha					#-- float. Common envelope alpha hyper parameter [adim]
43) kickDirectionPower		#-- float. Hyper parameter describing SN kick direction distribution [adim]
44) wolfRayetMultiplier		#-- float. Multiplicative constant for Wolf Rayet (WR) mass loss rates [adim]
45) RLOFSecondaryAfterCEE	#-- bool. Whether the secondary experiences RLOF after Common Envelope Event [adim]
46) PrimaryMTCase			#-- int. Primary Mass Transfer (MT) case. 0 = no mass transfer, 1 = case A, 2 = case B, 3 = case C [adim]
47) SecondaryMTCase			#-- int. Secondary Mass Transfer (MT) case. 0 = no mass transfer, 1 = case A, 2 = case B, 3 = case C [adim]
48) preSNeOrbitalEnergy1	#-- float. PreSN  Orbital energy [Msol AU^2 yr^-2]
49) postSNeOrbitalEnergy1	#-- float. PostSN Orbital energy [Msol AU^2 yr^-2]
50) preSNeOrbitalEnergy2	#-- float.  PreSN  Orbital energy [Msol AU^2 yr^-2]
51) postSNeOrbitalEnergy2	#-- float. PostSN Orbital energy [Msol AU^2 yr^-2]
52) CEflag					#-- bool. True if the system experienced at least one Common Envelope Event [adim]
53) lambda1CE				#-- float. Lambda parameter describing envelope binding energy for star 1 [adim]
54) lambda2CE				#-- float. Lambda parameter describing envelope binding energy for star 2 [adim]
55) EccentricityPreCEE		#-- float. Eccentricity before Common Envelope Event [adim]
56) EccentricityPostCEE		#-- float. Eccentricity after Common Envelope Event [adim]
57) SemiMajorAxisPreCEE		#-- float. Semi-major axis before Common Envelope Event [Rsol]
58) SemiMajorAxisPostCEE	#-- float. Semi-major axis after Common Envelope Event [Rsol]
59) RL1to2PreCEE			#-- float. Roche lobe as seen by the primary (q=M1/M2) at the onset of the Common Envelope Event [Rsol]
60) RL1to2PostCEE			#-- float. Roche lobe as seen by the primary (q=M1/M2) after the envelope has been expelled in a Common Envelope Event [Rsol]
61) RL2to1PreCEE			#-- float. Roche lobe as seen by the secondary (q=M2/M1) at the onset of the Common Envelope Event [Rsol]
62) RL2to1PostCEE			#-- float. Roche lobe as seen by the secondary (q=M2/M1) after the envelope has been expelled in a Common Envelope Event [Rsol]
63) optimisticCEFlag		#-- bool. True if any of the stars did not have a clear core-envelope separation (optimistic) during a Common Envelope Event [adim]
64) mergesInHubbleTimeFlag	#-- bool. True if the DCO has a coalescence time less than a Hubble time [adim]
65) doubleCommonEnvelopeFlag#-- bool. True if the binary experiences a double-core common envelope phase at some point during its evolution [adim]
66) bindingEnergyCEEStar1	#-- float. Energy of the star calculated using the lambda1CE parameter [ergs]
67) bindingEnergyCEEStar2	#-- float. Binding energy of the star calculated using the lambda2CE parameter [ergs]
68) recycledPrimary			#-- bool. True if the primary is a NS and there is stable mass transfer onto it [adim]
69) recycledSecondary		#-- bool. True if the secondary is a NS and there is stable mass transfer onto it [adim]
70) USSNPrimary				#-- bool. True if there was mass transfer from a HeHG/HeGB primary donor to a secondary NS [adim]
71) USSNSecondary			#-- bool. True if there was mass transfer from a HeHG/HeGB secondary donor to a primary NS [adim]
72) ECSNPrimary				#-- bool. True if the primary exploded via ECSN [adim]
73) ECSNSecondary			#-- bool. True if the secondary exploded via ECSN [adim]