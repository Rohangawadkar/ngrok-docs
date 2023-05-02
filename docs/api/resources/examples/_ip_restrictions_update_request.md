
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy_ids":["ipp_2PE1VOz0JKOgT1TvOTG6wX0MqT0","ipp_2PE1VM2roG6znWurcaXJN8suHEz"]}' \
https://api.ngrok.com/ip_restrictions/ipx_2PE1VLPSfIVBEVwA3tUGGL5gesV
