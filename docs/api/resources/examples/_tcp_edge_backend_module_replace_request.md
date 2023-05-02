
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"backend_id":"bkdtg_2PE1VxL8HaZGlxb6a7YD6TzE7AJ"}' \
https://api.ngrok.com/edges/tcp/edgtcp_2PE1W1atJrvkvqBiI4q665VtU8r/backend
