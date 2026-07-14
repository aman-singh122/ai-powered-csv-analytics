=============================================================
AI POWERED CSV ANALYTICS ENGINE
Software Engineering Internship Project
Organization: Clinicea
Prepared By: Aman
=============================================================

1. PROJECT OVERVIEW
-------------------------------------------------------------

This project was developed during my Software Engineering Internship at Clinicea.

The objective of the project was to build an AI-powered analytics engine capable of answering natural language questions over structured healthcare datasets.

Instead of manually writing SQL queries, users can ask questions in plain English, such as:

• Show top doctors by revenue
• Revenue by city
• Appointments by weekday
• Total completed appointments
• Monthly revenue trend

The system automatically converts these natural language questions into SQL using Google's Gemini AI, executes the query on healthcare datasets, and returns analytical results along with graphs and AI-generated explanations.

Initially, the analytics engine was implemented using CSV files and temporary SQLite databases.

During the internship, I studied the complete architecture, identified its limitations, researched modern analytical technologies, and designed an optimized architecture using DuckDB and Parquet.

The project also includes a CSV upload pipeline that automatically converts uploaded CSV datasets into Parquet files using DuckDB, making them ready for high-performance analytics.

-------------------------------------------------------------
2. MAJOR WORK COMPLETED DURING INTERNSHIP
-------------------------------------------------------------

During the internship I worked on the following tasks:

• Studied the complete analytics architecture.

• Understood the frontend-to-backend request lifecycle.

• Analyzed the existing CSV analytics engine.

• Documented the complete architecture.

• Implemented and analyzed AI-powered SQL generation using Gemini.

• Studied dataset routing and dynamic schema detection.

• Worked on SQLite-based analytics execution.

• Designed an optimized DuckDB + Parquet analytics architecture.

• Implemented CSV upload and automatic CSV → Parquet conversion.

• Studied ETL concepts for large healthcare datasets.

• Compared CSV, SQLite, DuckDB, Parquet, and Vector Database approaches.

• Designed scalable analytics workflows.

• Prepared architecture diagrams and technical documentation.

-------------------------------------------------------------
3. PROJECT FEATURES
-------------------------------------------------------------

• Natural Language Analytics

• AI-generated SQL Queries

• Dynamic Dataset Selection

• CSV Upload

• Automatic CSV → Parquet Conversion

• DuckDB Analytical Query Engine

• Dynamic Schema Detection

• Automatic Graph Generation

• AI-generated Insights

• REST APIs

• Modular Backend Architecture

-------------------------------------------------------------
4. TECHNOLOGY STACK
-------------------------------------------------------------

Frontend

• HTML
• CSS
• JavaScript

Backend

• Node.js
• Express.js

Artificial Intelligence

• Google Gemini API

Databases

• SQLite
• DuckDB

Storage

• CSV
• Parquet

Libraries

• Multer
• PapaParse
• csv-parser
• parquetjs-lite
• ExcelJS
• HighCharts
• Chart.js
• PDFKit
• Tesseract OCR
• PDF Parse

-------------------------------------------------------------
5. PROJECT STRUCTURE
-------------------------------------------------------------

Source_Code/
│
├── frontend
│
├── backend
│
├── controllers
│
├── routes
│
├── services
│
├── utils
│
├── package.json
│
└── ...

-------------------------------------------------------------
6. DOCUMENTATION
-------------------------------------------------------------

The Documentation folder contains:

• Complete Technical Documentation (DOCX)

• PDF Version

• Notes

The documentation explains:

• Existing Architecture

• Request Flow

• Backend Workflow

• AI SQL Generation

• CSV Processing

• DuckDB Architecture

• ETL Pipeline

• CSV vs Parquet

• Performance Analysis

• Proposed Architecture

-------------------------------------------------------------
7. RESEARCH IMAGES
-------------------------------------------------------------

The Research_Images folder contains all diagrams created during the internship, including:

• Existing Architecture

• Optimized Architecture

• CSV vs Parquet

• DuckDB Internal Working

• ETL Pipeline

• Upload Workflow

• Analytics Flow

• Query Execution

-------------------------------------------------------------
8. HOW TO RUN THE PROJECT
-------------------------------------------------------------

Prerequisites

• Node.js (v18 or later recommended)
• npm
• Google Gemini API Key

-------------------------------------------------------------
Step 1

Open terminal.

-------------------------------------------------------------
Step 2

Navigate to the project folder.

Example

cd Source_Code

-------------------------------------------------------------
Step 3

Install all dependencies.

Command

npm install

-------------------------------------------------------------
Step 4

Create a .env file in the project root.

Example

GEMINI_API_KEY=YOUR_API_KEY

(Add any other environment variables required by the project.)

-------------------------------------------------------------
Step 5

Start the backend server.

Development Mode

npm run dev

Production Mode

npm start

-------------------------------------------------------------
Step 6

Open the application in your browser (if applicable) and begin interacting with the analytics engine.

-------------------------------------------------------------
9. MAIN DEPENDENCIES
-------------------------------------------------------------

The project uses the following major packages:

• express
• duckdb
• sqlite
• sqlite3
• multer
• @google/genai
• csv-parser
• papaparse
• parquetjs-lite
• exceljs
• chartjs-node-canvas
• highcharts
• pdfkit
• pdf-parse
• pdf2pic
• tesseract.js
• crypto-js
• dotenv
• cors

Install all dependencies using:

npm install

-------------------------------------------------------------
10. LEARNING OUTCOMES
-------------------------------------------------------------

Through this project I gained practical experience in:

• Backend Development

• REST APIs

• Artificial Intelligence

• Prompt Engineering

• DuckDB

• SQLite

• Parquet

• ETL Pipeline

• Healthcare Analytics

• SQL Query Generation

• Enterprise Software Architecture

• Performance Optimization

• System Design

-------------------------------------------------------------
11. FUTURE IMPROVEMENTS
-------------------------------------------------------------

Possible future enhancements include:

• AWS S3 integration

• Incremental ETL

• Streaming Analytics

• Query Caching

• Metadata Catalog

• Dashboard Integration

• Distributed Analytics

• Multi-user Dataset Isolation

-------------------------------------------------------------
END OF README
=============================================================