# Mastering_DS_ML
This repository is to master data science and machine learning algorithms. I will be reading some books and making the programming exercises with useful comments:
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems
- Learning SQL: Generate, Manipulate, and Retrieve Data
- Data Science from scratch
- Practical Statistics for Data Scientist

# MySQL
Inside the container the sakila database must be created.
1. Getting inside MySQL:

    - mysql -u root --host localhost --port 3306 

2. After downloaded the required files and being exposed to the image, in my case, the path to the files inside the cointener is this:

    - SOURCE /var/lib/mysql/mysql/sakila-db/sakila-schema.sql;

    - SOURCE /var/lib/mysql/mysql/sakila-db/sakila-data.sql;
