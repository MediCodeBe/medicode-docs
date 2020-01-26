#Transports

###Create a transport
A transport is always linked to a [patient](patients.md). You need to create the transport from the patient's section by clicking on the green button in the patient's list. Or by clicking the "create new transport" button on the patient's page.

When creating a transport these fields are fillable.

- **Pickup address** - *This is the address where the ambulance crew should pickup the patient. Each new address is registered in the [locations](locations.md) section. The pickup location can be specified by filling in the "pickup department" field. (Required field)*
- **Pickup time** - *This is the time when the ambulance crew should pick up the patient (Required field)*
- **Delivery address** - *This is the address where the ambulance crew should deliver the patient. Each new address is registered in the [locations](locations.md) section. The delivery location can be specified by filling in the "delivery department" field. (Required field)*
- **Delivery time**  - *This is the time when the ambulance crew should deliver the patient (Required field)*
- **Trip direction** - *This specifies whether it is an outward or a return trip (Required field)*
- **Transport Applicant** - *This specifies who requested the transport. These values can be customised in the administrator dashboard, by default these are: "Private", "Doctor", "Hospital". (Required field)*
- **Transport mode** - *This specifies how the patient should be transported, these values can be customised in the administrator dashboard, by default these are: "Lying", "Wheelchair", "Sitting". (Required field)*
- **Transport reason** - *This specifies why the patient needed to be transported, these values can be customised in the administrator dashboard, by default these are: "Treatment", "Consultation", "Emergency". (Required field)*
- **Transport type** - *This specifies the type of transport, these values can be customised in the administrator dashboard, by default these are: "Non-urgent", "Intensive care", "Emergency". (Required field)*
- **Passengers** - *This specifies whether there are passengers. (Required field)*
- **Prio code** - *This specifies which prio code the transport has. (Required field)*
- **Mutuality transport number** - *When the transport is commissioned by a mutuality, you can specify the transport ID given by the mutuality.*
- **Payment patient** - *When the transport is commissioned by a mutuality, you can specify the amount the patient should pay.*
- **Payment mutuality** - *When the transport is commissioned by a mutuality, you can specify the amount the mutuality should pay.*
- **Transport notes** - *Here you can add some notes for the ambulance crew.*



###Transport statuses
By default MediCode comes with these statuses, you can change the statuses by contacting the MediCode support desk. 
These are the default statuses:

- Please assign vehicle
- Vehicle assigned
- Accepted
- Heading to patient
- Arrived at patient
- Carrying patient
- Arrived at delivery address
- Finished

When a new transport is registered, the status will automatically be set to "Please assign vehicle"



