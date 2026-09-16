# Cached NIST ESTAR reference data

Fetched from the official NIST ESTAR text endpoint on 2026-09-16.
Source: https://physics.nist.gov/PhysRefData/Star/Text/ESTAR.html
Endpoint: https://physics.nist.gov/cgi-bin/Star/e_table-t.pl

These files are reference data for the research demonstrator only. They do not make the app a clinically validated dose engine.

## Cached materials
- `water_liquid`: NIST material 276, 81 rows, 1.000E-02 to 1.000E+03 MeV
- `air_dry`: NIST material 104, 81 rows, 1.000E-02 to 1.000E+03 MeV
- `bone_cortical_icrp`: NIST material 120, 81 rows, 1.000E-02 to 1.000E+03 MeV
- `soft_tissue_icrp`: NIST material 261, 81 rows, 1.000E-02 to 1.000E+03 MeV

CSV columns preserve the units shown by NIST. Raw text responses are retained alongside the parsed CSV files for traceability.
