# car_price_predictor

Look powerpoint here for graphical and easy explanation about what I did.

Program tells you the price of a car

First I scraped lots of car data from the internet car selling website. Data is not included in this repository.

Then I modified data, dropped useless attributes, cleaned it, splitted some data to different columns. In practical just modified it so it so I can train my predictor to be as accurate enough it can be. 

Then I described data and got knowledge about what are the outliers and what limits I should use to make my data be good quality.

Then I scaled numerical values and tried many different algorithms and figured out what worked best in my case.

Finally I used my model to predict car price. You enter Manufacturer, Model, Year, Mileage, Fuel type, engine size, drivetrain, transimission and seller data. Output is the typical selling price of that kind of car in finnish car market. 

In future I plan to implement this into website and add also power as one attribute that helps us to predict the price. Because car power has huge correletaion on car's price too. For example now Scoda Octavia RS price is hard to predict, because we cant say with these attributes is the car RS or normal Octavia. But with car power attribute we would know and our model would be more accurate.

