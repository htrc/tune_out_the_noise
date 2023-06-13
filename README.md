# TuningOutTheNoise
Code and data for "Tuning out the Noise" paper

## Data
The raw sample sentences we used to benchmark each NER model are in `sample_sentences.tsv`

Our annotated, gold-standard entity dataset is available, by page text, in the folders `ann1` and `ann2` for each round of annotation, respectively. These files feed right into brat (https://brat.nlplab.org/) the annotation software we used for each round.


### Code
Each NER model was implemented individually by different team members. Each implementation is available in a Python notebook, with the name of the NER software in the notebook filename.
