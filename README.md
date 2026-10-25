# Protocols för Mac och Windows

Projektöversikt, checklistor och automatisk Excel-uppföljning.

**[Senaste stabila versionen: Protocols 0.8.1](https://github.com/allbinbjurstrom/protocols-releases/releases/tag/v0.8.1)**

- [Mac med Apple Silicon – 0.8.1](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.8.1/Protocols-0.8.1-Mac-arm64.zip)
- [Ladda ner Windows 0.8.1](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.8.1/Protocols-0.8.1-Windows-x64-Setup.exe)
- [Guide för OneDrive-mapp och Excel](INSTALLERA-ONEDRIVE.txt)
- [Alla filer, kontrollsummor och verifieringsresultat](https://github.com/allbinbjurstrom/protocols-releases/releases/tag/v0.8.1)

## Koppla en OneDrive-mapp i Windows 0.8.1

Öppna **Inställningar → OneDrive-mapp**, välj källmapp och Excel-mapp och klicka på **Aktivera och synka**. Källmappen behöver finnas lokalt i Utforskaren. OneNote och ett AI-konto behövs inte för mappkopplingen.

Protocols läser exporterade HTML-, MHT-, Word-, text-PDF- eller TXT-sidor enligt checklistmallen. Varje sida behöver projektnamn, unikt projektnummer, ansvarig och alla 21 kontrollpunkter. OneNotes egna .one-filer och genvägar kan inte läsas direkt. När en sida ändras i OneNote behöver även exportfilen uppdateras.

**Protocols-OneDrive.xlsx** samlar Översikt, Kontrollpunkter och Synkstatus. Privata arbetsanteckningar och det fullständiga källunderlaget utelämnas. Projekt och kontrollpunkter redigeras i källan. Låsta Excel-filer lämnas intakta; exporten kan göras om när filen har stängts.

Med appen öppen synkas mappen normalt var femte minut. Windows registrerar dessutom körning var tredje timme och efter inloggning, även med stängt appfönster. Datorn måste vara igång och kontot inloggat. OneDrive-klienten sköter molnsynkningen. Den befintliga OneNote-skrivbordskopplingen finns kvar som alternativ.

## Installera och uppdatera

Stäng Protocols och kör installationsfilen i samma Windows-konto som tidigare. Appidentiteten och befintliga krypterade projekt behålls. Installationsfilen är ännu inte digitalt signerad; företagets IT kan behöva godkänna den.

Protocols 0.8.1 levereras genom appens automatiska uppdatering på Mac och Windows. Öppna **Inställningar → Uppdateringar → Sök efter uppdateringar** för att hämta direkt. Med automatiska uppdateringar aktiverade hämtar appen paketet i bakgrunden och installerar när appen avslutas. Den befintliga signerade filförteckningen och SHA-256 verifieras före installation; uppdaterarens publika nyckel och signaturkrav behålls.

Lokala arbetsytor är krypterade för datorkontot. Excel-filer och exporterade säkerhetskopior är vanliga filer; välj mappar med lämplig åtkomst. Ingen Protocols-server eller månadsavgift behövs för mappsynkningen.

## Om repot

Detta repo innehåller nedladdningar, guider och versionsinformation. Källkoden till appen publiceras inte här. Kontrollsummor och verifieringsresultat för varje version finns bland filerna på respektive versionssida.
