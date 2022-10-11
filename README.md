# interestingnessmeasureforkbs

There are number of studies which focus on mining logical rules from knowledge bases (KBs), however they do not consider relations that can have several objects. These are called quasi-functions which can dramatically alter the interestingness of the rule. To the best of our knowledge, there are no studies that propose a measure to evaluate the strength of a logical rule in KBs by considering the impact of quasi-functions. We propose a new interestingness measure to assess the degree of certainty of logical rules by considering  functions and quasi-functions. The main objective of the proposed measure is to evaluate the strength of a rule more appropriately by grouping the subjects in quasi-functions.

We compare the proposed measure with a widely used measure on a synthetic test data and on real KBs ([Dbpedia](https://dbpedia.org/sparql/Dbpedia) and [Wikidata](https://query.wikidata.org/)). We show that the proposed measure is more effective in showing the rule quality, and therefore, it is an appropriate interestingness measure for logical rule evaluation.

This repository contains the Java code and the sample synthetic datasets to evaluate the proposed interestingness measure as submitted to PeerJ Computer Science journal with the name "An Interestingness Measure for Knowledge Bases".
