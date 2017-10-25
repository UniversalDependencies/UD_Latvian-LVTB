# Treebank

Latvian UD Treebank is based on Latvian Treebank being created at University of Latvia, Institute of Mathematics and Computer Science, Artificial Intelligence Laboratory.

The UD Latvian treebank v2.1 consists of 3,916 sentences (54,819 tokens), and it has been obtained by automatic conversion of both the morphological and the syntactic annotations of the original treebank. The original data contains manually verified syntactic annotation according to a hybrid dependency-constituency schema, as well as manually verified morphological tags and lemmas.

# Data sets

The training data contains news articles, interviews, annotations, media clippings and press releases. The development and test sets are split out to contain an interview, a news article, a press release, a clipping and few annotations.

Train: 2313 sentences
Dev: 741 sentences
Test: 918 sentences

# Statictics

Tree count:  3916
Word count:  54819
Token count: 54819
Dep. relations: 36 of which 4 language specific
POS tags: 16
Category=value feature pairs: 56

# Licensing

The data set is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. Please contact us if you are interested in acquiring a commercial licence.

# Acknowledgments

This work was partially supported by European Regional Development Fund under the grant agreement No. 1.1.1.1/16/A/219 (Full Stack of Language Resources for Natural Language Understanding and Generation in Latvian).

# References

Pretkalniņa L., Rituma L., Saulīte B. Universal Dependency Treebank for Latvian: A Pilot. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 289, IOS Press, 2016, pp. 136-143

Pretkalniņa L., Rituma L. Constructions in Latvian Treebank: the Impact of Annotation Decisions on the Dependency Parsing Performance. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 268, IOS Press, 2014, pp. 219-226

Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. Towards a Latvian Treebank. Actas del III Congreso Internacional de Lingüística de Corpus. Valencia, Spain, 2011, pp. 119-127

Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. A Prague Markup Language profile for the SemTi-Kamols grammar model. Proceedings of the 18th Nordic Conference of Computational Linguistics. Riga, Latvia, 2011, pp. 303-306

# Changelog

2017-11-15 v2.1
  * Removed duplicated and artificially constructed sentences.
  * Fixed a bug producing Evident=Fh,Nfh where Evident=Fh should be.
  * Added enhanced dependencies.

2017-02-15 v2.0
  * Annotation changed according to UD v2 guidelines.
  * Lots of new data.
  * Some annotation errors corrected.

2016-11-15 v1.4
  * Corrected a number of syntactic annotation mistakes.
  * Multi-word conjunctions: first part is now tagged PART.
  * Added new sentences.

=== Machine-readable metadata =================================================
Documentation status: stub
Data source: automatic
Data available since: UD v1.3
License: CC BY-NC-SA 4.0
Genre: news fiction legal spoken science other
Contributors: Pretkalniņa, Lauma; Saulīte, Baiba; Rituma, Laura; Nešpore-Bērzkalne, Gunta; Grūzītis, Normunds
Contact: lauma@ailab.lv, normunds@ailab.lv
===============================================================================
