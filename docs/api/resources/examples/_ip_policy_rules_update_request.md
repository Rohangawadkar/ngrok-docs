
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"cidr":"212.3.15.0/24"}' \
https://api.ngrok.com/ip_policy_rules/ipr_2PE1VDbEWg5gn3uhpXz8scepHAM
