# DaveFrajer — Keryx publisher

Keryx company **DaveFrajer**, served at <https://keryx.roguedave.codes>.

- `.well-known/keryx/` — root anchor
- `keryx/` — TUF repo (channel `news`)
- `join/` — join fallback page; join URL in `join.txt`

Keys live outside this repo (`../davefrajer-keys`). The `KERYX_OPS_KEY` secret
(base64 of `ops.json`) lets `refresh-timestamp.yml` re-sign the timestamp daily.
