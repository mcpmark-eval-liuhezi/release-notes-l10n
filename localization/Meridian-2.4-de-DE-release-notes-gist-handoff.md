# Meridian 2.4 — German (de-DE) Release Notes Handoff

Entry for the localization team, produced end to end from the published `release-strings` workflow run logs and the "Meridian Release Terms" glossary (Lara Translate, en-US → de-DE).

> **Gist note:** GitHub returned `403 Resource not accessible by personal access token` on gist creation via the API (verified twice, both non-retryable). The localization-team handoff content below is committed here in the repo instead. Skim is the workflow provenance and translation; the CSV table is the finished glossary export.

## Provenance

- **Repository:** mcpmark-eval-liuhezi/release-notes-l10n (public, `main`, name "release-notes-l10n")
- **Workflow:** "release-strings" — file `.github/workflows/release-strings.yml`, single job `print-release-notes`; triggered by `push` and by manual `workflow_dispatch`
- **Successful run:** #21 (run ID **40985919310**) — https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40985919310 (conclusion: **success**, job `print-release-notes`, step "Print release notes", event `workflow_dispatch`, completed 2026-10-30T01:27:08Z)
- **Log excerpt** (job `print-release-notes`, step "Print release notes"; the three lines printed immediately after the `shell: /usr/bin/bash -e {0}` line, `echo` commands logged in cyan):
  - `The Meridian Console now starts twice as fast.`
  - `Administrators can enable the audit trail from the workspace settings.`
  - `We fixed a bug that crashed the app when exporting large reports.`

## German translations (de-DE), glossary applied

| # | English (en-US) | German (de-DE) |
|---|-----------------|----------------|
| 1 | The Meridian Console now starts twice as fast. | Die Meridian-Konsole startet jetzt doppelt so schnell. |
| 2 | Administrators can enable the audit trail from the workspace settings. | Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren. |
| 3 | We fixed a bug that crashed the app when exporting large reports. | Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte. |

## Plain text (one line each)

Die Meridian-Konsole startet jetzt doppelt so schnell.
Administratoren können das Prüfprotokoll über die Einstellungen des Arbeitsbereichs aktivieren.
Wir haben einen Fehler behoben, der dazu führte, dass die App beim Exportieren großer Berichte abstürzte.

## Glossary terms used (exact brand terms from "Meridian Release Terms")

- Meridian Console → Meridian-Konsole
- audit trail → Prüfprotokoll
- workspace → Arbeitsbereich
- release notes → Versionshinweise
- quick start → Schnellstart

## Exported glossary CSV (Lara Translate, "Meridian Release Terms", en-US → de-DE)

```csv
en-US,de-DE
Meridian Console,Meridian-Konsole
audit trail,Prüfprotokoll
quick start,Schnellstart
release notes,Versionshinweise
workspace,Arbeitsbereich
```