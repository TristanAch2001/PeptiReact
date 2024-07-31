# PeptiReact

PeptiReact is a random forest based model used to predict CD8+ T cell cross-reactivity between two given epitopes. The user must define a subject peptide, against which a T cell
is known to react, and a query peptide. The model will output a binary prediction on cross-reactivity.

The dataset that was used to train the model is available as features.xlsx, additionally the original epitope sequences are available as .txt files.

Model hyperparameters can be found in the optuna notebook.
