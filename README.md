# D3wat.Barcode
Party invitation and guest management site using JavaScript, HTML, CSS, Python Flask, MySQL, Google Cloud, Azure APIs, and WhatsApp API. Users can create accounts, party tickets, manage guests, send WhatsApp invites, and track responses. Future mobile app for event tracking and barcode scanning.

**Project Description: Party Invitation and Guest Management Website**

This website streamlines the process of organizing and managing party invitations and guest lists. Built using JavaScript (with multiple libraries), HTML, CSS, and Python Flask, it also integrates MySQL for database management, Google Cloud and Azure APIs for additional functionalities, and the WhatsApp API for real-time communication and call-to-action features.

### Key Features:
1. **User Account Creation:**
   - Users can create an account on the website to manage their events.

2. **Party Ticket Creation:**
   - Users can create a party ticket by specifying details such as:
     - Type of party
     - Party poster (image upload)
     - Date, time, and location
     - Name of the venue
     - Open or invitation-only event (with unique barcodes for each guest for entrance scanning)

3. **Guest Management:**
   - Add guests individually through a form or by uploading an Excel file with the guest list.
   - Automatically send personalized WhatsApp messages to all listed guests containing the party poster and details.
   - Messages include a call-to-action allowing guests to accept or decline the invitation.

4. **Notifications and Tracking:**
   - Users receive notifications for each guest's response (accept or decline).
   - Accepted guests receive a Google Maps location and their unique barcode for entry.

5. **Event Day Features:**
   - On the day of the event, users can scan each guest's barcode to verify their attendance.
   - A future mobile app (currently in development) will offer a full dashboard showing:
     - Number of accepted, declined, and unresponsive guests.
     - Number of guests already scanned and yet to be scanned.

6. **Admin Dashboard:**
   - The dashboard provides comprehensive data on guest responses and attendance.
   - A button for scanning guest barcodes directly via the website (in progress).

### Future Projects:
- **Mobile App:**
  - Development of a mobile app that provides users with a full dashboard and the ability to manage guest lists, send invitations, and scan barcodes directly from their mobile devices.

This project leverages various technologies to ensure a seamless and efficient party planning and management experience.
