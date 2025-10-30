1. Create a new branch and push changes:
- git branch --> check current branch
- git checkout -b branch-name --> create and switch to a new branch locally
- git add . --> stage all modified or added files
- git add filename --> stage specific files
- git commit -m "Describe your message" --> commit all staged files
- git push origin your-branch-name --> push branch to remote

2. Remove files from a repo (main or other branch):
- git branch --> check current branch
- git switch branch-name --> switch branch if needed
- remove files manually or with commands
- git add -u --> stage removed files
- git commit -m "Describe your message" --> commit changes
- git push origin your-branch-name --> push changes to remote

3. Switch branches:
- git switch branch-name

To create an app for the main project (BACKEND)

Move to backend directory,
Type command python manage.py startapp app-name,
Then add the newly added app in the "INSTALLED_APPS" in settings.py(Main project)
--------------------- R E M E M B E R ---------------------

Kung maghimo mog new files much better nga ibutang sa ninyu og other branch para di mag conflict sa main,

Kuan pud periodically fetch and pull sa main branch to check sa mga changes and updates,

Always check what branch you are in, if mag directly edit ka sa file/s sa main branch, better nga chat lang sa gc para dili mabuang ang remote repo

Ayaw sad diay og pull og lahos2 fetch and pull jud buhata para makita unsay kalahian sa imoha local og sa remote repo kay nay tendency ma error ehehe

Testing 1, 2, 3 Dev 123
