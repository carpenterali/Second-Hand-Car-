User Manual for the Second Hand Car Application

1. Introduction
This application is designed to manage and analyze car-related data. It provides functionalities to view, edit, and analyze information stored in a SQLite database, with a user-friendly interface. The application is implemented using Python and leverages a combination of scripts and a graphical interface for ease of use.

2. Installation and Setup
System Requirements:
Python 3.8 or later
Required Python libraries:
PyQt5
pandas
sqlite3
matplotlib
Steps to Install:
Extract the program files from the ZIP archive.
Navigate to the extracted folder.
Ensure Python and the required libraries are installed:
 pip install PyQt5 pandas matplotlib


The program includes a SQLite database (cars.sqlite) and additional scripts.

3. Folder Structure
main.py: The main script to run the application.
main_ui.ui: The graphical interface file.
cars.py: Script containing database-related operations.
ui_style.py: Styles and themes for the graphical interface.
data.csv: Sample CSV file for importing/exporting car data.
cars.sqlite: SQLite database file with preloaded car data.
cars.ipynb: Jupyter Notebook for data analysis and testing.
.git, .ipynb_checkpoints, and __pycache__: Metadata and temporary files.

4. Usage Instructions
4.1 Running the Program
To launch the application, execute the main.py script:
python main.py

This will start the graphical interface of the program.
4.2 User Interface Overview
Dashboard: View a summary of car-related data.
Data Import/Export: Import new data from data.csv or export database records to CSV.
Database Management:
Add new car entries.
Update existing records.
Delete records.
Analysis Tools: Visualize car data using graphs and charts.
4.3 Working with the Database
Connecting to the Database: The application automatically connects to cars.sqlite on startup.
Editing Records: Use the interface to add, modify, or delete car data.
4.4 Importing/Exporting Data
Import: Upload data from a CSV file by selecting data.csv.
Export: Save the current database contents into a CSV format.
4.5 Data Analysis
View Graphs: Generate visualizations for trends and summaries.
Notebook Analysis: Use the cars.ipynb file for custom data analysis.

5. Customization
The application's appearance can be modified using ui_style.py. For example, you can:
Change color schemes.
Adjust button styles.

6. Troubleshooting
Application Does Not Start: Ensure Python is installed and all required libraries are installed.
Database Errors: Check that cars.sqlite is in the same directory as main.py.
Import/Export Issues: Verify the format of data.csv matches the database schema.

7. Advanced Features
7.1 Notebook Analysis
The cars.ipynb file allows users to perform advanced data analysis using Python libraries like pandas and matplotlib. Open it in Jupyter Notebook to explore.
7.2 Extending the Database
You can expand the cars.sqlite database by:
Adding new tables via SQL commands.
Modifying existing table structures.

8. Frequently Asked Questions (FAQ)
Can I change the database file? Yes, update the path in cars.py to point to a new SQLite file.
How do I add new analysis charts? Update the logic in cars.py and integrate it with main_ui.ui.
What if I need more features? Modify the source code to include additional functionalities.

9. License and Credits
This application is open-source and can be modified for personal or commercial use. If you use this project, please credit the original developers.

10. Contact Information
For support or inquiries, contact:

GitHub: https://github.com/carpenterali/se_project
GitHub: https://github.com/kemalsinoplu/se_project


