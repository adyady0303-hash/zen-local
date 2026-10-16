# Zen Local — publicare gratuită

Acest depozit conține pagina publică GitHub Pages și fișierele mici de instalare. Arhiva Windows de 163 MB se publică separat ca asset într-un GitHub Release; nu o adăuga în istoricul Git.

## Setare GitHub Pages

1. Creează un depozit public numit `zen-local` în contul `adyady0303-hash`.
2. Încarcă în rădăcina depozitului fișierele din acest pachet.
3. În Settings → Pages, alege Deploy from a branch, ramura `main` și folderul `/ (root)`.
4. Creează un Release cu tag-ul `v1.0.0` și încarcă `Zen-Local-Windows-x64.zip` și `Zen-Local-Windows-x64.sha256.txt`.
5. Publică Release-ul. Linkul de descărcare al site-ului folosește automat ultimul Release publicat.

Adresa GitHub Pages va fi `https://adyady0303-hash.github.io/zen-local/`. Nu este necesar un domeniu plătit. Proiectul Diaspora AI nu este modificat.

## Ce descarcă utilizatorul

Aplicația este pentru Windows x64 și necesită instalarea separată a Ollama. Pachetul nu include modele AI și nu este semnat digital. Generarea AI rulează local pe calculatorul utilizatorului.