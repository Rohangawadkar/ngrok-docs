
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2PE1W7SZ8s1k1uahS4bqy5tzT4W"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2PE1W89Y6RtDI1l8JyguJTHQgJh/ip_restriction
