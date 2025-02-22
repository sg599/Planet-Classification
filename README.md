***Planet Classification***

*Project Overview*

The idea of this project is to perform a multi-class classification on a dataset with astronomical objects.The goal is to train two models to classify the object type, and compare afterwards the models' performance. The data was preprocessed using numpy, Matplotlib, Seaborn, Pandas. For the models the `sklearn` library was used with model 1 being *Random Forest* and model 2 being *Neural Network (MLP)*.

*Dataset*

The dataset inlcudes various numeric features giving information about the object's size, weight, distance, gravity, radiation, etc. Based on these features there are 4 possible objects to be classified as:
* Planet
* Moon
* Star
* Dwarf Planet

*Installation and Requirements*

* Python 3.x
* Required libraries: pandas, matplotlib, seaborn, numpy, sklearn

*Usage*

* Use `data.npz` as the dataset to perform the data preprocessing, visualizations, and model training/testing.
* View `Report_Planet_Classification.pdf` for explanation of the process and the results.

*Key Findings*

* Equal accuracy for model 1 and model 2 (72%).
* The Neural Network took longer to be trained compared to the Random Forest.
* Choose model 1 (Random Forest) 

*File Structure*
* `data.npz` => The dataset used
* `Planet_Classification.ipynd` => Pyhton notebook for the model selection
* `Report_Planet_Classification` => Full report about the project
* `README.md` => Project Documentation
