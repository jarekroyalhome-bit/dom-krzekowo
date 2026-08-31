# Dom na sprzedaż — Szczecin, Krzekowo (ZAN-DS-3)

Landing oferty. Wdrożenie: **kod na GitHub, hosting na Netlify** (jak slawoszewo / dom-mierzyn).

## Pliki
- `index.html` — cała strona
- `img/` — zdjęcia (26 wnętrz + agentka + logo)
- `.nojekyll`, `README.md`

## Wdrożenie (jak poprzednie projekty)
1. Pliki są już w repo GitHub `dom-krzekowo`.
2. Netlify → **Add new site → Import an existing project → GitHub → `dom-krzekowo`**.
3. Build settings zostaw puste (to statyczny HTML), Publish directory: `/` (root). **Deploy.**
4. Strona ruszy pod adresem `nazwa.netlify.app` (możesz zmienić w Site settings → Change site name, albo podpiąć własną domenę).

## Formularz „Umów prezentację"
Działa przez **Netlify Forms** — bez żadnego klucza. Po pierwszym deployu:
- Zgłoszenia widać w **Netlify → Forms → prezentacja**.
- Powiadomienia na maila: **Site settings → Forms → Form notifications → Add notification → Email → katarzyna@zlotyadres.pl**.
- Po publikacji zrób jedno testowe zgłoszenie, żeby potwierdzić, że mail dochodzi.

## Aktualizacja treści
Zmieniasz plik w repo GitHub → Netlify sam przebuduje i opublikuje (auto-deploy z gałęzi main).
