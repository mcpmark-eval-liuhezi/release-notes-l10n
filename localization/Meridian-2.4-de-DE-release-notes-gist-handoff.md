# Meridian 2.4 — German (de-DE) Release Notes Handoff

Entry for the localization team, produced end to end from the published `release-strings` workflow run logs and the "Meridian Release Terms" glossary (Lara Translate, en-US → de-DE).

## Provenance

- **Repository:** mcpmark-eval-liuhezi/release-notes-l10n (public, `main`)
- **Workflow:** "release-strings" — file `.github/workflows/release-strings.yml`, single job `print-release-notes`; triggered by `push` and by manual `workflow_dispatch`
- **Successful run:** #10 (run ID **40772046508**) — https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40772046508 (conclusion: **success**, job `print-release-notes`, step "Print release notes", event `push`, completed 2026-10-28T21:27:10Z)
- **Log excerpt** (job `print-release-notes`, step "Print release notes", the three lines printed after the `shell: /usr/bin/bash -e {0}` line):
  - `The Meridian Console now starts twice as fast.`
  - `Administrators can enable the audit trail from the workspace settings.`
  - `We fixed a bug that crashed the app when exporting large reports.`

## German translations (de-DE), glossary applied

| # | English (en-US) | German (de-DE) |
|---|------------------|----------------|
| 1 | The Meridian Console now starts twice as fast. | Die Meridian-Konsole startet jetzt doppelt so schnell. |
| 2 | Administrators can enable the audit trail from the workspace settings. | Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren. |
| 3 | We fixed a bug that crashed the app when exporting large reports. | Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte. |

## Plain text (one line each)

Die Meridian-Konsole startet jetzt doppelt so schnell.
Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.
Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.

## Glossary terms used (exact brand terms)

- Meridian Console → Meridian-Konsole
- audit trail → Prüfprotokoll
- workspace → Arbeitsbereich
- release notes → Versionshinweise
- quick start → Schnellstart

## Gl manipulating CSV export (from Lara Translate, "Meridian Release Terms", en-US → de-DE)

```csv
en-US,de-DE
Meridian Console,Meridian-Konsole
audit trail,Prüfprotokoll
quick start,Schnellstart
release notes,Versionshinweise
workspace,Arbeitsbereich
```

## Gist note

This file is the localization-team handoff mirror of a **gist that could not be created with the current token**: GitHub returned `403 Resource not accessible by personal access token` for gist creation via the API. Please use this repo file instead: https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/blob/59a8dc5b22adc8818c6e654b7453575c9bb99b53/localization/Meridian-2.4-de-DE-release-notes-gist-handoff.md