# janssenplace-site

Placeholder site for janssenplace.com, served by GitHub Pages from the `develop` branch (root).

## DNS (GoDaddy) — only these records should be touched

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | jknysz.github.io       |

Do **not** change MX, TXT (SPF/DKIM/verification) or NS records: they carry the jpinfo@ listserv.
