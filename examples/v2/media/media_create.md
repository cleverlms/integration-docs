## Create media material
### Error list
| Attribute      | Error                 | Description           |
|----------------|:----------------------|-----------------------|
| category_id    | Attribute is required | Attribute is required |
| category_id    | Must be an integer    | Must be an integer    |
| name           | Attribute is required | Attribute is required |
| name           | Must be a string      | Must be a string      |
| description    | Must be a string      | Must be a string      |
| status         | Attribute is required | Attribute is required |
| status         | Status is invalid     | Status is invalid     |
| image_token    | Must be a string      | Must be a string      |
| video_sd_token | Must be a string      | Must be a string      |
| video_hd_token | Must be a string      | Must be a string      |

### [An example of an error for running tasks of the same type in parallel](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/uniq_task_error.json)
### [Example of a module unavailable error](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/module_unavalible_error.json)
### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/media/media_create.json)