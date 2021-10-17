## Access cscli

```
docker run --rm --entrypoint /usr/local/bin/cscli -v  crowdsec_crowdsec-config:/etc/crowdsec/:ro -e DISABLE_ONLINE_API=true -e DISABLE_AGENT=true crowdsecurity/crowdsec:latest
```
