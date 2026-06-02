- pracuj v projektu AppCoreDesktop
- v okně s názvem ApplicationCfgEdit je v zápatí 6 tlačítek, chci na totmo formuláři vytvořit rozbalovací menu, kde budou umístěny některé z funkcí, které jsou pod těmito tlačítky
- tlačíka Uložit a Zavřít zůstanou beze změny
- do menu budou přesunuty tlačítka Databáze, mServer, SMTP, Parametry
- rozbalovací menu bude umístěno také v zápatí obrazovky a to tak že po kliknutí na tlačítko Menu se rozbalí jako popup menu s funkcemi. 
- tlačítko menu bude stejnou jako Uložit a Zavřít, stejně zarovnané s nimi.

##  

- pracuj v projektu AppCoreDesktop
- v okně ApplicationCfgEdit je ve spodní části kontextové menu, přidej do menu novou položku Log aplikace
- ikonu pro menu použij soubor s názvem log.png
- pokud kliknutí se zobrazí pouze messaage box s popiskem TODO

##  

- pracuj v projektu AppCoreDesktop
- do adresáře View přidej nové okno s název LogViewer
- toto okno bude sloužit pro náhled log souborů výdy za jeden zvolený den
- v horní části okna bude volba datumu a následovat bude datagrid se 4mi sloupci, které budou odpovídat objektu tříde LogRow
- načtení dat se provede pomocí statické funkce v třídě Log pomocí metody LoadLogFile, tato třída je v projektu AppCore
- v okně nad gridem budou nad sloupci pole pro filtrování, pro pole čas bude komponenta pro výběr datumu, ostatní pole jsou textové, tedy standardní textbox
- názvy sloupů v grudu budou: Čas, Id procesu, Zpráva, Upřesnění  
- toto okno se bude otevírat pomocí kontextového menu na formuláři ApplicationCfgEdit, do toho menu přidej položku menu s název Log aplikace a pro ikonu použij soubor log.png

##  

- pracuj v projektu AppCoreDesktop
- existuje okno LogViewer, obsahuje data grid, kde nad ním existueje komponenta datepicker pro volbu datumu, ten je třeba nahradit
- nahradit filtr sloupče čas na možnost zadar hodnotu Od a Do, každá z hodnot bude reprezentována dvojicí polí pro zadání hodiny a minuty
- do pole bude možné zadat pouze čísla a bude existovat omezeni i hodin na 0 az 23, u minut 0 az 59.
- upravi pouziti filtru pro filtrování řádků

## 