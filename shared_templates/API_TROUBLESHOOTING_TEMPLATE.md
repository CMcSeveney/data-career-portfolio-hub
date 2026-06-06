# API Troubleshooting Template

## API Summary
| Item | Details |
|---|---|
| API name | Add API name |
| Endpoint | Add endpoint path only, not private full URL |
| Method | GET / POST / PUT / PATCH / DELETE |
| Authentication type | None / API key / Bearer token / OAuth |
| Tool used | Postman / Bruno / Python requests |

## Privacy Reminder
Do not include real API keys, bearer tokens, passwords, private URLs, customer identifiers or internal request payloads.

## Request Details
### Method
```text
GET
```

### Endpoint
```text
/api/example-endpoint
```

### Headers
```json
{
  "Authorization": "Bearer REDACTED_TOKEN",
  "Content-Type": "application/json"
}
```

## Status Code Interpretation
| Status Code | Meaning | Likely Cause | Next Step |
|---|---|---|---|
| 200 | Success | Request worked | Validate returned data |
| 400 | Bad request | Invalid payload or parameter | Check request body and required fields |
| 401 | Unauthorised | Missing or invalid authentication | Check token/API key |
| 403 | Forbidden | Authenticated but lacks permission | Check permissions or role |
| 404 | Not found | Endpoint or resource does not exist | Check URL and resource ID |
| 429 | Too many requests | Rate limit exceeded | Retry later or reduce request frequency |
| 500 | Server error | Server-side failure | Capture evidence and escalate |

## Developer-Ready Summary
```text
Issue:
Endpoint:
Method:
Status code:
Expected result:
Actual result:
Steps to reproduce:
Evidence:
```
