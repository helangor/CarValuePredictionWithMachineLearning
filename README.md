# Predicting price of the car with Machine Learning
Python script that takes raw car data as an input. Then does some data wrangling, data visualization, training RandomForestRegressor ML model and finally tiny user input option to 
get the value of the car. 


#### Why I made this project
I wanted to try Machine Learning with Python. Predicting the price of the car seemed very interesting topic to try it on. 

#### What I learned 
1. Getting data: Data was obtained by using selfmade Python scraper to scrape the internet car selling website. Data is not included in this repository. My dataset was about 30k cars. 
2. Cleaning: How to find best attributes, which has the highest correlation with the price and which attributes were useless and should be dropped. Also wrangling attributes to correct formats so ML could understand them and cleaning anomalities and outliers from the data.  
3. Visualization: Visualizating data to get good understanding about it. Figuring out outlier limits and best correlation attributes 
4. Creating Machine Learning model: Tried several different algorithms to find the one with the best accuracy. Also tried to avoid over/underfitting as best as I could.
5. User Input: Creating simple User input to test the model. Selecting best attributes and output is the price of the car. 

Was a really nice project, which taught a lot to me. I was very happy with the accuracy of the model. It is impressive when you take in mind that the data I used was scraped and the price was car list price. Therefore it had many changing factors. 

I also did a project to improve projects Automation level to nearly 100 percent with camera and image recognition. Repo to it is [here](https://github.com/helangor/AutomaticLicensePlateRecognitionCamera)

## License
[MIT](https://choosealicense.com/licenses/mit/)
