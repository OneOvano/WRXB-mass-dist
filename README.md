# WRXB-mass-dist
 Mass distribution for WR, NS and BH for close binaries from Milky Way and some Local Group galaxies 

catalogs/ - catalogues used in the work. Each catalog contains the following file:

1) ReadMe - description of the catalog structure

2) *.dat - catalog file

3) *.pdf - article on this catalog (if available)

  catalogs/HMXB_N23 - "XRBcats: Galactic High Mass X-ray Binary Catalogue" by Neumann et al. (2023)

  catalogs/HMXB_F23 - "A catalogue of high-mass X-ray binaries in the Galaxy: from the INTEGRAL to the Gaia era" by Fortin et al. (2023)

  catalogs/LMXB_A23 - "XRBcats: Galactic low-mass X-ray binary catalogue" by Avakyan et al. (2023)

  catalogs/LMXB_F24 - "A catalogue of low-mass X-ray binaries in the Galaxy: From the INTEGRAL to the Gaia era" by Fortin et al. (2024)

  catalogs/WROB - "WR+OB close binaries of MW, LMC and SMC catalog" by Shaposhnikov (in progress)

catalogs/updates - last updates for some objects parameters estimation

dist-testing.ipynb - testing distribution recovery algorithms on artificial distributions

WRXB-mass-dist.ipynb - code for constructing mass distributions for WR stars and compact objects in CBS. Conceptually contains the following elements:

  1) Data preparation: combining data from available catalogs, extracting necessary features

  2) Simple methods for analyzing distributions: histograms, KDE, sum of individual probability distributions. Testing hypotheses about the same mass distribution for HMXB and LMXB, statistical assessment of the significance of the "mass dip" (~2-5 solar masses), data grouping

  3) Methods for reconstructing distributions based on neural networks - VAE, GAN, NF (in progress)

  4) Comparison of the results of simple and complex methods, final reconstruction of distributions

  5) Construction of the mass distribution of CO cores of WR stars at the time of collapse. The calculation is based on simple relationships, includes mass loss
  
  6) Comparison of the constructed mass distributions for NS, BH and WR's CO-cores in TDS, construction of a possible transformation from the mass distribution of CO-cores to the mass distribution of compact objects

  7) Conclusions

README.md - this description
