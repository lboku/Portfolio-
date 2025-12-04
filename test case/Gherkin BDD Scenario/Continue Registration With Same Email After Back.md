__Id:__ GB-006

__Title:__ Continue Registration With Same Email After Back

__Feature__

User Registration

__Scenario:__

Registration continues using the same Email after returning with Back and clicking Next again

__Description:__ 

**Given** the user opens the registration details page

**And** enters valid First Name, Last Name, and Email

**And** clicks the Next button

**And** lands on the "Verify Pin Code" page

**Given** the user returned using the Back button

**When** the user clicks Next again without modifying the fields

**Then** the system navigates to the "Verify Pin Code" page again

**And** the system does not block the Email as already used


__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual