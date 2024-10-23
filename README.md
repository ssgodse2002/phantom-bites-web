**Phantom Bites** 🍽️  

**Phantom Bites** is a dynamic phantom kitchen management system designed using modern web technologies like **Bootstrap, JavaScript (ES6), and localStorage** to handle *kitchen orders, track their status, and manage delivery* efficiently. This system includes different user modules for **customers, admin, kitchen staff, and delivery agents**, each playing a critical role in the seamless functioning of the phantom kitchen.  


**Key Features**:  

*Responsive UI* built using the latest Bootstrap framework.  
Use of *JavaScript ES6* for real-time interactions and DOM manipulation.  
*localStorage* to store and retrieve customer orders, simulate order tracking, and order preparation.<br>
A clear and simple workflow that tracks orders from customer placement to delivery<br>
.
# Modules:<br>
##### 1. Customer Module:
Order Placement: Customers can browse through various cuisines and place orders. Each order is dynamically generated with unique IDs and stored locally.
Order Tracking: Customers can view their orders, which are automatically assigned default statuses like "Queued to get prepared."
Dynamic Menu: A menu system that allows customers to choose from a variety of items and submit orders, which are stored with increasing unique IDs (e.g., Today5001).
##### 2. Admin Module:
Order Management: Admin can view all incoming orders, their statuses, and update the flow of order processing.
User Management: Admin has control over managing users such as kitchen staff and delivery agents.
Dashboard Analytics: Tracks the overall performance of the kitchen, total orders, and status of order fulfillment.
##### 3. Kitchen Staff Module:
Order Queue: Kitchen staff can view all the orders queued for preparation.
Order Status Update: Kitchen staff update the status of the order as it moves from "Queued" to "Preparing" and finally "Prepared."
Notification System: Once an order is prepared, the system notifies the delivery agent to pick it up for delivery.
##### 4. Delivery Agent Module:
Order Pickup: Delivery agents receive notifications when an order is ready for pickup.
Tracking: Allows agents to view customer locations and mark orders as "Out for Delivery" and "Delivered."
Order Completion: Once delivered, the agent updates the order status to "Delivered," completing the order lifecycle.

**Technologies Used**:
#### HTML/CSS: For the structure and styling of the website.
#### Bootstrap: For a responsive, mobile-friendly design.
#### JavaScript (ES6): To handle client-side functionality, including order management and localStorage operations.
#### localStorage: To temporarily store orders on the client-side, simulating a backend for order processing and tracking.
