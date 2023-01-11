## Task statistic
### Response format
Response format **JSON**

### Response structure
| Attribute  | Description                          | Data type |
|------------|--------------------------------------|-----------|
| task       | Task ID                              | int       |
| login      | Login                                | string    |
| answer     | Answer id                            | int       |
| status     | Status (checking, completed, failed) | string    |
| comment    | User comment                         | string    |
| created_at | Create date                          | string    |
| fields     | Answer list                          | array     |

### Answer list (attrbiute fields)
| Attrbiute | Description | Data type |
|-----------|-------------|-----------|
| id        | Question ID | int       |
| value     | Value       | string    | null |

### Example
[Report](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/tasks/tasks-statistic.json)