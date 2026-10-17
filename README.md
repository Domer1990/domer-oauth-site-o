# DOMER Drive Local — publiczna strona informacyjna OAuth

Statyczna witryna HTML/CSS, bez skryptów zewnętrznych, analityki, reklam i własnych plików cookies. Zawiera stronę informacyjną, politykę prywatności, cookies i warunki korzystania.

Repozytorium przeznaczone wyłącznie do publikacji publicznych plików strony. Nie umieszczaj tutaj sekretów, konfiguracji klienta Google OAuth, tokenów ani danych użytkowników.

## Hosting GitHub Pages

Repozytorium: https://github.com/Domer1990/domer-oauth-site-o

Po opublikowaniu przez **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root)** spodziewane adresy:

- https://domer1990.github.io/domer-oauth-site-o/
- https://domer1990.github.io/domer-oauth-site-o/privacy.html
- https://domer1990.github.io/domer-oauth-site-o/cookies.html
- https://domer1990.github.io/domer-oauth-site-o/terms.html

Linki muszą zostać sprawdzone pod kątem odpowiedzi HTTP i zawartości — samo istnienie repozytorium nie włącza automatycznie GitHub Pages.

## Google OAuth

W Google Auth Platform dla istniejącego projektu „Domer Drive Local” adresy homepage i privacy policy powinny wskazywać działającą publiczną witrynę. Google może wymagać weryfikacji własności domeny w Search Console oraz zaakceptowania domeny w Authorized domains. Adres na współdzielonej domenie github.io może zostać odrzucony mimo poprawnego wdrożenia GitHub Pages. W takim przypadku należy użyć własnej weryfikowalnej domeny; nie należy publikować danych ani adresów środowiska prywatnego.

Zakres używany przez aplikację: https://www.googleapis.com/auth/drive. Polityka prywatności opisuje rzeczywisty szeroki zakres OAuth oraz ograniczenie faktycznie wykonywanych operacji.

## Zakres publiczny

Repozytorium nie ma połączenia z prywatną infrastrukturą aplikacji. GitHub Pages służy jedynie jako hosting publicznych dokumentów informacyjnych.
