# SmartTrade AI Callback

A minimal public GitHub Pages placeholder for the SmartTrade AI authentication return URL.

## Security

- This page does not read, display, store, log, or transmit query parameters.
- It immediately removes query strings and fragments from the visible browser URL.
- It is **not yet a functional Angel One authentication integration** and does not pass tokens to the Android app.
- Never commit API keys, client secrets, PINs, OTPs, JWTs, feed tokens, or other credentials here.

## Deployment

Enable GitHub Pages in repository Settings → Pages:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Expected site URL after GitHub confirms deployment:
https://ariffm1.github.io/SmartTradeAI-Callback/

Do not register this URL with Angel One until Angel One confirms it accepts this exact HTTPS callback URL and the authentication flow is implemented and tested safely.

## Next steps

The Android app still needs a verified callback/deep-link flow and secure token handling. A static page alone cannot securely act as a token-exchange backend.
