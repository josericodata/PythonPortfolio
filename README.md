# Classic Models In Python

## Background
**Goal:** I will be using Python to recreate some queries that imaginary stakeholders may request. Here we will learn how to connect a DB to Python and explore a few of the innumerable possibilities of this language.

## Technology
For this set of examples, I am using Jupyter Notebook from Anaconda Distribution.

## Dataset
We will be using the dataset loaded into MySQL.

## Scenarios

### Scenario 1:
First, we must try the connection between Python and MySQL. For that, we need four libraries: `pandas`, `getpass`, `pymysql`, and `sqlalchemy`. I faced an issue with `mysql` being missing from the Anaconda distribution; please see this [link](https://stackoverflow.com/questions/64414751/conda-mysql-package-not-recognized-in-any-python-interpreter) that solved the problem.
![A picture containing icon
Description automatically generated](assets/img/1.png)
Fig. 1. 

### Scenario 2:
Imagine now that we want to print an Excel file for each of the tables:
![A picture containing icon
Description automatically generated](assets/img/2.png)
Fig. 2. 
Now you have each table extracted into an Excel file.
![A picture containing icon
Description automatically generated](assets/img/result1.png)
Fig. 3. 
### Scenario 3:
Add columns from an Excel file to a data frame pulled from SQL. We will be adding office city and phone to employee info. For that, we use a sort of "Vlookup" function that uses a unique identifier `officeCode` to bring the new columns in.
![A picture containing icon
Description automatically generated](assets/img/3.png)
Fig. 4. 

### Scenario 4:
A Data Analyst spends most of their time cleaning datasets; dropping duplicates is a good example of it. As a data frame, I will be using the Excel file containing all employees. I purposely triplicated the number of employees from 23 to 69; now we are going to see how to reverse to 23 unique employees.
![A picture containing icon
Description automatically generated](assets/img/4.png)
Fig. 5. 

### Scenario 5:
Mary, our General Sales Manager, wants to know the count of orders excluding the two biggest accounts. Customers 124 and 141 have placed 17 and 26 orders, respectively. The figure for Mary should be 283.
![A picture containing icon
Description automatically generated](assets/img/5.png)
Fig. 6. 
### Scenario 6:
Now, from the package `Pandas`, we are going to use a vertical bar plot. Data shown is taken from MySQL scenario 1. We will get an ordered visual by table based on row count.
![A picture containing icon
Description automatically generated](assets/img/6.png)
Fig. 7. 
### Scenario 7:
Another great library for visualizations is `matplotlib`. Now we want to create a plot for customers that exceed revenue of 130K.
![A picture containing icon
Description automatically generated](assets/img/7.png)
Fig. 8. 
### Scenario 8:
For this case, we want to create a pie chart displaying each of the products by percentage of revenue.
![A picture containing icon
Description automatically generated](assets/img/8.png)
Fig. 9. 

### Scenario 9:
Use a scatter chart representing sales reps by revenue.
![A picture containing icon
Description automatically generated](assets/img/9.png)
Fig. 10. 

### Scenario 10:
To wrap up the case scenarios, we are going to see the `geopandas` library, demonstrating that in Python you can manipulate maps. My colleague Oshimi is asking if we can turn Japan green because his grandmother used to exhibit an old picture of a green Japan. Apparently, he truly believes this action can ramp up sales revenue in Asia. Meanwhile, we will work this out for Oshimi.
![A picture containing icon
Description automatically generated](assets/img/10.png)
Fig. 11. 


## Notes
This is just a tiny bit of what you can do in Python. In case you are interested in replicating some of the scenarios, please find all Jupyter notebooks: [Jupyter_Notebooks](assets/scripts).

## License
Copyright (c) 2024 josericodata. This project is made available under the MIT License - see the [LICENSE](LICENSE) file for more details.
