# Library Circulation Analytics Project

## Project Overview
This project builds a Library Circulation Analytics system using SQLite Online. It includes designing the database schema, importing sample datasets, writing detailed SQL analytics queries and views, performing data quality checks, and analyzing query performance improvements via indexing.

## ERD Diagram
The Entity-Relationship Diagram (ERD) visualizing the database schema can be found here:  
[https://dbdiagram.io/d/Library-Circulation-Analytics-ERD-69042daa6735e11170987031](https://dbdiagram.io/d/Library-Circulation-Analytics-ERD-69042daa6735e11170987031)

## How to Run Scripts in SQLite Online

1. **Set up the database schema**  
Open `library_schema.sql` using SQLite Online and run the entire script to create necessary tables with all constraints.

2. **Import sample data**  
Use the Import feature of SQLite Online to upload all CSV data files located in the `CSVs` folder to the corresponding tables.

3. **Run analytical queries**  
Load and execute `reports.sql` to generate all required library circulation analytics reports as specified.

4. **Create views**  
Run the SQL commands in `views.sql` to build useful database views for patron activity, branch performance, and catalog status.

5. **Validate data quality**  
Run `dq_checks.sql` to perform key data quality checks across your tables ensuring integrity and consistency.

6. **Analyze and optimize performance**  
Use `performance.md` for detailed instructions on querying the database execution plans before and after adding indexes, which are designed to optimize query speed.

## Screenshots Included
- **CSV Import**: Confirmation showing successfully imported tables and data in SQLite Online.  
- **Data Quality Checks**: Results proving absence of nulls, duplicates, invalid entries, and other integrity violations.  
- **Performance Analysis**: EXPLAIN QUERY PLAN outputs before and after indexing illustrating query optimization.  
- **Report Outputs**: Sample results of your core library analytics queries and views.

## Contact Information
Om Patel
Patelom120704@gmail.com

---

*Thank you for reviewing this submission for the Library Circulation Analytics project.*
