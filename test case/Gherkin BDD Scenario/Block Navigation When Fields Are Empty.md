__id:__ DRESSUP-181

__title:__ Block Navigation When Fields Are Empty

__Feature__

User Registration

__Scenario:__

Registration is blocked when all fields are empty

__description:__ 

**Given** all fields are empty
**When** the user clicks the Next button
**Then** he system does not navigate to the next page
**And** And all empty fields are marked as errors


__Priority:__ high

__Type:__ function

__automation status:__ manual