# 2. The Reference Energy System

The reference energy system of the RMC model encompasses a comprehensive macro energy system supply chain, which can be divided into three stages: primary energy extraction, secondary energy processing and conversion, and final energy consumption ({ref}`Fig. 2-1 <Fig. 2-1>`). The energy demand sectors consist of three major end-use consumption categories: industry, buildings, and transportation. The industrial sector includes traditional energy-intensive industries such as iron and steel, cement, petrochemicals, and chemicals, as well as general manufacturing, advanced manufacturing, and emerging sectors such as information technology. The transportation sector covers road transport, rail transport, shipping, etc., with detailed classifications of transport modes available in the relevant chapter of the RMC|Transport model. The building sector includes commercial facilities and residential households. Energy demand is represented in the model as final energy and is exogenously determined based on socio-economic development projections. The above processes are illustrated in the modeling system structure shown in the figure below.

```{figure} _static/fig_2_1.png
---
name: Fig. 2-1
align: center
---
Fig. 2-1: Diagram for modeling system structure.
```

Based on the modeling characteristics of MESSAGEix, we have energy technologies (processes) and energy commodities. The interconversion and flow of energy commodities are linked through energy technologies, thereby forming the different components of the energy system. Energy technologies are characterized by a detailed set of parameters. The figure below ({ref}`Fig. 2-2 <Fig. 2-2>`) illustrates a simplified reference energy system within this framework, showing the linkages between energy commodities and technologies, and briefly outlining the scope of the energy system. Note that this schematic does not include all possible technology combinations or inter-regional energy flows.


```{figure} _static/fig_2_2.png
---
name: Fig. 2-2
align: center
---
Fig. 2-2: A simplified reference energy system.
```

The current version of the model involves over 400 energy technologies from energy supply to consumption, covering the full spectrum of energy supply: upstream resource extraction (resource supply), midstream processing and conversion (power plants, refineries, coking plants, etc.), energy transmission, import, and export.

## 2.1. Energy resource endowments

### 2.1.1. Fossil fuel reserves and resources

The accessibility and cost of fossil fuels play a critical role in shaping the future of the energy sector, thereby directly impacting the nature of future climate mitigation challenges. It is imperative to understand the changes in the availability of fossil fuels and their extraction costs. The assumptions on fossil energy resources in RMC are derived from a variety of sources, including national and global databases such as NBS and the United States Geological Survey (USGS), as well as reports and forecasts from diverse energy research institutes and organizations.
'Reserves' in this model refer to the quantities of fossil fuels that have been confirmed to exist through geological assessment with a significant degree of certainty regarding their existence (proven, probable, or possible) and can be commercially extracted under current economic and technological conditions. 'Resources', a broader concept than 'reserves', includes those that have not yet been discovered, as well as those that are technologically unfeasible or economically unviable, but might be recoverable in the future, as well as those quantities that are geologically possible, but yet to be found. {ref}`Table 2-1 <Table 2-1>` shows the calculated fossil fuel resources in the RMC model for 2022. Estimating fossil fuel reserves is built on technological assumptions. With an improvement in technology, the amount that may be considered a 'reserve' vs. a 'resource' can actually vary widely.

```{table} Table 2-1: Calculated results of China's fossil fuel resources in the RMC model.
:name: Table 2-1

| 列1 | 列2 | 列3 |
|-----|-----|-----|
| A   | B   | C   |
| D   | E   | F   |
```
