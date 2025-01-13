---
title:  "Clustering Parcels of Land for Development: Map of Vacant Lots/Properties in North Lawndale"
header:
  teaser: "/assets/images/cubs_parcels.png"
categories: 
  #- Jekyll
tags:
  #- update
classes: wide
---
The following map was created for the purpose of identifying all contiguous vacant parcels (city owned, county owned, privately owned) in North Lawndale that could potentially be bundled and acquired to host potential development projects.

This map has two layers, one containing the individual parcels currently owned by either the City of Chicago, Cook County, or private landowners, and an accompanying layer which merges and aggregates any lots that touch and are contiguous providing area measures in acres.

# Vacant Parcels Map

<iframe src="/assets/maps/parcel_universe_cluster_map.html" height="700" width="1000"></iframe>

This map can be used to identify clustered vacant parcels regardless of ownership type, generate a measure of square acreage of each clustered parcel group, and allow users to see which parcels comprise each cluster and identify ownership.

For example, say that the Chicago Cubs want to develop a community center and baseball fields in North Lawndale, a site which would require 12-14 acres of contiguous land. If confined to city-owned lots, whose inventory comes from ChiBlockBuilder, there are no contiguous parcels measuring more than 2 acres. By bringing in county owned parcels and privately owned vacant parcels, we can identify portfolios of parcels across ownership type that could be strategically acquired to make such a development possible.

While none of the clustered parcels have an acerage matching the 12 to 14 acres desired, clusters have been found up top 7 acres, where multiple clusters are next to each other. 

Two map Layers:
- City-owned Parcels
  - Underlying Parcels from ChiBlock Builder, Cook County Land Bank, Cook County Assessor with underlying Address,ownership type, and other information.
- Merged Parcels
  - Layer of above individual parcels merged if they were touching. Provides area in acres of merged parcels to help identify large groupings of publicly owned city parcels for development.    
