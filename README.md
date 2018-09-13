# Marine-Species-Characterization
The [Ocean Biogeographic Information System](http://iobis.org) (OBIS) provides the global database of marine biological observations and measurements linked with environmental data. This analysis uses the geographic areas (exclusive economic zones) summarized by OBIS and the OBIS Application Programming Interface (API). This provisional Biogeographic Analysis Package summarizes the most reported species within each exclusive economic zone observed and reported to the OBIS. The numbers reported are actual presence observations, meaning the absence records are excluded from the summary. Species were compiled by scientific name and aggregated by the class level of the taxonomic hierarchy for summarization purposes.

# Purpose
OBIS began as the data repository for the census of marine life (Ausubel 1999), and has since expanded to become the global database for marine biological observations and measurements. Data in OBIS have been used for many purposes including understanding global patterns of marine biodiversity (Tittensor et al. 2010, Dornelas et al. 2014, Chaudhary et al. 2017), taxonomic assessments (Rees et al. 2017, Panasiuk et al. 2018), and species distribution modeling (Bosch et al. 2017, Asch and Erisman 2018). This analysis provides a visualization of the taxonomic breadth and record count available in OBIS for U.S. Exclusive Economic Zones (EEZs). EEZs, and management of biological resources in them, are important to commercial fishing industry, sports fishing, and managers tasked with meeting the needs of mulitple users of these systems. 

# Abstract Stakeholder
Stakeholders for the type of information in this analysis include researchers, data analysts, and resource managers. By looking at this visualization any of those stakeholders could get an initial preview of the data available in OBIS and make basic decisions about the suitability of the data for their needs.


# Inputs
All data for this analysis are served via the OBIS API. The data are summarized by OBIS to exclusive economic zones as defined by OBIS and are therefore considered OBIS Areas. OBIS Area species can be found at http://api.iobis.org/v3/area. Then the summarized data for each of these areas can be found at the OBIS API for that area such as http://api.iobis.org/v3/statistics/composition/class?areaid=267.

# Literature Cited
Ausubel, J.H. (1999) Toward a census of marine life. Oceanography 12(3):4-5.

Asch, R.G.; Erisman, B. (2018). Spawning aggregations act as a bottleneck influencing climate change impacts on a critically   endangered reef fish. Diversity Distrib. Online first. https://hdl.handle.net/10.1111/ddi.12809

Bosch, S.; Tyberghein, L.; Deneudt, K.; Hernandez, F.; De Clerck, O. (2018). In search of relevant predictors for marine species distribution modelling using the MarineSPEED benchmark dataset. Diversity Distrib. 24(2): 144-157. https://hdl.handle.net/10.1111/ddi.12668

Chaudhary, C.; Saeedi, H.; Costello, M.J. (2017). Marine species richness is bimodal with latitude: A reply to Fernandez and Marques. Trends Ecol. Evol. 32(4): 234–237. https://hdl.handle.net/10.1016/j.tree.2017.02.007

Dornelas, M.; Gotelli, N.J.; McGill, B.; Shimadzu, H.; Moyes, F.; Sievers, C.; Magurran, A.E. (2014). Assemblage time series reveal biodiversity change but not systematic loss. Science (Wash.) 344(6181): 296-299. http://hdl.handle.net/10.1126/science.1248484

Panasiuk, A.; Jazdzewska, A.; Slomska, A.; Irzycka, M. (2018). Genetic identity of two physonect siphonophores from Southern Ocean  waters – the enigmatic taxon Mica micula and Pyrostephos vanhoeffeni. J. Mar. Biol. Ass. U.K. Early view: 1-8. https://hdl.handle.net/10.1017/s0025315418000218

Rees, T.; Vandepitte, L.; Decock, W.; Vanhoorne, B. (2017). IRMNG 2006–2016: 10 years of a global taxonomic database. Biodiversity Informatics 12: 1-44. https://hdl.handle.net/10.17161/bi.v12i0.6522

Tittensor, D.P.; Mora, C.; Jetz, W.; Lotze, H.K.; Ricard, D.; Vanden Berghe, E.; Worm, B. (2010). Global patterns and predictors of marine biodiversity across taxa. Nature (Lond.) 466(7310): 1098-1101. https://hdl.handle.net/10.1038/nature09329

# USGS Provisional Software
This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the software.
