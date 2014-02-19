Bitbucket REST API 1.0 Review
=============================

Endpoints
---------

* user


### User endpoint resources

* profile `/user`
* priveleges `/user/privileges`
* follows `/user/follows`
* repositories `/user/repositories`
 * following `/user/repositories/overview`
 * dashboard `/user/repositories/dashboard`

### Users endpoint resources

* account 
  * profile `/users/{accountname_or_email}`
  * plan `/users/{accountname}/plan`
  * followers `/users/{accountname}/followers`
  * events `/users/{accountname}/events`
  * consumers `/users/{accountname}/consumers`
    * consumer `/users/{accountname}/{id}`
  
* emails
* invitations
* oauth
* priveleges
* ssh-keys

