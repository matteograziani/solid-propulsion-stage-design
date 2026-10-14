# Preliminary Design and Optimization of a High-Thrust Solid Rocket Propulsion Stage

Project developed within the Aerospace Propulsion Laboratory course (Bachelor's Degree Thesis in Aerospace Engineering at Politecnico di Milano, A.Y. 2024–2025).

## Project Overview
This work addresses the preliminary sizing and optimization of a high-thrust solid propellant stage based on a star-perforation grain configuration. The main objective was to design a configuration capable of delivering an average thrust of 3 MN over a burning duration of 65 seconds, complying with strict geometric, structural, and mass constraints while achieving a neutral combustion profile.

## Tools and Methodologies
* **Thermodynamic Modeling:** Integration of NASA CEA (Chemical Equilibrium with Applications) to model isentropic nozzle expansion and chemical equilibrium analysis (full shifting in the throat and frozen equilibrium in the divergent section).
* **Numerical Codes (MATLAB):** Development of dedicated scripts for the geometric design of the star grain (`design_opt`), forward Euler numerical integration for pressure and thrust transients (`iter_plus`), and piecewise least-squares polynomial approximation of thermodynamic parameters to reduce computational overhead.
* **Optimization Analysis:** Implementation of iterative algorithms to maximize volumetric efficiency (~0.77), port length-to-diameter ratio ($L_p/D_{ch}$), and thrust profile neutrality.

## Alternative Propellant Formulations
The project compares the baseline mixture against three alternative solid propellant formulations:
1. **Eco-friendly formulation:** Partial replacement of ammonium perchlorate (AP) with ammonium nitrate (AN) to reduce HCl emissions.
2. **High burning rate formulation:** Utilization of nano-aluminum to enhance reactivity and accelerate the burning rate.
3. **Tailored burning rate formulation:** Combined use of micro and nano-aluminum to control condensate particle size and improve the thermodynamic expansion efficiency.

## Case Study and Thermal Sensitivity
* **Case Structural Analysis:** Sizing of internal layers (liner, Ta-Hf-C thermal insulation film, and advanced composite structural shell made of Graphite IM), resulting in a total dry mass of approximately 3000 kg, well within project limits.
* **Thermal Sensitivity:** Study of the influence of the initial grain temperature ($T_0$) on ballistic performance and chamber pressure, verifying the invariance of the total impulse.

## Authors
* Graziani Matteo Marwan
* Grillo Guido
* Guerrieri Mattia
* Guidi Michele

*Advisor:* Prof. Christian Paravan  
*Co-advisors:* Valerio Santolini  
*(Politecnico di Milano - School of Industrial and Information Engineering)*
