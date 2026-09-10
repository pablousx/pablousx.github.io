# pablousx.github.io

GitHub Pages publishes `docs/` from `main` at https://pablousx.github.io/.
The homepage links to projects and does not redirect visitors.

Project repositories with Pages enabled publish independently at paths such as
https://pablousx.github.io/omadocs/. Each project deploys its own HTML at its
artifact root; GitHub adds the repository path. Leave the custom-domain setting
empty and do not add a `CNAME` file to either publishing source.

GitHub manages DNS and HTTPS for this address; no Cloudflare DNS record is needed.
The historical `dist/` portfolio is not part of the Pages publishing source.
