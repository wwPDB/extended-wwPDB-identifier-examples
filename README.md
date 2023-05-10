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

* Models
   * [7fgz](Models/7fgz-extended_CCD_code-model.cif) with extended CCD code `7ZTVU`replacing `EPE`
   * [pdb_00017fgz](Models/pdb_00017fgz-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code 7ZTVU replacing `EPE`
   * [7xsv](Models/7xsv-extended_CCD_code-model.cif) with extended CCD code `BB87Q`replacing `SEP` in polymer
   * [pdb_00017xsv](Models/pdb_00017xsv-extended_PDB_CCD_codes-model.cif) with extended PDB accession and and CCD code `BB87Q` replacing `SEP` in polymer
   * [8eur](Models/8eur-extended_CCD_code-model.cif) with extended CCD code `WAS` replacing `WAS`
   * [7w41](Models/7fgz-extended_CCD_code-model.cif) with extended CCD code `8B8`replacing `9RQZS`
   * [pdb_00017w41](Models/pdb_0001741-extended_PDB_CCD_codes-model.cif) with extended PDB accession code and CCD code `8B8` replacing `9RQZS`
   * [pdb_00017u1t](Models/pdb_00017u1t-extended_PDB_codes-model.cif) with extended PDB accession code