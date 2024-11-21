## Learning program statistic
### Response format
Repost format **JSON**

### Response structure
| Attribute  | Description                     | Data type     |
|------------|---------------------------------|---------------|
| id         | Learning program ID             | int           |
| name       | Learning program name           | string / null |
| deadline_type | Deadline type                   | string / null|
| deadline_at | Deadline value in unixtime      | int / null|
| deadline_period_at | Deadline type period            | string / null|
| points     | Maximum points                  | int           |
| materials  | Learning program structure      | array         |
| statistics | Learning program user statistic | array         |

### Learning program structure (attribute materials)
| Attribute | Description              | Data type |
|-----------|--------------------------|-----------|
| pdf       | Count materials PDF      | int       |
| scorm     | Count materials SCORM    | int       |
| link      | Count materials LINK     | int       |
| html      | Count materials HTML     | int       |
| test      | Count materials TEST     | int       |
| video     | Count materials VIDEO    | int       |
| longread  | Count materials LONGREAD | int       |
| document  | Count materials DOCUMENT | int       |
| total     | Total materials          | int       |

### Learning program user statistic (attribute statistics)
| Attribute      | Description                                                                                       | Типы значений  |
|----------------|---------------------------------------------------------------------------------------------------|----------------|
| login          | Login                                                                                             | string         |
| user_status    | Login status (active, blocked)                                                                    | string         |
| program_status | User status in learning program (appointed, in_progress, completed, checking, fail)               | string         |
| progress       | User progress                                                                                     | int            |
| points         | User points                                                                                       | int / null     |
| start_at       | Start date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)                             | string / null  |
| active_at      | Last activity date in learning program. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00) | string / null  |
| end_at         | End date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)                               | string / null  |
| deadline_at         | Deadline date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)                          | string / null  |
| passed_at_time | Passed at time flag                                                                               | boolean / null |
| pdf            | Count passed materials PDF                                                                        | int            |
| scorm          | Count passed materials SCORM                                                                      | int            |
| link           | Count passed materials LINK                                                                       | int            |
| html           | Count passed materials HTML                                                                       | int            |
| test           | Count passed materials TEST                                                                       | int            |
| video          | Count passed materials VIDEO                                                                      | int            |
| longread       | Count passed materials LONGREAD                                                                   | int            |
| document       | Count passed materials DOCUMENT                                                                   | int            |

### Example
[Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/learning-program/learning-program-statistic-response.json)