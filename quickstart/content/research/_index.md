---
date : '2025-06-03T18:31:05+03:00'
draft : true
title : 'Research'
---


## Research

My M.Sc. research at **Ben-Gurion University of the Negev**, conducted within the *Ecological Complexity Lab* under the supervision of Dr. Shai Pilosoph, focuses on modeling the effects of land use change on the risk of tick-borne disease transmission in rural Madagascar.

### Title  
**Predicting Human Exposure to Tick-Borne Disease: The Role of Market Integration via Land Use Change in Northern Madagascar**

### Research Objectives

This project investigates how dynamic and heterogeneous land use patterns in underdeveloped tropical regions influence human exposure to tick-borne diseases. Unlike traditional "habitat island" frameworks, the study considers landscapes where every land cover type can act as habitat to some extent.

Using data from an international collaborative project in four villages surrounding **Marojejy National Park**, I developed a **stochastic agent-based model** simulating tick population dynamics across land types and scenarios of economic-driven land transformation.

The model integrates:
- Spatial structure of land use
- Tick life cycle stages and transitions
- Movement probabilities based on habitat type, host behavior, and carrying capacity
- Future land-use scenarios informed by socio-economic trends

### Methodology Highlights
- A **3-layer lattice model** was designed to simulate larva, nymph, and adult tick populations across a spatial grid.
- The model uses a **Gillespie algorithm** for stochastic simulation, with layers representing life stages and transitions.
- Several **movement kernels** (random, distance-dependent, and habitat-weighted) were tested to model realistic tick dispersal.
- Human infection risk is estimated through modeled tick-human encounter rates, using land classification and human activity data.

### Case Study Area
- The **Sava region**, Madagascar — a globally important area for vanilla production and rapidly shifting agricultural practices.
- Focus on how **market integration**, such as global vanilla demand, alters land use and affects ecological disease risks.

### Preliminary Findings
- Tick abundance is influenced not only by habitat type but also by surrounding landscape composition — a **mass effect** that sustains populations even in suboptimal areas.
- Different movement kernels and land-use transitions lead to **nonlinear, context-dependent outcomes** in human exposure risk.
- Initial simulations suggest **agroforestry expansion** and **tavy (slash-and-burn)** agriculture have strong effects on predicted disease risk.

### Broader Impact
This research addresses a critical gap in disease ecology by modeling zoonotic disease risk in **tropical, data-scarce regions**. The results will inform land management and public health planning where traditional modeling frameworks fall short.

---

For technical details, collaboration context, or to access publications and code, please [contact me](/#contact) or visit [GitHub](https://github.com/yuvalbloch).
