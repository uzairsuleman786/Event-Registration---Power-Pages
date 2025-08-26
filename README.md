# Event-Registration---Power-Pages
Event Registration created on Power Pages

Lets create Event Registration Pages Site!

Step 1: Create Solution and Define data Model (Dataverse tables)

We’ll keep it simple with two main tables:

Event
Event Name (Text)
Event Date (Date)
Location (Text)
Description (Multiline Text)
Seats Available (Number, optional)

Registration
Registrant Name (Text)
Email (Email)
Event (Lookup to Event table)
Registration Date (Auto, Today’s Date)
Status (Choice: Pending, Confirmed, Cancelled)

Step 2: Set Up Power Pages Site - Control+Shift+R (For Refresh)
Go to power pages! and Create new site 

Step 3: Expose Events to Public (Optional)
Somehow it is unable to save - but lets retry it again later

Lets Create listing Page for Events
These are default List views, lets create out pages custom Listing view
Right now, I dont have any event, Lets create event records from backend
Lets add a button in Home, redirect to Event. Make User Friendly

Any Anoynmous user can view Events but Registration needs to be done by Authenticated users

So I have generated code for registration from GPT
Copying the downloaded fetchxml
Let me just create Form submission JS script
Generated this code from GPT but now update it accordingly to my need

I need WEBAPI Wrapper to call webapis
Let me add this webapi wrapper in the web template so, I can include 1 line code, instead of whole function
Lets give table permission and webapi permissions in site settings
For Now, I am giving all roles, but change it later
Registration Form is created and using webapi, we have created our record for registration of an event.


Now Add button on Listing Events to redirect to Registration Form
Fine for now, Listing Registration but just based on Login user

Fetch Registrations
Let me create contact lookup in registration for login user based fetching
Now when you create registration, it will registered by login user

you can skip this step if you are creating fetchxml at this point and selecting all columns
Lets do Deletion of the Registration as well.
webapi wrapper includes for Deletion api use.

Delete permission is not in placed for now, I keep it that way
Lets create registration detail page 

Let me get the view detail code from GPT
We have created Create, View, Delete
Lets create Edit Page for Registration

Lets Run end to end Scenarios 

So We have completed our CRUD operation using webapi

Thats it for This video!
Thanks for watching 
Bye!
:)
