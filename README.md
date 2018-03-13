# Sign Language Recognition System
The overall goal of this project is to build a word recognizer for American Sign Language video sequences, demonstrating the power of probabalistic models. In particular, this project employs [hidden Markov models (HMM's)](https://en.wikipedia.org/wiki/Hidden_Markov_model) to analyze a series of measurements taken from videos of American Sign Language (ASL) collected for research (see the [RWTH-BOSTON-104 Database](http://www-i6.informatik.rwth-aachen.de/~dreuw/database-rwth-boston-104.php)). In this video, the right-hand x and y locations are plotted as the speaker signs the sentence.

![Introduce image](introduce.png)

# Install
This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/0.17/install.html)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [jupyter](http://ipython.org/notebook.html)
- [hmmlearn](http://hmmlearn.readthedocs.io/en/latest/)


Notes:

- It is highly recommended that you install the Anaconda distribution of Python and load the environment included in the "Your conda env for AI ND" lesson.
- The most recent development version of hmmlearn, 0.2.1, contains a bugfix related to the log function, which is used in this project. In order to install this version of hmmearn, install it directly from its repo with the following command from within your activated Anaconda environment:
```
pip install git+https://github.com/hmmlearn/hmmlearn.git
```

