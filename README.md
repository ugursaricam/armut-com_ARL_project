<img src="https://cdn.armut.com/images/armut-header-logo-colour@2x.png" width="100%"/>

# Armut.com Recommendation System
This is a recommendation system developed for a dataset belonging to armut.com. The dataset contains information about the users, the services they received, and the categories of these services, along with the creation date of each service.

The recommendation system is developed using the apriori and association_rules algorithms from the mlxtend library. The goal of the recommendation system is to suggest relevant services to the users based on their previous service requests. The system first creates a basket for each user and month pair by grouping the services based on their categories. It then applies the apriori algorithm to find the frequent itemsets, and the association_rules algorithm to generate the association rules.

# Prerequisites
To run the recommendation system, you need to have Python 3 and the following libraries installed:

* **pandas**
* **mlxtend**

You can install the required libraries using the following command:

`$pip install pandas mlxtend`
