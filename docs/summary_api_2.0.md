* **Branch restriction**

  `GET repositories/{accountname}/{repo_slug}/branch-restrictions`

  `POST repositories/{accountname}/{repo_slug}/branch-restrictions`

  `GET repositories/{accountname}/{repo_slug}/branch-restrictions/{id}`

  `PUT repositories/{accountname}/{repo_slug}/branch-restrictions/{id}`

  `DELETE repositories/{accountname}/{repo_slug}/branch-restrictions/{id}`


* **Pull Requests**

  `GET repositories/{owner}/{repo_slug}/pullrequests`

  `POST repositories/{owner}/{repo_slug}/pullrequests`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}`

  `PUT repositories/{owner}/{repo_slug}/pullrequests/{id}`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}`

  `GET repositories/{owner}/{repo_slug}/pullrequests/activity`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/activity`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/commits`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/patch`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/diff`

  `POST repositories/{owner}/{repo_slug}/pullrequests/{id}/merge`

  `POST repositories/{owner}/{repo_slug}/pullrequests/{id}/decline`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/comments`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/comments/{comment_id}`

  `GET repositories/{owner}/{repo_slug}/pullrequests/{id}/approvals`

  `POST repositories/{owner}/{repo_slug}/pullrequests/{id}/approve`

  `DELETE repositories/{owner}/{repo_slug}/pullrequests/{id}/approve`


* **Pull Request Changeset**

  `GET repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/changesets`

  `POST repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/changesets/{approver}`

  `GET repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/changesets/{approver}`

  `DELETE repositories/{accountname}/{repo_slug}/pullrequests/{pull_request_id}/changesets/{approver}`


* **Teams**

  `GET teams/{teamname}`

  `GET teams/{teamname}/members`

  `GET teams/{teamname}/followers`

  `GET teams/{teamname}/following`

  `GET teams/{teamname}/repositories`


* **Users**

  `GET users/{username}`

  `GET users/{username}/followers`

  `GET users/{username}/following`

  `GET users/{username}/repositories`


* **Repositories**

  `GET repositories`

  `GET repositories/{owner}`

  `GET repositories/{owner}/{repo_slug}`

  `POST repositories/{owner}/{repo_slug}`

  `DELETE repositories/{owner}/{repo_slug}`

  `GET repositories/{owner}/{repo_slug}/forks`

  `GET repositories/{owner}/{repo_slug}/watchers`


* **Differences or patches**

  `GET repositories/{owner}/{repo_slug}/diff/{spec}`

  `GET repositories/{owner}/{repo_slug}/patch/{spec}`


* **Commit or Commits**

  `GET repositories/{owner}/{repo_slug}/commits`

  `GET repositories/{owner}/{repo_slug}/commits/{revision}`

  `POST repositories/{owner}/{repo_slug}/commits/{revision}`

  `GET repositories/{owner}/{repo_slug}/commit/{revision}`

  `GET repositories/{owner}/{repo_slug}/commit/{revision}/comments`

  `GET repositories/{owner}/{repo_slug}/commit/{revision}/comments/{comment_id}`
