__Id:__ GB-006

__Title:__ Clicking the Sign Up button 

__Feature__

User Registration

__Scenario:__

The indicator icon turns red when an invalid email format is entered

__Description:__ 

**Given** the user is on the personal details registration page

**And** the "Sign Up" button is visible

**When** the user enters "invalid-email" in the Email field

**Then** the email indicator icon turns red

**And** the system marks the Email as invalid

__Priority:__ medium

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual