# ES-0
This repository includes all the necessary material for replicating the paper "The impact of variance in district magnitude on the effective number of electoral parties", written by Pau Grau for the course Electoral Systems taught by Ignacio Lago at the MA of Research in Political Science at UPF (2019-2020).

## Folders:

1. **"Creating the final dataset"** : provides the new variables with ID variables (alesina.dta, clea1.dta, Legislative_new1.dta) as well as the ".rmd" file (Dataset.rmd) for building through the R statistical software these unified datasets from their original sources. The final dataset is "LegisCLEAN.dta" and was created through STATA with "legislativenewDOFILE.do" script, which is the one provided by Clark & Goler (2006) with the commands for merging the new variables. 

2. **Statistical Analyis** : provides the analyses performed for the paper. It includes a "html" document that can be downloaded and opened with any Internet browser, as well as the "Rmd" file, which can be opened with RStudio (https://rstudio.com/) and from which all the analyses can be replicated.

3. **Merging datasets** : provides a dataset (FINAL_DATA1.CSV) including Bormann & Golder (2013), the fragmentation measure from Alesina et al. (2003) and variance from Kollman et al. (2019). Even though it has been not used in the paper, it might be useful for further studies. 


## References

Alesina, A., Devleeschauwer, A., Kurlat, S., & Wacziarg, R. (2003). Fractionalization. Journal of Economic Growth, 8, 155-194.

Bormann, N. C., & Golder, M. (2013). Democratic Electoral Systems around the world, 1946-2011. Electoral Studies, 32(2), 360-369. https://doi.org/10.1016/j.electstud.2013.01.005

Kollman, K., Hicken, A., Caramani, D., Backer, D., & Lublin, D. (2019). Constituency-level elections archive. Ann Arbor, MI: Center for Political Studies, University of Michigan [producer and distributor].
