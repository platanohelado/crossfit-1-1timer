CROSSFIT TIMER – PUBLICERA PÅ GITHUB PAGES

Filerna i denna mapp ska ligga direkt i roten av ett GitHub-repository:

index.html
manifest.webmanifest
service-worker.js
icons/icon-192.png
icons/icon-512.png

Snabbguide:
1. Skapa ett konto på https://github.com om du inte redan har ett.
2. Skapa ett nytt repository, exempelvis crossfit-timer.
3. Ladda upp ALLA filer och mappen icons.
4. Öppna repositoryts Settings.
5. Välj Pages i vänstermenyn.
6. Under Build and deployment:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
7. Spara.
8. Vänta tills GitHub visar webbadressen.
9. Öppna adressen i Chrome på Android.
10. Tryck på menyknappen med tre punkter och välj Installera app
    eller Lägg till på startskärmen.

Viktigt:
- Behåll mappstrukturen exakt.
- Appen fungerar offline efter att den öppnats minst en gång.
- Vid uppdateringar kan service-worker.js behöva få ett nytt CACHE_NAME,
  exempelvis crossfit-timer-v2.
