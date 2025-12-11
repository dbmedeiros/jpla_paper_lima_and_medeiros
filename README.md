# Partisan and Nonpartisan Models of Constitution-Making: A Comparative Case Study of Brazil and Chile
Welcome to the replication materials for the paper “Partisan and Nonpartisan Models of Constitution-Making: A Comparative Case Study of Brazil and Chile” (https://doi.org/10.1177/1866802X251397954).

This repository contains the R scripts, Stata do-file, and all associated datasets required to reproduce the figures and tables presented in the article.

To replicate Figures 1–7, use the R script [JPLA_script_wnominate_figures_1-7.R](https://github.com/dbmedeiros/jpla_paper_/blob/main/JPLA_script_wnominate_figures1-7.R). To replicate Tables 3 and 4, use [JPLA_script_wnominate_tables_3-4.R](https://github.com/dbmedeiros/jpla_paper_/blob/main/JPLA_script_wnominate_tables_3-4.R). Both scripts require five datasets:

- [Votacionces_CC_.xlsx](https://github.com/dbmedeiros/jpla_paper_/blob/main/Votaciones_CC_.xlsx): roll-call votes (committees and floor) from the Chilean Constitutional Convention (CC);

- [perfiles_id_clean_novo.xlsx](https://github.com/dbmedeiros/jpla_paper_/blob/main/perfiles_id_clean_novo.xlsx): biographical and identification information for CC members;

- [anc.dta](https://github.com/dbmedeiros/jpla_paper_/blob/main/anc.dta): roll-call votes and member information from Brazil’s National Constituent Assembly (ANC);

- [votcom.xlsx](https://github.com/dbmedeiros/jpla_paper_/blob/main/votcom.xlsx): roll-call votes from ANC standing committees;

-[votcsist.xlsx](https://github.com/dbmedeiros/jpla_paper_/blob/main/votcsist.xlsx): roll-call votes from the ANC Systematization Committee.

To replicate Figure 8, use the Stata do-file [JPLA_script_matching_figure8.do](https://github.com/dbmedeiros/jpla_paper_/blob/main/JPLA_script_matching_figure8.do), which requires only the dataset [wnominate_matching.dta](https://github.com/dbmedeiros/jpla_paper_/blob/main/wnominate_chile.dta), containing CC member information and their W-NOMINATE scores.
