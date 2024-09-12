Online Shoppers Purchasing Intention Dataset Description:
This dataset represents the sessions of different users on an e-commerce website over a one-year period.
The goal is to predict whether a user will make a purchase based on various attributes related to the user's session. 
The dataset is especially interesting because it contains both numerical and categorical attributes, including web-page navigation details, as well as some external factors.


Columns
1. Administrative:
Type: Numerical
Description: This represents the number of pages of this type (i.e., administrative) that the user visited during the session.

2. Administrative_Duration:
Type: Numerical
Description: This is the total amount of time (in seconds) the user spent on administrative pages during the session.

3. Informational:
Type: Numerical
Description: This represents the number of informational pages visited by the user during the session.

4. Informational_Duration:
Type: Numerical
Description: This is the total amount of time (in seconds) the user spent on informational pages during the session.

5. ProductRelated:
Type: Numerical
Description: This represents the number of product-related pages visited by the user during the session.

6. ProductRelated_Duration:
¶
Type: Numerical
Description: This is the total amount of time (in seconds) the user spent on product-related pages during the session.

7. PageValues:
Type: Numerical
Description: Represents the average value of the page averaged over the value of the target page or the completion of an e-commerce transaction. Higher values indicate higher intent to purchase.

8. SpecialDay:
Type: Numerical (ranging between 0 and 1)
Description: This feature indicates the proximity of the time of the site visit to a special day (like Valentine's Day or Mother's Day). For instance, if the day is a special day, its value might be 1 or close to 1. If it's far from any special day, it'd be closer to 0.

9. Month:
Type: Categorical
Description: Represents the month of the year during which the session occurred. For example, "Jan" for January, "Feb" for February, and so on.

10. Region:
Type: Categorical
Description: Represents the geographic region from which the user accessed the website.

11. TrafficType:
Type: Categorical
Description: Represents the type of traffic source by which the user came to the website. It could denote different channels like direct traffic, referrals, organic search, paid search, etc.

12. VisitorType:
Type: Categorical
Description: Specifies the type of visitor. Categories include "Returning_Visitor", "New_Visitor", and possibly other types.

13. Weekend:
Type: Binary (True/False)
Description: A boolean feature indicating whether the session took place on a weekend.

14. Revenue:
Type: Binary (True/False)
Description:A target variable indicating whether the session concluded with a transaction (True if a purchase was made, False otherwise).

The dataset provides insights into the behavior of website visitors and their purchasing patterns, making it a valuable resource for e-commerce businesses aiming to enhance their user experience and increase sales.
You can find the dataset here: https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset
