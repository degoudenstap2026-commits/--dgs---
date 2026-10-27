DE GOUDEN STAP — ONLINE OPSLAAN VOOR ALLE BEZOEKERS

Open index.html voor de website en admin.html voor het beheerpaneel.

ONLINE OPSLAAN INSTELLEN (eenmalig)
1. Maak een project aan op https://supabase.com/
2. Open SQL Editor in Supabase en voer de volledige inhoud van supabase-setup.sql uit.
3. Ga naar Project Settings > API. Kopieer de Project URL en de publishable/anon public key.
4. Open supabase-config.js en vul die twee waarden in. Gebruik NOOIT een service_role- of secret key in de website.
5. Maak in Supabase een beheeraccount aan via Authentication > Users > Add user.
6. Upload alle bestanden en de map assets naar je GitHub-repository en publiceer via GitHub Pages.
7. Open op je gepubliceerde website /admin.html, log in met dat beheeraccount, wijzig iets en klik op Opslaan.

Na deze setup worden opgeslagen wijzigingen centraal bewaard en kunnen alle bezoekers ze zien na het vernieuwen van de pagina.

LET OP
- Supabase is een externe dienst waarvoor je zelf een project moet aanmaken.
- Zonder ingevulde configuratie werkt alleen de lokale opslag in je browser.
- De public website kan inhoud lezen; alleen ingelogde accounts kunnen schrijven via de database policies.
- Bewaar nooit een service_role/secret key in de browser of GitHub.

PRODUCTLINKS TOEVOEGEN
1. Open admin.html op je gepubliceerde website.
2. Log in als beheerder.
3. Vul bij elk product het veld Product-URL / webshoplink in met een volledige link die begint met https:// (of http://).
4. Klik op Opslaan. Bij een werkende Supabase-configuratie worden de links online opgeslagen voor alle bezoekers.
5. In Onze Collectie verschijnt de knop “Bekijk product bij de webshop” als het product een geldige URL heeft.

Let op: zonder ingelogde Supabase-beheerder worden wijzigingen alleen lokaal in deze browser opgeslagen.
