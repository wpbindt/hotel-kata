# hotel-kata

You are running a hotel with rooms that can be booked. All rooms have a number that identify them.

Users should be able to obtain which rooms are available, given an arrival and departure date.

Users should be able to initiate a booking by specifying room number, arrival date and departure date. If the room
 is available in the given time period, this results in the creation a booking.

A booking can have 3 statuses:
- Reserved
- Confirmed
- Unconfirmed

A booking always starts with the status "Reserved". 
A booking with status "Reserved" blocks the availability of the booked room. Bookings should be confirmed within 24h. If not, the status of the
booking becomes "Unconfirmed". Unconfirmed bookings can no longer be confirmed and do no longer block the availability of the room.

Users should always be able to get the status of their booking.
