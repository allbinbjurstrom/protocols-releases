# Protocols för Mac och Windows

Projektchecklistor med lokal OneNote-import och automatisk Excel-uppföljning.

**[Senaste versionen: Protocols 0.5.1](https://github.com/allbinbjurstrom/protocols-releases/releases/tag/v0.5.1)**

- [Windows x64 – installationsfil](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.1/Protocols-0.5.1-Windows-x64-Setup.exe)
- [Mac med Apple Silicon – packa upp appen](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.1/Protocols-0.5.1-Mac-arm64.zip)
- [Installationsguide](INSTALLERA.txt)

## Installera på Windows

Avsluta Protocols och kör installationsfilen i samma Windows-konto som tidigare.
Den gamla programversionen tas bort automatiskt. Projekt, inställningar och
lokala säkerhetskopior behålls.

Protocols 0.4.0 och senare kan även hämta nya versioner från
**Inställningar → Appuppdateringar**. Uppdateringarna verifieras med en signerad
filförteckning och SHA-256 innan de installeras.

## Arbeta med lokala projekt

Börja med **Importera → OneNote** eller **Ny fil**. Klistra in checklistan eller
välj en exporterad lokal OneNote-sida. Granska innehållet och spara projektet.
Projekt, importerat underlag och privata arbetsanteckningar lagras lokalt och
krypteras för datorkontot. Ingen Microsoft-appregistrering, tenant-ID eller
app-ID behövs. Tidigare importerade projekt finns kvar efter uppgradering.

Sidomenyn följer arbetets sju steg från import till **Gemensam Excel**.
Sidorna Överblick, Huvudprojekt och direkt OneNote-anslutning har tagits bort.
Appen öppnar det sparade projektet direkt vid start.

## Ledningsöversikt och autosynk

Öppna ledningsöversikten från **Inställningar**. Där finns även autosynk från en
lokal eller OneDrive-synkad mapp med exporterade OneNote-checklistor. Välj
källmapp, Excel-mapp och intervall. Synkningen körs medan appen är öppen.
Varje objekt får en Excel-fil och Protocols-Ledningsoversikt.xlsx samlar
uppföljningen. [Läs guiden](https://github.com/allbinbjurstrom/protocols-releases/releases/download/v0.5.1/Ledningsoversikt.md).

OneNote-exporterna kan vara HTML/HTM, MHT/MHTML, DOCX, PDF med text eller TXT
med appens fullständiga checklistmall. .one-filer och OneNote-genvägar behöver
exporteras först. Filer på OneDrive ska finnas tillgängliga lokalt.

## Valfri AI och lagring

Appen fungerar utan AI. Valfri ChatGPT-hjälp startas av användaren och kräver
att förslagen granskas innan de sparas. Arbetsanteckningar, källtext och privata
AI-utkast utelämnas från Excel och delbara sammanställningar.

Windows-installationen saknar Authenticode-certifikat. Mac-appen är lokalt
signerad men inte Apple-notariserad. Följ organisationens installationsrutin.
Kontrollsummor finns i [SHA256SUMS.txt](SHA256SUMS.txt).
