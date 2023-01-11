## Export user answers on test questions
### Error list
| Attribute      | Error                                                                                            | Description                                                                              |
|----------------|:-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| companyId      | Value is required                                                                                | Value is required                                    |
| language       | Value is required                                                                                | Value is required                                    |
| userStatus     | User Status is invalid.                                                                          | User Status is invalid                                              |
| materialStatus | Material Status is invalid.                                                                      | Material Status is invalid                                          |
| filters        | Filter question is required                                                                      | Filter question is required                                       |
| filters        | Filter with_reset must be boolean                                                                | Filter with_reset must be boolean               |
| filters        | Filter question must be array                                                                    | Filter question must be array                                       |
| filters        | Filter question has not integer elements                                                         | Filter question has not integer elements                  |
| filters        | Filter question elements count is greater <max limit>                                            | Filter question elements count is greater <max limit> |
| filters        | Filter login elements count is greater <max limit>                                               | Filter login elements count is greater <max limit>    |
| filters        | Filter question_type must be array                                                               | Filter question_type must be array                      |
| filters        | Filter question_type has not string elements                                                     | Filter question_type has not string elements             |
| filters        | Filter question_type has not valid type. Allowed types: mcq, select-image, open-question         | Filter question_type has not valid type. Allowed types: mcq, select-image, open-question                                                                                         |
| filters        | Filter answer_status must be array                                                               | Filter answer_status must be array                     |
| filters        | Filter answer_status has not string elements                                                     | Filter answer_status has not string elements             |
| filters        | Filter answer_status has not valid status. Allowed statuses: success, fail, checking, not_answer | Filter answer_status has not valid status. Allowed statuses: success, fail, checking, not_answer                 |
| afterDate      | Invalid value format. Valid Y-m-d\TH:i:sP                                                        | Invalid value format. Valid Y-m-d\TH:i:sP                                                 |
| toDate         | Invalid value format. Valid Y-m-d\TH:i:sP                                                        | Invalid value format. Valid Y-m-d\TH:i:sP                                                    |