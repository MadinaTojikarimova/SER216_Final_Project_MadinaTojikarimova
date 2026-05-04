# SER216_Final_Project_MadinaTojikarimova

Digital Parking Permit System
Functional requirements 
The following functional requirements define the core capabilities that the Digital Parking Permit System
must provide to its users.
The system shall allow students and staff to register one or more vehicles
by providing vehicle details (make, model, colour, and licence plate
number) linked to their university ID.
Security staff shall be able to search any permit by licence plate number
and create, view, or update violation records associated with that permit.
Registered users shall be able to submit a parking permit application,
selecting a preferred parking zone and desired permit duration (daily,
semester, or annual).
FR-03 Zone Availability Check The system shall display real-time availability of all parking zones before
a permit is approved, preventing over-allocation of spaces in any zone.
FR-04 Violation Record
Management
1.2 Non-Functional Requirements
These requirements define quality attributes and constraints the system must satisfy.
Performance
The system shall load parking zone availability data within 2 seconds
under normal network conditions with up to 500 concurrent users.
All user data and permit records shall be encrypted in transit using TLS
1.2 or higher, and system access shall be controlled by role-based
permissions (student / staff / security)
