# Music Store Data Analysis

## Project Overview

This project focuses on relational database design and analysis using SQL to explore a real-world music store dataset. It demonstrates the practical application of SQL skills by constructing a normalized schema, importing large-scale data, and answering complex business queries relevant to a digital music store environment[attached_file:1].

## Objectives

- **Design** a normalized relational database schema for a music store with proper key constraints and relationships.
- **Import and validate** data from multiple CSV sources.
- **Write and optimize** SQL queries for data analysis, with a focus on business-oriented insights.
- **Demonstrate** advanced SQL concepts such as joins, aggregations, subqueries, and handling of real-world data challenges[attached_file:1].

## Tech Stack

- **SQL Database:** MySQL (compatible with other popular SQL engines)
- **Tools:** MySQL Workbench / DBeaver / command line
- **Languages:** SQL

## Database Schema

The schema includes ten tables: Genre, MediaType, Employee, Customer, Artist, Album, Track, Invoice, InvoiceLine, Playlist, and PlaylistTrack. All tables are interrelated through primary and foreign keys. The schema diagram included in the project folder illustrates these relationships clearly.

## Setup Instructions

1. **Create Database**  
   Create a new database named `music_store`.

2. **Create Tables**  
   Use the SQL DDL scripts provided in the `schema.sql` file to create required tables with appropriate constraints (including `AUTO_INCREMENT` and `CASCADE` on foreign keys)[attached_file:1].

3. **Import Data**  
   - Download CSV files from the provided dataset link.
   - Import each CSV file into its respective table, ensuring column names match.
   - Use bulk import features for large files like `Track`, `InvoiceLine`, and `PlaylistTrack`. Refer to supporting documentation for troubleshooting large imports[attached_file:1].
   
4. **Data Validation**  
   Confirm that data loads correctly and that relational integrity is maintained.

## Key Business Questions Answered

The project answers a variety of analytical and business intelligence questions using SQL queries, including but not limited to:

- Who is the senior most employee by job title?
- Which countries have the most invoices?
- What are the top 3 highest invoice totals?
- Which city generates the most revenue?
- Who is the best customer by total spending?
- Identify Rock music listeners and their details.
- Determine the top 10 artists (bands) in Rock genre by track count.
- List tracks longer than the average song length.
- Track customer spending by artist.
- Find the most popular genre per country.
- Find the top-spending customer for each country[attached_file:1].

## Challenges Faced

- Handling and importing large datasets securely and efficiently.
- Enforcing foreign key constraints and dealing with data consistency.
- Designing optimized queries for data aggregation and time-based analysis.


