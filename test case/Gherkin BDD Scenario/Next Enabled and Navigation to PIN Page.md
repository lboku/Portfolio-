__id:__ DRESSUP-181

__title:__ Next Enabled and Navigation to PIN Page

__Feature__

User Registration

__Scenario:__

Next button becomes active and navigates to the Verify Pin Code page when all fields are filled correctly

__description:__ 

**Given** First Name and Last Name are filled with valid text
**And** Email is filled in a correct email format

**When** the user clicks the Next button
**Then** he system navigates to the "Verify Pin Code" page
**And** exactly 1 request is sent to the backend

__Priority:__ high

__Type:__ function

__automation status:__ manual