# COLF-VID

## COLF-VID

COLF-VID is a **CO**rpus of **L**iteral and **F**igurative readings of German **V**erbal **ID**ioms in context. It comes in 34 files containing annotated instances (along with the sentences they occur in) of 34 different German verbal idiom (VID) types. The annotation consists of four labels coded as integers: `LITERAL` -> `1`, `IDIOMATIC` -> `2`, `UNDECIDABLE` -> `3` and `BOTH` -> `4`. A more detailed description of the corpus can be found in the paper [Supervised Disambiguation of German Verbal Idioms with a BiLSTM
Architecture](https://www.aclweb.org/anthology/2020.figlang-1.29.pdf). At the moment, there exist three different versions of COLF-VID:

- COLF-VID_1.0: The version of the corpus that was used during the experiments described in the paper. It was lemmatized with [GermaLemma](https://github.com/WZBSocialScienceCenter/germalemma) and POS tagged with the [TreeTagger](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/).
- COLF-VID_1.1: The cleaned version of COLF-VID_1.0. COLF-VID_1.0 contained some dublicates that were removed. Does not contain lemmas or POS tags at the moment, but we will add those along with dependency information in the near future with [UDPipe](http://ufal.mff.cuni.cz/udpipe).
- COLF-VID_2.0: Work in progress. We aim to add annotations for VID instances in the corpus that were not part of the pre-chosen set of the 34 VID types and thus were not annotated in the first run.

## LICENSE

Available under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/) (In the paper we erroneously write that we make it available under the Creative Commons Attribution-ShareAlike 4.0 International license).
