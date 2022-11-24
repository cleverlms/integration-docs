## Rename users
### List errors
| Attribute | Error                                        | Description                                                               |
|-----------|:---------------------------------------------|---------------------------------------------------------------------------|
| from      | Value is required                            | Value is required                          |
| from      | Value must be string                         | Value must be string                            |
| from      | Value should be at most <max limit> symbols  | Value should be at most <max limit> symbols                        |
| from      | Value should be at least <min limit> symbols | Value should be at least <min limit> symbols                             |
| from      | Login not exists                             | Login not exists |
| to        | Value is required                            | Value is required                            |
| to        | Value must be string                         | Value must be string                              |
| to        | Value should be at most <max limit> symbols  | Value should be at most <max limit> symbols                        |
| to        | Value should be at least <min limit> symbols | Value should be at least <min limit> symbols                             |
| to        | Bad login format                             | Bad login format                  |
| to        | Login is already exists                      | Login is already exists  |

### [Example response](https://github.com/cleverlms/integration-docs/blob/main/examples/v3/user/login_rename.json)