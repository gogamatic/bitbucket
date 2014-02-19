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

* **Patch Queue**

  `POST /repositories/{accountname}/{repo_slug}/mq`
  
* **Followers**

  `GET /repositories/{accountname}/{repo_slug}/followers`
