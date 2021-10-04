# Classification of Physiological Signals
Processing signals from wearable sensors (pressure, temperature, electrocardiogram, electroencephalogram, electrodermal) to extract features and perform classification using Python
Project performed in cooperation with a fellow coursemate Antonio Arbues at ETH Zurich

## Abbreviations
- ECG = electrocardiogram
- EEG = electroencephalogram
- EDA = electrodermal activities
- GSR = galvanic skin response
- EMO = facial landmark trajectories

## Main Code
- (aarbues_asarioglou_code.ipynb) -> Extracting a wide variety of features from the provided datasets of ECG, EEG, EDA and EMO measurements from 44 participants as they watched different affective movie clips from the AS-CERTAIN dataset. Then, using the extracted features to train a random forest classifier to try to classify the emotional state of each participant while watching a movie clip, by rating both valence (positive or negative feeling) from -3 to +3 and arousal (intensity of the feeling) from 0 to 6.

## Extracted Features
- (Arousal_Valence.npy) -> Dataset with self-rating of arousal and valence while watching each movie clip by all the individual participants
- (EDA_features.npy) -> Dataset with EDA features extracted
- (EEG_features.npy) -> Dataset with EEG features extracted
- (EMO_features.npy) -> Dataset with EMO features extracted


