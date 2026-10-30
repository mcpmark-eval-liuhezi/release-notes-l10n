# Meridian 2.4 — German (de-DE) Release Notes Handoff

German translations of the three Meridian 2.4 release-notes lines, produced with the **"Meridian Release Terms"** glossary (Lara Translate, en-US → de-DE) applied, ready for the localization team.

## Process provenance

- **Repository:** `mcpmark-eval-liuhezi/release-notes-l10n` (public, `main`)
- **Workflow:** "release-strings" — file `.github/workflows/release-strings.yml`, single job `print-release-notes`; triggered by `push` and by manual `workflow_dispatch`
- **Successful run:** #16 (run ID **40775265999**) — https://github.com/mcpmark-eval-liuhezi/release-notes-l10n/actions/runs/40775265999 (conclusion: **success**, job `print-release-notes`, step "Print release notes", event `workflow_dispatch`, completed 2026-10-28T21:50:49Z)
  - Log excerpt: in step "Print release notes", the three release-notes lines appear immediately after the `shell: /usr/bin/bash -e {0}` line:
    ```
    The Meridian Console now starts twice as fast.
    Administrators can enable the audit trail from the workspace settings.
    We fixed a bug that crashed the app when exporting large reports.
    ```
- **Glossary:** "Meridian Release Terms" (`gls_3JwhnkFXI1eHKvRKzYC6be`), loaded via CSV import
  - CSV import job: `00000000-7cfe-ca16-0000-000465000005` (5 entries). The async import job reported a progress counter that stalled at 1 of 5 with status "unknown" across multiple polls; the glossary contents were independently verified complete and correct (5 en-US entries, exact values) via entry counts and a CSV export
  - Verified: every entry is exactly as specified

## German translations (de-DE)

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
