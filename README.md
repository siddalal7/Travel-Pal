# Travel_Partner
Travel Buddy Python/Django Project by Siddhant Dalal

INTRO:
--------------------
-Application was built as part of the Coding Dojo Python course. The web app must satisfy the following requirements:

1. Login and registrations must have validation. All validation errors must appear on the page. Password must be atleast 8 characters and the app should have log out functionality.

2. Each display must be unique to the user logged in. Display the logged in user's created or joined travel plans. You must also display other users' travel plans that the logged in user can join.

3. You must code the ability to join other users' travel plans. Once a user joins a travel plan, the plan should move from the other trips table into the Trips scheduled table.

4. Selecting a particular travel plan should also show the users that have joined that specific plan.

5. Add the ability to add new travel plans and apply validation. The new travel plan should appear on the logged in user's schedule table.

![Image of the wireframe](https://i.imgur.com/Y0SdSvU.png)


TECHNOLOGY USED:
-----------------
1.  Python3.6.4 and SQLite were used for all back-end and data storage logic.

2.  A Virtual Environment was used to manage all module and library dependencies.

3.  CSS3 and HTML5 were used for initial form validation.

4.  Bcrypt was used as a salt/hash algorithm to obsfuscate each user's password stored in SQLite.

5.  Django, Nginx, and Gunicorn were used for server deployment, routing, and execution with data and template client-side service requests handled with Jinja2 and JavaScript.
