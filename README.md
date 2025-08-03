# 🌌 Pleiades Cluster Reduction & Isochrone Analysis

![Isochrone Fit](plei_isofit.pdf)

## 📘 Overview
This project uses **Gaia DR3** data to produce a clean dataset of the **Pleiades star cluster** that identifies true cluster members through data reduction. Reducing the original dataset using parallax and proper motion techniques narrows extracted stars to stars positioned at the same distance and moving in the same direction. This project also builds a **Color–Magnitude Diagram (CMD)** using key astrophysical properties and overlay **theoretical isochrones** to explore stellar ages, and distances. 

Using the included Colab notebook, you can:
- 🔭 Filter and clean Gaia DR3 data for the Pleiades  
- 📊 Build CMDs and overlay isochrones  
- 🏷️ Annotate isochrones with **stellar masses**  
- 🔍 Investigate regions of the CMD in detail

---

## ☁️ Dataset
- Source: GAIA DR3
- Format: CSV
- Number of stars surveyed: 1423

--- 

## 🔧Tools Used
- Python - Data Cleaning and analysis
- pandas - Data manipulation
- matplotlib - Visualization

---


## 🚀 Features
✅ Filters Gaia DR3 catalog for the Pleiades cluster  

✅ Handles proper motion, parallax, and color corrections  

✅ Generates CMD plots 

✅ Overlays isochrones

✅ Runs on **Google Colab** or **Jupyter Notebook**

---

## ✍️ Methodology

1️⃣ Clean & Filter GAIA
- Load Gaia DR3 data, clean dataset for abnormalities, and filtered the dataset using parallax, celestial coordinates (RA/Dec), and proper motion. 

2️⃣ Visualize filtered sky data 
- ![Parallax](plx_hist.pdf)
- ![Proper Motion](pm_plei.pdf)

3️⃣ CMD
- Data extracted from Gaia includes **apparent brightness** and since we want to compare **intrinsically**, a calculation for absolute magnitude is included in Colab notebook for completeness. (Note: due to Pleiades being a nearby cluster, apparent mag. can be assumed as absol. mag., but it is otherwise included for good practice.)
  
- ![CMD](plei_cmd.pdf)

4️⃣ Overlay isochrone
- Isochron fitting with star cluster data is a common method to determining the age of a star cluster. By plotting the observed stars on the CMD and overlaying isochrones of different ages, astronomers can see whcih **best matches** the data.

- ![Isochrone Fit](plei_isofit.pdf)

---


## 🚀Key Insights
- Found cluster members: 292
- Calculated distance to Pleiades: 137.12 [pc]
- Pleiades is a rather young cluster with stars still being formed and in the early stages of stellar evolution. Star members have yet to fully branch from the main sequence. 

--- 

## ✨ Future Enhancements
- 🔧 Add age-fitting automation (χ² minimization)
- 🌈 Estimate metallicity
- 📊 Stellar evolution modeling (PARSEC/MIST)

--- 


## 🛰️ Data Resources 

- 📊 GAIA DR3: https://gea.esac.esa.int/archive/

- 🌟 Star Cluster properties: https://simbad.cds.unistra.fr/simbad/sim-id?Ident=%40675533&Name=Cl+Melotte+++22&submit=display+all+measurements#lab_meas

- 📐 Isochrones: https://stev.oapd.inaf.it/cgi-bin/cmd
