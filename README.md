To Supply Leftover Food to Poor – Full Project Summary
Table of Contents

1. Project Overview
2. User Needs
3. Problems Solved
4. Key Features
5. System Architecture
6. Data Model
7. Custom Objects & Fields
8. User Roles & Access
9. Technical Stack
10. Project Phases
11. Advantages
12. Contributions
1. Project Overview
This Salesforce-based project is designed to facilitate the collection and redistribution of surplus food from venues like restaurants, hostels, and event halls to people in need. It uses Salesforce’s declarative and programmatic tools to manage donations, volunteers, drop-off points, and execution details.



2. User Needs
- Venues need a platform to donate extra food.
- NGOs need visibility into nearby food availability.
- Volunteers need task assignments for timely distribution.
- Admins need monitoring tools for reporting and auditing.

3. Problems Solved
- Reduces food waste through real-time donation tracking.
- Simplifies coordination between donors, NGOs, and volunteers.
- Enables fair and controlled access to data based on roles and distance.

4. Key Features
- Venue Form Flow for fast data entry
- Distance calculation with Trigger logic
- Sharing rules based on geolocation
- Custom Reports and Dashboards
- Public groups and profiles for access control
5. System Architecture
  <img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/7cc09e84-b655-4741-bd86-368dbd12d519" />

 



6. Data Model
  <img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/2ec3d92a-e9ab-45af-beba-20de19932fe6" />

 

8. Custom Objects & Fields
Custom Objects:
- Venue
- Drop-Off Point
- Task
- Volunteer
- Execution Details

Key Custom Fields:
- Distance (formula + number field)
- Geolocation fields
- Ratings
- Volunteer ID, Task ID (Auto Number)
- Food Category (Picklist)
- Name, Email, Phone
8. User Roles & Access
- Roles: Manager > Sales Executive > Sales Person (used in NGO scenario)
- Profiles: NGOs Profile with access only to certain tabs and objects
- Public Groups: Iksha, NSS, Street Cause
- Sharing Rules: Based on distance calculated for Drop-Off Points
9. Technical Stack
- Platform: Salesforce Lightning Experience
- Automation: Flows, Apex Trigger
- Security: Role Hierarchy, Sharing Rules, Field-Level Security
- Reporting: Reports & Dashboards
- UI: Lightning App Builder + Tabs + Screen Flow
10. Project Phases
- Phase 1: Requirement Gathering and Object Design
- Phase 2: Relationships and Field Creation
- Phase 3: Automation (Flow + Trigger)
- Phase 4: Profiles, Roles, Groups, and Sharing
- Phase 5: Reports, Dashboards, Testing, Demo
11. Advantages
- Provides efficient food supply chain tracking
- Uses real-time data sharing to reduce food waste
- Scalable and customizable for various NGOs
- Automates key processes to reduce manual work
12. Contributions
- Designed and built entire application architecture
- Created flows, triggers, sharing rules, and profiles
- Tested and validated with multiple user logins
- Created comprehensive reports and dashboards
- Documented and demonstrated all functionalities
AUTHOR:
Dilleswari Maddi
Salesforce Platform Developer | Web Developer | Tech Enthusiast
https://www.linkedin.com/in/m-dilleswari
