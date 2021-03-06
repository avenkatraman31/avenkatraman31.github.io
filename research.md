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
(1) CP-FE simulations of spherical nanoindentation to estimate the nanoindentation Yield for different sets of material properties, (2) Development of a Gaussian Process Regression (GPR) Surrogate Model for the Yield, as a function of the supplied material properties, (3) Bayesian calibration of the CP models using MCMC sampling by probing the GPR model using different configurations of material properties to estimate their optimum along with UQ, (4) Bayesian Model Selection for Model form Uncertainty Quantification,(5) Estimation of Model discrepancy and correlation to deformation micromechanisms
</details>

##### Publication: Bayesian Analysis of Parametric Uncertainties and Model Form Probabilities for two different Crystal Plasticity Models of Lamellar Grains in Titanium alloys
<details>
	<summary>
		Workflow for the project
	</summary>
	<img src="https://avenkatraman31.github.io/lamellar.svg" 
alt="Workflow for the project" style="width: 800px;height: 600px;"/>
</details>

<img src="https://avenkatraman31.github.io/lamellar2.svg" 
alt="Workflow for the project" style="width: 1200px;height: 800px;"/>


### Reduced-Order Models for Ranking Damage Initiation in Dual-Phase Composites Using Bayesian Neural Networks
#### Advisor: Prof. Surya Kalidindi
#### Collaborator: [Dr. David Montes de Oca Zapiain](https://scholar.google.com/citations?user=fbthy5AAAAAJ&hl=en)

<details>
<summary>Description</summary>
In this paper, we explore the merits of the application of the VBI–NN approach for building ROMs to capture the quantitative correlations between the microstructure and its resistance to damage initiation. Specifically, we demonstrate the viability of formulating a VBI–NN–ROM (i.e., variational Bayesian inference-incorporated feedforward neural network-based reduced-order model) that is able to accurately capture and reflect the microstructure sensitivity of the resistance to damage initiation of dual-phase composites in a rigorous probabilistic framework. The VBI–NN–ROM is critically validated by suitable comparisons with FE-based ground-truth estimation for selected, digitally created RVEs.
</details>

##### Publication: [Reduced-Order Models for Ranking Damage Initiation in Dual-Phase Composites Using Bayesian Neural Networks](https://doi.org/10.1007/s11837-020-04387-y)
<details>
	<summary>Workflow for the project</summary>
<img src="https://avenkatraman31.github.io/damage.svg" 
alt="Workflow for the project" style="width: 1600px;height: 800px;"/>
</details>



### Texture-sensitive prediction of micro-spring performance using Gaussian process models calibrated to finite element simulations
#### Advisor: Prof. Surya Kalidindi
#### Collaborator: [Dr. David Montes de Oca Zapiain](https://scholar.google.com/citations?user=fbthy5AAAAAJ&hl=en)

<details>
<summary>Description</summary>
This project explores benefits of building a computationally low-cost surrogate model relating the mechanical performance of micro-springs to crystallographic texture and single-crystal elastic constants. This task is accomplished by leveraging advances in (i) computationally-expensive finite element (FE) models that explicitly incorporates the constitutive response of individual grains in to simulate the overall mechanical response of the micro-spring, (ii) efficient parametrization of the extremely large space of textures using Fourier basis (i.e., generalized spherical harmonics), (iii) sequential design of FE simulations to maximize model fidelity while also minimizing the overall computational expense incurred in generating the data, and (iv) the use of Gaussian process models for incorporating uncertainty quantification into the development of the desired surrogate model. The strategy implemented in this work proved to be remarkably efficient in producing the desired surrogate model. The utility of the surrogate model established in this work is demonstrated with a case study addressing an inverse solution for the specific crystallographic texture that maximizes the micro-spring performance for a selected material, resulting in an 80% improvement.
</details>

##### Publication: [Texture-sensitive prediction of micro-spring performance using Gaussian process models calibrated to finite element simulations](https://doi.org/10.1016/j.matdes.2020.109198)

