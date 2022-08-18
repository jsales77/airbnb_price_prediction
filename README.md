# airbnb_price_prediction
**BACKGROUND**

Airbnb is an online marketplace that connects people who want to rent out their homes with people are looking for accommodations in specific locales. It offers property owners a way to make their property profitable as well as offering cheaper accommodations to customers than that of a hotel.

In this project, we begin by cleaning the data set as well as creating a new column for state abbreviations. Once the data has been cleaned, the dataframe is plotted into various graphs looking for correlations between variables. We find that price does not have a strong correlation with any other variable within the dataset.

Once the exploratory analysis is finished, we begin building and testing linear and multiple linear regression models. Both of these models showed poor results so I moved on to using K-Nearest Neighbor regression and classifier models. The classifier model performed the best with an accuracy of 77%. Lastly, we test if a decision tree would show better results than those of the KNN classifier model. The decision tree only showed 58% accuracy which meant teh KNN classifier model was the most accurate.

Creating a higher accuracy with this data set would not be possible due to a few factors. The first being that the timeline is limited to one year and does not provide any trends in price changes over the years. The second being that many listings had outrageous price ranges or incredibly high minimum nights required (>1000). As a result, the 77% accuracy provided by the KNN classifier model will be the best model to use for this data set.
