# SDplots_VaccineUpdates
We here provide recommendations for vaccine strains to be included in the vaccine against human influenza A viruses in parallel to the recommendations provided by the WHO. 

The utilized method is described in Scientific Reports (https://www.nature.com/articles/s41598-017-18791-z). Al data of the study as well as the software are [available here](https://github.com/hzi-bifo/SDplots). In short, the SD plots method utilizes genetic sequences of the major surface protein of circulating influenza A viruses. From a genealogy calculated for each subtype, the frequencies changes of amino acid changes associated with a particular clade over consecutive seasons are determined and changes increasing significantly in frequency considered as candidate changes providing a selective advantage. If these changes have already reached more than 50% frequency in the current season and are located in regions of the surface proteins known to alter antigenicity, an update of the vaccine strain with a strain from the particular clade is recommended. 
Our results for the vaccine strain prediction are summarized in the table below.

| Current season | Season recommended | Date of recommendation | Current H3N2 vaccine strain | Update recommended | Current pH1N1 vaccine strain | Update recommended | Detailed analysis |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 2017S | 2018S | 19 September 2017 | A/Hong Kong/4801/2014 | No | A/Michigan/45/2015 | (No)\* | [link to results](https://github.com/hzi-bifo/SDplots_VaccineUpdates/tree/master/Recommendation%20in%202017S%20for%202018S) |
| 2018N | 2019N | 22 February 2018 | A/Singapore/INFIMH-16-0019/2016 | Yes | A/Michigan/45/2015 | (No)\* | [link to results](https://github.com/hzi-bifo/SDplots_VaccineUpdates/tree/master/Recommendation%20in%202018N%20for%202019N) |

Information about current vaccine strains are obtained by [the WHO](http://www.who.int/influenza/vaccines/virus/recommendations/en/).
***
\*The antigenicity and avidity changing sites that we use for the evaluation have been experimentally identified for the H3N2 subtype and don't necessarily have the same function in the pH1N1 virus. To our knowledge, there are no comprehensive studies of antigenicity or avidity altering sites in the pH1N1 virus yet, which makes the evaluation of observed sites in the SD plots difficult for this subtype and the recommendation should be taken with caution.
