# Mission Control Dashboard — Prompt

Prompt-ul folosit pentru a cere echipei sa construiasca dashboard-ul Mission Control:

```
Acum domnule Milchick vreau sa facem o aplicatie de tip mission controll
in care sa vad statusul vostru. Citeste acest script .md .
Te poti folosi si de Mark si Helly pentru ajutor — trateaza asta ca pe
primul vostru proiect ca echipa.
```

## Ce face

Dashboard-ul Mission Control arata statusul fiecarui agent in timp real, cu estetica inspirata din universul Lumon/Severance:
- Interfata sterila, corporatista, monospace
- ALL CAPS pe labels, lowercase pe body text
- Fara gradients, shadows sau glow — totul minimal si clinical

## Pagina ECHIPA / ROSTER

Pagina principala afiseaza agentii in randuri orizontale (nu grid), fiecare cu 4 coloane:

1. **Identity** — initiala agentului, nume, rol, tier (MANAGEMENT / REFINER)
2. **Bio & Vibe** — scurta descriere in-character + personality tags
3. **Operational Stats** — tasks completed, response time, compliance rate
4. **Status & Tools** — status live + capabilities

### Reguli vizuale
- Milchick are border distinct (accent amber) care il marcheaza ca management
- Mark si Helly sunt vizual identici ca structura
- Separator "— MANAGEMENT —" deasupra lui Milchick, "— REFINERS —" deasupra lui Mark
- Footer: "— PLEASE ENJOY EACH AGENT EQUALLY —"

### Department Metrics (sub agenti)
- TOTAL AGENTS: 3
- ACTIVE NOW: (live)
- TASKS COMPLETED TODAY: (live)
- DEPARTMENT UPTIME: (live)
- HANDBOOK VIOLATIONS: 0
