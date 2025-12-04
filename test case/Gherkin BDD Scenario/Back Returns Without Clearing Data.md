__Id:__ GB-002

__Title:__ Back Returns Without Clearing Data

__Feature__

User Registration

__Scenario:__

Back button returns to the previous page without clearing entered data

__Description:__ 

**Given** the user opens the registration details page

**And** enters valid First Name, Last Name, and Email

**And** clicks the Next button

**And** lands on the "Verify Pin Code" page

**When** the user clicks the Back button

**Then** the system navigates back to the First Name/Last Name/Email page

**And** all previously entered values remain filled


__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual