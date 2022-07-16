# IndoNLU Split

## Summary
This folder contains IndoNLU split of the Idn-tagged-corpus-CSUI corpus (abbreviated as BaPOS in the IndoNLU paper).
The corpus consists of 10000 sentences labelled with 23 POS tag classes as defined in **"Designing an Indonesian part of speech tagset and manually tagged Indonesian corpus" (Dinakaramani et al., 2014)**, i.e.:

| POS Tag | Description |
|:-:|---|
| CC | Coordinating conjunction |
| CD | Cardinal number |
| OD | Ordinal number |
| DT | Determiner / article |
| FW | Foreign word |
| IN | Preposition |
| JJ | Adjective |
| MD | Modal |
| NEG | Negation |
| NN | Noun |
| NNP | Proper noun |
| NND | Classifier |
| PR | Demonstrative pronoun |
| PRP | Personal pronoun |
| RB | Adverb sangat |
| RP | Particle pun |
| SC | Subordinating conjunction |
| SYM | Symbol |
| UH | Interjection |
| VB | Verb |
| WH | Question |
| X | Unknown |
| Z | Punctuation |

## The split 
In `IndoNLU`, the `Idn-tagged-corpus-CSUI` dataset is splitted into 3 setsU, i.e., 
- 8,000 train sentences
- 1,000 validation sentences
- 1,029 test sentences

## References

### Idn-tagged-corpus-CSUI
If you use this dataset, please cite the original `Idn-tagged-corpus-CSUI` corpus:
```
@inproceedings{dinakaramani2014idncorpus,
  author={Dinakaramani, Arawinda and Rashel, Fam and Luthfi, Andry and Manurung, Ruli},
  booktitle={2014 International Conference on Asian Language Processing (IALP)}, 
  title={Designing an Indonesian part of speech tagset and manually tagged Indonesian corpus}, 
  year={2014},
  pages={66-69},
  doi={10.1109/IALP.2014.6973519}
}
```

### IndoNLU
If you use the split provided on this folder, please also cite the IndoNLU paper:
```
@inproceedings{wilie-etal-2020-indonlu,
    title = "{I}ndo{NLU}: Benchmark and Resources for Evaluating {I}ndonesian Natural Language Understanding",
    author = "Wilie, Bryan  and
      Vincentio, Karissa  and
      Winata, Genta Indra  and
      Cahyawijaya, Samuel  and
      Li, Xiaohong  and
      Lim, Zhi Yuan  and
      Soleman, Sidik  and
      Mahendra, Rahmad  and
      Fung, Pascale  and
      Bahar, Syafri  and
      Purwarianti, Ayu",
    booktitle = "Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 10th International Joint Conference on Natural Language Processing",
    month = dec,
    year = "2020",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.aacl-main.85",
    pages = "843--857"
}
```

## Contact
- Bryan Wilie <bwilie@connect.ust.hk>
- Karissa Vincentio <karissavin@gmail.com>
- Genta Indra Winata <gentaindrawinata@gmail.com>
- Samuel Cahyawijaya <scahyawijaya@connect.ust.hk>
