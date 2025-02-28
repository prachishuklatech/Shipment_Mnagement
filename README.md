# Shipment_Mnagement
Project created on NetBeans connected with Login2Xplore jsonpower db.

Shipment Management Form

 Description
The Shipment Management Form is a web-based application that allows users to store and manage shipment details using JsonPowerDB (JPDB). This form enables users to input shipment information, including shipment number, description, source, destination, shipping date, and expected delivery date. The data is securely stored in a JSON-based database, ensuring easy retrieval and management.

 Benefits of Using JsonPowerDB
- Simple JSON-based storage: No need for complex SQL queries, making it easy to integrate.
- High performance: Fast and efficient data retrieval and storage.
- Schema-free: Allows flexible data handling without predefined table structures.
- Lightweight and serverless: Ideal for small projects and applications without heavy backend requirements.
- Easy API integration: Directly interacts with the database using simple REST API calls.

 Release History
- Version 1.0 (Initial Release):
  - Implemented the shipment management form with form validation.
  - Integrated JSONPowerDB with API calls.
  - Added functionality to save shipment details to the database.
  - Implemented form reset after submission.

Table of Contents
1. [Description](#description)
2. [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Release History](#release-history)
4. [Illustrations](#illustrations)
5. [Scope of Functionalities](#scope-of-functionalities)
6. [Examples of Use](#examples-of-use)
7. [Project Status](#project-status)
8. [Sources](#sources)
9. [Other Information](#other-information)


 Scope of Functionalities
- User Input & Validation: Ensures all fields are filled before submission.
- Data Storage: Saves shipment details in the SHIPMENT-TABLE of the DELIVERY-DB database.
- Database Connectivity: Uses JsonPowerDB APIs to send and retrieve data.
- Error Handling: Alerts the user in case of missing fields or API request failures.
- Form Reset: Clears the form after successful submission.

Examples of Use
1. Adding a New Shipment
   - Fill in shipment details.
   - Click on the Save button.
   - Data is sent to JsonPowerDB and stored.
   - Form resets for a new entry.

2.Checking Stored Data (via API Tools)
   - Use API request: `http://api.login2explore.com:5577/api/iml`.
   - Use `GET` request to retrieve data from **SHIPMENT-TABLE**.

 Project Status
🚀 In Development – More features such as shipment tracking and update functionality may be added in future versions.

 Sources
- [JsonPowerDB Documentation](http://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)
- [jQuery Library](https://jquery.com/)

 Other Information
- This project is part of an internship at Login2Xplore.
- The application is built using HTML, JavaScript, jQuery, and JSONPowerDB.
- Feel free to contribute or suggest improvements!



---

💡 Contributors: Prachi Shukla
📅 Date:28 February 2025  
📩 Contact: shuklaprachimds@gmail.com

