# Myelofibrosis Docking Project: TGF-β Receptor Targeting

This project explores drug discovery pathways for myelofibrosis, with a focus on inhibiting TGF-β Receptor Type I (TGFBR1) to reduce bone marrow fibrosis. The workflow uses AutoDock Vina and Open Babel to prepare and dock small molecules to the crystal structure of TGFBR1 (PDB ID: `6B8Y`).

The goal of this project is to identify potential inhibitors of the TGF-β receptor involved in fibrotic signaling, using in silico docking as a citizen-science approach toward myelofibrosis treatment discovery.

## Tools Used
- [AutoDock Vina](http://vina.scripps.edu/)
- [Open Babel](https://openbabel.org/wiki/Main_Page)

1. **Download PDB**: Retrieved `6B8Y.pdb` from RCSB
2. **Clean**: Removed bound inhibitor (`D0A`) and waters
3. **Hydrogen & Charge Prep**: Added polar hydrogens and Gasteiger charges
4. **Convert to PDBQT**: Used Open Babel to create docking-ready `pdbqt` file
5. **Dock Ligands** *(next step)*: Ligand preparation and docking via AutoDock Vina

> Hata, A., et al. (2018). Structure of TGF-β receptor I in complex with small-molecule inhibitor. *PDB ID: 6B8Y*, RCSB Protein Data Bank.

![spinningprotNEWmain](https://github.com/user-attachments/assets/82777127-6aa2-4743-b835-9924bf59bf3a)
