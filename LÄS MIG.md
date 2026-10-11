# AEM Cassette Player – installera på iPad

Det här är en fristående webbapp (PWA). Den måste ligga på en HTTPS-adress för att kunna
installeras och fungera offline. Två gratis sätt:

## Alternativ 1: Netlify Drop (enklast, ca 1 minut)
1. Packa upp zip-filen.
2. Gå till https://app.netlify.com/drop på en dator.
3. Dra hela mappen `aem-cassette-player` till sidan.
4. Du får en adress, t.ex. `https://namn-123.netlify.app`. Skapa ett gratiskonto om du vill att den ska ligga kvar.

## Alternativ 2: GitHub Pages
1. Skapa ett nytt repository och ladda upp innehållet i mappen (index.html ska ligga i roten).
2. Settings → Pages → Branch: `main` / root → Save.
3. Adressen blir `https://<användarnamn>.github.io/<repo>/`.

## Lägg till på iPad
1. Öppna adressen i **Safari**.
2. Tryck på **Dela** (fyrkant med pil uppåt).
3. Välj **Lägg till på hemskärmen** och tryck **Lägg till**.
4. Starta från ikonen – appen öppnas i helskärm utan webbläsarfält.

## Bra att veta
- Den installerade appen har ett eget bibliotek, skilt från Safari. Importera musiken i appen efter installationen.
- Efter första starten fungerar appen utan nätverk.
- iPadOS kan pausa ljudet när appen ligger i bakgrunden.
- Uppdatera: ladda upp nya filer till samma adress; appen hämtar den nya versionen vid nästa start med nätverk.
