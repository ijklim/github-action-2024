# Testing GitHub Action

* Must create Personal Access Token (PAT)
* Must create secret in the repo for created PAT

# Generate Personal Access Token on GitHub

1. Log in to your GitHub account.
1. Click on your profile picture in the top-right corner of the page.
1. From the dropdown menu, select "Settings".
1. In the left sidebar, scroll down and click on "Developer settings".
1. In the new left sidebar, click on "Personal access tokens".
1. Click on "Tokens (classic)" if you want to create a classic token, or "Fine-grained tokens" for more granular control.
1. Click on "Generate new token" (for classic) or "Generate new token (classic)" (for fine-grained).
1. Give your token a descriptive name in the "Note" field.
1. Set an expiration date for your token (recommended for security).
1. Select the scopes or permissions you want to grant this token. Be careful to only select what you need.
1. Scroll to the bottom and click "Generate token".
1. Your new personal access token will be displayed. Make sure to copy it immediately and store it securely, as you won't be able to see it again.

# Create Repository secret

1. Access Repository
1. Select the Settings tab
1. In the left sidebar, scroll down and click on "Secrets and variables", then "Actions".
1. Click on "New repository secret" in the "Repository secrets" section
1. Name the secret "PERSONAL_ACCESS_TOKEN" , and paste in the token from the task "Generate Personal Access Token on GitHub"
1. Click "Add secret"
