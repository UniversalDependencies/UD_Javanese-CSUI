# Summary

UD Javanese-CSUI is a dependency treebank in Javanese, a regional language in Indonesia with more than 68 million users. This treebank was annotated manually. The newest version has 1000 sentences and 14K words.

# Introduction

UD Javanese-CSUI is dependency treebank for Javanese, the regional language that has the most users in Indonesia (more than 68 million native speakers). This treebank was annotated manually. The newest version has 1000 sentences and 14K words.

The original sentences were taken from several resources: 
1. Javanese reference grammar books (125 sents)
2. [OPUS](https://opus.nlpl.eu/), especially from the Javanese section of the WikiMatrix v1 corpus (150 sents)
2. Online news ([Solopos](https://www.solopos.com/jagad-jawa)) (725 sents)


The sentences in this corpus use the Latin script, do not use the original writing system of Javanese ([Hanacaraka](https://id.wikipedia.org/wiki/Aksara_Jawa))

Javanese has several language levels, such as Ngoko, Krama, Krama Inggil, and Krama Andhap. In this Javanese dependency treebank, the sentences predominantly use Ngoko words, with some of them use Krama words.

# Acknowledgments

* UD Javanese-CSUI was developed by the [Information Retrieval and Natural Language Processing (IR-NLP)](https://ir.cs.ui.ac.id) Laboratory of Faculty of Computer Science, Universitas Indonesia. 
* We are greatful to the many people who made this dataset possible: Ika Alfina, Arlisa Yuliawati, Dipta Tanaya, Arawinda Dinakaramani, Putri Rizqiyah, and Sri Hartati Wijono.


## References

@unpublished{Alfina2023,
author = {Alfina, Ika and Yuliawati, Arlisa and Tanaya, Dipta and Dinakaramani, Arawinda and Zeman, Daniel},
keywords = {Natural Language Processing,POS tagging,Universal Dependencies,dependency parsing,low-resource language,tokenization},
title = {{A Gold Standard Dataset for Javanese Tokenization, POS Tagging, Morphological Feature Tagging, and Dependency Parsing}},
year = {2023}
}


# Changelog

* 2023-05-15 v2.12
  * Added 875 sentences (became 1000 sentences).
  * Added nsubj:outer and csubj:outer to deprel list

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
