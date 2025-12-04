__id:__ GB-009

__title:__ Re-Send Works After Back → Next Return

__Feature__

User Registration

__Scenario:__

Re-Send button works after returning with Back and navigating to PIN page again

__Description:__ 

**Given** the user opens the registration details page
**And** enters valid First Name, Last Name, and Email
**And** clicks the Next button
**And** lands on the "Verify Pin Code" page
**Given** the user is on the Verify Pin Code page again using the same Email
**When** the user clicks the Re-Send button
**Then** the system sends a new PIN code again to the same Email
**And** the UI displays a confirmation 
**that** the code was sent



__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual