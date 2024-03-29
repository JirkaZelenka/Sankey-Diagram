# Sankey-Diagram

### 3.11.2021
### status: In progress

## Popis projektu
* **Motivace:** Připravit interaktivní a intuitivní **Sankey diagram** ke zobrazení přesunů zaměstnatnců  - odchody, změny "skupiny", aj., v průběhu času.
* **Očekávání:** Jsme schopni zobrazit různá časová období a porovnat je. Můžeme si plně customizovat grafy. Vysoká interaktivita a přehlednost. Procenta i absolutní hodnoty.
* **Přístup:** Využití package **PLOTLY** pro vizualizace, dále Tlačítka a Dropdowny a další funkcionality grafů.

## Cíle
1) Vytvoření jednoduchých dummy dat
2) Vytvoření základního diagramu
3) Zapojení přídavných vlastností jako tlačítka, dropdown listy, aj.
4) Příprava dat pro využití časových filtrů
5) Export grafu, propojení s JDBC, jiné...?
6) Nice to have: Indikace, zda se mezi danými obdobími něco změnilo i když to graf nezachycuje: A (->B->) A

## Output: 
1) V Jupyter notebooku se nezobrazí, proto přikládám HTML file *figure_188.html*, který je potřeba otevřít přes nakolnování repository do GitHub desktop aplikace, aby byl interaktivní.

2) Totéž zároveň jako obyčejný obrázek: *figure_188.png*

3) Nejlepší je asi zbrazení touto cestou: https://raw.githack.com/JirkaZelenka/Sankey-Diagram/main/figure_188.html

## TBD:
* zobrazit spolu s abs. hodnotami i procenta 

* Datumy nastavovat jako kombinace dvou tlačítek, nebo tlačítko + slider (ale hodnoty pořád musí být předpočítané pro všechny kombinace)

* Napojení na databáze

## Užitečné odkazy:

https://plotly.com/python/sankey-diagram/     # pozice nodů

https://www.youtube.com/watch?v=_jqrlvDVfls   # příklad 1

https://www.kaggle.com/jrmistry/plotly-how-to-change-plot-data-using-dropdowns   # příklad 2 - filtrování dat, ale jen pro překrývající se scatterploty, ne Sankey

https://github.com/plotly/plotly.py/issues/2508   # troubleshooting zobrazování, viz Import packagů

https://www.tutorialspoint.com/plotly/plotly_slider_control.htm  # slider TBD
