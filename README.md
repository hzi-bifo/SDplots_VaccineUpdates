# Live vaccine strain recommendations for the human influenza vaccine
Recommendations for vaccine strain updates and the influenza A H3N2 and pH1N1 strains to be used for the human influenza vaccine, according to the method described in [Klingen, Reimering et al.](https://www.nature.com/articles/s41598-017-18791-z), which performed favorable in comparison to the recommendations of the WHO in retrospective testing experiments. All data of the study as well as the software are [available here](https://github.com/hzi-bifo/SDplots).

We provide the recommendations with our method in parallel to the WHO, using a computational approach.  In short, the SD plots method utilizes all available genetic sequences of the major surface protein of circulating influenza A viruses. From available sequences from the EpiFlu database, a genealogy is calculated for each subtype, and the changes in frequencies of amino acid changes associated with a particular clade are determined.  Changes increasing significantly in frequency among the sequenced isolates over consecutive seaons are considered as candidate changes providing a selective advantage. If these changes have reached a frequency of more than 50% in the current season and are located in antigenicity-altering regions of the surface protein,  an update of the vaccine strain with a strain from the particular clade is recommended. There is no consideration of antigenic or neutralization data from the current season, as this is not made (publicly) available by the WHO. Note that analysis of clade-associated amino acid change dynamics is different from counting frequencies of amino acid changes from the raw data. The latter approach cannot distinguish between homoeoplasies, i.e. amino acid changes introduced multiple times in parallel in the evolutionary history, and thus of the genetic context of changes, or consider changes that have later been reverted again.

##  Current and prior forecasts by the WHO

| Current season | Season recommended | Date of recommendation | Recommended H3N2 vaccine strain | Recommended pH1N1 vaccine strain |
|:-----:|:-----:|:-----:|:-----:|:-----:|
| 2017N | 2018N | 02 March 2017 | A/Hong Kong/4801/2014 | A/Michigan/45/2015 | 
| 2017S | 2018S | 19 September 2017 | A/Singapore/INFIMH-16-0019/2016 | A/Michigan/45/2015 |
| 2018N | 2019N | 22 February 2018 | A/Singapore/INFIMH-16-0019/2016 | A/Michigan/45/2015 | 

Information about current vaccine strains is obtained from the [WHO](http://www.who.int/influenza/vaccines/virus/recommendations/en/).
***
\*The antigenicity and avidity changing sites that we use for the evaluation have been experimentally identified for the H3N2 subtype and don't necessarily have the same function in the pH1N1 virus. To our knowledge, there are no comprehensive studies of antigenicity or avidity altering sites in the pH1N1 virus yet, which makes the evaluation of observed sites in the SD plots difficult for this subtype and the recommendation should be taken with caution.

## Performance overview of SD-plot vaccine strain prediction

Include image here with legend references the paper. * Until 2016S, performance was evaluated in retrospective testing, where data from after the time of the whO vaccine strain meeting for a particular season was excluded from the analysis. 


## Related literature

[1: Klingen TR, Reimering S, Loers J, Mooren K, Klawonn F, Krey T, Gabriel G,
McHardy AC. Sweep Dynamics (SD) plots: Computational identification of selective
sweeps to monitor the adaptation of influenza A viruses. Sci Rep. 2018 Jan
10;8(1):373. doi: 10.1038/s41598-017-18791-z.](https://www.ncbi.nlm.nih.gov/pubmed/29321538)


[2: Klingen TR, Reimering S, Guzmán CA, McHardy AC. In Silico Vaccine Strain
Prediction for Human Influenza Viruses. Trends Microbiol. 2018 Feb;26(2):119-131.
doi: 10.1016/j.tim.2017.09.001.](https://www.ncbi.nlm.nih.gov/pubmed/29032900)


[3: Kratsch C, Klingen TR, Mümken L, Steinbrück L, McHardy AC. Determination of
antigenicity-altering patches on the major surface protein of human influenza
A/H3N2 viruses. Virus Evol. 2016 Feb 14;2(1):vev025. eCollection 2016](https://www.ncbi.nlm.nih.gov/pubmed/27774294) 
