# github-branch-protection-rules
This is a python script to loop through all your repos from your API token and update review counts and enforce admins off the master branch

# Creating this to mass update all of our repos settings.

# First you need to create a personal token (this way the script will know what access you have to repos).
# https://github.com/settings/tokens
# I gave it all access except to delete repos, well because I don't want that power in any PythonScripts

# Uses https://github.com/PyGithub/PyGithub
