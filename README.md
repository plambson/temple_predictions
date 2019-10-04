# Temple Predictions
A rudimentary attempt to forecast temples by region in advance of announcements by The Church of Jesus Christ of Latter-Day Saints leadership. This is created as a tongue-in-cheek attempt to put quantitative analysis to a decision that is directed and made with factors that lie well outside of any model, meaning the most predictive variable is exogenous. 
The attached notebook goes through the following process to collect cleanse and forecast.
1. Scrape the Church's website to get countries, states and information on membership, congregation, etc.
1. Create a dataset with minor modifications
1. Run linear regression where # of Temple ~ Congregations + Family History Centers + Total Church Membership + Stakes
1. Use model to predict the number of temples for each geography then compare the actual compliment to the prediction

The differences in actual temples and predicted temples are visualized below </br>
(ex. Brazil- Temples: 6, Predicted Temples: 12.02, Difference: 6.02)

##### Underserved Temples
![Underserved Temples](https://lambson-temple-images.s3-us-west-2.amazonaws.com/Underserved_temple.png)

##### Overerved Temples
![Overserved Temples](https://lambson-temple-images.s3-us-west-2.amazonaws.com/Overserved_temple.png)

##### Full Predicitons
[prediction.csv](https://lambson-temple-images.s3-us-west-2.amazonaws.com/prediction.csv)
