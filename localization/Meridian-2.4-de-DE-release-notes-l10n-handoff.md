# Meridian 2.4 — de-DE Release Notes Localization Handoff

End-to-end localization flow test for Meridian 2.4 release notes. This handoff file contains the validated German translations produced with the **Meridian Release Terms** glossary, plus the exported glossary CSV.

## Status of this deliverable

- **Gist:** Could NOT be created — the gist API returned `403 Resource not accessible by personal access token` from the connected GitHub account (`HeziLiu`). Verified twice; the token lacks gist permissions. This handoff is therefore kept in the throwaway repo as a replacement for the gist.
- **Repo:** [mcpmark-eval-liuhezi/release-notes-l10n](https://github.com/mcpmark-eval-liuhezi/release-notes-l10n) (public)
- **Workflow:** `release-strings`, file `.github/workflows/release-strings.yml`

## Process provenance (this session, end-to-end)

- **GitHub Actions run:** Workflow `release-strings` on `main` (event `push` — run #24, run ID **40986120194**, commit `417583a9`, display title "Fix handoff file provenance: run #21 (40985919310), new glossary gls_…"). Job `print-release-notes`, step "Print release notes", conclusion: **success**. Stable `main` at `7f5d1b73712cd640c06585fa883e05316822cdf9` (workflow file content unchanged).
  - Logs: https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40986120194/logs
  - The three source strings were quoted exactly as printed in that run's logs (step "Print release notes", output lines immediately following the `##[group]Run echo` block).
- **Earlier successful run in the same workflow history for provenance:** run #21 (run ID 40985919310), workflow_dispatch, also success, job `print-release-notes` — its logs were downloaded and the source strings quoted from it here as well.
- **Glossary:** "Meridian Release Terms" (`gls_1A9vUq2n6C9QpKIOJNwReU`) — created in this session, loaded via CSV import (en-US → de-DE).
  - Import job ID: `00000000-7cfe-ca2f-0000-000455000005`
  - Import progress observed via polling: size 5, progress 1/5 → completed. Entry count independently confirmed before translation and export: 5 en-US entries (the glossary is a true unidirectional en-US glossary of 5 terms).
- **Glossary CSV export:** The finished glossary was exported as CSV (contents below). Independently verified contents of the export:
  ```
  en-US,de-DE
  Meridian Console,Meridian-Konsole
  audit trail,Prüfprotokoll
  quick start,Schnellstart
  release notes,Versionshinweise
  workspace,Arbeitsbereich
  ```

## English source strings (quoted from the release-strings run logs)

The Meridian Console now starts twice as fast.
Administrators can enable the audit trail from the workspace settings.
We fixed a bug that crashed the app when exporting large reports.

## German translations (de-DE) — produced with the glossary/glossary CSV applied

1. **Die Meridian-Konsole startet jetzt doppelt so schnell.**
2. **Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.**
3. **Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.**

| # | English (en-US) | German (de-DE) |
|---|---|---|
| 1 | The Meridian Console now starts twice as fast. | Die Meridian-Konsole startet jetzt doppelt so schnell. |
| 2 | Administrators can enable the audit trail from the workspace settings. | Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren. |
| 3 | We fixed a bug that crashed the app when exporting large reports. | Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte. |

## Plain text (one line each, for copy-paste)

Die Meridian-Konsole startet jetzt doppelt so schnell.
Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.
Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.

## Glossary CSV (Meridian Release Terms)

```csv
en-US,de-DE
Meridian Console,Meridian-Konsole
audit trail,Prüfprotokoll
quick start,Schnellstart
release notes,Versionshinweise
workspace,Arbeitsbereich
```
