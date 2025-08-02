# Star-Cluster-Analysis

# 🌌 Pleiades Cluster Reduction & Isochrone Analysis

![CMD Preview](plei_cmd.pdf)

## 📘 Overview
This project processes **Gaia DR3** data for the **Pleiades star cluster** to produce a clean dataset and build a **Color–Magnitude Diagram (CMD)**.  
It also overlays **theoretical isochrones** to explore stellar ages, distances, and mass distributions.

Using the included Colab notebook, you can:
- 🔭 Filter and clean Gaia DR3 data for the Pleiades  
- 📊 Build CMDs and overlay isochrones  
- 🏷️ Annotate isochrones with **stellar masses**  
- 🔍 Investigate regions of the CMD in detail

---

## 🚀 Features
✅ Filters Gaia DR3 catalog for the Pleiades cluster  
✅ Handles proper motion, parallax, and color corrections  
✅ Generates CMD plots in seconds  
✅ Overlays isochrones with labeled mass tracks  
✅ Runs on **Google Colab** or **Jupyter Notebook**

---

## 📊 Usage
### ▶️ Run the Notebook
Open pleiades_cluster_reduction.ipynb and execute step by step:

- 1️⃣ Load Gaia DR3 data
- 2️⃣ Filter the dataset (parallax, proper motion, RA/Dec window)
- 3️⃣ Load an isochrone file (see link below)
- 4️⃣ Plot CMD + overlay isochrone
- 5️⃣ Annotate stellar masses

--- 


## 🛰️ Data Resources 

- 🌟 GAIA DR3: https://gea.esac.esa.int/archive/

- Star Cluster properties: https://simbad.cds.unistra.fr/simbad/sim-id?Ident=%40675533&Name=Cl+Melotte+++22&submit=display+all+measurements#lab_meas

- 📐 Isochrones: https://stev.oapd.inaf.it/cgi-bin/cmd