<img src="https://avenkatraman31.github.io/microspring.jpg" 
alt="Workflow for the project" style="width: 1000px;height: 500px;"/>

### Masters' thesis: Hydrogen embrittlement in martensitic stainless steels
#### Advisor: [Prof. Ratna Kumar Annabattula](https://scholar.google.com/citations?hl=en&user=5oiU2GsAAAAJ&view_op=list_works&sortby=pubdate) , Department of Mechanical Engineering, IIT Madras.    

<details>
<summary>Description</summary>
My thesis involved the study of the effect of hydrogen on strength and toughness of metals. Specifically, I studied the localization of plastic strain around crack-like defects in pre-cracked specimens by modeling the interaction between mechanics and hydrogen diffusion. The material strength was degraded progressively based on a Hydrogen concentration dependent softening expression (which is a key idea in Hydrogen Enhanced Localized Plasticity or HELP). The computational results are compared with analytical and experimental data for validation. To further illustrate the validity of HELP, we have developed a crystal plasticity model for hydrogen diffusion to study the slip accumulation/dislocation pile-up near stress concentration zones. A parametric study is done to determine the orientation dependency of hydrogen diffusion, by varying the crystal lattice orientation. The results are shown to reasonably validate the HELP micromechanism for FCC metals.
</details>

<details>
	<summary>
		Images
	</summary>
<img src="https://avenkatraman31.github.io/hemb.JPG" 
alt="Algorithm for modeling the interaction between mechanics and hydrogen diffusion" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/crack.JPG" 
alt="Crack tip mesh in ABAQUS" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/ctodVsTime.JPG" 
alt="CTOD vs time illustrates Hydrogen induced degradation" style="width: 300px;height: 300px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://avenkatraman31.github.io/JVsCtod.JPG" 
alt="J vs CTOD illustrates lower ductile fracture resilience" style="width: 300px;height: 300px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</details>

### Effect of particle size and inter-particle spacing on dislocation behaviour in Ni-based super alloys using Molecular Dynamics
##### Advisor: Prof. Anand Krishna Kanjarla , Department of Metallurgical and Materials Engineering, IIT Madras.    

<details>
	<summary>
		Description
	</summary>
Ni-based superalloys are very useful for high-temperature applications because of their strength retention capabilities and creep compliance. At moderate volume fractions, the shape of the precipitates (Ni3Al) is usually in the form of thin plate-like structures or cuboids when the fraction of the volume occupied by the precipitate is moderately high. The interaction of dislocations with precipitates can result in climb, bow-out (the so-called orowan bowing) or it could result in the shearing of the precipitate by the dislocation.    
While precipitation hardening has been studied extensively using continuum mechanics, its underlying mechanism in the atomistic scale has not been investigated satisfactorily. The continuum assumption makes use of both long-range and short range forces (ie), those that arise from the intrinsic stress field associated with a screw/edge dislocation or those that arise from the interaction of the dislocation and the particle, which are in turn, thought to originate from the mismatch of the elastic properties between the matrix and precipitate phases. The short-range interactions were studied using the LAMMPS molecular dynamics package. The MD simulations have been done to simulate the effect of precipitate on matrix mechanical properties. The generation of stacking faults and misfits have been investigated and the subsequent strengthening effect has been explained reasonably well, within the confines of the simulation box, by plotting stress-strain response. The strength has been shown proportional to particle size and inter-particle distance. In addition, an estimate of the critical distance for precipitate shearing has been calculated. 
</details>

##### Publication: [Effect of particle size and inter-particle spacing on dislocation behaviour of Nickel based super alloys](https://arxiv.org/abs/1707.04398)

<details>
	<summary>
		Images
	</summary>
	<img src="https://avenkatraman31.github.io/eps_1.PNG" 
	 alt="boundary conditions" style="width: 400px;height: 400px;"/>
 	<img src="https://avenkatraman31.github.io/eps_2.PNG" alt="Orowan Bowing" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://avenkatraman31.github.io/sfault.jpg" alt="Stacking Fault" style="width: 400px;height: 400px;"/>
</details>