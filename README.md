# NM-EX9h2

Test in Postman
Flights
GET  /flights
GET  /flights/1
GET  /flights/search?source=Chennai&destination=Mumbai
GET  /flights/fare?max=5000
POST /flights  → { "flightNumber":"IG105", "source":"Mumbai", "destination":"Chennai", "departureTime":"16:00", "fare":4000, "availableSeats":60 }
PUT  /flights/1
DELETE /flights/1
Passengers
GET  /passengers
POST /passengers → { "name":"Sneha", "email":"sneha@gmail.com", "phone":"9876543213" }
PUT  /passengers/1
DELETE /passengers/1
Bookings
GET /bookings
POST /bookings?flightId=1&passengerId=1
GET  /bookings/passenger/1
GET  /bookings/flight/1
PUT  /bookings/1/cancel
DELETE /bookings/1
