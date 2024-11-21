## Exporting a list of user responses to training program test questions
### Response structure
| Attribute      | Description                                                            | Типы значений |
|----------------|------------------------------------------------------------------------|---------------|
| id             | Answer ID                                                              | string        |
| attempt_id     | Attempt ID                                                             | string        |
| attempt_number | Attempt number                                                         | int / null    |
| material_id    | Material ID                                                            | int           |
| question_id    | Question ID                                                            | int           |
| question_type  | Question type                                                          | string        |
| login          | Login                                                                  | string        |
| status         | Answer status                                                          | string        |
| score          | Points value                                                           | int           |
| text           | User answer for open question                                          | string / null |
| created_at     | Create timestamp. Format Y-m-d\TH:i:sP (ex, 2020-12-01T15:52:01+03:00) | string        |
| answers        | Answer ID list                                                         | array         |
