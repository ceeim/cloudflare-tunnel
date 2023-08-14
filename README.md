# Cloudflare Tunnel

Inspired by [https://github.com/zizifn/edgetunnel](https://github.com/zizifn/edgetunnel)

## Deploy in Cloudflare Pages

1. Fork this repo to create Cloudflare Pages.

3. Add an environment variable. The variable name is `UUID` , generate variable value on your own.

## Deploy in Cloudflare Workers

1. Copy the code of `_worker.js` deploy to Cloudflare Workers.

2. Alternatively, you can click the button below to deploy directly.

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/ceeim/cloudflare-tunnel)

## Usage

Open your Workers domain `https://xxx.workers.dev/` or Pages domain `https://xxx.pages.dev/` in your browser.

Then you can see the following page: the path `/{UUID}` to get the clash config and vless:// link.
