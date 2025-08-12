EntryPL — statyczny landing PL/EN pod Cloudflare Pages

SZYBKI DEPLOY (GitHub → Cloudflare Pages)
1) Utwórz nowe repo na GitHub i wrzuć zawartość tego folderu.
2) Cloudflare → Pages → Create project → Connect to GitHub → wybierz repo.
3) Ustaw:
   - Framework preset: None
   - Build command: (puste)
   - Output directory: /
4) Po deployu dodaj domenę: Pages → Custom domains → entrypl.com
5) Przekierowanie www → apex działa przez plik _redirects.

FORMULARZ: Podmień action w <form> na swój endpoint (Formspree/Workers).

SEO: Ustaw docelowe <title> i <meta>. Hreflang wskazuje https://entrypl.com/ oraz https://entrypl.com/en/

HTTPS: W Cloudflare włącz „Always Use HTTPS”.

Powodzenia!
