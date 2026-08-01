# nodejs

A minimal Node.js web application — a starter you can deploy to your own server in a couple of minutes with [DollarDeploy](https://dollardeploy.com).

It's a plain [Express](https://expressjs.com) app: a home page, a 404 page, and static assets. Nothing to configure — it reads its port from `process.env.PORT` and starts with `npm start`, which is all any host needs.

## Deploy on DollarDeploy

For a step-by-step guide, see [How to Deploy a Node.js App on DollarDeploy](https://docs.dollardeploy.com/blog/), or:

1. Sign up free at [dollardeploy.com](https://dollardeploy.com) — one app, one server, no card.
2. Connect a server you own (Hetzner, DigitalOcean, Vultr, or any box with SSH), or let DollarDeploy provision one.
3. Create a new app, point it at your fork of this repo, and pick the **Node.js** type.
4. Deploy. You get an HTTPS URL, logs, backups, and monitoring — on by default.

Your app runs as an isolated **systemd** service on your own server — no Docker, no lock-in, at a price you chose.

## Run locally

```bash
npm install
npm start
```

Then open http://localhost:3000.

## License

[MIT](LICENSE)
