

* **Events**


  `GET /users/{accountname}/events`
  

* **Users**

  `GET /users`

  `DELETE /users/{accountname}`
  

* **Plan**

  `GET /users/{accountname}/plan/`
  

* **Ad**

  `DELETE /users/{accountname}/ad/{ad_id}`


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


* **Followers**

  `GET /users/{accountname}/followers`

  

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
