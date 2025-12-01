__id:__ DRESSUP-181

__title:__ Clicking the Sign Up button 

__Feature__

User Registration

__Scenario:__

The indicator icon turns red when an invalid email format is entered

__description:__ 

**Given** the user is on the personal details registration page
**And** the "Sign Up" button is visible
**When** the user enters "invalid-email" in the Email field
**Then** the email indicator icon turns red
**And** the system marks the Email as invalid

__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__automation status:__ manual