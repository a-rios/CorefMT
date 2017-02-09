# CorefMT

Annotated News Commentary Corpus (v11)
see: http://opus.lingfil.uu.se/download.php?f=News-Commentary11/News-Commentary11.tar.gz

 - Morphological analysis: FreeLing (http://nlp.lsi.upc.edu/freeling/)
 - Tagging: Wapiti (https://wapiti.limsi.fr/)
 - Parsing: MaltParser (http://www.maltparser.org/)
 - Co-Reference: Corzu: (http://www.cl.uzh.ch/de/research/completed-research/coreferenceresolution.html)

Contents:

 - es-en: pure text, sentence aligend
 - es-en-trees: English text, Spanish dependency trees in Moses XML (binarized)
 - es-en-posscoref: pure text, Spanish with dummies for null subjects and annotated possessive pronoun 'su/sus' and annotated relative pronoun 'que'
 - es-en-posscoref-trees: English text, Spanish dependency trees in Moses XML, with dummies for null subjects and annotated possessive pronoun 'su/sus' and annotated relative pronoun 'que'

nc11.es.coref.conll.tar.bz2
  - annotated Spanish corpus, conll with entities
  
nc11.es.coref.chains.tar.bz2
  - *.mables: extracted markables
  - *.mables.chains: co-reference chains
  - *.ante_scores: scores of possible antecedent for each pronoun

The format of the mentions is as follows:
[MentionID, SentenceID, MentionStartToken, MentionEndToken, PoS, Person, Gender, Number, Gram. Funct., Animate, Dependency Head Token, Gov. Verb, NE class, *, Head lemma]
