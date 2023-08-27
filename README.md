# Aim of Repo
Repo for deploying google cloud function code updates.
A push to main will update the google cloud function cloud-source-repositories-test with the contents in main.py

## How to set up
1. Create main.py with code
2. Push it to a GitHub repo
3. Take Cloud Source Repositories into use in Google console and link it to your GitHub Account
4. Create a **1st gen** Google Cloud Function with the default options , when you come to the "code part":
   
   4.1 Choose Cloud Source Repositories as Source code
   
   4.2 Choose Runtime that suits your code in main.py (here python)
   
   4.3 Let entrypoint be the name of the main function in the main.py file
   
   4.4 In repository, paste the name of the repo in Cloud Source Repositories (not its name in GitHub)
   
   4.5 Fill in the correct branch name from Cloud Source Repositories
   
   4.6 Fill in the correct directory from Cloud Source Repositories
   

