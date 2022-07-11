# Website-vs-App
Multivariate Linear Regression model

A New York City based e-commerce commpany sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want. The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

Using Multivariate Linear Regression to study the correlations between the different factors and how they affect the how much the customer spends. LMS(least mean square) algorithm is used along with Batch Gradient Descent algorithm.

The model considers the following features for constructing the hypothesis:

    Avg. Session Length
    Time on App
    Time on Website
    Length of Membership

The output(y) is the Yearly Amount Spent.

The model finds the coefficients corresponding to the above features. In the given case, the coeffcients of Time on App and Time on Website are compared. The feature having higher coeffcient value is the parameter which the company must focus on.
