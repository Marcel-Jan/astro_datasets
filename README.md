## Astronomy and space related (downloadable) datasets

This is a list of astronomy and space related (downloadable if possible) datasets. When I'm learning new ways of working with data, I like to use astronomy and space related datasets to play with. For example, I used the asteroids dataset of the Minor Planet Center to learn how to use the pandas, matplotlib and sklearn libraries in Python (see https://youtu.be/iXjJNc8zGsM and https://youtu.be/mWxAq1NmKsU). 


### Asteroids by the Minor Planet Center. 
| Item | Info |
| ----- | ---- |
| Name | All the asteroids with calculated orbits contained in the MPC database |
| Content description | Orbital data of all know asteroids. Observational data. |
| Provider |  Minor Planet Center |
| Location |  http://www.minorplanetcenter.net/data |
| Formats | Fortran (.DAT), JSON (has extended data) | 
| Retrieval | plain download |
| Size | 81 MB (extended set, compressed with gz), 450 MB (extended set, unzipped) |
| Partitioned | No |
| Records | about 750,000 |
| Updates | The extended dataset is updated daily. |
| Documentation | http://minorplanetcenter.net/Extended_Files/Extended_MPCORB_Data_Format_Manual.pdf |


### GAIA - GAIA DR1, DR2, DR3 Source  
| Item | Info |
| ----- | ---- |
| Name | GAIA DR1, DR2, DR3  |
| Content description | The full astrometric solution — positions on the sky (α, δ), parallax, and proper motion — for around 1.46 billion (1.46 109) sources, with a limiting magnitude of about G ≈ 21 and a bright limit of about G ≈ 3. The astrometric solution is accompanied with some new quality indicators, like RUWE, and source image descriptors.
positions.  |
| Provider | ESA  |
| Location | https://gea.esac.esa.int/archive/  |
| Formats | CSV, FITS, Votable  |
| Retrieval | Plain download  |
| Size | |
| Partioned | Yes, files of 40 MB (CSV)  |
| Records | Variability analysis, together with the underlying epoch photometry, for 10.5 million sources. Apart from classification into 24 variability classes, detailed variability results are provided in separate tables. More info here: https://www.cosmos.esa.int/web/gaia/dr3  |
| Updates | Dataset DR2 was published 25 april 2018), DR3 on 13 june 2022  |
| Documentation | https://www.cosmos.esa.int/web/gaia/dr1, https://gea.esac.esa.int/archive/documentation/GDR2/Gaia_archive/chap_datamodel/sec_dm_main_tables/ssec_dm_gaia_source.html |


### LIGO  
| Item | Info |
| ----- | ---- |
| Name | LIGO and VIRGO data  |
| Content description |  Gravitational wave data  |
| Provider | LIGO  |
| Location | https://losc.ligo.org/data/  |
| Formats | HDF5 and JSON  |
| Retrieval | Make selection on the site, then download  |
| Size | ?  |
| Partioned | ?  |
| Records | ?  |
| Updates | In releases after certain amount of time.  |
| Documentation | https://losc.ligo.org/data/#yellow_box, https://losc.ligo.org/tutorials/  |


