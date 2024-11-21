## Exporting a list of user responses to training program test questions
### Errors list
| Attribute      | Error                                                                                            |
|----------------|:-------------------------------------------------------------------------------------------------|
| companyId      | Value is required                                                                                |
| language       | Value is required                                                                                |
| userStatus     | User Status is invalid.                                                                          |
| materialStatus | Material Status is invalid.                                                                      |
| filters        | Filter question is required                                                                      |
| filters        | Filter with_reset must be boolean                                                                |
| filters        | Filter question must be array                                                                    |
| filters        | Filter question has not integer elements                                                         |
| filters        | Filter question elements count is greater <max limit>                                            |
| filters        | Filter login elements count is greater <max limit>                                               |
| filters        | Filter question_type must be array                                                               |
| filters        | Filter question_type has not string elements                                                     |
| filters        | Filter question_type has not valid type. Allowed types: mcq, select-image, open-question         |
| filters        | Filter answer_status must be array                                                               |
| filters        | Filter answer_status has not string elements                                                     |
| filters        | Filter answer_status has not valid status. Allowed statuses: success, fail, checking, not_answer |
| afterDate      | Invalid value format. Valid Y-m-d\TH:i:sP                                                        |
| toDate         | Invalid value format. Valid Y-m-d\TH:i:sP                                                        |
