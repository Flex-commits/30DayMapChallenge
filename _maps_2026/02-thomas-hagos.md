---
day: 2
creator: Thomas Hagos
title: The Nile, Connected
thumbnail: /assets/thumbnails/2026/02-thomas-hagos.png
source: https://github.com/Flex-commits/30-days-mapping/tree/main/day02-nile
---

**One basin, many tributaries.**

I followed the Nile upstream through Sudan, the Ethiopian highlands and the equatorial lake catchments. This map shows 133,797 connected river reaches. Color distinguishes the White Nile, Blue Nile and Atbara systems; line thickness follows Strahler stream order. An Africa locator highlights the basin, and annotations identify the main headwater regions and Mediterranean outlet.

[View the full map and project](https://flex-commits.github.io/30-days-mapping/nile/) · [Portfolio](https://flex-commits.github.io/MUSA-Portfolio/projects/nile-connected/) · [Reproducible source](https://github.com/Flex-commits/30-days-mapping/tree/main/day02-nile)

![The Nile, Connected: river network colored by tributary system](https://flex-commits.github.io/30-days-mapping/nile/nile-connected.png?v=20261103-context)

The network is selected using downstream connectivity within HydroBASINS’ Nile basin, not country borders. These are modeled drainage lines; not all channels carry perennial flow. Smaller streams and disconnected networks are excluded. The source routes to one Mediterranean outlet, so the map is not a complete delta-distributary or canal inventory.

Sources: HydroRIVERS v1.0 and HydroBASINS v1.c, WWF / McGill, accessed via UNESCO IHP-WINS; Natural Earth geographic context. Reference geography: Nile Basin Initiative. Citation: Lehner & Grill (2013), doi:10.1002/hyp.9740. Data downloaded November 3, 2026. Full source notices and limitations are in the linked project.

Map by Thomas Hagos using Python, GeoPandas and Matplotlib. Research, code and editing were assisted by AI; river geometry comes from the documented datasets.