### Supernovae
| Item | Info |
| ----- | ---- |
| Name | The Open Supernovae Catalog |
| Content description | The goal of this catalog is to act as a centralized, open repository for supernova metadata, light curves, and spectra. |
| Provider | The Open Supernovae Catalog. Unfortunately the domain sne.space is no longer available. But the data is available on Github and can be downloaded with a the [https://github.com/astrocatalogs/astrocats](AstroCats) catalog generation package|
| Location | [https://sne.space/download/](https://github.com/astrocatalogs/supernovae) |
| Formats | JSON |
| Retrieval | Plain download, Python package [https://github.com/astrocatalogs/astrocats](AstroCats) |
| Size | ? |
| Partioned | On ranges of years |
| Records | ? |
| Updates | Yes. Whenever supernovae occur | 
| Documentation | https://github.com/astrocatalogs/supernovae?tab=readme-ov-file |


### CosmoSim  
| Item | Info |
| ----- | ---- |
| Name | CosmoSim |
| Content description | The CosmoSim database provides results from cosmological simulations performed within different projects: MultiDark and Bolshoi, CLUES, and Galaxies.  |
| Provider | Leibniz-Institute for Astrophysics Potsdam (AIP) |
| Location | https://www.cosmosim.org/ |
| Formats | CSV, XML |
| Retrieval | Registration, then a SQL query needs to be written |
| Size | Several terabytes ? |
| Partioned | No. Need to write SQL query |
| Records | ? |
| Updates | Presumably after new simulations| 
| Documentation | https://www.cosmosim.org/cms/documentation/demos-and-tutorials/first-steps-with-cosmosim/ |


### Fireball and Bolide Data  
| Item | Info |
| ----- | ---- |
| Name | Fireball and bolide data |
| Content description | Exceptionally bright meteors that are spectacular enough to to be seen over a very wide area. Provided by U.S. Government sensors. API available via https://ssd-api.jpl.nasa.gov/doc/fireball.html |
| Provider | NASA Center for Near Earth Object Studies |
| Location | https://cneos.jpl.nasa.gov/fireballs/ |
| Formats | CSV, Excel, API |
| Retrieval | Plain download |
| Size | 53 KB |
| Partioned | No |
| Records | 735 |
| Updates | Yes. When new occurrences happen | 
| Documentation | https://cneos.jpl.nasa.gov/fireballs/ (Click "Table Column Descriptions") |


### Meteorite landings  
| Item | Info |
| ----- | ---- |
| Name | Meteorite Landings |
| Content description | information on all of the known meteorite landings. The data is location oriented. |
| Provider | NASA |
| Location | https://data.nasa.gov/dataset/meteorite-landings  |
| Formats | CSV, RDF, XML and JSON |
| Retrieval | Download or API  |
| Size | 4 MB (CSV), 12,6 MB (JSON)  |
| Partioned | No  |
| Records | about 45,000  |
| Updates | Yes.  |
| Documentation | Not known  |


### HYG Stellar database
| Item | Info |
| ----- | ---- |
| Name | HYG Stellar database |
| Content description | "The HYG database (v3.0) is a compilation of interesting (to me, anyway) stellar data from a variety of catalogs. It is useful for background information on all sorts of data: star names, positions, brightnesses, distances, and spectrum information. It also powers the charts elsewhere on this site." |
| Provider | David Nash |
| Location | http://www.astronexus.com/hyg, https://github.com/astronexus/HYG-Database |
| Formats | CSV |
| Retrieval | Plain download |
| Size | 33 MB |
| Partioned | No |
| Records | 119615 |
| Updates | Last on 3 years ago | 
| Documentation | http://www.astronexus.com/hyg |

### Exoplanets
| Item | Info |
| ----- | ---- |
| Name | NASA Exoplanet Archive |
| Content description | Confirmed exoplanets |
| Provider | NASA |
| Location | https://exoplanetarchive.ipac.caltech.edu/, https://exoplanetarchive.ipac.caltech.edu/bulk_data_download/ (bulk) |
| Formats | CSV (web interface), PDF (obtainable with wget) |
| Retrieval | Via table in web interface or in bulk with wget |
| Size | 1 MB (simple table in CSV),  ? (bulk) |
| Partioned | Bulk: per exoplanet |
| Records | 34031 (Summary reports in PDF) |
| Updates | When new discoveries occur | 
| Documentation | https://exoplanetarchive.ipac.caltech.edu/docs/API_exoplanet_columns.html, http://irsa.ipac.caltech.edu/docs/batch_download_help.html (wget) |

Got anything to add to this list? Send a mail to astro_datasets@marcel-jan.eu.


### Template
| Item | Info |
| ----- | ---- |
| Name |  |
| Content description |  |
| Provider |  |
| Location |  |
| Formats |  |
| Retrieval |  |
| Size |  |
| Partioned |  |
| Records |  |
| Updates |  | 
| Documentation |  |


