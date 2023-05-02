
#### Example Request
```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"type":"dashboard","ip_policy_ids":["ipp_2PE1VOz0JKOgT1TvOTG6wX0MqT0"]}' \
https://api.ngrok.com/ip_restrictions
