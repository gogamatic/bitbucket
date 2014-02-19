* **User**
  
  `GET /user`

  `GET /user/privileges`
  
  `GET /user/follows`
  
  `GET /user/repositories`
  
  `GET /user/repositories/overview`
  
  `GET /user/repositories/dashboard`

* **Issues**

  `GET /repositories/{accountname}/{repo_slug}/issues`

  `POST /repositories/{accountname}/{repo_slug}/issues`
  
  `GET /repositories/{accountname}/{repo_slug}/issues/{issue_id}`
  
  `PUT /repositories/{accountname}/{repo_slug}/issues/{issue_id}`
  
  `DELETE /repositories/{accountname}/{repo_slug}/issues/{issue_id}`

* **Issue Followers**

  `GET /repositories/{accountname}/{repo_slug}/issues/{issue_id}/followers`

* **Issue Comments**

  `GET /repositories/{accountname}/{repo_slug}/issues/{issue_id}/comments`

  `POST /repositories/{accountname}/{repo_slug}/issues/{issue_id}/comments`
  
  `GET /repositories/{accountname}/{repo_slug}/issues/{issue_id}/comments/{comment_id}`
  
  `PUT /repositories/{accountname}/{repo_slug}/issues/{issue_id}/comments/{comment_id}`

* **Issue Components**

  `GET /repositories/{accountname}/{repo_slug}/issues/components`

  `POST /repositories/{accountname}/{repo_slug}/issues/components`
  
  `GET /repositories/{accountname}/{repo_slug}/issues/components/{object_id}`
  
  `PUT /repositories/{accountname}/{repo_slug}/issues/components/{object_id}`
  
  `DELETE /repositories/{accountname}/{repo_slug}/issues/components/{object_id}`

* **Issue milestones**

  `GET /repositories/{accountname}/{repo_slug}/issues/milestones/`

  `POST /repositories/{accountname}/{repo_slug}/issues/milestones`
  
  `GET /repositories/{accountname}/{repo_slug}/issues/milestones/{object_id}`
  
  `PUT /repositories/{accountname}/{repo_slug}/issues/milestones/{object_id}`
  
  `DELETE /repositories/{accountname}/{repo_slug}/issues/milestones/{object_id}`

* **Issue versions**

  `GET /repositories/{accountname}/{repo_slug}/issues/versions`

  `POST /repositories/{accountname}/{repo_slug}/issues/versions`
  
  `GET /repositories/{accountname}/{repo_slug}/issues/versions/{object_id}`
  
  `PUT /repositories/{accountname}/{repo_slug}/issues/versions/{object_id}`
  
  `DELETE /repositories/{accountname}/{repo_slug}/issues/versions/{object_id}`


* **Repository Tags**

  `GET /repositories/{accountname}/{repo_slug}/tags`

  `GET /repositories/{accountname}/{repo_slug}/branches-tags`


* **Repository Branches**
 
  `GET /repositories/{accountname}/{repo_slug}/branches`


* **Repository Main Branch**
 
  `GET /repositories/{accountname}/{repo_slug}/main-branch`


* **Wiki**
 
  `GET /repositories/{accountname}/{repo_slug}/wiki/{page}`

  `POST /repositories/{accountname}/{repo_slug}/wiki/{page}`
  
  `PUT /repositories/{accountname}/{repo_slug}/wiki/{page}`


* **Changeset Comments**

  `GET /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments`

  `POST /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments`

  `GET /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments/{comment_id}`

  `PUT /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments/{comment_id}`

  `DELETE /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments/{comment_id}`

  `PUT /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/comments/spam/{comment_id}`

* **Changesets**

  `GET /repositories/{accountname}/{repo_slug}/changesets/`

  `GET /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/`

  `GET /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/diffstat`

  `GET /repositories/{accountname}/{repo_slug}/changesets/{raw_node}/diff`

* **Changeset File History**

  `GET /repositories/{accountname}/{repo_slug}/filehistory/{node}/{path}`


* **Pull Request Comments**

  `GET /repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/comments`

  `GET /repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}`

  `POST /repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}`

  `PUT /repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}`

  `DELETE /repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}`

  `PUT /repositories/{accountname}/{repo_slug}/pullrequests/{request_id}/comments/spam/{comment_id}`


* **Change Request Participants**

  `GET /repositories/{accountname}/{repo_slug}/pullrequests/{request_id}/participants/`


* **Revision**

  `GET /repositories/{accountname}/{repo_slug}/src/{revision}/{path}`

  `GET /repositories/{accountname}/{repo_slug}/lines/{revision}/{path}`

  `GET /repositories/{accountname}/{repo_slug}/raw/{revision}/{path}`

  `GET /repositories/{accountname}/{repo_slug}/manifest/{revision}/`


* **Events**

  `GET /repositories/{accountname}/{repo_slug}/events`

  `GET /users/{accountname}/events`

