__id:__ DRESSUP-181

__title:__ Accept Correct PIN and Complete Registration

__Feature__

User Registration

__Scenario:__

Correct PIN code allows the user to proceed to the success page

__description:__ 

**Given** the user is on the Verify Pin Code page
**When** the user enters the correct PIN code
**And** clicks the Next button
**Then** the registration completes successfully
**And** the user is redirected to the Welcome/Success page

__Priority:__ high

__Behavior:__ positive

__Type:__ function

__automation status:__ manual