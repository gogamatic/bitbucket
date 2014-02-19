Bitbucket REST API 1.0 Structure
================================

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
    * profile `/users/{accountname}`
    * plan `/users/{accountname}/plan`
    * followers `/users/{accountname}/followers`
    * events `/users/{accountname}/events`
    * consumers `/users/{accountname}/consumers`
      * consumer `/users/{accountname}/consumers/{key_id}`
    * emails `/users/{accountname}/emails`
      * address `/users/{accountname}/emails/{email_address}`
  
* emails
* invitations
* oauth
* priveleges
* ssh-keys


* User
  * profile `/user`
  * priveleges `/user/priveleges`
  * follows `/user/follows`
  * repositories `/user/repositories`
    * following `/user/repositories/follows`
  * repositories `/user/repositories/overview`
  * dashboard `/user/repositories/dashboard`
  * following `/user/repositories/following`

* Users
  * account
