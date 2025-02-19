swagger: '2.0'
info:
  title: Classic API Resource Documentation
  description: |
     <h1>asd123</h1>

  version: production
basePath: /JSSResource/
produces:
  - application/xml
  - application/json
consumes:
  - application/xml
  - application/json
security:
  - basicAuth: []
paths:
  /accounts:
    get:
      responses:
        '200':
          description: No response was specified
      tags:
        - accounts
      operationId: findAccounts
      summary: Finds all accounts
  '/accounts/groupid/{id}':
    delete:
      parameters:
        - description: |
            <h1>asd123</h1>

          format: int64
          in: path
          name: id
          required: true
          type: integer
      responses:
        '200':
          description: No response was specified
      tags:
        - accounts
      operationId: deleteGroupById
      summary: Deletes a group by id
