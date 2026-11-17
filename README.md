# pirate.actor
learn how to be a pirate :-D

## Cloudflare publishing

Production uses native Cloudflare Git builds from `main`. Run `npm ci` and
`npm run check:deploy` to validate the explicit public assets directory. The
build command is `npm run build`; the deploy command is `npm run deploy`.
Cloudflare retains deployment credentials; GitHub Pages remains a recovery source.
The build revision is published at `/.well-known/cloudflare-build.json`.

## Licensing scope

Original project code and documentation are licensed under the [Apache License, Version 2.0](LICENSE). Third-party dependencies, vendored code, quoted material, data, fonts, media, and other third-party assets retain their respective licenses and rights; this grant does not relicense them. Existing license notices and attribution must be preserved.
