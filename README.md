[![Build Status](https://travis-ci.org/YasushiKobayashi/certbot-ssl.svg?branch=master)](https://travis-ci.org/YasushiKobayashi/certbot-ssl)
[![Run Status](https://api.shippable.com/projects/59760b63343b2007000c4e07/badge?branch=master)](https://app.shippable.com/github/YasushiKobayashi/certbot-ssl)
[![Coverage Badge](https://api.shippable.com/projects/59760b63343b2007000c4e07/coverageBadge?branch=master)](https://app.shippable.com/github/YasushiKobayashi/certbot-ssl)

### install
`ansible-galaxy install YasushiKobayashi.certbot-ssl`

### ansible role initial setting
- cenos6
- amazone-linux

### vars
```
cerbot:
  - { domain: example.com, email: admin@example.com }
  - { domain: api.example.com, email: admin@example.com }
```
