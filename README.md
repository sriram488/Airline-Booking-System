In this project, a command-line airline reservation system that handles flight searches, bookings, and cancellations entirely from the terminal. Using Python and MySQL, we'll create a dual-interface application where users can search flights, make reservations, and process payments, while administrators manage flight inventory and system operations. The system will feature intelligent flight search capabilities, including direct flights and multi-leg itineraries, with real-time pricing integration through an external API.


Flowchart of the application

<img width="2642" height="1623" alt="6AD62A5E-3E7E-4C76-A5D2-2FAFF03D61FE_1_201_a" src="https://github.com/user-attachments/assets/db8ac37f-6a98-4943-a2a8-c1e588bdb4c3" />



The architecture of the application using object-oriented programming principles with three distinct layers: a CLI interface for user interactions, a repository layer managing MySQL database operations, and a controller layer processing business logic. 
We'll start by designing the database schema and seeding it with initial flight data, then build the Flight component with full CRUD functionality for administrators. 
Next, we'll develop the Reservation component that manages booking records, payment processing, and user confirmations through dedicated database interaction functions and controller logic.

The core of the system lies in the flight search functionality, where we'll implement algorithms that find direct routes between cities and calculate connecting flight itineraries when direct options aren't available. 
We'll integrate an external pricing API to fetch real-time ticket costs, then build a ranking system that identifies the cheapest available options across all search results. 
Finally, we'll complete the reservation management workflow by connecting search results to the booking process, validating seat availability, and confirming reservations in the database.

By the end, we'll have a production-ready booking system demonstrating layered software architecture, object-oriented design patterns, relational database management, API integration, and complex search algorithms. 
This project showcases how to build scalable command-line applications with clear separation of concerns, making it an excellent foundation for understanding enterprise application development.
