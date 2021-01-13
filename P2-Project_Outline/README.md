# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
My project is a computer repair shop ticket system that supports creating, viewing, updating and deleting service tickets. After customers login they will be able to create and view their own tickets. After technicians login they will be able to view and update service tickets that were created by customers. After administrators login they will be able to create (*1), view, update and delete any ticket.

(*1) - Allowing admins to create tickets will require tickets be assigned to an existing user or allowing admins to create new users. Allowing admins to create new users may not be practical to implement depending on time.

### Features
- User Login: Users will be able to create accounts and login.
- User Groups: Available features will be determined by the user's group.
- Create Ticket: Create a new service ticket.
- List Tickets: List tickets that the user's group has permission to view.
- View Ticket Details: View detailed ticket information.
- Search Tickets: Search ticket fields
- Update Tickets: Technicians and admins will be able to update tickets.
- Delete Tickets: Admin will be able to delete tickets.
Advanced features may include:
- using an API to notify customers of ticket status changes via SMS/Email
- using an API to calculate tax and shipping rates
### Technologies
MySQL
C#
Razor
Bootstrap
JavaScript
### What I'll Have to Learn
- How to implement Role-based access control (RBAC)
- How to connect to and use SMS/Email API
- How to connect to and use tax and shipping rate API
### Project Tracker
https://trello.com/b/IgSXb4iJ/liftoff-project-board