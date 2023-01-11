## Export user poll answers
### Response format
Response format **JSON**
### Response structure
| Attribute   | Description                       | Data type     |
|-------------|-----------------------------------|---------------|
| question_id | Question ID                       | int           |
| login       | Login                             | string        |
| answers     | Answers list. Empty if no answers | array         |
| comment     | User comment                      | string / null |

### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/poll/poll-user-answers.json)