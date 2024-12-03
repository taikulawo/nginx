# Nginx test

## HTTP/3

```bash
SSLKEYLOGFILE=key.log curl --http3 https://localhost:443 --resolve localhost:443:127.0.0.1 -vk
SSLKEYLOGFILE=key.log curl --http3 https://www.example.org:443 --resolve www.example.org:443:127.0.0.1 -vk
```