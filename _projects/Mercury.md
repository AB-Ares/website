---
layout: page
title: Mercury
description: 
img: assets/img/Mercury.png
importance: 1
category: planets
---

#### Preamble 
With ESA's 'BepiColombo currently en route for Mercury, there is a regain in interest for the innermost terrestrial planet. The crust of Mercury has been the stage for various geological processes, including volcanism, the formation of giant impact basins, but also global contraction and tectonic activity. Each of these processes has profoundly affected the structure, composition, and porosity of the crust. My work on Mercury consists of characterizing the structure of the crust and unravelling geodynamical evolution of the planet using geophysical models. 

#### Mercury's crustal porosity as constrained by the planet's bombardment history

Knowing the structure of the crust is critical to understanding a planet's geologic evolution. Crustal thickness inversions rely on bulk density estimates, which are primarily affected by porosity. Due to the absence of high-resolution gravity data, Mercury's crustal porosity has remained unknown. In [Broquet et al. (2024)](https://doi.org/10.1029/2024GL110583), we use a model that was calibrated to the Moon to relate Mercury's impact crater population and long-wavelength crustal porosity in the cratered terrains. Therein, porosity is created by large impacts and then decreased as the surface ages due to pore compaction by smaller impacts and overburden pressure. Our models fit independent gravity-derived porosity estimates in the northern regions, where data is well resolved. Porosity in the cratered terrains is found to be 9% to 18% with an average and standard deviation of 13±2%, indicating lunar-like crustal bulk densities of 2565±70 kg m-3 (Figure 1) from which updated crustal thickness maps are constructed.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/projects_img/Mercury_poro.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: Crustal porosity in cratered terrains for the best-fit lunar parameters (a) and for the model that best fits gravity-derived crustal porosities (b). Associated bulk density of the crust considering the above porosity maps and grain density estimates (c, d). The blue outline in (a) indicates basins with diameter >200 km and regions covered by major smooth plain units are masked out. 
</div>

#### Coupling geophysical inversions and machine learning to unveil Mercury's geodynamic history

Mercury’s tectonic record is dominated by compressive landforms including lobate scarps, high-relief ridges and wrinkle ridges. Previous analyses of these structures have constrained the planet’s thermal contraction to a range of either no more than 2 km or up to 7 km. This important discrepancy have strong implications for our understanding of Mercury’s geodynamic history and results from different interpretation of the tectonic record. In [Broquet & Andrews-Hanna (2024c)](https://www.hou.usra.edu/meetings/lpsc2024/pdf/2412.pdf) we improve upon previous work by considering the contribution of flexural strain to the tectonic record, proposing a consistent mapping of primary tectonic landforms, and making use of machine learning to analyze all compressive landforms rather than relying on displacement-length ratios (Figure 2). We show that when considering the entire tectonic record of Mercury, global contraction averages to 6.3 km. Removing small secondary ridges that are parallel and in close vicinity to a primary longer ridge reduces contraction to about 3.5 km, which is substantially higher than when neglecting wrinkle ridges (~1.2 km). Tectonic strain exhibits prominent lateral variation in all scenarios, with some regions experiencing near-zero contraction, while others recorded several kilometers of deformation. This is interpreted to be due to local plume-induced flood volcanism sequences, variable crustal heat production, or a change in the planet’s orbit and associated surface temperature. Our tectonic strain history indicates a period of rapid contraction from 4.1 to 3.9 Ga, followed by more steady cooling, which have implications the planet’s geodynamic history. Based on an inversion of present-day gravity and topography for crustal deformations, we show that flexural strain can counteract contractional strain as well as add to it. Although some regions with tectonic strain excess and deficit can be explained by local lithospheric flexure, the net effect of flexural strain on global contraction is negligible.
 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/projects_img/Mercury_tecto.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: Mercury tectonics and neural network mapping. A) Mercury’s digital terrain model (DTM, Becker et al. 2016) in Mollweide and polar projections showing the tectonic mapping of Klimczak et al. (2024) together with smooth plains (Denevi et al., 2013). B) Neural network ridge detection results for 3 example profiles. The elevation profile is displayed on the top and the detection probability is shown below. The red line delimits our boxcar fit to the distribution. Manually chosen ridge endpoints are indicated by the dots for comparison. 
</div>
