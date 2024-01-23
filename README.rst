Dependencies:
============
- Python 3.8
- Django 3.2 
- dbsqlite
- postgresql 
- psycopg2-binary 2.9.6
- promise 2.3
- PyJwt 2.8.0
- graphql-core 2.3.2 
- pyjnius 1.5.0
- pyinstaller 5.13.0
- pillow 10.0.0
- requests 2.31.0

Build System:
============
- Build System:  
  - setuptools
  - pip

Package Management:
==================
- pip

Document Generation:
===================
- Sphinx

Testing Framework:
=================
- Pytest
- UnitTest

Continuous Integration(CI):
==========================
- Not Used 

Code Coverage:
=============
- coverage.py

Code Analysis and Linting:
=========================
- PEP-8

Versioning:
==========
- Semantic Versioning
  - format: Major.Minor.Patch
  - Example: 11.1.2

Branching Strategy:
==================
- Develop Branch
- Feature Branch 

Contributing Guidelines:
=======================
Contributing guidelines are crucial for creating a collaborative and efficient
development environment. They help contributors understand how to contribute 
to a project, maintain consistency, and facilitate a smooth review and 
integration process. Below are guidelines for contributors, including steps on
how to fork, branch, and submit pull requests:

Forking the Repository:
-----------------------
1. Fork the Repository:
    - Click on the "Fork" button on the GitHub repository to create a copy of the 
      repository under your GitHub account.

2. Clone the Forked Repository:
    - Clone the forked repository to your local machine using the following command:
      git clone https://github.com/your-username/repository.git

Creating a Feature Branch:
--------------------------
1. Create Branch
    - Create a new branch for your contribution. Use a clear and descriptive branch name 
      related to the feature or bug you are addressing:
      git checkout -b feature/new-feature

Making Changes:
---------------
1. Make Changes:
    - Implement the necessary changes or additions.
    - Follow coding conventions, style guidelines, and any project-specific rules.

Committing Changes:
------------------
1. Commit Changes:
    - Commit your changes with a clear and concise commit message:
      git commit -m "Add Ticket Number Add feature: description of the feature"

Keeping Your Fork Updated:
-------------------------
1. Sync with the Upstream Repository:  
    - To keep your fork up to date with the original repository, add the upstream 
      repository:
      git remote add upstream https://github.com/original-owner/repository.git

    - Fetch changes from the upstream repository and merge them into your local branch:
      git fetch upstream
      git merge upstream/main

Submitting a Pull Request:
-------------------------
1. Push Changes:
    - Push your changes to your fork on GitHub:
      git push origin feature/new-feature

2. Create a Pull Request:
    - Go to your fork on GitHub and create a new pull request.
    - Provide a clear title and description for your pull request, explaining the purpose of the changes.

3. Follow Code Review:
    - Be responsive to feedback and be prepared to make additional changes if required.
    - Address comments and update your pull request branch as needed.

4. Squash Commits (if requested):
    - If the maintainers request a single, clean commit, squash your commits into one before merging.

Review and Merge:
----------------
1. Code Review:
    - The project maintainers will review your pull request.
    - Address any additional feedback and make changes if necessary.
2. Merge:
    - Once your pull request is approved, it will be merged into the main branch.

Code Review Process:
===================


Testing Instructions:
====================
1. Install Dependencies:
    - Make sure you have Python installed on your system.
    - Install project dependencies by running:
      pip install -r requirements.txt

Run Unit Tests:
---------------
1. Navigate to the Project Directory:
    Open a terminal and navigate to the root directory of the project:
    cd path/to/project

2. Run Tests:
    - Run all unit tests using the following command:
      pytest
    - To run tests for specific modules or directories:
      pytest path/to/tests
    - Additional pytest options, such as -k for selecting specific tests, can be used as needed.

Code Organization:
==================
.. image:: _static/code.png
   :alt: Code Organization

- restro_table: Django application for restaurant table
- static: Foder used by django to store static files.
- stock: Django application to maintain stock.
- supplier: Django application for supplier
- tax_service: Django application for tax and service charges
- terminal: Django application for terminal
- user: Django application for user
- utils: Normal folder to store utility functions, classes, e.t.c
- venv: This is also virtual environment. This is used during the time of development
- .editor_config: This file is responsible to maintain code like spaces and table across multiple editor.
- .env: This file is used to store secret data
- .gitignore: This file is used by git to ignore files and folder
- conf.py, index.rst, make.bat, Makefile: This file is automatically generated by sphinx. Welcome — Sphinx documentation (sphinx-doc.org)
- manage.py: This file is generated by django
- qodana.yaml: This file is generated by qodana, maintained by pycharmQodana Cloud
- README.rst: This file contains basic info about project
- requirments.txt: This file contains packages used inside this project
- runserver.py: This is custom version or manage.py file used for buding this project using pyinstaller to generate exe.
- runserver.spec: This file is automatically generated by pyinstallerPyInstaller Manual — PyInstaller 6.2.0 documentation

IDE configuration:
=================
- Not Specific

Developement Workflow:
======================

Acknowledgments:
================
.. include:: acknowledgement.rst