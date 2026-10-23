# Deportation System Digital Atlas — map draft

A working draft of an interactive map of ICE detention-transfer flows since January 20,
2025, built for GOG522 (GIS for Social Sciences, University at Albany) and a companion
methods paper. This repo is published on demand from the Quarto project's `map/`
folder -- see that project's `map/README.md` for the current, honest list of what this
draft does and does not do yet.

Password-gated (client-side only, same convention as the author's other map,
jonnealon/TheChurn -- not real security, just a light barrier against casual visitors).

Sources: Deportation Data Project (ICE records via FOIA); CovenAnalytica/coldCounter
(hold-room addresses); U.S. Census Bureau (geocoder, cartographic boundary file);
28 U.S.C. § 41 (circuit composition); Human Rights First's ICE Flight Monitor (flight
data, not yet joined into this map). Full citations in the source project's
`references.bib`.

Companion pages, all linked from the map's own "More views" row -- see each one's own
README in the source project for what it shows:
`network-3d/` (an experimental, interactive 3D layout of the same transfer network),
`airports/` (every airport ranked by ICE Air flight volume, with a Part 139 section),
`miles/` (a data-viz analysis page for distance-moved statistics),
`population/` (a "unit chart," one dot per arrested individual, regrouped on click),
`circuits/` (circuit-to-circuit flow and case outcome).

Analysis and design: Jon Nealon.
