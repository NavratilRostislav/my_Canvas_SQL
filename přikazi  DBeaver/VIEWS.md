pohledy s SQL jsou virtuální tabulky, které umožnují prezentovat data z jedné nebo více tabulek v konkrétním formátu, aniž by bilo nutno tato data ukládat samostatně.

	**vytvoření pohledu**

**CREATE VIEW** nazev_pohledu [[AS]]
[[SELECT]] SLOUPEC1, SLOUPEC2, .....
[[FROM]] NAZEV TABULKY

	**Dotazování na pohled**
[[SELECT]]* [[FROM]] nazev_pohledu;

	**aktualizace pohledu**

[[CREATE OR REPLACE VIEW]] nazev_pohledu [[AS]]
[[SELECT]]
[[FROM ;]]

	**smazání pohledu**
[[DROP VIEW]] nazev_pohledu;
