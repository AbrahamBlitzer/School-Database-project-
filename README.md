Dav6100 project

This project implements a relational database for a school system in PostgreSQL, following a standard schema covering departments, students, instructors, courses, prerequisites, advising relationships, classrooms, sections, time slots, teaching assignments and enrollment records. The notebook creates the database, defines each table with appropriate primary keys, foreign keys, not-null constraints, and uniqueness constraints, loads data from source files and uses queries to solve questions about the database.

Requirements

A working PostgreSQL installation, a conda environment running Python 3.12, and Jupyter Lab installed in that environment are needed before starting.

Setup

Before running the notebook, edit start_env.sh with your local configuration and run it to start the PostgreSQL server. Then create and activate a conda environment with Python 3.12 and install Jupyter Lab into it. Place all required data files in a data directory located alongside the notebook; the notebook checks for this folder on startup and will raise an error if it's missing.
