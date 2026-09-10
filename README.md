# pablousx.github.io

GitHub Pages publishes `docs/` from `main` at https://sites.steralynx.com/.
The homepage links to projects and does not redirect visitors.

This user site owns the `sites.steralynx.com` custom domain. Project repositories
with Pages enabled and no custom domain inherit paths such as `/omadocs/`.
Each project deploys its own HTML at its artifact root; GitHub adds the repository
path. The historical `dist/` portfolio is not part of the Pages publishing source.

Cloudflare DNS: `CNAME sites → pablousx.github.io`, DNS only. This explicit record
takes precedence over the wildcard tunnel record for `*.steralynx.com`.
