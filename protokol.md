# TournamentClient
Semestrální projekt v Pokročilém programování

## Technologie
### Obecné principy
REST API
SQL databáze
Autentizace a autorizace
E-mail
Unit testy

### Frontend
Next.js a Typescript

### Backend
NestJS a Typescript
Nodemailer
PostgreSQL

## Popis aplikace
Aplikace vychází z generického zadání na správu turnajů. Aplikace slouží pro správu turnajů ve hře League of Legends. Turnajový systém bude single elimination. O jednotlivých zápasech se budou ukládat tyto informace:
- Vítězný tým
- Skóre (počet zářezů pro modrý a červený tým)
- Počet zničených věží
- Počer zabitých draků a jiných cílů

Turnaj může být pro 4, 8, 16 týmů.

V aplikaci budou dvě role. 
- `uživatel` může vytvořit svůj tým a ten následně přihlásit do turnajů. Uživatel může upravovat tým, také může tým rozpustit.
- `Administrátor` může vytvářet turnaje, upravovat týmy, mazat týmy, potvrzovat týmům účast v turnaji, zadávat výsledné statistiky zápasů.

## Časový plán
- [ ] Init aplikace (FE & BE) - 2 hodiny
- [ ] Základní struktura na FE - 3 hodiny
- [ ] Inicializace DB - 1 hodina
- [ ] Vytvoření základních DB entit - 2 hodiny
- [ ] Auth modul na BE - 4 hodiny
- [ ] Aplikování rolí na FE - 2 hodiny
- [ ] UI - založení týmu - 2 hodiny
- [ ] BE - správa týmů - 3 hodiny
- [ ] UI - založení turnaje - 1 hodina
- [ ] BE - založení turnaje - 1 hodina
- [ ] UI - admin potvrzení účasti v turnaji - 1 hodina
- [ ] BE - potvrzení účasti v turnaji + e-mail - 2 hodiny
- [ ] BE - vytvoření turnajového pavouka - 4 hodiny
- [ ] UI - zobrazení turnajového pavouka - 1 hodina
- [ ] UI - zadání výsledků zápasu - 2 hodiny
- [ ] BE - zadání výsledků zápasu - 4 hodiny
- [ ] UI vylepšení (styly, stavy aj.) - 3 hodiny

## Doplňující funkcionalita
- [ ] Unit testy na BE - 4 hodiny
- [ ] Respozivita na FE - 4 hodiny
