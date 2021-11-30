# MOONS

Different files used to create mock spectra catalogs with CIGALE on the COSMOS field. the notebook File_to_CIGALE-format.ipynb contains the procedure to get a sample of objects from the COSMOS2015 catalog and correct the photometric data. Also the FMOS-COSMOS spectroscopic data. In general it can be use to convert the COSMOS2015 catalog and obtain larger samples without matching to a spectroscopic catalog. 

Notes on the gas-phase metallicity, ionization parameter and reshfit subdivision of the sample to be fitted with CIGALE are also explained. This is important when modeling continuum and emission lines. Modeling continuum-only is easier as the nebular module does not need to be taken into account. The sub-division in metallicity bins after SED fitting the sample and obtaining SFR and stellar mass is straightforward.

# Acknowledgements

These notebooks are created for the working groups of the MOONS consortium. This is part of my Ph.D. thesis (http://www.theses.fr/s210961) at LAM (https://www.lam.fr/?lang=en) funded by AMIDEX (https://www.univ-amu.fr/en/public/amidex-team).

# License

The code is released under an MIT license. MIT is a short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications and larger works may be distributed under different terms and without source code.
