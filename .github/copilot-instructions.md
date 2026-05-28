# Copilot Instructions — gdpr-dpia

> See root `.github/copilot-instructions.md` for global conventions.

Claude Code plugin voor **AVG/GDPR Data Protection Impact Assessments (DPIA)**. Genereert DPIA-templates, checkt verwerkingsgrondslagen, valideert bewaartermijnen, reviewt verwerkersovereenkomsten, en helpt bij het opstellen van een verwerkingsregister.

## Structure

```
.claude-plugin/plugin.json    # Plugin metadata (name, description, version, keywords)
skills/gdpr-dpia/
  SKILL.md                    # Skill definition — triggers, model config, scope
```

## Installation

```bash
claude install djimit/gdpr-dpia
```

## Typical Usage

- **DPIA opstellen** — Genereer DPIA-templates voor specifieke verwerkingen (AVG Art. 35)
- **Verwerkingsgrondslag check** — Valideer of grondslag (toestemming, gerechtvaardigd belang, wettelijke verplichting, etc.) correct is
- **Bewaartermijn validatie** — Check of bewaartermijnen proportionaliteit en doelbinding respecteren
- **Verwerkersovereenkomst review** — Review DPA/verwerkersovereenkomsten op AVG-compliance
- **Verwerkingsregister** — Help bij opstellen en onderhouden van verwerkingsregister
- **Datalek-respons** — Adviseer over meldplicht (72u) aan AP en betrokkene

## Domain Context

- AVG (GDPR) — Verordening 2016/679, van kracht sinds 25 mei 2018
- UAVG — Nederlandse uitvoeringswet AVG
- AP — Autoriteit Persoonsgegevens
- BIO2-koppeling — informatiebeveiliging en privacy by design

## License

MIT (see `plugin.json`)
