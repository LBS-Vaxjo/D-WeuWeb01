# Grunderna i GitHub

## Kursöversikt och lärandemål

Målet med den här kursen är att ge dig en kort introduktion till GitHub. Vi kommer också att tillhandahålla material för vidare lärande samt några idéer för att komma igång på vår plattform.

## Git och GitHub

Git är ett **distribuerat Versionshanteringssystem (VCS)**, vilket innebär att det är ett användbart verktyg för att enkelt spåra ändringar i din kod, samarbeta och dela. Med Git kan du spåra ändringarna du gör i ditt projekt så att du alltid har en historia över vad du har arbetat med och enkelt kan återgå till en äldre version om det behövs. Det gör också samarbete med andra enklare – grupper av människor kan arbeta tillsammans på samma projekt och sammanfoga sina ändringar till en gemensam källa!

GitHub är ett sätt att använda samma kraft som Git online med ett användarvänligt gränssnitt. Det används över hela mjukvaruvärlden och bortom det för att samarbeta och behålla projektens historia.

GitHub är hem för några av världens mest avancerade teknologier. Oavsett om du visualiserar data eller bygger ett nytt spel finns det en hel gemenskap och uppsättning verktyg på GitHub som kan ta dig till nästa steg. Den här kursen börjar med grunderna i GitHub, men vi kommer att gräva djupare senare.

## Förstå GitHub-flödet

GitHub-flödet är en lättviktsprocess som gör det möjligt för dig att experimentera och samarbeta med dina projekt enkelt, utan risken att förlora ditt tidigare arbete.

### Förråd (Repositories)

Ett förråd är där ditt projektarbete äger rum - tänk på det som din projektmapp. Det innehåller alla dina projekts filer och revisionshistorik. Du kan arbeta inom ett förråd själv eller bjuda in andra att samarbeta med dig på dessa filer.

### Kloning (Cloning)

