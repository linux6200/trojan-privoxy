# trojan-privoxy

trojan client with privoxy for http proxy

## How to use

```bash
docker run --rm \
--name trojan-proxy \
-e REMOTE_ADDR="remote-host" \
-e REMOTE_PORT="remote-port" \
-e PASSWORD="password" \
-p 36180:1086 \
-p 1087:1087 \
-d \
trojan-privoxy:latest
```
