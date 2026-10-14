# pirate.actor
learn how to be a pirate :-D

## Cloudflare publishing

Production uses native Cloudflare Git builds from `main`. Run `npm ci` and
`npm run check:deploy` to validate the explicit public assets directory. The
build command is `npm run build`; the deploy command is `npm run deploy`.
Cloudflare retains deployment credentials; GitHub Pages remains a recovery source.
The build revision is published at `/.well-known/cloudflare-build.json`.
