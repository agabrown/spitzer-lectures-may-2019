# spitzer-lectures-may2019
Material from the Spitzer Lectures, Princeton University, May 2019

Anthony G.A. Brown<br/>
brown@strw.leidenuniv.nl

* [Lectures](#Lectures)
* [Related code](#related-code)
* [Related slide sets](#related-slides)

## <a name="Lectures">Lectures</a>

1. [Gaia: Celestial Inventory from the Solar System to the Milky Way](./gaia-dataproducts-and-beyondgaia/gaia-dataproducts-and-beyondgaia.pdf) 
   * An overview of the Gaia mission is provided with brief descriptions of the spacecraft,
     scientific instruments, and the way data are collected on-board Gaia. This is followed by an
     overview of all the data products planned for current and future Gaia data releases and the
     plans for the extended Gaia mission. In the final part of the lecture I discuss future options
     for (space) astrometric surveys, including considerations on accuracy scaling and some of the
     difficulties to be solved when aiming for orders of magnitude improvement over Gaia. 
2. [Astrometry basics and the interpretation of astrometric data](./astrometry-basics-and-interpretation/astrometry-basics-and-interpretation.pdf)
   * The basics of astrometry are discussed in terms of the vector formulation used in the Hipparcos
     and Gaia data processing. The material is aimed at the use and interpretation of modern
     astrometric catalogue data but does not include a detailed treatment of astrometry and the
     astrometric measurement process. The second part of the lecture is aimed at the analysis of
     Gaia data, following the paper by [Luri et al.
     (2018)](https://doi.org/10.1051/0004-6361/201832964), with an emphasis on the responsible use
     of parallax data. The corresponding Python/R notebooks can be found
     [here](https://github.com/agabrown/astrometry-inference-tutorials).
3. [Gaia science tour](./gaia-science-tour/gaia-science-tour.pdf)
   * A selection of science results from Gaia DR1 and DR2 are discussed. This lecture is
     complementary to the colloquium.
4. [Ins and outs of Gaia DR2](./ins-and-outs-gaiadr2/ins-and-outs-gaiadr2.pdf)
   * An overview of the contents of Gaia DR2 is provided with an emphasis on the less well known
     aspects. Subsequently the following topics on the use and analysis of the catalogue data are
     discussed:
     * Uncertainties, uncertainty inflation, systematic errors
     * Known issues in Gaia DR2
     * Use of photometric and radial velocity data
     * Data quality filtering
     * Information useful in construction selection functions for Gaia
     * Propagation of source coordinates to other epochs and cross-matching
5. [Colloquium: Gaia: mission status and results from the second data release](./colloquium/colloquium-princeton-may2019.pdf)
   * I will present an overview of the Gaia mission status, followed by a summary of the Gaia DR2
     contents and the plans for Gaia DR3 and DR4 (more details in the [related slide set](#related-slides) below). The status of the mission extension is presented.
     This is complemented by highlights from the science harvested from Gaia DR2.
     
## <a name="related-code">Related code</a>

* Python/R [tutorials](https://github.com/agabrown/astrometry-inference-tutorials) from the [Luri et al.](https://doi.org/10.1051/0004-6361/201832964) paper on the use of parallaxes.
* [Python tools](https://github.com/agabrown/gaiadr2-ruwe-tools) for working with renormalized unit weight error (RUWE).
* [Example](https://github.com/agabrown/gaiadr2-6dgold-example) of data cleaning using the Gaia DR2 data quality indicators.

## <a name="related-slides">Related slide sets</a>

* Lindegren et al. (2018) slide set on [Gaia DR2
  astrometry](https://www.cosmos.esa.int/documents/29201/1770596/Lindegren_GaiaDR2_Astrometry_extended.pdf/1ebddb25-f010-6437-cb14-0e360e2d9f09)
* Slides from the 53rd ESLAB Symposium "The Gaia Universe" on the plans for Gaia DR3 and Gaia DR4
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2637972.svg)](https://doi.org/10.5281/zenodo.2637972)
