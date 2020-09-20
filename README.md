# bamazon

## Description

Bamazon is a CRM that focuses on sales. It provides command-line interfaces for customers, managers, and supervisors.

## How to Run

To run Bamazon on Windows and Mac, you will need Bash, Node, npm, and MySQL Workbench.

In Bash, type git clone git@github.com:https://github.com/swissbizz/bamazon to download Bamazon.

Then, type cd https://github.com/swissbizz/bamazon; npm install to download the required packages.

In MySQL Workbench, connect to localhost:3306 and run bamazon_schema.sql then bamazon_seeds.sql.

Finally, in Bash, type node bamazonCustomer.js to log in as a customer, node bamazonManager.js as a manager, and node bamazonSupervisor.js as a supervisor.
