# Data
This directory contains data associated with this project.

The files contain the following:

* `novel_stimuli_plus_prasada_data.csv`: full list of stimuli used in our rating study, consisting of A) original Prasada 
stimuli, and B) novel stimuli to balance out the stimulus categories in Prasada stimuli and present participants a balanced design; included with 
the Prasada stimuli are the participant ratings reported in the original papers (for comparison with novel ratings).
* `novel_data.csv`: ratings collected for the stimuli in the above file.
* `raw_ratings/`: directory containing unprocessed rating/

## Codebook

### `novel_stimuli_plus_prasada_data.csv`
* `type`: principled versus statistical generic, as categorized in Prasada 2006/2013
* `item`: the stimulus sentence
* `subject`: the concept that the generic describes
* `is_are`: column denoting whether, when creating queries from items, we should use "is it" or "are they" for grammatical/conceptual correctness
* `property`: the property that the generic describes
* `origin`: where the _item_ originates, either Prasada 2006/2013 or novel (created for this study)
* `Truth.judgment`; `Cue.validity.estimate`; `Prevalence.estimate`: ratings from Prasada 2006
* `in.general`; `by.virtue.of`; `causal.essence`; `statistical`; `formal`; `should`: ratings from Prasada 2013

### `novel_stimuli_plus_prasada_data.csv`
* `pp`: participant
* `type`: principled versus statistical generic, as categorized in Prasada 2006/2013
* `item`: the stimulus sentence
* `subject`: the concept that the generic describes
* `property`: the property that the generic describes
* `source`: where the _data_ originates, all novel (collected for this study)
* `by_virtue_of`; `cue_validity`; `generic`; `prevalence`: the four types of rating collected in this rating study, see trial generation notebook for code that generated the four types of queries
