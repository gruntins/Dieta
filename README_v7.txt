GruntinsFIT v7

Izmaiņas:
- XSS aizsardzība visā aplikācijā: lietotāja / skenera / lokāli saglabāti teksti tiek sanitizēti un HTML izvade tiek escapota.
- Papildu drošības slānis ar Content Security Policy.
- Svara sadaļā datuma un svara ievades lauki ir centrēti un vairs neiziet ārpus kartītes mobilajā skatā.
- Svara laukā darbojas gan komats, gan punkts decimāldaļai (piem. 75,5 vai 75.5).
- Svara saglabāto datu validācija padarīta drošāka.
- Esošā GruntinsFIT v6 funkcionalitāte saglabāta.

GitHub aizvieto:
1. index.html
2. sw.js
3. manifest.webmanifest
4. icon-192.png / icon-512.png tikai tad, ja repozitorijā to nav

Pēc tam Commit changes. Service worker cache nosaukums ir gruntinsfit-v7.
