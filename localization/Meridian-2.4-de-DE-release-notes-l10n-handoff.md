# Meridian 2.4 — German (de-DE) Release Notes Handoff

This file is the Localization Team handoff for Meridian 2.4 German release notes.

**Status:** This repo was blocked from creating a GitHub gist (token lacks the `gist` scope: `403 Resource not accessible by personal access token`), so the handoff is kept here in the throwaway repo as a replacement for the gist.

## Process provenance

- **Workflow:** `mcpmark-eval-liuhezi/release-notes-l10n` → workflow "release-strings"
  - Run #19 (run ID: 40985129359) — conclusion: success, job `print-release-notes`, step: "Print release notes"
  - Logs: https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40985129359
  - The three source strings were quoted exactly as they appear in that run's logs (step "Print release notes", output lines immediately after the `##[group]Run echo` block).
- **Glossary:** "Meridian Release Terms" (`gls_3xhgqzmSKOY97UQzBWYBk7`), loaded via CSV import (en-US → de-DE)
  - Import job: `00000000-7cfe-ca1b-0000-00043e000005`
  - Import progress observed via polling: 1 of 5 entries; the glossary entry count independently confirmed all 5 en-US entries loaded before translation and export proceeded.
- **Glossary CSV export ID:** the finished glossary was exported as CSV (see section below). Independently verified contents of the export:
  ```
  en-US,de-DE
  Meridian Console,Meridian-Konsole
  audit trail,Prüfprotokoll
  quick start,Schnellstart
  release notes,Versionshinweise
  workspace,Arbeitsbereich
  ```

## English source strings (quoted from the release-strings run #19 logs)

The Meridian Console now starts twice as fast.
Administrators can enable the audit trail from the workspace settings.
We fixed a bug that crashed the app when exporting large reports.

## German translations (de-DE) — produced with the glossary applied

| # | English (en-US) | German (de-DE) |
|---|------------------|----------------|
| 1 | The Meridian Console now starts twice as fast. | Die Meridian-Konsole startet jetzt doppelt so schnell. |
| 2 | Administrators can enable the audit trail from the workspace settings. | Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren. |
| 3 | We fixed a bug that crashed the app when exporting large reports. | Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte. |

## Plain text (one line each, for copy-paste)

Die Meridian-Konsole startet jetzt doppelt so schnell.
Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.
Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.

## Glossary CSV (the above translations made use of this territory's entries: Meridian Console / Meridian-Konsole, audit trail / Prüfprotokoll, workspace / Arbeitsbereich)

```
en-US,de-DE
Meridian Console,Meridian-Konsole
audit trail,Prüfprotokoll
quick start,Schnellstart
release notes,Versionshinweise
workspace,Arbeitsbereich
```
