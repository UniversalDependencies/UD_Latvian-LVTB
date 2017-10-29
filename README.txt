# Treebank

Latvian UD Treebank is based on Latvian Treebank created at University of Latvia, Institute of Mathematics and Computer Science (http://sintakse.korpuss.lv).

The UD treebank consists of 3,916 sentences (54,819 tokens), and it has been obtained by automatic conversion of both the morphological and the syntactic annotations of the original treebank. The original data contains manually annotated syntax and semi-automatically annotated morphological tags and lemmas.

# Data sets

The training data contains news articles, interviews, annotations, media clippings and press releases. The development and test sets are split out to contain an interview, a news article, a press release, a clipping and few annotations.

Train: 3988 sentences
Dev: 976 sentences
Test: 1175 sentences

# Statictics

Tree count:  6139
Word count:  88040
Token count: 88040
Dep. relations: 122 of which 90 language specific
POS tags: 16
Category=value feature pairs: 56

# Acknowledgments

This work was partially supported by European Regional Development Fund under grant agreement No. 1.1.1.1/16/A/219 (Full Stack of Language Resources for Natural Language Understanding and Generation in Latvian).

# References

Pretkalniņa L., Rituma L., Saulīte B. Universal Dependency Treebank for Latvian: A Pilot. Proceedings of the 7th International Conference on Human Language Technologies — the Baltic Perspective (HLT 2016), Frontiers in Artificial Intelligence and Applications, Vol. 289, IOS Press, 2016, pp. 136–143

Pretkalniņa L., Rituma L. Constructions in Latvian Treebank: the Impact of Annotation Decisions on the Dependency Parsing Performance. Proceedings of the 6th International Conference on Human Language Technologies — the Baltic Perspective (HLT 2014), Frontiers in Artificial Intelligence and Applications, Vol. 268, IOS Press, 2014, pp. 219–226

Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. Towards a Latvian Treebank. Actas del 3 Congreso Internacional de Lingüística de Corpus. Tecnologias de la Información y las Comunicaciones: Presente y Futuro en el Análisis de Corpus, eds. Candel Mora M.Á., Carrió Pastor M., 2011, pp. 119–127


# Changelog

2017-11-15 v2.1
  * Removed duplicated and artificially constructed sentences.
  * Fixed bug resulting Evident=Fh,Nfh where Evident=Fh should be.
  * Added more data.
  * Added enhanced dependencies.

2017-02-15 v2.0
  * Annotation changed according to UDv2 guidelines.
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
Includes text: yes
Genre: news fiction other
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Pretkalniņa, Lauma; Rituma, Laura; Saulīte, Baiba; Nešpore-Bērzkalne, Gunta; Grūzītis, Normunds
Contributing: elsewhere
Contact: lauma@ailab.lv, normunds@ailab.lv
Paragraphs to web:18
===============================================================================
