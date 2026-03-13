## O aplikaci

Desktopová hobby aplikace pro všechny fanoušky FVE a sdílení elektřiny v České republice. 

Slouží pro vizualizaci a analýzu dat exportovaných z portálu EDC.

---

## Funkce

- **Import dat** – Import CSV souborů exportovaných z portálu EDC do lokální SQLite databáze. Aplikace automaticky opravuje formátovací odlišnosti v exportu EDC (mezery v názvech sloupců, desetinná čárka místo tečky).
- **Správa míst** – Přiřazení EAN čísel (odběrných i výrobních míst) k pojmenovaným lokalitám.
- **Přehled dat** – Procházení importovaných dat s filtry a přehlednou tabulkou.
- **Analýza spotřeby** – Přehledy spotřeby elektrické energie pro vybraná odběrná místa a časová období (den / týden / měsíc / rok):
  - Celková spotřeba, spotřeba ze sítě a sdílená elektřina
  - Koláčový graf rozdělení spotřeby
  - Sloupcový graf časového průběhu spotřeby
  - Graf průměrného příkonu (W) – periodický i denní profil (96× 15min intervalů)
- **Analýza výroby** – Přehledy výroby elektrické energie pro vybraná výrobní místa a časová období:
  - Celková výroba, sdílená elektřina a prodej do sítě
  - Koláčový a sloupcový graf průběhu výroby
  - Srovnávací analýza výroby a spotřeby (přebytek, nedostatek, soběstačnost)
- **Nastavení** – Uživatelská nastavení aplikace
- **Export dat** – Export databáze pro zálohu nebo přenos

---

## Jak exportovat data z EDC a importovat je do aplikace

### 1. Přihlaste se na portál EDC

Přejděte na [portál EDC](https://www.edc-cr.cz) a přihlaste se ke svému účtu.

### 2. Exportujte data sdílení elektřiny

1. V menu portálu přejděte do sekce **SPRÁVA DAT** → **Zobrazení a export dat**.
2. Zvolte Skupinu sdílení a požadované časové období (doporučujeme exportovat po měsících).
3. Zvolte tento typ zobrazení: Zobrazení dat pro jednotlivé výrobní a odběrná EAN.
4. Zaškrtněte volbu "Naměřená data" i "Výsledky vyhodnocení".
5. Jako typ dat nejlépe vyberte "Aktuální k datu" a nechte vybrané dnešní datum.
6. Spusťte export a stáhněte výsledný soubor ve formátu **CSV**.
7. Zkontrolujte, že jsou v exportu zahrnuty **všechna vaše odběrná i výrobní místa (EAN)**.

> **Důležité nastavení exportu:** Správné nastavení exportu je zobrazeno na snímku obrazovky v aplikaci na obrazovce *Import dat* (sekce „Jak připravit data o sdílení elektřiny pro import"). Dodržte toto nastavení, aby šla data správně importovat.

### 3. Importujte data do aplikace

1. Otevřete aplikaci **Sdílení elektřiny**.
2. V levém menu vyberte obrazovku **Import**.
3. Klikněte na tlačítko **Vyberte soubor** a vyberte stažený CSV soubor.
4. Zkontrolujte zobrazený název souboru.
5. Klikněte na **Importovat data**.
6. Aplikace soubor automaticky zpracuje, opraví formátovací odlišnosti EDC exportu a uloží data do lokální databáze.
7. Po úspěšném importu se zobrazí potvrzovací zpráva.

> **Poznámka:** Pokud pro daný časový interval již data existují, budou aktualizována (ne zduplikována). Import lze opakovat i pro stejné období.

### 4. Prohlédněte si data

Po úspěšném importu přejděte na obrazovky **Analýza spotřeby** nebo **Analýza výroby** a vyberte místo a časové období, které chcete zobrazit.

## Sdílení elektřiny

Pravidla sdílení elektřiny jsou popsána na: https://www.edc-cr.cz/pro-verejnost/nase-temata/sdileni-elektriny/

## Podpora vývoje

Pokud Vám tato aplikace přijde užitečná a chtěli byste podpořit její vývoj, můžete zvážit příspěvek na: https://ko-fi.com/michalboron

## Licence

Software je možné používat pro soukromou potřebu.

Autor nenese žádnou odpovědnost za škody vzniklé používáním tohoto software.