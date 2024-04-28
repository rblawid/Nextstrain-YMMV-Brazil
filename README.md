Unveiling Global Evolution and Spread of yam mild mosaic virus through Genomic Analysis

Two methods, NextStrain and BEAST, were employed for phylogeographical analysis. For the BEAST analysis, first we conducted an evaluation of temporal molecular evolutionary signals by performing root-to-tip linear regression analyses between genetic divergence and sampling date using TempEst v.1.5.3. Subsequently, we assessed phylogenetic signals in the aligned sequences by testing nucleotide saturation substitutions using DAMBE v.6. Temporal calibration was performed based on the sampling data. Additionally, tests of data randomization were conducted for accurate estimations of the substitution rate. The nucleotide substitution GTR model with estimated base frequencies and Gamma rate heterogeneity with invariant sites was employed. Initially, the strict model was tested, but it did not yield adequate sampling of posterior results. Consequently, the uncorrelated relaxed clock with a lognormal relaxed distribution (UCLN) and with exponential distribution (UCEXP) were tested, along with four demographic models to explore population size changes over time: exponential growth, expansion growth, Bayesian Skyline, and Constant Size, with growth rate parameterization (EXP). Two discrete traits, Host and Country, were studied under the symmetric substitution model. The best-fit model was selected through marginal likelihood comparisons using path sampling (PS) and stepping-stone sampling (SS) estimates. 

To perform the NextStrain analysis, the metadata from our dataset were organized in a TSV file, which included information such as strain, collection date, country of origin, geographic region, and hosts. Posteriorly, the dataset was indexed, and aligned using MAFFT v7. Using Augur tools within Nextstrain, we inferred a phylogenetic tree using IQTREE, generated a time-resolved tree using TreeTime, and identified amino acid mutations and ancestral traits such as country and host.
