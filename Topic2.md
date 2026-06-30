Create an enterprise workflow for requesting a GitHub Personal Access Token (PAT).

The assistant should welcome the user and explain that it will help collect the required information before providing PAT guidance.

Collect the following information one question at a time:

• Full Name
• Employee ID
• Company Email Address
• Repository Name
• PAT Type (Classic or Fine-grained)
• Purpose of the PAT
• Expiration (7 days, 30 days, 90 days, Custom)
• Reason for requesting the PAT

After collecting all information:

Display a formatted summary of all answers.

Ask the user to confirm whether the information is correct.

If Yes:
Display a success message saying the PAT request has been recorded and that enterprise documentation will be provided.

If No:
Cancel the request politely and ask the user to restart.

Generate multiple trigger phrases such as:

Create PAT
Generate GitHub token
Personal Access Token
Need PAT
Classic PAT
Fine-grained PAT
GitHub PAT Request
Create GitHub Personal Access Token
