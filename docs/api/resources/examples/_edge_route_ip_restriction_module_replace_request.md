
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2PE1Vga4o9zoINyzIYYjfoN7ASh","ipp_2PE1VdwBqLyzOqtZFGf1XHthVqK"]}' \
https://api.ngrok.com/edges/https/edghts_2PE1Var9mP6e5G9Ku3Nt0kCUPlV/routes/edghtsrt_2PE1VZkQPlj0ROu7d0knYYGc9Ry/ip_restriction
