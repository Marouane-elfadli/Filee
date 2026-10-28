<p align="center">
  <a href="https://filee.sh"><img src="docs/media/banner-en.jpg" alt="Filee: Ziehen. Ablegen. Konvertiert." width="100%"></a>
</p>

<p align="center">
  <b>Ein kostenloser, quelloffener Dateikonverter, den du per Ziehen bedienst.</b><br>
  Halte eine Taste gedrückt (<kbd>Strg</kbd>, unter macOS <kbd>Option</kbd>), ziehe Dateien und lege sie im Ringmenü, das sich am Mauszeiger öffnet, auf einem Format ab.
</p>

<p align="center">
  <a href="https://filee.sh"><b>Website</b></a> ·
  <a href="https://github.com/KnifeLemon/Filee/releases/latest"><b>Download</b></a> ·
  <a href="https://www.linkedin.com/company/filee-sh/"><b>LinkedIn</b></a> ·
  <a href="#installation">Installation</a> ·
  <a href="#befehlszeile">Befehlszeile</a> ·
  <a href="#entwicklung">Entwicklung</a>
</p>

<p align="center">
  <a href="https://github.com/KnifeLemon/Filee/actions/workflows/ci.yml"><img src="https://github.com/KnifeLemon/Filee/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/KnifeLemon/Filee/releases/latest"><img src="https://img.shields.io/github/v/release/KnifeLemon/Filee?color=7F77DD&label=release" alt="Neueste Version"></a>
  <a href="https://github.com/KnifeLemon/Filee/releases"><img src="https://img.shields.io/github/downloads/KnifeLemon/Filee/total?color=1D9E75" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-3C3489" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/Linux-x64%20%7C%20ARM64-3C3489" alt="Linux x64 | ARM64">
  <img src="https://img.shields.io/badge/macOS-preview-534AB7" alt="macOS Vorschau">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-6A62C9" alt="MIT-Lizenz"></a>
</p>

<p align="center">
  <a href="https://trendshift.io/repositories/276987"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/weekly?language=C%23&v=2" alt="Filee: #1 C#-Repository der Woche auf Trendshift" width="250" height="55"></a>
  <a href="https://trendshift.io/repositories/276987"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/daily?language=C%23&v=2" alt="Filee: #1 C#-Repository des Tages auf Trendshift" width="250" height="55"></a>
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.es.md">Español</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a> ·
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.ar.md">العربية</a> ·
  <a href="README.pt-BR.md">Português (Brasil)</a> ·
  <a href="README.pt-PT.md">Português (Portugal)</a> ·
  <a href="README.fr.md">Français</a> ·
  <a href="README.th.md">ไทย</a> ·
  <a href="README.tr.md">Türkçe</a> ·
  <b>Deutsch</b>
</p>

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Direkt am Mauszeiger</b><br>
      Kein App-Fenster, das du öffnen musst.
      Die Formate erscheinen dort, wo du gerade bist, und zwar nur die, die zu den gezogenen Dateien passen.
    </td>
    <td width="33%" valign="top">
      <b>268 Formate, keine weitere Software</b><br>
      Bilder, PDF, Word, Excel, PowerPoint, HWP, E-Books, Archive, Schriften, CAD, 3D-Modelle und Geodaten funktionieren ohne Office, Hancom Office oder LibreOffice.
    </td>
    <td width="33%" valign="top">
      <b>Bleibt auf deinem Computer</b><br>
      Es wird nichts hochgeladen.
      Filee arbeitet offline und speichert das Ergebnis neben dem Original.
    </td>
  </tr>
</table>

## So sieht es aus

<p align="center">
  <a href="https://filee.sh"><img src="docs/media/demo-en.webp" alt="trip.jpg wird bei gedrückter Strg-Taste gezogen: Am Mauszeiger öffnet sich ein Ringmenü mit Formaten, die Datei wird auf PNG abgelegt, ein Fortschrittsring füllt sich und trip.png erscheint" width="820"></a><br>
  <sub>Sieh dir das 27-Sekunden-Video an und probiere die interaktive Demo auf <a href="https://filee.sh">filee.sh</a> aus</sub>
</p>

## Installation

