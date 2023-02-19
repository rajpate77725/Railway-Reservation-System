# Railway-Reservation-System
The Railway Reservation System is concerned with the reservation of railway tickets of the passengers.

This project is developed on the railway reservation system using linked list and queue in the data structures. The information required during the reservation is name, age, gender and mobile number and once the reservation is done the user will get his reservation number.

## Features
● To make the reservation process easier for the passengers.<br>
● The data is stored in a computer rather than manual work.<br>
● The system allow user to do following functions like<br>
  a) reservation of ticket :<br>
  This function is used to reserve a ticket for passengers.<br>
  b) cancellation of ticket<br>
  Using this function passengers can cancel a reserved ticket.<br>
  
## Objectives
● The main object of the project is to manage the details of reservation of passengers.<br>
● Easily monitoring the reservation as well as waiting list status.<br>
● All handwritten work and paperwork will be computerized, so therefore the workload of railway staff will be decreased.<br>
● To increase the efficiency of the railway reservation system.<br>


## Functions used
int create() - This function is used to create a node of linked list wherein all reservations and data of passengers are stored. It is only used for first reservation.

int reserve() - This function is used to add further reservations to linked list after the creation of the first reservation in the create() function. Also when the defined size of reservation is full the following reservations are stored in the waiting list giving two different modes for waiting reservation. 

int cancel(int) - This function is used to cancel the reservation of passengers with the help of user defined reservation number. 

void enq(node*) - This function is used to add the reservation of passengers to the queue.

node* deq - This function is used to remove the reservation from queue. This function is used along with the cancel(int) function.

void display() - This function is used to display the reservation data of the passengers.

## Appendix
This project was created as a semester course work for the subject Fundamentals of Data Structure at Pimpri Chinchwad College Of Engineering.
