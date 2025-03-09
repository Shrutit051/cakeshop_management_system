# 🍰 Cake Shop Management System 🍰

## Overview

The **Cake Shop Management System** is a Java-based application designed to manage the operations of a cake shop. It includes features for both employees and customers, such as managing the cake catalog, placing orders, viewing order history, and processing orders. The system uses various data structures like Binary Search Trees (BST), Linked Lists, Queues, and Hash Tables to efficiently manage and store data.

## Features

### Employee Features
1. **View Cake Catalog**: Employees can view the entire cake catalog, including details like cake name, prices for different sizes, and available quantities.
2. **Add Cake to Catalog**: Employees can add new cakes to the catalog with details such as name, prices for small, medium, and large sizes, and available quantities.
3. **View Order History**: Employees can view the history of all orders placed by customers.
4. **Process Orders**: Employees can process orders from the queue, updating the order status and reducing the available stock of cakes.

### Customer Features
1. **View Cake Catalog**: Customers can view the cake catalog, including cake names and prices for different sizes.
2. **Place Order**: Customers can place orders by providing their details (name, email, phone, address, and delivery option) and selecting a cake and size.
3. **Switch to Employee Menu**: Customers can switch to the employee menu if they have the necessary credentials.

## Data Structures Used

1. **Binary Search Tree (BST)**: Used to store and manage the cake catalog. The BST allows for efficient searching, insertion, and deletion of cakes based on their medium price.
2. **Linked List**: Used to store the order history. Each node in the linked list contains details of an order.
3. **Queue**: Used to manage incoming orders. Orders are processed in a First-In-First-Out (FIFO) manner.
4. **Hash Table**: Used to store customer information. The hash table allows for quick lookup of customer details using their email as the key.

## Code Structure

The code is organized into several classes, each responsible for a specific part of the system:

1. **Cake**: Represents a cake with attributes like name, prices for different sizes, and available quantities.
2. **CakeBSTNode**: Represents a node in the Binary Search Tree used to store cakes.
3. **OrderHistoryNode**: Represents a node in the Linked List used to store order history.
4. **OrderQueueNode**: Represents a node in the Queue used to manage incoming orders.
5. **CustomerHashNode**: Represents a node in the Hash Table used to store customer information.
6. **Customer**: Represents a customer with attributes like name, email, phone, address, and delivery option.
7. **CakeShopManagement**: The main class that ties everything together. It contains methods for managing the cake catalog, orders, and customer information.

## How to Run the Code

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/cake-shop-management.git
   cd cake-shop-management
   ```

2. **Compile the Java Code**:
   ```bash
   javac dsminipro/CakeShopManagement.java
   ```

3. **Run the Application**:
   ```bash
   java dsminipro.CakeShopManagement
   ```

4. **Follow the On-Screen Instructions**:
   - Choose whether you are an employee or a customer.
   - If you are an employee, enter the password `Admin123` to access the employee menu.
   - Follow the menu options to manage the cake catalog, view order history, process orders, or switch to the customer menu.
   - If you are a customer, you can view the cake catalog, place orders, or switch to the employee menu.

## Example Usage

### Employee Menu
1. **Add a Cake**:
   - Enter cake details such as name, prices for small, medium, and large sizes, and available quantities.
   - The cake will be added to the catalog and can be viewed by selecting the "View Cake Catalog" option.

2. **View Order History**:
   - View a list of all orders placed by customers.

3. **Process Orders**:
   - Process orders from the queue, updating the order status and reducing the available stock of cakes.

### Customer Menu
1. **Place an Order**:
   - Enter your details (name, email, phone, address, and delivery option).
   - Select a cake and size from the catalog.
   - The order will be added to the queue, and a bill will be printed.

2. **View Cake Catalog**:
   - View the list of available cakes along with their prices for different sizes.

## Future Enhancements

1. **User Authentication**: Implement a more secure authentication system for employees.
2. **Database Integration**: Replace in-memory data structures with a database for persistent storage.
3. **Advanced Search**: Add advanced search options for customers to filter cakes by price, size, or availability.
4. **Order Tracking**: Allow customers to track the status of their orders.
5. **Payment Integration**: Integrate with payment gateways to handle online payments.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Sanika Shidore (UCE2023461)**
- **Shreya Gujarathi (UCE2023463)**
- **Siddhi Vaidya (UCE2023464)**
- **Shruti Thakur (UCE2023469)**
- this is our Mini Project for our course Data Structures(Course code - 23PCCE302) of semester 3, second year, computer engineering! 

---

This README provides a comprehensive overview of the Cake Shop Management System, including its features, data structures, code structure, and instructions on how to run the code. It also outlines potential future enhancements and acknowledges the contributors.
