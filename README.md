# Play Store App Popularity Prediction

The purpose of this project is to predict if an app on the Google Play Store will be popular based on its features. This repository is a solution to the HackerRank Data Scientist Test.

## Description

Mobile applications have truly revolutionized the way products and service are used. Businesses have started to realize the potential of having an app and they have begun to capitalize on the apps user-friendly nature and easy to organize features.

### Problem Statement

Mobile Store is a leading online market place, where businesses can host their mobile apps and users can download them. In this competitive era, the more popular the app is,the higher the returns a business can expect. With this is mind, mobile store wants to analyze what factors influence an app's popularity

Using machine learning, help them predict the popularity of an app uploaded to their markertplace.

Perform an analysis of the given data to determine how different features are related to the app popularity. Build a machine learning model that can predict popularity. For each record in the test set (test.csv) predict the value of the popularity variable (High or Low).

Submit a csv file with a header row plus each of the test entries, each on its own line the file (submissions.csv) should have exactly 2 columns:
- app-id
- popularity (High or Low)

## Getting Started

### Dependencies

View `requirements.txt`

### Installation

1. Clone and change directory into repo:
```
git clone https://github.com/jovi-s/app-popularity.git && cd "$(basename "$_" .git)"
```
2. Install necessary packages
```
pip install -r requirements.txt
```

### Executing program

- Run `notebook/app-popularity.ipynb`
- Change read_csv and to_csv paths for HackerRank assessment only

## Authors

[Jovinder Singh](https://www.linkedin.com/in/jovindersingh/)

## Version History

- 0.2 (Future)
    - Perform further feature engineering
    - Hyperparameter Tuning
- 0.1 (Current)
    - Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

- [Play Store Analysis](https://github.com/sahanasub/Google-Play-Store-Analysis-and-App-Popularity-Prediction)
- [Play Store Analysis](https://github.com/halmonchaquayla/Google-Play-Store-Analysis)
- [Play Store Analysis](https://www.researchgate.net/publication/343769728_Analysis_of_Google_Play_Store_Data_set_and_predict_the_popularity_of_an_app_on_Google_Play_Store)
- [HackerRank Data Scientist Test](https://www.chegg.com/homework-help/questions-and-answers/1predict-mobile-app-popularity-mobile-applications-truly-revolutionized-way-products-servi-q86656966)
