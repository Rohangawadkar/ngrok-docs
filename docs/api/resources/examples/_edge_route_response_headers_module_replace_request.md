
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"Content-Security-Policy":"script-src 'self'","X-Frame-Options":"DENY"}}' \
https://api.ngrok.com/edges/https/edghts_2PE1Vu0hyHDbcxGyHiHPl31nRST/routes/edghtsrt_2PE1VuVzggeF7ve3N03DhaO6d7O/response_headers
