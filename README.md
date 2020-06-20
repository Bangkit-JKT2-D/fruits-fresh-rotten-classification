# Fresh-Rotten-Fruits-Predictor
--this is a final project assignment--
We create a Tensorflow model to predict the fresh and rotten fruits. By doing so, we hope we can easily separate fresh and rotten fruits from fruit images.

## Project Structure
```bash
.
├── README.md
├── datasets
│   ├── test "--> Our test datasets, contains fresh and rotten apples, bananas, oranges"
│   │   ├── freshapples
│   │   ├── freshbanana
│   │   ├── freshoranges
│   │   ├── rottenapples
│   │   ├── rottenbanana
│   │   └── rottenoranges
│   └── train "--> Our train datasets, contains fresh and rotten apples, bananas, oranges"
│       ├── freshapples
│       ├── freshbanana
│       ├── freshoranges
│       ├── rottenapples
│       ├── rottenbanana
│       └── rottenoranges
├── fresh-rotten-fruits-improve.ipynb "--> final python notebook for creating our model"
├── fresh_rotten_fruits_baseline.ipynb "--> baseline python notebook"
└── upload\ test
    ├── Apple,\ Banana,\ Orange "--> List of Images we used for testing the model"
    └── Wrong\ predict "--> List of Images that already tested and the model predict it wrong"
```

## Datasets
Training Data and Testing Data that were used are sourced from kaggle :https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification

## Network
For this model, we use Convolutional Neural Networks. Our model used transfer learning InceptionV3 for the baseline model with 6 class(Fresh and Rotten banana, apple, and orange). We also using VGG16 for the improved model with 2 class(Fresh and Rotten Fruit) which is our final model.

## Prequisites
You don't need to install anything since its written in Google Colab which is a cloud service
- Copy this repository link into the collab https://github.com/Bangkit-JKT2-D/fruits-fresh-rotten-classification/blob/master/fresh-rotten-fruits-improve.ipynb
- After succesfully open the notebook, create cookies.txt for downloading the dataset from kaggle
- First of all, With the assumption of using Google Chrome, download extension [cookies.txt](https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg)
- Open the kaggle link dataset [fruit-rotten-dataset](https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification) then on your right top corner of browser, choose the cookies.txt.
- download the cookies.txt.
- upload the cookies.txt on the notebook as what required

## Built With
* [Tensorflow Keras](https://www.tensrflow.org) - The AI framework used

## Authors
* **Ahmad Emir Alfatah**  - [aemiralfath](https://github.com/aemiralfath)
* **Anggardha Febriano**  - [anggardhanoano](https://github.com/anggardhanoano)
* **Zahroh Ayu Khumayr**  - [zakhumayr](https://github.com/zakhumayr)

