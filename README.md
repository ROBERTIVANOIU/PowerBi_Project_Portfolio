# PowerBi_Project_Portfolio
This project covers the end-to-end design and implementation of a dimensional data model (Star Schema architecture) for analytics and reporting.
It takes raw source tables, cleans and transforms the data, and structures it into an optimized data model complete with dimensions, facts, core business measures, and data security.


# Step-by-Step Workflow & Implementation Phases
# 1. Discovery, Data Cleaning & Conceptual Foundation:
Overview of the project goals and architecture design.
Inspecting the raw source tables to understand their structure, relationships, and data types, while cleaning out the data by handling nulls, removing duplicates, standardizing formats, and fixing inconsistencies before modeling.
Establishing the fundamental differences between Facts (quantitative business events/transactions) and Dimensions (descriptive context/master data).


# 2. Building the Dimension Tables:
Designing and populating the customer dimension table.
Building the product dimension table, organizing categories, subcategories.


# 3. Building the Fact Tables:
Constructing the core sales transactional fact table, linking it to the customer, product, and date dimensions, and ensuring clean, accurate metrics like revenue and quantity.
Capturing operational metrics related to delivery times, shipping, and order status.
Finalizing and integrating the remaining operational tables into the star schema framework.

# 4. Calculations, Enhancement & Security:
Creating a dedicated Calendar/Date table and establishing relationships for time-based analysis.
Writing and validating key business measures (DAX or SQL aggregation calculations) to power analytical reports.
Implementing security roles to restrict data access based on user permissions.
