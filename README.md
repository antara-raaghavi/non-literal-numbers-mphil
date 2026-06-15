# Non-literal interpretation of number words in different languages by language models

This repository contains code and data for the MPhil dissertation  "Non-literal interpretation of number words in different languages by language models" submitted to the University of Cambridge by Antara Bhattacharya on 17 June 2026. 

## File structure and organization

We store the code and data in a `.7z` folder, which is password-protected with the password `nonliteral` to impede web-scraping and prevent contamination of the benchmark in LLM training data. You may need to install the 7-Zip file manager to access this data.

Extracting the files in `non-literal-numbers-multiling`, you will find the following subfolders:

1. `corpus_comparisons` contains code and data for Experiment 1, in which we conduct a corpus analysis using the Europarl corpus. The evaluations and statistics are found in `corpus_evals.ipynb`.

2. `europarl_corpus` contains all our parsed and filtered files from the Europarl corpus. 

3. `survey_comparisons_models` contains the scripts used to query all models for Experiments 2 and 3.

4. `survey_evals` contains the results from the human ground-truth surveys and the model responses which we evaluate in Experiments 2 and 3. Evaluations and statistics are found in `survey_evals.ipynb`. Anonymized survey responses for English and Danish are available at the files `en_anonymized_responses.csv` and `da_anonymized_responses.csv` respectively.

5. `surprisal` contains code and data for Experiment 4, in which we manually annotate the benchmark sentences and calculate surprisal measurements under the mGPT multilingual model. The main code used is in `surprisal_measure.ipynb`.

Please contact arb247@cam.ac.uk if you have any issues with access to the code and data.
