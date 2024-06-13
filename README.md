# IBM Introduction to Relational Databases 

### Final Laboratory
<hr>

### Scenario
In this scenario, you have recently been hired as a Data Engineer by a <b>New York-based coffee shop chain</b> looking to expand nationally by opening several franchise locations. They want to streamline operations and revamp their data infrastructure as part of their expansion process.

Your job is to <b>design their relational database systems for improved operational efficiencies</b> and make it easier for their executives to make data-driven decisions.

Currently, their data resides in <b>several systems: accounting software, supplier databases, point of sales (POS) systems, and even spreadsheets</b>. You will review the data in all of these systems and design a central database to house all of the data. You will then create the database objects and load them with source data. Finally, you will create subsets of data your business partners require, export them, and load them into staging databases using several RDBMS.


### Data used in this project
In this project, you will be working with a subset of data from the [Coffee shop sample data](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/12/beanie-coffee-1113?utm_source=Exinfluencer&utm_content=000026UJ&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDB0110ENSkillsNetwork24601058-2021-01-01&utm_medium=Exinfluencer&utm_term=10006555).

You will use a modified version of the data for the project, so to succeed in the project, download the linked files when prompted in the instructions. You do not need to use any data from the source.

In your scenario, you will be working with data from the following sources:

- Staff information held in a spreadsheet at headquarters (HQ)
- Sales outlet information held in a spreadsheet at HQ
- Sales data output as a CSV file from the POS system in the sales outlets
- Customer data output as a CSV file from a custom customer relationship management system
- Product information maintained in a spreadsheet exported from your supplier's database


### Objectives
After completing this lab, you will be able to:

- Identify entities
- Identity attributes
- Create an entity relationship diagram (ERD) using the pgAdmin ERD tool
- Normalize tables
- Define keys and relationships
- Create database objects by generating and running the SQL script from the ERD tool
- Create a view and export the data
- Create a materialized view and export the data
- Import data into a MySQL database using phpMyAdmin GUI tool
- Import data into a MySQL database


### Task 1: Identify entities
The first step when designing a new database is to review any existing data and identify the entities for your new system.

The following image shows sample data from each source you will be working with to design your new central database. Review the image and identify the entities you plan to create.


Note: You can download a copy of this image or open it in another browser tab for reference later in the lab.
Make a list of the entities you have identified. Take a screenshot and save it as Task1.jpg or Task1.png.

  
