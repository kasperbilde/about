# About me
My name is Kasper Bilde and I live in Denmark with my spouse and our son.
I have a large interest in computational fluid dynamics which I've been using to
study particle-laden flows and turbulence. I strive to use open-source software
whenever it makes sense and is available.

## Employment
2020-Present: Industrial PhD Student, Alfa Laval Aalborg.
2019-2020: R&D Engineer, Alfa Laval Aalborg.
2017-2019: Engineering student assistant, Aalborg Energie Technik A/S

## Education

2020-2022: PhD student at Aalborg University on particle agglomeration and breakage for fast sedimentation processes
onboard marine vessels using CFD-PBM.

2017-2019: M.Sc. in Thermal Energy and Process Engineering at Aalborg University.
Master's thesis on dynamic start-up of natural circulation boilers.

2014-2017: B.Sc. in Energy Engineering at Aalborg University

## Publications
Schlegel, Fabian, Bilde, Kasper Gram, Draw, Mazen, Evdokimov, Ilya, Hänsch, Susann, Khan, Harris, … Tekavčič, Matej. (2022, March 23). HZDR Multiphase Addon for OpenFOAM (Version 4.0.0). Rodare. http://doi.org/10.14278/rodare.1496

Bilde, Kasper Gram, Kim Sørensen, and Thomas Condra. *"Mathematical model of natural circulation biomass boilers during start-up."* International Journal of Heat and Mass Transfer 143 (2019) DOI: [10.1016/j.ijheatmasstransfer.2019.118477](https://www.sciencedirect.com/science/article/pii/S0017931019323774?casa_token=k0BnqqdakcsAAAAA:J_RHdbNKhoUzuwdCGpwcwlf0o-00fnMiK_W7hJhvpXXzlvktrrVS3SmHgwB2Xl9_Ns0KT2lE-w)


Find me on my socials:

<a href="https://www.linkedin.com/in/kasper-gram-bilde/" target="_blank"><img src="imgs/linkedin.svg" alt="drawing" height="30"/></a>

# Projects
In this list some of the challenging and fun projects that I have worked on
during the past years.

## Agglomeration and breakage of particles in turbulent flows
Marine scrubbers are used to clean the exhaust gas of the engine for SOx and as
a bi-product, approximately 40% of the particulate mass is transferred from the
gas phase to the water phase inside the scrubber. Before this scrubber water can
be discharged into the Oceans when operating in closed-loop mode, the water needs
to be cleaned. As space onboard a vessel is sparse, high-speed separators are
utilised for an efficient separation of solids. The most dominating factor when
working with sedimentation is the particle size, as the settling velcocity is
highly dependent on the particle size. Therefore, I am developing a framework
for predicting particle aggregation and breakage in turbulent flows for industrial
applications.

As the particles are micron-sized, a CFD-PBM (population balance modelling) approach
is adopted in the Euler-Euler framework. The PBE (population balance equation)
is used to track the number density function and interfacial momentum exchange models
are applied between the phases. A breakage- and aggregation kernel is developed
and adopted into `OpenFOAM`. Several models and a tutorial case has been comitted
and accepted by The OpenFOAM Foundation. <a href="https://github.com/OpenFOAM/OpenFOAM-dev/commit/0999cd0efea8811f6d98c631f5ff3a53f6efb2d9" target="_blank">Link for the tutorial.</a>

An example of the particle size through a turbulent pipe flocculator is seen in the video below.
<video controls width=100%>
    <source src="https://github.com/kasperbilde/openfoam-workshop/blob/main/visuals/developmentwork.mp4"
            type="video/mp4">
</video>

## Cloud computing in Azure
    1. Management of Ubuntu virtual machine for department


# Software
1. OpenFOAM
1. Matlab
1. LIGGGHTS (+CFDEM)
1. Git

# Presentations
A list of public available presentations are seen in this list.

## 17th OpenFOAM Workshop.
The topic of the presentation was on the aggregation and breakage of particles
through a turbulent 90 degree pipe bend.
<a href="https://kasperbilde.github.io/openfoam-workshop/" target="_blank">Click here</a> to start the presentation.