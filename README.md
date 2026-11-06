# Payunit status

Checks every 5 minutes, from GitHub (outside the server):

| Site | Address |
|---|---|
| Payunit | https://payunit.co/ |
| Merchant API | https://payunit.co/api/v1/health |
| Mobile API | https://api.payunit.co/v1/ping |
| Stores platform | https://stores.payunit.co/login |
| www | https://www.payunit.co/ |

If something stops answering twice in a row, an issue «🔴 Payunit: a site is down» is opened, and GitHub notifies the owner (app and email). When it answers again, the issue gets a comment and is closed.

- **History:** the closed issues.
- **Last check:** `status/last-check.txt`.

Nothing secret is stored here.
