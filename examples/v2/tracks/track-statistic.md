## Learning track statistic
### Response Format
The response is provided in format **JSON**
### Response structure
| Attribute | Description | Value types |
| -------| ----- | ---- |
| id | Learning track id | int |
| name | Learning track name | string |
| max_points | Total points for the learning track | int |
| user_status | User status | string |
| status | Passing status | string |
| start_date | Start date. Value format Y-m-d\TH:i:sP (for example, 2023-12-01T15:52:01+03:00) | string / null |
| active_at | Last active date. Value format Y-m-d\TH:i:sP (for example, 2023-12-02T15:52:01+03:00) | string / null |
| end_at | End date. Value format Y-m-d\TH:i:sP (for example, 2023-12-03T15:52:01+03:00) | string / null |
| passed_at_time | Passed on time | bool / null |
| points | Points | int |
| objects_amount | Objects amount | int |
| objects_passed | Objects passed | int |
| global_progress | Global progress | int |
| progress_in_moment | Progress on moment | int |

### [An example of an error for running tasks of the same type in parallel](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/uniq_task_error.json)
### [Example of a module unavailable error](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/module_unavalible_error.json)
### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/tracks/track-statistic-response.json)