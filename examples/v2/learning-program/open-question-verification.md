## Update open question status
### Error list
| Attribute | Error                                        | Desciption                                                                            |
|-----------|:---------------------------------------------|---------------------------------------------------------------------------------------|
| id        | Attribute is required                        | Attribute is required                                        |
| id        | Answer id does not exist                     | Answer id does not exist                                   |
| id        | Attribute must be string                     | Attribute must be string                                   |
| status    | Attribute is required                        | Attribute is required                                    |
| status    | Unsupported task answer status               | Unsupported task answer status                                           |
| status    | Attribute must be string                     | Attribute must be string                               |
| mark      | Attribute is required                        | Attribute is required                                      |
| mark      | Attribute must be string                     | Attribute must be string                                 |
| mark      | Limit must be no less than <min limit>.      | Limit must be no less than <min limit>  |
| mark      | Limit must be no greater than <max limit>.   | Limit must be no greater than <max limit> |
| comment   | Max length comment is <max limit> characters | Max length comment is <max limit> characters              |
### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/learning-program/open-question-verification.json)