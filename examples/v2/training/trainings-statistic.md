## Training statistic
### Response format
Response format **JSON**

### Response structure
| Attribute              | Description                                                                            | Data type     |
|------------------------|----------------------------------------------------------------------------------------|---------------|
| user_id                | User ID                                                                                | int           |
| material_id            | Material ID                                                                            | int           |
| fio                    | User fullname                                                                          | string        |
| user_status            | User status (active, blocked)                                                          | string        |
| login                  | Login                                                                                  | string        |
| start_time             | Begin date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)                  | string / null |
| complete_date          | End date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)                    | string / null |
| total_time             | Passed time. Default value 0.                                                          | int           |
| name                   | Name                                                                                   | string / null |
| is_required            | Mandatory training                                                                     | int           |
| user_scores            | User points                                                                            | int           |
| max_interaction_scores | Max score for interactions                                                             | int           |
| pdf_viewed             | Viewed pdf materials count                                                             | int           |
| pdf_total              | Total number of pdf in the training                                                    | int           |
| link_viewed            | Viewed link materials count                                                            | int           |
| link_total             | Total number of link in the training                                                   | int           |
| html_viewed            | Viewed html materials count                                                            | int           |
| html_total             | Total number of html in the training                                                   | int           |
| scorm_total_time       | Scorm material transit time. Default value null                                        | int / null    |
| scorm_status           | Scorm progress status (completed, not completed, not started, Unknown, passed, failed) | string        |
| scorm_percent          | Percentage of material passing scorm. Default value null                               | int / null    |
| user_final_scores      | The number of points scored for the final test. Default value 0                        | int           |
| max_final_scores       | Maximum points for the final test. Default value 0                                     | int           |
| percent_final_scores   | Final test pass percentage. Default value null                                         | int / null    |
| last_activity          | Last activity date. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)          | string / null |
| current_turn           | Number of the current attempt to pass the final test. Default value null               | int / null    |
| turns_count            | Number of attempts to pass the final test. Default value null                          | int / null    |
| filled_type            | Fill source                                                                            | string / null |
| group_region           | Group region value                                                                     | string        |
| group_city             | Group city value                                                                       | string / null |
| group_role             | Group role value                                                                       | string / null |
| group_position         | Group position value                                                                   | string / null |
| group_team             | Group team value                                                                       | string / null |
| group_department       | Group department value                                                                 | string / null |
| group_function         | Group function value                                                                   | string / null |
| form_question_10       | Form question value                                                                    | string / null |

### Example
[Report](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/training/trainings_statistic.json)