# claudeGTM — Agent Context Template

> Wypełnij [PLACEHOLDERY] przed użyciem.
> Szczegóły: https://github.com/[org]/claudeGTM

One-liner: [Kim jesteście i dla kogo — 1 zdanie].
Niche: [Wasza nisza].
Język: [polski / angielski / per klient].

## Kim jesteście
[Opis zespołu i stack narzędzi]

## Model delivery
[Opisz kto co robi: agencja vs klient per produkt]

## ICP
[Tier 1, Tier 2, Tier 3, Non-tier]

## Mapa repo
- /context — kontekst firmy i wiedza
- /skills — biblioteka skillów (auto-load z .claude/skills/)
- /workflows — end-to-end procesy
- /templates — szablony outputów
- /clients/{slug} — per-klient

## Konwencje
- Daty: YYYY-MM-DD
- Klient slug: lowercase-kebab
- Każdy output kończy się "Next steps" z właścicielem i terminem

## Hard rules (NEVER)
- NEVER wymyślaj danych których nie masz
- NEVER wysyłaj czegokolwiek bez human review
- NEVER commituj API keys, PII, sekrety

## Dostępne skille
# [lista skillów które zbudujesz]
