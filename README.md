# Streamline manual and repetitive data entry tasks through automation.

The two tiny modules in this project are a sales order (JavaFX) module that will import data from an excel sheet and an automated data entry module (Python) that will enter data automatically. 

## Prerequisites:

To successfully run the project, ensure the following prerequisites are met:
* Java 1.8.0_66: https://www.java.com/download/
* Python 3.8: Download and install from https://www.python.org/downloads
* Pandas: Install using pip install pandas in the command prompt
* Xlrd : Install using  pip install xlrd in the command prompt
* Pyautogui: Install using pip install pyautogui in the command prompt
* Oracle Database 19c: Download and install it from https://www.oracle.com/database/technologies/oracle19c-windows-downloads.html

## Project Execution:

* Follow these steps to execute the project:
1. Clone the project repository to your local machine.
2. Configure your database schema credentials in the src/database/DbConnection file.
3. Execute the database script found in database/script.sql within your preferred database IDE (e.g., SQL Developer, TOAD, etc.).
4. Run the project, either through NetBeans IDE or the command prompt.

## Execution Flow:

* Upon running the project, a graphical user interface (GUI) form will appear as a pop-up window.
* Data required for automation will be sourced from an Excel sheet located at automation/Sales Orders.xlsx.
* The automation process is initiated through the Python script.

## Automation Process:

* The Python script (automation/script.py) is responsible for automating data entry.
* It reads data from the Excel sheet and proceeds to enter this data into the GUI form.
* The script automates the "save" operation as well.
* The automation script is designed to iterate 10 times, thanks to a break statement embedded within the code.

## Project Benefits:

This project offers several advantages:
* Elimination of manual data entry, reducing the potential for human error.
* Efficiency gains through automation, leading to time and cost savings.
* Integration with an Oracle Database for secure and organized data storage.
* Ease of use, with clear instructions for setup and execution.

## Use Cases:

This project is well-suited for businesses and organizations that frequently deal with data entry tasks, such as processing sales orders, customer information, or inventory management. It can significantly enhance operational efficiency by automating repetitive processes.

Here are some use cases for this project:

1. Inventory Management:

   Automating the entry of inventory data, including product details, quantities, and pricing, into a database system.
   Regularly updating inventory levels and ensuring accurate stock records without manual intervention.

2. Financial Transactions:

   Automating the entry of financial transactions, such as invoices, receipts, and expense reports, into accounting software.
   Reducing the risk of errors in financial records, which can have significant implications for businesses.

3. Customer Relationship Management (CRM):

   Automatically inputting customer data, contact information, and interactions into a CRM system.
   Streamlining the process of managing customer relationships and improving customer service.


