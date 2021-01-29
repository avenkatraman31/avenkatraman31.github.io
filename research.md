## [Home](https://avenkatraman31.github.io/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Research](https://avenkatraman31.github.io/research.html)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Academics](https://avenkatraman31.github.io/academics.html)

## RESEARCH
My research interests include:
- Crystal Plasticity and Molecular Dynamics
- Uncertainty Quantification and Propagation, Verification, Validation
- Machine Learning 
- Bayesian Calibration

### Model parameter and Model form Uncertainty Quantification (UQ) for Crystal Plasticity Models for α+β Titanium alloys
#### Advisor: Prof. Surya Kalidindi and Prof. David McDowell

<details>
<summary>Description</summary>
We present a comprehensive framework for assessment of model parameter and model form uncertainty for Crystal Plasticity (CP) Models that describe the effective mechanical response of the lamellar colonies of  α+β Titanium alloys. This is motivated by the gaps that currently exist in the understanding of the effective constitutive response of the lamellar grains. This work involved
- CP-FE simulations of spherical nanoindentation to estimate the nanoindentation Yield for different sets of material properties
- Development of a Gaussian Process Regression (GPR) Surrogate Model for the Yield, as a function of the supplied material properties
- Bayesian calibration of the CP models using MCMC sampling by probing the GPR model using different configurations of material properties to estimate their optimum along with UQ
- Bayesian Model Selection for Model form Uncertainty Quantification 
- Estimation of Model discrepancy and correlation to deformation micromechanisms
</details>

##### Publication: Bayesian Analysis of Parametric Uncertainties and Model Form Probabilities for two different Crystal Plasticity Models of Lamellar Grains in Titanium alloys
<img src="https://avenkatraman31.github.io/lamellar.svg" 
alt="Workflow for the project" style="width: 800px;height: 600px;"/>

### Reduced-Order Models for Ranking Damage Initiation in Dual-Phase Composites Using Bayesian Neural Networks
#### Advisor: Prof. Surya Kalidindi
#### Collaborator: [Dr. David Montes de Oca Zapiain](https://scholar.google.com/citations?user=fbthy5AAAAAJ&hl=en)

<details>
<summary>Description</summary>
In this paper, we explore the merits of the application of the VBI–NN approach for building ROMs to capture the quantitative correlations between the microstructure and its resistance to damage initiation. Specifically, we demonstrate the viability of formulating a VBI–NN–ROM (i.e., variational Bayesian inference-incorporated feedforward neural network-based reduced-order model) that is able to accurately capture and reflect the microstructure sensitivity of the resistance to damage initiation of dual-phase composites in a rigorous probabilistic framework. The VBI–NN–ROM is critically validated by suitable comparisons with FE-based ground-truth estimation for selected, digitally created RVEs.
</details>

##### Publication: [Reduced-Order Models for Ranking Damage Initiation in Dual-Phase Composites Using Bayesian Neural Networks](https://doi.org/10.1007/s11837-020-04387-y)

<img src="https://avenkatraman31.github.io/damage.svg" 
alt="Workflow for the project" style="width: 1200px;height: 800px;"/>

### Masters' thesis: Hydrogen embrittlement in martensitic stainless steels
##### Advisor: [Prof. Ratna Kumar Annabattula](https://scholar.google.com/citations?hl=en&user=5oiU2GsAAAAJ&view_op=list_works&sortby=pubdate) , Department of Mechanical Engineering, IIT Madras.    

<details>
<summary>Description</summary>
My thesis involved the study of the effect of hydrogen on strength and toughness of metals. Specifically, I studied the localization of plastic strain around crack-like defects in pre-cracked specimens by modeling the interaction between mechanics and hydrogen diffusion. The material strength was degraded progressively based on a Hydrogen concentration dependent softening expression (which is a key idea in Hydrogen Enhanced Localized Plasticity or HELP). The computational results are compared with analytical and experimental data for validation. To further illustrate the validity of HELP, we have developed a crystal plasticity model for hydrogen diffusion to study the slip accumulation/dislocation pile-up near stress concentration zones. A parametric study is done to determine the orientation dependency of hydrogen diffusion, by varying the crystal lattice orientation. The results are shown to reasonably validate the HELP micromechanism for FCC metals.
</details>
<details>
	<summary>
		Images
	</summary>
<img src="https://avenkatraman31.github.io/hemb.JPG" 
alt="Algorithm for modeling the interaction between mechanics and hydrogen diffusion" style="width: 1200px;height: 800px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/crack.JPG" 
alt="Crack tip mesh in ABAQUS" style="width: 1200px;height: 800px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/ctodVsTime.JPG" 
alt="CTOD vs time illustrates Hydrogen induced degradation" style="width: 1200px;height: 800px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/JVsCtod.JPG" 
alt="J vs CTOD illustrates lower ductile fracture resilience" style="width: 1200px;height: 800px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</details>
-------------------------------------------------------------------------------
### Effect of particle size and inter-particle spacing on dislocation behaviour in Ni-based super alloys
##### Advisor: Prof. Anand Krishna Kanjarla , Department of Metallurgical and Materials Engineering, IIT Madras.    

Ni-based superalloys are very useful for high-temperature applications because of their strength retention capabilities and relatively high creep compliance. The shape of the precipitates (Ni3Al) is usually in the form of thin plate-like structure or cuboidal when the fraction of the volume occupied by the precipitate is moderately high. The interaction of dislocations with precipitates can result in climb, bow-out (the so-called orowan bowing) or it could result in the cutting of the precipitate by the dislocation.    
While precipitation hardening has been studied extensively using continuum mechanics, its underlying mechanism in the atomistic scale has not been investigated satisfactorily. The continuum assumption makes use of both long-range and short range forces (ie), those that arise from the intrinsic stress field associated with a screw/edge dislocation or those that arise from the interaction of the dislocation and the particle, which are in turn, thought to originate from the mismatch of the elastic properties between the matrix and precipitate phases. The short-range interactions were studied using the LAMMPS molecular dynamics package. The MD simulations have been done to simulate the effect of precipitate on matrix mechanical properties. The generation of stacking faults and misfits have been investigated and the subsequent strengthening effect has been explained reasonably well, within the confines of the simulation box, by plotting stress-strain response. The strength has been shown proportional to particle size and inter-particle distance. This, to an extent, explains precipitation hardening. 

<img src="https://avenkatraman31.github.io/eps_1.PNG" 
 alt="boundary conditions" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://avenkatraman31.github.io/eps_2.PNG" alt="boundary conditions" style="width: 400px;height: 400px;"/>
