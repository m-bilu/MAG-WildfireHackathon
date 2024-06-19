# 🎆 MAG Wildfire Hackathon 2nd Place Winners 🎆

This repo contains the code and dataset developed by Team Cedar Bend, coming in at 2nd place out of 30 teams at the MAG Wildifre Hackathon on May 25th. 

## Goal

The goal of the challenge is to create a model that is capable of predicting future fire growth when given weather, fire weather indices, topography, fire fuel, and low-resolution fire hotspots

The entire dataset contains data covering 8 fires in BC in 2018 with over 250k total area burned. All 8 fires overlapped in duration and burned in the same geographic location. You will use 7 of these fires as your training set for your model where you have full labels on the area burned per Jullian day. The test dataset contains a single fire in which your task is to predict the future fire growth over 20 days.

Here is a snippet of some of these fires:

![image](https://github.com/m-bilu/MAG-WildfireHackathon/assets/92327720/5e614df3-8c2e-4705-b64d-06231dffa4ef)

Our model should train to predict the fire growth given the weather, fire weather indices, topography, fire fuel, and past fire growth. Our model will be tested on its ability to predict fire growth for future days.

## Evaluation

Submissions are evaluated using a combination of evaluation metrics. Fire 2214 is located in BC and lasts for 30 Jullian days (213 to 243). Your goal is to predict fire growth for fire 2214 in the test folder for Jullian days 223 to 243. We will provide the first 10 days of burning (213 to 223) for fire 2214.

In your submission, set burned areas to be 1.0 and non-burned areas to be 0. Burned areas are areas that your model predicts to be burned over the latter 20 days for the test fire. Your submission does not need to include information on specific burned areas each day. The first 10 days of burning per Jullian days are provided for the test fire.

![image](https://github.com/m-bilu/MAG-WildfireHackathon/assets/92327720/a3f1a000-84f2-441d-b6b7-c575c54f68ca)


## Results

The top 10 teams off of the Kaggle submissions were selected to present, from which the top 3 were selected on their model's insights, scalability and efficiency as well as test accuracy.

For an in-depth look at our methodology, you can look at the .ppt file in the repo.
