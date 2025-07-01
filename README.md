# 🧠 MySQL for Beginners: Creating a Database and Importing Data

This guide was created as a **technical instruction manual** for beginners learning **MySQL**. It walks users through the process of designing a database, creating tables, defining relationships, and importing data using Excel files. The instructions are tailored for those with little to no prior experience working with relational databases.

## 📚 Project Background

As an Information Science major at the University of Maryland, I developed this set of instructions during the Spring 2023 semester to demonstrate how to:

- Design a relational database using an Entity-Relationship Diagram (ERD)
- Build the schema in MySQL Workbench
- Import data from Excel files into structured tables
- Understand and apply one-to-many relationships

The example used throughout the guide is a **Car Models** database, which includes tables for `models`, `brands`, and `countries`.

## 🛠️ Tools & Materials

- ✅ MySQL Workbench
- ✅ Microsoft Excel
- ✅ Working Computer
- ✅ Source data files (models, brands, countries)

## 🚀 Key Features

- Step-by-step guide with visuals for:
  - Creating a new database and ERD
  - Building normalized tables with appropriate constraints
  - Establishing one-to-many relationships
  - Forward engineering the database schema
  - Importing data via the **Table Data Import Wizard**

## 🧱 Database Structure

The example schema includes:

- **models** — car model name, specs, and brand ID
- **brands** — brand name, associated country ID
- **countries** — country name and region

Relationships:
- One brand can have many models
- One country can have many brands

## 🔁 Sample Workflow

1. Open MySQL Workbench
2. Create a new model and rename it `carmodels`
3. Create tables: `models`, `brands`, `countries`
4. Define columns using Excel headers
5. Set `AI` (Auto Increment) for ID columns, `NN` (Not Null) for all
6. Add 1:n relationships (models → brands → countries)
7. Forward engineer the model to generate the schema
8. Use the **Import Wizard** to load data from Excel files into the tables

