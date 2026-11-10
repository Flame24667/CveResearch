# CVE Matrix

| Date | Platform | Category | CVE | Trigger | Trigger detail | Public PoC | Status | Folder | Notes |
|---|---|---|---|---|---|---|---|---|---|
| YYYY-MM-DD | Android | rce | CVE-YYYY-XXXXX | browser_page/file_handler | Describe the tested trigger path | yes/no | blocked/fail/pass/replaced | `android/rce/CVE-YYYY-XXXXX/` | |
| 2026-11-10 | Linux | info_leak | CVE-2025-64516 | browser_page | Open the GLPI-hosted page; it anonymously fetches the ticket-only SVG and renders fabricated PII inline. | yes | pass | `linux/info_leak/CVE-2025-64516/` | Verified by successful checker response and browser screenshot; 50 seeded items. |