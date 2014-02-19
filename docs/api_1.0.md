bitbucket.org REST API 1.0 Resources
====================================

* ####user
  * profile `/user`
  * priveleges `/user/privileges`
  * follows `/user/follows`
  * repositories 
    * visible `/user/repositories`
    * following `/user/repositories/overview`
    * dashboard `/user/repositories/dashboard`

* ####users
  * account 
    * profile `/users/{accountname}`
    * plan `/users/{accountname}/plan`
    * followers `/users/{accountname}/followers`
    * events `/users/{accountname}/events`
    * consumers `/users/{accountname}/consumers`
      * consumer `/users/{accountname}/consumers/{key_id}`
    * emails `/users/{accountname}/emails`
      * email `/users/{accountname}/emails/{email_address}`
    * invitations `/users/{accountname}/invitations`
      * email `/users/{accountname}/invitations/{email_address}`
        * group `/users/{accountname}/invitations/{email_address}/{group_owner}/{group_slug}`
    * ssh-keys `/users/{accountname}/ssh-keys`
      * key `/users/{accountname}/ssh-keys/{key_id}`
      
* ####groups
  * matching `/groups?{filter}&{filter}*...`
  * account `/groups/{accountname}`
    * group `/groups/{accountname}/{grup_slug}`
      * members `/groups/{accountname}/{group_slug}/members`
        * member `/groups/{accountname}/{group_slug}/members/{membername}`

* ####group-priveleges
  * account `/group-priveleges/{accountname}`
    * repositories `/group-privileges/{accountname}/{group_owner}/{group_slug}`
    * repository `/group-priveleges/{accountname}/{repo_slug}` 
      * group `/group-priveleges/{accountname}/{repo_slug}/{group_owner}/{group_slug}` 

* ####invitations

* ####repositories
 

      
   
  
