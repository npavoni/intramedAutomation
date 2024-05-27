🏗️ Project Structure
The project is organized into the following key components:

pages: Screens organized as separate class files.
step_defs: Step definition files for each test
reports: Contains the reports that are generated after every execution.
📁 Folder Structure
.
├── reports                        # Reports files
│   └── reports.html               # Automated tests report on HTML format
│   └── report.xml                 # Automated tests report on XML format
├── tests                          # Automated tests
│   ├── step_defs                  # Step definition modules for each test case
│   └── conftest.py                # Shared configuration and functions for tests
├── pytest.ini                     # Command line options
└── README.md
Setup Process

1 - In order to install the project properly, make sure to install all the dependencies by running the following command in the terminal:

pip install -r requirements.txt 
EXECUTION

You can execute all the tests cases by running the following command :

pytest
If you want to execute one test case you can do it by executing the following command:

pytest test_name.py
