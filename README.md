# New_Latin_Vallex

The New Latin Vallex (LV) works in connection with the Latin WordNet (LWN). Each Synset in LWN is paired with a LV Valency Frame.

The New_Latin_Vallex is a revision of the project Latin-VALLEX with DOI: 10.5281/zenodo.2549277, but it adopts a different approach: LV is intuition based, which means that for each sense listed for a lemma or hypolemma, there is a valency frame, established on the basis of the dictionary meaning listed for that lemma, and not on the wordform in context (although naturally dictionary meanings are drawn from textual evidence).

## File structure

- `ID`: [LiLa](https://lila-erc.eu) lemma ID
- `label`: written representation of the lemma
- `type` : LEMMA/HYPOLEMMA
- `uri`: LiLa lemma URI
- `id_synset` : mapped on Princeton WordNet 3.0 synset ids
- `arguments_set` : set of valency arguments for that specific synset (meaning)
- `status`: 
  - `reviewed`: **ALL** synsets are matched by a valency frame
  - `incomplete`: **SOME** senses covered by Princeton WordNet 3.0, the entry needs completing.


## Credits

- **Creator**: Eleonora Litta
- **Contributors**: Paolo Ruffolo, Marco Passarotti

The _LiLa: Linking Latin_ project has received funding from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme – Grant Agreement No. 769994.

## Citation
[![DOI](https://zenodo.org/badge/294657059.svg)](https://zenodo.org/badge/latestdoi/294657059)
