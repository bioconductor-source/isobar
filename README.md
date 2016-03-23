isobar - R package for iTRAQ and TMT proteomics data
================================================================================================

isobar provides methods for preprocessing, normalization, and  
report generation for the analysis of proteomics data generated by Mass 
spectrometers using isobaric peptide tags, such as iTRAQ and TMT. 
PDF and Excel reports can automatically be generated based on a configuration file.
Include modules for validating and integrating data focussing on 
post-translational protein modifications (isobar-PTM).

## Installation

The official Bioconductor version can be found at http://bioconductor.org/packages/release/bioc/html/isobar.html

To install isobar from Bioconductor, call

    ## try http:// if https:// URLs are not supported
    source("https://bioconductor.org/biocLite.R")
    biocLite("isobar")

To install the development version of isobar, the easiest way is using the devtools package:

    ## install.package("devtools") # if you do not have the devtools package
    devtools::install_github("fbreitwieser/isobar")

The following packages are suggested for some uses in isobar, and maybe should be installed as well: MSnbase, OrgMassSpecR, biomaRt, Hmisc, gplots and limma.

## References

- Florian P. Breitwieser, André Müller, Loïc Dayon, Thomas Köcher, Alexandre Hainard,  Peter Pichler, Ursula Schmidt-Erfurth, Giulio Superti-Furga, Jean-Charles Sanchez, Karl Mechtler, Keiryn L. Bennett, and Jacques Colinge (June 2011). “General statistical modeling of data from protein relative expression isobaric tags.” In: J Proteome Res
10.6, pp. 2758–2766 
- Florian P. Breitwieser and Jacques Colinge (Sept. 2013). “Isobar(PTM): a software tool for the quantitative analysis of post-translationally modified proteins.” eng.  In: J Proteomics 90, pp. 77–84

For publications citing isobar please see Google scholar for [isobar](https://scholar.google.at/scholar?cites=3978696839477939063&as_sdt=20000005&sciodt=0,21&hl=de) and [isobar PTM](https://scholar.google.at/scholar?cites=988743004087549055&as_sdt=20000005&sciodt=0,21&hl=de).

Many thanks to Alexey Stukalov, Xavier Robin and Florent Gluck who contributed to the development of the package.
