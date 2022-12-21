# Mini-Projects-
In the process of learning Python Programming Language, I tried executing all concepts practically with the help mini projects. I will be uploading all mini-projects here one by one. If you have any suggestions do let me konw. 

# Mini-Project 01-
## Generating Data with noise, Plotting Single file data with best fit curves and Multiple Text File Handling

Conclusion:
- 4 steps for curve fitting of and distribtution or data-
Generating or importing data.
Defining function for the distribution.
Plotting oringinal data.
Executing curve fit on the data and plotting it.

- We use the function curve_fit from the python module scipy.optimize to fit our data. It uses non-linear least squares to fit data to a functional form. One can learn more about curve_fit by using the help function within the Jupyter notebook or scipy online documentation. The curve_fit function has three required inputs: the function you want to fit, the x-data, and the y-data you fit. There are two outputs. The first is an array of the optimal values of the parameters. The second is a matrix of the estimated covariance of the parameters from which you can calculate the standard error for the parameters.
- We use for loop for mutiple file handling. Alos we used "for loop" for sorting and arranging data in order and avoid scatterness of the plot.
- Adding titles, labels and legends in the plot makes the plot more attractive and presentable.


# Mini Project 02 - 
## Plotting Covid-19 cases and deaths by states with best fit curve 

Conclusion:
- Sub-data frame of california's total cases and days do not follow the stated distribution.
- Since we used exponential function of numpy.random for creating a random data, the data is following exponential distribution.
- We can analyse and manipulate the given data with the help of pandas and numpy library and for plotting we used matplotlib.pyplot.


# Mini project 03 -
## Exploring the Data Sets of Hotel  bookings

Conclusion:
- According to given data, two types of hotels categories preferred by customers are "City Hotel" and "Resort Hotel".
- Among these 2 categories "City Hotel" have more booking than "Resort Hotel" throughout the year.
- August, July, May, October and April had highest number of bookings in year respectively.
- Both categories have bookings mainly in mid-time of the month i,e around 15th date of each month.
- There are more average days in waiting list for "City Hotel" than "Resort Hotel".
- On average Customer mainly prefers "Resort Hotel" for weekend night stays than "City Hotel".
- During weekdays also on average customer prefers "Resort Hotel" than "City Hotel" for night stays.


# Mini Project 04 - 
## Titanic Survivors Data Exploration and Visualization

Conclusion:
- We can see that amongst those who survived, maximum number of passengers had embarked at Southhampton.
- Because of 25% of correlation between survived and fare, we can say that mostly passengers who survived had higher average fares i.e mainly first class passengers.
- More passenger survived who were travelling alone than those travelling with friends or family.
- We can observe that maximum females survived the journey. This must be mainly because, we have seen in the film as well, women and children were given preference to board the safety boats.
- Maximum passengers who survived are 1st Class females while the least are 3rd class males.


# Mini Project 05- 
## App Development (Mall Billing Dashboards)

Objectives:
- Creating a mall billing dashboard, that can take information like name, phone number, number of units of medical purpose items, grocery items and cold drinks from user and generate bill with respective taxes with unique bill number.
- Adding buttons like clear, generate bill, clear, exit fro performing different functions on given data.
- Creating highly interactive Mall Billing Dashboard.

Conclusion:
- With the help of the Tkinter library we, created an interface for the bill.
- Dashboard is divided into 6 Label Frames such as customer details, Medical purposes, Grocery items, Cold drinks, 2- Bill detail area.
- Customer Details: This Label Frame takes inputs from user like Customer's Names and phone numbers and also contains a text box in which we can enter previously generated bill numbers and search for their details with the help of the search button.
- Medical Purpose: This label frame takes inputs from user such as several units of medical products i.e Sanitizer, Mask, Hand Gloves, Dettol, Disprine and Thermal Gun.
- Grocery Items: This label frame takes input from user such as several units of Grocery items i.e Rice, Food oil, Wheat, Pulses, Flour, Flour, Suger.
- Cold Drinks: This label frame takes inputs from user such as several units of Cold drinks i.e Coke, Sprite, Lime, Fanta, Mazz and Mountain Dew.
- Bill Details Area: This Label Frame has 6 text boxes with their labels. On clicking the Total button, Total Medical Price, Total grocery price Total Cold Drinks price will give total prices i.e sum of the product of several units of each product and its price of each section in medical purpose items, grocery items and cold drinks respectively and Medical Tax, Grocery Tax and Cold Drinks Tax will give the applicable total amount of taxes on all medical purpose products, Grocery items and Cold drinks respectively.
- Generate bill button will give bill receipts in the above-specified format with all entered information by the user, bill number and the total amount of the bill and will also save the bill.
- Clear Button will clear all entered data by the user.
- Exit Button will exit the application.
- We Can add new items in any section, and change the prices of each product and its applicable taxes by making required changes in the code easily.

