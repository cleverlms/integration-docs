## Material statistic
### Response format
Report format **JSON**

### Response structure
| Attribute  | Description                                         | Data type     |
|------------|-----------------------------------------------------|---------------|
| id         | Material ID                                         | int           |
| name       | Material name (company locale)                      | string / null |
| type       | Material type (pdf, scorm, link, html, test, video) | string / null |
| points     | Max points (if no points, then null)                | int / null    |
| statistics | User statistic                                      | array         |

### User statistic (attribute statistics)
| Attribute       | Description                                                                   | Data type     |
|-----------------|-------------------------------------------------------------------------------|---------------|
| login           | Login                                                                         | string        |
| user_status     | User status (active, blocked)                                                 | string        |
| material_status | User status in material (appointed, in_progress, completed, checking, fail)   | string        |
| points          | User points                                                                   | int / null    |
| progress        | User progress                                                                 | int           |
| start_at        | Date begin. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)         | string / null |
| end_at          | Date end. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)           | string / null |
| update_at       | Date last activity. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00) | string / null |

### Example
[Report](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/learning-program/materials_statistic.json)