#Permissions

- **administration** - *This role gives access to the administrator dashboard. This permission is only given to system administrators.*
- **transport-read** - *This role gives a user the ability to view transports, intervention reports. This gives not the permission to create or edit any transports.*
- **transport-write** - *This role gives a user the ability to create and update transports*
- **transport-write-report** - *This role gives a user the ability to create a intervention report to a transport.*
- **transport-delete** - *This role gives a user the ability to delete transports*
- **patient-read**  - *This role gives a user the ability to view patients, medical notes, ... . This gives not the permission to create or edit any patients.*
- **patient-write** - *This role gives a user the ability to create and update patients*
- **patient-delete** - *This role gives a user the ability to delete patients*
- **patient-write-note** - *This role gives a user the ability to create a medical note for a patient*
- **patient-delete-note** - *This role gives a user the ability to delete medical notes*
- **vehicle-read** - *This role gives a user the ability to view vehicles, but not to create or edit any vehicles*
- **vehicle-write** - *This role gives a user the ability to create and update vehicles*
- **vehicle-delete** - *This role gives a user the ability to delete vehicles*
- **location-read** - *This role gives a user the ability to view locations, but not to create or edit any locations*
- **location-write** - *This role gives a user the ability to create and update locations*
- **location-delete** - *This role gives a user the ability to delete locations*
- **dispatch-read** - *This role gives a user the ability to manage various dispatching tasks. (assign vehicle, dispatch dashboard, dispatch calendar, ...)*
- **dispatch-write** - *This role gives a user the ability to update a transport status. This permission is commonly given to all users (paramedics, dispatchers, ...)*

###Roles
In MediCode you can create your own "roles", a role is a collection of individual permissions. This is a easy way to manage the permissions and assigning multiple permissions to a user. 

By default MediCode comes with these roles:

- **Admin** - *The admin role has ALL the permissions by default, this role is only given to a system administrator.*
- **Dispatcher** - *The dispatcher role has the permission to create, edit patients and transports. Just enough to do the dispatching.*

###User specific permissions
You can add roles to a user, if you want to give 1 single user more permissions you can add it manually. You can specify some roles AND permissions to a user.