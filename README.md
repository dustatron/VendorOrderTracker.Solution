# _PIERRE'S BAKERY VENDOR MANAGEMENT_

#### _Vendor and Order Tracker Basic Web App Project_, _March 13, 2020_

#### By _**Drake Wilcox**_

## Description

_This project was created for Week 3 of the C# Unit at Epicodus. The purpose of the project was to create a ASP.NET Core MVC web appplication for "Pierre's Bakery." The Appication allows Pierre to track their vendors and all orders associated with that particular Vendor. When a new vendor is created, it is added to a list of Vendors. Each vendor acts as a link to a unique page that lists current orders for that particular vendor, and a link to add new orders. When the user clicks on a particular order all of the information entered by the user on both forms for that vendor and order is displayed in a final order page._

## Specifications:

| Specification | Example Input | Example Output |
| :-------------|:-------------:|:-------------:|
| Application allows user to input Vendor information and displays a list of Vendors | Form submitted with "Vendor Name", "Description", and "Location" | List of Vendors | 
| When a user enters a new vendor, the application displays all vendors that have been inputed | Second Form submitted with Vendor Information | Vendor List: "Vendor 1" "Vendor 2" |
| When a user clicks on the name of the vendor the application returns with a list of orders | User Clicks Vendor Name | Numbered List of Orders: |
| When user views orders they are given the option to add new order information to that vendor | User Clicks "Add New Order" | Form with inputs for "Order Title," "Description," "Order Price," and "Date of Order." |
| When a user adds a new Order Form, they are directed to a list of orders for the selected vendor | User Clicks "Add Order" | "All Current Orders for this Vendor: "|
| When a user clicks on the Order Name they are directed to a to a page of order details for that particular order | User Clicks Order Name | Order Details: "Title:" "Description:" "Date:" "Price:" |




## Setup/Installation Requirements

To use this application, follow the following instructions. 

#### Installing .NET core

##### For macOS: 

* Dowload [this .NET Core SDK](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer) which will prompt a .pkg file download from Microsoft.

* Open the file. This will launch and walk you through installation steps. Use default settings. 

* Confirm the installation is successful by opening the terminal and running the command ``$ dotnet --version``. You should see something like ``2.2.105`` in response.

##### For Windows: 
* Visit the [Microsoft .NET Installation Guide](https://docs.microsoft.com/en-us/dotnet/framework/install/).

#### Installing donet script

* After installing .NET Core, run the command `` dotnet tool install -g dotnet-script `` in Terminal. 

#### Application Setup:
_Clone this repository via Terminal using the following commands:_
* ``$ cd desktop``
* ``$ git clone "https://github.com/drakewilcox/VendorOrderTracker.Solution" ``
* ``$ cd VendorOrderTracker.Solution``

_To Run this Application, enter the following command in the Terminal:_

* ``cd Vendor Order Tracker``
* ``dotnet restore``
* ``dotnet build``
* ``dotnet run`` or ``dotnet watch run``
* as server is running go to the page ``http://localhost:5000`` in your browser to view page.

_To view the source code of this application, open the folder in the Text Editor of your choice. (Example: to open via Visual Code enter the command ``code . `` in Terminal.)_

## Technologies Used
* _Git_
* _C#_
* _ASP.NET Core MVC_
* _dotnet script_
* _VS Code_
* _Bootstrap_
* _CSS_
* _Razor_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Drake Wilcox_**