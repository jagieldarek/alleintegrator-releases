# AlleIntegrator — wydania

To repozytorium zawiera **wyłącznie pliki wydań** aplikacji AlleIntegrator. Kod źródłowy
aplikacji nie jest tu publikowany.

Każde wydanie (`vX.Y.Z`) zawiera:

| Plik | Do czego służy |
|---|---|
| `release.json` | opis wydania: wersja, sumy kontrolne, identyfikatory obrazów Dockera |
| `docker-compose.yml` | konfiguracja instalacji |
| `update-engine.sh` | silnik aktualizacji uruchamiany przez aplikację |
| `install.sh`, `install.ps1` | instalatory (Linux/macOS, Windows) |
| `napraw.*`, `aktualizuj.*`, `jak-wrocic.txt` | naprawa i ręczna aktualizacja |
| `SHA256SUMS` | sumy kontrolne wszystkich plików |

Obrazy Dockera: `ghcr.io/jagieldarek/alleintegrator-api` i `ghcr.io/jagieldarek/alleintegrator-web`.

## Instalacja

Instrukcja krok po kroku: <https://alleintegrator.pl/pobierz>

## Bezpieczeństwo

Aplikacja pobiera pliki wyłącznie z tego repozytorium i sprawdza ich sumy kontrolne przed
uruchomieniem. Aplikacja nie wysyła nam żadnych informacji o instalacji.

Kontakt: <https://alleintegrator.pl/kontakt>
