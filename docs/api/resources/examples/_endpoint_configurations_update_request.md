
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy":{"ip_policy_ids":["ipp_2PE1UYVgpOykE4cs31CJN71RIiD"]}}' \
https://api.ngrok.com/endpoint_configurations/ec_2PE1UYem85IFgdgM7LwnUzXUGhW
