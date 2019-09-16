# Certsure Developer Test
Thank you for taking the time to take our developer test. It consists of two parts:
1. A coding test
2. A few technical questions

Please submit your results by uploading the relevant ZIP file to a shared cloud storage folder (Google Drive, Dropbox, OneDrive, etc). Make sure you only send a single zip file named `{yourname}-{role-applied-for}.zip` containing:
- A single markdown file with the answers to the technical questions
- One folder containing the coding test
 
## Coding Test
NICEIC (a brand of Certsure) has a vast number of electrical contractors across the country. We try to make it easier for people requiring work done to make finding a contractor.

For this test you’ll be creating a “Find A Contractor” tool. This tool will accept a postcode input and return a list of contractors nearby. We’re not looking for you to implement correct location lookups, but the list should at least be randomised for each entry.

Returned data should include:
- Company Name
- Address
- Telephone Number
- Email Address
- Approval (One or more of:)
	- Domestic Installer
	- Approved Contractor
	- PAT

*for example:*

| Company Name  | Address          | Telephone Number | Email Address   | Approval           |
|---------------|------------------|------------------|-----------------|--------------------|
| Steve’s Leccy | 50 Pilward Drive | 07000000001      | steve@leccy.com | Domestic Installer |

You can create the application as either a command line application, web application, web API, or mobile application in .NET Framework or .NET Core. Think about the type of work you would be doing at Certsure and choose an appropriate application type.

We’re not looking for a fully finished product, but more the way you approach the challenge and any considerations you have. Refer back to the job spec and try to demonstrate the skills we're looking for.

## Technical Questions
1. How long did you take to complete the coding test? What would you add to your solution if you had more time?
2. What was the most useful feature that was added to the latest version of your chosen platform and technology (e.g. Xamarin/.NET Core)
3. How would you track down an issue in a production environment? Have you ever had to do this?
4. Please describe yourself using JSON