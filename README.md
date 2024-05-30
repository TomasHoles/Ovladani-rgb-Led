Zapojení
Připojte IR přijímačový modul:

GND k GND na Arduinu
VCC k 5V na Arduinu
OUT k digitálnímu pinu 12 na Arduinu
Připojte RGB LED:

Společný pin (katoda nebo anoda) k GND nebo VCC podle typu LED
Červený pin k digitálnímu pinu 9 na Arduinu (přes rezistor)
Zelený pin k digitálnímu pinu 5 na Arduinu (přes rezistor)
Modrý pin k digitálnímu pinu 6 na Arduinu (přes rezistor)

Návod k použití
Nahrajte uvedený kód do vaší Arduino desky.
Otevřete sériový monitor pro zobrazení debug zpráv.
Použijte IR dálkový ovladač k:
Zadání číselné hodnoty (0-255) pomocí číselných tlačítek.
Stisknutí MINUS pro nastavení jasu červené LED.
Stisknutí PLUS pro nastavení jasu zelené LED.
Stisknutí EQ pro nastavení jasu modré LED.
