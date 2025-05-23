**CASA**, the Common Astronomy Software Applications, serves as the primary data processing software for the Atacama Large Millimeter/submillimeter Array (ALMA) and Karl G. Jansky Very Large Array (VLA), and is often used by other radio telescopes. 

The CASA organization on GitHub contains prototype packages that the CASA team is developing for the next generation of radio telescopes (such as the [ngVLA](https://ngvla.nrao.edu/) and [ALMA WSU](https://science.nrao.edu/facilities/alma/science_sustainability/wideband-sensitivity-upgrade)), along with other ancillary packages related to production CASA (such as documentation). The production CASA code is hosted on [Bitbucket](https://open-bitbucket.nrao.edu/projects/CASA/repos/casa6/browse).

# Useful links:
- [Download CASA](https://casa.nrao.edu/casa_obtaining.shtml)
- [CASA documentation](https://casadocs.readthedocs.io/en/stable/)
- [CASA Repository](https://open-bitbucket.nrao.edu/projects/CASA/repos/casa6/browse)

# Prototype Packages Being Developed:
These prototype packages are still under development and will be rapidly changing, however, some have progressed to the stage where tutorials are available.

| Package  | Description | Tutorial Available |
| -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------ |
| [astrohack](https://github.com/casangi/astrohack)  | Antenna panel and position corrections.                   | [Yes](https://astrohack.readthedocs.io/en/stable/tutorial_vla.html)|
| [casagui](https://github.com/casangi/casagui)      | CASA GUI desktop.                                         | [Yes](https://github.com/casangi/casagui)|
| [graphviper](https://github.com/casangi/graphviper)| Dask based MapReduce for Multi-Xarray datasets.           | [Yes](https://graphviper.readthedocs.io/en/latest/graph_building_tutorial.html)|
| [astroviper](https://github.com/casangi/astroviper)| Radio interferometry data processing.                     | No |
| [xradio](https://github.com/casangi/xradio)        | Xarray radio astronomy data IO.                           | No |
| [cloudviper](https://github.com/casangi/cloudviper)| Cloud-native container orchestration system configurations| No |
| [toolviper](https://github.com/casangi/toolviper) | Radio astronomy processing tools using the VIPER framework| [Yes](https://github.com/casangi/toolviper)

# Production CASA Packages:

| Package                                                                                      | Description                                          |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [](https://github.com/casangi/casadocs)[casadocs](https://github.com/casangi/casadocs)       | CASA documentation. |
| [](https://github.com/casangi/examples)[examples](https://github.com/casangi/examples)       | Examples of how to use CASA.                          |
| [](https://github.com/casangi/casabench)[casabench](https://github.com/casangi/casabench)    | Tracking performance metrics of CASA.                 |
| [](https://github.com/casangi/casaconfig)[casaconfig](https://github.com/casangi/casaconfig) | Reference data and converters for CASA operation.     |

We welcome feedback at [casa-feedback@nrao.edu](casa-feedback@nrao.edu).
