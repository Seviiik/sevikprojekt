# Volební skraper
  O co jde v projektu?

  Tento skript umožňuje ziskat výsledky parlamentních voleb z roku 2017 pro konkrétní okres z této webové stránky
  (vyberte si okres ve sloupci Vyber obce) a uložit je do CSV souboru.

  Jak na to?

  Před spuštěním projektu nainstalujte potřebné knihovny uvedené v souboru reguirements.txt Skript spustite v
  přikazovém řádku pomocí následujícího přikazu: python main.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103"  vystup.csv

  Výstupem bude soubor .csv s výsledky voleb pro dany okres.

  Jak to vypadá v praxi?
  Odkaz ->https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103
  Název výstupniho souboru -> cheb_volby17.csv
