# SSIS_ETL_Project_PowerLifting
## Designing an ETL (Extract, Transform, Load) Process Using SQL Server Integration Services

**********************************************

## SSIS Project: Control Flow and Data Flow Tasks (copies windows) with a description of the applied transformations.
**********************************************
### Dataset: 

This dataset is a snapshot of the OpenPowerlifting database as of April 2019. OpenPowerlifting is creating a public-domain archive of powerlifting history. Powerlifting is a sport in which competitors compete to lift the most weight for their class in three separate barbell lifts: the Squat, Bench, and Deadlift.
The dataset was taken from [kaggle.](#https://www.kaggle.com/datasets/open-powerlifting/powerlifting-database)

**********************************************

### Control flow: SQL execution task:

![Текст с описанием картинки](/pictures/etl1.png)
**********************************************

### Data flow of dimensions Meets, Date:
![Текст с описанием картинки](/pictures/et2.png)

**********************************************
### Data transformation in Meets, Date data flow:

![Текст с описанием картинки](/pictures/etl3.png)

**********************************************

### Derived column for Date  data flow Date, Meets:

![Текст с описанием картинки](/pictures/etl4.png)

**********************************************

### Lookup query for Date dimension to get primary keys:

![Текст с описанием картинки](/pictures/etl5.png)
**********************************************

### Data sorting:
![Текст с описанием картинки](/pictures/etl6.png)

