
#### Example Response
```json
{
  "enabled": true,
  "options_passthrough": false,
  "cookie_prefix": "",
  "inactivity_timeout": 0,
  "maximum_duration": 0,
  "idp_metadata_url": "",
  "idp_metadata": "\n\u003cEntityDescriptor xmlns=\"urn:oasis:names:tc:SAML:2.0:metadata\" validUntil=\"2020-09-14T12:53:23.691Z\" cacheDuration=\"PT1M\" entityID=\"http://127.0.0.1:12345/metadata\"\u003e\u003cIDPSSODescriptor xmlns=\"urn:oasis:names:tc:SAML:2.0:metadata\" protocolSupportEnumeration=\"urn:oasis:names:tc:SAML:2.0:protocol\"\u003e\u003cNameIDFormat\u003eurn:oasis:names:tc:SAML:2.0:nameid-format:transient\u003c/NameIDFormat\u003e\u003cSingleSignOnService Binding=\"urn:oasis:names:tc:SAML:2.0:bindings:HTTP-Redirect\" Location=\"http://127.0.0.1:12345/sso\"\u003e\u003c/SingleSignOnService\u003e\u003cSingleSignOnService Binding=\"urn:oasis:names:tc:SAML:2.0:bindings:HTTP-POST\" Location=\"http://127.0.0.1:12345/sso\"\u003e\u003c/SingleSignOnService\u003e\u003c/IDPSSODescriptor\u003e\u003c/EntityDescriptor\u003e\n",
  "force_authn": false,
  "allow_idp_initiated": true,
  "authorized_groups": [],
  "entity_id": "https://idp.local-ngrok.com/saml/ec_2PE1VIzThFpSf79wNkPd9n08ep8",
  "assertion_consumer_service_url": "https://idp.local-ngrok.com/saml/ec_2PE1VIzThFpSf79wNkPd9n08ep8/acs",
  "single_logout_url": "https://idp.local-ngrok.com/saml/ec_2PE1VIzThFpSf79wNkPd9n08ep8/slo",
  "request_signing_certificate_pem": "-----BEGIN CERTIFICATE-----\nMIID7DCCAtSgAwIBAgIRAJEfyDp1G+HJ3ScjmGZl3KcwDQYJKoZIhvcNAQELBQAw\ngZQxSDBGBgNVBAoMP2h0dHBzOi8vaWRwLmxvY2FsLW5ncm9rLmNvbS9zYW1sL2Vj\nXzJQRTFWSXpUaEZwU2Y3OXdOa1BkOW4wOGVwODFIMEYGA1UEAww/aHR0cHM6Ly9p\nZHAubG9jYWwtbmdyb2suY29tL3NhbWwvZWNfMlBFMVZJelRoRnBTZjc5d05rUGQ5\nbjA4ZXA4MCAXDTIzMDUwMjA2MDQwOVoYDzIwNTgwNDIzMDYwNDA5WjCBlDFIMEYG\nA1UECgw/aHR0cHM6Ly9pZHAubG9jYWwtbmdyb2suY29tL3NhbWwvZWNfMlBFMVZJ\nelRoRnBTZjc5d05rUGQ5bjA4ZXA4MUgwRgYDVQQDDD9odHRwczovL2lkcC5sb2Nh\nbC1uZ3Jvay5jb20vc2FtbC9lY18yUEUxVkl6VGhGcFNmNzl3TmtQZDluMDhlcDgw\nggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEKAoIBAQC7XUua42y3iMBasEm3ktbH\n4ehdBYj1KP+k4qoUjYUvnbFLM9/qsrU2RCz8liZ5QwXXPSA6bpQwX8zwOH5jColx\niBGaAATxsNo4tJTl/I5vAL+CwHD1/aISJcCN90F2E5FlKsQmbFuCuXoGUOynL733\nTUT9CDExd8+5xVz9IUibMZBT9xewIRo/COBusvxOoR6w+YRDFrpty2egpSVjq0nj\nc03yM6YDvLlYc7dd5EKLcCA+9BOj2rzM+u7Q4TAFK/r4KPNswZ/vSf5AmXxDPXv0\nVk6zSIBTNZg+yaxkrgCRJvL218jGTzPt2idIFzevPcftLzB2vJPiGtQ0xiDXlbKV\nAgMBAAGjNTAzMA4GA1UdDwEB/wQEAwIHgDATBgNVHSUEDDAKBggrBgEFBQcDATAM\nBgNVHRMBAf8EAjAAMA0GCSqGSIb3DQEBCwUAA4IBAQBvJtaM46Zn1Rq9gcoqIqTa\nu/V3nfQwZ78buJ92MHuSMDpaVCMEfnhnT9ltkrGUhRSDWkqTpZdMP9M3dZ29SvJ2\naglD2ja3KUgly+yI5BMIUa/c+enRMRraqZyxOlKoyGX1zQh5pMSifDCr8MK81DlR\n4d6mNOPL9Me9/av3sHXsPqJ4PAkvBRURL+T3Vl8Nk5To4Yan4m61SsPIjBECtcBW\nSF6HJCzzF5XGyPbqp8H9Zq8bgDB4s1g+GwOCc591jzeIqc5JplYfIbivmF74ibmu\nnKRA/ixy4H5KvE5FBz7POOn3junRwRON2zq3KDSQy1i+bRxATnjv/3G184OqRxYl\n-----END CERTIFICATE-----\n",
  "metadata_url": "https://idp.local-ngrok.com/saml/ec_2PE1VIzThFpSf79wNkPd9n08ep8",
  "nameid_format": "urn:oasis:names:tc:SAML:2.0:nameid-format:persistent"
}