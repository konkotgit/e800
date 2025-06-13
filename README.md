# E800
## Klon komputera Elwro 800 Junior

Komputer powstał na bazie implementacji opracowanej przez Nietoperza z forum speccy.pl
E800 pozwala na uruchomienie trzech różnych maszyn

* Elwro 800-3 Junior
* Elwro 804 Junior PC
* ZX Spectrum 48

## Specyfikacja:
* Procesor Z80
* Pamięć ROM
* Pamięć RAM
* Wyjścia video: RGB, Kompozyt, S-Video
* Gniazdo EAR/MIC jack 3,5mm
* Gniazdo wyjścia dzwięku jack 3,5mm
* Gniazdo PS/2 dla klawiatury
* Wbudowany AY-3-8910
* Wbudowany kontroler stacji dyskietek
* Gniazdo joysticka w standardzie Kempston

## Wyjście video RGB
Wyjście RGB używa 9 pinowego złącza minidin. Pinout jest zgodny z kablem do SEGA Genesis2 i Mega Drive 2

## Zasilacz
Do zasilania proponuję użyć dobrej jakości zasilacza o napięciu pomiędzy 9 - 12v i wydajności prądowej min 3A.

## Bluetooth
Na płycie głównej znajduje się miejsce na wpięcie modułu bluetooth MH-M18 umożliwiającego wczytywanie programów z PC lub smartfonów.

## ROM
W komputerze za pomocą zworki J14 mamy możliwość przełączenia pomiędzy dwoma róznymi wsadami pamięci ROM.

## Junet
Klon nie ma zaimplementowanej obsługi sieci Junet

## Stacja dyskietek
Kontroler stacji dyskietek oparty jest na układzie WD37C65B (GM82C765B)
Standardową stację dyskietek od PC podłączamy kablem prostym bez przeplotu.
Oczywiście działa też bez problemów z gotekiem.

Uwaga
Zastosowany w E800 kontroler stacji dyskietek WD37C65B zgodnie z wszelakimi datasheet powinien być zgodny z Intel 8272 który był stosowany oryginalnie w Juniorze.
Jak się okazuje to jest prawie zgodny. Działa odczyt i zapis dyskietek natomiast na tą chwilę nie działa formatowanie. 

## Klawiatura
Klawiatura oprata jest na przełącznikach typu Cherry MX. Klawiatra z płytą główną połączona jest za pomocą 20 pinowej taśmy ICD.
W klawiaturze montujemy kątowe złącze ICD. 
W E800 można użyć klawiatury mechanicznej lub PS/2
Klawiatura PS/2 wymaga odpowiedniego firmware w CPLD i zaprogramowanego układu Attiny.

## Elwro 804 Junior PC
Elwro 804 Junior PC startując będzie próbował wczytać z dyskietki system CP/J.
Aby uruchomić komputer w trybie BASIC należy przytrzymać klawisz B przy resecie lub przy włączaniu zasilania.
