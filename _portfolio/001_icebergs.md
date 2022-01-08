---
title: "Iceberg Distribution for Greenland Ice Sheet"
excerpt: "Quantifying and visualizing the changes of iceberg distribution around the Greenland Ice Sheet.<br/><img src='https://raw.githubusercontent.com/glacierSid/imgs/main/gris_roi_v3_gxvseb_thumbnails.jpg'>"
collection: portfolio
---

Iceberg calving is a major source of mass loss around the Greenland Ice Sheet (GrIS); once discharged to fjords,
iceberg melt rates are predominantly dictated by their size. In this study we use open-source, machine learning (ML)
algorithms on publicly-available Sentinel-1 Synthetic Aperture Radar (SAR) imagery to quantify how iceberg sizes
vary, both temporally (every 2 weeks from 2017-2020) and spatially (along fjord lengths) around the ice sheet. We
leverage the cloud computing platform Google Earth Engine and its data catalog to perform iceberg segmentation
around GrIS. The ML model is trained on pre-processed dual polarized Sentinel-1 SAR images of icebergs along with
additional features generated with edge filters and textural filters. Our technique provides a robust approach towards
consistent and accurate segmentation of icebergs in varied environmental conditions such as rough waters, sea-ice,
brash, and water. <br/>

Our results highlight the seasonal and longer-term variability in both iceberg production and transport along
fjords. In particular, several glaciers with relatively constant calving rates throughout the length of our record exhibit
large variability in iceberg size distribution. And, in parts of the ice sheet, the presence of sea ice greatly influences the
transport of icebergs of all sizes; however, this observation is not universal around the ice sheet. Distinct patterns in
calving and iceberg transport can be recognized given our robust and dense dataset of iceberg distributions

![Sermilik_ROI](https://raw.githubusercontent.com/glacierSid/imgs/cbc76b6e64163c1cefeb150866d589ea0852b069/sermilik_roi_joined.png)
![Sermilik_timeseries](https://raw.githubusercontent.com/glacierSid/imgs/main/sermilik_timeseries_trendOnly_may17-dec2020_v3_hgldk1.png)

## Collaborators
Leigh A. Stearns, Isabella M. Bray, C. J. van der Veen

## Link to presentation
<a href = 'https://agu2021fallmeeting-agu.ipostersessions.com/Default.aspx?s=F3-9C-E4-62-A1-C2-E8-F0-EA-2A-2C-FA-B1-4F-27-75'> Iceberg distributions along Greenland Fjords, 2017 -- 2020 </a>
