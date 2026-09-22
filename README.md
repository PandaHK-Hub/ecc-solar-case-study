# Grid-tied solar + storage — conservation facility case study (Vietnam, 2020)

Expandable Schneider-based PV + storage: cut peak grid stress, provide backup through seasonal instability, and present live harvesting as an on-site sustainability demo.

**System design & sourcing:** [Panda Labs Ltd.](https://github.com/PandaHK-Hub), Hong Kong  
**Commissioned:** 23 December 2020

---

## Roles (public)

| Role | Party |
|------|--------|
| Facility / operator | **Client 1** |
| Project coordination | **Client 2** |
| Funding | _______ (private foundation) |
| Local installation | Local install partner |
| System design & sourcing | **Panda Labs Ltd., Hong Kong** |

Personal contacts are omitted from this public write-up.

---

## Problem

- Seasonal grid instability (approximately November–April).
- Conservation operations need resilient power for pumps, heating, facilities, and care systems.
- Desire to reduce peak demand on the local grid and demonstrate sustainable energy on site.

Site solar resource (south-facing array): on the order of **~5.0–5.8 kWh/m²/day** depending on season and tilt.

Observed facility demand class (pre-solar):

| Metric | Value |
|--------|-------|
| Peak demand | ~29.7 kW |
| Minimum demand | ~8.7 kW |
| Average demand | ~16.1 kW |
| Annual energy use (bill-based) | ~130,000 kWh/year class |

---

## Objectives

1. De-stress the local grid at peak.  
2. Provide backup if the grid fails.  
3. Reduce electricity cost and enable optional export income.  
4. Deliver a visible public demo (lobby live display).

---

## Solution

Architecture: **expandable grid-tied** PV with **DC-coupled** storage (Schneider Conext family).

### Power electronics (as installed)

- 6× Schneider Conext XW+ 8548 (clustered; expandable toward ~2× inverter capacity class, ~41 kW → ~82 kW class)
- Schneider Conext MPPT charge controllers
- System control / battery monitors / Gateway for monitoring
- Lobby live display of harvest activity

### Array & storage (class)

- JA Solar PV array (STC array class ~21–28 kW depending on rating basis in source study)
- Vision-class sealed lead-acid storage; usable energy on the order of **~32–48 kWh** depending on DoD assumptions in the study
- Layout planned for future MPPT / inverter / battery expansion

---

## Results

### Energy

| Metric | Approx. value |
|--------|----------------|
| Average daily grid draw (before) | ~387 kWh/day |
| Average daily grid draw (after) | ~274 kWh/day |
| Daily reduction | ~113 kWh/day (~29%) |

Peak shaving + solar harvest shifted load so PV covered much of morning peak and storage supported afternoon peak, with charging biased to off-peak / standard periods where applicable.

### Financials (numbers only — no party names)

| Metric | Approx. USD |
|--------|-------------|
| Annual energy cost reduction | ~**6,913** |
| Annual export / feed-in income | ~**270** |
| Combined annual benefit (before opex/depreciation framing in study) | ~**7,183** class |
| Average annual cash flow after depreciation & opex (study) | ~**3,020** |

Illustrative daily averages from the study:

| Component | Approx. USD/day |
|-----------|-----------------|
| Savings from solar harvesting | ~16.61 |
| Savings from peak shaving | ~2.33 |
| Feed-in income | ~0.74 |
| Total daily benefit class | ~18.9 |

---

## What this repository is / isn’t

| Is | Isn’t |
|----|--------|
| Engineering case study for portfolio / methods | Install manual or as-built package |
| Public-safe roles + financial outcomes | Identifiable client, NGO, installer, or funder names |
| Pointer to Panda Labs field engineering | Supplier quotes, POs, or personal contacts |

---

## Related

- Org: [github.com/PandaHK-Hub](https://github.com/PandaHK-Hub)
- Methods write-up: [verification-loop](https://github.com/PandaHK-Hub/verification-loop)

---

## License / notice

See [`NOTICE`](./NOTICE). Case study text © Panda Labs Ltd. All rights reserved.
