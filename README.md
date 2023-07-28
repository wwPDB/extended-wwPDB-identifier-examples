# extended-wwPDB-identifier-examples
Example data files depicting extended length CCD names and extended PDB identifiers

As previously anounced, in [Future Planning: Entries with extended PDB and CCD ID codes will be distributed in PDBx/mmCIF format only](https://www.wwpdb.org/news/news?year=2021#607760112786e73a79c76f9d), the wwPDB will need to extend the length of the chemical component database (CCD) identifiers (residue codes) and PDB identifiers as the available pool of codes is used up.

Due to legacy PDB file format limitations, CCD id codes have been limited to three alpha-numeric characters, and PDB codes to four.

As early as Fall 2023, the availabile three character CCD identifiers will be consumed and the wwPDB will need to extend the length.

Existing identifiers will not be extended to the exsting PDB entries, but will only be used for newer CCD and PDB codes.

Within this repository are sample CCD and model files displaying extended length identifiers.

Some examples:

* CCD
  * [SEP](CCD/BB87Q.cif) with CCD identifier changed to `BB87Q`
  * [EPE](CCD/7ZTVU.cif) with CCD identifier changed to `7ZTVU`
  * [8B8](CCD/9QRZS.cif) with CCD identifier changed to `9QRZS`
  * [WAS](CCD/9ABCD.cif) with CCD identifier changed to `9ABCD`
  * [BMA](CCD/1XAMB.cif) with CCD identifier changed to `1XAMB`
  * [DVA](CCD/X2AVD.cif) with CCD identifier changed to `X2AVD`

* PRD and PRDCC
  * [PRD_999999](PRD/PRD_999999.cif) with CCD component X2AVD replacing DVA in PRD_000001
  * [PRDCC_999999](PRDCC/PRDCC_999999.cif) with CCD component X2AVD replacing DVA in PRD_000001

* Models
   * [7fgz](Models/7fgz-extended_CCD_code-model.cif) with extended CCD code `7ZTVU`replacing `EPE`
   * [pdb_00017fgz](Models/pdb_00017fgz-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code 7ZTVU replacing `EPE`
   * [7xsv](Models/7xsv-extended_CCD_code-model.cif) with extended CCD code `BB87Q`replacing `SEP` in polymer
   * [pdb_00017xsv](Models/pdb_00017xsv-extended_PDB_CCD_codes-model.cif) with extended PDB accession and and CCD code `BB87Q` replacing `SEP` in polymer
   * [8eur](Models/8eur-extended_CCD_code-model.cif) with extended CCD code `9ABCD` replacing `WAS`
   * [7w41](Models/7w41-extended_CCD_code-model.cif) with extended CCD code `9QRZS`replacing `8B8`
   * [pdb_00017w41](Models/pdb_00017w41-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code `9QRZS` replacing `8B8`
   * [pdb_00017u1t](Models/pdb_00017u1t-extended_PDB_codes-model.cif) with extended PDB accession code
   * [1b5f](Models/1b5f-extended_CCD_code-model.cif) with extended CCD code `1XAMB` replacing `BMA` in branched entities of oligosaccharides
   * [pdb_00011b5f](Models/pdb_00011b5f-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code `1XAMB` replacing `BMA` in branched entities of oligosaccharides
   * [1a7y](Models/1a7y-extended_CCD_code-model.cif) with extended CCD code `X2AVD` replacing `DVA` in the oligopepetide entity PRD_999999
   * [pdb_00011a7y](Models/pdb_00011a7y-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code `X2AVD` replacing `DVA` in the oligopepetide entity PRD_999999
   