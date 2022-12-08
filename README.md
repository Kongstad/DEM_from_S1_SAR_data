# Digital Elevation Models from Sentinel-1 SAR data via SNAP Toolbox.

(Repository under construction)
Obtaining DEM's from Sentinel-1 SAR data through SNAP toolbox. This repository does not contain any python code and is rather a demonstration of the retrieval and usage of SAR data to create Digital Elevation Models


1) Find data via Copernicus Sci Hub. I have chosen a section over the eastern mountain range in the US state of Washington.
The tile ID I have used is: S1A_IW_SLC__1SDV_20220724T015425_20220724T015452_044236_05479C_68C5
  * Start Time: 07/24/22, 01:54:25Z
  * Stop Time: 07/24/22, 01:54:52Z
  * Flight Direction: ASCENDING
  * Polarization: VV+VH

![alt text](images/Scihub.PNG)

...) Using the ASF Data Search Vertex to locate the baseline. Baseline uses information from two synthetic aperture radar (SAR) images of the same target area acquired at different times (temporal baseline) and from slightly different satellite orbit positions (perpendicular baseline).
The tile I have used is: S1A_IW_SLC__1SDV_20220817T015427_20220817T015454_044586_055259_036A
  * Perpendicular: -8 meters
  * Temporal: 24 days
  * Start Time: 08/17/22, 01:54:27Z
  * Stop Time: 08/17/22, 01:54:54Z
  * Flight Direction: ASCENDING
  * Polarization: VV+VH
This tile has a perpendicular baseline of -8m and a temporal baseline of 24 days.

![alt text](images/ASF.PNG)


...) Finished DEM product exported as KMZ file and displayed in Google Earth Pro on top of a Satellite image
![alt text](images/DEMinGE.PNG)
