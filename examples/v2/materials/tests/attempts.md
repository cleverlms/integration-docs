## Export test user attempts
### Response format
Repost format **JSON**

### Response structure
| Attribute   | Description                                                                   | Data type     |
|-------------|-------------------------------------------------------------------------------|---------------|
| id          | Attempts ID                                                                   | string        |
| material_id | Material ID                                                                   | string        |
| login       | Login                                                                         | string        |
| status      | Attempt status (fail, completed, checking)                                    | string        |
| number      | Attempt sequence                                                              | int / null    |
| points      | Attempt points                                                                | int           |
| percent     | Attempts success percent                                                      | int           |
| q_count     | Total attempts                                                                | int           |
| q_success   | Success attempt count                                                         | int           |
| q_fail      | Failed attempt count                                                          | int           |
| q_checking  | Checking attempts count                                                       | int           |
| started_at  | Start attempt timestamp. Format Y-m-d\TH:i:sP (ex, 2020-12-01T15:52:01+03:00) | string        |
| ended_at    | End attempt timestamp. Format Y-m-d\TH:i:sP (ex, 2020-12-01T15:52:01+03:00)   | string / null |
| created_at  | Create row timestamp. Format Y-m-d\TH:i:sP (ex, 2020-12-01T15:52:01+03:00)    | string        |
| updated_at  | Update row timestamp. Format Y-m-d\TH:i:sP (ex, 2020-12-01T15:52:01+03:00)    | string        |

### Example
[Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/materials/tests/attempts.json)