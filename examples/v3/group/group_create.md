## Create errors
### List errors
| Attribute   | Error                            | Description                      |
|-------------|:---------------------------------|----------------------------------|
| id          | Attribute is required            | Attribute is required            |
| id          | Must be an integer               | Must be an integer               |
| parent_id   | Attribute is required            | Attribute is required            |
| parent_id   | Must be an integer               | Must be an integer               |
| name        | Attribute is required            | Attribute is required            |
| name        | Must be a string                 | Must be a string                 |
| name        | Cannot be empty                  | Cannot be empty                  |
| name        | Must be less than 255 characters | Must be less than 255 characters |
| name        | Contains invalid characters      | Contains invalid characters      |
| external_id | Must be a string                 | Must be a string                 |
| external_id | Cannot be empty                  | Cannot be empty                  |
| external_id | Must be less than 255 characters | Must be less than 255 characters |