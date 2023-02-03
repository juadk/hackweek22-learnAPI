![Hackweek10_1](https://user-images.githubusercontent.com/6025636/216646365-38995c61-41bd-4bc7-b543-c966c87b8c3d.png)

# hackweek22-learnAPI

## Goals
1. Keep learning Golang by reading/writing a book about Golang API.

    Feature of the API is to retrieve and manage information about movies, these are endpoints and actions:

        | Actions | URL Pattern               | Action                                          |
        |---------|---------------------------|-------------------------------------------------|
        | GET     | /v1/healthcheck           | Show application health and version information |
        | GET     | /v1/movies                | Show the details of all movies                  |
        | POST    | /v1/movies                | Create a new movie                              |
        | GET     | /v1/movies/:id            | Show the details of a specific movie            |
        | PATCH   | /v1/movies/:id            | Update the details of a specific movie          |
        | DELETE  | /v1/movies/:id            | Delete a specific movie                         |
        | POST    | /v1/users                 | Register a new user                             |
        | PUT     | /v1/users/activated       | Activate a specific user                        |
        | PUT     | /v1/users/password        | Update the password for a specific user         |
        | POST    | /v1/tokens/authentication | Generate a new authentication token             |
        | POST    | /v1/tokens/password-reset | Generate a new password-reset token             |
        | GET     | /debug/vars               | Display applications metrics                    |

2. Add API testing (Cypress / Ginkgo)
   * Build fake DB with data set and load API tests
  
3. Create a UI (next hackweek? :-) )
    * Vue 3 + bootstrap css
