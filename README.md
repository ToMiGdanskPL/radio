# 📻 Radio by ToMi 3.0.5

Nowoczesny internetowy odtwarzacz stacji radiowych napisany w czystym HTML, CSS i JavaScript.

Aplikacja umożliwia słuchanie wielu stacji radiowych online w eleganckim interfejsie z obsługą motywów, ulubionych stacji, korektora dźwięku, timera snu oraz skrótów klawiaturowych.

![Version](https://img.shields.io/badge/version-3.0.5-orangeg.shields.io/badge/HTML5-supported-red
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellowhields.io/badge/license-MIT-green

---

## ✨ Funkcje

### 🎵 Odtwarzanie radia online

- Odtwarzanie internetowych stacji radiowych LIVE
- Szybkie przełączanie między stacjami
- Sterowanie odtwarzaniem (Play / Pause)
- Następna i poprzednia stacja
- Regulacja głośności

### ❤️ Ulubione stacje

- Dodawanie stacji do ulubionych
- Zapisywanie ulubionych w LocalStorage
- Szybki dostęp do najczęściej słuchanych rozgłośni

### 🌙 Timer snu

- Automatyczne wyłączenie odtwarzania po:
  - 15 minutach
  - 30 minutach
  - 45 minutach
  - 60 minutach
  - 90 minutach
  - 120 minutach

- Wizualny licznik pozostałego czasu

### 🎚 Korektor dźwięku (EQ)

3-pasmowy korektor audio oparty o Web Audio API:

- Bas (Low)
- Środek (Mid)
- Treble (High)

Możliwość resetowania ustawień jednym kliknięciem.

### 🎨 Motyw jasny / ciemny

- Automatyczne wykrywanie preferowanego motywu systemowego
- Przełączanie między trybem jasnym i ciemnym
- Zapamiętywanie ustawień użytkownika

### ➕ Dodawanie własnych stacji

Użytkownik może dodawać własne stacje radiowe:

- nazwa stacji
- gatunek muzyczny
- URL strumienia
- logo stacji

Własne stacje są zapisywane lokalnie w przeglądarce.

### 🔍 Wyszukiwanie

- filtrowanie stacji w czasie rzeczywistym
- wyszukiwanie po nazwie
- wyszukiwanie po gatunku

### ⌨ Skróty klawiaturowe

| Skrót | Funkcja |
|---------|----------|
| Space | Odtwarzanie / Pauza |
| ← | Poprzednia stacja |
| → | Następna stacja |
| ↑ | Głośniej |
| ↓ | Ciszej |
| M | Wyciszenie |
| Esc | Zamknięcie okna dialogowego |

### 📱 Responsywny interfejs

Aplikacja działa poprawnie na:

- komputerach
- tabletach
- smartfonach
- iPhone / Android

---

## 🎧 Wbudowane stacje radiowe

Przykładowe stacje dostępne w aplikacji:

- RMF FM
- RMF MAXX
- RMF Classic
- Radio ZET
- Radio Plus
- Eska
- Eska GO
- Eska Rock
- VOX FM
- TOK FM
- Radio 357
- Radio Nowy Świat
- Antyradio
- Chillizet
- Radio Gdańsk
- Radio Kaszëbë
- Dublin's Q102
- oraz wiele innych

---

## 🛠 Technologie

Projekt wykorzystuje:

### Frontend

- HTML5
- CSS3
- JavaScript ES6+

### Biblioteki

- TailwindCSS
- Font Awesome 6

### API

- Web Audio API
- Media Session API
- LocalStorage API

---

## 📂 Struktura projektu

```text
radio-by-tomi/
│
├── index.html
├── README.md
│
└── assets/
    ├── logos/
    └── screenshots/
```

---

## 🚀 Uruchomienie

### Opcja 1 — lokalnie

Pobierz repozytorium:

```bash
git clone https://github.com/twoje-konto/radio-by-tomi.git
```

Przejdź do katalogu:

```bash
cd radio-by-tomi
```

Uruchom plik:

```bash
index.html
```

lub otwórz go w przeglądarce.

---

### Opcja 2 — Live Server (VS Code)

Zainstaluj rozszerzenie:

```text
Live Server
```

Następnie:

```text
PPM na index.html
→ Open with Live Server
```

---

## 💾 Zapisywane dane

Aplikacja przechowuje lokalnie:

```javascript
radio_tomi_theme
radio_tomi_volume
radio_tomi_favorites
radio_tomi_custom_stations
```

Dane nie są wysyłane na żaden serwer.

---

## 📱 Obsługa Media Session

Aplikacja wspiera:

- Android
- iOS
- Dynamic Island
- ekran blokady telefonu
- przyciski multimedialne Bluetooth

Dostępne akcje:

- Play
- Pause
- Poprzednia stacja
- Następna stacja

---

## 🔒 Prywatność

Aplikacja:

✅ nie wymaga logowania

✅ nie zbiera danych użytkownika

✅ nie korzysta z zewnętrznych baz danych

✅ przechowuje ustawienia wyłącznie lokalnie

---

## 🧑‍💻 Autor

**ToMi**

Projekt stworzony jako nowoczesny internetowy odtwarzacz stacji radiowych z wykorzystaniem HTML, CSS i JavaScript.

---

## 📄 Licencja

MIT License

Możesz swobodnie używać, modyfikować i rozwijać projekt zgodnie z warunkami licencji MIT.

---

## 🎉 Wersja

Aktualna wersja:

```text
Radio by ToMi 3.0.5
```

Created by ToMi with AI ❤️
