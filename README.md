﻿# Nodejs-JWT
# API-REST-NodeJS-JWT

The university needs to take control of the computer equipment
(computers (desktops and laptops), mouse, keyboard, monitors, etc.), mobiles (cell phones,tablets, speakers, etc.), etc. For this, it is necessary to have a web application where record the data of the different equipment that you currently have in your inventory to have a better control of such equipment.

Add a new field to the users module to save the password.

The password must be saved in the encrypted database.

Add a new field to the users module to save the role.

Allowed roles are administrator and teacher.

Adjust the user creation service to allow adding the password and role fields.

Define a new service that allows user authentication by email and password.

Adjust the inventory services, equipment statuses, brands and types of equipment so that they receive the token in the request header.

Users with an administrator role have access to the creation of equipment states, brands, types of equipment, users and inventories.

Users with the teacher role can only view inventories.
