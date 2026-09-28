# Mn migration at CoCrFeMnNi solidification interfaces

Data and code accompanying **Mn migration and liquid-side enrichment at CoCrFeMnNi solidification interfaces**, submitted to *Computational Materials Science*.

## Download and reproduce

Download [Data_and_Code.zip](Data_and_Code.zip) for the complete 5.04 MB supplementary package containing 100 scientific files. The ZIP checksum is provided in [SHA256SUMS.txt](SHA256SUMS.txt). The archive is identical to the supplementary data and code supplied with the manuscript.

After extracting the archive, follow `Data_and_Code/README.md`. It lists the software requirements, calculation sequence and correspondence to the manuscript figures and tables.

| Component | Files supplied |
|---|---|
| EPMA | Raw maps and acquisition metadata for six fields, field numbering and processing and plotting scripts |
| MD simulation | Alloy construction program, LAMMPS preparation and solidification inputs, random seeds and parameter sets for three independent replicas |
| Interatomic potential | The MEAM parameter files used in the simulations and their source references |
| MD analysis | Programs for interface migration, local composition, regional chemical order and individual Mn paths |

Full MD trajectories, restart files and job logs are not distributed. The supplied inputs generate the trajectories needed by the analysis programs. Individual atomic paths may vary with the LAMMPS build, parallel decomposition and floating-point arithmetic; the three replicas are the statistical units.

## Potential provenance

The third-party parameter files and their SHA-256 values are documented in `Data_and_Code/MD/potentials/README.md` in the archive. The [NIST Interatomic Potentials Repository entry](https://www.ctcms.nist.gov/potentials/entry/2018--Choi-W-M-Jo-Y-H-Sohn-S-S-et-al--Co-Ni-Cr-Fe-Mn/) provides the corresponding potential and original literature. No additional license is granted for the third-party files.
