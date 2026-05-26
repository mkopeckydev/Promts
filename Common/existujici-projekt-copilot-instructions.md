Zadání:

- Analyzuj celé solution a vygeneruj copilot-instructions.md pro každý projekt a tyto soubory pro jednotlivé projekty umístí v každém jednotlivém projektu do podadresáře .github.
- Nevytvářej copilot-instructions.md na úrovni solution ale jen na úrovni jednotlivých projektů v solution.

Cíl:

Vytvořit kvalitní GitHub Copilot instrukce pro projekty v existujícím produkčním solution.

Požadavky:

- Veškerý popis, komentáře a architektonická logika piš v češtině
- Veškeré názvy proměnných, funkcí, tříd, interfaces, typů, enumů a identifikátorů v generovaném kódu musí být vždy v angličtině
- Veškeré code snippets musí používat anglický naming
- Framework-specific termíny ponechávej v angličtině
- Nevymýšlej technologie, které nejsou v repository
- Inferuj pravidla z existujícího kódu projektu

Před generováním instrukcí:

1. Projdi:

- package manifests
- README
- CI/CD konfigurace
- lint/formatter konfigurace
- test setup
- strukturu složek
- existující coding style

2. Inferuj:

- architekturu projektu
- coding conventions
- naming conventions
- build/test/lint commandy
- používané frameworky a knihovny
- preferované patterns
- zakázané patterns
- conventions pro dependency injection
- conventions pro API layer
- conventions pro state management
- conventions pro testing

Výstup musí:

- být stručný
- být konkrétní
- používat bullet points
- být optimalizovaný pro GitHub Copilot
- být optimalizovaný pro Visual Studio / VS Code
- být vhodný pro větší existující codebase
- preferovat minimální diffy
- preferovat zachování existující architektury
- preferovat reuse existujících utilities/components

Přidej explicitní pravidla:

- nepřepisovat celé soubory
- měnit pouze relevantní části kódu
- zachovávat existující naming conventions
- preferovat existující utility před vytvářením nových
- business logiku oddělovat od UI/controller vrstvy
- dodržovat existující folder structure

Důležité:

- Text instrukcí piš česky
- Kódové identifikátory musí být anglicky
- Názvy proměnných nikdy negeneruj česky
- Komentáře v kódu generuj anglicky
- Commit messages preferuj anglicky
- API endpoint naming musí být anglicky

Přidej sekci:

# Naming Rules

s explicitními pravidly:

- Variables must use English names
- Function names must use English verbs
- Class names must use English nouns
- Database entities must use English naming
- API routes must be in English
- Avoid Czech identifiers in source code

Nevysvětluj výstup.

Vrať pouze finální markdown obsah souboru.

