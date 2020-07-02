# DETECTION OF FAILURE OF BEARINGS ON IMS DATASET

Used the IMS dataset for prediction of when the bearings will fail using autoencoders

### Salient features of the dataset:

- The dataset used was the IMS dataset which comes from the Prognostics Data Repository hosted by NASA and was made available by the Center of Intelligent Maintenance Systems (IMS), of University of Cincinnati.
- The data was gathered from an experiment involving four bearings on a loaded shaft  rotating at a constant speed and consists of three different datasets: In set one, two accelerometers have been installed on each bearing, whereas in datasets two and three, only one accelerometer has been used.
- Each dataset is formatted in individual files named with the time of collection. Each file consists of 20,480 points with a sampling rate set of 20 kHz. Each row in the data file is a data point.
- The seven different states of health for the bearings observed are Early, Normal, Suspect, Imminent failure, Inner race failure, Rolling element failure and Stage 2 failure

### Autoencoders

- An autoencoder is a type of artificial neural network used to learn efficient data coding in an unsupervised manner
- The aim of an autoencoder is to learn a representation (encoding) for a set of data, typically for dimensionality reduction, by training the network to ignore signal “noise”
- Autoencoders are learned automatically from data examples. It means that it is easy to train specialized instances of the algorithm that will perform well on a specific type of input and that it does not require any new engineering, only the appropriate training data