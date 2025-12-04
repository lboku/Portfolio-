__Id:__ GB-005

__Title:__ Block Next When PIN Is Incorrect

__Feature__

User Registration

__Scenario:__

Next button does not proceed when an incorrect PIN code is entered

__Description:__ 

**Given** the user is on the Verify Pin Code page

**When** the user enters "000000" in the PIN code field

**And** the PIN does not match the code sent to Email

**Then** the Next button does not work

**And** the system shows an error that the PIN code is incorrect

__Priority:__ high

__Behavior:__ positive

__Type:__ function

__Automation status:__ manual