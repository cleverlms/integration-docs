## Poll statistic
### Response format
Report format **JSON**
### Reponse structure
| Attribute | Description                                                           | Data type     |
|-----------|-----------------------------------------------------------------------|---------------|
| id        | Poll ID                                                               | int           |
| login     | Login                                                                 | string        |
| start_at  | Date begin. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00) | string / null |
| end_at    | Date end. Format Y-m-d\TH:i:sP (example, 2020-12-01T15:52:01+03:00)  | string / null |

### [Example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/poll/poll-statistic.json)