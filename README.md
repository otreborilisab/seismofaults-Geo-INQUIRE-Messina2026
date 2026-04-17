# seismofaults-Geo-INQUIRE-Messina2026

Repository containing Jupyter Notebooks to demonstrate access and usage of the EFEHR European Fault-Source Model 2020 Web services (OGC WFS) at the GEO-INQUIRE Workshop in Messina, Italy, April 2026 (https://www.geo-inquire.eu/dissemination/workshops/hazard-modelling).

See the EDSF web portal (https://seismofaults.eu/efsm20) for more information about the datasets.

## Web Services (Geo-INQUIRE installation VA2-33-1)

EFSM20 (geometry and activity parameters) OGC Web Feature Service
https://services.seismofaults.eu/EFSM20/ows?service=WFS&request=getCapabilities

EFSM20 Meshes (3D triangular meshes) OGC Web Feature Service
https://services.seismofaults.eu/EFSM20_Meshes/ows?service=WFS&request=GetCapabilities

## References
>Basili, R., Danciu, L., Beauval, C., Sesetyan, K., Vilanova, S. P., Adamia, S., Arroucau, P., Atanackov, J., Baize, S., Canora, C., Caputo, R., Carafa, M. M. C., Cushing, E. M., Custódio, S., Demircioglu Tumsa, M. B., Duarte, J. C., Ganas, A., García-Mayordomo, J., Gómez de la Peña, L., Gràcia, E., Jamšek Rupnik, P., Jomard, H., Kastelic, V., Maesano, F. E., Martín-Banda, R., Martínez-Loriente, S., Neres, M., Perea, H., Šket Motnikar, B., Tiberti, M. M., Tsereteli, N., Tsironi, V., Vallone, R., Vanneste, K., Zupančič, P., and Giardini, D. (2024). The European Fault-Source Model 2020 (EFSM20): geologic input data for the European Seismic Hazard Model 2020, Nat. Hazards Earth Syst. Sci., https://doi.org/10.5194/nhess-24-3945-2024

>Basili R., Danciu L., Beauval C., Sesetyan K., Vilanova S., Adamia S., Arroucau P., Atanackov J., Baize S., Canora C., Caputo R., Carafa M., Cushing M., Custódio S., Demircioglu Tumsa M., Duarte J., Ganas A., García-Mayordomo J., Gómez de la Peña L., Gràcia E., Jamšek Rupnik P., Jomard H., Kastelic V., Maesano F. E., Martín-Banda R., Martínez-Loriente S., Neres M., Perea H., Sket-Motnikar B., Tiberti M. M., Tsereteli N., Tsironi V., Vallone R., Vanneste K., Zupančič P. (2022). European Fault-Source Model 2020 (EFSM20): online data on fault geometry and activity parameters [Data set]. Istituto Nazionale di Geofisica e Vulcanologia (INGV). https://doi.org/10.13127/efsm20

>Basili R., Taccone R., Vallone R., Maesano F. E. (2024). European Fault-Source Model 2020 (EFSM20): 3D triangular meshes [Data set]. Istituto Nazionale di Geofisica e Vulcanologia (INGV). https://doi.org/10.13127/efsm20/meshes

## Setup
Set up a virtual environment with the following dependencies:

#!pip install -q matplotlib geopandas shapely pandas requests numpy math scipy owslib ipyleaflet ipywidgets "pyvista[jupyter]" trame

If running on conda, please refer to 
https://docs.conda.io/projects/conda/en/4.6.1/user-guide/tasks/manage-environments.html

## Acknowledments
The notebooks were created by

>Roberto Basili
>
>Istituto Nazionale di Geofisica e Vulcanologia
>
>Via di Vigna Murata, 605 - 00143 Roma, Italy
>
>https://orcid.org/0000-0002-1213-0828


With contributions by

>Rita Chiara Taccone, Francesco E. Maesano, Antonio Scala
>
>Istituto Nazionale di Geofisica e Vulcanologia


The notebooks are provided free for use via a GNU General Public License v 3.0

Geo-INQUIRE is funded by the European Commission under project number 101058518 within the HORIZON-INFRA-2021-SERV-01 call.
