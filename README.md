# XOps Status Page

[![Uptime CI](https://github.com/basel5001/upptime-status/actions/workflows/uptime.yml/badge.svg)](https://github.com/basel5001/upptime-status/actions/workflows/uptime.yml)

Automated uptime monitoring and status page powered by [Upptime](https://upptime.js.org/).

## Monitored Services

| Service | URL | Status |
|---------|-----|--------|
| Portfolio | https://basel5001.github.io | Live |
| GitHub Profile | https://github.com/basel5001 | Live |
| Google DNS | https://dns.google | Live |

## How It Works

- GitHub Actions checks each URL every 5 minutes
- Response time data collected daily
- Status page auto-generated and deployed to GitHub Pages
- Incidents tracked via GitHub Issues

## Adding a Service

Edit `.upptimerc.yml` and add under `sites:`:

```yaml
- name: My Service
  url: https://example.com
  expectedStatusCodes: [200]
```

## License

MIT
