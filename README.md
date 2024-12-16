# Computation of Flux Footprint and Overlay on Satellite Image

## Project Description
This project focuses on calculating the **flux footprint** using the **Kormann and Meixner method** and visualizing it by overlaying the computed footprints onto high-resolution satellite imagery. The study was conducted using data collected from a flux tower located at the Department of Agricultural Meteorology, Anand Agriculture University, Anand.

### What is a Flux Footprint?
A flux footprint, also known as an atmospheric flux footprint, represents the upwind area contributing to the flux measurements captured by an instrument. Understanding flux footprints is essential for atmospheric studies, such as analyzing gas exchange, pollutant dispersion, or energy fluxes.

---

## Objectives
- To calculate the flux footprint using analytical models based on data collected from the flux tower.
- To overlay the flux footprint onto satellite imagery for spatial visualization.

---

## Study Area and Dataset
### Study Area
- **Location:** Near the Department of Agricultural Meteorology, Anand Agriculture University, Anand.
- **Latitude:** 22.53° N
- **Longitude:** 72.98° S

### Dataset
- Data collected from the flux tower for the year **2009**.
- Parameters used:
  - Measurement height above displacement height (**zm**) in meters.
  - Roughness length (**z0**) in meters.
  - Mean wind speed at zm (**umean**) in m/s.
  - Obukhov length (**ol**) in meters.
  - Standard deviation of lateral velocity fluctuations (**sigmav**) in m/s.
  - Friction velocity (**ustar**) in m/s.
  - Wind direction (**wind_dir**) in degrees.

---

## Methodology
1. **Data Collection:**
   - Data was obtained from the flux tower located in the study area.
2. **Flux Footprint Calculation:**
   - Used the **Kormann and Meixner** method to compute the flux footprint.
3. **Visualization:**
   - Overlaid the flux footprint onto high-resolution satellite images using **QGIS**.
4. **Analysis:**
   - Compared stable and unstable atmospheric conditions across different seasons.

---

## Results
### Seasonal Analysis
1. **Autumn:**
   - **Stable:** Concentrated and localized flux.
   - **Unstable:** Dispersed flux over a larger area, primarily from the South/Southeast.
2. **Winter:**
   - Flux primarily from the Southwest.
3. **Summer:**
   - Larger dispersion areas in unstable conditions, with flux coming from the West.
4. **Monsoon:**
   - Prevailing flux direction towards the Northwest.

### Height Impact
- **2m height:** Smaller, more localized footprint.
- **5m height:** Larger, more dispersed footprint.

---

## Conclusion
1. **Stable vs. Unstable Conditions:**
   - Stable conditions lead to more localized footprints, while unstable conditions result in larger, dispersed footprints.
2. **Height Effect:**
   - Increasing the flux measurement height captures a broader influence.
3. **Seasonal Variations:**
   - Seasonal shifts in wind patterns and atmospheric stability significantly impact flux footprints.

---

## Contributors
- **Sanket Gondaliya** (@SanketGondaliya)
- **Darshan Gajera** (@DarshanGajera)
- **Deep Rabadiya** (@DeepRabadiya)
- **Kaushal Kathiriya** (@KaushalKathiriya)

---

