Overview
This repository contains the dimensional model for Fufu Republic, a restaurant chain in Nigeria. The model is designed to analyze sales data, manage inventory, and improve customer experience.

Contents
Dimensional Model Schema: Diagram of the star schema for sales analysis.
Business Process Documentation: Details on the sales analysis process and business questions.
Dimensional Model
Fact Table: SalesFact

Measures: TotalSalesAmount, QuantitySold
Dimensions:

Customer: CustomerID, Name, Email, PhoneNumber
Date: DateKey, Date, Month, Year
Outlet: OutletID, LocationName, BranchType
MenuItem: MenuItemID, Name, Category, Price
PaymentMethod: PaymentMethodID, PaymentMethodName
Usage
Refer to the diagrams and documentation to understand how the model can be used for analyzing sales and managing inventory.

![fufu-republic star-schema](https://github.com/user-attachments/assets/a31cac84-67ad-47af-9852-0dd1561eee96)


Contributing
Feel free to contribute by forking the repository and submitting pull requests.

