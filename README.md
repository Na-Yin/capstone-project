# TDI Capstone Project
(Sep. to Nov. 2019 cohort)

This project is intended to help US power plant forecast industrial power consumption using history power usage data.

I'm currently still working on deploying a app to Heroku. Stay tuned to look at my website.


## 1: Why important?
Industry is one of the main economic sectors which consume a significant amount of power. Power supply planning requires the optimization of the decisions concerning the short term demand for each of the next day. Accurate forecast allows to minimize the cost of delivery of power for customers and thus is very important to power plant. 
Each industrial site has its own power consumption pattern. One power plant will supply power to lots of industrial sites. If we use one model to forecast all the industrial sites, we could not have a good prediction. It's better to build one model for each industrial site and then combine together to forecast next day power consumption for that region.

## 2: Dataset
The dataset for this project is from ENERNOC 2012 Commercial Energy Consumption Data which include quarter hour power usage of 100 industrial sites for 2012. 
These data also provide the sites information: longitude & latitude, industrial category and area size. These sites could be classified into four industrial catergories: commercial property, education, food sale & storage and light industrial.
Although these sites are located in different area of US, location feature has few contribution to prediction model. Thus, I use them to mimic the various industrial sites within one power plant supplying area.

## 4: Conclusion
The final model of this project will be very helpful for power plant to make prediction of how much power to delivery. Weather also has a significant influence on power consumption, I plan to incorporate weather data into my model. Thus, this project will help power plant to be better face the impact of special weather or event on power usage.

## 5: Next steps:
- Incorporate weather data
- Construct Heroku app

## Feedback and Contact:
If you have any feedback on my project, or you would like to discuss potential work that we can do together, please feel free to reach out to me: na.yin@mg.thedataincubator.com