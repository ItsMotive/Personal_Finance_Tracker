# Personal Finance Tracker

The Personal Finance Tracker is a Python application that allows users to track their income, expenses, and savings goals. It provides a user-friendly graphical interface (GUI) for data entry, stores data using PostgreSQL and PgAdmin, and generates visual reports using Matplotlib. The application helps users effectively manage their finances by offering tools for tracking income, expenses, savings progress, and budget adherence.

## Table of Contents
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installing](#installing)
    - [PostgreSQL Setup](#setting-up-postgresql-server)
- [GUI Interfaces](#gui-interfaces)
- [Running Tests](#running-the-tests)
- [Deployment](#deployment)
- [Built With](#built-with)
- [Versioning](#versioning)
- [Roadmap](#roadmap)
- [Author](#authors)
- [Acknowledgements](#acknowledgments)

## Getting Started

These instructions will guide you through the setup of the project and getting it up and running on your local machine for development and testing.

### Prerequisites

To set up this project, you will need the following:

```
- Python 3.x
- Tkinter (for the GUI)
- PostgreSQL and PgAdmin (for data storage)
- Matplotlib (for data visualization)
- Git and GitHub (or another version control system)
```

### Installing

A step-by-step guide to set up the development environment:
1. Install Python:
    - Download the latest version of Python form the official website.
    - Verify the installation by running the following command.
    ```css
    python --version
    ```

2. Install required libraries:

    Open terminal and install the necessary Python libraries:
    ```
    pip install tk matplotlib psycopg2-binary pandas prettytable 
    ```

3. Clone the repository:
    ```bash
    git clone https://github.com/ItsMotive/Personal-Finance_Tracker
    ```

4. Navigate to the project directory:
    ```bash
    cd your-project-directory
    ```

### Setting up PostgreSQL server
1. Install [PostgreSQL](https://www.postgresql.org/) and [PgAdmin](https://www.pgadmin.org/)
2. Open up [Credentials.py](/src/Credentials.py) and update credentials with your information
3. Run [main.py](/src/main.py) and click on "Setup PostgreSQL Database" button

## GUI Interfaces

Main GUI Tab:

<img src="assets/screenshots/main_window.PNG" alt="Main Window" width="400" height="250">

Main Income GUI Tab:

<img src="assets/screenshots/main_income_window.PNG" alt="Income Window" width="400" height="250">

Main Expense GUI Tab:

<img src="assets/screenshots/main_expense_window.PNG" alt="Expense Window" width="400" height="250">

Main Saving Goals GUI Tab:

<img src="assets/screenshots/main_savings_goal_window.PNG" alt="Savings Window" width="400" height="250">

Main Savings GUI Tab:

<img src="assets/screenshots/main_savings_window.PNG" alt="Savings Window" width="400" height="250">

Main Budget GUI Tab:

<img src="assets/screenshots/main_budget_window.PNG" alt="Report Window" width="400" height="250">

Example Report Selection GUI:

<img src="assets/screenshots/income_report_selection_window.PNG" alt="Report Selection Window" width="200" height="200">

Example Bar Graph GUI:

<img src="assets/screenshots/income_bar_graph_window.PNG" alt="Bar Graph" width="400" height="250">

Example Pie Graph GUI:

<img src="assets/screenshots/income_pie_graph_window.PNG" alt="Pie Graph" width="300" height="250">

Example Table GUI:

<img src="assets/screenshots/income_table_window.PNG" alt="Table GUI" width="400" height="250">

Example Input Form GUI:

<img src="assets/screenshots/income_entry_window.PNG" alt="Input Form" width="400" height="250">

Example Expense vs Income Graph: 

<img src="assets/screenshots/comparison_bar_graph_window.PNG" alt="Input Form" width="400" height="250">

Example CSV Editor: 

<img src="assets/screenshots/sample_csv_editor.PNG" alt="CSV Editor" width="400" height="250">

Sample CSV Importer: 

<img src="assets/screenshots/sample_csv_importer.PNG" alt="CSV Importer" width="400" height="250">

## Running the tests

**WIP**

### Break down into end to end tests

***WIP***

## Built With

* [Tkinter](https://docs.python.org/3/library/tkinter.html) - GUI Framework
* [PostgreSQL](https://www.postgresql.org/) - Database for storing financial data
* [PgAdmin](https://www.pgadmin.org/) - Visually see database
* [Matplotlib](https://matplotlib.org/) - Libraries for data visualization


## Versioning

I use Git for version control and GitHub for repository management. To view the history of changes or switch between versions, use Git commands like git log or explore the commits on this repository.

You can check out specific versions or releases by visiting the releases page on GitHub or by using Git tags and branches.

For example, to check out a specific version:
```php
git checkout <tag_name>
```

Or to view the latest changes:
```bash
git log
```

## Roadmap

This section outlines features and improvements that are currently being worked on or planned for future releases:

- **Upcoming Functionality Additions**:
    - **Savings Progress**: Users will be able to enter progress towards a specific savings goal
    - **Savings Goal Current Progress**: Users will be able to see current progress towards all goals
    - **Budgeting System**: Users will be able to set monthly budgets for different categories and receive alerts when exceeding them.
    - **Recurring Transactions**: Automatically log recurring income or expense transactions (e.g., rent, salary)
    - **Manual Data Entry**: Users will be able to add/modify entries manually through a text document
    - **Interest Calculator**: Users will be able to calculate future profits dependent on savings type (Compound, Simple, etc.)

- **Upcoming Improvements**: 
    - Restructuring the project for a more efficient and organized directory structure.
    - Addressing any redundancies in code and improving performance where necessary.
    - Fixing potential issues to ensure smooth user experience and functionality.
        - Closing main window does not close out opened graphs

## Authors

* **Austin** - *Initial work* - [ItsMotive](https://github.com/itsmotive)

## Acknowledgments

* Thanks to open-source libraries like Tinter and Matplotlib.
* Inspiration from financial tracking applications.
