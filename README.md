# ecoevolutionary_mutualism

---

This repository contains the mathematica files for the analysis of the model presented in *"Eco-evolutionary logic of mutualisms"* by Chaitanya S. gokhale, Marcus Frean and Paul Rainey.

Corresponding PDF files of the Mathematica versions are also provided to make the code development accessible and replicable in a different language.

### Mathematica files

- **interintragamedynamics.nb	**
	- This files contains the basic model to generate the simple Stream Vector visialisations as shown in the manuscript
- **evopopulationdynamics.nb	**
	- Incuding population dynamics, this file take a bit longer to run... You can comment appropriate plots out if you do not want the detailed resolution
- **panelgeneration.nb	**
	- The appendix contains the details where we are not bound by the same interactions in the intra species game as in the fixed mutualistic interspecies game. This file takes the longest to run but generates a 4x4 panel denoting hte full factorial combination of the 4 intraspecies games for the two species
- **oscillating_p.nb**
	- We implement environmental fluctuations in a sinusoidal manner where the fluctuations control the impact of the inter vs intra game interactions on the fitness. Manipulating $a$ allows us to change the amplitude of the fluctuations.