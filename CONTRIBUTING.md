# zasady współpracy
Witamy w naszym projekcie! Aby współpraca przebiegała sprawnie i efektywnie, prosimy o przestrzeganie poniższych zasad.

## 1. przygotowanie projektu  
1.Sklonuj repozytorium na swój komputer.
'''bash
git clone https://github.com/USERNAME/REPOSITORY.git

2.Przejdź do katalogu projektu
'''bash
cd REPO

3.Utworz wirutalne srodowisko
'''bash
python -m venv .venv

4.Aktywuj środowisko i zainstaluj zależności, jeżeli projekt zawiera plik requirements.txt
'''bash
.venv\Scripts\Actiavte.ps1

'''bash
pip install -r requirements.txt




## 2. praca z gałęziami
Nie pracujemy bezpośrednio na gałęzi main.
Każde nowe zadanie realizujemy na osobnej gałęzi.
Nazwy gałęzi powinny jasno określać ich przeznaczenie:
feature/nazwa-funkcji – nowe funkcjonalności.
fix/nazwa-poprawki – poprawki błędów.
docs/nazwa-dokumentacji – zmiany w dokumentacji.
refactor/nazwa-zmiany – ulepszenia kodu.

## 3. zasady pisania kodu
Pisz czytelny, uporządkowany i zrozumiały kod.
Stosuj jednolity styl programowania.
Używaj opisowych nazw zmiennych, funkcji i klas.
Unikaj powtarzania tego samego kodu.
Usuwaj niepotrzebne fragmenty i komentarze.
Komentuj bardziej skomplikowane rozwiązania.

## 4. Commity
Każdy Commit powinien zawierac krótki i zrozumiały opis zmian w trybie rozkazującym.
'''bash

git commit -m"feat: dodaj zadanie..."
git commit -m"fix: popraw element input"
git commit -m"docs: zaktualizuj readme.md"

## 5. Zgłoszenie (issues)


## 6. Pull requestes
.

## 7. Komunikacja w zespole
Komunikuj się z pozostałymi członkami zespołu w sposób uprzejmy i profesjonalny.
Informuj zespół o postępach w pracy.
Zgłaszaj napotkane problemy i trudności.
Szanuj opinie oraz pomysły innych osób.
Nie wprowadzaj dużych zmian bez wcześniejszego uzgodnienia z zespołem.

**Dziękujemy za współpracę i wkład w rozwój projektu!**
