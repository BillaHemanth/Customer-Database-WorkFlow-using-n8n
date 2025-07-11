# Room Booking Automation Workflow using n8n + Airtable
This project demonstrates how to automate room booking data collection using n8n with Airtable as a backend database.
* Overview -
    - This workflow allows users to submit a room booking form, and the submitted data is automatically stored in an Airtable base.
    - It’s a low-code solution suitable for small businesses, guesthouses, or personal projects needing a simple booking system.
* Workflow Components -
1. Form Trigger (n8n Form) -
Title: ROOM BOOKING
Fields:
         Name (Required)
         Email (Required, email format)
         Phone Number (Required)
         Room Type (Dropdown: Single Bed, Double Bed, Furnished)

2. Airtable Integration - 
         On form submission, the workflow:
         Sends data to Airtable using the Create Record operation.
         Stores Name, Email, Phone Number, and Room type in the configured table.
