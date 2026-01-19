# testrepo
# Assignment: Event Management & Ticketing System (MongoDB Project)
# Objective: Design a backend MongoDB schema for managing events, ticketing, and userinteractions such as browsing, booking, and managing tickets.
# Collection Descriptions:
1. Users (db.Users): Stores personal details and roles (Attendee/Organizer).
2. Events (db.Events): Contains event metadata, pricing, and live ticket availability.
3. Tickets (db.Tickets): A transactional collection representing a booking.
4. Categories (db.Categories): A master metadata collection for event types.
# CRUD Capability
The system is fully dynamic, supporting:
Create: Adding new events and user registrations.
Read: Complex filtering of events by date and location.
Update: Real-time decrementing of availableTickets upon booking.
Delete: Cleaning up cancelled bookings or expired events.
# Aggregation
 Generate reports:
- Top 5 events by ticket sales
- Total revenue earned by an organizer
- Number of attendees per event
- Events grouped by category and status
 # indexes
 Use indexes to optimize frequent queries such as event searches by date or category.
