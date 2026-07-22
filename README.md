# Bartosz Kuć

Warsaw-based developer. JDG owner running [skanfirmy.pl](https://skanfirmy.pl). Day job in process automation at a global ad-tech company.

## honest-mcp — 13 open-source local MCP servers

A family of small, auditable MCP servers that let AI clients (Claude, Cursor, Zed) reach real services **without a cloud middleman**. Every server runs on your own machine and talks directly to the actual service API. No hosted MCP host, no data collection, no third-party token custody. MIT.

```
Your AI client ↔ MCP stdio ↔ this server (on your Mac) ↔ HTTPS ↔ real service
```

### Polish accounting & business

| Repo | What |
|---|---|
| [mbank-parser-mcp](https://github.com/bartosz-kuc/mbank-parser-mcp) | Parses mBank CSV exports **fully offline** — no network calls at all |
| [nbp-mcp](https://github.com/bartosz-kuc/nbp-mcp) | NBP FX rates + gold fixing — accounting-grade conversion helpers |
| [honest-vies-mcp](https://github.com/bartosz-kuc/honest-vies-mcp) | EU VAT check with consultation number for audit proof |
| [nip-krs-mcp](https://github.com/bartosz-kuc/nip-krs-mcp) | Biała Lista MF + KRS registry lookups |
| [pl-holidays-mcp](https://github.com/bartosz-kuc/pl-holidays-mcp) | Business-day math that respects Polish public holidays |

### Polish public data

| Repo | What |
|---|---|
| [stat-gov-mcp](https://github.com/bartosz-kuc/stat-gov-mcp) | GUS Bank Danych Lokalnych — public statistics down to the gmina |
| [nfz-mcp](https://github.com/bartosz-kuc/nfz-mcp) | NFZ waiting lists and medical service dictionary |
| [imgw-mcp](https://github.com/bartosz-kuc/imgw-mcp) | IMGW weather, hydro data, and active meteorological warnings |
| [gios-air-mcp](https://github.com/bartosz-kuc/gios-air-mcp) | GIOŚ air quality — station data and composite index |

### Google (self-hosted alternatives)

| Repo | What |
|---|---|
| [honest-gmail-mcp](https://github.com/bartosz-kuc/honest-gmail-mcp) | Gmail — send, search, label, draft |
| [honest-calendar-mcp](https://github.com/bartosz-kuc/honest-calendar-mcp) | Google Calendar |
| [honest-drive-mcp](https://github.com/bartosz-kuc/honest-drive-mcp) | Drive with full permission management — the piece missing from the official connector |

### Utility

| Repo | What |
|---|---|
| [rss-mcp](https://github.com/bartosz-kuc/rss-mcp) | RSS/Atom feed reader |

## Quality

Each server is ~150–300 lines of Python — auditable in one sitting.

Every repo ships the same automation stack:

- Dependabot weekly version and security updates
- GitHub CodeQL SAST on every push and PR
- CI matrix on Python 3.10–3.13
- Secret scanning with push protection
- MIT licensed, verified commits

## Consulting

Available for consulting on Polish tax and business integrations (KSeF, GUS/NFZ/GIOŚ APIs, mBank data), MCP server design, and AI-assisted tooling for JDGs and small teams.

- Email: **firma@bartosza.pl**
- Site: [skanfirmy.pl](https://skanfirmy.pl)
