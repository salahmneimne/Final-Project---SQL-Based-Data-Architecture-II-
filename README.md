# Final-Project - Renewable Energy Farms – SQL Database Design & Analytics

## Overview
This project implements a normalized relational database to model renewable energy farms, energy generation, customers, and billing across multiple countries.  
It supports **operational analytics**, **commercial billing**, and **sustainability (CO₂ avoidance) analysis**.


## Scope & Features
- Multi-country renewable energy portfolio
- Technologies: Solar, Wind, Hydro, Biomass, Geothermal
- Energy generation tracking (annual & monthly)
- Consolidated customer billing (multi-plant invoices)
- CO₂ emissions avoidance calculations
- Fully normalized schema (3NF)


## Data Model
The database contains **9 entities**:
Country, EnergyType, Plant, Plant_Address, GenerationRecord, Customer, Invoice, Invoice_Line, Invoice_Line_Detail.

- Proper handling of **many-to-many relationships**
- Referential integrity via foreign keys
- Junction table used for portfolio billing
- Climate attributes included for performance analysis

ERD provided in the MySQL Workbench (.mwb) file.

## Technologies
- SQL (MySQL-compatible)
- MySQL Workbench (ERD)
- Relational data modeling
- Analytical SQL (JOINs, GROUP BY, window functions)

## Analytical Queries
- Top locations per energy type
- Energy mix percentage by technology
- Maintenance efficiency analysis
- Last-year energy generation overview
- Energy sold & CO₂ avoided by customer sector and energy family

## Key Learning Outcomes
- Translating business rules into a normalized database
- Designing scalable billing models using junction tables
- Writing real-world analytical SQL
- Modeling sustainability metrics without redundancy


## Notes
- All data is synthetic and created for academic purposes
- The model is extensible to real-world energy and billing systems

## Files:
<img width="996" height="854" alt="Renewable Energy Farms Database ERD" src="https://github.com/user-attachments/assets/ff66835b-265b-4be6-acac-7ad26d5716ea" />

SQL Group Assignment - Renewable Energy Farms.docx (https://github.com/user-attachments/files/24315686/Team.2.-.SQL.Group.Assignment.-.Renewable.Energy.Farms.docx)




