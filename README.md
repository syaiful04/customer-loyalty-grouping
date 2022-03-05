# customer-loyalty-grouping
This project was carried out to gain insight from the data of a cafe with the aim of clustering which will later be used to grow the business of the cafe.

I finished this project with my friend and we disguise the real name of cafe become "Omah Cafe and Resto" for confidential things. These are the process to gain the insight based on (CRISP DM) cross-industry standard process for data mining.

# Business Understanding
Omah Cafe & Resto since 2015, which is located in Surabaya. Omah Cafe & Resto offers a traditional atmosphere with traditional to modern processed menus. We will innovate in the form of updating promo packages to increase sales and maintain an existence in loyal customers.

Purpose of the project: To classify customers into two categories, namely loyal customers and disloyal customers by using clustering. So that we can make product category packages that have high and low buying interest.

- Improve product category sales efficiency between low and high sales.
- Increase engagement rate for loyal customers without limiting customer choice of product discounts.

# Data Understanding
Using the Omah Café&Resto sales dataset, the data contains purchase history in each product category with 9854 rows and 26 columns. 
![image](https://user-images.githubusercontent.com/100661486/156867470-a87cf5fa-74bc-4b09-86f3-021aeb60691e.png)
![image](https://user-images.githubusercontent.com/100661486/156867484-b11539fb-12b4-4ee6-819a-f9cad3c89f7f.png)
![image](https://user-images.githubusercontent.com/100661486/156867492-fde06994-f8e4-4220-9fbf-73b4b21ea4d2.png)


# Data Preparation
The data used does not include all the columns in the dataset, some unused variables will be dropped. So the dataset used is to use product categories as columns and combine several of the same transaction ids.

# Modelling
The algorithm used for clustering is K-Preparatio Means. K-Means is used to find out the pattern of the dataset and create groups. There are 2 clusters formed to classify loyal and disloyal customers.
![image](https://user-images.githubusercontent.com/100661486/156867974-1e13f202-2ec5-4fcf-a7ca-736fe7a480fa.png)
![image](https://user-images.githubusercontent.com/100661486/156868031-fe6115ee-81e5-4cf6-abd8-e743ecc86adf.png)

# Evaluation and Deployment
The model has succeeded in achieving the initial goal of classifying customer loyalty. Recommendations for promo packages for loyal customers based on product sales in each category.
