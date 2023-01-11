## Create document category
### Error list
| Attribute   | Error                            | Description                                                |
|-------------|:---------------------------------|------------------------------------------------------------|
| status      | Invalid status                   | Invalid status                |
| companyId   | Company Id must be an integer.   | Company Id must be an integer |
| language    | Language must be an integer.     | Language must be an integer  |
| description | Value must be string             | Value must be string   |
| parent_id   | Parent id does not exist         | Parent id does not exist                  |
| parent_id   | Parent id is subcategory already | Parent id is subcategory already     |
### [Response example](https://github.com/cleverlms/integration-docs/blob/main/examples/v2/information/information_category_create.json)