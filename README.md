# sf-docs

Dokumentation und NIN-Referenzen fuer die **strawberryfactory** GEE Tools Suite.

> GEE = Gebaeude-Elektro-Engineering. Werkzeuge fuer den Projektalltag im
> Elektroingenieurbuero, nach Schweizer Normen (NIN, SIA, BKP).

---

## strawberryfactory Tools-Suite

| Repo | Zweck | Status |
|------|-------|--------|
| [sf-docs](https://github.com/strawberryfactory/sf-docs) | Dokumentation, NIN-Referenzen, Anleitungen | public, WIP |
| [sf-calc](https://github.com/strawberryfactory/sf-calc) | Elektro-Rechner (Kabel, Kurzschluss, PV, Leistung) | public, WIP |
| [sf-kb](https://github.com/strawberryfactory/sf-kb) | Knowledge Base: Interview-Prozess fuer Projektbeschriebe | private, WIP |
| [sf-buildingfile](https://github.com/strawberryfactory/sf-buildingfile) | Marimo-Gebaeude-Abbild fuer Lastprofile | private, WIP |
| sf-mcp | MCP-Server fuer Azure, Vertec, Messerli (geplant) | nicht angelegt |
| sf-office-tui | Terminal-UI fuer den Buero-Alltag (geplant) | nicht angelegt |

---

## Grundsaetze

- **Schweizer Kontext:** NIN 2020, SIA 108, SIA 380, BKP-Katalog KBOB.
- **Open Source wo moeglich** (MIT Lizenz fuer sf-docs, sf-calc).
- **Klein anfangen**, aber sauber. Jede Aenderung auf einem `wip/*`-Branch + PR.
- **Keine Secrets** im Repo. `.env` ist immer in `.gitignore`.

---

## Inhalte dieses Repos (geplant)

- `nin/` — NIN-Hinweise, Checklisten
- `sia/` — SIA-Phasenmodell, Leistungsbilder
- `bkp/` — BKP-Kategorien und Zuordnungen (BKP 23.x Elektro)
- `beispiele/` — Durchgerechnete Projektbeispiele
- `entscheidungen/` — ADRs fuer die Tools-Suite

Status: noch leer. Wird schrittweise befuellt.

---

## Mitwirken

Dieses Repo ist Teil eines Freizeitprojekts. Beitraege willkommen, aber ohne
SLA. Bei Fragen: Issue oeffnen.

---

## Lizenz

MIT. Siehe [LICENSE](./LICENSE).
