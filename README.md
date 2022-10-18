# Hotel-Booking-Management-System implementing OOPs concepts-in-Java
This is a Hotel Management tool which can be used to manage activities like Storing customer details, Booking rooms (4 types), Ordering food, Cancel bookings and Generating Bills/Invoices. 

It can also be used to see different room features and room availibility.

It is a menu driven program and it runs until the user exits.

File handling has been used to store the current status of the hotel(customer details, booked rooms, food ordered) in a file, so
that when we restart the program, the old details are not lost.

The program reads the file when it restarts to know the previous status of the hotel. Writing of file has been done in a
separate thread as it can be done parallely. 

User defined exception is thrown if the user tries to book an already allotted room. 

Exception handling is properly done to deal with any
kind of unexpected exception.

##### Topics Covered-  
Classes and Objects, Inheritance, File Handling with Objects, ArrayList, implementing
Interface, User defined exception and Exception handling.
