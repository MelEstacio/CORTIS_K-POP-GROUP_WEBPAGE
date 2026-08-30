CORTIS — Fanbase & Artist Platform

A software engineering project designed to explore the development of a digital platform that connects fans, artists, content, events, and commerce within a single ecosystem.

CORTIS began as a web development project inspired by the digital presence of K-pop groups and evolved into a broader software engineering project focused on system design, relational databases, backend development, and data organization.

The project is currently being redesigned around a structured PostgreSQL database and a set of business rules intended to represent a realistic fanbase platform.

🎯 Project Purpose

The goal of CORTIS is to model and eventually implement a platform where fans can interact with artists and their content while accessing features such as:

Artist and group information
Fan accounts
Events and tickets
Products and orders
Loyalty and reward levels
Promotional campaigns
Artist-related releases and activities

Rather than focusing only on the visual interface, the project is being developed with particular attention to how information is structured, related, validated, and processed within the system.

🏗️ System & Database Design

The current development phase focuses on the relational database architecture using PostgreSQL.

The database is being designed through the progression of:

Conceptual Model → Logical Model → Physical Model

The schema incorporates concepts such as:

Primary and foreign keys
Supertype/subtype modeling
Relationship and cardinality analysis
Database normalization
Named constraints
NOT NULL and CHECK constraints
Identity columns
Business rules and data integrity
Many-to-many relationships through associative tables

The model currently includes entities related to:

Artists
├── Groups
└── Members

Debuts

Fans
└── Loyalty Levels

Products

Orders
└── Order Items

Events
└── Tickets

Promotions

The database structure is continuously refined as new business requirements and edge cases are identified.

📊 Data & Python

As the project develops, Python will be incorporated into the system to explore data manipulation and analysis based on the information stored in the relational database.

Planned applications include:

Extracting data from PostgreSQL
Data manipulation and transformation
Exploratory data analysis
Generating insights from fan and commerce data
Working with structured datasets

This stage will connect the database engineering side of the project with my current studies in Data Analysis and Python.

💻 Technologies
Current
PostgreSQL
SQL
Python — data analysis development
Excel
Draw.io — database modeling
Previous / Original Implementation
HTML5
CSS3
JavaScript
PHP

The original project began as a web-focused implementation and is currently being restructured as a broader software engineering project.

🚧 Project Status

In active development.

The database architecture is currently being implemented and refined in PostgreSQL. Application-layer development and Python-based data analysis will be incorporated as the project progresses.

This project is being developed as part of my Computer Science studies and serves as a practical environment for applying concepts in software engineering, databases, programming, and data analysis.
