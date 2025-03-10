# TargetOrtho2_Python3
Files for the Python3 version of TargetOrtho2

Provided here are files for using the Python3 version of TargetOrtho2.
Essentially the only thing that has been changed from the original version is that the code has been changed to Python3. 
This version has all of the same functionality as the command line version of the original TargetOrtho2.
For instructions on installing and running the Python3 version of TargetOrtho2, see the attached manuscript TargetOrtho2_Protocol.pdf. 
For the original TargetOrtho2 developed by Glenwinkel et al., 2021 go to the following link: https://github.com/loriglenwinkel/TargetOrtho2.0
For instructions on installing and running the original version, see the preprint at the following link: https://bio-protocol.org/exchange/preprintdetail?id=2769&type=3&searchid=EP1734754216906950&sort=0

In this repository we have provided three options for running the Python3 version of TargetOrtho2.
  TargetOrtho2_Python3_github.zip uses the original genomes and annotations from Glenwinkel et al., 2021. This option is explicitly mentioned in the protocol Rumley, Kim, and Hobert 2025.
  TargetOrtho2_WBPS19 uses the WBPS19 versions of the genomes and annotations of the original eight nematode species from Glenwinkel et al., 2021.
  TargetOrtho2_WBPS19_plus_C_trop uses the WBPS19 versions of the genomes and annotations of the original eight nematode species from Glenwinkel et al., 2021, as well as C. tropicalis genome sequence and annotations as published in Toker et al., 2024. https://www.biorxiv.org/content/10.1101/2024.11.23.624988v1

Because GitHub limits file uploads to 25 MB, the components of TargetOrtho2_WBPS19 and TargetOrtho2_WBPS19_plus_C_trop have been uploaded as several .zip files and placed in their respective folders. In order to use these two options for TargetOrtho2, you must decompress the .zip files and organize the resulting folders in the same format as in TargetOrtho2_Python3_github.  For TargetOrtho2_WBPS19_plus_C_trop, you must move Caenorhabditis_tropicalis_NIC203.scaffolds.fa to the genomes folder.  Also, for TargetOrtho2_WBPS19_plus_C_trop, you must use a species list to run targetortho_mod_C_trop.py with all nine genomes. The species list all_species.txt, which lists all nine species, is provided in the folder species_lists.
