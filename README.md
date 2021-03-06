## subdomainPy: Python scripts for Subdomain Modeling in ADCIRC+SWAN
----
**subdomainPy:** A repository of Python 2 scripts that allow users to extract subdomain grids and generate full and subdomain input files including control file, grid information file, nodal attributes file, SWAN control file, and ADCIRC+SWAN boundary condition files.

**Subdomain Modeling:** An exact reanalysis technique for ADCIRC+SWAN that enables the assessment of local *subdomain* changes with less computational effort than would be required by a complete resimulation of the full domain. So long as the subdomain is large enough to fully contain the altered hydrodynamics, multiple local changes may be simulated within it without the need to calculate new boundary conditions (Baugh et al., 2015).

![breaches](https://github.com/alperaltuntas/subdomainPy/blob/master/doc/breaches.png)

### Home Page:
- [Subdomain Modeling Home Page](http://www4.ncsu.edu/~jwb/subdomain/)

### Manual:
- [Subdomain Modeling User Manual](https://github.com/alperaltuntas/subdomainPy/blob/master/doc/userManual.pdf)

### Download:
    $ git clone https://github.com/ncsu-ce/subdomainPy.git
