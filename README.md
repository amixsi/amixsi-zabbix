Zabbix library

## Unit tests

We need setup passwords for users:

- **amix** `AMIX_PASS`
- **amix.reports** `AMIX_REPORTS_PASS`
- **amix.api.maintenance** `AMIX_API_MAINTENANCE`

Run tests:

```
AMIX_PASS=... AMIX_REPORTS_PASS=... AMIX_API_MAINTENANCE=... composer test
```
