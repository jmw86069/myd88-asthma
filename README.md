# Myd88 Asthma Supplemental Data

Gene expression data across multiple timepoints are included in an [online interactive display](https://jmw86069.github.io/myd88-asthma/7panelLayout/index.html) including:
* whole lung samples at 0, 2, 4, and 6 hours
* endothelial cells (ECs, sorted) at 2 hours
* conventional dendritic cells (cDCs, sorted) at 6 hours
* alveolar macrophages (AMs, sorted) at 6 hours

Each sample represents data in four cell line genotypes:
* wildtype (**WT**)
* cDC-specific knockout of MyD88 (**DC.KO**)
* EC-specific knockout of MyD88 (**EC.KO**)
* full knockout of MyD88 (**KO**)

Gene expression measurements were obtained using the Nanostring nCounter Mouse Immunology Gene Expression Codeset, processed using nCounter software, and further analyzed using R-3.6.1 as described in the publication below.

[Supplementary Data Summary Page: MyD88/Asthma Expression Profiles](https://jmw86069.github.io/myd88-asthma/).
Click [Web Visualizations](https://jmw86069.github.io/myd88-asthma/7panelLayout/index.html) to view the figures.

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
