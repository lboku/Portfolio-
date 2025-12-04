__Id:__ GB-003

__Title:__ Clicking the Sign Up button 

__Feature__

User Registration

__Scenario:__

Registration is blocked when using an already registered email

__description:__ 

**Given** the Email already exists in the database

**When** the user clicks the Next button

**Then** he system shows an error that the Email is already in use

**And** the system does not navigate to the next page

__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual