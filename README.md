# Virtual Appointments (For OctoberCMS)

Easily manage appointments and bookings using the google Calendar and Google Meets services. Create and manage services, categories and your staff users, connect the google calendars of your staff to access to videocalls with your clients.

##Requirements

* This plugin requires the following plugins:
	* Rainlab.Users to manage the staff
	* Offline.Cashier to manage the payments

```
This plugin uses the Google Api library, already embebed
```

* It contains translations to English and Spanish


## Configuration instructions

```markdown
**In order to use the plugin you need to register a Google Application and enable Calendar API**
```

### Google Application configuration and redirection pages
* Go to Settings > CMS > Virtual Appointments
* In the Google Calendar tab enter your google application Name and upload the secret key in JSON format.
__You can download it from Google Console when you create your Google Application__
* In the "General" tab select a page for activating account, login and profile page, in order the plugin can properly redirect to those pages when needed.

### Services
* On the top menu click on the "Virtual Appointments" item
* The first page to open by default is the services list. there you can manage the services you will offer as agency. Your staff users could choose from these services list.
* The price you set for the service is overridable by the staff, they can customize the price for the services and you will see the final price at the appointment list.
* There exists two modes for the services:
	* The normal mode works as an agenda booking, the clients will see the staff calendar with the slots available to book an appointment.
	* The real-time mode works as an in time videocall generator, when the staff user status is "Available for real-time appointments", it will appear in the list of available staff, then the client can make the payment and instantly it will receive a google Meets link to connect with the staff in that moment.
	
	```
	Èvery time someone the staff receives a real-time appointment
	the status "Available for real-time appointments" turns off. in order to avoid conflicts
	```

### Categories
* On the top menu click on the "Virtual Appointments" item
* At the side menu that will open, click on the "Categories" item
* There you can manage your categories 
* These categories will appear in the staff list at the frontend to filter staff by the categories they provide or offer.


### Staff or service providers
* On the top menu click on the "Virtual Appointments" item
* At the side menu that will open, click on the "Service providers" item
* There you can manage your staff information as an admin.
* The staff users has an option in the top menu to manage the profile, calendar, hours, days-off, services, categories

##Components

### Staff widget

*