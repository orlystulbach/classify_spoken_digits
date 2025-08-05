# Model Classifying Spoken Digits

Our model predicts the values of spoken digits for the sake of helping medical professionals with accurate dosage labeling. Our model can predicts with 85% accuracy. We programmed this using numerous Python libraries, includig the Keras library to build and train our neural network and the Librosa library to intake our 30,000 audio files, convert them to MFCC coefficients, and help our model analyze and predict the value of the spoken digit.

The AI4ALL Ignite Program seeks to expand access to AI education to all students. It is a wonderful program that hosts a weekly lecture, teaching students about the concepts and implementations of AI, as well as the ethical considerations one must make when building an AI model and/or using AI. The program assigns students to small groups with provided mentors and enables students to collaborate on an AI project of their choosing.

## Problem Statement <!--- do not change this line -->

Because my group was assigned to the Healtchare and Life Sciences sector of AI4ALL, I decided to approach my doctor and ask how she though AI could help improve her practice. She explained that a simple dictation tool would make a huge impact. My group processed this information alongside our mentors and did more research into how a model that could process audio could make a difference. We learned that according to the NIH, "Medication errors rank as the most frequent and avoidable source of patient harm." We realized we should begin by training our model on digits, not only because they would be good building blocks, but because they could improve medication labeling errors!

## Key Results <!--- do not change this line -->

Enumerate the main results of this project in a list and describe them.
1. Inputted 30,000 recorded entries from an Audio MINST Kaggle dataset, as well hundreds of our own voiced entries.
2. Achieved 99% accuracy with our model.
3. Made a Streamlit web interface to test our model in real time and as of now have attained 85% accuracy.


## Methodologies <!--- do not change this line -->

(UPDATE IN README.md)
To accomplish this, we used numerous Python technologies, primarily including the Keras and Libroas libraries. Keras enabled us to build and train our model. Librosa provided us with the ability to convert our audio (.wav) files to MFCC coefficients that our model could digest and predict the values of. We used a neural network with 112 features and 10 layers, as well as a data augmentation layer.


## Data Sources <!--- do not change this line -->

[Link to Kaggle Dataset](https://www.kaggle.com/datasets/sripaadsrinivasan/audio-mnist)

## Technologies Used <!--- do not change this line -->

- Python
- Keras (Tensorflow)
- Librosa
- Numpy
- Streamlit
- Sci-kit learn
- Noise reducer


## Authors <!--- do not change this line -->

(UPDATE IN README.md)
List the names and contact information (e.g., email, GitHub profiles) of the authors or contributors.
- Christopher Mayfield -- https://github.com/christophermayfield -- [cmayfield3@student.mtsac.edu](mailto:cmayfield3@student.mtsac.edu)
- Orly Stulbach -- https://github.com/orlystulbach -- [o.stulbach@gmail.com](mailto:o.stulbach@gmail.com)
- Beamlak Woldeab -- https://github.com/beamlakwoldeab -- [bwoldeab@smith.edu](mailto:bwoldeab@smith.edu)
- Kanishka Singh -- [kanishka.singh416@gmail.com](mailto:kanishka.singh416@gmail.com)
