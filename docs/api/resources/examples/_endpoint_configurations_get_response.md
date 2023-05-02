
#### Example Response
```json
{
  "id": "ec_2PE1UYem85IFgdgM7LwnUzXUGhW",
  "type": "https",
  "description": "app servers",
  "created_at": "2023-05-02T06:04:02Z",
  "uri": "https://api.ngrok.com/endpoint_configurations/ec_2PE1UYem85IFgdgM7LwnUzXUGhW",
  "basic_auth": null,
  "circuit_breaker": null,
  "compression": null,
  "request_headers": {
    "enabled": true,
    "add": {
      "x-frontend": "ngrok"
    },
    "remove": [
      "cache-control"
    ]
  },
  "response_headers": null,
  "ip_policy": {
    "enabled": true,
    "ip_policies": [
      {
        "id": "ipp_2PE1UYVgpOykE4cs31CJN71RIiD",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2PE1UYVgpOykE4cs31CJN71RIiD"
      }
    ]
  },
  "mutual_tls": null,
  "tls_termination": null,
  "webhook_validation": null,
  "oauth": null,
  "saml": null,
  "oidc": null,
  "backend": null
}