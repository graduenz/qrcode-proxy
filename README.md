# qrcode-proxy

Simple URL proxy implementation with a configurable 301 Redirect.

Initially intended to be used with printed QRCodes pointing to subdomains.

- [qrcode-proxy](#qrcode-proxy)
  - [Supported platforms](#supported-platforms)
    - [Netlify](#netlify)
    - [Vercel](#vercel)

## Supported platforms

### Netlify

Fork this repository to your account, or download it as a ZIP file, then create a new project in Netlify using it.

Before finishing the project setup, make sure you do the following in the last step:

- In **Build settings**:
  - Change the **Base directory** to "netlify".
- In **Environment variables**:
  - Add `REDIRECT_TARGET_URL` with the url you want to be redirected to.
    - Example: https://github.com/graduenz/qrcode-proxy


### Vercel

⚠️ WIP
