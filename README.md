## Business Insights 360
An imaginary company called AtliQ Hardware is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights from large amount of data. Also due to the lack of effective analytics the company faced a major loss in Latin America.
Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.
I have completed this project following the Codebasics Power BI course 
## Table content
* [Need of Business Intelligence](#Need-of-Business-Intelligence)
* [Data preview](Data-Preview)
* [Data Extraction](Data-Extraction)
* [Data Transformation](Data-Transformation)
* [Data Modeling](Data-Modeling)
* [Dashboard Design](Dashboard-Design)

## Need of Business Intelligence
AltiQ Hardware is a rapidly growing global company specializing in computer hardware and accessories. The business operates through three main channels:
- Retailers: Partnerships with major retailers like Croma and Amazon.
- Direct: Online sales through our e-store and AltiQ executive.
- Distributors: Collaborations with distributors such as Neptune in China.
Recently, AltiQ Hardware faced unexpected losses due to the expansion into the American market. These decisions were made based on surveys, intuition, and limited Excel analysis. In contrast, the competitors have dedicated analytics teams driving data-driven decisions.
To thrive in the industry, The decision makers recognize the need to establish the analytics team. This team will empower AtilQ with data-driven insights and informed decision-making capabilities, ensuring them continued success.

## Data Preview
The company has manage to collect two database as gdb041 and gdb056 which provide the necessary data about the past history of transactions and the tables.As follows:
- gdb041
dim_customer
dim_product
dim_market
fact_forecast_monthly
fact_sales_monthly

- gdb056 
freight_cost
manufacturing_cost
post_invoice_deductions
pre_invoice_deductions

## Data Extraction
As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

## Data Transformation
After extracting dataset we have do some preprossing and transformation to avoid the biasness towards results. In this project data transaction like removing duplicates, changing data types, grouping tables according to fact and dimensions etc operations done on the dataset.

## Data Modeling
- Data modeling is a very crucial step for preparing reports.
- Here is an example of the data model we have established in this project.
- In the beginning, the model schema was a star schema, but as flat files such as market share or operational cost were added, the schema evolved into a snowflake schema.

<img width="856" alt="Data model" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/0b18d69b-6840-483e-aaca-393b267774ca">

## Dashboard Design
Based on the initial mock up given the dashboard design finallized as follows:
