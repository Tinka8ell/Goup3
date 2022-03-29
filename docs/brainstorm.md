# Result of brainstorm of the class structure:

User
* user_Id
* Name:String
* Paid_Ticket_array:Ticket[]
* Booking_array:Ticket[]
* Functions
  * Receive_ticket():void

Ticket
* ticket_Id
* No_of_tickets:int
* Concert_id:Concert
* User_id:User

Booked_Ticket is a ticket
* Cost:float

Paid_Ticket is a ticket

Concert
* Concert_id
* Concert_date:Datetime
* Concert_location:String
* Concert_price:float
* Available_Tickets:int
* Booked_tickets:int
* Bought_tickets:int
* Functions
  * Show_Available(): return price: float
  * Book():void
  * Pay():void

Booking system
* Users_array:User[]
* Concerts_array:Concert[]
* Functions
  * Find_a_concert_seat(): return price: float
  * Book_a_ticket():void
  * Pay_for_ticket():void
