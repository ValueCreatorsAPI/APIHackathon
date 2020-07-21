NatWest Mobile APP - Prototype version 1.0

The objective of this document is to explain the functionality, modules, API and technical details of this application.
The concept is designed in web application using C#.Net for promoting the idea in Mobile App.

Modules & API details
1) Home page - Main Menu details (Commitments, Cash Inflow and Pal Teller)

2) Commitments - This step will connect with Accounts & Transactions API and pull the Standing Order/DirectDebits 
and schedueld Payments data for the customer. Basicall showing the customers his expenses in detail.

3) Cash Inflow - This step will show the Customer his Income. This module will connect with Transactions API and pull the Credits/Debits for the customers,
which intun handled with the logic of standard and Variable Income based on criteria.

4) Pal Teller - This feature will help the customer in terms of providing suggestions, recommendations and any support 
to manage his funds better. This feature has scope to connect with 3rd party API's, CORA and other bank API's for loans, investment and well being.

Technology used
1) Postman to activate an API
2) Visual Studio 2015
3) .Net Framework 4.5
4) Programming language c#