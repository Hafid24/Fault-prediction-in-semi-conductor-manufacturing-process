# Fault-prediction-in-semi-conductor-manufacturing-process

A complex modern **semi-conductor manufacturing process** is normally under consistent surveillance via the monitoring of signals/variables collected from sensors and or process measurement points. The datesets are donated in *2008-11-19* and can be obtained from <http://archive.ics.uci.edu/ml/machine-learning-databases/secom/>.
Data descreption: it consists of two files one is *secom.csv* and *secom_labels.csv*.

- *1567* data points or measurements.
- *590* variabels, one label *1* for fail and *-1* for pass and variable for the time points beimg measured.

Analysis process:

- Reduce the number of features and obtain the most relevent variables that affect the fault.

- Develope a *classification model* to detect that occurance of a *faul*.

- Develope another *classification model* to *predict* the *fault* within **1 hour**.
