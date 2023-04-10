Phonepe_Pules_Project Link --http://localhost:8508/

Hi friends this is the app i created to analyse Phonepe pulse data which i get through Phonepe pulse github repo.Then I deployed this app in streamlit.

First lets extracts datas from the github and convert it into csv files.
This is the dataset i used in my streamlit web application to visualize datas.

After cloning files from github repo i created a for loop to loop through each folder and get datas from it and then append it to a dataframe to make it easy to covert to csv.

To insert datas into Mysql i used sqlalchemy(in order to establish connection you want pymysql also).

To see full code see in mysqlinsert.ipynb file Repeat the above process for all csv files to insert into your Mysql database.

Then after inserting all my files to Mysql database. I created a new file named main.py to create a app using streamlit.
