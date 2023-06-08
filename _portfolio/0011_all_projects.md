---
title: "List of projects"
excerpt: "Here is a list of projects that I have worked on with some of them shown in more details in the links below:"
collection: portfolio
---

### Segment Anything in Glaciology: An initial study implementing the Segment Anything Model (SAM)
Shankar, S., Stearns, L. A., & Veen, C. J. van der. (2023). Segment Anything in Glaciology: An initial study implementing
the Segment Anything Model (SAM). Research Square Platform LLC. https://doi.org/10.21203/rs.3.rs-3011246/v1
- Led the research study for implementation of foundational model, SAM, for instance segmentation of glaciological features, remote sensing
platforms, and spatial resolutions.
- Automated the codebase for generation of binary masks of objects of interest from the model.
- Created and tested with-prompt and no-prompt approaches to quantify robustness and limitations of the SAM model.
- Extensive statistical analysis and ground truth data creation for validation of the model. 

### NASA funded: Iceberg Distribution for the Greenland Ice Sheet 2016 - 2022
Shankar, S., Stearns, L., Bray, I., and van der Veen, C., “Iceberg distributions along Greenland Fjords, 2017 -
2020”, vol. 2021, 2021.
- Built automated iceberg segmentation machine learning model in Google Earth Engine (GEE) that identifies
icebergs in Sentinel-1 imagery around Greenland.
- Identified and analyzed iceberg distribution in over 250 fjords of Greenland covering 109,000 sq.km and in
150 km coastal waters of Greenland covering 1.09 million sq.km every 15 days from 2017 - 2021.
- Parallelized and improved processing of imagery and the automated workflow, from imagery to final
geolocation of icebergs and theirrespective size, significantly.
- Time-series analysis of iceberg distribution in fjords.
- Automated and scaled pre-processing of more than 6000 Sentinel-1 images.
- Improved processing time by 90%, through automation and parallelization of 24 terabytes of radar imagery
covering Greenland, creating a high spatial and temporal resolution dataset.

### Deep Learning Approach to Iceberg Tracking 2021 – present
Stearns, L., Shankar, S., Shahin, M., and van der Veen, C., “Distribution and motion of icebergs in a proglacial
melange: weekly observations from 2020 at Helheim Glacier, East Greenland”, vol. 2021, 2021.
- Prepared the training data by labeling and augmenting icebergs in Sentinel-1 SAR imagery on the Roboflow
platform.
- Trained deep learning model, YOLOv4, with custom labeled iceberg data, to detect icebergs in Sentinel-1
SAR images.
- Used iceberg trained YOLOv4 weights to DeepSORT for tracking icebergs in successive Sentinel-1 imagery
in melange.

### NASA Pilot Study: Significant contribution of small icebergs to the freshwater budget in Greenland fjords 2019 – 2020
Rezvanbehbahani, S., Stearns, L. A., Keramati, R., Shankar, S., and van der Veen, C. J. (2020). Significant
contribution of small icebergs to the freshwater budget in Greenland fjords. Nature Communications earth
environment, 1(1), 1-7.
- Deep learning model, UNet for detection and segmentation of icebergs in high resolution PLANET imagery.
- Implemented the prediction workflow for detecting the icebergs.
- Contributed to analyzing the results of iceberg estimates.

### NASA Interdisciplinary Sciences (IDS): Fjord Systems, Marine Mammals, and Subsistence Hunting
in East Greenland 2021 – present
- Built an automated, open-source, machine learning model that identifies icebergs in sea-ice, melange,
mixed-media conditions in Sentinel-1 SAR imagery for East Greenland.
- Implementing sea-ice labeled training data to differentiate sea-ice types against icebergs.
- Produced bi-monthly iceberg distribution results in 52 fjords of East Greenland for 5 years.


### Mapping icebergs in m´elange using ICEYE SAR imagery 2021 – present
Harcourt, W., Stearns, L., Shahin, M., and Shankar, S., “Mapping icebergs in melange using ICEYE imagery”,
vol. 2021, 2021.
- Trained and built an automated, open-source, deep learning model - UNet, that identifies icebergs in a
m´elange in a single polar- ization ICEYE SAR imagery.
- Analyzing the requirements needed for building an iceberg segmentation machine learning model.
- Implemented GLCM texture analysis for identifying attributes of icebergs that are critical for training the
machine learning model.
### Terminus Tracking of glaciers around the Greenland Ice Sheet 2020 – present
- Built a tool that determines positions of glacier terminus in different environmental conditions such as
sea-ice, melange, mixed-media in Sentinel-1 SAR imagery.
- Implemented textural analysis of the bands.
- Built a width average methodology that provides aggregate position change of the terminus using changes
in the position of the pixels forming the glacier terminus.
