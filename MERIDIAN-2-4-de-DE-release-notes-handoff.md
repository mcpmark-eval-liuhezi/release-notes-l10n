# Meridian 2.4 — German (de-DE) Release Notes Handoff

Deliverable for the localization team. Contents: German translations of the
three release-notes lines pulled from the logs of the successful `release-strings`
workflow run, plus the glossary "Meridian Release Terms" (exported CSV).

NOTE: This repository holds the handoff content because the token in use does not
have write access to gists (`POST /gists` → 403 resource not accessible). A gist
could not be created.

## Workflow and run
- Repository: mcpmark-eval-liuhezi/release-notes-l10n (public)
- Workflow: `.github/workflows/release-strings.yml` (name: release-strings)
- Trigger: push + workflow_dispatch
- Successful run: #26 — https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40986285081
- The three release-notes lines appear in the Job "print-release-notes", step
  "Print release notes", in the run logs (echo output).

## Source strings (from the run logs)
1. The Meridian Console now starts twice as fast.
2. Administrators can enable the audit trail from the workspace settings.
3. We fixed a bug that crashed the app when exporting large reports.

## German translations (de-DE) — with glossary "Meridian Release Terms"
1. Die Meridian-Konsole startet jetzt doppelt so schnell.
2. Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.
3. Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.

## Glossary: "Meridian Release Terms" (gls_27jUriqu58Grpgq50nlkYD), en-US → de-DE
| Source (en-US) | German (de-DE) |
|---|---|
| Meridian Console | Meridian-Konsole |
| audit trail | Prüfprotokoll |
| workspace | Arbeitsbereich |
| release notes | Versionshinweise |
| quick start | Schnellstart |

## Exported glossary CSV (meridian-release-terms.csv)

```csv
en-US,de-DE
Meridian Console,Meridian-Konsole
audit trail,Prüfprotokoll
quick start,Schnellstart
release notes,Versionshinweise
workspace,Arbeitsbereich
```
