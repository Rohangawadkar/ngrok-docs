---
title: SMTP Mail Servers
---

# Using ngrok with SMTP Mail Servers
------------

The common port for the SMTP protocol used by most mail servers is `25` for insecure traffic and `465` for secure traffic. You can use an ngrok TCP tunnel to connect to a local mail server with the following command.

```bash
ngrok tcp 25
```

