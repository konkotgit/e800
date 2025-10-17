# E800  
## Klon komputera Elwro 800 Junior

E800 to współczesny klon komputera Elwro 800 Junior, oparty na implementacji opracowanej przez Nietoperza z forum [speccy.pl](https://speccy.pl). Komputer umożliwia uruchomienie trzech różnych maszyn:

- **Elwro 800-3 Junior**
- **Elwro 804 Junior PC**
- **ZX Spectrum 48**

---

## Specyfikacja

- **Procesor:** Z80  
- **Pamięć ROM:** z możliwością przełączania wsadów  
- **Pamięć RAM**  
- **Wyjścia wideo:** RGB, kompozyt, S-Video  
- **Audio:**  
  - EAR/MIC – jack 3,5 mm  
  - Wyjście audio – jack 3,5 mm  
- **Klawiatura:** PS/2 lub mechaniczna (Cherry MX 5-pin)  
- **Układ dźwiękowy:** AY-3-8910  
- **Kontroler FDD:** WD37C65B (GM82C765B)  
- **Joystick:** w standardzie Kempston  

---

## Wyjście wideo RGB

Wyjście RGB wykorzystuje 9-pinowe złącze Mini-DIN. Pinout jest zgodny z kablami SEGA Genesis 2 / Mega Drive 2.

---

## Zasilanie

Zalecany zasilacz:  
- Napięcie: 9–12 V  
- Prąd: minimum 3 A  
- Dobra jakość zasilacza jest kluczowa dla stabilnego działania

---

## Bluetooth

Na płycie głównej znajduje się złącze do montażu modułu **Bluetooth MH-M18**. Umożliwia on ładowanie programów z komputera PC lub smartfona.

---

## EAR/MIC

Uwaga! W przypadku problemów z wczytywaniem programów z taśmy należy odwrócić tranzystor Q1 BC517.
Występują z dwoma rodzajami wyprowadzeń CBE lub EBC.

---


## ROM

Za pomocą zworki **J14** można przełączać się między dwoma wsadami ROM.

---

## Junet

Ten klon nie obsługuje sieci **Junet**.

---

## Stacja dyskietek

- Kontroler: **WD37C65B**  (GM82C765B)
- Obsługuje standardowe stacje dyskietek PC (bez przeplotu)
- Gotek działa poprawnie

**Uwaga:**  
Na ten moment **formatowanie dyskietek nie działa**, choć odczyt i zapis funkcjonują poprawnie.

---

## Klawiatura

- Wersja mechaniczna oparta na przełącznikach Cherry MX (5-pin)
- Połączenie przez taśmę 20-pin IDC (kątowe złącze w klawiaturze)
- Możliwość użycia klawiatury **PS/2** — wymaga odpowiedniego firmware'u w **CPLD** i zaprogramowanego układu **Attiny**

---

## Tryb Elwro 804 Junior PC

Po uruchomieniu w trybie **804**, komputer próbuje wczytać z dyskietki system **CP/J**.

Aby uruchomić komputer w trybie **BASIC**, przytrzymaj klawisz **B** podczas włączania zasilania lub resetu.

![E800 Picture 1](/photos/e800_1_s.jpg)

![E800 Picture 2](/photos/e800_25_s.jpg)