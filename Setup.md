• Below are the components required in the solution -
	• Copilot Studio
	• Environment Variables
		○ SharePoint Site
		○ SharePoint List (**ProjectSubmission**) to store ProjectDetails
	• Connection references
		○ SharePoint
		○ Word Online
	• Cloud flows
	• Database -> SharePoint
		○ SharePoint Document Library (**ProjectSubmissions**) to store dynamically generated Word documents
		○ Store the ARB document template (**ARB.docx**) in "Documents" library
		○ SharePoint List with these columns -> **ProjectSubmission**
			**Column Name ||	Type**
			Description	|| Multiple lines of text
			Department ||	Single line of text
			Stakeholders	|| Single line of text
			UserCount	|| Number
			Authentication	|| Single line of text
			Technology	|| Single line of text
			PowerPlatformTools	|| Single line of text
			Database	|| Single line of text
			API Integration	|| Single line of text
			DataFeed	|| Single line of text
			Compliance	|| Single line of text
			Auditable	|| Boolean
			ExpectedStartDate	|| Date
			LicenseDetails	|| Single line of text
			Support	|| Single line of text
			Status	|| Choice (Submitted, Under Review, Approved)
• Download the SmartARB zip file from this GitHub repository.
• Go to the Power Apps Maker Portal:  https://make.powerapps.com/
• Ensure you are in a Power Platform environment where you have solution import permissions.
• Navigate to "Solutions".
• Click "Import solution".
• Browse and select the downloaded .zip file.
Click "Next" and then "Import". Wait for the solution import to complete successfully.
