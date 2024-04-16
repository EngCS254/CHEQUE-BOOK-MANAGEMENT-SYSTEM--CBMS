# CHEQUE BOOK MANAGEMENT SYSTEM (CBMS)

<img src="https://i.pinimg.com/originals/31/bb/e6/31bbe6f8f918fa492ca44ff6b3f0fda6.jpg" width="1000" height="400">

## Introduction
Welcome to the future of banking efficiency and customer satisfaction. Our Cheque Book Management System revolutionizes the way Consolidated Bank handles its cheque book issuance, inventory management and compliance, ensuring a seamless and secure experience for both banks and their customers.

## Problems Addressed

**1.	Manual Errors in Cheque Book Issuance**: Current manual processes for issuing cheque books are prone to human errors, leading to discrepancies in record-keeping and potential financial losses.
   
**2.	Inefficient Inventory Management**: Banks struggle to efficiently manage their cheque book inventory, often leading to shortages or overstocking, impacting customer service and operational costs.
  
**3.	Lack of Real-time Tracking**: The absence of real-time tracking of cheque book issuance and usage makes it challenging for banks to monitor and respond promptly to customer requests and potential fraud.
  
**4.	Customer Dissatisfaction**: Manual processes result in delays and errors in cheque book issuance, leading to customer dissatisfaction and a negative impact on the bank's reputation.
  
## Solution: Cheque Book Management Syatem (CBMS)
An automated system that streamlines cheque book issuance, tracks inventory in real-time, enhances compliance, and improves customer satisfaction. Built on a relational database and deployed on Streamlit.

## Objectives of CBMS
**1. Efficient Cheque Book Tracking**: Develop a system that efficiently tracks the issuance, use, and availability of cheque books.

**2. Streamline Cheque Book Issuance**: Create a platform that streamlines the process of issuing cheque books, reducing manual errors and saving time for bank staff and customers.

**3. Improve Security**: Implement robust security features to protect against fraudulent activities, ensuring that cheque books are issued and used securely.

**4. Comprehensive Reporting and Reconciliation**: Provide detailed reports on cheque book issuance, usage, and inventory.

**5. User-Friendly Interface**: Design a user-friendly interface that is easy to navigate and understand, reducing the learning curve of bank staff.

## Exploring CBMS

**1. Sidebar**

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/1.%20Sidebar.PNG" width="700">

**2.	All Cheque Books page** 

Displays a data frame of all cheque books that have gone through the branch since CBMS started operating.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/2.%20All%20cheque%20books.png" width="700">

**3.	Cheque Books in Store page** 

All cheque books are kept in a physical store until their owners come to collect them. This page displays a data frame of all cheque books held in the physical store at any given time before collection.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/3.%20cheque%20books%20in%20store.png" width="700">

**4.	Cheque Books Received page**

Allows adding, editing, and deleting entries of cheque books received.

**i) Adding cheque book section**

In this section, the recipient of the new cheque book at the bank inputs the cheque book details, including Account Name, Account Number, Currency (KES, USD, or GBP), Number of Cheque Books, and Contact Number. Clicking the ‘Add’ button adds the cheque book to all tables in the database except the ‘Cheque Books Issued Out’ table.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/4.%20Add%20cheque%20book%20section.png" width="700">

**ii) Editing cheque book section**

This section enables the recipient of the cheque books to edit entries in case of errors. The editable fields are similar to the cheque book details entered in the "Add Cheque Book" section.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/5.%20Edit%20cheque%20book%20section.png" width="700">

**iii) Deleting cheque book section**

This section allows users to delete a cheque book entry from all tables in the database.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/6.%20Delete%20entry%20section.png" width="700">

**5.	Cheque Books Issued Out page**

Allows autofilling and issuing out of cheque books.

**i) Autofilling section**

This section enables users to autofill cheque book details, simplifying the process and making it more efficient.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/7.%20Autofill%20details%20section.png" width="700">

**ii) Issue Out section**

Here, the user verifies the autofilled details for accuracy and then proceeds to issue the cheque book. Upon clicking the ‘Issue Out’ button, the system appends the issued cheque book details to the ‘Cheque Books Issued Out’ table in our database and removes it from the ‘Cheque Books in Store’ table.

<img src="https://github.com/EngCS254/CHEQUE-BOOK-MANAGEMENT-SYSTEM--CBMS/blob/main/8.%20Issue%20out%20cheque%20book%20section.png" width="700">

## Conclusion

In conclusion, our Cheque Book Management System is not just a solution; it's a transformational tool that redefines banking efficiency and customer service. By addressing the key challenges faced by banks in cheque book issuance and management, our system empowers banks to streamline their operations, reduce risks, and enhance customer satisfaction. Embrace the future of banking with our innovative solution and elevate your institution to new heights of success and excellence.


