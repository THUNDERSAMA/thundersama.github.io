# thundersama.github.io
Portfolio

## Ask my Portfolio

The interactive RAG section lives in `index.html` and uses the static-site-friendly `window.PORTFOLIO_ASK_API_URL` runtime setting. The endpoint defaults to the public portfolio API. To override it during deployment, inject `window.PORTFOLIO_ASK_API_URL` before the Ask my Portfolio script runs (for example, from your hosting provider's environment-backed config step).

Use the **Mock mode** control in the section to replay sample events without contacting the API. Leave it off for live requests.
