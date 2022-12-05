# EDA-Hotel-Booking-Analysis
OBJECTIVE:

Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other


STEPS FOLLOWED:


•	Data Collection and Understanding:

First we  read the data using pandas libarary.After collecting the data it’s very important to understand our data. So we had hotel booking analysis data which had 119390 Observatios and 32 Attributes. Also we observed there are different types of datatype 
like integer,float and object.


•	Data Cleaning and Manipulation: 

First we have found the null and missing values. 
Data can go missing due to incomplete data entry, equipment malfunctions, lost files and many other reasons.
There were four columns namely company, agent, country and children with missing values. Then fill the missing value of company with 0, 
fill the missing value of country with others, fill the missing value of children with mean and fill the missing value of agent with 0.


•	Handling Duplicate Data: As mentioned earlier there were 119390 Observations out of which 31994 duplicate values are there, so we dropped it from our data set.then we have used Python pandas matplotlib and seaborn to explore the data


CONCLUSIONS :

1.We observe that 61% of customers prefer City hotel whereas 39% people opt for Resort hotel

2.Though city hotel is most preferred we also observe that most cancellations are made for city hotel type. In terms of percentage city hotel has 67% and resort hotel has 33% of cancellation

3.We see that there are 11 types of room type out of which room type A is in demand

4.we also note that Room type H,G,C are better with respect to adr

5.Upon exploring we observe that the reason for cancellation is not impacted for not receiving reserved room type

6.There are 4 customer types out of which Transient type count is high

7.The unique values of market segement are 'Direct', 'Corporate', 'Online TA', 'Offline TA/TO',
       'Complementary', 'Groups', 'Undefined', 'Aviation' out of which Online TA is count is high
       
8.Agent 9 has done more number of bookings 

9.In the month of August and July high number of bookings are made

10.most number of customers donot opt for any sort of changes in booking 

11.There are 5 types of distribution channel TA/TO,Direct,Corporate,GDS,Undefined here we observe that 81.98% people opt for TA/TO distribution channel where as 12.27% opt for Direct distribution channel

13.For City Hotel GDS generates more revenue

14.The most preferred meal is Bed and Breakfast

15.People from Portugal and europe are the top 2 countries who make most number of bookings

16.We observe that Avg adr rises from January upto middle of year and reaches peak at August and then lowers to the end of year.

17.Resort hotel has high percentage of repeated guests and Portugal is the country from where most number of repeated guests are present

18.We observe that most customers donot have any special request The maximum number of special request opted is 5 where as very few customers has opted for this

19.We observe that for city hotel the highest duration of stay 3 For resort hotel maximum duration of stay is 1

20.2016 is the year with more number of bookings

