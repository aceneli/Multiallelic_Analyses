# Multiallelic Analysis Workflow

## Workflow

1. **Allele frequency calculation:** Allele frequencies (*AF*) were calculated from VCF files using *VCFtools* (`Allele Frequency Computation script`).

2. **Allele frequency aggregation:** Allele frequency columns (`AF1`, `AF2`, `AF3` and `AF4`) from the generated `.frq` files were summed and saved as CSV files (`Allele Frequency Sum-Ups script`).

3. **Multiallelic variant counts:** Different combinations of allele frequencies were aggregated to determine triallelic and tetrallelic variant counts (`Allele Frequency Column Combinations Sum-Ups script`).

4. **Percentage calculations:** Percentages were calculated using spreadsheet software.

5. **Visualisation:** Allele frequency proportions and counts were calculated and visualised using maps and bar plots (`Proportions, Counts Map and Bar Plots Generation script`).

