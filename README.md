# IOS
IOS - Operační systémy

 ### Spuštění:  
 * tradelog [-h|--help] [FILTR] [PŘÍKAZ] [LOG [LOG2 [...]]

#### PŘÍKAZ může být jeden z:
* list-tick   – výpis seznamu vyskytujících se burzovních symbolů, tzv. “tickerů”.
* profit      – výpis celkového zisku z uzavřených pozic."
* pos         – výpis hodnot aktuálně držených pozic seřazených sestupně dle hodnoty."
* last-price  – výpis poslední známé ceny pro každý ticker."
* hist-ord    – výpis histogramu počtu transakcí dle tickeru."
* graph-pos   – výpis grafu hodnot držených pozic dle tickeru."

#### FILTR může být kombinace následujících:
* -a DATETIME   – after: jsou uvažovány pouze záznamy PO tomto datu (bez tohoto data). "
                DATETIME je formátu YYYY-MM-DD HH:MM:SS."
* -b DATETIME   – before: jsou uvažovány pouze záznamy PŘED tímto datem (bez tohoto data)."
* -t TICKER     – jsou uvažovány pouze záznamy odpovídající danému tickeru. Při více výskytech přepínače se bere množina všech uvedených tickerů."
* -w WIDTH      – u výpisu grafů nastavuje jejich šířku, tedy délku nejdelšího řádku na WIDTH. "
                Tedy, WIDTH musí být kladné celé číslo. Více výskytů přepínače je chybné spuštění."
* -h a --help   – vypíšou nápovědu s krátkým popisem každého příkazu a přepínače."
