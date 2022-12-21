# Mini-Projects-
In the process of learning Python Programming Language, I tried executing all concepts practically with the help mini projects. I will be uploading all mini-projects here one by one. If you have any suggestions do let me konw. 

# Mini-Project 01-
Generating Data with noise, Plotting Single file data with best fit curves and Multiple Text File Handling

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
Plotting Covid-19 cases and deaths by states with best fit curve 

Conclusion:
- Sub-data frame of california's total cases and days do not follow the stated distribution.
- Since we used exponential function of numpy.random for creating a random data, the data is following exponential distribution.
- We can analyse and manipulate the given data with the help of pandas and numpy library and for plotting we used matplotlib.pyplot.


# Mini project 03 -
Exploring the Data Sets of Hotel  bookings

Conclusion:
- According to given data, two types of hotels categories preferred by customers are "City Hotel" and "Resort Hotel".
- Among these 2 categories "City Hotel" have more booking than "Resort Hotel" throughout the year.
- August, July, May, October and April had highest number of bookings in year respectively.
- Both categories have bookings mainly in mid-time of the month i,e around 15th date of each month.
- There are more average days in waiting list for "City Hotel" than "Resort Hotel".
- On average Customer mainly prefers "Resort Hotel" for weekend night stays than "City Hotel".
- During weekdays also on average customer prefers "Resort Hotel" than "City Hotel" for night stays.
