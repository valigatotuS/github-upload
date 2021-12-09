Title:  <Database Management: Project>
Author: <Valentin Quevy>
date:   <17/11/2021>

Summary:
    The purpose of this project is to learn developping simple 
    database driven web-sites using python [flask], html & css.

PS:
    In order to execute following project:
      a) Execute powershell in admin mode
      b) >Set-ExecutionPolicy RemoteSigned 
      c) cd to project...
      d) venv\scripts\activate

This folder "Project" contains:
    -src/:
      -my_app.py      -> api module
      -my_database.py -> database module
      -my_queries.py  -> queries module
      -main.py        -> functional code
      -test.py        -> test code
    -files/:
      -ER_diagram.png -> Entity Relational Diagram of database
      -db.db          -> sqlite3 database file
      -init_db.txt    -> queries for creating the tables of 'db.db'
      -rows/          -> folder containing csv-files with the table-rows 
    -templates/:
      -index.html     -> home-page
      -about.html     -> about-page
      -login.html     -> login-page 
    -venv/            -> virtual environment setup for the project 
    