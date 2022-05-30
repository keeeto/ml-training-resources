# ml-training-materials

This is a collection of interactive notebooks covering different aspects of machine learning primarily for chemistry/materials science.

## Running locally

To run the notebooks on your local machine, you will want to set up the correct `conda` environment.


```
conda env create -f ml-mater-conda.yaml
```

## Contents

* Classical ML models for generic classification
	- classification_decision_tree.ipynb
* Classical ML models for property prediction
	-  regression_decision_tree.ipynb
	-  sulfides_exercise.ipynb
* Deep neural networks for classifying spectra
	-  dnn_for_spectra.ipynb
* Interpretable machine learning
	-  interpretable_ml.ipynb

## Run in Colab

* Navigate to http://colab.research.google.com/
* Sign in with your Google account
* On the menu that appears choose Github
* In the searchbar type: https://github.com/keeeto/ml-training-materials
* Choose the notebook you want to open
* For the practical; open `regression_decision_tree_practical.ipynb`

## Saving notebooks

* If you want to save and reload the notebooks you will need to save a copy of the original notebook to your _Google Drive_
* Go to File > Save copy in Drive
* When you want to reload navigate to: http://colab.research.google.com/
* Got to File > Open
* Choose the _Google Drive_ tab, you should now see your saved notebooks.

## Credits and Attribution

These notebooks were developed for various projects and courses.

### `classification_decision_tree.ipynb`

Is largely based on material from the excellent [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
by Jake VanDer Plas and is material that I have used teaching the [SciML Introduction to Machine Learning course](https://github.com/stfc-sciml/sciml-workshop). 

### `regression_decision_tree.ipynb`

Is based on material published in the paper [Data-Driven Discovery of Photoactive Quaternary Oxides Using First-Principles Machine Learning](https://pubs.acs.org/doi/full/10.1021/acs.chemmater.9b01519).

### `sulfides_evercise.ipynb`

Is an excercise that I developed as part of my course - Machine Learning for Chemists, that I teach at the University of Reading

### `dnn_for_spectra.ipynb`

Was developed as part of the [SciML Introduction to Machine Learning course](https://github.com/stfc-sciml/sciml-workshop).

### `interpretable_ml.ipynb`

Is material to accompany a chapter on Building Trust in Machine Learning in my book [Machine Learning in Materials Science](https://pubs.acs.org/doi/book/10.1021/acsinfocus.7e5033).
