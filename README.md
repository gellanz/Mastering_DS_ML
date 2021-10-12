# Mastering_DS_ML
This repository is to master data science and machine learning algorithms. I will be reading some books and making the programming exercises with useful comments:
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems
- Learning SQL: Generate, Manipulate, and Retrieve Data
- Data Science from scratch
- Practical Statistics for Data Scientist

# MySQL
Inside the container the sakila database must be created.
1. Getting inside MySQL:

    - mysql -u root -ppass --host localhost --port 3306

2. After downloading the required files and being exposed to the image, in the case of this repo, the path to the files inside the cointener is "/databases/, execute the following commands:

    - SOURCE /databases/sakila-schema.sql;

    - SOURCE /databases/sakila-data.sql;

3. Connecting to the sakila database in the other container using the network of docker compose.