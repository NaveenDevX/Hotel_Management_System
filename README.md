Hotel Management System
Project Description
This is a simple console-based Hotel Management System implemented in Java. It allows users to manage hotel room bookings effectively, including viewing available rooms, booking rooms by number or type, canceling bookings, and calculating the total price for a booking. The system persists room data in a text file to maintain state between program executions.

Features
Room Management: Each room has a room number, type (e.g., Single, Deluxe, Suite, Luxury), price, and availability status.

Load and Save Data: Room details and their availability are loaded from and saved to a file (rooms.txt).

View Available Rooms: Users can see a list of all rooms that are currently available.

Book Rooms: Users can book one or more rooms by room number or book rooms by selecting a room type.

Cancel Bookings: Users can cancel an existing booking by specifying the room number.

Calculate Total Amount: Users can calculate the total cost of a booked room based on its price.

Console Menu Interface: Easy-to-use menu to navigate through the various system functions.

How to Use
Run the HotelManagementSystem Java program.

Use the console menu to select options:

View available rooms.

Book rooms by entering the number of rooms or by room type.

Cancel bookings.

Calculate the total amount for a booked room.

Exit the application.

The system will automatically load room data on startup and save any changes such as bookings and cancellations.

File Structure
HotelManagementSystem.java - Main program containing all the logic for room management.

rooms.txt - Data file storing room details and their availability status.

Prerequisites
Java Development Kit (JDK) installed (version 8 or above recommended).

Basic command line knowledge for running Java programs.

How to Run
Compile and run the program using the following commands:

bash
javac HotelManagementSystem.java
java HotelManagementSystem
Notes
Ensure the rooms.txt file exists in the same directory as the program with correct room data formatted as:

text
roomNumber, roomType, price, isAvailable
The system currently supports basic room types such as Single, Deluxe, Suite, and Luxury.

This project is ideal for learning basic Java programming, file handling, and building a simple but functional hotel booking system.
