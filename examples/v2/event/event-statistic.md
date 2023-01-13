## Event statistic
### Response format
Report export in **JSON**
### Response structure
| Attribute         | Description                                                                                             | Data type     |
|-------------------|---------------------------------------------------------------------------------------------------------|---------------|
| event_id          | Event ID                                                                                                | int           |
| event_status      | Event status (active, hide)                                                                             | string        |
| event_type        | Event type (offline, online, zoom)                                                                      | string        |
| login             | Login                                                                                                   | string        |
| user_event_status | Event user status (not enrolled, applied, approved, confirm attendance, participated, declined, missed) | string        |
| created_at        | Date of application for participation in the event. Format Y-m-d\TH:i:sP (2020-12-01T15:52:01+03:00)    | string / null |
