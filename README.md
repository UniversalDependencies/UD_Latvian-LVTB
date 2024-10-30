# Summary

Latvian UD Treebank is based on Latvian Treebank ([LVTB](http://sintakse.korpuss.lv)), being created at University of Latvia, Institute of Mathematics and Computer Science, [Artificial Intelligence Laboratory](http://ailab.lv).

# Introduction

Latvian UD Treebank v2.15 consists of 19'367 sentences (327'464 tokens), and it has been obtained by automatic conversion of both the morphological and the syntactic annotations of the original LVTB treebank. LVTB data contains manually verified syntactic annotation according to a hybrid dependency-constituency schema, as well as manually verified morphological tags and lemmas. LVTB is released in parallel with Latvian UD Treebank since v2.2 and features the same version numbers. The corresponding LVTB versions are listed [here](http://sintakse.korpuss.lv/versions.html). Key `LvtbNodeId` in Latvian UD Treebank CoNLL-U field `MISC` provides the mapping from Latvian UD Treebank to LVTB. Each LVTB version is superset of the corresponding Latvian UD Treebank version in terms of included sentences.

# Acknowledgments

This work was supported by European Regional Development Fund under the grant agreement No. 1.1.1.1/16/A/219 ([Full Stack of Language Resources for Natural Language Understanding and Generation in Latvian](https://github.com/LUMII-AILab/FullStack)) in synergy with the grant agreement No. 1.1.1.2/VIAA/1/16/188. The pilot project was supported by State Research Programme "National Identity". The work was continued within the State Research Programme "[Digital Resources for the Humanities](http://www.digitalhumanities.lv/projects/DHVPP-en/)" under the grant agreement No. VPP-IZM-DH-2020/1-0001, and now is continued in State Research Programme "[Research on Modern Latvian Language and Development of Language Technology](http://www.digitalhumanities.lv/projects/vpp-late/)" under the grant agreement No. VPP-LETONIKA-2021/1-0006.

# References

* Pretkalniņa L., Rituma L., Saulīte B. Deriving enhanced Universal Dependencies from a hybrid dependency-constituency treebank. Proceedings of the 21sh International Conference Text, Speech, and Dialogue, LNCS, Vol. 11107, Springer Link, 2018, pp. 95-105

* Grūzītis N., Pretkalniņa L., Saulīte B., Rituma L., Nešpore-Bērzkalne G., Znotiņš A., Paikens P. Creation of a Balanced State-of-the-Art Multilayer Corpus for NLU. Proceedings of the 11th International Conference on Language Resources and Evaluation (LREC). Miyazaki, Japan, 2018, pp. 4506-4513

* Pretkalniņa L., Rituma L., Saulīte B. Universal Dependency Treebank for Latvian: A Pilot. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 289, IOS Press, 2016, pp. 136-143

* Pretkalniņa L., Rituma L. Constructions in Latvian Treebank: The Impact of Annotation Decisions on the Dependency Parsing Performance. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 268, IOS Press, 2014, pp. 219-226

* Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. Towards a Latvian Treebank. Actas del III Congreso Internacional de Lingüística de Corpus. Valencia, Spain, 2011, pp. 119-127

* Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. A Prague Markup Language profile for the SemTi-Kamols grammar model. Proceedings of the 18th Nordic Conference of Computational Linguistics. Riga, Latvia, 2011, pp. 303-306

# Licensing

This data set is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

By using this data set, you agree to comply with the European Intellectual Property Rights and the European General Data Protection Regulation.

Please, [let us know](mailto:normunds.gruzitis@ailab.lv) if you use this data set for product or service development.

# Data splits

The training data covers various text types: news, fiction, academic texts, legal texts, transcripts of spoken language, etc. The development and test sets are carefully split out to cover all those types.

Train: 14887 sentences\
Dev:    2080 sentences\
Test:   2400 sentences

# Changelog

2024-11-15 v2.15
  * New data.
  * Introduced `advmod:neg` for negation particles and `advmod:emph` for various other particles.
  * DET/PRON distinction is now done by lexeme, not by syntax tree.
  * Personal pronouns depending on nouns are now `nmod`.
  * Most of comparison constructions considered secondary predicative components in Latvian are now `advcl` or `acl` in UD.
  * Fixes regarding several `flat` and `fixed` constructions, as well as prepositional and pronominal nmods.

2024-05-15 v2.14
  * New data.
  * Various minor fixes.

2023-11-15 v2.13
  * New data.
  * Various minor fixes.

2023-05-15 v2.12
  * New data.
  * Minor fixes in tags.

2022-11-15 v2.11
  * Various fixes.

2022-05-15 v2.10
  * New data.
  * Various minor fixes.

2021-11-15 v2.9
  * New data.
  * Some minor fixes.

2021-05-15 v2.8
  * New data.
  * "kļūt" is not AUX anymore.
  
2020-05-15 v2.6
  * Some singular errors fixed.

2019-11-15 v2.5
  * Added more data, improved consistency.
  * Major revision in what Latvian model considers secondary predicative components ('obl', 'appos', 'xcomp' etc. in UD terms).
  * The reflexive pronoun 'sevis' is not a reciprox.
  * Some objects are actually 'obl'.
  * Adjective definetness fixed.
  * Multiple singular errors fixed.

2019-05-15 v2.4
  * Added more data.
  * Participle voice fixed.
  * Issues #5, #6, #7, #8 fixed in the original data.
  * Fixed annotation errors according to the more strict validator.

2018-11-15 v2.3
  * Added more data.
  * Negative verbs and participles now have lemmas without the prefix 'ne'.
  * Both masculine and feminine adjectives have the same lemma (masculine).
  * Fixed varios annotation errors.

2018-04-15 v2.2
  * Repository renamed from UD_Latvian to UD_Latvian-LVTB.
  * Fixed tokenization for text errors.
  * Added notifications in the MISC field for corrected text errors.
  * Improved enhanced dependencies.
  * Added more data.

2017-11-15 v2.1
  * Removed duplicated and artificially constructed sentences.
  * Fixed a bug producing Evident=Fh,Nfh where Evident=Fh should be.
  * Added significantly more data.
  * Added enhanced dependencies.

2017-02-15 v2.0
  * Annotation changed according to UD v2 guidelines.
  * Lots of new data.
  * Some annotation errors corrected.

2016-11-15 v1.4
  * Corrected a number of syntactic annotation mistakes.
  * Multi-word conjunctions: first part is now tagged PART.
  * Added new sentences.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v1.3
License: CC BY-SA 4.0
Includes text: yes
Genre: news fiction legal spoken academic
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Pretkalniņa, Lauma; Rituma, Laura; Nešpore-Bērzkalne, Gunta; Saulīte, Baiba; Znotiņš, Artūrs; Grūzītis, Normunds
Contributing: elsewhere
Contact: lauma@ailab.lv, normunds@ailab.lv
===============================================================================
</pre>
