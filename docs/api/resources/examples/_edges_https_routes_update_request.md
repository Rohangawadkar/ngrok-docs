
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"environment\": \"production\"}"}' \
https://api.ngrok.com/edges/https/edghts_2PE1VXDpixyFr4zqWeHwwfx3Lq8/routes/edghtsrt_2PE1VTEkkeP9GwkUPJZuNiWU9X6
