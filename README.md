# Summary

UD Javanese-CSUI is a dependency treebank in Javanese, a regional language in Indonesia with more than 68 million users. It was developed by Alfina et al. from the Faculty of Computer Science, Universitas Indonesia. The newest version has 1000 sentences and 14K words with manual annotation.

# Introduction

UD Javanese-CSUI is a dependency treebank in Javanese, a regional language in Indonesia with more than 68 million users. It was developed by Alfina et al. from the Faculty of Computer Science, Universitas Indonesia. The newest version has 1000 sentences and 14K words with manual annotation.

The sentences use the Latin script and do not use the original writing system of Javanese ([Hanacaraka](https://id.wikipedia.org/wiki/Aksara_Jawa)).

The original sentences were taken from several resources: 
1. Javanese reference grammar books (125 sents)
2. [OPUS](https://opus.nlpl.eu/), especially from the Javanese section of the WikiMatrix v1 corpus (150 sents)
2. Online news ([Solopos](https://www.solopos.com/jagad-jawa)) (725 sents)

Javanese has several language levels, such as Ngoko, Krama, Krama Inggil, and Krama Andhap. In this treebank, the sentences predominantly use Ngoko words, some of which use Krama words.

# Split
This dataset has only one split: test. 
Since the dataset is small, we recommend using 10-fold cross validation (use [ud-tool](https://github.com/UniversalDependencies/tools/blob/master/conllu-tenfold.pl) to split the dataset).

If you need three splits, the suggestions to split the 1000 sentences are:
* Test: 1st, 11th, 21st, ..., 991st sentence, total 100 sents.
* Dev: 5th, 15th, 25th, ..., 995th sentence, total 100 sents.
* Train: the rest, total 800 sents. 


# Acknowledgments
* The contributors of the second version (v2.12): Ika Alfina, Arlisa Yuliawati, Dipta Tanaya, Arawinda Dinakaramani, and Daniel Zeman
* The contributors of the first version (v2.9): Ika Alfina, Arlisa Yuliawati, Dipta Tanaya, Arawinda Dinakaramani, Putri Rizqiyah, and Sri Hartati Wijono


## References

@unpublished{Alfina2023, <br>
author = {Alfina, Ika and Yuliawati, Arlisa and Tanaya, Dipta and Dinakaramani, Arawinda and Zeman, Daniel}, <br>
title = {{A Gold Standard Dataset for Javanese Tokenization, POS Tagging, Morphological Feature Tagging, and Dependency Parsing}}, <br>
year = {2023} <br>
}


# Changelog

* 2024-10-25 v2.15
  * fixed errors

* 2023-05-15 v2.12
  * Added 875 sentences (became 1000 sentences).
  * Added nsubj:outer and csubj:outer to the deprel list
  * Added Mood=Irr to the feature-value list

* 2021-11-15 v2.9
  * Initial release in Universal Dependencies with 125 sentences.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.9
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction grammar-examples wiki news fiction
Lemmas: not available
UPOS: automatic with corrections
XPOS: not available
Features: automatic with corrections
Relations: automatic with corrections
Contributors: Alfina, Ika; Yuliawati, Arlisa; Tanaya, Dipta; Dinakaramani, Arawinda; Zeman, Daniel; Rizqiyah, Putri;  Wijono, Sri Hartati;
Contributing: elsewhere
Contact: ika.alfina@cs.ui.ac.id
===============================================================================
</pre>
