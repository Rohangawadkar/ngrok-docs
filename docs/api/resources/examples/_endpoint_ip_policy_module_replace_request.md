
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy_ids":["ipp_2PE1VMFtPN6VKlsF0RRHu7zo66U"]}' \
https://api.ngrok.com/endpoint_configurations/ec_2PE1VIzThFpSf79wNkPd9n08ep8/ip_policy
