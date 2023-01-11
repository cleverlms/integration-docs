## Update documents
### Error list
| Attribute   | Error                         | Description                                                  |
|-------------|:------------------------------|--------------------------------------------------------------|
| id          | Value is required             | Value is required               |
| id          | Information ID does not exist | Information ID does not exist                |
| companyId   | Attribute is required         | Attribute is required        |
| companyId   | Must be an integer            | Must be an integer   |
| category_id | Must be an integer            | Must be an integer |
| category_id | Category ID not exists        | Category ID not exists       |
| category_id | Category must be subcategory  | Category must be subcategory  |
| name        | Must be a string              | Must be a string            |
| type        | Type is invalid.              | Type is invalid                        |
| description | Must be a string              | Must be a string     |
| status      | Status is invalid.            | Status is invalid                      |
| content     | Must be string                | Must be string         |
| content     | Сannot be blank               | Сannot be blank           |
| language    | Limit must be an integer.     | Limit must be an integer        |
| file_token  | Must be a string              | Must be a string      |
| image_token | Must be a string              | Must be a string     |
| filename    | Must be a string              | Must be a string        |
### [Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/information/information_update.json)