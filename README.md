# The GALAH Survey: Data Release 4

Sven Buder (ANU & ASTRO 3D, sven.buder@anu.edu.au) and the GALAH Collaboration (2024)

## Abstract

The stars of the Milky Way carry the chemical history of our Galaxy in their atmospheres as they journey through its vast expanse. Like barcodes, we can extract the chemical fingerprints of stars from high-resolution spectroscopy. The fourth data release (DR4) of the Galactic Archaeology with HERMES (GALAH) Survey, based on a decade of observations, provides the chemical abundances of up to 32 elements for 917\,588 stars that also have exquisite astrometric data from the $Gaia$ satellite. For the first time, these elements include life-essential nitrogen to complement carbon, and oxygen as well as more measurements of rare-earth elements critical to modern-life electronics, offering unparalleled insights into the chemical composition of the Milky Way.

For this release, we use neural networks to simultaneously fit stellar parameters and abundances across the full spectrum, leveraging synthetic grids computed with Spectroscopy Made Easy. These grids account for atomic line formation in non-local thermodynamic equilibrium for 14 elements. In a two-iteration process, we first fit stellar labels for all 1\,085\,520 spectra, then co-add repeated observations and refine these labels using astrometric data from $Gaia$ and 2MASS photometry, improving the accuracy and precision of stellar parameters and abundances. Our validation thoroughly assesses the reliability of spectroscopic measurements and highlights key caveats for catalogue users.

GALAH DR4 represents yet another milestone in Galactic archaeology, combining detailed chemical compositions from multiple nucleosynthetic channels with kinematic information and age estimates. The resulting dataset, covering nearly a million stars, opens new avenues for understanding not only the chemical and dynamical history of the Milky Way, but also the broader questions of the origin of elements and the evolution of planets, stars, and galaxies.

## Data Access

**Data Products**: All public data products can be found at https://cloud.datacentral.org.au/teamdata/GALAH/public/GALAH_DR4/ as FITS files or for automated download.  
**Data Analysis Code**: The public data analysis repository can be found at https://github.com/svenbuder/GALAH_DR4.  
**Interactive access**: provided via DataCentral here: https://docs.datacentral.org.au/galah.  

## How to Cite

Please cite this work as follows:

```bibtex
@article{Buder2024b,
    author = {{Buder}, S., {Kos}, J., {Wang}, E.~X., {McKenzie}, M., {Howell}, M., {Martell}, S.~L., {Hayden}, M.~R., {Zucker}, D.~B., {Nordlander}, T., {Montet}, B.~T., {Traven}, G., {Bland-Hawthorn}, J., {De~Silva}, G.~M., {Freeman}, K.~C., {Lewis}, G.~F., {Lind}, K., {Sharma}, S., {Simpson}, J.~D., {Stello}, D., {Zwitter}, T., {Amarsi}, A.~M., {Armstrong}, J.~J., {Banks}, K., {Beavis}, M.~A., {Beeson}, K., {Chen}, B., {Ciuc{\u{a}}}, I., {Da~Costa}, G.~S., {de~Grijs}, R., {Martin}, B., {Nataf}, D.~M., {Ness}, M.~K., {Rains}, A.~D., {Scarr}, T., {Vogrin{\v{c}}i{\v{c}}}, R., {Wang}, Z., {Wittenmyer}, R.~A., {Xie}, Y., {The GALAH Collaboration}},
    title = {The GALAH Survey: Data Release 4},
    journal = {arXiv e-prints},
    volume = {abs/2409.19858)},
    month = apr,
    pages = {arXiv:2409.19858},
    year = {2024},
    archivePrefix = {arXiv},
    eprint = {2409.19858},
    keywords = {Surveys -- the Galaxy -- methods: observational -- methods: data analysis -- stars: fundamental parameters -- stars: abundances},
    doi = {10.48550/arXiv.2409.19858},
    primaryClass = {astro-ph.GA},
    adsurl = {https://ui.adsabs.harvard.edu/abs/2024arXiv240919858B},
}
```
