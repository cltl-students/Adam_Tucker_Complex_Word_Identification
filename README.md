# An investigation of complex word identification (CWI) systems for English.
Vrije Universiteit Amsterdam Computational Lexicology and Terminology Lab Department of Language and Communication Faculty of Humanities

To run the feature extraction notebooks in the CAMB, CAMB_A and Final_system folders, you will need to download Stanford CoreNLP [here](https://stanfordnlp.github.io/CoreNLP/) and then navigate to the stanford-corenlp-4.5.4 folder and start core with “% java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -port 9000 -timeout 15000

# Data
The dataset used to train these models was collected by Yimam et al. (2018) and is available [here](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/complex-word-identification-dataset.html).

# Thesis Report
This repository consists of a series of notebooks investigating feature-based aproaches for complex word identification in English. 


Available here (https://www.overleaf.com/read/wmvwtmpbkvqs)

# Project Structure

```
CWI_Masters
└───Baseline_model
        │   feature_extraction.ipynb
        │   lm
        │   lmodel
        │   prob_run.ipynb
        │   prob_train.ipynb
        │   run_model.ipynb
        │   train_model.ipynb
└───CAMB
        │   binary-features
        │   lmodel
        │   Algorithm Application.ipynb
        │   MWE_feats.ipynb
        │   Populating Word Features-MWE.ipynb
        │   Populatinng Word Features.ipynb
        │   prob_run.ipynb
        │   prob_train_CAMB.ipynb

└───CAMB_A
        │   Corpus
        |   Extracted_feats_pkl
        |   RoBERTa_Feat_Flat.ipynb
        |   Algo_Aplic_and_Eval.ipynb
        |   Learner_Feat_extract.ipynb
        |   RoBERTa_Feat_extract.ipynb
└───Final_system
└───Models
└───pickled-dataframes
│   .gitignore
│   LICENSE
│   README.md
│   requirements.txt

```
