# My_Finery_NYCDSA_Fall_2018_Product
# Multi-Class Product Classifier

### STYLING AND WARDROBE MANAGEMENT APPLICATION
• Worked directly with the fashion industry start-up to improve their styling and wardrobe management application

• Extracted features from unstructured email receipt corpus by using Natural Language Processing

• Developed models using Supervised ML methods to accurately identify and classify women’s wardrobe products


#### Problem Formulation
My capstone project aimed to help a fashion industry startup to improve their customer wardrobe inventory Application. The App gathers the information about the customers’ wardrobe inventory from their emails and catalogs the products into 12 different product categories.

Identifying the women’s products and correctly classifying them into different categories is the big challenge. Through this project, I built machine learning models for the company to efficiently and accurately predict the product category. 

#### Data Exploration

Given a new email receipt with information such as brand Id, retailer data, item name, retailer Id, and category Id I want to assign the products on it into one of the 12 categories.

#### Output: Product Category

Tops – 110

Bottoms - 120

Dresses - 140

Jumpsuits - 130

Outerwear - 150

Activewear - 160

Beachwear- 170

Shoes - 200

Bags - 300

Accessories 400

Beauty 500

Miscellaneous 600

Kids 610

Mens 620

None 0

The information I am interested in such as ‘item name’, ‘brand name’ and ‘category Id’ exists in strings. This is a supervised machine learning text classification problem. Predicting the right category on the provided string will help this company best serve its clients.

To tackle this problem, I investigated which supervised methods are best suited to handle text data, multi-class classification and imbalanced classes.  Upon cleaning the data, engineering features, and balancing classes, I implemented Naive Bayes, Multinomial Logistic Regression, Support Vector Machine and Tree-based models.
