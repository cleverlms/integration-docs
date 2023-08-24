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

### [Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/media/media_create.json)