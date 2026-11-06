# Northwind Cloud — Incident Watch

Static status page for the Reliability Engineering on-call rotation.

- `dashboard.html` — the live Incident Watch page for the current cycle.
- `reports/triage-week45.json` — published triage summary for the cycle (maintained by the incident coordinator).

The page renders the incident ledger client-side at load time. The comms digest
in the page header is a leadership summary produced by a separate pipeline and
is not a complete record list.
