# JTD-Boggle-107 atlas

## Overview

JTD-Boggle-107 atlas is a brain atlas (anatomical labels combining the individual brains, used for labeling) which is manually labeled human brain images.

This brain atlas is based on mindboggle atlas (https://mindboggle.info/) and adds/excludes some regions to define the 107 regions found in the normal brain.
Specifically, we made the following improvements:
- Finely defined Brain-stem into the following regions:
  - Pons
  - Midbrain
  - Medulla oblongata
  - Superior cerebellar peduncle
- Excludes the following regions from mindboggle atlas:
  - ctx-lh-unknown
  - ctx-rh-unknown
  - WM-hypointensities
  - non-WM-hypointensities
  - Left-vessel
  - Right-vessel
  - Left-choroid-plexus
  - Right-choroid-plexus
- Improved misclassification of cortex and sulcus

We prepared three kinds of atlas images and atlas masks. The one is the JTD-Boggle-107 atlas based on the mindboggle atlas image, the others are an image with no atrophy (showing normal size ventricles), and an image diagnosed with Alzheimer’s disease with brain atrophy (showing a ventricular enlargement), each based on the JTD-Boggle-107 atlas.


## Label Definitions

| value | label |
| ---- | ---- |
|1	|CSF|
|2	|White matter (Left)|
|3	|Lateral ventricle (Left)|
|4	|Inferior lateral ventricle (Left)|
|5	|Cerebellum white matter (Left)|
|6	|Cerebellum cortex (Left)|
|7	|Thalamus (Left)|
|8	|Caudate nucleus (Left)|
|9	|Putamen (Left)|
|10	|Globus pallidus (Left)|
|11	|Third ventricle|
|12	|Fourth ventricle|
|14	|Hippocampus (Left)|
|15	|Amygdala (Left)|
|17	|Nucleus accumbens (Left)|
|18	|Ventral diencephalon (Left)|
|21	|White matter (Right)|
|22	|Lateral ventricle (Right)|
|23	|Inferior lateral ventricle (Right)|
|24	|Cerebellum white matter (Right)|
|25	|Cerebellum cortex (Right)|
|26	|Thalamus (Right)|
|27	|Caudate nucleus (Right)|
|28	|Putamen (Right)|
|29	|Globus pallidus (Right)|
|30	|Hippocampus (Right)|
|31	|Amygdala (Right)|
|32	|Nucleus accumbens (Right)|
|33	|Ventral diencephalon (Right)|
|38	|Optic chiasm|
|39	|Posterior corpus callosum|
|40	|Middle posterior corpus callosum|
|41	|Central corpus callosum|
|42	|Middle anterior corpus callosum|
|43	|Anterior corpus callosum|
|45	|Superior temporal sulcus (Left)|
|46	|Caudal anterior cingulate cortex (Left)|
|47	|Caudal middle frontal gyrus (Left)|
|48	|Cuneus (Left)|
|49	|Entorhinal cortex (Left)|
|50	|Fusiform gyrus (Left)|
|51	|Inferior parietal lobule (Left)|
|52	|Inferior temporal gyrus (Left)|
|53	|Cingulate gyrus (Left)|
|54	|Lateral occipital sulcus (Left)|
|55	|Lateral orbitofrontal cortex (Left)|
|56	|Lingual gyrus (Left)|
|57	|Medial orbitofrontal cortex (Left)|
|58	|Middle temporal gyrus (Left)|
|59	|Parahippocampal gyrus (Left)|
|60	|Paracentral gyrus (Left)|
|61	|Pars opercularis (Left)|
|62	|Pars orbitalis (Left)|
|63	|Pars triangularis (Left)|
|64	|Calcarine sulcus (Left)|
|65	|Postcentral gyrus (Left)|
|66	|Posterior cingulate cortex (Left)|
|67	|Precentral gyrus (Left)|
|68	|Precuneus (Left)|
|69	|Rostral anterior cingulate cortex (Left)|
|70	|Rostral middle frontal gyrus (Left)|
|71	|Superior frontal gyrus (Left)|
|72	|Superior parietal lobule (Left)|
|73	|Superior temporal gyrus (Left)|
|74	|Supramarginal gyrus (Left)|
|75	|Frontal pole (Left)|
|76	|Temporal pole (Left)|
|77	|Transverse temporal gyrus (Left)|
|78	|Insular cortex (Left)|
|80	|Superior temporal sulcus (Right)|
|81	|Caudal anterior cingulate cortex (Right)|
|82	|Caudal middle frontal gyrus (Right)|
|83	|Cuneus (Right)|
|84	|Entorhinal cortex (Right)|
|85	|Fusiform gyrus (Right)|
|86	|Inferior parietal lobule (Right)|
|87	|Inferior temporal gyrus (Right)|
|88	|Cingulate gyrus (Right)|
|89	|Lateral occipital sulcus (Right)|
|90	|Lateral orbitofrontal cortex (Right)|
|91	|Lingual gyrus (Right)|
|92	|Medial orbitofrontal cortex (Right)|
|93	|Middle temporal gyrus (Right)|
|94	|Parahippocampal gyrus (Right)|
|95	|Paracentral gyrus (Right)|
|96	|Pars opercularis (Right)|
|97	|Pars orbitalis (Right)|
|98	|Pars triangularis (Right)|
|99	|Calcarine sulcus (Right)|
|100|Postcentral gyrus (Right)|
|101|Posterior cingulate cortex (Right)|
|102|Precentral gyrus (Right)|
|103|Precuneus (Right)|
|104|Rostral anterior cingulate cortex (Right)|
|105|Rostral middle frontal gyrus (Right)|
|106|Superior frontal gyrus (Right)|
|107|Superior parietal lobule (Right)|
|108|Superior temporal gyrus (Right)|
|109|Supramarginal gyrus (Right)|
|110|Frontal pole (Right)|
|111|Temporal pole (Right)|
|112|Transverse temporal gyrus (Right)|
|113|Insular cortex (Right)|
|130|Pons|
|131|Midbrain|
|132|Medulla oblongata|
|133|Superior cerebellar peduncle|



## License
This repository is licensed under CC BY 4.0.  
Please see the details in [LICENSE.md](./LICENSE.md).  
© Juntendo University and FUJIFILM Corporation 2023