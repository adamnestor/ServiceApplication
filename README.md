# Service Application
## Final Project Proposal

### Application Summary

This service application aims to streamline the tracking and organization of service hours for both a school that requires service hours for graduation and the students within that school. Users can easily create accounts as school administrators or students. School admins gain access to a comprehensive dashboard where they can monitor student progress, manage service requirements, and oversee student profiles with options to update information and approve incoming service events. Students, on the other hand, enjoy a personalized dashboard showcasing their progress, including detailed service event listing with options to update, delete, or create new events. Our application fosters efficient communication and organization or service hours, empowering both administrators and students to fulfill their service requirements effectively. 

### Welcome Page
    
1. **Welcome to website**
2. **Information regarding mission and purpose**
3. **Ability to Create Account / Sign In as an organization administrator (admin)**
    1. Create Account
        - Admin Name
        - Admin Username
        - Admin Password
        - Organization Name
        - Total Service Requirements
        - Optional Sub Requirements
            -- Number of Hours for each year
        - Optional Service Categories
    2. Sign In
        - Username
        - Password
4. **Ability to Create Account / Sign In as a student user**
    1. Create Account
        - Student Name
        - Student Username
        - Student Password
        - Student Organization (Select from Dropdown Menu)
    2. Sign In
        - Username
        - Password

### Admin User Experience

1. **Organization Admin Home Page**
    1. Dashboard of Progress
    2. List of Students within Organization
    3. List of Submitted Service Event Seeking Approval
    4. Ability to update admin user password
    5. Ability to give a user admin status??
    6. Ability to update organization service requirements
        * Update organization name
        * Update requirements
        * Update sub requirements
        * Update service categories
    7. Ability to delete organization

2. **Admin View of Individual Students**
    - When a student listed on home page is clicked
        * Ability to remove student from organization
        * Ability to view list of service events for student
3. **Admin View of Service Events**
    - When a service event on home page is clicked
        * View Event Information
        * Ability to change status of event to "Needs Attention" or "Approved"
        * ability to leave comments

### Student User Experience

1. **Student User Home Page**
    1. Dashboard of Progress
        * Overall Requirement Progress
        * Optional Sub Reqirement Progress
        * Ability to update password/organization
        * Ability to delete account
    2. List of Service Events
        * Organized with most recent on top
        * Information regarding service event
            - Location
            - Date
            - Number of Hours
            - Status: Submitted, Needs Attention, Approved
            - Description of Event
            - Service Supervisor Name
            - Category (if defined)
            - Comments
    3. Ability to create a new service event

2. **Service Event View**
    - When a service event list on home page is clicked
        * Ability to update event
        * Ability to delete event
