Bitbucket REST API 1.0 Review
=============================

Endpoints and Resources
---------

* user
  * profile `/user`
  * priveleges `/user/privileges`
  * follows `/user/follows`
  * repositories 
    * visible `/user/repositories`
    * following `/user/repositories/overview`
    * dashboard `/user/repositories/dashboard`

* users
  * account 
    * profile `/users/{accountname_or_email}`
    * plan `/users/{accountname}/plan`
    * followers `/users/{accountname}/followers`
    * events `/users/{accountname}/events`
    * consumers `/users/{accountname}/consumers`
    * consumer `/users/{accountname}/consumers/{key_id}`
  
* emails
* invitations
* oauth
* priveleges
* ssh-keys

