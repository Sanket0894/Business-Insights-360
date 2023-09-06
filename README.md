## Business Insights 360
An imaginary company called AtliQ Hardware is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights from large amount of data. Also due to the lack of effective analytics the company faced a major loss in Latin America.
Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.
I have completed this project following the Codebasics [Power BI course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)
## Table content
* [Need of Business Intelligence](Need-of-Business-Intelligence)
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
- ### gdb041
 
  dim_customer

  dim_product

  dim_market

  fact_forecast_monthly

  fact_sales_monthly

- ### gdb056
 
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
##### Home View
This view will help the end user to navigate through various views by clicking on the perticular buttons like 

<img width="670" alt="Home" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/f7bd30b9-ee1e-4ae1-8b4a-4cf0c66d4233">

- [Info](Info)
- [Finance view](Finance-View)
- [Sales view](Sales-View)
- [Market view](Market-View)
- [Supply chain view](Supply-Chain-View)
- [Executive View](Executive-View)
- [Support](Support)

## Info 

<img width="650" alt="Info" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/fed7840d-a6bd-4ab9-b2a5-b0f1d7dcf224">

## Finance View 

<img width="671" alt="FInance" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/eac3e9d1-8e11-4eff-8dca-c4d011ca3db4">

## Sales View 

<img width="674" alt="Sales" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/fa882a65-062d-4377-93b1-083ae77251fe">

## Market View

<img width="671" alt="Market" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/5efed690-2c8f-49fe-a249-7283dbd5a08e">

## Suppply Chain View 

<img width="669" alt="SCM" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/1ab22a4e-da40-4d8f-8054-487900be33e5">

## Executive View 

<img width="675" alt="Executive" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/829b5806-3781-4f54-bae1-c74b82407aad">

## Support 

<img width="669" alt="support" src="https://github.com/Sanket0894/Business-Insights-360/assets/131572641/8d99c97d-13e5-4635-9d78-c79142c28ca2">



For interactive report you can check out here: [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjI4MDc1NzMtZTQ4Ny00NWJkLTlkNmYtM2E5ZGEyYTI2NjM3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Outcome
This dashboard will provide the insights to the decision makers of AtliQ Hardware to take the necessary decision on the on going problem in the latin American region.


