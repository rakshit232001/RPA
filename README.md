# RPA

# Robotic Process Automation Projects

Welcome to our collection of Robotic Process Automation (RPA) projects! Below you'll find a brief description of each project 

## 1. Sales Order Validation

### Description:
Validating orders is a time consuming process for Catchy Components. They desperately need an bot to automate the process of validating orders to improve their customer experience and send invoices out in a timely fashion. The Bot must start by launching this challenge page. From there, the bot needs to click the link below to launch the organization's sales order application, navigate to the Sales Order tab, then start validating orders.

-For each order with a status of “Confirmed” or “Delivery Outstanding” - the bot needs to expand the order by clicking the “+” button

     ->For each item included in the order, the bot needs to perform a lookup in the tracking details in the Global Express tracking website
     ->If the status for all items is “Delivered” - the bot needs to click the “Generate Invoice” button for the entire order
     ->If one or more items from the order are not yet delivered, no action should be taken on this order.

Once all orders have been checked, the bot should click the “Export” button in the top right corner of the Sales Order app to generate a sales order report that should be uploaded below in order to be validated.



## 2. Shipment Processing

### Description:
Genexit International, a manufacturing company, has received a list of orders and intends to ship them with tracking numbers. For each PO number, corresponding details for the order are available in the ProcureEase appplication. Use this information to generate the tracking number using the ShipGlobe Tracking Number Generator application. Select the Shipping Type (based on the rules below) for the listed PO numbers, and submit the form.

Purchase Orders
Fill in the missing data for the following purchase orders before you submit. Select the Shipping Type based on the following criteria: For orders with a value of $300 or less, Ground Shipping should be chosen. For orders with a value of $600 or greater, Express Plus should be selected. Otherwise, Express should be the preferred option.

Rules for solving this challenge:
Use a Generative AI provider (such as ChatGPT) to obtain the full name of the state associated with the state code in the ProcureEase purchase order lookup application. For instance, if the state code for PO Number 99-771-9626 is "TX," send "TX" to ChatGPT to retrieve the full state name. Extract the state name from the model's response and use it in the Tracking number generator application to generate the tracking number.

## 3. IMDB Dashboard

### Description:
The IMDb Dashboard project involves creating a dashboard that aggregates data from IMDb (Internet Movie Database) to provide insights into movie ratings, trends, and popular genres. It leverages RPA to extract, transform, and visualize IMDb data for easy analysis.

## 4. Data Extraction from PDF

### Description:
This project automates the extraction of data from PDF documents, such as invoices, reports, or forms. It utilizes RPA techniques and VBScript to parse PDF files, extract relevant information, and populate databases or spreadsheets with accurate data.

## 5. Dynamic ID in Input Forms

### Description:
The Dynamic ID in Input Forms project addresses the challenge of automating tasks involving web forms with dynamically generated IDs. It employs RPA solutions to dynamically locate and interact with input fields, regardless of their changing identifiers, ensuring seamless form submission and data entry.
## 6. Quarter Close Process - Finance

### Description:
The finance department of Peters Manufacturing needs your help. At the end of each fiscal quarter, the finance team spends a significant amount of time doing very important work: making sure that all of the financial obligations that were met, they were invoiced on time, that they paid on time and that, all payments cleared in the expected time period.

For each of the transactions below, find the matching transaction in the Arcadia Banking application. If a match is found, mark the transaction as 'Verified'. If no match is found, mark the trasaction as 'Unverified' so that the finance team can dig into this transaction further.


---

Feel free to reach out if you have any questions or suggestions for improvement!
