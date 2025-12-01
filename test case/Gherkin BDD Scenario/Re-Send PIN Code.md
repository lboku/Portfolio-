__id:__ DRESSUP-181

__title:__ Re-Send PIN Code

__Feature__

User Registration

__Scenario:__

Clicking the Re-Send button sends the PIN code again to Email

__description:__ 

**Given** the user is on the Verify Pin Code page
**When** the user clicks the Re-Send button
**Then** he system sends a new PIN code to the same Email
**And** the UI displays a confirmation message that the code was sent

__Priority:__ high

__Behavior:__ positive

__Type:__ function

__automation status:__ manual