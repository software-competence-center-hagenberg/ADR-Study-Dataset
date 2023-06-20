# ADR Study Dataset

This repository contains the crawled metadata of 921 public GitHub repositories which was used in the paper "Using Architecture Decision Records in Open Source Projects – An MSR Study on GitHub".

The repositories were mined as part of the study and contained ADR (Architecture Decision Records) were analyzed. The results of the analysis can be found in a JSON file for each repository in the [repositories](./repositories/) folder. The actual ADRs are not included in this repository. The further use and exploitation of the content of the ADRs must be carried out under the respective license specified (see LICENSE file or similary in the particular repository).

## Using Architecture Decision Records in Open Source Projects – An MSR Study on GitHub

https://ieeexplore.ieee.org/document/10155430

DOI: 10.1109/ACCESS.2023.3287654

Georg Buchgeher, Stefan Schöberl, Verena Geist, Bernhard Dorninger, Philipp Haindl, and Rainer Weinreich: "Using Architecture Decision Records in Open Source Projects – An MSR Study on GitHub", IEEE Access, 2023.

Architecture decision records (ADRs) have been proposed as a resource-efficient means for capturing architectural design decisions (ADDs), and have received attention not only from researchers but also from practitioners. We conducted a mining software repositories (MSR) study, in which we analyzed the use of ADRs in open source repositories at GitHub. Our results show that the adoption of ADRs is still low, although the number of repositories using ADRs is increasing every year. About 50\% of all repositories with ADRs contain just one to five ADRs suggesting that the concept has been tried but not yet definitively adopted. In repositories that use ADRs more systematically, we observed that recording decisions is a team activity conducted by two or more users over a longer period of time. In most repositories the template proposed by Michael Nygrad is used. We, finally, provide an interpretation of the obtained results and discuss open future research challenges by elaborating on implications of the study’s findings as well as on recommendations on how to further increase the adoption of ADRs.
