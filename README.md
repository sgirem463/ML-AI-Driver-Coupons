# The Coupons for Drivers project
## Overview
The project analyze how lilely a driver would accept different coupons (Bar, Coffee House, takeaway food...) delivered to their cellphone. Data from a csv file was collected from a survey done on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver.

## Analysis
There are three sections in the Jupyter project.

### The first section
reads the coupons data into a DataFrame, examine the data and does some cleaning up by removing the 'car' column which isn't relevant to our analysis, also removes rows with NaN values.

### The second section
investigates the Bar coupons, check to see which groups of driver are more likely to accept Bar coupons, the conclusion is:

    - Those who went to a bar 4 or more times a month is highly likely to accept a bar coupon, at 76.2%
    - Those who go to cheap restaurants more than 4 times a month and income is less than 50K are also very likly to accept, at 74.6%
    - Those who go to bars more than once a month and are under the age of 30, at 72%
    - Those who go to bars more than once a month, had passengers that were not a kid, and were not widowed, at 70.9%
    - Those who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry, also at 70.9%

### The third section
investigates the Coffee House coupons, check to see which groups of driver are more likely to accept Coffee House coupons, the conclusion is:

    - Single female professionals who went to a Coffee House more than once a month in both morning (79.2%) and afternoon (75.8%)
    - The slighter broader group all female professionals who went to a Coffee House more than once a month in the morning is also good (70.8%)
    - Those who went to a coffee house more than once a month when temperature is 80 and the exprration is 1-day (77.6%)
    - Those who went to a Coffee House more than once a month with friends as passengers and with a Bachelors or higher education (75.6%)
    

#### The Jupyter Notebook is: 
