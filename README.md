# Dataset_code_Thesis-MM-LiDAR_Yu
Here are the code and dataset related to the doctoral thesis **"Material probing using multimodal multispectral LiDAR based on a femtosecond-laser supercontinuum"**. [Thesis link]()

### Thesis abstract
Light detection and ranging (LiDAR) is a well-established technology that provides precise three-dimensional (3D) spatial information. However, conventional monochromatic LiDAR is weak at observing material information, which is crucial for comprehensive 3D digitization and environmental perception. The most established solution for the joint acquisition of spatial and material information is fusing spectral data from an RGB/hyperspectral camera and point cloud data from a monochromatic LiDAR. This sensor fusion approach encounters inherent challenges, such as co-registration problems between point cloud data and camera images and the high sensitivity to ambient light variation due to cameras being passive sensors. To address these problems, multispectral LiDAR was proposed a decade ago by extending the spectral dimension of conventional monochromatic LiDAR to provide simultaneously 3D spatial and spectral information through fully active sensing without the need to co-register spatial and spectral data. Nonetheless, material information is not solely encoded in the optical intensity of the backscattered light from a target surface but also in other optical modalities, such as phase, polarization, and frequency shifts.

This thesis introduces the concept of multimodal multispectral (MM) LiDAR, which extends the modal dimension of multispectral LiDAR and thus allows for enhanced material probing capabilities. A comb-based MM LiDAR prototype was developed in this work, including three optical modalities (i.e., reflectance, penetration depth, and polarization) and 33 spectral channels from 580 nm to 900 nm with 10 nm resolution. Built upon a mode-locked femtosecond supercontinuum laser source and taking advantage of the intermode-beating approach in distance measurement, the comb-based MM LiDAR achieves sub-mm distance precision for most spectral channels at a ranging distance of 0.5 m with 1 ms integration time. This performance provides the basis for observing the wavelength-dependent penetration depth of light in target materials. This extended modal dimension demonstrates better material classification performance on material specimens relevant to construction, e.g., stone, wood, plastic, and concrete.

Further contributions of this thesis include proposing a specialized feature selection method and decision-making pipeline to determine the optimal feature configuration of the MM LiDAR developed and used within this thesis, considering the classification task among multiple material categories and the data structure of MM features. Moreover, this thesis introduces polarization-resolved reflectance spectra extracted from the MM feature space and leverages them to augment the classification of material composition and enable the observation of additional target characteristics, such as surface roughness. Overall, the findings of this work contribute to advancing LiDAR technology beyond 3D and towards holistic environmental perception.

### Paper A
Han, Y., Salido-Monzú, D. and Wieser, A., 2022. Comb-based multispectral LiDAR providing reflectance and distance spectra. Optics Express, 30(23), pp.42362-42375.
[Article DOI](https://doi.org/10.1364/OE.473466)   [Dataset and codes](http://hdl.handle.net/20.500.11850/627737)

### Paper B
Han, Y., Salido-Monzú, D., Butt, J.A., Schweizer, S. and Wieser, A., “A feature selection method for multimodal multispectral LiDAR sensing," under review.
[Dataset and codes](https://github.com/yuhan-yhyh/Dataset_Code_MGSVM-FS-MM-LiDAR.git)

### Paper C
Han, Y., Salido-Monzú, D. and Wieser, A., 2023. Classification of material and surface roughness using polarimetric multispectral LiDAR. Optical Engineering, 62(11), pp.114104-114104.
[Article DOI](https://doi.org/10.1117/1.OE.62.11.114104)   [Dataset and codes](https://github.com/yuhan-yhyh/Dataset_Code_PML.git)
### Related conference paper
Han, Y., Salido-Monzú, D., Butt, J.A. and Wieser, A., 2022, May. Polarimetric femtosecond-laser LiDAR for multispectral material probing. In Optics and Photonics for Advanced Dimensional Metrology II (Vol. 12137, pp. 70-77). SPIE. [Article DOI](https://doi.org/10.1117/12.2624458)   [Dataset and codes](http://hdl.handle.net/20.500.11850/553220)
