# Word-Pronounciation

Requirements: Android Studio, Jupyter Notebook

## Probelm Statement

- Therapy tools available in the market focuses only on assisting the therapist, but sometimes that does not provide an efficient way in treating them. 
- Hence, this proposal aims to include a novel and innovative ML based method in diagnosing the communication disorders.
- So this project will help the children to rectify the disorder easily at an early age without spending a lot of money, in an efficient way and fun way.

## Modules

- Data collection
- Building a ML model
  - Data Preprocessing
    * Padding
    * Spectogram
    * One-hot-encoding
  - Model Fitting with CNN
  - Converting the model to tflite model
- Integrating Model with application
- App Development



<img width="549" alt="image" src="https://github.com/11swathi/Word-Pronounciation/assets/46857476/89dd4763-7c4d-48ed-97ab-7f680dae9201">



## Dataset

- Voice recording of children aged between 6-14yrs is collected (both disordered and normal audios).
- Recordings consist of children saying small words.
- Then this audio files are converted into wave forms for data pre-processing.


## What do we do in the app?

- Record the audio of the child for whom, therapy is needed.
- The recorded audio is now compared with the tflite model.
- The data is now tested, and the output s printed in the screen.
- The percentage of the correct pronounciation is printed and the the pronounciation is compared with the other words, and the percentage is also printed.
- So, with the app can help children to speak correctly and clearly.
- Children competively will use the app, to get a 100% correct pronounciation.
- This is now a efficient way of giving a therapy.


# Final Output of the app 

<img width="877" alt="image" src="https://github.com/11swathi/Word-Pronounciation/assets/46857476/83cd0de5-8811-4b1e-a365-58f3ef584e99">


