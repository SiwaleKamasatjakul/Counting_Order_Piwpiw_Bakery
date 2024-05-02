# Counting_Order_Piwpiw_Bakery

Challenge
At Piwpiw Bakery, they offer a special product called "รักหนูมั๊ยย 3 กระปุก" for 100 baht. With this offer, customers can select three items from our menu of delightful treats. However, to ensure smooth processing, we kindly request customers to note their choices in the Buyer Message section during checkout, which makes it challenging for them to count orders accurately.

Business Goal
1. Utilize machine learning to accurately count each order, aiming to achieve correctness of over 80%.

Technologies Used: 
1. Python
2. Natural Language Processing (NLP) techniques

My Contributions:
- Preprocessed and cleaned the raw text data, including tokenization and vectorization.
- Developed and trained a machine learning model.
- Improved model performance.
- Automated categorizing and counting orders based on text data provided in both the "Buyer Message" and "Seller Note" columns. This process utilizes machine learning techniques, including TF-IDF vectorization and a pre-trained model, to predict the category for each word in the text data. The predicted categories are then used to determine the count of each category. Additionally, the code includes a condition to handle special cases and assigns values to the 'random' column accordingly. The resulting DataFrame contains the original data along with the predicted categories and counts.

Result

Achieved an accuracy rate of 86% in the logistic regression model during training.
Achieved 99% accuracy when utilizing this model for order counting. The dataset comprises orders checked out by customers on May 1st, 2024.
