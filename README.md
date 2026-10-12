# Oxford MBiol Computer Skills — Bayesian phylogenetics and epidemiology

Data files for the *Bayesian phylogenetica and epidemiology* **Computer Skills** module on the **MBiol** programme, Department of Biology, University of Oxford. The practical uses **Chikungunya virus (CHIKV)** data from the Indian Ocean region and a Kassala / eastern Sudan outbreak case study to introduce Bayesian phylogenetics, BEAST MCMC output, maximum clade credibility (MCC) trees, discrete trait annotations, and phylodynamic summaries in **R** / **R Markdown**.

## Contacts

- **Convenor:** Bernardo Gutierrez — [bernardo.gutierrez@biology.ox.ac.uk](mailto:bernardo.gutierrez@biology.ox.ac.uk)
- **Demonstrator:** Ellie Bourgikos — [elizabeth.bourgikos@lincoln.ox.ac.uk](mailto:elizabeth.bourgikos@lincoln.ox.ac.uk)

Additional module materials may also be available on the University of Oxford **Canvas** site for the module (SSO login required).

## Repository contents

| Item | Description |
|------|-------------|
| `MCC_trees/` | MCC trees for the 2018 outbreak and 2019 hypothetical outbreak |
| `MCMC_log_files/` | BEAST MCMC logs exported to CSV for use in R |

### Data files used in the practical and assessment

- `MCC_trees/MCC_CHIKV_IndianOcean.tree`
- `MCC_trees/MCC_CHIKV_IndianOcean_2019hypotheticaloutbreak.tree`
- `MCMC_log_files/CHIKV_IndianOcean_BEAST_output_log.csv`
- `MCMC_log_files/CHIKV_IndianOcean_updated_BEAST_output_log.csv`

## How to clone this repository locally

Using HTTPS:

```bash
git clone https://github.com/BernardoGG/Oxford_MBiol_Computer_Skills-Bayesian_phylogenetics.git
cd Oxford_MBiol_Computer_Skills-Bayesian_phylogenetics
```

Using SSH:

```bash
git clone git@github.com:BernardoGG/Oxford_MBiol_Computer_Skills-Bayesian_phylogenetics.git
cd Oxford_MBiol_Computer_Skills-Bayesian_phylogenetics
```

Then open the main practical `.Rmd` in **RStudio** and set the working directory to the repository root so relative paths to `MCC_trees/` and `MCMC_log_files/` resolve correctly. The practical setup chunk installs required R packages (including Bioconductor packages `ggtree` and `treeio`).

## Licence and use

These materials are provided for teaching and learning in the Oxford MBiol Computer Skills course. If you wish to reuse or adapt them, please Bernardo Gutierrez ([bernardo.gutierrez@biology.ox.ac.uk](mailto:bernardo.gutierrez@biology.ox.ac.uk)).
