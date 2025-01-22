# Laboratory Dashboard Application

This application is designed to handle data processing, visualization, and web application functionalities using various libraries such as Pandas, Plotly, Dash, SQLAlchemy, and more.

## Features

1. **Data Handling and Processing**:
   - Utilizes Pandas for data manipulation and analysis.
   - Supports various data formats including Excel files.

2. **Visualization**:
   - Employs Plotly for creating interactive visualizations.
   - Generates Gantt charts, timelines, and other graphical representations.

3. **Web Application**:
   - Built using Dash framework for creating web applications.
   - Incorporates Bootstrap for responsive design and layout.

4. **Database Interaction**:
   - Connects to databases using SQLAlchemy, pyodbc, psycopg2, and sqlite3.
   - Supports CRUD operations and event listening for SQL queries.

5. **File Handling**:
   - Manages file operations including reading, writing, and logging.
   - Handles Excel files using openpyxl.

6. **Error Handling**:
   - Implements robust error handling mechanisms using try-except blocks.
   - Logs errors and exceptions for debugging purposes.

## Libraries Used

- pandas
- numpy
- datetime
- plotly
- dash
- pyodbc
- psycopg2
- sqlite3
- sqlalchemy
- openpyxl
- re
- logging

## HTML Template

The application uses a custom HTML template for rendering the web pages. The template includes Bootstrap CSS and JavaScript for styling and interactivity.

## Application Structure

The application is structured into various sections including:

1. **Introduction**: The Laboratory Dashboard Application is designed to handle data processing, visualization, and web application functionalities. It leverages various libraries such as Pandas, Plotly, Dash, and SQLAlchemy to create an interactive and user-friendly interface for managing laboratory data, generating reports, and visualizing data through charts and tables.
2. **How It Works**: The application is built using the Dash framework, which allows for the creation of web applications with interactive components. The core functionalities include:

* Data Handling: Using Pandas for data manipulation and analysis.
* Visualization: Employing Plotly to create interactive charts and graphs.
* Web Application: Utilizing Dash to build the web interface, incorporating Bootstrap for responsive design.
* Database Interaction: Connecting to databases using SQLAlchemy and other database libraries to perform CRUD operations.
* File Handling: Managing file operations, including reading and writing Excel files.
* Error Handling: Implementing robust error handling mechanisms to ensure smooth operation.
3. **Popular Libraries**:
* Pandas: Used for data manipulation and analysis, providing data structures like DataFrames.
* Numpy: Utilized for numerical operations and handling arrays.
* Plotly: Employed for creating interactive visualizations such as Gantt charts and timelines.
* Dash: Framework for building web applications with interactive components.
* SQLAlchemy: Used for database interaction, supporting various SQL operations.
* Openpyxl: Handles Excel file operations.
* Logging: Implements logging for debugging and error tracking.
4. **Applications**: User can look for testing information and filter data reports by data, test bench, test status and others, consult full datalogs, verify test status and update, delete or add information to tests database, generate GANTT charts, consult and download standards, manuals, forms and other lab documentation, generate report related to quantity of tests realized and extract useful information from it. User can also report test data, check consulting data tables.
5. **Limitations and Future**: This is a prototype, so, it is necessary to refine the application to extract and update the data to a more robust database in snowflake environment. Some functionalities such as pre-test form, contacts and few others sitll to be implemented in the next releases.
6. **Conclusion**: The Laboratory Dashboard Application is a comprehensive tool for managing laboratory data, generating reports, and visualizing data through interactive charts and graphs. By leveraging popular libraries such as Pandas, Plotly, Dash, and SQLAlchemy, the application provides a robust and user-friendly interface for laboratory operations. While there are some limitations, the future scope includes enhancements in visualization, real-time data processing, machine learning integration, and cloud services, making it a promising tool for laboratory data management.

## Usage

To run the application, execute the following command:

```bash
python app.py
