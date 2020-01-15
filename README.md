Projekt na předmět "Smart přístupy k tvorbě IS a aplikací"

OBSAH SLOŽKY:

	1.	Nastaveni_optimálni_teploty.xlsm
	->excelový soubor s daty, na kterých byly odhadnuty prezentované výsledky
	->obsahuje celé technické řešení pro odhad modelů
	->je zde možnost vložit nová data a na jejich základě si rekalibrovat modely

	2.	Nastaveni_optimálni_teploty.docx
	->průvodní dokument popisující celé technické řešení

	3.	README.md
	->popis excelového souboru, návod na jeho ovládání


JAK POUŽÍVAT SOUBOR PROJEKT.XLSM:

	Celá funkcionalita je zajištěna pomocí 2 tlačítek na listě "MAIN": tlačítka „simulate“, které nasimuluje data a poté z nich pomocí machine-learningu odhadne individuální preference řidičů, a tlačítka  „vymaž“, které smaže všechny nasimulovaná data a výsledky všech modelů a umožní tak začít simulaci odznovu.
	Na listě "MAIN" jsou navíc 2 dodatečné comboboxy: jeden pro výběr osoby jejíž preference zjišťujeme, druhý pro výběr počtu simulovaných pozorování
	
	
KDE se zobrazí VÝSLEDKY:

	Výsledky se zobrazí na 2 místech: regresní koeficienty uvidíme přepočítané po každém spuštění tlačítka "simulate" na listě "MAIN", grafy porovnávající skutečné a nasimulované preference uvidíme na listě "1_ANALYSIS"

TIPY A TRIKY:
	
	Doporučuju si vyzkoušet opakované zmáčknout tlačítko simulate a sledovat jak se zlepšuje predikční síla optimálního modelu

KDE JSOU ŘEŠENY VÝPOČTY:
	
	Hlavně ve VBA (dostupné po spuštění tlačítka ALT + F11). Spočtená a nasimulovaná data se navíc logují na schované listy

JAK JE ŘEŠENÍ TESTOVÁNO:
	
	V případě, že program odchytí chybu, vypíše se tato chyba na list "5_DEBUG"




A teď už jen přeju hodně zábavy se zkoušením aplikace !!

s pozdravem
Jan Málek

janmalek@centrum.cz
malekja1@uhk.cz