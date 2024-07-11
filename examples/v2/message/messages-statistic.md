## Messages statistic
### Response Format
The response is provided in format **JSON**
### Response structure
| Attribute | Description | Value types |
| -------| ----- | ---- |
| message_id | Message id | int |
| login | User login | string |
| viewed_at | Date the message was viewed. Value format Y-m-d\TH:i:sP (for example, 2023-12-01T15:52:01+03:00) | string / null |

### [An example of an error for running tasks of the same type in parallel](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/uniq_task_error.json)
### [Example of a module unavailable error](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/module_unavalible_error.json)
### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/message/messages-statistic.json)