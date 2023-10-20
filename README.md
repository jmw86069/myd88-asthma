# Myd88 Asthma Supplemental Data

Gene expression data across multiple timepoints are included in an [online interactive display](https://jmw86069.github.io/myd88-asthma/) including:
* whole lung samples,
* (sorted) endothelial cells (ECs) at 2 hours,
* (sorted) conventional dendritic cells (cDCs) at 6 hours, and
* (sorted) alveolar macrophages (AMs) at 6 hours.

Gene expression measurements were obtained using the Nanostring nCounter Mouse Immunology Gene Expression Codeset

[Supplementary Data: MyD88/Asthma Expression Profiles](https://jmw86069.github.io/myd88-asthma/7panelLayout/index.html)

This repository contains static data and figures accompanying<br>
**"MyD88-dependent Dendritic and Epithelial Cell Crosstalk Orchestrates Immune Responses to Allergens"**<br>
authored by Dr. Seddon Y. Thomas *et al*, 2018, who is both a gifted scientist and a fantastic person.

[Mucosal Immunol. 2018 May; 11(3): 796–810.](https://doi.org/10.1038%2Fmi.2017.84)

## Interactive display

Figures were prepared using the R package [Trelliscope](https://github.com/hafen/trelliscopejs/)
to create a static HTML set of figures across all genes and samples.
This novel interface provides interactivity without the need for an active
R-shiny server, which is a remarkably useful consideration especially when
used for supplementary data for a scientific publication.

The interface relies on only the Trelliscope javascript library
and therefore is entirely encoded by fixed HTML file.
The interface also provides interactive querying and filtering capabilities.