När ett förråd skapas med GitHub, lagras det på distans i ☁️. Du kan klona ett förråd för att skapa en lokal kopia på din dator och sedan använda Git för att synkronisera de två. Detta gör det enklare att åtgärda problem, lägga till eller ta bort filer och skicka större ändringar. Du kan också använda redigeringsverktyget efter eget val istället för GitHub UI. Att klona ett förråd hämtar också ner all förrådsdata som GitHub har vid den tidpunkten, inklusive alla versioner av varje fil och mapp för projektet! Detta kan vara till hjälp om du experimenterar med ditt projekt och sedan inser att du gillade en tidigare version mer. För att lära dig mer om kloning, läs ["Klona ett förråd"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commita och skicka (Committing and pushing)

**Commita** och **skicka** är hur du kan lägga till ändringar du gjort på din lokala maskin till det avlägsna förrådet på GitHub. På det sättet kan din instruktör och/eller dina lagkamrater se ditt senaste arbete när du är redo att dela det. Du kan göra en commit när du har gjort ändringar i ditt projekt som du vill "checkpointa." Du kan också lägga till ett användbart **commit-meddelande** för att påminna dig själv eller dina lagkamrater om vilket arbete du har gjort (t.ex. "Lade till en README med information om vårt projekt").

När du har en commit eller flera commitar som du är redo att lägga till i ditt förråd kan du använda kommandot "push" för att lägga till dessa ändringar i ditt avlägsna förråd. Att commita och skicka kan kännas nytt i början, men vi lovar att du kommer att vänja dig 

## GitHub-termer att känna till

### Förråd (Repositories)

Vi har redan nämnt förråd, det är där ditt projektarbete äger rum, men låt oss prata lite mer om detaljerna kring dem! När du arbetar mer på GitHub kommer du att ha många förråd, vilket kan kännas förvirrande till en början. Lyckligtvis hjälper din ["GitHub-dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) till att enkelt navigera till dina förråd och se användbar information om dem. Se till att du är inloggad för att se det!

Förråd innehåller också **README**s. Du kan lägga till en README-fil i ditt förråd för att berätta för andra varför ditt projekt är användbart, vad de kan göra med ditt projekt och hur de kan använda det. Vi använder den här README:n för att kommunicera hur man lär sig Git och GitHub med dig. För att lära dig mer om förråd, läs ["Skapa, Klona och Arkivera Förråd"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) och ["Om README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Grenar (Branches)

Du kan använda grenar på GitHub för att isolera arbete som du inte vill sammanfoga med ditt slutliga projekt ännu. Grenar (branches) gör det möjligt för dig att utveckla funktioner, fixa buggar eller säkert experimentera med nya idéer i ett avgränsat område av ditt förråd. Vanligtvis kan du skapa en ny gren från ditt förråds standardgren, vanligtvis "main". Det skapar en ny arbetskopia av ditt förråd som du kan experimentera med. När dina nya ändringar har granskats av en lagkamrat eller du är nöjd med dem kan du sammanfoga dina ändringar i förrådets standardgren. För att lära dig mer om grenar, läs ["Om Grenar"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forkar (Forks)

En fork är ett annat sätt att kopiera ett förråd, men används vanligtvis när du vill bidra till någon annans projekt. Att forka ett förråd gör att du kan experimentera fritt med ändringar utan att påverka det ursprungliga projektet och är mycket populärt när man bidrar till öppen källkod. För att lära dig mer om att forka, läs ["Forka ett repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Dra-begäranden (Pull requests)

När du arbetar med grenar kan du använda ett dra-begärande för att informera andra om de ändringar du vill göra och be om deras feedback. När ett dra-begärande öppnas kan du diskutera och granska de potentiella ändringarna med medarbetare och lägga till fler ändringar om det behövs. Du kan lägga till specifika personer som granskare av ditt dra-begärande, vilket visar att du vill ha deras feedback på dina ändringar! När ett dra-begärande är redo att gå kan det sammanfogas med din huvudgren. För att lära dig mer om dra-begäranden, läs ["Om Dra-begäranden"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Ärenden (Issues)

Ärenden är ett sätt att spåra förbättringar, uppgifter eller buggar för ditt arbete på GitHub. Ärenden är ett bra sätt att hålla koll på alla uppgifter du vill arbeta med för ditt projekt och låta andra veta vad du planerar att arbeta med. Du kan också använda ärenden för att meddela ett favoritprojekt med öppen källkod om en bugg du har hittat eller en funktion du tycker skulle vara bra att lägga till!

För större projekt kan du hålla koll på många ärenden på en projektöversikt. GitHub-projekt hjälper dig att organisera och prioritera ditt arbete och du kan läsa mer om dem [i detta dokument "Om Projektöversikter"](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Du kommer troligtvis inte att behöva en projektöversikt för dina uppgifter, men när du går vidare till ännu större projekt är de ett bra sätt att organisera ditt teams arbete! Du kan också länka samman dra-begäranden och ärendena för att visa att en fix är på gång och för att automatiskt stänga ärendet när någon sammanfogar dra-begärandet. För att lära dig mer om ärenden och hur du länkar dem till dina dra-begäranden, läs ["Om Ärenden"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Din användarprofil

Din profil sida berättar för människor historien om ditt arbete genom de förråd du är intresserad av, de bidrag du har gjort och de samtal du har haft. Du kan också ge världen en unik vy in i vem du är med din profil README. Du kan använda din profil för att låta framtida arbetsgivare veta allt om dig! För att lära dig mer om din användarprofil och hur du lägger till och uppdaterar din profil README, läs ["Hantera din Profil README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Använda markdown på GitHub

Du har kanske redan lagt märke till det, men du kan lägga till lite rolig formatering i dina ärenden, dra-begäranden och filer. ["Markdown"](https://guides.github.com/features/mastering-markdown/) är ett enkelt sätt att formatera dina ärenden, dra-begäranden och filer med några enkla syntax. Detta kan vara användbart för att organisera din information och göra det enklare för andra att läsa. Du kan också lägga till gifs och bilder för att underlätta förståelsen! För att lära dig mer om att använda GitHub's variant av markdown, läs ["Grundläggande Skriv- och Formateringssyntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Engagera dig med GitHub-communityn

GitHub-communityn är omfattande. Det finns många typer av människor som använder GitHub i sin vardag - studenter som du, professionella utvecklare, entusiaster som arbetar med öppen källkod och upptäcktsresande som just hoppar in i världen av mjukvaruutveckling på egen hand. Det finns många sätt du kan interagera med den större GitHub-communityn, men här är tre platser där du kan börja.

#### Stjärnmarkera förråd

Om du tycker att ett förråd är intressant eller om du vill hålla koll på det, stjärnmarkera det! När du stjärnmarkerar ett förråd används det också som en signal för att ge bättre rekommendationer på github.com/explore. Om du vill komma tillbaka till dina stjärnmarkerade förråd kan du göra det via din användarprofil. För att lära dig mer om att stjärnmarkera förråd, läs ["Spara Förråd med Stjärnor"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars).

#### Följ användare

Du kan följa människor på GitHub för att få meddelanden om deras aktivitet och upptäcka projekt i deras communityn. När du följer en användare kommer deras offentliga GitHub-aktivitet att visas på din dashboard så att du kan se alla coola saker de arbetar med. För att lära dig mer om att följa användare, läs ["Följa Personer"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Bläddra i GitHub Explore

GitHub Explore är en bra plats att göra just det... utforska :smile: Du kan hitta nya projekt, evenemang och utvecklare att interagera med.

Du kan kolla in GitHub Explore-webbplatsen [på github.com/explore](https://github.com/explore). Ju mer du interagerar med GitHub, desto mer anpassad blir din Explore-vy.

## 📝 Valbara nästa steg

* Öppna en dra-begäran och låt din lärare veta att du har avslutat den här kursen.
* Skapa en ny markdown-fil i det här förrådet. Låt dem veta vad du har lärt dig och vad du fortfarande är förvirrad över! Experimentera med olika stilar!
* Skapa din profil README. Låt världen veta lite mer om dig! Vad är du intresserad av att lära dig? Vad jobbar du på? Vad är din favorithobby? Lär dig mer om att skapa din profil README i dokumentet ["Hantera din Profil README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Gå till din användardashboard och skapa ett nytt förråd. Experimentera med funktionerna inom det förrådet för att bekanta dig med dem.
* [Låt oss veta vad du gillade eller inte gillade med innehållet i den här kursen](https://support.github.com/contact/education). Vad skulle du vilja se mer av? Vad skulle vara intressant eller hjälpsamt för din inlärningsresa?

## 📚 Resurser

* [En kort video som förklarar vad GitHub är](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Git och GitHub lärande resurser](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Förstå GitHub-flödet](https://guides.github.com/introduction/flow/)
* [Hur man använder GitHub-grenar](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interaktiv Git-träningsmaterial](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Utbildningscommunityns forum](https://education.github.community/)
* [GitHub-communityns forum](https://github.community/)
