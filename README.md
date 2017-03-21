#P4 Item Catalog project
=============

Required tools:

Python
PostgreSQL for Python
If the database is required on the Virtual Machine

Vagrant
Virtual Box


Instruction:

Clone the repository: https://github.com/commento/P4ItemCatalog.git

Access the Virtual Emulated Server with commands:
vagrant up
vagrant ssh

In the project folder Create the Database with the command:
python database_setup.py

Populate the database with the command:
python lotsofmenus.py

Execute the local host (port 5000) with the command:
python project.py

the project is almost entirely implemented in the main file:
- project.py

The other two python files are related to database creation/declaration and population using SQLAlchemy
- database_setup.py
- lotsofmenus.py

The folder templates contains all the htlm pages implemented also with jinja2 templates.
The folder static contains css styling and static images.

