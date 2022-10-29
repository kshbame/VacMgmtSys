# **Actors**

- HR/Admin employee
- Regular employee

# **Use Case List**

- System Registration
- Self Registration
- Request Time Off
- Cancel Time Off Request
- Handle Time Off Request

# **Details**

## Use Case Name
System Registration

### Actor (Initiator)
- HR or admin

### Overview
- There is a new employee to be added. HR or Admin adds initial information
about the employee such as group, reporting manager, level.

### Pre-Conditions
- There is a new employee hired and needs to be added to the system.

### Description
- HR adds a new employee instance.
- HR adds employee's details such as name, reporting manager, pay grade level.
- HR submits the employee details.

### Post Conditions
- System add's time off details based upon employee level.

### Goal accomplished
- Employee basic details are added to the system.

-----------------------------------------------------------------------------------

## Use Case Name
Self Registration

### Actor (Inititator)
- Employee

### Overview
- System has created an instance of the employee with basic details. Employee 
needs to complete the profile.

### Pre-Conditions
- Basic employee details are ready.

### Description
- Employee adds further details such as address, emergency contacts etc.

### Post Conditions
- System validates all the details and asks for incomplete details to be filled and saved.

### Outcome
- All employee details are completed as needed.

-----------------------------------------------------------------------------------

## Use Case Name
Request Time Off

### Actor (Inititator)
- Employee

### Overview
- An employee tries to add a leave request.

### Pre-Conditions
- Complete employee details are ready in the system.

### Description
- An employee browses his time off options.
- An employee selects the date(s) for time off.
- An employee selects the time off category.
- An employee submits this request.

### Post Conditions
- System receives the time off request and starts validating it.

### Outcome
- Time off request is raised.

-----------------------------------------------------------------------------------

## Use Case Name
Cancel time off request

### Overview
- An employee has decided to cancel time off request.

### Pre-Conditions
- An employee has raised a time off request.

### Description
- An employee loads previously raised time off request.
- An employee proceeds to cancel this request.

### Post Conditions
- Systems receives the cancellation request.

### Outcome
- Leave cancellation requestion raised.