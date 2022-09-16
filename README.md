# Airline-Satisfaction

Classification model for airline passenger satisfaction with **Random Forest**.

***

Multicollinearity Test:
<html>
<body>
<!--StartFragment-->

variables | VIF
-- | --
Age	| 6.705045
Flight Distance	| 3.060498
Inflight wifi service	| 6.520216
Departure/Arrival time convenient	| 6.747509
Gate location	| 7.809001
Food and drink	| 6.147438
Leg room service	| 7.381074
Checkin service	| 7.392314
Departure Delay in Minutes	| 1.142629
Class	| 7.170803

<!--EndFragment-->
</body>
</html>

***

Train Score:

class | precision | recall | f1-score | support
-- | -- | -- | -- | --
0    |   1.00    |  1.00   |   1.00   |  44955
1   |    1.00   |   1.00   |   1.00  |   58498
accuracy  |          |         |      1.00  |  103453

Test Score:

class | precision | recall | f1-score | support
-- | -- | -- | -- | --
0   |    0.95  |    0.94  |    0.95   |  11239
1   |    0.95   |   0.97    |  0.96   |  14625
accuracy |         |            |     0.95  |   25864

***

More than half the passengers are not satisfied with their flight experience, as we've discovered, some of the things that might significantly impact their experience are ```wifi service``` and ```check in service```. 
- ```wifi service``` could be improved by providing a faster or more stable connection. Or to make it available in all class including eco class.
- ```check in service``` could be improved by easier online check in, to reduce queue time and possibility to aboard the plane late.
