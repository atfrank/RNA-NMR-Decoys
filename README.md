# RNA-NMR-Decoys
Atomistic decoy sets for RNAs in PDB that were solved using NMR, and for which NMR chemical shift data is available.

Decoy sets consist of:  
- structures in the corresponding NMR bundle
- structures generated using FARFAR
- structures extracted from MD simulations (simulations were initiated from the first model in the corresponding NMR bundle)

Contained in each folder are:
- coordinates/ - coordinate files of decoys in PDB format (compressed with .gzip)
- chemical_shifts.txt - NMR chemical shifts
- struct.txt - structural comparison info for decoys relative to the solve NMR structures

Coordinate files can be decompressed using by executing:
 
``
./decompress-coordinates.sh
``

Find download links and citation info at:

[![DOI](https://zenodo.org/badge/71631383.svg)](https://zenodo.org/badge/latestdoi/71631383)