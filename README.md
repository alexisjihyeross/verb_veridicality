# verb_veridicality
Veridicality Assessment in Verb-Complement Constructions for NLI Systems

The file verb_veridicality_evaluation.tsv contains the dataset introduced in our paper, How well do NLI models capture verb veridicality?

The fields in this file are:
- ``index``: Index
- ``task``: The type of complement (either ``to`` or ``that``)
- ``verb``: The verb
- ``sentence``: The sentence
- ``neg_sentence``: The negated version of the sentence
- ``complement``: The complement
- ``turker_pos_ratings``: The ratings given by the three turkers in the positive environment
- ``turker_neg_ratings``: The ratings given by the three turkers in the negative environment
- ``bert_pos_entailment_prob``: The probability of entailment as output by BERT in the positive environment
- ``bert_pos_contradiction_prob``: The probability of contradiction as output by BERT in the positive environment
- ``bert_pos_neutral_prob``: The probability of neutral as output by BERT in the positive environment
- ``bert_neg_entailment_prob``: The probability of entailment as output by BERT in the negative environment
- ``bert_neg_contradiction_prob``: The probability of contradiction as output by BERT in the negative environment
- ``bert_neg_neutral_prob``: The probability of neutral as output by BERT in the negative environment
- ``signature``: The signature of the verb as determined by a [manually-curated dictionary of implicative and factive verbs](http://web.stanford.edu/group/csli_lnr/Lexical_Resources/) (one of ``+/+``, ``+/-``, ``-/+``, ``o/+``, ``o/-``, ``-/o``, ``+/o``, or ``o/o``)
