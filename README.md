# Transposon Classifier "RFSB"
Transposon classification tool for nucleotide sequence classification, providing classification, model training and prediction evaluation. *RFSB* is part of [TransposonUltimate](https://github.com/DerKevinRiehl/TransposonUltimate).

- **Mode 1: Transposon classification**
  - **Description**: Mode 1 classifies given transposon DNA sequences in a fastaFile and stores the predicted results into an outputPredictionFile. (RFSB comes with a pretrained classification model ready to use)
  - **Input**:  Transposon nucleotide sequence(s) (FASTA File)
  - **Output**: Class predictions (and probabilities)
- **Mode 2: Prediction evaluation**
  - **Description**: Mode 2 evaluates given transposon classification results by a classification software predLabelFile onto the true class labels trueLabelFile and calculate results of the evaluation (accuracy, precision, recall, F1, MCC, false positive rate and the confusion matrix for all three perspectives). The results can be print to console, stored into CSV and PICKLE file, and in addition to that diagrams can be generated as well.
  - **Input**:  Prediction label file and true label file
  - **Output**: Classification performance evaluation
- **Mode 3: Model training**
  - **Description**: Mode 3 trains the proposed RFSB transposon classification model onto a given transposon DNA sequence database. The taxonomy can either be given or is automatically detected scanning the true label file corresponding to the database fasta file. Once trained, the model will store the taxonomic scheme and given e-threshold. The proteinDB necessary to run RPSTBLASTN however needs to be given, when running Mode 1.
  - **Input**:  Transposon database, true labels (optionally classification taxonomy)
  - **Output**: Trained classification model

# Installation, Explanation of file structures, Citations, Acknowledgements and Benchmark Code
Please read README.md here [transposon_classifier_rfsb](https://github.com/DerKevinRiehl/transposon_classifier_rfsb)

# Changes made for @unisaVersion



