# Energy Flow Sankey Diagram - Manufacturing Analysis

## Business Context
This Sankey diagram visualizes energy consumption flow from various sources (Solar, Coal, Natural Gas, Wind, Hydro) to end uses in manufacturing operations (Manufacturing, Equipment, Heating, Lighting, Cooling).

## Contact
**Email:** 23f3004096@ds.study.iitm.ac.in

## Visualization Details
- **Tool Used:** RAWGraphs (https://rawgraphs.io/)
- **Chart Type:** Sankey Diagram (Alluvial Diagram)
- **Data Structure:** Source → Target flow data
- **Dimensions:** 512x512 pixels
- **Format:** PNG

## Data Overview
The visualization represents energy flow quantities (in arbitrary units) showing:
- **Energy Sources:** Solar, Coal, Natural Gas, Wind, Hydro
- **End Uses:** Manufacturing, Equipment, Heating, Lighting, Cooling
- **Flow Values:** Proportional arrow widths representing energy quantities

## Key Insights
- Coal provides the largest energy input for manufacturing operations
- Natural Gas is primarily used for heating applications
- Renewable sources (Solar, Wind, Hydro) contribute significantly to lighting and cooling
- Equipment usage draws from multiple energy sources for redundancy

## Files
- `README.md` - This documentation file
- `chart.png` - Sankey diagram visualization (512x512px)

## Data Structure
```csv
source,target,flow
Solar,Manufacturing,892
Coal,Equipment,1250
Natural Gas,Heating,1120
...
```

## Purpose
This visualization was created for executive presentations and strategic planning to analyze:
- Energy efficiency opportunities
- Resource optimization
- Sustainability initiatives
- Cost reduction strategies

---

**Created for:** Windler and Sons - Strategic Consulting  
**Analyst:** 23f3004096@ds.study.iitm.ac.in
