# Redigeringsmanual - Freelancing Hairdresser CMS

*En komplett guide för att hantera din webbplats med Payload CMS*

## Översikt

Detta CMS-system är särskilt utformat för frisörverksamheten och använder svenska som standardspråk. Systemet gör det möjligt att skapa flexibla webbsidor, blogginlägg och hantera media på ett professionellt sätt.

## 🏠 Kom igång

### Logga in
1. Gå till admin-panelen (vanligtvis `/admin`)
2. Logga in med dina uppgifter
3. Du kommer till huvudpanelen med en översikt av systemet

### Första intryck
- **Dashboard**: Visar senaste aktivitet och snabbåtgärder
- **Navigation**: Vänster sidopanel med alla samlingar
- **Live Preview**: Realtidsförhandsgranskning av dina ändringar

## 📄 Sidor (Pages)

### Skapa en ny sida
1. Klicka på **"Pages"** i vänstermenyn
2. Klicka på **"Add New"**
3. Fyll i:
   - **Titel**: Sidans namn (visas i webbläsaren)
   - **Slug**: URL-sökväg (genereras automatiskt från titeln)

### Sidans struktur
Varje sida består av tre flikar:

#### 🎯 Hero-flik
Välj hur din sida ska börja:
- **Ingen**: Ingen header-sektion
- **Låg påverkan**: Bara text och länkar
- **Medelhög påverkan**: Text, länkar och bild
- **Hög påverkan**: Stor och iögonfallande header

#### 📝 Content-flik
Här bygger du sidans innehåll med olika block:

**Innehållsblock (Content)**
- Flexibel textlayout i kolumner
- Stöd för rubriker (H2, H3, H4)
- Kan länkas till andra sidor

**Call to Action (CTA)**
- Marknadsföringssektion med knappar
- Upp till 2 länkar per CTA
- Olika knappdesigner (standard, outline)

**Mediablock**
- Enkel bildvisning
- Välj från mediabiblioteket

**Arkivblock**
- Visa samling av blogginlägg
- Filtrera efter kategori
- Anpassa antal inlägg som visas

**Formulärblock**
- Bädda in kontaktformulär
- Välj från skapade formulär

#### 🔍 SEO-flik
Optimera för sökmotorer:
- **Meta-titel**: Visas i sökresultat
- **Meta-beskrivning**: Kort beskrivning i sökresultat
- **Delningsbild**: Bild som visas när sidan delas

### Publicering
- **Spara utkast**: Sparar ändringar utan att publicera
- **Publicera**: Gör sidan synlig för besökare
- **Schemalägg**: Välj datum för automatisk publicering

## 📝 Blogginlägg (Posts)

### Skapa ett inlägg
1. Gå till **"Posts"** → **"Add New"**
2. Fyll i:
   - **Titel**: Inläggets rubrik
   - **Hero-bild**: Huvudbild för inlägget
   - **Innehåll**: Huvudtext med formatering

### Inläggets innehåll
Använd den avancerade textredigeraren för:
- Formatering (fet, kursiv, understruken)
- Rubriker och listor
- Länkar till andra sidor
- Inbäddade bilder

### Specialblock för inlägg
**Bannerblock**
- Viktiga meddelanden i 4 stilar:
  - Info (blå)
  - Varning (gul)
  - Fel (röd)
  - Framgång (grön)

**Kodblock**
- Visa kod med syntax-highlighting
- Stöd för TypeScript, JavaScript, CSS

### Organisera inlägg
- **Kategorier**: Organisera inlägg efter ämne
- **Relaterade inlägg**: Länka till liknande innehåll
- **Författare**: Tilldela författare till inlägget

## 🖼️ Media (Bilder & filer)

### Ladda upp filer
1. Gå till **"Media"** → **"Add New"**
2. Dra och släpp filer eller klicka för att välja
3. Fyll i:
   - **Alt-text**: Beskrivning för tillgänglighet
   - **Bildtext**: Valfri beskrivning

### Automatisk bildoptimering
Systemet skapar automatiskt olika storlekar:
- **Miniatyr**: 300px bred
- **Kvadrat**: 500x500px
- **Liten**: 600px bred
- **Medium**: 900px bred
- **Stor**: 1400px bred
- **Extra stor**: 1920px bred
- **Delningsbild**: 1200x630px

