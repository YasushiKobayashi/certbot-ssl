
### install
`ansible-galaxy install YasushiKobayashi.certbot-ssl`

### ansible role initial setting
- cenos6
- amazone-linux

### vars
```
cerbot:
  - { domein: example.com, email: admin@example.com }
  - { domein: api.example.com, email: admin@example.com }
```
