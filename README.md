# Storyledger

Check book chapters against your story notes. Find facts and build a timeline.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://ledger.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http storyledger https://ledger.rowhousesoftware.com/mcp
```

## Tools

- `list_series`: Lists your series, books and chapters, and how many slips are open.
- `check_chapter`: Finds slips in one chapter, with both quotes.
- `list_flags`: Lists every open slip in a series, in reading order.
- `find_in_bible`: Looks up a person, place or thing, with the quote for each fact.
- `timeline`: Shows the series timeline.

## Free and paid

Your first 3 chapters are free, no card. Then it's $18 a month for up to 200,000 words, about two books. You upload books on the site. The connector reads what's there.

## Sign in

You sign in with your Storyledger account (OAuth 2.1). Claude opens the sign in page the first time.

## Help

- Site: https://ledger.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
