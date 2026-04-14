### 📂 Repository Overview

This repository contains the scripts and outputs supporting the study:

**“Climatic fingerprint of the 2023 wheat head blast outbreak and its historical and future analogs in southern South America.”**

The project integrates climate data processing, index computation, and analog-based analysis to characterize the environmental conditions associated with wheat head blast outbreaks.

A Quarto website version of this project, including results and visualizations, is available at:  
👉 https://igorerhardt.github.io/Paper-WheatBlast-AnalogYears/

---

## 🔄 Workflow Overview

The analytical workflow is organized into the following main steps:

1. **Data acquisition and preprocessing**  
   Retrieval and preparation of climate datasets.

2. **Feature extraction**  
   Derivation of relevant climatic variables for the epidemiological analysis.

3. **Climate indices computation**  
   Calculation of indices describing conditions favorable to wheat head blast.

4. **Analog year detection**  
   Identification of years with climatic conditions similar to the 2023 outbreak.

5. **Visualization and interpretation**  
   Generation of figures and summaries to support analysis and communication of results.

---

## 📜 Script Workflow

The workflow is implemented through the following Quarto scripts:

1. **`CORDEX_Retrieval.qmd`**  
   Handles the acquisition and preprocessing of climate data from CORDEX, including formatting and subsetting for the study region.

2. **`AnalogYearsProc.qmd`**  
   Performs climate index computation, analog year detection, and generates the main outputs and visualizations.

---