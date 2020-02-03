
# Avocado Type Prediction

[![](https://github.com/aniacharya/MachineLearning/blob/master/images/Avocado.jpg)](https://github.com/aniacharya/MachineLearning/blob/master/images/Avocado.jpg)

Did you know that fresh avocados come in a variety of sizes, types and varietals?

Hass avocados are the most commonly known varietal type of avocado. The Hass variety accounts for the majority of avocados sold in the U.S. It’s the most well-known variety but not the only varietal. There are hundreds of known varietals of fresh avocados from the Anaheim variety to the Zutano.

Each varietal type has its own distinct characteristics in the following areas.
- Taste (nutty to light)
- Flesh texture (buttery to watery)
- Blossom type (A or B)
- Seed size
- Skin/peel color when ripe (green to purplish black)
- Fruit shape (round to obovate)
- Peel characteristics (thick and bumpy to thin and smooth)

The most commonly sold sizes of fresh Hass avocado can be identified by their Product Lookup code or PLU or sticker.
- Small/Medium Hass Avocado (~3-5oz avocado) - PLU4046.
- Large Hass Avocado (~8-10oz avocado) - PLU4225.
- Extra Large Hass Avocado (~10-15oz avocado) - PLU4770.
- Hass Avocado Bags - Size varies.

## Data overview
[![](https://github.com/aniacharya/MachineLearning/blob/master/images/data-vs-information.jpg)](https://github.com/aniacharya/MachineLearning/blob/master/images/data-vs-information.jpg)

Here in the dataset, each row represents a avocado, each column contains avocado's attributes described in column Metadata.

##### The Data set includes information about:
- Type of avocado - either conventional or organic.
- Average price.
- Total volume.
- Total bags of yield.
- Small bags, large bags, extra large bags.
- Year of yield.
- Sales of three different varities such as PLU4046, PLU4225, PLU4770.
- Region in which it is grown.


## Model Selection
Here, the alogorithms used to classify the type of avocado are Logestic regression, Decission trees and Random Forest.

Second part of the project involves the price prediction using linear regression.

## Insights
[![](https://github.com/aniacharya/MachineLearning/blob/master/images/insights.png)](https://github.com/aniacharya/MachineLearning/blob/master/images/insights.png)

Different algorithms have predicted based on the various criterion and we are see the comparision with respect to the Accuracy score:

##### Acocado Type Prediction:
1. Logestic regression give a result of 0.9241095890410959 
2. Decission tree give a result of 0.9956164383561644 
3. Random forest give a result of 0.9983561643835617 

##### Average Price Prediction:
Linear regression results are:
1. r_squared - 0.5551459309622133
2. Adjusted_r_squared - 0.5532177709106564
3. Mean absolute error for test set - 0.19960875675726328
