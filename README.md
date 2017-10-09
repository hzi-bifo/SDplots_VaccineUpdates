# SDplots_VaccineUpdates
This repository contains the SD plot results for the current influenza season to make a vaccine recommendation.

The SD plots method was published as a preprint (http://www.biorxiv.org/content/early/2017/02/21/110528) and all data of the study as well as the software are [available here](https://github.com/hzi-bifo/SDplots). For details of the method, please refer to the manuscript. In short, the SD plots method works by calculating frequencies per season for each substitution that is found in a phylogenetic tree. We test for a significant increase in frequency from one season to the next. If a substitution is significant in one season and reaches more than 50% frequency, we mark this as a selective sweep - the season in which the substitution was identified is then marked with an asterisk and the name of the substitution is written to the top.

Our results for the vaccine strain prediction are summarized in the table below.

| Current season | Season recommended | Current H3N2 vaccine strain | Update recommended | Current pH1N1 vaccine strain | Update recommended | Detailed analysis |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 2017S | 2018S | A/Hong Kong/4801/2014 | No | A/Michigan/45/2015 | (No)\* | [link to results](https://github.com/hzi-bifo/SDplots_VaccineUpdates/tree/master/Recommendation%20in%202017S%20for%202018S) |

Information about current vaccine strains are obtained by [the WHO](http://www.who.int/influenza/vaccines/virus/recommendations/en/).
***
\*The antigenicity and avidity changing sites that we use for the evaluation have been experimentally identified for the H3N2 subtype and don't necessarily have the same function in the pH1N1 virus. To our knowledge, there are no comprehensive studies of antigenicity or avidity altering sites in the pH1N1 virus yet, which makes the evaluation of observed sites in the SD plots difficult for this subtype and the recommendation should be taken with caution.
