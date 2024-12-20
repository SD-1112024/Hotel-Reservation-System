# Hotel Reservation System

This is a simple **Hotel Reservation System** written in Java. It allows users to view available rooms, make reservations, cancel bookings, manage customer profiles, apply discounts to rooms, process payments, and leave feedback. The system also has an admin login for managing reservations and room details.

## Features

- **Room Management**: View available rooms, make reservations, apply discounts, and manage room bookings.
- **Customer Management**: Create customer profiles with basic details such as name, email, and phone number.
- **Reservation System**: Make and cancel reservations, view reservation details, and process payments.
- **Feedback System**: Customers can leave feedback and rate the rooms they've stayed in.
- **Admin Panel**: An admin login to manage reservations and room details.

## Key Components

1. **Room Class**:
   - Represents each room in the hotel, with attributes like room number, type, price, and available features.
   - Offers functionality to check availability, apply discounts, and manage room booking status.

2. **Customer Class**:
   - Stores customer details like name, email, and phone number.
   - Used to track which customer makes which reservation.

3. **Reservation Class**:
   - Represents a booking made by a customer, including the room, reservation date, check-in and check-out dates, and payment status.
   - Calculates the total price for the stay and tracks the payment status.

4. **Admin Class**:
   - Handles admin authentication using a username and password.
   - Provides functionality to view reservations, add/remove rooms, and access reservation statistics.

5. **Feedback System**:
   - Allows customers to leave ratings and comments for rooms they have stayed in.
   - Enables the hotel to receive insights from customers about their experience.

## How to Use

### 1. **Starting the Program**:
   - Run the program in any Java IDE (e.g., IntelliJ IDEA, Eclipse) or from the terminal using the `java` command.
   
### 2. **Main Menu**:
   Once the program starts, the user is presented with a main menu that offers the following options:
   - View Available Rooms
   - Make a Reservation
   - View All Reservations
   - Cancel a Reservation
   - Manage Customer Profiles
   - Apply Discounts to Rooms
   - Process Payment
   - Admin Login
   - Leave Feedback and Review Rooms
   - Exit

### 3. **Admin Access**:
   To access the admin features, select the "Admin Login" option from the main menu. The default login credentials are:
   - **Username**: `admin`
   - **Password**: `admin123`

### 4. **Room and Reservation Management**:
   - Users can view the available rooms, make reservations, and manage bookings.
   - The admin can add, remove, and manage rooms, as well as view detailed statistics.

### 5. **Payment and Feedback**:
   - Users can process payments for their reservations and leave feedback with ratings and comments for the rooms.

## Requirements

- **Java 8 or higher**: This program is written in Java and uses basic Java libraries.
- **IDE**: A Java IDE like IntelliJ IDEA or Eclipse can be used for running and modifying the code.
- **Command Line**: Alternatively, the program can be compiled and executed from the command line using the `javac` and `java` commands.

## Example Usage

1. **View Available Rooms**:
   - The user can view a list of rooms that are available for booking.
   
2. **Make a Reservation**:
   - A customer enters their details (name, email, phone) and selects a room to reserve.
   
3. **Leave Feedback**:
   - After staying at a room, the customer can leave feedback and rate the room.

4. **Admin Panel**:
   - The admin can log in using the credentials and manage rooms, view all reservations, and add/remove rooms.

## Future Enhancements

- **Database Integration**: To store customer and reservation data persistently.
- **Advanced Payment System**: Integration with real payment gateways.
- **GUI**: Create a graphical user interface for better user experience.
- **Notifications**: Implement email or SMS notifications for customers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


