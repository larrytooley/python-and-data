# Automating Regression at Caterpillar with StatsModels

## Description:

Caterpillar Reman Powertrain Indiana (Franklin, IN) needed to create regression models for more than 4000 parts in order to improve inventory performance. This session will demonstrate some of the code used to clean and organize data in preparation to create the regression models. Additionally, the differences between scikit-learn's and StatsModels' regression functionality will be compared and why I chose StatsModels. Finally, the session will provide a small primer in regression analysis and some use cases.

## Abstract:

Caterpillar's Franklin facility uses a hodgepodge of legacy software for planning of material and generating reporting. There are various issues with ERP automation of material planning. The facility leans heavily on the tool most know best, Excel. The task we will discuss in this presentation can be completely handled by Excel; however, it is slow and prone to keying errors.

Python has provided important time savings and functionality through pandas, StatsModels, and scikit-learn. Pandas is used to collect data together and clean the data prior to exporting back to Excel for use by planners and analysts. The regression model initially suggested is less than optimal. We will cover the weaknesses, as well as, what is being done to improve material planning going forward.

### Pandas functionality covered:
* read
* concat
* pivot
* head
* tail
* write

### StatsModels and scikit-learn"
* Regression output
