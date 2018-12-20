
<link rel="stylesheet" href="/css/style.css">
# MS-FINDER tutorial

### Abstract

The purpose of metabolomics is to perform the 'comprehensive' analysis for small biomolecules of
living organisms. Gas chromatography coupled with electron ionization mass spectrometer (GC/MS)
and liquid chromatography coupled with electrospray ionization- (ESI-) tandem mass spectrometer
(LC/MS/MS) are the preferred tools for untargeted metabolomics. Currently, the main bottleneck of
GC/MS- and LC/MS/MS based untargeted analysis is compound identification due to the limitation of
EI-MS and MS/MS records of authentic standard.

MS-FINDER was launched as a universal program for compound 'annotation' that supports
EI-MS (GC/MS) and MS/MS spectral mining. First, MS-FINDER aims to provide solutions for 1)
formula predictions, 2) fragment annotations, and 3) structure elucidations by means of unknown
spectra. In addition, the program can annotate your unknowns by the public spectral databases such as
MassBank, LipidBlast, and GNPS. MS-FINDER has been developed as the collaborative work
between Prof. Masanori Arita team (RIKEN, Reifycs Inc.) and Prof. Oliver Fiehn team (UC Davis)
supported by the JST/NSF SICORP 'Metabolomics for the low carbon society' project.

![MS-FINDER screenshot](/MS-FINDER/images/scrMsDial1.png)

## Table of contents

- [Software environments](#Software environments)
- Required programs
- Acceptable ASCII formats
	* MSP format for MS/MS
	* MSP format for EI-MS
	* MAT format
	* Adduct ion format: [M+Na]+, [M+2H]2+, [M-2H2O+H]+, [2M+FA-H]-, etc.
	* User defined structure database format
	* Specific field to fix the formula element count
- Import queries
	- A. From a folder which includes MSP or MAT format files
	- B. From the graphical user interface of the MS-FINDER program
	- C. From the MS-DIAL program
- Parameter setting
	- Method tab
	- Mass spectrum tab
	- Formula finder tab
	- Structure finder tab
	- Data source tab
- Compound annotation by in silico fragmenter
- Compound annotation by searching spectral databases
- FSEA: fragment set enrichment analysis
- Compound annotation (batch analysis)
- Peak assignment (single)
- Peak assignment (batch job)
- Molecular spectrum networking
- Mouse function
- Export
- Help

### Software environments
+ Windows OS (.NET Framework 4.5 or later): Windows 7 or later
+ RAM: 8.0 GB or more

