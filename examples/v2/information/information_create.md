## Create documents
### Error list
| Attribute   | Error                     | Description                                                  |
|-------------|:--------------------------|--------------------------------------------------------------|
| companyId   | Attribute is required     | Attribute is required        |
| companyId   | Must be an integer        | Must be an integer   |
| category_id | Attribute is required     | Attribute is required      |
| category_id | Must be an integer        | Must be an integer |
| name        | Attribute is required     | Attribute is required             |
| name        | Must be a string          | Must be a string            |
| type        | Attribute is required     | Attribute is required             |
| type        | Type is invalid.          | Type is invalid                        |
| description | Must be a string          | Must be a string     |
| status      | Attribute is required     | Attribute is required           |
| status      | Status is invalid.        | Status is invalid                      |
| content     | Attribute is required     | Attribute is required          |
| content     | Must be string            | ЗMust be string         |
| content     | Сannot be blank           | Сannot be blank           |
| language    | Limit must be an integer. | Limit must be an integer        |
| file_token  | Must be a string          | Must be a string      |
| image_token | Must be a string          | Must be a string     |
| filename    | Must be a string          | Must be a string        |
### [Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/information/information_create.json)