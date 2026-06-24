# openbank-bian

Project home & explainer for **openbank-bian** — a runnable reference implementation of UK Open Banking (OBIE) rebuilt as **BIAN-style microservices in Go**.

**Live site:** https://sreenivas-sadhu-prabhakara.github.io/openbank-bian/

The site covers *what each service is*, *why this architecture matters*, and *how composable, consent-first banking helps the industry evolve*.

## The microservices

| Service | OBIE / BIAN | Repository |
|---|---|---|
| Consent (:8081) | Consents / Consent Administration | https://github.com/Sreenivas-Sadhu-Prabhakara/openbank-consent |
| Accounts (:8082) | AISP / Customer Position | https://github.com/Sreenivas-Sadhu-Prabhakara/openbank-accounts |
| Payments (:8083) | PISP / Payment Order | https://github.com/Sreenivas-Sadhu-Prabhakara/openbank-payments |
| Funds (:8084) | CBPII / Customer Position | https://github.com/Sreenivas-Sadhu-Prabhakara/openbank-funds |
| Party (:8085) | Party / Party Reference Data | https://github.com/Sreenivas-Sadhu-Prabhakara/openbank-party |

## Disclaimer

Independent, educational reference implementation. Not production software; not affiliated with or certified by OBIE / Open Banking Limited or BIAN. The FAPI security profile (OAuth2/OIDC, MTLS, signed request objects) is intentionally stubbed.

---

This repo is a static, single-file site (`index.html`) served via GitHub Pages — no build step.
