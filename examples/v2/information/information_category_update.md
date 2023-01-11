## Update document category
### Error list
| Attribute   | Error                                       | Description                                                   |
|-------------|:--------------------------------------------|---------------------------------------------------------------|
| id          | Value is required                           | Value is required                |
| status      | Invalid status                              | Invalid status                   |
| name        | Value must be string                        | Value must be string             |
| name        | Value should be at most <max limit> symbols | Value should be at most <max limit> symbols |
| description | Value must be string                        | Value must be string      |
| parent_id   | Parent id does not exist                    | Parent id does not exist                     |
| parent_id   | Parent id is subcategory already            | Parent id is subcategory already        |
### [Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/information/information_category_update.json)