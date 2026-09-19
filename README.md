# A6W — Aerobiczna Szóstka Weidera

42-dniowy program treningu brzucha (A6W) w formie aplikacji webowej (PWA) z głosowym prowadzeniem treningu po polsku. Działa offline, bez sklepu z aplikacjami.

**Otwórz aplikację:** https://geglus9.github.io/Sz-stka-Weidera/

## Instalacja na iPhone (Safari)

1. Otwórz powyższy link w **Safari** (musi być Safari, nie Chrome ani inna przeglądarka).
2. Stuknij ikonę trzech kresek na dole ekranu (obok paska adresu) i kliknij Udostępnij.
3. Przewiń listę w dół i wybierz **„Dodaj do ekranu początkowego”**.
4. Zatwierdź nazwę i stuknij **„Dodaj”** w prawym górnym rogu.
5. Na ekranie głównym pojawi się ikonka A6W — uruchamiaj aplikację z niej, nie z przeglądarki.

## Instalacja na Androidzie (Chrome)

1. Otwórz link w **Chrome**.
2. Stuknij menu (trzy kropki w prawym górnym rogu).
3. Wybierz **„Zainstaluj aplikację”** (lub „Dodaj do ekranu głównego”).
4. Potwierdź instalację.

## Offline

Po pierwszym otwarciu aplikacja zapisuje się w pamięci urządzenia (service worker) i działa bez internetu — łącznie z trybem samolotowym. Postęp treningu (ukończone dni) zapisywany jest lokalnie na urządzeniu, w tej jednej zainstalowanej ikonce.

## Reset postępu

W widoku listy dni na dole znajduje się przycisk **ZERUJ**, który po potwierdzeniu resetuje wszystkie dni do stanu początkowego.

## Pliki w repozytorium

| Plik | Rola |
|---|---|
| `index.html` | cała aplikacja (interfejs, logika, głos) |
| `manifest.json` | opis aplikacji dla systemu (nazwa, ikony, tryb pełnoekranowy) |
| `sw.js` | service worker — zapewnia działanie offline |
| `icon-192.png`, `icon-512.png` | ikony aplikacji |
