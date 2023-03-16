# An Open Software Development-based Ecosystem of R Packages for Metabolomics Data analysis

## Authors and Affiliations

- Andrea Vicini, Computational Biology and Bioinformatics, de Duve Institute, UCLouvain, Brussels, Belgium
- Roger Giné, Universitat Rovira i Virgili, Department of Electronic Engineering & IISPV, Tarragona, Spain
- Michele Stravs, Department of Environmental Chemistry, Eawag, Dübendorf, Switzerland; Institute of Molecular Systems Biology, ETH Zürich, Zürich, Switzerland
- Josep M. Badia, Universitat Rovira i Virgili, Department of Electronic
  Engineering & IISPV, Tarragona, Spain
- Carolin Huber, Department of Effect Directed Analysis, Helmholtz Center for
  Environmental Research, UFZ, Leipzig, Germany
- Liesa Salzer, Research Unit Analytical BioGeoChemistry, Helmholtz Munich,
  Neuherberg, Germany
- Jan Stanstrup, Department of Nutrition, Exercise and Sports, University of
  Copenhagen, Frederiksberg, Denmark
- Nir Shahaf, Department of Plant and Environmental Sciences, Weizmann Institute
  of Science, Rehovot, Israel
- Thomas Naake, Genome Biology Unit, European Molecular Biology Laboratory,
  Heidelberg, Germany
- Helge Hecht, RECETOX, Masaryk University, Brno, Czech Republic
- Steffen Neumann, Computational Plant Biochemistry, MetaCom, Leibniz Institute of Plant Biochemistry
- Michael Witting, Metabolomics and Proteomics Core, Helmholtz Munich,
  Neuherberg, Germany
- Sebastian Gibb, Anesthesiology and Intensive Care Medicine, University
  Hospital Greifswald, Greifswald, Germany
- Laurent Gatto, Computational Biology and Bioinformatics, de Duve Institute, UCLouvain, Brussels, Belgium
- Johannes Rainer, Institute for Biomedicine, Eurac Research, Bolzano, Italy


## Abstract

300 words.

Andrea Vicini, Roger Giné, Michele Stravs, Josep M Badia, Caroline Huber, Liesa
Salzer, Jan Stanstrup, Nir Shahaf, Thomas Naake, Helge Hecht, Steffen Neumann,
Micheal Witting, Sebastian Gibb, Laurent Gatto, Johannes Rainer


Lack of support, maintenance and further development is common with
scientific research software. In particular, development by a single researcher
can easily result in orphaned software packages, especially if combined with poor
documentation or lack of adherence to open software development standards.

The RforMassSpectrometry initiative aims to develop an efficient, thoroughly
documented and stable infrastructure for mass spectrometry (MS) data
analysis. As part of this initiative, a growing ecosystem of R software packages
was and is being developed covering different aspects of metabolomics and
proteomics data analysis. To avoid the aforementioned problems open shared
development, documentation, support and stability are emphasized.

At the heart of the package ecosystem is the `Spectra` package, that provides
the core infrastructure to handle MS data. Core functionality, which can be
easily re-used by other R software packages, is provided by the `MsCoreUtils`
and `MetaboCoreUtils` packages. Version 4 of the `xcms` package for LC-MS data
pre-processing is now based mainly on this new infrastructure hence gaining
support for additional data types, better data handling and support for ion
mobility data. Integration of the `xcms` package into the package ecosystem
simplifies complete analysis workflows which can include the `MsFeatures`
package for feature grouping, and the `MetaboAnnotation` package for annotation
of untargeted metabolomics data. Seamless integration of publicly available
annotation resources is possible through packages such as `MsBackendMassbank`,
`MsBackendMsp` or `CompoundDb`, the latter also allowing to
create and manage lab-specific annotation resources. `MsQuality` enables rapid,
efficient, and standardized quality assessment of MS data.

Finally, integration of Python based functionality, such as provided by the
`matchms` package, is possible through the `SpectriPy` package, and the
`SpectraQL` adds support for the MassQL common query language to
R/`Spectra`.


## Mentioned packages and (main) authors/contributors

- `CompoundDb` Jan Stanstrup, Josep M. Badia, Roger Giné, Andrea Vicini,
  Johannes Rainer.
- `MetaboAnnotation` Michael Witting, Andrea Vicini, Carolin Huber, Nir Shachaf,
  Johannes Rainer
- `MetaboCoreUtils` Michael Witting, Andrea Vicini, Liesa Salzer, Sebastian
  Gibb, Michael Stravs, Roger Giné, Johannes Rainer
- `MsBackendMassbank` Michael Witting, Johannes Rainer, Michael Stravs
- `MsBackendMsp` Steffen Neumann, Johannes Rainer, Michael Witting
- `MsCoreUtils` Laurent Gatto, Johannes Rainer, Sebastian Gibb, Thomas Naake,
  Josep M. Badia, Micheal Witting, Roger Giné.
- `MsFeatures` Johannes Rainer
- `MsQuality` Thomas Naake, Johannes Rainer
- `Spectra` Laurent Gatto, Johannes Rainer, Sebastian Gibb, Jan Stanstrup
- `SpectraQL` Johannes Rainer, Andrea Vicini, Sebastian Gibb
- `SpectriPy` Michael Witting, Johannes Rainer, Carolin Huber, Helge Hecht
- `xcms` Steffen Neumann, Johannes Rainer, Roger Giné, Jan Stanstrup

## Authors by number of packages

- Johannes Rainer (12)
- Michael Witting (6)
- Sebastian Gibb (4)
- Andrea Vicini (4)
- Roger Giné (4)
- Jan Stanstrup (3)
- Josep M Badia (2)
- Carolin Huber (2)
- Nir Shachaf (1)
- Michael Stravs (2)
- Steffen Neumann (2)
- Laurent Gatto (2)
- Liesa Salzer (1)
- Thomas Naake (2)
- Helge Hecht (1)
