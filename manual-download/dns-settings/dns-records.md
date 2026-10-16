# kitchenwhiz.in — DNS settings (from Squarespace, 16 Oct 2026)

Note shown by Squarespace: *"You're using custom nameservers. Your DNS records are managed with your third-party nameserver provider. To activate the DNS records below, switch to Squarespace nameservers."*
So these are the records held in Squarespace; the live records are whatever the external nameserver provider has.

Screenshots: `squarespace-dns-1-defaults.png`, `squarespace-dns-2-domain-connect-and-custom.png`; full page saved as `Squarespace Domains - kitchenwhiz.in - DNS Settings.pdf`

## Squarespace Defaults

| Type  | Name | Priority | TTL   | Data                     |
|-------|------|----------|-------|--------------------------|
| A     | @    | N/A      | 4 hrs | 198.185.159.144          |
| A     | @    | N/A      | 4 hrs | 198.185.159.145          |
| A     | @    | N/A      | 4 hrs | 198.49.23.144            |
| A     | @    | N/A      | 4 hrs | 198.49.23.145            |
| CNAME | www  | N/A      | 4 hrs | ext-sq.squarespace.com   |

## Squarespace Domain Connect

| Type  | Name           | Priority | TTL  | Data                                 |
|-------|----------------|----------|------|--------------------------------------|
| CNAME | _domainconnect | N/A      | 1 hr | _domainconnect.domains.squarespace.com |

## Custom records

| Type  | Name               | Priority | TTL     | Data                     |
|-------|--------------------|----------|---------|--------------------------|
| CNAME | email              | N/A      | 4 hrs   | email.secureserver.net   |
| CNAME | shopuspessentials  | N/A      | 30 mins | uspessentials.pages.dev  |
| MX    | @                  | 20       | 4 hrs   | mx2.zoho.com             |
