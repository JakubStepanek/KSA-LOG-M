#

## Náklady na zásoby

- **Pořizovací náklady** - fixní charakter
  - příprava, vystavení a odeslání objednávky
  - na příjem, dopravu...
- **Náklady spojené s držením zásob**
  - na úroky z kapitálu uloženého do zásob (8 až 12.5 %)
  - na prostora na správu zásob cca 7 %
  - vyplývající z rizika neprodejnosti či nepoužitelnosti zásob (zkažení, móda, nepotřebnost)
  
**Celkem 15 až 35 %**

- <font color="#999999">Náklady z nedostatku zásob</font>
  - náklady na express objednávku
  - penále za pozdní dodání
  - ušlý zisk

![Náklady na zásoby](../media/naklady-na-zasoby.png)

## Kdy je potřeba objednat?

- **Okamžik objednání záleží na** zvoleném **schématu řízení zásob** pro jednotlivé typy položek

- příslušný **systém řízení zásob volíme na základě charakteru zboží**

  - (spotřebě, obrátce, dodacích podmínkách, pořizovacích nákladech...)
  - **Sortiment** rezdělíme dle charakteru do skupin
  - Přiřadíme strategicky nejvhodnější model řízení
![Pilový diagram zásob](../media/pilovy-diagram-zasob.png)

## Ukazatelé zásob

- **DOZ** - Doba obratu zásob = za jak dlouho se teoreticky obmění 100% zásoby
- **Index OZ** - index obratu zásob = kolikrát se zásoba obmění za sledované období (např. rok)
- Dodací lhůta a interval
- WIP - Work in proces = rozpacovanost ve výrobě [ks]
- LT - Lead time = průběžná doba výroby
- VA index = index přidané hodnoty

## Objedaní systémy

B = online sledování
b = fixní intervaly
S = narvu to po strop
Q = stejné množství

- **Systém (B, Q)**
![Q, B](../media/system-(B%2CQ).png)
- **Systém (B, S)**
![B, S](../media/system-(B%2CS).png)
- **Systém (b, Q)**
  - Pro B/C položky, nízká hodnota obděru bez nározových požadavků
- **Systém (s, Q)**
- **Systém (s, S)**
  - Pro B/C položky, vyšší hodnota odběru nepravidelně
- **Systém (s, T)**
  - pro náhradní díly
- **Systém 2 zásobníků**
- **Model přechodného neuspokojení poptávky**
![Model přechodného neuspokojení poptávky](../media/Model%20p%C5%99echodn%C3%A9ho%20neuspokojen%C3%AD%20popt%C3%A1vky.png)
- **Produkční model** - pro mezioperační zásoby
![Produkční model](../media/produkcni-model.jpg)

### Kolik je potřeba objednat?

- Lze určit napr. dle deterministických modeů jako je **Campův vztah**
- Dnes se pro A-čkové položky prefferují JIT/JIS dodávky
- Rozhodujícím kritériem je:
  - Kapacita transportních obalů a prostředků
  - Čas na zjištění potřeby zákaznííka a čas obstarání zboží od dodavatele
  - Čas potřebný na zpracování a dodání zboží k zákazníkovi
  - Zákaznický odbyt a způsob na odebírání

- Campův vzorec

![Campův vzorec](../media/campuv-vzorec.png)

- Vzorec KANBAN

![Vzorec KANBAN](../media/vzorec-kanban.png)
