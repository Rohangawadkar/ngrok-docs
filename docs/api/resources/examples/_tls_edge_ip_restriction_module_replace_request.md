
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2PE1W9tRU5fbpHzccgqCUCSNPrF","ipp_2PE1W8w5SVX9KPnnQWOVP04OjA2"]}' \
https://api.ngrok.com/edges/tls/edgtls_2PE1WBUgK0lxHyDfEwbSAdJ5zlS/ip_restriction
