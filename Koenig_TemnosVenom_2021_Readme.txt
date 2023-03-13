This Koenig_TemnosVenom_2021_readme.txt file was generated on 20221214 by Phoebe Koenig

-------------------
GENERAL INFORMATION
-------------------

Title of Dataset: Data from: Testing optimal defense theory in a social insect: increased risk results in increased venom investment

Author Information (Name, Institution, Address, Email)

	Principal Investigator: Phoebe A. Koenig, Cornell University, pak98@cornell.edu, ORCID id: 0000-0001-9702-7784 
	Associate or Co-investigator: Corrie S. Moreau, Cornell University, Comstock Hall, corrie.moreau@cornell.edu, ORCID id: 0000-0003-1139-5792


Date of data collection (single date, range, approximate date): 20200503 - 20210220 <format YYYYMMDD>

Geographic location of data collection: Ithaca, NY, Tompkins County, Comstock Hall, Cornell University

Information about funding sources or sponsorship that supported the collection of the data: This research was supported by an NSF GRFP awarded to Phoebe Koenig, as well as research grants from Cornell Sigma Xi, Sigma Xi, and the Tschinkel Award from IUSSI-NAS.


--------------------------
SHARING/ACCESS INFORMATION
--------------------------

Licenses/restrictions placed on the data, or limitations of reuse: CC-BY (NC)

Recommended citation for the data:
 
Citation for and links to publications that cite or use the data:

Links to other publicly accessible locations of the data:

Links/relationships to ancillary or related data sets:


--------------------
DATA & FILE OVERVIEW
--------------------

File list (filenames, directory structure (for zipped files) and brief description of all data files):
Koenig_TemnosVenom_2021.csv ;This file has body measurements and venom sac measurements for individual Temnothorax longispinosus ants along with census information from their nests

Relationship between files, if important for context:

Additional related data collected that was not included in the current data package:

If data was derived from another source, list source:

If there are there multiple versions of the dataset, list the file updated, when and why update was made:


--------------------------
METHODOLOGICAL INFORMATION
--------------------------

Description of methods used for collection/generation of data: <Include links or references to publications or other documentation containing experimental design or protocols used in data collection>

Methods for processing the data: <describe how the submitted data were generated from the raw or collected data>

Software- or Instrument-specific information needed to interpret the data, including software and hardware version numbers:

Standards and calibration information, if appropriate:

Environmental/experimental conditions:

Describe any quality-assurance procedures performed on the data: 

People involved with sample collection, processing, analysis and/or submission:
Sample collection involved: Phoebe Koenig
Processing and Analysis: Phoebe Koenig, with help from Lynn Johnson at the Cornell Statistical Consulting Unit


--------------------------
DATA-SPECIFIC INFORMATION <Create sections for each datafile or set, as appropriate>
--------------------------

File: Koenig_TemnosVenom_2021.csv

Number of variables: 19

Number of cases/rows: 2357

Variable list, defining any abbreviations, units of measure, codes or symbols used:

Date.Collected.D.M: (DD-Month-YYYY) Date on which colony was collected. Year should always be 2021.

Date.Dissected.D.M: (DD-Month-YYYY) Date on which ant was dissected to measure venom sac. Year should be 2021 or 2022.

Date.Collected.Year: (YYYY) Year in which colony was collected. Should be 2021 for every colony.

Colony: The colony number identifier. Technically, this is a nest, not a colony.

Adult.Count: The number of adults in the nest on the day it was censused

Queen.Count: The number of queens without wings in the nest on the day it was censused

Larvae.Count: The number of larvae in the nest on the day it was censused. This number could be an underestimate as larvae can be small and hard to count

Pupae.Count: The number of pupae in the nest on the day it was censused Males.Count : The number of males in the nest on the day it was censused

Winged.Queen.Count: The number of unmated, winged queens in the nest on the day it was censused

Egg.Count: The number of eggs in the nest on the day it was censused. This number could be an underestimate as eggs are small and hard to count

Worker.Queen: Whether the dissected ant was a worker or a queen

Behavior.Code: If Worker.Queen=="Worker", this is either Nurse or Forager. If Worker.Queen=="Queen", this is either Mated or Unmated. Mated means the queen was counted in the Queen.Count and did not have wings. Unmated means the queen was either counted in Winged.Queen.Count or hatched while the colony was in the lab, and had wings. For both workers and queens, we also have the option pupa, which is where I dissected a pupa. There are not very many of them and I exclude these data for analyses

Callow: (Binary) was the individual dissected callow? 1 if yes, 0 if not

Webers.Length.mm: Weber's length in mm

Venom.Sac.Length.mm: Length of venom sac in mm

Venom.Sac.Width.mm: Width of venom sac in mm

Ant: Ant number (identifier)


Missing data codes: NA- data was not collected

Specialized formats or other abbreviations used: