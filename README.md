## OP Pharmacy Management System

**Introduction**

The OP Pharmacy Management System is a free and open-source software application that helps pharmacies manage their inventory, sales, and customers. It is a web-based application that can be accessed from any device with a web browser.

**Features**

The OP Pharmacy Management System includes the following features:

* **Inventory management:** Track your inventory levels in real-time, set reorder points, and generate reports.
* **Sales management:** Process sales transactions, track customer purchases and generate sales reports.
* **Customer management:** Store customer information, track prescription history, and send email reminders for refills.
* **Reporting:** Generate a variety of reports, including inventory reports, sales reports, and customer reports.

**Installation**

To install the OP Pharmacy Management System, you will need a web server with PHP and MySQL support.

1. Clone the OP Pharmacy Management System repository from GitHub:

```
git clone https://github.com/bisnukundu/OP-Pharmacy-M-S.git
```

2. Create a database for the OP Pharmacy Management System:

```
mysql -u root -p
CREATE DATABASE OP_Pharmacy_Management_System;
```

3. Run the composer and npm commands to install all packages.

```
npm install

composer install
```

4. Copy the database name and paste it inside the .env file.

```
DB_DATABASE="OP_Pharmacy_Management_System"
```

5. Run this command to migrate all tables to the database.

```
php artisan migrate
```
6. After all processes Run the application.

```
php artisan serve
```


**Usage**

Once the OP Pharmacy Management System is installed, you can log in to the application using the username and password that you created during the installation process.

The OP Pharmacy Management System is a user-friendly application, and it is easy to learn how to use. The application includes a comprehensive help system that can provide you with assistance with any questions that you may have.

**Contributions**

The OP Pharmacy Management System is an open-source project, and we welcome contributions from the community. If you have any suggestions for improvements or new features, please feel free to create an issue on the GitHub repository.

**Support**

If you need assistance with the OP Pharmacy Management System, please feel free to open an issue on the GitHub repository. We will do our best to respond to your issue as quickly as possible.

**License**

The OP Pharmacy Management System is licensed under the MIT License. This means that you are free to use, modify, and distribute the software for any purpose, including commercial use.

**Conclusion**

The OP Pharmacy Management System is a powerful and flexible pharmacy management system that can help pharmacies of all sizes improve their efficiency and productivity. The software is free and open source, and it is easy to install and use. We encourage you to try the OP Pharmacy Management System today.


