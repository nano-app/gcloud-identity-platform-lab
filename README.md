# gcloud-identity-platform-lab

## Intro
  - Using gcloud 'Identity Platform' with sample provider is email/password (manual add) as a credential db
  - Write some web code to authen a user/password (hard code) against the above ID service

## Main steps:
  - Enable gcloud 'Identity Platform'
  - Enable 'Identity Toolkit API' lib/api
  - Add new Provider = 'Email/password'
     - create new user (any email/password)
     - Go to 'Application setup detail' for sample code with API key
  
  @ Cloud shell (quick dev env.)
  
  - Sample index.hml with API call authenticate a hard code credential (user name), password
  - Run the web: 
        # python -m http.server 8080
