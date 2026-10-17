# Zen Local

Pagina publică: https://adyady0303-hash.github.io/zen-local/

Acest depozit conține pagina GitHub Pages și fișierele text de instalare. Pachetul Windows este publicat separat în GitHub Releases, nu în istoricul Git.

## Release curent: 1.0.3

Asset-ul principal este `Zen-Local-Setup-1.0.3-x64.exe` (aproximativ 156 MiB), împreună cu fișierul SHA-256. Instalatorul autonom verifică fișierele extrase, creează pictograme pe desktop și în meniul Start și pornește Zen Local. Nu este necesară extragerea manuală a unui ZIP.

Aplicația pentru Windows x64 folosește Ollama și modelul AI instalate separat. Remapările simple sunt instantanee; generarea AI pentru cereri complexe folosește Ollama local. Verificarea GPC integrată caută probleme structurale, dar compilarea finală se face în Zen Studio. Pachetul nu este semnat digital, astfel că Windows poate afișa un avertisment de editor necunoscut.

## GitHub Pages

Pages folosește ramura `main` și folderul rădăcină `/`. Nu este necesar un domeniu plătit. Site-ul distribuie aplicația desktop; nu rulează AI în browser.
