# Lunar Navigation

## Screenshots
### Slope
![screenshot1](images/super_slope_hazard.png)
![screenshot2](images/slope_mask.png)
![screenshot3](images/slope_hazard.png)
![screenshot4](images/super_slope_hazard.png)
![screenshot5](images/output_super_slope_dtm.png)
![screenshot6](images/output_slope_dtm.png)

### Crater
![screenshot7](images/super_crater_hazard.png)
![screenshot8](images/super_crater_mask.png)
![screenshot9](images/crater_mask.png)
![screenshot10](images/crater_hazard.png)

### Shadow
![screenshot11](images/shadow_hazard.png)
![screenshot12](images/shadow_mask.png)
![screenshot13](images/super_shadow_hazard.png)
![screenshot14](images/super_shadow_mask.png)

### Hazard
![screenshot15](images/hazard_map.png)
![screenshot16](images/hazard_map_critical.png)
![screenshot17](images/hazard_mask.png)
![screenshot18](images/hazard_mask_critical.png)
![screenshot19](images/super_hazard_critical_compare.png)
![screenshot20](images/super_hazard_map.png)
![screenshot21](images/super_hazard_map_critical.png)
![screenshot22](images/super_hazard_mask.png)
![screenshot23](images/super_hazard_mask_critical.png)

### Combined
![screenshot24](images/super_hazard_mask.png)
![screenshot25](images/super_hazard_map.png)
![screenshot26](images/hazard_mask.png)
![screenshot27](images/hazard_map.png)

## Abstract

Lunar Navigation is a critical component for the success of lunar missions, requiring a comprehensive approach that integrates advanced techniques. This multifaceted system aims to ensure safe lunar navigation through the generation of high-resolution hazard maps, employing super-resolution methods, crater detection, crater pattern matching, and visual terrain relative navigation.

### Super-Resolution with Keras and GANs

- Utilizes Keras and Generative Adversarial Networks (GANs) to enhance low-resolution images from terrain mapping cameras.
- Provides a clearer, more detailed view of the lunar surface.
- Contributes to enhanced navigation accuracy by improving image resolution.

### Crater Detection with Ellipse R-CNN

- Employs the Ellipse R-CNN model for crater detection.
- Combines object retrieval and occlusion pattern recognition for precise hazard identification.
- Enhances the safety of lunar navigation by identifying potential hazards on the lunar surface.

### Crater Pattern Matching

- Focuses on recognizing recurring patterns in the lunar terrain.
- Refines hazard prediction by identifying consistent features.
- Provides valuable insights for mission planning and navigation safety.

### Visual Terrain Relative Navigation

- Involves identifying lunar surface features using visual data.
- Classifies terrain using DenseNet, estimating depth with Pix2Pix and GANs.
- Enhances navigation precision through deep learning techniques for terrain analysis and depth estimation.

### Challenges and Considerations

- Training feature-based transforms poses challenges in adapting to lunar surface variations.
- Accommodating varying lunar lighting conditions for accurate image analysis.
- Ensuring regular updates in the dynamic lunar environment for real-time navigation.
- Enhancing image resolution from terrain relative cameras to improve feature recognition.

### System Components

- Relies on deep learning models for various navigation tasks.
- Requires substantial computational resources for processing large datasets.
- Utilizes fine-tuned generative models to enhance image resolution.
- Incorporates advanced image processing techniques for accurate terrain analysis.

### Significance

- Integral for achieving safe lunar landings and ensuring the success of lunar exploration missions.
- Advances scientific endeavors by providing valuable data on the lunar environment.
- Demonstrates the capability of deep learning in addressing complex challenges in space exploration.