Lade Filee von den [Releases](https://github.com/KnifeLemon/Filee/releases/latest) herunter.

<a href="https://apps.microsoft.com/detail/XPDCN05L89WS0C?referrer=appbadge&cid=github&mode=full"><img src="https://get.microsoft.com/images/de%20dark.svg" alt="Microsoft Store" width="200"></a>

- **Windows 10/11**: Führe `Filee-<version>-win-Setup.exe` aus oder entpacke `win-Portable.zip` und starte `Filee.exe`.
  - Setup ist Filees eigenes Installationsprogramm, in den Sprachen von Filee, und braucht nichts weiter auf dem PC.
  - Es kann das Explorer-Menü, den Start bei der Anmeldung, den Befehl `filee` und optionale Module einrichten.
  - Stille Installationen verstehen die Schalter von Inno Setup (`/VERYSILENT /SUPPRESSMSGBOXES`).
- **macOS 13+** (Vorschau): Entpacke das Paket `osx-arm64` oder `osx-x64` und führe `./install.sh` aus.
  - Oder öffne die `.dmg` und ziehe Filee in den Ordner „Programme“ (der Befehl `filee` wird von `install.sh` eingerichtet).
  - Das Paket ist noch nicht notarisiert. Erlaube den ersten Start unter Systemeinstellungen → Datenschutz & Sicherheit → **Trotzdem öffnen**.
- **Linux x64/ARM64** (Ubuntu 22.04+): Entpacke das Paket und führe `./install.sh` aus (ohne Root-Rechte, Python 3 erforderlich).
  - Ziehgesten funktionieren unter X11.
    Unter Wayland nutze die Ablagefläche und das Kontextmenü des Dateimanagers.

Filee zeigt neue Versionen in seinem Menü an und aktualisiert sich selbst, wobei Einstellungen und Module erhalten bleiben.
Nach einem Update zeigen ein paar Folien, was neu ist.

**Windows: Filee startet nicht (kein Fenster, keine Fehlermeldung)?**
Das passiert unter Windows 10, das lange nicht aktualisiert wurde, auf einem PC, dessen Prozessor den hardwaregestützten Stapelschutz (Hardware-enforced Stack Protection, CET) unterstützt.
Windows schaltet diesen Schutz ein, doch ihm fehlt eine Komponente, die .NET braucht, sodass Filee und Setup sofort beendet werden.

- **Empfohlen:** Installiere die verfügbaren Windows-Updates (das neueste kumulative Update).
- **Wenn ein Update nicht möglich ist:** Meist hilft es, den Schutz nur für Filee abzuschalten.
  Führe dazu als Administrator in PowerShell aus:

```powershell
Set-ProcessMitigation -Name Filee.exe -Disable UserShadowStack
Set-ProcessMitigation -Name filee-cli.exe -Disable UserShadowStack
```

Mache dasselbe mit dem Dateinamen von Setup (z. B. `Filee-<version>-win-Setup.exe`) oder nutze das portable ZIP, für das nur diese beiden Zeilen nötig sind.
Um es rückgängig zu machen, entferne die Einträge unter Windows-Sicherheit → App- und Browsersteuerung → Exploit-Schutz → Programmeinstellungen.

## Funktionen

- **Ein Ringmenü am Mauszeiger**: Halte eine Taste gedrückt, ziehe Dateien und lege sie auf einem Format ab.
  Es erscheinen nur Formate, die zu den Dateien passen.
- **Direkt aus dem Browser**: Ziehe ein Bild, einen Link auf eine Datei oder einen Download aus Chrome, Edge, Firefox oder Safari auf dieselbe Weise.
  - Filee speichert es in deinem Downloads-Ordner (oder behält nur die konvertierte Datei) und konvertiert es.
  - Links werden ohne die Anmeldung deines Browsers heruntergeladen.
- **Eine Symbolleiste pro Dateityp**, per Drag & Drop angeordnet, mit Vorlagen für:
  - Qualität, Größe, DPI
  - PDF-Seiten und Komprimierung
  - Video und Audio
  - Ausgabeordner und Dateinamen
- **Zwei Seiten für jedes Ringmenü**: Drücke <kbd>Tab</kbd> oder drehe das Mausrad, während es geöffnet ist, um es auf seltenere Formate und Werkzeuge umzudrehen.
- **Zuschneiden vor dem Konvertieren**: Die Zuschneiden-Option öffnet Bilder nacheinander.
  Ziehe den Rahmen auf, wähle ein Seitenverhältnis, und nur dieser Ausschnitt wird gespeichert.
- **Viele Dateien gleichzeitig**, parallel.
  Routen mit mehreren Schritten (HWP → HWPX → DOCX) werden automatisch gefunden.
- **Überwachte Ordner** konvertieren jede Datei, die darin landet.
- **Letzte Konvertierungen** auf der Startseite, jeweils mit Vorschaubild: Öffne das Ergebnis oder öffne es mit einer anderen App.
- **Weitere Wege**: das Kontextmenü, ein Tastenkürzel, die Ablagefläche und der [`filee`-Befehl](#befehlszeile).
- Helles und dunkles Design mit eigener Akzentfarbe und Transparenz des Ringmenüs, in English, Español, 日本語, 한국어, 简体中文, 繁體中文, Polski, हिन्दी, Русский, العربية (von rechts nach links), Português (Brasil), Français, नेपाली, ไทย, Türkçe, Português (Portugal) und Deutsch.

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="docs/media/page-toolbar-en.png" alt="Editor des Ringmenüs mit Profilen und Vorlagen"></td>
    <td width="50%"><img src="docs/media/page-home-en.png" alt="Startseite mit Ablagefläche und letzten Konvertierungen"></td>
  </tr>
  <tr>
    <td align="center"><sub>Ordne das Ringmenü per Drag & Drop an, ein Profil pro Dateityp</sub></td>
    <td align="center"><sub>Startseite: Ablagefläche und letzte Konvertierungen</sub></td>
  </tr>
</table>

## Formate

| Von | Nach |
|---|---|
| **Bilder**: JPG, PNG, WEBP, AVIF, TIFF, BMP, GIF, APNG, ICO, ICNS, JPEG XL, JPEG 2000, PSD/PSB, TGA, PPM, HEIC, QOI, DDS, PCX, MNG, CUR, …;<br>GIMP XCF, Kamera-RAW (CR2, CR3, NEF, ARW, DNG, …), DICOM, OpenEXR, HDR, FITS, JPEG XR (Windows), iPhone Live Photo (LIVP) lesbar | jedes dieser Formate (HEIC⁵), PDF, SVG (vektorisiert), skaliert, Graustufen;<br>Live/Motion Photos (iPhone, Android) → ihr Video (MP4, MOV⁵) und ein Video → Live Photo (iPhone) oder Motion Photo (Android)⁵, experimentell |
| **Vektor**: SVG, SVGZ, EMF, WMF, AI<br>EPS, PS¹<br>CDR, VSD, CGM, ODG, FODG² | PDF (Vektor), PNG und andere Bilder,<br>SVG ↔ SVGZ, SVG → DXF/DWG, PDF → EPS/PS¹, SVG → EMF, WMF, ODG² |
| **PDF** | DOCX, HWPX, TXT, PNG, JPG, TIFF, CBZ, PPTX (ein Bild pro Seite), SVG²;<br>zusammenführen (zuerst in einer Reihenfolge deiner Wahl), teilen, Seitenbereiche, komprimieren (kleinere PDFs) |
| **Dokumente**: DOCX, DOCM, DOTX, EML, Outlook MSG;<br>OFD (chinesische E-Rechnungen, amtliche Dokumente) lesbar<br>DOC, ODT, FODT, OTT, RTF, WPS, WPD, Pages, ClarisWorks, MacWrite, T602, …² | PDF, DOCX, HWPX, EPUB, TXT, HTML;<br>MSG → EML<br>ODT, FODT, OTT² |
| **Tabellen**: XLSX, XLSM, XLS, XLT, ODS, CSV, TSV<br>OTS, FODS, Numbers, ET² | PDF, XLSX, ODS, CSV, TSV, JSON, HWPX, HTML<br>XLT, OTS² |
| **Präsentationen**: PPTX, PPTM, POTX, POTM, PPSX<br>PPT, ODP, OTP, FODP, Keynote² | PDF, PNG, JPG, DOCX, HWPX<br>OTP² |
| **HWP**: HWP, HWPX | PDF, PNG, DOCX, HWPX ↔ HWP, TXT, Markdown, HTML |
| **Text**: TXT, LOG, Skriptquelltext (PY, PAC, BAT, COMMAND; wird gelesen, nie ausgeführt), Markdown, HTML;<br>MHTML (gespeicherte Webseiten) lesbar<br>reStructuredText, LaTeX, Org, AsciiDoc, Typst, MediaWiki, DocBook, Jupyter, Textile, man, OPML³ | UTF-8-TXT, PDF, DOCX, HWPX, EPUB<br>untereinander, PPTX-Folien³ |
| **E-Books**: EPUB, KEPUB, MOBI, AZW3, AZW, AZW4, FB2, CBZ, CBR, CB7, HTMLZ, TXTZ<br>LIT, LRF, CHM, PDB, …⁴ | PDF, EPUB, KEPUB (Kobo), DOCX, TXT, HTML, HWPX<br>MOBI, AZW3⁴ |
| **Video**⁵: MP4, MOV, MKV, WEBM, AVI, WMV, FLV, MPEG, Video CD (DAT), TS, M2TS, 3GP, OGV, VOB, … | MP4 (H.264, HEVC, AV1), WEBM, MOV, MKV, AVI, GIF, APNG, MP3, M4A, 720p,<br>Untertitel (SRT, ASS, WebVTT) |
| **Audio**⁵: MP3, M4A, AAC, WAV, FLAC, OGG, OPUS, WMA, AIFF, AMR, APE, WavPack, TTA, DSD (DSF, DFF), DTS, AC3, E-AC3, … | MP3, M4A (AAC, ALAC), WAV, FLAC, OGG, OPUS, AAC, WavPack, TTA, W64, AC3, E-AC3 |
| **Untertitel**: SRT, ASS/SSA, WebVTT, SAMI (SMI), LRC, TTML, MicroDVD, SCC | untereinander als UTF-8 (koreanische CP949-Dateien werden korrekt gelesen) |
| **Archive**: ZIP, ANSYS Workbench (WBPZ), 7Z, RAR, TAR, TAR.GZ, TAR.BZ2, TAR.XZ, GZ, ISO, CAB, DMG, ALZ, EGG, … | entpacken, ZIP, 7Z, TAR, TAR.GZ;<br>beliebige Dateien → ein ZIP |
| **CAD**: DWG, DXF | PDF, SVG, PNG, DWG ↔ DXF |
| **Schriften**: TTF, OTF, WOFF, WOFF2, EOT;<br>FON (Windows-Bitmap-Schriften) lesbar | untereinander;<br>FON → eine Schrift pro Größe |
| **Daten**: JSON, JSON Lines, YAML, TOML, XML<br>vCard, iCalendar | untereinander, CSV und XLSX (Tabellen);<br>vCard, iCalendar ↔ CSV |
| **3D-Modelle**: GLB, glTF, STL, OBJ (+ MTL), 3MF, PLY;<br>FBX lesbar | untereinander, PNG-Vorschau |
| **Geodaten (Vektor)**: Shapefile, GeoJSON, KML, KMZ, GPX<br>CSV mit Koordinaten; Garmin FIT lesbar | untereinander und CSV / XLSX / JSON;<br>projizierte Daten (UTM, Web Mercator, Lambert, Albers) werden als WGS-84-Längen-/Breitengrad ausgegeben |

Nicht markierte Formate funktionieren sofort, ohne Office, Hancom Office oder LibreOffice.
Markierte brauchen ein optionales Modul, das nur bei Bedarf heruntergeladen wird: ¹ Ghostscript, ² LibreOffice, ³ Pandoc, ⁴ calibre, ⁵ FFmpeg ([Details](docs/ENGINES.md)).

## Befehlszeile

Der Befehl `filee` nutzt dieselben Module und Vorlagen wie die App (Setup oder `install.sh` richtet ihn ein).

```
filee convert photo.heic --to jpg
filee convert *.png --to webp --quality 80 -o converted
filee watch D:\Inbox --to pdf --move-originals
```

Alle Befehle und Optionen: [filee.sh/cli](https://filee.sh/cli/) oder `filee help`.

## Entwicklung

Baue mit dem .NET-10-SDK unter Windows, macOS oder Linux:

```bash
git clone https://github.com/KnifeLemon/Filee.git
cd Filee
pwsh build/fetch-engines.ps1 -Only rhwp,pandoc   # optionale Module
dotnet run --project src/Filee.App
dotnet test
```

[Architektur](docs/ARCHITECTURE.md) · [Module](docs/ENGINES.md) · [Einen Konverter hinzufügen](docs/ADDING-A-CONVERTER.md) · [Eine Sprache hinzufügen](docs/ADDING-A-LANGUAGE.md) · [Mitwirken](CONTRIBUTING.md)

Pull Requests sind willkommen.
Wenn dir Filee ein paar Klicks erspart, hilft ein ⭐ anderen, es zu finden.

## Richtlinie zur Code-Signierung

Filee wird von **Myeonggu Kim** ([KnifeLemon](https://github.com/KnifeLemon)) entwickelt und veröffentlicht.

- Windows-Versionen werden mit einem Open-Source-Code-Signing-Zertifikat von [Certum](https://www.certum.eu/) signiert, das auf Myeonggu Kim ausgestellt ist („Open Source Developer MYEONGGU KIM“).
  - Frühere Versionen bis einschließlich 2.0.0 sind nicht signiert.
  - SmartScreen kann bei einer neuen Version weiterhin warnen, bis sie oft genug heruntergeladen wurde („Weitere Informationen“ → „Trotzdem ausführen“).
- macOS-Pakete sind ad hoc signiert und nicht notarisiert.
- Nur Dateien, die vom GitHub-Actions-Release-Workflow dieses Repositorys gebaut wurden, werden signiert, und jede Version wird von Hand signiert und freigegeben.
  - Bibliotheken und Programme, die ihre Hersteller signiert haben (.NET, SkiaSharp, ImageMagick, die Microsoft-C++-Laufzeit …), behalten ihre eigenen Signaturen. Mitgelieferte Komponenten, die unsigniert kommen (rhwp, 7-Zip und die meisten Bibliotheken), werden als Teil von Filee mit dem Zertifikat von Filee signiert.

### Datenschutzerklärung

Filee konvertiert Dateien auf deinem eigenen Computer und lädt sie nie hoch.
Es erhebt keine Nutzungsdaten und sendet keine Telemetrie.
Es verbindet sich nur in diesen Fällen mit dem Internet:

- um bei GitHub (`api.github.com`) nachzufragen, ob eine neuere Version existiert, kurz nach dem Start und danach alle paar Stunden.
  Das lässt sich unter Einstellungen → Über Filee abschalten („Automatisch nach Updates suchen“).
- um die Konvertierungsmodule herunterzuladen, die du installieren möchtest, von den offiziellen Adressen, die in [`engines.json`](src/Filee.Engines/Infrastructure/engines.json) festgelegt sind, sowie die Sprachen der Texterkennung (OCR), die eine Vorlage verwendet und die in [`ocr-languages.json`](src/Filee.Engines/Infrastructure/ocr-languages.json) festgelegt sind.
- wenn du auf einen Link klickst, der deinen Webbrowser öffnet.

## Unterstützen

Filee ist kostenlos und bleibt es.
Wenn du das Projekt unterstützen möchtest, wähle den Weg, der dir passt ([Fairy](https://fairy.hada.io/@filee) akzeptiert koreanische Karten und Easy-Pay).

**Dein Name oder Logo hier.**
Monatliche Unterstützer werden hier namentlich aufgeführt, Sponsoren erhalten ihr Logo hier und auf der Seite „Über Filee“.
Einmalige Unterstützer können ebenfalls um eine Nennung bitten.

<!-- sponsors: src/Filee.App/Assets/Sponsors/sponsors.json -->

<p align="center">
  <a href="https://github.com/sponsors/KnifeLemon"><img src="https://img.shields.io/badge/GitHub%20Sponsors-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="GitHub Sponsors"></a>
  <a href="https://patreon.com/KnifeLemon"><img src="https://img.shields.io/badge/Patreon-000000?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"></a>
  <a href="https://ko-fi.com/knifelemon"><img src="https://img.shields.io/badge/Ko--fi-FF6433?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi"></a>
  <a href="https://paypal.me/knifelemon"><img src="https://img.shields.io/badge/PayPal-002991?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"></a>
  <a href="https://fairy.hada.io/@filee"><img src="https://img.shields.io/badge/Fairy-2E9E6B?style=for-the-badge" alt="Fairy"></a>
</p>

## Lizenz

MIT, © 2026 Myeonggu Kim (KnifeLemon) und Filee-Mitwirkende.
Mitgelieferte Komponenten von Drittanbietern behalten ihre eigenen Lizenzen, die in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) aufgeführt sind.

<p align="center">
  <a href="https://star-history.com/#KnifeLemon/Filee&Date"><img src="https://api.star-history.com/svg?repos=KnifeLemon/Filee&type=Date" alt="Star-Verlauf" width="600"></a>
</p>