### Fokuspunkt
- Välj viktigaste delen av bilden
- Säkerställer bra beskärning på olika skärmar

## 🗂️ Kategorier

### Skapa kategorier
1. Gå till **"Categories"** → **"Add New"**
2. Fyll i:
   - **Titel**: Kategorinamn
   - **Slug**: URL-vänlig version

### Användning
- Organisera blogginlägg
- Filtrera innehåll i arkivblock
- Hjälper besökare hitta relaterat innehåll

## 🔗 Navigation

### Header-navigation
1. Gå till **"Globals"** → **"Header"**
2. Lägg till upp till 6 navigationslänkar
3. Varje länk kan vara:
   - **Intern**: Länk till sidor på webbplatsen
   - **Extern**: Länk till andra webbplatser
   - **Ny flik**: Öppna i nytt fönster

### Footer-navigation
1. Gå till **"Globals"** → **"Footer"**
2. Konfigurera på samma sätt som header
3. Visas längst ner på alla sidor

## 🎨 Designtips

### Användning av block
- **Använd CTA-block** för viktiga handlingar (boka tid, kontakta)
- **Innehållsblock** för huvudtext i kolumner
- **Mediablock** för att bryta upp text med bilder
- **Arkivblock** för att visa senaste blogginlägg

### Bilder
- Använd högkvalitativa bilder (minst 1200px breda)
- Fyll alltid i alt-text för tillgänglighet
- Välj fokuspunkt för bästa beskärning

### SEO-optimering
- Skriv unika meta-titlar för varje sida
- Håll meta-beskrivningar under 160 tecken
- Använd beskrivande sluggar (URL:er)

## 🔄 Arbetsflöde

### Typisk arbetsprocess
1. **Skapa utkast**: Börja med att spara som utkast
2. **Använd förhandsgranskning**: Se hur det ser ut live
3. **Granska SEO**: Kontrollera meta-information
4. **Publicera**: Gör innehållet synligt för besökare

### Versionshantering
- Systemet sparar automatiskt var 0,1 sekund
- Upp till 50 versioner sparas per dokument
- Återställ till tidigare versioner vid behov

## 🔍 Sökfunktion

### Sök innehåll
- Använd sökfältet i admin-panelen
- Sök i titel, innehåll och meta-information
- Filtrera efter typ av innehåll

## 📱 Responsiv design

### Förhandsgranskning
Testa hur din sida ser ut på olika enheter:
- **Mobil**: 375px bred
- **Surfplatta**: 768px bred
- **Dator**: 1440px bred

## 🚀 Avancerade funktioner

### Schemalagd publicering
- Sätt datum och tid för automatisk publicering
- Perfekt för kampanjer och evenemang
- Innehållet publiceras automatiskt

### Omdirigeringar
- Hantera gamla URL:er som flyttats
- Automatisk omdirigering till nya sidor
- Behåll SEO-värde från gamla länkar

### Formulär
- Skapa kontaktformulär
- Anpassa fält efter behov
- Få meddelanden via e-post

## 🆘 Vanliga frågor

**Q: Kan jag ångra ändringar?**
A: Ja, gå till versionshistorik och återställ till tidigare version.

**Q: Hur stora kan bilderna vara?**
A: Systemet optimerar automatiskt, men använd inte filer större än 10MB.

**Q: Kan jag se hur sidan ser ut innan publicering?**
A: Ja, använd förhandsgranskningsfunktionen i redigeraren.

**Q: Hur skapar jag en länk till en annan sida?**
A: Använd länkfunktionen i textredigeraren och välj intern länk.

**Q: Kan jag redigera navigation utan att påverka publicerade sidor?**
A: Nej, navigation är global och påverkar alla sidor direkt.

## 📞 Support

Om du behöver hjälp:
1. Kontrollera denna manual först
2. Testa i förhandsgranskningsläge
3. Kontakta systemadministratören

---

*Denna manual uppdateras regelbundet. Senast uppdaterad: Juli 2025*