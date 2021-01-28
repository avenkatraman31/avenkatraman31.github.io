



## [Home](https://avenkatraman31.github.io/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Research](https://avenkatraman31.github.io/research.html)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Academics](https://avenkatraman31.github.io/academics.html)

## RESEARCH
The areas that I'm interested in include:
- Plasticity and fracture mechanics
- Micromechanics  
- Multi-scale modeling of materials 
- Molecular Dynamics  


### Modeling of Dynamic Recrystallization
##### Advisor: Prof. Yung Shin - _Donald A. and Nancy G. Roach Professor of Advanced Manufacturing_, Department of Mechanical Engineering, Purdue University

One of the techniques available for improving strength as well as ductility is grain refinement via _Severe Plastic deformation_ (SPD) which results in _Ultra-Fine Grained_ (UFG) structures. The evolution of micrometer sized grains into grains that are a few hundred nanometer in size has been well documented via experiments on various metals and alloys. However, the empirical relationship between the grain-size and accumulated plastic strains is specific to that metal and hence a physics based model is necessary to to better design and optimize a multi-pass cold rolling process for producing a desirable cold rolled microstructure. Typical modelling efforts in the high temperature regime follow dislocation theories. These approaches are mostly basedon stress-dislocation relations and kinematics of the dynamic recovery (DRV) and dynamic recrystallization (DRX). Materials whose dislocations are able to cross-slip and climb can easily rearrange into polygonal sub-grain structures and tend to display a high degree of DRV, while materials with low stacking fault energy show a much lower level of DRV. In the latter case, dislocation density rises until it reaches a critical condition, at which point new grains nucleate and grow during further straining. Based on dislocation theory, I developed a macroscale-mesoscale model in Abaqus using a user-defined hardening subroutine "**VUHARD**" to study the evolution to plastic strains, grain size and dislocation density for multi-pass hot rolling of commercially pure Titanium (Cp-Ti) and Aluminium Alloy -1200 (AA-1200). I developed a Lagrangian model for Cp-Ti and Eulerian model for AA-1200. I was able to demonstrate grain refinement during multi-pass hot rolling and also recrystallization induced softening. Please do look at my report for further details:

#####Report: [Modeling of dynamic recrystallization](https://adityavenkatraman.github.io/SUMMER INTERNSHIP REPORT.pdf)

#####Snippets from my report  
<img src="https://AdityaVenkatraman.github.io/peeq.PNG" 
alt="Plastic strain" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://AdityaVenkatraman.github.io/grain size.PNG" 
alt="grain size" style="width: 400px;height: 380px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://AdityaVenkatraman.github.io/graph_1.PNG" 
alt="graphs_1" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  
_Predictive modeling considering only DRV._  
_Discrepancy between measured and predicted values_   
_is due to recrystallization._  
-------------------------------------------------------------------------------

###Particle Reinforced Plasticity
#####Advisor: Prof.Shyam Keralavarma, Dept. of Aerospace Engineering, IIT Madras.

Hard particles such as oxides and carbides can only deform elastically. They are used as dopants/deliberate inclusions in soft materials. Their constraint power is much larger than that of the soft matrix which is typically some epoxy resin. When subjected to a load, due to their relatively higher strength, their load sharing capability is also enhanced. The reduction of the load carried by the matrix results in an overall reduction in the plastic strain in the matrix. Moreover, the overall plastic strain in the specimen is reduced because of the reduction in the volume fraction of the matrix in comparison to the overall composite. These effects increase the effective strain hardening parameters of the system.  
This theory is developed to determine the elasto-plastic behaviour of particle reinforced composites. The considered material is a composite with elastic spherical particles dispersed uniformly in a ductile work hardening matrix. This theory combines the Mori Tanaka’saverage stress method and Hill’s(1965) discovery of decreasing constraint power of matrix in polycrystal plasticity. It is approximated that the decreasing constraint power of matrix can be characterized using the secant Elastic moduli of the matrix. The stress and strain of the matrix is assumed to follow the modified Ludwik equation.In a composite usually the hard particles are the load carrying members and reduce the stress carried by the matrix. We have assumed that the plastic strain is carried only by the matrix and hence its magnitude depends on the volume fraction of the particles. Based on the Eshelby’s (1957) solution of an ellipsoidal inclusion and Mori Tanaka’s(1973) concept of average stress in the matrix, the average stress and strain in the particles are determined using Eshelby’s equivalence principle. Computation of the effective properties by means of MATLAB and also verification with Abaqus is done. Please look at my report for further details:

#####Report: [Particle reinforced plasticity](https://adityavenkatraman.github.io/PARTICLE REINFORCED PLASTICITY final.pdf)

#####Snippets from my report

<img src="https://AdityaVenkatraman.github.io/prp_1.PNG" 
alt="boundary conditions" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://AdityaVenkatraman.github.io/prp_2.PNG" alt="s33_pe33" style="width: 400px;height: 380px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://AdityaVenkatraman.github.io/prp_3.PNG" 
alt="pl_vol" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  

-------------------------------------------------------------------------------


### Hydrogen embrittlement in martensitic stainless steels
##### Advisor: Prof. Ratna Kumar Annabattula , Department of Mechanical Engineering, IIT Madras.    

-------------------------------------------------------------------------------
### Effect of particle size and inter-particle spacing on dislocation behaviour in Ni-based super alloys
##### Advisor: Prof. Anand Krishna Kanjarla , Department of Metallurgical and Materials Engineering, IIT Madras.    

Ni-based superalloys are very useful for high-temperature applications because of their strength retention capabilities and relatively high creep compliance. The shape of the precipitates (Ni3Al) is usually in the form of thin plate-like structure or cuboidal when the fraction of the volume occupied by the precipitate is moderately high. The interaction of dislocations with precipitates can result in climb, bow-out (the so-called orowan bowing) or it could result in the cutting of the precipitate by the dislocation.    
While precipitation hardening has been studied extensively using continuum mechanics, its underlying mechanism in the atomistic scale has not been investigated satisfactorily. The continuum assumption makes use of both long-range and short range forces (ie), those that arise from the intrinsic stress field associated with a screw/edge dislocation or those that arise from the interaction of the dislocation and the particle, which are in turn, thought to originate from the mismatch of the elastic properties between the matrix and precipitate phases. The short-range interactions were studied using the LAMMPS molecular dynamics package. The MD simulations have been done to simulate the effect of precipitate on matrix mechanical properties. The generation of stacking faults and misfits have been investigated and the subsequent strengthening effect has been explained reasonably well, within the confines of the simulation box, by plotting stress-strain response. The strength has been shown proportional to particle size and inter-particle distance. This, to an extent, explains precipitation hardening. 

<img src="https://AdityaVenkatraman.github.io/eps_1.PNG" 
 alt="boundary conditions" style="width: 400px;height: 400px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://AdityaVenkatraman.github.io/eps_2.PNG" alt="boundary conditions" style="width: 400px;height: 400px;"/>
