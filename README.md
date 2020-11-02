# 'Single-cell sequencing of the human midbrain reveals glial activation and a neuronal state specific to Parkinson's disease'. 

Image analysis scripts used in 'Single-cell sequencing of the human midbrain reveals glial activation and a neuronal state specific to Parkinson's disease'. In this study, we analyzed microscopy images of two midbrain tissues. The tissues were stained for neuronal and dopaminergic markers, Cadps2 and glial cells (oligodendrocytes, astrocyes and microglia). The analysis is done in three steps.

## General workflow
The 'OligoAstroMicroAnalysis.m' is used to extract fluorescent objects (oligodendrocytes-PLP1, astrocytes-GFAP, microglia-IBA1) according to the intensity and area size.
The 'MicrogliaRamificationAnalysis.m' extracts the fluorescent objects (microglia-IBA1) according to the intensity and area size. Furthermore, on each object, skeleton of the IBA1 mask was generated with a thinning function to identify the branching of the object areas. 
The '

