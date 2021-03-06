# Goup3
Group Project to create UML project

## Melody’s Music
Welcome to Melody’s Music! 🎧

Melody’s Music is a company that provides a suite of services, 
including an application called ‘Melody’s Music Jam' 🎵 
built for various platforms including iOS, Android and Desktop.
Users can use the ‘Melody’s Music Jam” application to choose a concert event to go to:
* Choose a concert event organised in a city scheduled for a specific date/time
* Request the number of tickets 🎫 they want to book for
* Place the order, make a payment for an amount in British Pounds Sterling and receive the tickets to their personal account

----

Your Engineering Squad works for Melody’s Music 🎧 and you received a request from the CTO to prototype a new project.
As part of the technology roadmap for the ‘Melody’s Music Jam' application, 
there is a requirement to upgrade the legacy (old) ticketing, 
order & payment system to a new ticketing, order & payment system. 💰🤑 
The CTO has tasked your squad to create a UML diagram to visualise how the new ticketing, order & payment system may look like.
----
✅ Read through carefully

✅ Work in your team to create a UML diagram to visualise how the new ticketing, order and payment system may look.

Feel free to use a tool like Flowchart Maker & Online Diagram Software or Microsoft Powerpoint

💥 Please note that we are not looking for perfect solutions here 
(the Software objects you design is entirely up to you which is why in various companies people have come up with various different solutions with pros and cons).

💥 We are looking for you to demonstrate your UML diagramming skills, focusing especially on: 
Class Diagrams, Inheritance, Abstract Classes and Interfaces where relevant to your chosen creation.

### Members of Group 3
* Mark Ingamells
* Jayshree Iyer
* Archana Janarthanan

## Activity
* Brainstorm of [class structure](docs/brainstorm.md)

### Mark's UML
* Initial implementation of the brainstorm:
![Initial implementation of the brainstorm](docs/Mark/InitialImplementaion.png)
* After rationalisation (removed ids, naming convention, data structures)
![After rationalisation](docs/Mark/Rationalised.png)
* Encapsulate and flesh out functions
![Encapsulate](docs/Mark/Encapsulate.png)
* After reorganising and moving bookings to be held by booking system 
and making old Ticket class an abstract class TicketData. 
![After reorganising](docs/Mark/Reorganise.png)
* After reviewing each of our UML diagrams, we decided to present this one.
* But before we show it, there needed to be some spelling corrections, and during that process 
I removed the "bookings" field from "User" and added a getter to access the list from the "Booking System".
![Clarified UML](docs/Mark/Clarifications.png)
* After preparing for the presentation, we decided "User" was confusing with default actor of User, 
so we renamed the class to "UserAccount".
  ![Renamed User](docs/Mark/RenamedUser.png)
