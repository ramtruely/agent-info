Create an enterprise workflow for requesting a GitHub Repository Secret.

The agent should help a user request creation of a GitHub Secret used by GitHub Actions or CI/CD pipelines.

Ask the following questions one by one:

• Full Name
• Employee ID
• Company Email
• Repository Name
• Secret Name
• Secret Purpose (do not ask for the secret value)
• Business Justification

Display all collected information in a summary card.

Ask the user to confirm the request.

If confirmed,
call a placeholder action that represents sending the request to DevOps through Power Automate.

Display a success message informing the user that the request has been recorded.

If rejected,
cancel the request politely.

Generate suitable trigger phrases for GitHub Secret requests.
