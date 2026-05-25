# China Soil Pollution Map

Interactive static map of provincial soil heavy-metal pollution in mainland China.

## What it shows

- Province-level interactive map for Cd, Pb, Zn, Cu, As, and Cr.
- Derived "composite concern" view using the maximum Igeo value across the six metals.
- Province detail panel, sortable data table, and professional notes on methodology and limits.

## Data

The map uses province-level Igeo values from Table 5 in:

Shi Hangyuan, Wang Peng, Zheng Jiatong, Xiao Rongbo, Deng Yirong, Zhuang Changwei. Spatial Distribution Characteristics of Soil Heavy Metals in China and Zoning Control Countermeasures. Environmental Science, 2023, 44(8): 4706-4716.

Official national context is cited from the 2014 National Soil Pollution Survey Bulletin by China's environmental and land-resource authorities.

This visualization is for macro-scale screening and communication. It is not a substitute for parcel-level soil investigation, remediation decisions, or statutory exceedance assessment.

## Local Preview

```bash
python3 -m http.server 5173
```

Open `http://127.0.0.1:5173/index.html`.
