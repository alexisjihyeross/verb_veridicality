# verb_veridicality
Veridicality Assessment in Verb-Complement Constructions for NLI Systems

The file verb_veridicality_evaluation.tsv contains the dataset introduced in our paper, [How well do NLI models capture verb veridicality?](https://www.aclweb.org/anthology/D19-1228.pdf)

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

# Citation
```
@inproceedings{ross-pavlick-2019-well,
    title = "How well do {NLI} models capture verb veridicality?",
    author = "Ross, Alexis  and
      Pavlick, Ellie",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D19-1228",
    doi = "10.18653/v1/D19-1228",
    pages = "2230--2240",
    abstract = "In natural language inference (NLI), contexts are considered veridical if they allow us to infer that their underlying propositions make true claims about the real world. We investigate whether a state-of-the-art natural language inference model (BERT) learns to make correct inferences about veridicality in verb-complement constructions. We introduce an NLI dataset for veridicality evaluation consisting of 1,500 sentence pairs, covering 137 unique verbs. We find that both human and model inferences generally follow theoretical patterns, but exhibit a systematic bias towards assuming that verbs are veridical{--}a bias which is amplified in BERT. We further show that, encouragingly, BERT{'}s inferences are sensitive not only to the presence of individual verb types, but also to the syntactic role of the verb, the form of the complement clause (to- vs. that-complements), and negation.",
}
```
