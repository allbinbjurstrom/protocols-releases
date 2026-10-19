# Protocols för Mac och Windows

Projektchecklistor, ledningsöversikt och automatisk Excel-uppföljning.

**[Senaste versionen: Protocols 0.5.0](https://github.com/allbinbjurstrom/protocols-releases/releases/tag/v0.5.0)**

- [Windows x64 – installationsfil](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.0/Protocols-0.5.0-Windows-x64-Setup.exe)
- [Mac med Apple Silicon – packa upp appen](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.0/Protocols-0.5.0-Mac-arm64.zip)
- [Installationsguide](INSTALLERA.txt)

## Automatisk uppdatering

Protocols 0.4.0 och senare kan hämta nya stabila versioner automatiskt.
Kontrollera **Inställningar → Appuppdateringar**. Där finns också **Sök efter
uppdateringar** och **Starta om och uppdatera**. Appen kontrollerar signatur,
filstorlek, plattform och SHA-256 före installation. Arbetet ska vara sparat
innan uppdateringen installeras. Äldre versioner behöver uppgraderas manuellt.

## Kom igång

1. Börja med **OneNote** eller **Ny fil** och fyll i projektuppgifterna.
2. Följ checklistans 21 kontrollpunkter från anbud till avslut.
3. Koppla Excel för automatisk uppföljning eller exportera en separat kopia.
4. Öppna **Inställningar → Öppna ledningsöversikt** för att följa alla projekt,
   ansvariga, skeden, uppdragsvärden och framsteg i arbetsytan.

## Autosynk från OneNote-mapp

Välj **Konfigurera autosynk**. Ange källmappen med exporterade
OneNote-checklistor, välj en Excel-mapp och aktivera automatisk synkning.
Undermappar kan ingå som huvudprojekt. Varje objekt får en egen Excel-fil och
**Protocols-Ledningsoversikt.xlsx** samlar alla objekt, kontrollpunkter och
synkproblem. Synkningen körs med valt intervall medan appen är öppen.

Källfiler kan vara HTML, HTM, MHT/MHTML, DOCX, PDF med text eller TXT och behöver
appens fullständiga checklistmall. `.one`-filer och OneNote-genvägar behöver
exporteras först. Vid OneDrive ska filerna finnas tillgängliga lokalt;
OneDrive sköter molnsynkningen. Läs [guiden för ledningsöversikt och
autosynk](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.0/Ledningsoversikt.md).

## Valfri AI och lagring

Appen fungerar utan AI. Valfri ChatGPT-hjälp förbereder projekt och arbetsutkast
som du granskar innan de sparas. Projektuppgifter, checklista, arbetsanteckningar
och valt underlag skickas till OpenAI först när du startar en AI-genomgång.

Arbetsytan lagras lokalt och krypteras för datorns användarkonto. Arbetsanteckningar,
källsidornas fullständiga text och privata AI-utkast utelämnas från Excel och
delbara sammanställningar. Exporterade säkerhetskopior och Excel-filer är
vanliga filer. Ändringar i Excel läses inte tillbaka till appen.

Mac-appen är lokalt signerad men inte Apple-notariserad. Windows-installationen
saknar Authenticode-certifikat. Följ organisationens installationsrutin.
Kontrollsummor finns i [SHA256SUMS.txt](SHA256SUMS.txt).
