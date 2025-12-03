table# Bootstrap Tabulky - Cvičení

## Zadání

Naučte se vytvářet HTML5 tabulky se sémantickou strukturou a formátovat je pomocí Bootstrap frameworku.

Vaším úkolem je:

1. **Přidat chybějící HTML tagy** pro vytvoření správné struktury tabulky
2. **Použít Bootstrap třídy** pro formátování tabulky
3. **Dodržet sémantickou strukturu** HTML5 tabulek

tabulka bude vypadat zhruba takto:
![tablescr.jpg](tablescr.jpg)


## Co byste měli použít

### HTML5 Struktura tabulky

- `<table>` - hlavní element tabulky
- `<caption>` - nadpis/popis tabulky
- `<col>` a `<colgroup>` - definice sloupců a jejich skupin
- `<thead>` - hlavička tabulky
- `<tbody>` - tělo tabulky (můžete použít vícekrát pro logické skupiny)
- `<tfoot>` - patička tabulky
- `<tr>` - řádek tabulky
- `<th>` - buňka hlavičky
- `<td>` - datová buňka

### Bootstrap třídy

Na elementu `<table>`:
- `.table` - základní styl Bootstrap tabulky
- `.table-striped` - proužkování řádků
- `.table-bordered` - ohraničení buněk
- `.table-hover` - zvýraznění řádku při najetí myší

Na ostatních elementech:
- `.table-dark` - tmavé pozadí (vhodné pro hlavičku)
- `.table-secondary` - šedé pozadí
- `.table-info` - světle modré pozadí (vhodné pro patičku)
- `.fw-normal` - normální tloušťka písma
- `.fw-bold` - tučné písmo
- `.text-center` - zarovnání textu na střed
- `.lead` - zvětšený text pro caption

### Další potřebné atributy

- `role="columnheader"` - role pro sloupec hlavičky
- `role="region"` - role pro oblast/region

## Postup řešení

1. Otevřete `index.html`
2. Přidejte do `<head>` Bootstrap CSS a JS:
   ```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
   ```
3. Obalte obsah v `<main>` do struktury tabulky s příslušnými tagy
4. Přidejte Bootstrap třídy pro formátování
5. Správně strukturujte data do řádků a buněk
6. Použijte `<tbody>` pro oddělení tříd 1.A a 1.B
7. Použijte `<tfoot>` pro řádek s průměry

## Tipy

- Každá třída (1.A a 1.B) má vlastní `<tbody>` element
- První sloupec obsahuje jména - používejte `<th>` místo `<td>`
- Hlavičky tříd by měly být zvýrazněny šedou barvou
- Poslední sloupec "Průměr" v patičce by měl být tučný
- Prázdné buňky ponechte prázdné (používají se pro vizuální strukturu)

---

**Hodnocení:** Dbejte na validitu HTML kódu a správné použití Bootstrap tříd.
