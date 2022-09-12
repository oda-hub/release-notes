Send to SDSC, ANTARES, GWOSC, SDSS/LegacySurvery (if possible) INTEGRAL collaborations and all users

----


# Release notes MMODA 22.09.0000

## What is MMODA

The Multi-Messenger Online analysis is an [open-source](https://github.com/oda-hub) **cloud-native platform** to derive **high-level scientific products for several astrophysical instruments**.
A [web-based interface](http://astro.unige.ch/mmoda/) and a [python API](https://oda-api.readthedocs.io/en/latest/user_guide/tutorial_main.html) allow the users to run easily the underlying services, which run complex pipelines in a computer cluster based at the University of Geneva. These pipelines have been developed by experts in the data analysis and exploit proximity to the data combined with state-of-the-art calibration and software.

Currently, MMODA provides data from:
* the [INTEGRAL](https://www.isdc.unige.ch/integral/) X- and gamma-ray observatory (for the instruments IBIS/ISGRI, JEM-X, and SPI-ACS),
* the gamma-ray mission [POLAR](https://www.astro.unige.ch/polar/), 
* the neutrino experiment [ANTARES](https://antares.in2p3.fr/),
* the gravitational wave experiments [LIGO and Virgo](https://www.gw-openscience.org/),
* the optical/IR [DESI LegacySurvey](https://www.astro.unige.ch/mmoda/help/mmoda/legacy-survey).

MMODA is developed joinly by [UNIGE Department of Astronomy](https://www.unige.ch/sciences/astro/en/), [EPFL LASTRO Laboratory](https://www.epfl.ch/labs/lastro), [UniParis APC](https://apc.u-paris.fr/APC_CS/en), [Kyiv Academic University](https://kau.org.ua/en), with some support of [SDSC EPFL](https://www.epfl.ch/research/domains/sdsc/).

<a  href="/mmoda/"
    title="Home"> <img
    src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo.png" alt="Home"
    width="100px" /></a>
<a  href="https://www.unige.ch/sciences/astro/en/"
    title="Departement of Astronomy - university of Geneva"><img
    src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo-fac-sciences.png" alt="Departement of Astronomy - university of Geneva" 
    width="100px" /></a>
<a  href="https://www.isdc.unige.ch/integral/"
    title="The INTErnational Gamma-Ray Astrophysics Laboratory - INTEGRAL"><img
    src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo-isdc.png" alt="The INTErnational Gamma-Ray Astrophysics Laboratory - INTEGRAL" 
    width="100px" /></a>
<a  href="https://www.epfl.ch/labs/lastro"
    title="Laboratory of Astrophysics (LASTRO) - EPFL"><img
    src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo-epfl.png" alt="Laboratory of Astrophysics (LASTRO) - EPFL"
    width="100px"/></a>
<a href="https://apc.u-paris.fr/APC_CS/en" target="_blank"
   title="Laboratoire AstroParticule et Cosmologie (APC)"><img
   src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo-apc.png" alt="Laboratoire AstroParticule et Cosmologie (APC)"
   width="30px"/></a>
<a href="https://kau.org.ua/en" target="_blank"
   title="Kyiv Academic University (KAU)"><img
   src="https://www.astro.unige.ch/mmoda/sites/all/themes/bootstrap_mmoda/logo-kau.png" alt="Kyiv Academic University (KAU)" 
   width="50px"/></a>
      

## Changes in MMODA 22.09.0000

`22.09.0000` is a major release, adding several new major features, and improving user experience.

## New instruments and integration

* Added [Gravitatitional Wave analysis](https://www.astro.unige.ch/mmoda/help/mmoda/gravitational-wave-analysis) based on [GWOSC](https://www.gw-openscience.org/) analysis threads.
* Added visible and infrared photometry from [DESI LegacySurvey](https://www.astro.unige.ch/mmoda/help/mmoda/legacy-survey) based on [NOIRLab](https://datalab.noirlab.edu/ls/dataAccess.php) TAP service.
* Added possibility to open the MMODA results in a JupyterLab analysis environment at [RenkuLab](https://renkulab.io/). 

## User experience improvements

* Some improvements in error reporting in frontend and API
* Some stability improvements

## Known limitations

Please consult https://github.com/oda-hub/known-issues for the list of known issues.

You may be interested to inspect [full list of closed issues](https://github.com/issues?q=org%3Aoda-hub+milestone%3Av22.07.0000) for this release.

## MMODA on the public marketplace

Discover [MMODA at EOSC marketplace](https://marketplace.eosc-portal.eu/services/astronomical-online-data-analysis-astrooda)