* **Services**

  `GET /repositories/{accountname}/{repo_slug}/services`

  `POST /repositories/{accountname}/{repo_slug}/services`

  `PUT /repositories/{accountname}/{repo_slug}/services/{service_id}`

  `DELETE /repositories/{accountname}/{repo_slug}/services/{service_id}`

* **Repositories**

  `POST /repositories`

  `GET /repositories/`

  `PUT /repositories/{username}/{repo_slug}`

  `DELETE /repositories`


* **Repository Links**

  `GET /repositories/{accountname}/{repo_slug}/links/{link_id}`

  `POST /repositories/{accountname}/{repo_slug}/links`

  `PUT /repositories/{accountname}/{repo_slug}/links/{link_id}`

  `DELETE /repositories/{accountname}/{repo_slug}/links/{link_id}`
  

* **Repository Deploy Keys**

  `GET /repositories/{accountname}/{repo_slug}/deploy-keys`

  `POST /repositories/{accountname}/{repo_slug}/deploy-keys`

  `DELETE /repositories/{accountname}/{repo_slug}/deploy-keys/{key_id}`
  

* **Fork repository**

  `POST /repositories/{accountname}/{repo_slug}/fork`

  `Patch Queue`

  `POST /repositories/{accountname}/{repo_slug}/mq`
  

* **Users**

  `GET /users`

  `DELETE /users/{accountname}`
  

* **Plan**

  `GET /users/{accountname}/plan/`
  

* **Ad**

  `DELETE /users/{accountname}/ad/{ad_id}`
  

* **Group Permissions**

  `GET /group-privileges/{accountname}`

  `GET /group-privileges/{accountname}/{group_owner}/{group_slug}`

  `DELETE /group-privileges/{accountname}/{group_owner}/{group_slug}`

  `GET /group-privileges/{accountname}/{repo_slug}/{group_owner}/{group_slug}`

  `PUT /group-privileges/{accountname}/{repo_slug}/{group_owner}/{group_slug}`

  `DELETE /group-privileges/{accountname}/{repo_slug}/{group_owner}/{group_slug}`
  

* **User Permissions**

  `GET /privileges/{accountname}/{repo_slug}`

  `GET /privileges/{accountname}/{repo_slug}/{privilege_account}`

  `PUT /privileges/{accountname}/{repo_slug}/{privilege_account}`

  `DELETE /privileges/{accountname}/{repo_slug}/{privilege_account}`

  `GET /privileges/{accountname}`

  `DELETE /privileges/{accountname}`
  

* **Team Privileges**

  `GET /users/{accountname}/privileges`

  `GET /users/{accountname}/privileges/{group_owner}/{group_slug}`

  `POST /users/{accountname}/privileges/{group_owner}/{group_slug}`

  `PUT /users/{accountname}/privileges/{group_owner}/{group_slug}`

  `DELETE /users/{accountname}/privileges/{group_owner}/{group_slug}`
  

* **Account Invites**

  `GET /users/{accountname}/invitations`

  `GET /users/{accountname}/invitations/{email}`

  `DELETE /users/{accountname}/invitations/{email}`

  `GET /users/{accountname}/invitations/{email}/{group_owner}/{group_slug}`

  `PUT /users/{accountname}/invitations/{email}/{group_owner}/{group_slug}`

  `DELETE /users/{accountname}/invitations/{email}/{group_owner}/{group_slug}`
  

* **Repository Invites**

  `POST /invitations/{accountname}/{repo_slug}/{email}`


  `Groups`

  `GET /groups`

  `GET /groups/{accountname}`

  `POST /groups/{accountname}`

  `GET /groups/{accountname}/{group_slug}`

  `DELETE /groups/{accountname}/{group_slug}`

  `PUT /groups/{accountname}/{group_slug}`
  

* **Group Members**

  `GET /groups/{accountname}/{group_slug}/members`

  `GET /groups/{accountname}/{group_slug}/members/{member_account}`

  `PUT /groups/{accountname}/{group_slug}/members/{member_account}`

  `DELETE /groups/{accountname}/{group_slug}/members/{member_account}`
  

* **Followers**

  `GET /users/{accountname}/followers`

  `GET /repositories/{accountname}/{repo_slug}/followers`
  

* **Consumer**

  `GET /users/{accountname}/consumers`

  `POST /users/{accountname}/consumers`

  `GET /users/{accountname}/consumers/{key_id}`

  `PUT /users/{accountname}/consumers/{key_id}`

  `DELETE /users/{accountname}/consumers/{key_id}`
  

* **SSH Keys**

  `GET /users/{accountname}/ssh-keys`

  `POST /users/{accountname}/ssh-keys`

  `GET /users/{accountname}/ssh-keys/{key_id}`

  `DELETE /users/{accountname}/ssh-keys/{key_id}`
  

* **Email**

  `GET /users/{accountname}/emails`

  `GET /users/{accountname}/emails/{email}`

  `DELETE /users/{accountname}/emails/{email}`

  `POST /users/{accountname}/emails/{email}`

  `PUT /users/{accountname}/emails/{email}`
