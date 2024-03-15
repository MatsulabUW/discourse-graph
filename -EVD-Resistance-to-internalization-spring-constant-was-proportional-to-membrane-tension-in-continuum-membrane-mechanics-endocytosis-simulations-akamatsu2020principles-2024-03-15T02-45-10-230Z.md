# [[EVD]] - Resistance to internalization (spring constant) was proportional to membrane tension in continuum membrane mechanics endocytosis simulations - [[@akamatsu2020principles]]
## Evidence Statement [🛈](https://roamresearch.com/#/app/akamatsulab/page/wn1c13SwK)  

## Evidence Description [🛈](https://roamresearch.com/#/app/akamatsulab/page/m2cRZ6Os5)  

## Snippets [🛈](https://roamresearch.com/#/app/akamatsulab/page/bloFHUOCc)  
  - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fakamatsulab%2F_GXT1ebBmb.gif?alt=media&token=ca26aaac-6252-47cd-a153-be8afc8f0be8)  
  - Fig 1(C)![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fakamatsulab%2FnxV9AxV3O8.png?alt=media&token=3ba79193-23e4-4a5b-b1dd-986fe6387375)  
  - Fig1(D) ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fakamatsulab%2FEYlzMTgTj4.png?alt=media&token=10050ad5-59c2-46ec-89a4-5de1d421e9e4)  
    - {{video: https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fakamatsulab%2FHfL0kwnHFI.mp4?alt=media&token=af645f73-8934-4758-a487-688ab262a45e}}  
  -   

## Grounding Context [🛈](https://roamresearch.com/#/app/akamatsulab/page/a__twAjyo)  
  - ### Figure Legend:  
    - **Figure 1. Multiscale modeling shows that a minimal branched actin network is sufficient to internalize endocytic pits against physiological membrane tension.**  
    - > (C) Force versus pit internalization relationships for different values of membrane tension. Internalization is defined as the pit displacement in Z. Shading delineates linear force-internalization regime (blue); ‘transition point’ from U to omega shape (orange); ‘omega-shaped’ regime where the neck is narrower than the pit diameter and the force required for internalization is lower than at the transition point (for tensions > 0.1 pN/nm) (yellow). Color matches the three snapshots in B. Parameters are given in Supplementary files 1 and 2.  
    - > (D) Resistance of pit to internalization versus membrane tension. Resistance (spring constant) is defined as absolute value of slope in C for the ‘Ushaped’ region. Each curve is calculated for a different value of membrane rigidity (where 1x = 320 pN!nm, the rigidity of the uncoated plasma membrane).  
  - ### Sentence from Results:  
    - > Simulations demonstrated that a clathrin-coated pit experiences a nearly linear force-extension relationship until an internalization of ~100 nm, at which point the pit can also adopt a pinched (or ‘omega’) shape, which requires a lower force (Figure 1C and Figure 1—video 1). We calculated the resistance to internalization as the slope of the force-extension plot for the linear regime and found that it is directly proportional to plasma membrane tension for a wide range of coat rigidities (Figure 1D).  
    - > The simple spring-like relationship uncovered above between force and endocytic pit internalization (Figure 1D) allowed us to simplify our mechanical treatment of the plasma membrane while modeling individual actin filaments and actin-binding proteins with realistic kinetics and mechanics  
    - > Importantly, most of the parameters in this model have been determined with measurements in vitro or in vivo, including the dimensions of the endocytic pit, its resistance to internalization (modeled as a spring, Figure 1D), rates of association and dissociation of different proteins, branching angles, capping rates, filament persistence length, and stall force (Supplementary file 3 and Materials and methods).  
    - > Further, to fully explore the space of solutions, we ran the simulations backward by starting from an ‘omega shaped’ pit at a large internalization and then decreasing the internalization. In Figure 1C, we plotted the curves for negative internalization > = the farthest internalization for the U shaped pit (generally ~100 nm).  
  - ### Relevant text from Methods section:  
    - > We used Cytosim (Nedelec and Foethke, 2007) to model the polymerization of a branched actin network coupled to the internalization of a clathrin-coated pit. This approach simplified the pit as a bead attached to a flat boundary (the plasma membrane) by a spring. This assumption of a linear force-extension relationship was validated in Figure 1. Actin filaments and actin-binding proteins (Arp2/3 complex, Hip1R) were explicitly simulated as individual objects (agents). Cytosim calculates the forces on each segment of actin from rules such as diffusion, confinement, growth, and binding based on Brownian dynamics.  
    - > Endocytic pit internalization is simplified as an elastic spring, with a linear relationship between force and extension. We show in Figure 1 that this linear relationship is characteristic of coated plasma membranes under force up until a threshold internalization of ~100 nm. Future studies will treat the coated membrane as a 3D, force-dependent curving surface; such an approach is outside the scope of the present work.  
    - > We used the relationship between internalization resistance and membrane tension (Figure 1) to calibrate the spring stiffness in our agent-based simulations. We relied on values of membrane tension measured in human skin melanoma SK-MEL-2 cells, based on atomic force microscope membrane tether rupture forces and the assumption that the rigidity of the plasma membrane is 320 pN!nm  

## How central is this evidence to the claim at hand?  
  - {{slider}}  
