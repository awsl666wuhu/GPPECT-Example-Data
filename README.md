# GPPECT-Example-Data
Example data of the Gold Purity Pulsed Eddy Current Testing (GPPECT) dataset

## Overview
This repository contains **example data** from the GPPECT (Gold Purity Detection via Pulsed Eddy Current Testing) study. This subset is provided to illustrate the data structure and demonstrate the temperature effects on PEC signals discussed in our paper.

## ⚠️ Important Notice
This is a **simplified example subset** from a single measurement session:
- Contains only 2 sample classes (out of 12 in the full study)
- Single operator measurements (full study includes 6 operators)  
- Limited temperature range representation
- **NOT intended as a standalone research dataset**
- For complete experimental results, please refer to the paper

## Data Description
- **File**: `pect_example_data.csv`
- **Size**: 400 measurements × 1002 features
- **Structure**:
  - Columns 1-1000: PEC signal amplitude values
  - Column 1001: Temperature (°C)
  - Column 1002: Sample class label (0 or 1)

## Example Usage
This data can be used to:
- ✅ Understand the GPPECT data format
- ✅ Visualize PEC waveforms and temperature effects
- ✅ Explore basic signal processing techniques

