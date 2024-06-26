# Ce este nou în NVDA


## 2023.2

Această versiune vine la pachet cu Magazinul de Suplimente, care înlocuiește Administratorul de Suplimente.
În Magazinul de Suplimente puteți căuta, instala și actualiza suplimentele comunității.
Puteți anula manual defectele de incompatibilitate pentru suplimentele vechi asumându-vă acest risc.

Există noi funcționalități braille, comenzi și suport pentru afișaje.
De asemenea, există noi gesturi de intrare pentru OCR și pentru navigarea prin obiecte.
În Microsoft Office, sunt îmbunătățite navigarea și raportarea formatării.

Sunt multe remedieri de erori, în special în ceea ce privește braille, Microsoft Office, browserele web și Windows 11.

Au fost actualizate eSpeak-NG, traducătorul braille LibLouis și Unicode CLDR.

### Noi funcționalități

* Magazinul de Suplimente a fost adăugat la NVDA. (#13985)
  * Răsfoiți, căutați, instalați și actualizați suplimentele comunității.
  * Anulare manuală pentru problemele de incompatibilitate cu suplimente învechite.
  * Administrarea suplimentelor a fost eliminată și înlocuită de Magazinul de Suplimente.
  * Pentru mai multe informații, vă rugăm să citiți ghidul de utilizare actualizat.
* S-a adăugat pronunția simbolurilor Unicode:
  * simboluri braille precum „⠐⠣⠃⠗⠇⠐⠜”. (#14548)
  * Simbolul tastei Mac Opțiune „⌥”. (#14682)
* Noi gesturi de intrare:
  * Un gest (care nu a fost setat) pentru a parcurge limbile disponibile pentru Windows OCR. (#13036)
  * Un gest (care nu a fost setat) pentru a parcurge modurile de afișare a mesajelor braille. (#14864)
  * Un gest (care nu a fost setat) pentru a comuta afișarea indicatorul de selecție pentru braille. (#14948)
* S-au adăugat gesturi pentru afișajele Tivomatic Caiku Albatross Braille. (#14844, #15002)
  * se afișează dialogul de setări braille
  * accesarea barei de stare
  * selectarea formei cursorului braille
  * selectarea modului de afișare a mesajelor braille
  * activarea/dezactivarea cursorului braille
  * Comutarea stării afișării indicatorului de selecție în Braille
* O nouă opțiune Braille pentru comutarea afişării indicatorului de selecție (punctele 7 și 8). (#14948)
* În Mozilla Firefox și Google Chrome, NVDA raportează acum când un control deschide un dialog, grilă, listă sau arbore dacă autorul a specificat acest lucru folosind aria-haspopup. (#14709)
* Acum este posibil să utilizați variabile de sistem (cum ar fi `%temp%` sau `%homepath%`) în specificația căii în timp ce creați copii portabile ale NVDA. (#14680)
* S-a adăugat suport pentru atributul `aria-brailleroledescription` ARIA 1.3, permițând autorilor web să suprascrie tipul unui element afișat pe afișajul Braille. (#14748)
* Când textul evidențiat este activat în Formatarea documentului, culorile evidențiate sunt acum raportate în Microsoft Word. (#7396, #12101, #5866)
* Când culorile sunt activate în Formatarea documentului, culorile fundalului sunt acum raportate în Microsoft Word. (#5866)
* Când apăsați `numpad2` de trei ori pentru a raporta valoarea numerică a caracterului în poziția cursorului de revizuire, informațiile sunt acum furnizate și în braille. (#14826)
* NVDA redă acum audio prin API-ul Windows Audio Session (WASAPI), care poate îmbunătăți capacitatea de răspuns, performanța și stabilitatea vorbirii și sunetelor NVDA.
Acest lucru poate fi dezactivat în Setări avansate dacă apar probleme la redare. (#14697)
* Când utilizați comenzile rapide Excel pentru a comuta format, cum ar fi aldine, cursive, subliniere și barare a unei celule în Excel, rezultatul este acum raportat. (#14923)
* S-a adăugat suport pentru afișajul Help Tech Activator Braille. (#14917)
* În versiunea Windows actualizată 10 May 2019 și cele ulterioare, NVDA poate anunța nume de desktop virtual atunci când le deschide, le schimbă și le închide. (#5641)
* Acum este posibil ca volumul sunetelor și bipurilor NVDA să urmeze setarea de volum a vocii pe care o utilizați.
Această opțiune poate fi activată în Setări avansate. (#1409)
* Acum puteți controla separat volumul sunetelor NVDA.
Acest lucru se poate face folosind Windows Volume Mixer. (#1409)
  - 

### Modificări

* Translatorul braille LibLouis actualizat la [3.26.0](https://github.com/liblouis/liblouis/releases/tag/v3.26.0). (#14970)
* CLDR a fost actualizat la versiunea 43.0. (#14918)
* Simbolurile Dash și em-dash vor fi întotdeauna trimise la sintetizator. (#13830)
* Schimbări LibreOffice:
  * Când este raportată locația cursorului de examinare, locația curentă a cursorului de scriere este acum raportată în raport cu pagina curentă în LibreOffice Writer pentru versiunile LibreOffice >= 7.6, similar cu ceea ce se face pentru Microsoft Word. (#11696)
  * Anunțul barei de stare (de exemplu, declanșat de `NVDA+end`) funcționează pentru LibreOffice. (#11698)
* Distanța raportată în Microsoft Word va onora acum unitatea definită în opțiunile avansate ale Word, chiar și atunci când utilizați UIA pentru a accesa documentele Word. (#14542)
* NVDA răspunde mai rapid la mutarea cursorului în comenzile de editare. (#14708)
* Driver Baum Braille: adaugă mai multe gesturi Braille pentru executarea comenzilor comune de la tastatură, cum ar fi `windows+d`, `alt+tab` etc.
Vă rugăm să consultați ghidul utilizatorului NVDA pentru o listă completă. (#14714)
* Când utilizați un afișaj Braille prin driverul standard Braille HID, dpad-ul poate fi folosit pentru a emula tastele săgeți și enter. De asemenea, spațiu+punct1 și spațiu+punct4 acum îndeplinesc funcţiile de săgeata sus și respectiv în jos. (#14713)
* Scriptul de raportare a destinației unui link acum raportează din poziția de focalizare, mai degrabă decât din navigatorul de obiecte. (#14659)
* Crearea copiilor portabile nu mai necesită introducerea unei litere de unitate ca parte a locaţiei absolute. (#14681)
* Dacă Windows este configurat să afișeze secunde în ceasul din bara de sistem, folosind `NVDA+f12` pentru a raporta ora, acum NVDA respectă această setare. (#14742)
* NVDA va raporta acum grupările neetichetate care au informații utile despre poziție, cum ar fi în versiunile recente ale meniurilor Microsoft Office 365. (#14878)

### Defecte rezolvate

* NVDA nu va mai trece în mod inutil la no braille de mai multe ori în timpul detectării automate, rezultând un jurnal mai curat, suprasolicitarea fiind redusă. (#14524)
* NVDA va reveni acum la USB dacă un dispozitiv Bluetooth HID (cum ar fi HumanWare Brailliant sau APH Mantis) este detectat automat și o conexiune USB devine disponibilă.
Acest lucru a funcționat înainte doar pentru porturile serial Bluetooth. (#14524)
* Acum este posibil să utilizați caracterul backslash în câmpul de înlocuire al unei intrări de dicționar, atunci când tipul nu este setat la expresie regulată. (#14556)
* În modul Navigare, NVDA nu va mai ignora în mod incorect mutarea focalizării către un element arborescent sau superior, de ex. trecerea de la un control la elementul părinte din listă sau celula grilă. (#14611)
  * Rețineți totuși că această remediere se aplică numai atunci când opțiunea Setează automat focalizarea sistemului la elementele focalizabile este dezactivată (care este implicit).
* NVDA nu mai face ca ocazional Mozilla Firefox să se blocheze sau să înceteze să răspundă. (#14647)
* În Mozilla Firefox și în Google Chrome, caracterele tastate nu mai sunt anunțate în unele casete de text, chiar și atunci când opțiunea „Pronunță caracterele tastate” este dezactivată. (#14666)
* Puteți folosi acum modul de navigare din Chromium Embedded Controls acolo unde înainte nu se putea. (#13493, #8553)
* Pentru simbolurile care nu au o descriere în traducerea curentă, va fi utilizat nivelul simbolului englezesc implicit. (#14558, #14417)
* Rezolvări pentru Windows 11:
  * NVDA poate anunța din nou conținuturile barei de stare a Notepad. (#14573)
  * Comutarea între file va anunța numele și poziția noii file pentru Notepad și pentru File Explorer. (#14587, #14388)
  * NVDA va anunța din nou elementele candidate la inserarea textului în limbi precum chineză și japoneză. (#14509)
* În Mozilla Firefox, deplasarea mausului peste textul de după un link raportează cum trebuie acel text. (#9235)
* În aplicația Calculator din Windows 10 și 11, o copie portabilă a NVDA nu va mai face nimic și nu va mai reda tonuri de eroare la introducerea expresiilor în calculatorul standard din modul suprapunere compactă. (#14679)
* La încercarea de amunțare a unui link fără atributul href, NVDA nu mai este silențios.
În schimb, va spune că link-ul nu are destinație. (#14723)
* Câteva rezolvări la intrarea/ieșirea pentru afișajele braille care au avut drept consecință mai puține erori frecvente și blocări ale NVDA. (#14627)
* NVDA se recuperează din mai multe situații, cum ar fi aplicațiile care nu mai răspund, ceea ce anterior a determinat blocarea completă. (#14759)
* Destinația link-urilor grafice este raportată corect în Chrome și Edge. (#14779)
* Este din nou posibilă accesarea, în Windows 11, a opțiunilor „Licență” și „Colaboratori” din meniul „Ajutor” al NVDA. (#14725)
* La forțarea suportului UIA cu anumite terminale și console, este remediată o eroare care a cauzat înghețarea și spam-ul fișierului jurnal. (#14689)
* Pentru NVDA, anunțarea focalizării câmpurilor de parolă din Microsoft Excel și Outlook nu mai este un eșec. (#14839)
* NVDA nu va mai refuza să salveze configurația după o resetare. (#13187)
* Când rulează o versiune temporară din lansator, NVDA nu va induce în eroare utilizatorii să creadă că pot salva configurația. (#14914)
* Au fost îmbunătățite combinațiile de taste pentru raportarea obiectului. (#10807)
* La deplasarea rapidă printre celulele din Excel, este mai puțin probabil ca NVDA să raporteze greșit o celulă sau o selecție. (#14983, #12200, #12108)
* În general, NVDA răspunde mai repede la comenzi și la schimbările de focalizare. (#14928)

### Modificări pentru dezvoltatori

## 2021.2

Această versiune introduce suportul preliminar pentru Windows 11.
În timp ce lansarea oficială a Windows 11 încă se lasă așteptată, această versiune de NVDA a fost testată pe versiunile de previzualizare ale acestui sistem de operare.
Acest fapt include o reparare importantă a cortinei ecranului (vedeți secțiunea Note Importante).
Instrumentul de Remediere a Înregistrării COM poate rezolva mai multe probleme atunci când se execută NVDA.
De asemenea, există actualizări pentru sintetizatorul eSpeak și pentru traducătorul braille LibLouis.
Există și alte rezolvări de probleme și îmbunătățiri, în special pentru suportul braille și pentru terminalele Windows, precum și pentru calculator, panoul de emoji și pentru istoricul planșetei.

### Note importante

Din cauza unei modificări în API-ul Magnification al Windows, Cortina de Ecran a fost actualizată cele mai noi versiuni de Windows.
Utilizați NVDA 2021.2 pentru a activa Cortina de Ecran cu Windows 10 21H2 (10.0.19044) sau mai nou.
Aceasta include Windows 10 Insiders și Windows 11.
Dacă folosiți o nouă versiune de Windows, pentru a fi sigur că funcționalitatea Cortină Ecran face ecranul complet negru, întrebați pe cineva care vede.

### Noi Funcționalități

* Suport experimental pentru adnotările ARIA:
  * adaugă o comandă pentru citirea unor informații pe scurt despre un obiect cu aria-details. (#12364)
  * adaugă o opțiune în panoul setărilor avansate care să raporteze atunci când un obiect are detalii în modul de navigare. (#12439)
* În versiunea 1909 a Windows 10, precum și în cele mai noi decât aceasta (chiar și în Windows 11), NVDA va anunța numărul de sugestii la efectuarea căutărilor în File Explorer. (#10341, #12628)
* În Microsoft Word, NVDA anunță rezultatul scurtăturilor cu liniuțe și cu linii suspendate atunci când este executat. (#6269)

### Modificări

* S-a actualizat Espeak-ng la 1.51-dev commit `ab11439b18238b7a08b965d1d5a6ef31cbb05cbb`. (#12449, #12202, #12280, #12568)
* Dacă articolul este activat din preferințele utilizatorului pentru formatarea documentului, NVDA va spune „articol” după conținut. (#11103)
* S-a actualizat traducătorul braille liblouis la [3.18.0](https://github.com/liblouis/liblouis/releases/tag/v3.18.0). (#12526)
  * Tabele braille noi: bulgară grad 1, birmană grad 1, birmană grad 2, kazahă grad 1, khmeră grad 1, curdă de nord grad 0, sepedi grad 1, sepedi grad 2, sesotho grad 1, sesotho grad 2, setswana grad 1, setswana grad 2, tătară grad 1, vietnameză grad 0, vietnameză grad 2, vietnameză de sud grad 1, xhosa grad 1, xhosa grad 2, iakută grad 1, zulu grad 1, zulu grad 2
* A fost redenumit Windows 10 OCR în Windows OCR. (#12690)

### Defecte Rezolvate

* În aplicația Calculator din Windows 10, NVDA va anunța expresiile de calcul pe un afișaj braille. (#12268)
* În programele terminale din versiunea 1607 a Windows 10, precum și în cele mai noi decât aceasta, nu mai sunt citite caracterele din dreapta cursorului de scriere în cazul inserării sau al eliminării  caracterelor din mijlocul unui rând. (#3200)
  * Diff Match Patch este activ în mod implicit. (#12485)
* Intrarea braille funcționează corespunzător cu următoarele tabele abreviate: arabă grad 2, spaniolă grad 2, urdu grad 2, chineză (China, mandarină) grad 2. (#12541)
* Instrumentul de Remediere a Înregistrării COM rezolvă mai multe probleme, în special în versiunile de Windows bazate pe 64 de biți. (#12560)
* Îmbunătățiri la butonul de control pentru dispozitivul braille Seika Notetaker de la Nippon Telesoft. (#12598)
* Îmbunătățiri la anunțarea panoului de emoji al Windows și a istoricului planșetei. (#11485)
* Au fost actualizate descrierile de caractere ale alfabetului bengalez. (#12502)
* NVDA se închide în siguranță atunci când este inițiat un nou proces. (#12605)
* Reselectarea driver-ului pentru afișajul braille Handy Tech din dialogul selectării afișajelor braille nu mai cauzează erori. (#12618)
* Versiunea 10.0.22000 a Windows este recunoscută ca Windows 11. Se aplică și pentru versiunile mai noi decât aceasta. (#12626)
* A fost reparat și testat suportul cortinei ecranului pe versiunile de Windows până la 10.0.22000. (#12684)
* Dacă nu sunt afișate rezultate la filtrarea gesturilor de intrare, dialogul acestora de configurare continuă să funcționeze așa cum era de așteptat. (#12673)
* A fost reparată o eroare care făcea ca primul element de meniu dintr-un submeniu nu era anunțat în niște contexte. (#12624)

### Modificări pentru Dezvoltatori (în engleză)

* `characterProcessing.SYMLVL_*` constants should be replaced using their equivalent `SymbolLevel.*` before 2022.1. (#11856, #12636)
* `controlTypes` has been split up into various submodules, symbols marked for deprecation must be replaced before 2022.1. (#12510)
  * `ROLE_*` and `STATE_*` constants should be replaced to their equivalent `Role.*` and `State.*`.
  * `roleLabels`, `stateLabels` and `negativeStateLabels` have been deprecated, usages such as `roleLabels[ROLE_*]` should be replaced to their equivalent `Role.*.displayString` or `State.*.negativeDisplayString`.
  * `processPositiveStates` and `processNegativeStates` have been deprecated for removal.
* On Windows 10 Version 1511 and later (including Insider Preview builds), the current Windows feature update release name is obtained from Windows Registry. (#12509)
* Deprecated: winVersion.WIN10_RELEASE_NAME_TO_BUILDS will be removed in 2022.1, there is no direct replacement. (#12544)

## 2021.1

Această versiune include suportul opțional și experimental pentru UIA-ul din Excel și din navigatoarele web bazate pe Chromium.
Există corecturi pentru câteva limbi și pentru accesarea link-urilor în Braille.
De asemenea, există actualizări făcute la Unicode CLDR și la simbolurile matematice, precum și la LibLouis.
Versiunea vine la pachet și cu rezolvarea multor erori precum cele din Office, Visual Studio și din interfețele câtorva limbi.

Notă:

 * Această versiune afectează compatibilitatea cu suplimentele existente.
 * Adobe Flash nu va mai avea suport începând cu această versiune de NVDA.

### Noi Funcționalități

* Suport prematur pentru UIA cu navigatoarele web bazate pe Chromium precum Edge. (#12025)
* Suport experimental și opțional pentru Microsoft Excel prin UI Automation. Se recomandă numai pentru compilarea 16.0.13522.10000 sau pentru cele mai noi decât aceasta. (#12210)
* Navigare mai facilă a ieșirii din Consola NVDA Python. (#9784)
  * cu alt+săgețile sus/jos se sare la rezultatul următor/precedent al ieșirii (se adaugă shift pentru selectare).
  * control+l curăță panoul de ieșire.
* NVDA raportează categoriile atribuite unei întâlniri din Microsoft Outlook dacă aceasta există. (#11598)
* Suport pentru afișajul braille Seika Notetaker de la Nippon Telesoft. (#11514)

### Modificări

* În modul de navigare, controalele pot fi activate cu deplasarea cursorului braille pe descriptoarele lor (e.x. „lnk” pentru un link). Acest lucru este util în special în cazul activării casetelor de bifat care nu au etichete. (#7447)
* NVDA îl împiedică pe utilizator să folosească funcționalitatea Windows 10 OCR dacă este activă cortina ecranului. (#11911)
* S-a actualizat Depozitul de Date Locale Comune Unicode (CLDR) la 38.1. (#11943)
* Au fost adăugate mai multe simboluri matematice în dicționarul de simboluri. (#11467)
* Manualul de utilizare, jurnalul de modificări și lista de comenzi au un aspect reîmprospătat. (#12027)
* NVDA pronunță cuvântul „nesuportat” atunci când se încearcă activarea aspectului ecranului în aplicații pentru care această funcționalitate nu este compatibilă, Microsoft Word fiind un bun exemplu. (#7297)
* Opțiunea „Încearcă să anulezi vorbirea pentru evenimentele expirate ale focalizării” din panoul de setări avansate este activă în mod implicit. (#10885)
  * Acest comportament poate fi dezactivat setând opțiunea la valoarea „Nu”.
  * Aplicațiile web precum Gmail nu mai furnizează informații învechite la deplasarea focalizării într-un mod rapid.
* S-a actualizat traducătorul braille liblouis la [3.17.0](https://github.com/liblouis/liblouis/releases/tag/v3.17.0). (#12137)
  * Noi tabele braille: braille literar bielorus, braille bielorus pentru calculator, urdu grad 1, urdu grad 2.
* A fost eliminat din NVDA suportul pentru conținutul Adobe Flash, fiindcă utilizarea acestui program este activ descurajată de către cei care l-au dezvoltat. (#11131)
* NVDA se va opri chiar și cu ferestrele deschise, procesul de dezactivare va închide toate ferestrele și casetele de dialog ale acestui cititor de ecran. (#1740)
* Monitorul de vorbire poate fi închis cu `alt+F4` și are un buton standard de închidere pentru o interacțiune mai ușoară cu utilizatorii care dețin dispozitive de indicare. (#12330)
* Monitorul Braille are un buton standard de închidere pentru o interacțiune mai ușoară cu utilizatorii care dețin dispozitive de indicare. (#12328)
* În dialogul listei de elemente, tasta acceleratoare pentru butonul „Activare” a fost eliminată din niște traduceri pentru a se evita coliziunea cu o etichetă a unui buton rotativ de tip element. Atunci când se poate, butonul încă este implicit al dialogului și, ca atare, poate fi activat prin simpla apăsare a tastei enter din lista de elemente. (#6167)

### Defecte Rezolvate

* Lista de mesaje din Outlook 2010 poate fi citită din nou. (#12241)
* În programele terminale din versiunea 1607 a Windows 10 și din cele mai noi decât aceasta, nu mai sunt citite caracterele din dreapta cursorului de scriere atunci când sunt inserate caractere în mijlocul unui rând sau sunt șterse. (#3200)
  * Această soluție experimentală trebuie să fie activată manual din panoul setărilor avansate NVDA prin modificarea algoritmului diff la Diff Match Patch.
* Nu ar trebui să mai apară în Microsoft Outlook distanța inadecvată care este raportată la apăsarea combinației Shift+Tab pentru deplasarea de la corpul mesajului la câmpul „Subiect”. (#10254)
* Inserarea caracterului tab pentru indentare la începutul unei linii de intrare care nu este goală, precum și efectuarea completării tab-ului în mijlocul unei linii de intrare, sunt suportate. (#11532)
* Informațiile de formatare și celelalte mesaje navigabile nu mai prezintă rânduri goale neașteptate atunci când aspectul ecranului este dezactivat. (#12004)
* Acum se pot citi comentariile din Microsoft Word cu UIA-ul activat. (#9285)
* A fost îmbunătățită performanța la interacțiunea cu Visual Studio. (#12171)
* Au fost reparate niște erori grafice precum lipsa elementelor la utilizarea NVDA cu un aspect de la stânga la dreapta. (#8859)
* Se respectă direcția aspectului GUI bazată pe limba NVDA, nu pe cea a sistemului de operare Windows. (#638)
  * problemă cunoscută pentru limbile care se citesc de la dreapta la stânga: marginea din dreapta a clipurilor grupate pe etichete/controale. (#12181)
* Locația Python este setată să corespundă în mod consecvent limbii selectate în preferințe și va apărea la utilizarea limbii implicite. (#12214)
* TextInfo.getTextInChunks nu se mai blochează atunci când este apelat în controalele Rich Edit precum vizualizatorul jurnalului NVDA. (#11613)
* În versiunile 1803 și 1809 ale Windows 10 se poate din nou folosi NVDA în limbile care au semnul Underscore (_) în cadrul numelui acestora. Una dintre aceste limbi este germana elvețiană, al cărei nume în sistemul NVDA de traduceri este de_CH. (#12250)
* Sunt raportate formatările strikethrough, superscript și subscript pentru celulele de Excel întregi dacă opțiunea corespunzătoare este activată. (#12264)
* A fost rezolvată problema cu privire la copierea configurației care se realiza în timpul instalării și care provenea de la o copie portabilă. Această eroare apărea în cazul în care dosarul implicit de configurare era gol. (#12071, #12205)
* NVDA nu pronunța corect niște diacritice sau litere cu accent, ca de exemplu À, Á, È, É, Ì, Í, Ò, Ó, Ù sau Ú, atunci când opțiunea „Spune "mare" după majuscule” era activă. Nu mai există această problemă în momentul de față. (#11948)
* A fost rezolvată problema cu privire la modificarea tonului în sintetizatorul SAPI4. (#12311)
* NVDA onorează parametrul liniei de comandă `--minimal` și nu redă sunetul de pornire, urmărind același comportament documentat, întocmai ca executabilul NVDA al unei copii portabile sau instalate. (#12289)
* În Microsoft Word sau Outlook, tasta de navigare rapidă prin tabel poate sări la tabelul de aspect dacă opțiunea „Include tabelele de aspect” este activată din setările modului de navigare. (#11899)
* NVDA nu va mai spune „↑↑↑” pentru emoji-uri în limbi particulare. (#11963)
* Espeak suportă din nou cantoneza și mandarina. (#10418)
* În noul browser Microsoft Edge bazat pe Chromium, câmpurile de text precum cel al barei de adrese sunt anunțate atunci când nu au niciun fel de conținut în ele. (#12474)
* A fost reparat driver-ul Seika Braille. (#10787)

### Modificări pentru Dezvoltatori (în engleză)

Începând cu această versiune de NVDA, modificările pentru dezvoltatori nu vor mai fi traduse în limba română, întrucât acestea nu prezintă interes pentru publicul larg din România și Republica Moldova. Pe site-ul comunității românești, [www.nvda.ro](http://www.nvda.ro), sunt numai trei suplimente NVDA realizate de doi programatori, iar în ceea ce privește contribuția la dezvoltarea NVDA din partea comunității noastre, un singur om se ocupă. Acest om este vorbitor fluent de engleză și germană.

În 2017, comunitatea internațională NVDA le-a recomandat traducătorilor să nu mai traducă modificările pentru dezvoltatori. Unii traducători și/sau echipe de traduceri nu au ținut cont de această recomandare, precum echipa noastră și echipa spaniolă, iar altele precum cea italiană au procedat întocmai. Începând cu versiunea 2017.2, aceste modificări nu mai sunt traduse în limba italiană, fiindcă nici acolo nu există un interes puternic pentru dezvoltarea de suplimente. Cele mai cunoscute suplimente la nivel internațional dezvoltate în cadrul comunității italiene sunt WeatherPlus și toolbarsExplorer, în timp ce LION (Live Inteligent OCR for NVDA) este mândria comunității noastre și singurul supliment cunoscut de utilizatorii străini.

Vom reveni cu traducerea acestor modificări atunci când va exista un interes real pentru acest lucru.

Acestea fiind spuse, vă mulțumim ppentru înțelegere!

### Lista de modificări

* Note: this is an Add-on API compatibility breaking release. Add-ons will need to be re-tested and have their manifest updated.
* NVDA's build system now fetches all Python dependencies with pip and stores them in a Python virtual environment. This is all done transparently.
  * To build NVDA, SCons should continue to be used in the usual way. E.g. executing scons.bat in the root of the repository. Running `py -m SCons` is no longer supported, and `scons.py` has also been removed.
  * To run NVDA from source, rather than executing `source/nvda.pyw` directly, the developer should now use `runnvda.bat` in the root of the repository. If you do try to execute `source/nvda.pyw`, a message box will alert you this is no longer supported.
  * To perform unit tests, execute `rununittests.bat [<extra unittest discover options>]`
  * To perform system tests: execute `runsystemtests.bat [<extra robot options>]`
  * To perform linting, execute `runlint.bat <base branch>`
  * Please refer to readme.md for more details.
* The following Python dependencies have also been upgraded:
  * comtypes updated to 1.1.8.
  * pySerial updated to 3.5.
  * wxPython updated to 4.1.1.
  * Py2exe updated to 0.10.1.0.
* `LiveText._getTextLines` has been removed. (#11639)
  * Instead, override `_getText` which returns a string of all text in the object.
* `LiveText` objects can now calculate diffs by character. (#11639)
  * To alter the diff behaviour for some object, override the `diffAlgo` property (see the docstring for details).
* When defining a script with the script decorator, the 'allowInSleepMode' boolean argument can be specified to control if a script is available in sleep mode or not. (#11979)
* The following functions are removed from the config module. (#11935)
  * canStartOnSecureScreens - use config.isInstalledCopy instead.
  * hasUiAccess and execElevated - use them from the systemUtils module.
  * getConfigDirs - use globalVars.appArgs.configPath instead.
* Module level REASON_* constants are removed from controlTypes - please use controlTypes.OutputReason instead. (#11969)
* REASON_QUICKNAV has been removed from browseMode - use controlTypes.OutputReason.QUICKNAV instead. (#11969)
* `NVDAObject` (and derivatives) property `isCurrent` now strictly returns Enum class `controlTypes.IsCurrent`. (#11782)
  * `isCurrent` is no longer Optional, and thus will not return None.
    * When an object is not current `controlTypes.IsCurrent.NO` is returned.
* The `controlTypes.isCurrentLabels` mapping has been removed. (#11782)
  * Instead use the `displayString` property on a `controlTypes.IsCurrent` enum value.
    * For example: `controlTypes.IsCurrent.YES.displayString`.
* `winKernel.GetTimeFormat` has been removed - use `winKernel.GetTimeFormatEx` instead. (#12139)
* `winKernel.GetDateFormat` has been removed - use `winKernel.GetDateFormatEx` instead. (#12139)
* `gui.DriverSettingsMixin` has been removed - use `gui.AutoSettingsMixin`. (#12144)
* `speech.getSpeechForSpelling` has been removed - use `speech.getSpellingSpeech`. (#12145)
* Commands cannot be directly imported from speech as `import speech; speech.ExampleCommand()` or `import speech.manager; speech.manager.ExampleCommand()` - use `from speech.commands import ExampleCommand` instead. (#12126)
* `speakTextInfo` will no longer send speech through `speakWithoutPauses` if reason is `SAYALL`, as `SayAllHandler` does this manually now. (#12150)
* The `synthDriverHandler` module is no longer star imported into `globalCommands` and `gui.settingsDialogs` - use `from synthDriverHandler import synthFunctionExample` instead. (#12172)
* `ROLE_EQUATION` has been removed from controlTypes - use `ROLE_MATH` instead. (#12164)
* `autoSettingsUtils.driverSetting` classes are removed from `driverHandler` - please use them from `autoSettingsUtils.driverSetting`. (#12168)
* `autoSettingsUtils.utils` classes are removed from `driverHandler` - please use them from `autoSettingsUtils.utils`. (#12168)
* Support of `TextInfo`s that do not inherit from `contentRecog.BaseContentRecogTextInfo` is removed. (#12157)
* `speech.speakWithoutPauses` has been removed - please use `speech.speechWithoutPauses.SpeechWithoutPauses(speakFunc=speech.speak).speakWithoutPauses` instead. (#12195, #12251)
* `speech.re_last_pause` has been removed - please use `speech.speechWithoutPauses.SpeechWithoutPauses.re_last_pause` instead. (#12195, #12251)
* `WelcomeDialog`, `LauncherDialog` and `AskAllowUsageStatsDialog` are moved to the `gui.startupDialogs`. (#12105)
* `getDocFilePath` has been moved from `gui` to the `documentationUtils` module. (#12105)
* The gui.accPropServer module as well as the AccPropertyOverride and ListCtrlAccPropServer classes from the gui.nvdaControls module have been removed in favor of WX native support for overriding accessibility properties. When enhancing accessibility of WX controls, implement wx.Accessible instead. (#12215)
* Files in `source/comInterfaces/` are now more easily consumable by developer tools such as IDEs. (#12201)
* Convenience methods and types have been added to the winVersion module for getting and comparing Windows versions. (#11909)
  * isWin10 function found in winVersion module has been removed.
  * class winVersion.WinVersion is a comparable and order-able type encapsulating Windows version information.
  * Function winVersion.getWinVer has been added to get a winVersion.WinVersion representing the currently running OS.
  * Convenience constants have been added for known Windows releases, see winVersion.WIN* constants.
* IAccessibleHandler no longer star imports everything from IAccessible and IA2 COM interfaces - please use them directly. (#12232)
* TextInfo objects now have start and end properties which can be compared mathematically with operators such as < <= == != >= >. (#11613)
  * E.g. ti1.start <= ti2.end
  * This usage is now prefered instead of ti1.compareEndPoints(ti2,"startToEnd") <= 0
* TextInfo start and end properties can also be set to each other. (#11613)
  * E.g. ti1.start = ti2.end
  * This usage is prefered instead of ti1.SetEndPoint(ti2,"startToEnd")
* `wx.CENTRE_ON_SCREEN` and `wx.CENTER_ON_SCREEN` are removed, use `self.CentreOnScreen()` instead. (#12309)
* `easeOfAccess.isSupported` has been removed, NVDA only supports versions of Windows where this evaluates to `True`. (#12222)
* `sayAllHandler` has been moved to `speech.sayAll`. (#12251)
  * `speech.sayAll.SayAllHandler` exposes the functions `stop`, `isRunning`, `readObjects`, `readText`, `lastSayAllMode`.
  * `SayAllHandler.stop` also resets the `SayAllHandler` `SpeechWithoutPauses` instance.
  * `CURSOR_REVIEW` and `CURSOR_CARET` has been replaced with `CURSOR.REVIEW` and `CURSOR.CARET`.
* `speech.SpeechWithoutPauses` has been moved to `speech.speechWithoutPauses.SpeechWithoutPauses`. (#12251)
* `speech.curWordChars` has been renamed `speech._curWordChars`. (#12395)
* the following have been removed from `speech` and can be accessed through `speech.getState()`. These are readonly values now. (#12395)
  * speechMode
  * speechMode_beeps_ms
  * beenCanceled
  * isPaused
* to update `speech.speechMode` use `speech.setSpeechMode`. (#12395)
* the following have been moved to `speech.SpeechMode`. (#12395)
  * `speech.speechMode_off` becomes `speech.SpeechMode.off`
  * `speech.speechMode_beeps` becomes `speech.SpeechMode.beeps`
  * `speech.speechMode_talk` becomes `speech.SpeechMode.talk`
* `IAccessibleHandler.IAccessibleObjectIdentifierType` is now `IAccessibleHandler.types.IAccessibleObjectIdentifierType`. (#12367)
* The following in `NVDAObjects.UIA.WinConsoleUIA` have been changed (#12094)
  * `NVDAObjects.UIA.winConsoleUIA.is21H1Plus` renamed `NVDAObjects.UIA.winConsoleUIA.isImprovedTextRangeAvailable`.
  * `NVDAObjects.UIA.winConsoleUIA.consoleUIATextInfo` renamed to start class name with upper case.
  * `NVDAObjects.UIA.winConsoleUIA.consoleUIATextInfoPre21H1` renamed `NVDAObjects.UIA.winConsoleUIA.ConsoleUIATextInfoWorkaroundEndInclusive`
    * The implementation works around both end points being inclusive (in text ranges) before [microsoft/terminal PR 4018](https://github.com/microsoft/terminal/pull/4018)
    * Workarounds for `expand`, `collapse`, `compareEndPoints`, `setEndPoint`, etc

## 2020.4

Această versiune include noi metode de intrare chinezești, o actualizare la Liblouis și la lista de elemente (NVDA+f7) funcționează acum în modul de focalizare.
Este disponibil ajutorul sensibil contextual la apăsarea F1 în ferestrele de dialog ale NVDA.
S-au făcut îmbunătățiri la regulile de pronunțare a simbolurilor, la dicționarul de vorbire, la mesajele Braille și la lectura rapidă.
Reparări de bug-uri și îmbunătățiri la Mail, Outlook, Teams, Visual Studio, Azure Data Studio și Foobar2000.
Pe web sunt îmbunătățiri la Google Docs și un suport mai consistent pentru ARIA.
Plus multe alte erori importante rezolvate și îmbunătățiri la fel de importante, pe care le veți afla dacă veți citi în continuare acest jurnal.

### Noi Funcționalități

* La apăsarea tastei F1 în cadrul ferestrelor de dialog ale NVDA se va deschide manualul de utilizare al acestui cititor de ecran, la secțiunea cea mai relevantă. (#7757)
* Suport pentru sugestiile de autocompletare (IntelliSense) în Microsoft SQL Server Management Studio plus Visual Studio 2017 și mai nou. (#7504)
* Pronunțarea simbolurilor: posibilitatea de a defini grupurile de simboluri complexe, împreună cu  suportul pentru referințele de grup într-un câmp de înlocuire, făcându-le mai simple și mai puternice. (#11107)
* Utilizatorii sunt notificați atunci când încearcă să creeze intrări în Dicționarul de Vorbire cu  înlocuiri invalide ale expresiilor regulate. (#11407)
 * Mai exact, sunt detectate erorile de grup.
* S-a adăugat suportul pentru noile metode de intrare ale chinezei tradiționale Quick și Pinyin din Windows 10. (#11562)
* Anteturile filelor sunt considerate câmpuri formular la apăsarea tastei F pentru navigarea rapidă. (#10432)
* S-a adăugat o comandă pentru activarea/dezactivarea raportării textului marcat (evidențiat), neexistând un gest asociat cu aceasta în mod implicit. (#11807)
* S-a adăugat parametrul liniei de comandă --copy-portable-config, care vă permite să copiați automat configurația furnizată în contul de utilizator atunci când instalați NVDA în mod silențios. (#9676)
* Este suportată operațiunea de deplasare a cursorului în Monitorul Braille, făcând trecerea mausului deasupra celulelor. (#11804)
* NVDA va detecta automat dispozitivele Humanware Brailliant BI 40X și 20X atât prin USB, cât și prin Bluetooth. (#11819)

### Modificări

* S-a actualizat traducătorul braille liblouis la versiunea 3.16.1:
 * Adresează crash-uri multiple
 * Adaugă tabelul braille grad 1 pentru limba bașchiră
 * Adaugă tabelul braille copt în 8 punte pentru calculator
 * Adaugă tabelele braille rusești literare (standard și detaliat)
 * Adaugă tabelul braille grad 2 pentru limba afrikaans
 * Șterge tabelul braille grad 1 pentru limba rusă
* La citirea cu modul de rostire completă în modul de navigare, comenzile „caută următor” și „caută precedent” nu se opres din citit dacă este activată opțiunea ”Permite lectura rapidă în modul de rostire completă”; acest mod continuă de la fraza de după termenul următor sau precedent găsit. (#11563)
* Pentru afișajele HIMS braille, tasta F3 a fost  înlocuită cu Spațiu + punctele 148. (#11710)
* Îmbunătățiri pentru UX-urile opțiunilor „timpul de expirare a mesajului braille” și „Arată mesajele pe termen nelimitat”. (#11602)
* În navigatoarele web și în alte aplicații care suportă modul de navigare, dialogul listei de elemente (NVDA+F7) poate fi afișat în modul de focalizare. (#10453)
* Actualizările la regiunile live ARIA sunt suprimate atunci când este inactivă raportarea schimbărilor dinamice de conținut. (#9077)
* NVDA va spune „Copiat pe planșetă” înainte de a începe să redea textul care tocmai a fost copiat. (#6757)
* A fost îmbunătățită prezentarea tabelului grafic de vizualizare din secțiunea „Administrare disc”. (#10048)
* Sunt dezactivate etichetele pentru controale (în gri) atunci când un control este inactiv. (#11809)
* A fost actualizată adnotarea emoji CLDR la versiunea 38. (#11817)
* Caracteristica „Evidențiere Focalizare” a fost redenumită. Acum poartă numele de „Evidențiere Vedere”. (#11700)

### Defecte Rezolvate

* NVDA funcționează din nou cu câmpurile de editare la utilizarea aplicației Fast Log Entry. (#8996)
* Se raportează timpul rămas în Foobar2000 dacă timpul total nu este disponibil (e.x. la redarea unui stream în direct). (#11337)
* NVDA detectează atributul aria-roledescription în elementele conținutului editabil din paginile web. (#11607)
* NVDA nu mai spune „listă” la fiecare rând al unei liste din Google Docs sau din orice alt conținut editabil din Google Chrome. (#7562)
* La navigarea cu tastele săgeată de la un caracter sau de la un cuvânt dintr-un element de listă la alt caracter sau cuvânt dintr-un conținut editabil de pe web, introducerea noului element de listă este anunțată. (#11569)
* NVDA citește rândul care trebuie atunci când cursorul de scriere al sistemului se află la sfârșitul unui link aflat la sfârșitul unui element de listă din Google Docs sau din orice alt conținut editabil de pe web. (#11606)
* În Windows 7, deschiderea și închiderea din desktop a meniului start setează cum trebuie focalizarea. (#10567)
* Când este activă opțiunea „încearcă să anulezi evenimentele expirate ale focalizării”, titlul filei este din nou anunțat atunci când se trece de la o filă la alta în Firefox. (#11397)
* NVDA nu mai eșuează  la anunțarea unui element de listă după tastarea unui caracter dintr-o listă în contextul folosirii vocilor de pentru SAPI5 de la Ivona. (#11651)
* Se poate din nou folosi modul de navigare la citirea e-mail-urilor din Windows 10 Mail 16005.13110 și mai nou. (#11439)
* La utilizarea vocilor pentru SAPI5 de la Ivona dezvoltate de harposoftware.com, NVDA poate să salveze configurația, să permită trecerea de la un sintetizator la altul și nu mai rămâne pe modul silențios după repornire. (#11650)
* Puteți insera numărul 6 în braille-ul pentru calculator utilizând o tastatură braille împreună cu afișajele de la HIMS. (#11710)
* Îmbunătățiri semnificative de performanță în ceea ce privește Azure Data Studio. (#11533, #11715)
* Cu opțiunea „încearcă să anulezi vorbirea pentru evenimentele expirate ale focalizării” activă, titlul ferestrei de dialog NVDA Find este din nou anunțat. (#11632)
* NVDA nu ar mai trebui să se blocheze când calculatorul este scos din modul de repaus și când focalizarea ajunge într-un document Microsoft Edge. (#11576)
* Nu mai este nevoie să apăsați tasta tab sau să mutați focalizarea după închiderea unui meniu contextual din Microsoft Edge pentru ca modul de navigare să fie din nou funcțional. (#11202)
* NVDA nu mai eșuează la citirea elementelor din listele de vizualizare dintr-o aplicație pe 64 de biți precum Tortoise SVN. (#8175)
* Treegrid-urile ARIA sunt afișate ca niște tabele obișnuite atât în modul de navigare din Firefox, cât și în cel din Chrome. (#9715)
* Poate fi inițiată o căutare inversă cu „find previews” prin NVDA+shift+F3 (#11770)
* Nu mai este tratat un script NVDA ca fiind repetat dacă se întâmplă o apăsare ilogică de taste între două executări ale scriptului. (#11388)
* Se poate dezactiva raportarea etichetelor puternice și accentuate din Internet Explorer prin dezactivarea raportării accentelor din setările NVDA de formatare a documentului. (#11808)
* Un număr mic de utilizatori au experimentat un bug care făcea ca NVDA să se blocheze timp de câteva secunde la navigarea printre celulele din Excel. Această problemă n-ar mai trebui să apară. (#11818)
* În compilările Microsoft Teams cu numere de versiuni precum 1.3.00.28xxx, NVDA nu mai dă rateuri la citirea mesajelor din conversații sau din canalele echipelor din cauza unui meniu focalizat incorect. (#11821)
* Textul din Google Chrome care este marcat ca fiind în același timp greșeală de gramatică și de ortografie va fi citit ca atare de NVDA. (#11787)
* La utilizarea Outlook (traducerea în limba franceză), scurtătura pentru „răspunsul către toți” (control+shift+R) funcționează din nou. (#11196)
* În Visual Studio, indiciile IntelliSense care oferă informații suplimentare cu privire la elementul IntelliSense selectat în acel moment sunt raportate o singură dată. (#11611)
* În Windows 10 Calculator, NVDA nu va anunța progresul calculelor dacă pronunțarea caracterelor tastate va fi inactivă. (#9428)
* NVDA nu mai dă crash-uri când se utilizează engleza americană grad 2, se extinde la braille-ul pentru calculator și când cursorul este activ, ori când se afișează un conținut în braille, ca de exemplu un URL. (#11754)
* Se pot raporta din nou informații de formatare pentru celula de Excel focalizată utilizându-se NVDA+F. (#11914)
* Intrarea QWERTY de pe afișajele braille de la Papenmeier care o suportă funcționează din nou și nu mai face ca NVDA să se blocheze aiurea. (#11944)

### Modificări pentru Dezvoltatori

* Testele de sistem pot trimite taste folosind spy.emulateKeyPress, care ia un identificator de tastă care este în concordanță cu numele proprii de taste ale NVDA, iar în mod implicit se blochează până când acțiunea este executată. (#11581)
* NVDA nu mai are nevoie ca dosarul actual să fie folder-ul de aplicație ca să funcționeze. (#6491)
* Setarea aria live politeness pentru regiunile live poate fi găsită în obiectele NVDA folosindu-se proprietatea liveRegionPoliteness. (#11596)
* Este posibilă definirea gesturilor separate pentru documentul Word și pentru Outlook. (#11196)

## 2020.3

Această versiune include câteva îmbunătățiri substanțiale la stabilitate și performanță, punându-se accent pe aplicațiile Microsoft Office. Există noi setări pentru activarea sau dezactivarea suportului pentru ecranele tactile și pentru activarea sau dezactivarea raportării graficelor.
Existența conținutului marcat (evidențiat) poate fi raportată în navigatoarele web. De asemenea, sunt disponibile noi tabele braille germane.

### Noi Funcționalități

* Acum, puteți activa sau dezactiva raportarea graficelor din setările NVDA de formatare a documentului. De reținut faptul că dezactivarea acestei opțiuni nu va exclude citirea textelor alternative din grafice. (#4837)
* Acum, puteți activa sau dezactiva suportul NVDA pentru ecranele tactile. A fost adăugată o opțiune în panoul Interacțiune Tactilă al setărilor NVDA. Gestul implicit este NVDA+control+alt+t. (#9682)
* S-au adăugat noi tabele braille nemțești. (#11268)
* Acum, NVDA detectează controale UIA de text read-only (#10494)
* Existența conținutului marcat (evidențiat) este raportat atât vocal cât și în braille în toate navigatoarele web. (#11436)
 * Aceasta poate fi activată sau dezactivată grație unei noi opțiuni de evidențiere care a fost adăugată în categoria de setări a Formatării Documentelor. 
* Pot fi adăugate noi taste simulatoare de sistem din dialogul Gesturilor de Intrare al NVDA. (#6060)
 * Pentru a face asta, apăsați butonul „Adaugă” după ce ați selectat categoria tastelor simulate ale tastaturii de sistem.
* Acum, este suportat Handy Tech Active Braille cu joystick. (#11655)
* Acum, setarea „Mod focalizare automată pentru mișcarea cursorului de scriere” este compatibilă cu „setează automat focalizarea la elementele focalizabile”. (#11663)

### Modificări

* A fost modificat scriptul pentru raportarea formatării (NVDA+f) astfel încât să raporteze formatarea de la cursorul de scriere al sistemului, nu de la cursorul de examinare, așa cum o făcea înainte. Pentru a vi se raporta formatarea de la poziția cursorului de examinare, apăsați NVDA+shift+f. (#9505)
* NVDA nu mai setează focalizarea sistemului la elementele focalizabile în mod implicit în modul de navigare, îmbunătățind astfel performanța și stabilitatea. (#11190)
* S-a actualizat CLDR de la versiunea 36.1 la versiunea 37. (#11303)
* S-a actualizat eSpeak-NG la versiunea 1.51-dev, commit 1fb68ffffea4
* Puteți utiliza navigarea prin tabel în casetele de listă care au elemente ce pot fi bifate atunci când lista particulară are coloane multiple. (#8857)
* În administratorul de suplimente, atunci când trebuie să confirmați eliminarea unui supliment, butonul „Nu” este implicit. (#10015)
* În Microsoft Excel, fereastra de dialog a listei de elemente prezintă formulele în forma lor localizată. (#9144)
* NVDA raportează terminologia corectă pentru notele din MS Excel. (#11311)
* La folosirea comenzii „mută cursorul de examinare la focalizare” în modul de navigare, cursorul de examinare este setat la poziția cursorului virtual de scriere. (#9622)
* Informațiile raportată în modul de navigare, cum ar fi cele de formatare cu NVDA+F, sunt afișate într-o fereastră puțin mai mare aflată în centrul ecranului. (#9910)

### Defecte Rezolvate

* NVDA va vorbi de fiecare dată când veți naviga cuvânt cu cuvânt și vă veți focaliza pe oricare simbol singular urmat de un spațiu alb, indiferent de setările verbozității. (#5133)
* Sunt din nou raportate descrierile obiectelor la utilizarea în aplicații a QT (versiunea 5.11 sau o versiune mai nouă). (#8604)
* NVDA nu mai rămâne silențios la ștergerea unui cuvând folosind combinația control+delete. (#3298, #11029)
  * Este anunțat cuvântul aflat în dreapta cuvântului șters.
* Lista de limbi este sortată corect în panoul setărilor generale. (#10348)
* În fereastra de dialog a gesturilor de intrare, s-a îmbunătățit în mod semnificativ performanța în timpul filtrării. (#10307)(
* Puteți trimite, de la un afișaj braille, caractere Unicode dincolo de U+FFFF. (#10796)
* NVDA va anunța conținutul ferestrei de dialog „Deschidere Cu” în actualizarea Windows 10 din mai 2020. (#11335)
* O nouă opțiune experimentală în panoul setărilor avansate (Activează înregistrarea selectivă pentru evenimentele UI Automation și pentru schimbările de proprietate) poate oferi îmbunătățiri substanțiale de performanță în Microsoft Visual Studio și în alte aplicații bazate pe UI Automation dacă este activată. (#11077, #11209)
* Pentru elementele de listă ce pot fi bifate, starea selectată nu mai este anunțată inutil, iar dacă se poate, este anunțată în schimb starea neselectată. (#8554)
* În actualizarea Windows 10 din mai 2020, NVDA afișează Cartograful de Sunete Microsoft la vizualizarea dispozitivelor de ieșire din fereastra de dialog a sintetizatorului. (#11349)
* În Internet Explorer, nummerele sunt anunțate corect pentru listele ordonate dacă lista nu începe cu 1. (#8438)
* În Google Chrome, NVDA va raporta ca nebifate toate controalele ce pot fi bifate (nu doar casetele de bifat) care sunt nebifate în acel moment. (#11377)
* Este din nou posibilă navigarea prin diverse controale atunci când limba interfeței NVDA este setată în aragoneză. (#11384)
* Nu ar trebui ca NVDA, fie și din când în când, să se mai blocheze în Microsoft Word la o apăsare rapidă a săgeților sus și jos sau la tastarea de caractere cu braille-ul activat. (#11431, #11425, #11414)
* NVDA nu mai adaugă un spațiu de urmărire inexistent la copierea obiectului navigator curent pe planșetă. (#11438)
* NVDA nu mai activează profilul Spune Tot dacă nu este nimic de citit. (#10899, #9947)
* NVDA poate să citească lista de caracteristici din administratorul Internet Information Services (IIS). (#11468)
* NVDA ține dispozitivul audio deschis, îmbunătățind astfel performanța pentru niște plăci de sunet. (#5172, #10721)
* NVDA nu se va mai bloca sau închide atunci când țineți apăsate în același timp tastele control+shift+săgeată jos în Microsoft Word. (#9463)
* Starea de extins/redus a folderelor din treeview-ul de navigare pe drive.google.com este mereu raportată de NVDA. (#11520)
* NVDA va autodetecta afișajul braille NLS eReader de la Humanware prin Bluetooth, întrucât numele său de Bluetooth este „NLS eReader Humanware”. (#11561)
* Îmbunătățiri semnificative de performanță în codul Visual Studio. (#11533)

### Modificări pentru Dezvoltatori

* BoxSizerHelper.addDialogDismissButtons al GUI Helper-ului suportă un nou argument cuvânt cheie „separat” pentru adăugarea unui separator orizontal standard la dialoguri (altele decât mesajele și dialogurile singure de intrare). (#6468)
* S-au adăugat proprietăți suplimentare la App module-uri, incluzând calea pentru executabil (appPath), este o aplicație din Windows Store (isWindowsStoreApp), și arhitectura computerului pentru aplicație (appArchitecture). (#7894)
* Este posibilă crearea de app module-uri pentru aplicații găzduite în cadrul wwahost.exe pe Windows 8 și mai nou. (#4569)
* Poate fi delimitat un fragment din jurnal și copiat pe planșetă folosindu-se NVDA+control+shift+F1. (#9280)
* Obiectele specifice NVDA care sunt găsite de colectorul de gunoi ciclic al Python sunt acum înregistrate atunci când sunt șterse de colector pentru a ajuta la eliminarea ciclurilor de referință din NVDA. (#11499)
 * Majoritatea claselor NVDA sunt urmărite, incluzând NVDAObjects, appModule-uri, GlobalPlugin-uri, SynthDrivere și TreeInterceptoare.
 * O clasă care trebuie să fie urmărită ar trebui să moștenească de la garbageHandler.TrackedObject.
* Diagnosticarea semnificativă pentru evenimentele MSAA poate fi activată din panoul setărilor avansate NVDA. (#11521)
* WinEvent-urile MSAA pentru obiectul navigator curent nu mai sunt filtrate împreună cu alte evenimente dacă numărătoarea de evenimente pentru un anumit thread este depășită. (#11520)

## 2020.2

Caracteristicile principale ale acestei versiuni includ suportul pentru un afișaj braille nou de la Nattiq, suportul îmbunătățit pentru interfața grafică a antivirusului ESET, dar și pentru Windows Terminal, și îmbunătățiri de performanță în ceea ce privește 1Password și sintetizatorul Windows OneCore. În plus, multe erori importante au fost remediate și multe alte îmbunătățiri au fost făcute.

### Noi Funcționalități

* Suport pentru noi afișaje braille:
 * Nattiq nBraille (#10778)
* S-a adăugat un script pentru deschiderea dosarului configurărilor NVDA (niciun gest implicit). (#2214)
* Suport îmbunătățit pentru interfața grafică a antivirusului ESET. (#10894)
* S-a adăugat suportul pentru Windows Terminal. (#10305)
* S-a adăugat o comandă pentru raportarea profilului activ de configurare (niciun gest implicit). (#9325)
* S-a adăugat o comandă pentru activarea sau dezactivarea raportării subscripturilor și a superscripturilor (niciun gest implicit). (#10985)
* Aplicațiile web precum Gmail nu mai raportează informații învechite atunci când focalizarea se deplasează rapid. (#10885)
 * Această remediere experimentală trebuie să fie activată manual prin opțiunea „Încearcă să anulezi vorbirea pentru evenimentele expirate ale focalizării”, care se află în panoul setărilor avansate.
* Au fost adăugate multe alte simboluri în dicționarul implicit al acestora. (#11105)

### Modificări

* S-a actualizat traducătorul braille liblouis de la versiunea 3.12 la versiunea [3.14.0](https://github.com/liblouis/liblouis/releases/tag/v3.14.0). (#10832, #11221)
* Acum, raportarea superscripturilor și a subscripturilor este controlată separat de raportarea atributelor fontului. (#10919)
* Datorită schimbărilor făcute în VS Code, NVDA nu mai dezactivează modul de navigare din Code în mod implicit. (#10888)
* S-au șters mesajele „sus” și „jos” la deplasarea cursorului de examinare la primul sau ultimul rând al obiectului navigator curent. (#9551)
* S-au șters mesajele „stânga” și „dreapta” la deplasarea cursorului de examinare la primul sau ultimul caracter al rândului obiectului navigator curent. (#9551)

### Defecte Rezolvate

* Acum, NVDA pornește cum trebuie atunci când nu poate crea fișierul de jurnal. (#6330)
* În versiunile recente ale Microsoft Word 365, NVDA nu va mai anunța „delete back word” dacă este apăsată combinația de taste Control+Backspace în timpul editării unui document. (#10851)
* În Winamp, NVDA va anunța din nou o singură dată activarea sau dezactivarea stărilor „aleator” și „repetare”. (#10945)
* NVDA nu mai este extrem de lent la deplasarea prin lista de elemente în 1Password. (#10508)
* Sintetizatorul Windows OneCore nu mai rămâne între pronunții. (#10721)
* NVDA nu se mai blochează atunci când deschideți meniul contextual pentru 1Password din zona notificărilor de sistem (System Tray). (#11017)
* În Office 2013 și mai vechi:
 * Sunt anunțate pamblicile atunci când focalizarea se deplasează pentru prima dată la ele. (#4207)
 * Elementele din meniul contextual sunt din nou raportate așa cum trebuie. (#9252)
 * Secțiunile de pamblici sunt anunțate consistent la navigarea cu Control+săgeți. (#7067)
* În modul de navigare din Mozilla Firefox și Google Chrome, textul nu mai apare incorect pe un rând separat atunci când conținutul web utilizează afișarea CSS: inline-flex. (#11075)
* În modul de navigare cu setarea automată a sistemului la elementele focalizabile dezactivată, nu mai puteți activa elemente care nu sunt focalizabile.
* În modul de navigare cu setarea automată a sistemului la elementele focalizabile dezactivată, nu mai puteți activa elemente la care se ajunge prin apăsarea tastei tab. (#8528)
* În modul de navigare cu setarea automată a sistemului la elementele focalizabile dezactivată, activarea anumitor elemente nu mai duce la o locație incorectă. (#9886)
* Nu se vor mai auzi sunetele de eroare ale NVDA la accesarea controalelor de text DevExpress. (#10918)
* Indiciile iconițelor din zona notificărilor de sistem nu mai sunt raportate la navigarea cu tastatura dacă textul lor și numele lor sunt identice, pentru a se evita anunțarea de două ori. (#6656)
* În modul de navigare cu setarea automată a sistemului la elementele focalizabile dezactivată, comutarea la modul de focalizare cu NVDA+Spațiu focalizează elementul de sub cursorul de scriere al sistemului. (#11206)
* Puteți din nou să căutați actualizări pentru NVDA pe anumite sisteme; e.x. curățări ale instalărilor de Windows. (#11253)
* Nu mai este deplasată focalizarea în aplicațiile Java atunci când selecția este schimbată într-o vedere de listă extinsă nefocalizată, tabel sau listă. (#5989)

### Modificări pentru Dezvoltatori

* execElevated și hasUiAccess s-au mutat de la modulul config la modulul systemUtils. Utilizarea prin modulul config nu mai este de actualitate. (#10493)
* S-a actualizat configobj la 5.1.0dev commit f9a265c4. (#10939)
* Este posibilă testarea automată a NVDA cu Chrome și cu un sample HTML. (#10553)
* IAccessibleHandler a fost transformat într-un pachet, OrderedWinEventLimiter a fost extras la un modul și s-au adăugat texte de unități. (#10934)
* S-a actualizat BrlApi la versiunea 0.8 (BRLTTY 6.1). (#11065)
* Recuperarea barei de stare poate să nu fie personalizată de un AppModule. (#2125, #4640)
* NVDA nu mai ascultă IAccessible EVENT_OBJECT_REORDER. (#11076)
* Un ScriptableObject defect (cum ar fi un GlobalPlugin căruia îi lipsește un apel către metoda init a clasei sale de bază) nu mai afectează manipularea scripturilor NVDA. (#5446)

## 2020.1

Caracteristicile principale ale acestei versiuni includ suportul pentru câteva noi afișaje braille de la HumanWare și APH, precum și reparări ale unor erori importante precum cea a citirii conținutului matematic în Microsoft Word utilizându-se MathPlayer / MathType.

### Noi Funcționalități

* Elementul curent selectat din casetele de liste este prezentat din nou în modul de navigare din Google Chrome, așa cum se întâmpla și în NVDA 2019.1. (#10713)
* Acum, puteți da click dreapta și dacă folosiți un dispozitiv cu ecran tactil, ca și cum ați folosi un maus fizic, apăsând o dată cu un deget și ținând apăsat. (#3886)
* Suport pentru următoarele afișaje braille: APH Chameleon 20, APH Mantis Q40, HumanWare BrailleOne, BrailleNote Touch v2 și NLS eReader. (#10830)

### Modificări

* NVDA va împiedica sistemul să se blocheze sau să intre în modul de repaus atunci când va citi tot. (#10643)
* Suport pentru iframe-urile out-of-process din Mozilla Firefox. (#10707)
* S-a actualizat traducătorul braille liblouis la versiunea 3.12. (#10161)

### Defecte Rezolvate

* Am făcut astfel încât NVDA să nu mai anunțe simbolul Unicode „minus” (U+2212). (#10633)
* La instalarea suplimentelor din administratorul de suplimente, numele dosarelor și fișierelor din fereastra de navigare nu mai sunt raportate de două ori. (#10620, #2395)
* În Firefox, la încărcarea Mastodon având activată interfața web avansată, toate cronologiile sunt redate corect în modul de navigare. (#10776)
* În modul de navigare, NVDA raportează „nebifat” pentru casetele care nu sunt bifate acolo unde uneori nu o făcea. (#10781)
* Controalele de comutare ARIA nu mai raportează informații precum „nu este apăsat bifat” sau „apăsat bifat”, menite să genereze confuzie în rândul utilizatorilor. (#9187)
* Nu ar mai trebui ca vocile SAPI4 să refuze să pronunțe un anume text. (#10792)
* NVDA poate din nou să citească ecuațiile matematice din Microsoft Word și să interacționeze cu ele. (#10803)
* NVDA va anunța din nou textul neselectat din modul de navigare la apăsarea unei taste săgeată cât timp textul este selectat. (#10731)
* NVDA nu se mai închide dacă există o eroare la pornirea eSpeak. (#10607)
* Erorile cauzate de Unicode în traduceri pentru scurtături nu mai opresc instalatorul, atenuate de revenirea la textul în engleză. (#5166, #6326)
* Ieșirea listelor și a tabelelor dinn sayAll, cu citirea de suprafață activată, nu mai anunță în continuu ieșirea din listă sau tabel.

### Modificări pentru Dezvoltatori

* Ghidul dezvoltatorului este construit acum cu Sphinx. (#9840)
* Câteva funcții de vorbire au fost împărțite în două. (#10593)
  * Versiunea speakX rămâne, însă acum depinde de o funcție getXSpeech, care întoarce o frecvență de vorbire.
  * Acum, speakObjectProperties se bazează pe getObjectPropertiesSpeech
  * Acum, speakObject se bazează pe getObjectSpeech
  * Acum, speakTextInfo se bazează pe getTextInfoSpeech
  * speakWithoutPauses a fost convertită într-o clasă și refabricată, însă nu ar trebui să afecteze în vreun fel compatibilitatea.
  * getSpeechForSpelling este depreciată, (deși încă este disponibilă) utilizați în schimb getSpellingSpeech.
  * Modificări private care nu ar trebui să îi afecteze pe dezvoltatorii de suplimente:
  * Acum, _speakPlaceholderIfEmpty este _getPlaceholderSpeechIfTextEmpty
  * Acum, _speakTextInfo_addMath este _extendSpeechSequence_addMathForTextInfo
* Vorbirea 'reason' a fost convertită într-un Enum, vedeți clasa controlTypes.OutputReason. (#10703)
  * Constantele nivelurilor de modul 'reason' sunt depreciate.
* Dependințele de compilare ale NVDA necesită Visual Studio 2019 (16.2 sau mai nou). (#10169)
* S-a actualizat SCons la versiunea 3.1.1. (#10169)
* Se permite din nou behaviors._FakeTableCell să nu aibă nicio locație definită. (#10864)

## 2019.3

NVDA 2019.3 este o versiune foarte importantă care conține modificări printre care se regăsesc actualizarea de la Python 2 la Python 3 și o rescriere majoră a subsistemului vorbirii NVDA.
Deși aceste modificări anulează compatibilitatea cu suplimentele NVDA mai vechi, actualizarea Python 3 este necesară pentru securitate, iar modificările la vorbire permit inovații în viitorul apropiat.
 Printre alte noutăți pe care le aduce această versiune se regăsesc suportul pentru VM-urile Java pe 64 de biți, funcționalitățile Cortină Ecran și Evidențiere Focalizare, suportul pentru mai multe afișaje braille și un nou monitor braille, precum și multe defecte rezolvate.

### Noi Funcționalități

* Acuratețea cu care mausul se deplasează la comanda obiectului navigator a fost îmbunătățită în câmpurile de text din aplicațiile Java. (#10157)
* S-a adăugat suportul pentru următoarele afișaje braille de la Handy Tech:
 * Basic Braille Plus 40
 * Basic Braille Plus 32
 * Connect Braille
* Acum, toate gesturile setate de utilizator pot fi eliminate prin apăsarea unui nou buton aflat în fereastra de dialog a gesturilor de intrare, numit „Resetare la valorile implicite”. (#10293)
* Acum, raportarea fontului din Microsoft Word înștiințează dacă textul este marcat ca ascuns. (#8713)
* S-a adăugat o comandă care deplasează cursorul de examinare la poziția care  era setată ca marcaj de început pentru selecție sau copiere: NVDA+shift+F9. (#1969)
* În Internet Explorer, Microsoft Edge și în versiunile recente de Firefox și Chrome, reperele sunt raportate în modul de focalizare și în navigarea obiectului. (#10101)
* În Internet Explorer, Google Chrome și Mozilla Firefox, puteți naviga la articole folosind scripturile navigării rapide. Aceste scripturi sunt neasciate în mod implicit și pot fi atribuite în dialogul gesturilor de intrare atunci când acesta este deschis dintr-un document în care modul de navigare este prezent. (#9227)
 * Și Figurile sunt raportate. Ele sunt considerate obiecte, prin urmare sunt navigabile cu tasta o a navigării rapide.
* În Internet Explorer, Google Chrome și Mozilla Firefox, elementele articolelor sunt raportate cu navigarea obiectului și opțional în modul de navigare dacă acesta este activat din setările de formatare a documentului. (#10424)
* S-a adăugat cortina ecranului, care face întregul ecran negru în Windows 8 și/sau în versiunile mai noi. (#7857)
 * S-a adăugat un script care activează cortina ecranului (până la următoarea repornire a NVDA cu o singură apăsare, ori cât timp rulează NVDA cu două apăsări), niciun gest implicit nu este atribuit.
 * Cortina poate fi activată și configurată în secțiunea „viziune” a ferestrei de dialog a setărilor NVDA.
* Noua versiune de NVDA vine la pachet și cu funcționalitatea de evidențiere a ecranului. (#971, #9064)
 * Evidențierea focalizării, obiectul navigator și poziția cursorului de scriere al modului de navigare pot fi activate și configurate în secțiunea „Vedere” a ferestrei de dialog a setărilor NVDA.
 * Notă: această caracteristică este incompatibilă cu suplimentul Focus Higlight, însă suplimentul încă poate fi utilizat atât timp cât commpilarea în evidențiator este inactivă.
* S-a adăugat unealta Monitor Braille, care vă permite să vizualizați ieșirea braille printr-o fereastră pe ecran. (#7788)

### Modificări

* Acum, manualul de utilizare descrie cum se folosește NVDA în Consola Windows. (#9957)
* În mod implicit, executarea nvda.exe înlocuiește o copie a NVDA care rulează deja. Parametrul de înlocuire -r|--replace, care este folosit în Linia de Comandă, încă este acceptat, însă ignorat. (#8320)
* În Windows 8 sau mai nou, NVDA va raporta numele produsului și informații cu privire la versiune pentru aplicațiile găzduite precum cele descărcate din Microsoft Store folosindu-se de informațiile oferite de acestea. (#4259, #10108)
* La activarea sau dezactivarea schimbărilor de urmărire cu tastatura din Microsoft Word, NVDA va anunța starea setării. (#942)
* Numărul versiunii de NVDA este înregistrat ca primul mesaj din jurnal. Acesta apare chiar dacă înregistrarea a fost dezactivată din Interfața Grafică a Utilizatorului. (#9803)
* Dialogul de setări nu mai permite modificarea nivelului configurat al jurnalului dacă aceasta a fost suprascrisă din Linia de Comandă. (#10209)
* În Microsoft Word, NVDA anunță starea de afișare a caracterelor neimprimabile la apăsarea scurtăturii de comutare Ctrl+Shift+8 . (#10241)
* S-a actualizat traducătorul braille Liblouis la commit-ul 58d67e63. (#10094)
* Când este activă raportarea caracterelor CLDR (aici sunt incluse și emoticoanele), ele sunt anunțate la toate nivelurile de punctuație. (#8826)
* Au fost incluse în NVDA pachete de Python aparținând unor terțe părți, cum ar fi comtypes, acum își înregistrează avertismentele și erorile în jurnalul NVDA. (#10393)
* S-au actualizat adnotările emoticoanelor Depozitului de Date Locale Comune Unicode la versiunea 36.0. (#10426)
* La focalizarea unei grupări din modul de navigare, și descrierea este citită. (#10095)
* Java Access Bridge este inclus cu NVDA pentru activarea accesului la aplicațiile Java, inclusiv pentru VM-urile Java bazate pe 64 de biți. (#7724)
* Dacă Java Access Bridge nu este activat pentru utilizator, NVDA îl activează automat la pornire. (#7952)
* S-a actualizat eSpeak-NG la 1.51-dev, commit ca65812ac6019926f2fbd7f12c92d7edd3701e0c. (#10581)

### Defecte Rezolvate

* Acum, emoticoanele și alte caractere unicode bazate pe 32 de biți ocupă mai puțin spațiu pe un afișaj braille atunci când sunt afișate ca valori hexadecimale. (#6695)
* În Windows 10, NVDA va anunța indiciile din aplicațiile universale dacă este setat să le raporteze în fereastra de dialog a prezentării obiectului. (#8118)
* În Windows 10 1607 sau mai nou, textul scris este raportat în Mintty. (#1348)
* În Windows 10 1607 sau mai nou, ieșirea din Consola Windows care apare în apropierea cursorului de scriere nu mai este anunțată. (#513)
* Controalele din dialogul de comprimare al Audacity sunt anunțate la navigarea prin fereastra acestuia. (#10103)
* NVDA nu mai tratează spațiile ca cuvinte din obiectul de examinare în editoarele bazate pe Scintilla precum Notepad++. (#8295)
* NVDA va împiedica sistemul să intre în modul de hibernare la deplasarea prin text cu comenzi ale afișajelor braille. (#9175)
* În Windows 10, Braille-ul va urmări editarea conținuturilor de celulă din Microsoft Excel și din alte controale de text unde obișnuia să funcționeze cu întârziere. (#9749)
* NVDA va raporta din nou sugestiile din bara de adrese a Microsoft Edge. (#7554)
* NVDA nu mai este silențios atunci când focalizează un antet de control al unui fișier HTML în Internet Explorer. (#8898)
* În Microsoft Edge bazat pe EdgeHTML, NVDA nu va mai reda sunetul de căutare pentru sugestii atunci când fereastra devine maximizată. (#9110, #10002)
* Casetele combinate ARIA 1.1 sunt suportate în Mozilla Firefox și Google Chrome. (#9616)
* NVDA nu va mai raporta conținutul coloanelor ascunse vizual pentru elementele de listă din controalele SysListView32. (#8268)
* Dialogul de setări nu mai afișează "info" ca nivel curent al jurnalului în modul de siguranță. (#10209)
* În meniul Start pentru Windows 10 Anniversary Update și mai nou, NVDA va anunța detaliile rezultatelor căutării. (#10232)
* În modul de navigare, dacă deplasarea cursorului sau utilizarea navigării rapide face ca documentul să sufere modificări, NVDA nu mai citește incorect conținutul în unele cazuri. (#8831, #10343)
* Au fost corectate niște nume de buline din Microsoft Word. (#10399)
* În Windows 10 May 2019 Update și mai nou, NVDA va anunța din nou primul emoticon selectat sau primul element al planșetei atunci când panoul de emoticoane, respectiv istoricul planșetei se deschid. (#9204)
* În Poedit se pot vedea din nou traduceri pentru limbi de la dreapta la stânga. (#9931)
* În aplicația Setări din Windows 10 April 2018 Update și mai nou, NVDA nu va mai anunța informații ale barei de progres pentru metri de volum, găsite în pagina Sisttem/Sunete. (#10284)
* Expresiile regulate invalide din dicționarele de vorbire nu mai întrerup complet vorbirea din NVDA. (#10334)
* La citirea elementelor cu bulină din Microsoft Word cu Interfața Automată a Utilizatorului activată, bulina din următorul element de listă nu mai este anunțată incorect. (#9613)
* Au fost rezolvate niște probleme rare de traducere braille și niște erori cu liblouis. (#9982)
* Aplicațiile Java pornite înaintea NVDA sunt accesibile. Nu mai este necesară repornirea acestora. (#10296)
* În Mozilla Firefox, când elementul focalizat devine marcat ca actual (aria-current), această modificare nu mai este anunțată în mod repetat. (#8960)
* NVDA nu va mai trata anumite caractere unicode compuse precum e-ul cu accent ascuțit ca un singur caracter la deplasarea prin text. (#10550)
* Este suportată versiunea 4 a Spring Tool Suite. (#10001)
* Nu rosti de două ori numele atunci când relația țintă aria-labelledby este un element interior. (#10552)
* În versiunea 1607 a Windows 10 și în versiunile mai noi, caracterele la tastarea cărora sunt utilizate tastaturi braille sunt rostite în multe situații. (#10569)
* La modificarea dispozitivului audio de ieșire, tonurile redate de NVDA vor fi redate prin noul dispozitiv audio selectat. (#2167)
* În Mozilla Firefox, mutarea focalizării în modul de navigare este mai rapidă. Aceasta face ca deplasarea cursorului din modul de navigare să aibă o viteză de reacție mult mai bună în multe situații. (#10584)

### Modificări pentru Dezvoltatori

* S-a actualizat Python la 3.7. (#7105)
* S-a actualizat pySerial la versiunea 3.4. (#8815)
* S-a actualizat wxPython la 4.0.3, care suportă Python 3.5+ (#9630)
* S-a actualizat six la versiunea 1.12.0 (#9630)
* S-a actualizat py2exe la versiunea 0.9.3.2 (în dezvoltare, commit b372a8e de la albertosottile/py2exe#13). (#9856)
* S-a actualizat modulul de comtype-uri UIAutomationCore.dll la versiunea 10.0.18362. (#9829)
* Fila-completare din consola Python sugerează doar atribute care încep cu o liniuță joasă (underscore) dacă aceasta este inserată mai întâi. (#9918)
* Instrumentul de linting Flake8 a fost integrat cu SCon-uri care reflectă cerințele codului pentru pull request-uri. (#5918)
* Întrucât NVDA nu mai depinde de pyWin32, module precum win32api și win32con nu mai sunt disponibile pentru suplimente. (#9639)
 * Apelurile win32api pot fi înlocuite cu apeluri directe la funcțiile dll win32 prin ctype-uri.
 * Ar trebui ca constant-urile win32con să fie definite în fișierele dumneavoastră.
* Argumentul „async” din nvwave.playWaveFile a fost redenumit la „asynchronous”. (#8607)
* Metodele speakText și speakCharacter din obiectele synthDriver nu mai sunt suportate.
 * Această funcționalitate este controlată de SynthDriver.speak.
* Clasele SynthSetting din synthDriverHandler au fost eliminate. Folosiți în schimb clasele driverHandler.DriverSetting.
* Clasele SynthDriver nn-ar mai trebui să expună indexul prin proprietatea lastIndex.
 * În schimb, ar trebui să notifice acțiunea synthDriverHandler.synthIndexReached cu indexul, odată ce redarea tuturor fișierelor audio s-a încheiat înainte de acel index.
* Clasele SynthDriver ar trebui să notifice acțiunea synthDriverHandler.synthDoneSpeaking, odată ce redarea tuturor fișierelor audio dintr-un apel SynthDriver.speak s-a încheiat.
* Clasele SynthDriver trebuie să suporte speech.PitchCommand în metoda lor de vorbire, întrucât modificările la ton pentru ortografia vorbirii depind de această funcționalitate.
* Funcționalitatea de vorbire getSpeechTextForProperties a fost redenumită în getPropertiesSpeech. (#10098)
* Funcționalitatea braille getBrailleTextForProperties a fost redenumită în getPropertiesBraille. (#10469)
* Câteva funcționalități de vorbire au fost modificate pentru a se reveni la secvențele de vorbire. (#10098)
 * getControlFieldSpeech
 * getFormatFieldSpeech
 * getSpeechTextForProperties, numită acum getPropertiesSpeech
 * getIndentationSpeech
 * getTableInfoSpeech
* S-a adăugat un modul textUtils care simplifică diferențele de șiruri dintre șirurile Python 3 și șirurile unicode Windows. (#9545)
 * Vedeți documentația modulului și modulul textInfos.offsets pentru  modele de implementări.
* S-a eliminat o funcție depreciată. (#9548)
 * AppModule-uri eliminate:
 * Reportofonul Windows XP.
 * Klango Player, un program abandonat.
 * A fost eliminat wrapper-ul configobj.validate.
 * Ar trebui să se folosească un nou cod din validarea importului configobj în loc de validarea importului
 * textInfos.Point și textInfos.Rect au fost înlocuite de locationHelper.Point, respectiv de locationHelper.RectLTRB.
 * braille.BrailleHandler._get_tether și braille.BrailleHandler.set_tether au fost eliminate.
 * config.getConfigDirs a fost eliminat.
 * config.ConfigManager.getConfigValidationParameter a fost înlocuit de getConfigValidation
 * Proprietatea inputCore.InputGesture.logIdentifier a fost eliminată.
   * Utilizați în schimb _get_identifiers în inputCore.InputGesture.
 * synthDriverHandler.SynthDriver.speakText/speakCharacter, a fost eliminat.
 * S-au eliminat câteva clase synthDriverHandler.SynthSetting.
   * Erau păstrate pentru compatibilitatea cu programe mai vechi (#8214), însă acum sunt considerate ca fiind depășite.
   * Driverele care foloseau clasele SynthSetting trebuie să fie actualizate ca să folosească clasele DriverSetting.
 * au fost eliminate niște coduri tradiționale, în mod particular:
  * Suportul pentru lista de mesaje din Outlook pre 2003.
  * O clasă de adsrat pentru meniul start clasic, găsită numai în Windows Vista și mai vechi.
  * Abandonarea suportului pentru Skype 7, întrucât Microsoft nu mai lucrează la el.
* Un framework care le permite dezvoltatorilor să creeze furnizori de evidențiere a viziunii; module care pot modifica conținutul ecranelor, bazat opțional pe intrarea din NVDA despre localizările obiectelor. (#9064)
 * Suplimentele pot să-și lase proprii furnuizori într-un folder visionEnhancementProviders.
 * Vedeți modulele vision și visionEnhancementProviders pentru implementarea framework-ului, respectiv exemple.
* Proprietățile claselor abstracte sunt suportate pe obiecte care moștenesc de la baseObject.AutoPropertyObject (de exemplu NVDAObjects și TextInfos). (#10102)
* S-a introdus displayModel.UNIT_DISPLAYCHUNK ca o unitate constantă textInfos specifică DisplayModelTextInfo. (#10165)
 * această constantă nouă permite plimbarea prin text într-un DisplayModelTextInfo într-un mod care seamănă mai îndeaproape cu modul în care sunt salvate bucățile de text în modelul de bază.
* displayModel.getCaretRect întoarce o instanță a locationHelper.RectLTRB. (#10233)
* Constantele UNIT_CONTROLFIELD și UNIT_FORMATFIELD au fost mutate de la virtualBuffers.VirtualBufferTextInfo la pachetul textInfos. (#10396)
* Pentru fiecare intrare din jurnalul NVDA sunt incluse informații despre „firul originar”. (#10259)
* Obiectele TextInfo UIA pot fi mutate/extinse de pagină, poveste și unitățile  de text formatField. (#10396)
* Modulele externe (appModule-uri și globalPlugin-uri) sunt mai puțin capabile să distrugă creația NVDAObjects. 
 * Excepțiile cauzate de metodele „chooseNVDAObjectOverlayClasses” și „event_NVDAObject_init” sunt prinse și înregistrate.
* Dicționarul aria.htmlNodeNameToAriaLandmarkRoles a fost redenumit în aria.htmlNodeNameToAriaRoles. De asemenea, el conține roluri care nu sunt repere.
* scriptHandler.isCurrentScript a fost eliminat din cauza lipsei de utilizare. Nu există niciun substitut pentru el. (#8677)

## 2019.2.1

Aceasta este o versiune minoră care repară câteva erori prezente în NVDA 2019.2. Reparările includ:

* Câteva crash-uri din Gmail văzute  în Firefox și în Chrome la interacțiunea cu meniuri pop-upp particulare, de exemplu la crearea de filtre sau la modificarea anumitor setări din Gmail. (#10175, #9402, #8924)
* În Windows 7, NVDA nu mai face ca Windows Explorer să dea crash când e folosit mausul în meniul start. (#9435) 
* În Windows 7, Windows Explorer nu mai dă crash la accesarea câmpurilor de editare de tip metadata. (#5337)
* NVDA nu se mai blochează la interacțiunea cu o imagine cu un URI base64 în Mozilla Firefox sau Google Chrome. (#10227)

## 2019.2

Caracteristicile principale ale acestei versiuni includ autodetectarea afișajelor braille de la Freedom Scientific, o setare de test inclusă în panoul de setări avansate care  face ca modul de navigare să nu mai miște focalizarea de unul singur, (această setare poate aduce îmbunătățiri), o opțiune de amplificare a vitezei pentru sintetizatorul Windows OneCore pentru ca mărirea vitezei vocilor să fie mai accentuată și multe alte defecte rezolvate.

### Noi Funcționalități

* Suportul NVDA pentru Miranda NG funcționează acum și cu versiuni mai noi ale aplicației. (#9053)
* Puteți dezactiva implicit modul de navigare dezactivând noua opțiune numită „Activează modul de navigare la încărcarea paginii” din setările modului de navigare NVDA. (#8716)
 * Rețineți că, chiar și atunci când această opțiune este dezactivată, puteți activa manual modul de navigare apăsând NVDA+spațiu.
* Puteți filtra simbolurile din dialogul punctuație/pronunțare simboluri ca și cum ați filtra obiecte din lista de elemente și din dialogul gesturilor de intrare. (#5761)
* S-a adăugat o comandă care modifică rezoluția unității de text a mausului (cât de mult text va fi citit la mișcarea mausului), nu are atribuit un gest implicit. (#9056)
* Sintetizatorul Windows OneCore are cum o opțiune de amplificare a vitezei vocilor, ceea ce înseamnă că viteza acestora se poate mări semnificativ. (#7498)
* Această opțiune poate fi setată din setările sintetizatorului pentru sintetizatoarele cu care este compatibilă la ora actuală, eSpeak-NG și Windows OneCore). (#8934)
* Acum, profilurile de configurare pot fi activate manual cu gesturi. (#4209)
  * Gesturile trebuie să fie configurate în dialogul lor de inntrare.
* În Eclipse, s-a adăugat suportul pentru autocompletarea din editorul de coduri. (#5667)
 * În plus, informațiile Javadoc, dacă există, pot fi citite din editor utilizându-se comanda NVDA+d.
* S-a adăugat o opțiune de test în panoul setărilor avansate care vă dă posibilitatea să opriți focalizarea sistemului să urmărească cursorul modului de Navigare (Setează automat focalizarea sistemului la elementele focalizabile). (#2039) Totuși, s-ar putea să nu funcționeze pe toate sit-urile web, s-ar putea să rezolve: 
 * Efectul benzii elastice: NVDA anulează sporadic apăsarea ultimei combinații de taste a modului de navigare sărind la locația precedentă.
 * Casetele de editare „fură” focalizarea sistemului la deplasarea printre ele cu săgeată jos pe anumite site-uri web.
 * Combinațiile de taste ale modului de navigare răspund greu.
* Pentru driverele afișajelor braille care le suportă, setările de driver pot fi modificate din categoria setărilor braille, aflată în fereastra de dialog a setărilor NVDA. (#7452)
* Afișajele braille de la Freedom Scientific sunt suportate acum de autodetectarea afișajelor braille. (#7727)
* S-a adăugat o comandă care afișează înlocuirea pentru simbolul de sub cursorul de examinare. (#9286)
* În Consola Python, câmpul de editare suportă acum lipirea rândurilor multiple de pe planșetă. (#9776)

### Modificări

* Volumul sintetizatorului este mărit și micșorat cu 5 în loc de 10 la utilizarea inelului de setări. (#6754)
* Textul din administratorul de suplimente este acum mai clar atunci când NVDA este lansat cu insigna --disable-addons. (#9473)
* Combinația de taste pentru câmpul de filtrare din lista de elemente din modul de navigare a fost modificată la alt+y. (#8728)
* S-au actualizat adnotările emoticoanelor Depozitului de Date Comune Locale Unicode la versiunea 35.0. (#9445)
* S-a actualizat Espeak-NG la commit-ul 67324cc.
* S-a actualizat traducătorul braille liblouis la versiunea 3.9.0. (#9439)
* Dacă un afișaj braille autodetectat este conectat prin Bluetooth, NVDA va continua să caute afișaje USB suportate de același driver și să treacă la o conexiune USB dacă devine disponibilă. (#8853)
* NVDA nu va mai spune cuvântul „selectat” după ce citește textul pe care un utilizator tocmai l-a selectat. (#9028)
* În Microsoft Visual Studio Code, modul de navigare este dezactivat în mod implicit. (#9828)

### Defecte rezolvate

* NVDA nu mai dă crash-uri dacă un folder de suplimente este gol. (#7686)
* Mărcile LTR și RTL nu mai sunt afișate în braille sau pe pronunțare de caracter la accesarea ferestrei de proprietăți. (#8361)
* Când se sare la câmpuri formular cu navigarea rapidă a modului de navigare, întregul câmp formular este anunțat, nu doar prima linie. (#9388)
* NVDA nu mai devine silențios când aplicația Mail din Windows 10 se închide. (#9341)
* NVDA nu mai dă rateuri la pornire atunci când setările regionale ale utilizatorului au configurată o limbă pe care NVDA nu o cunoaște, un bun exemplu fiind Engleza din Țările de Jos. (#8726)
* Când modul de navigare este activ în Microsoft Excel, iar dumneavoastră treceți la un navigator din modul de focalizare sau vice versa, starea modului de navigare este raportată acum corespunzător. (#8846)
* Acum, NVDA raportează corespunzător rândul de la cursorul mausului în Notepad++ și în alte editoare bazate pe Scintilla. (#5450)
* În Google Docs și în alte editoare bazate pe web, nu se mai afișează incorect în braille „lst end” înaintea cursorului din mijlocul unui element de listă. (#9477)
* În actualizarea din mai 2019 a Windows 10, NVDA nu mai citește multe notificări de volum dacă acesta se modifică cu butoane hardware când File Explorer are focalizare. (#9466)
* Încărcarea ferestrei de dialog a punctuației și pronunțării simbolurilor este acum mult mai rapidă când se utilizează dicționare de simboluri care conțin peste 1000 de intrări. (#8790)
* În editoarele Scintila precum Notepad++, NVDA poate citi rândul corect atunci când wordwrap-ul este activvat. (#9424)
* În Microsoft Excel, locația celulei este anunțată după ce se schimbă ca urmare a acționării comenzilor shift+enter sau shift+enter de pe blocul numeric. (#9499)
* În Visual Studio 2017 și mai nou, în fereastra de explorare a obiectelor, elementul selectat din arborele obiectelor sau din arborele membrilor cu categorii este raportat corect. (#9311)
* Suplimentele cu numele a căror diferență este făcută de majuscule, nu mai sunt tratate ca suplimente separate. (#9334)
* Pentru vocile Windows OneCore, viteza setată în NVDA nu mai este afectată de cea setată în configurările de vorbire ale Windows 10. (#7498)
* Jurnalul NVDA poate fi deschis cu NVDA+F1 dacă nu există informații de la dezvoltatori cu privire la obiectul navigator curent. (#8613)
* Iarăși e posibilă folosirea comenzile NVDA de navigare în tabel în Google Docs, Firefox și Chrome. (#9494)
* Acum, tastele barei de protecție funcționează corect pe afișajele braille de la Freedom Scientific. (#8849)
* La citirea primului caracter al unui document în Notepad++ 7.7 X64, NVDA nu se mai blochează pentru un timp maxim de 10 secunde. (#9609)
* Acum, HTCom poate fi folosit cu un afișaj braille Handy Tech în combinație cu NVDA. (#9691)
* În Mozilla Firefox, actualizările la o regiune live nu mai sunt raportate dacă acea regiune live se află într-o filă de fundal. (#1318)
* Dialogul de căutare al modului de navigare NVDA funcționează fără probleme chiar și atunci când fereastra de dialog care conține detalii despre NVDA este deschisă la un moment dat în fundal. (#8566)

### Modificări pentru Dezvoltatori

* Puteți seta proprietatea "disableBrowseModeByDefault" în modulele de aplicație pentru a lăsa modul de navigare dezactivat în mod implicit. (#8846)
* Stilul extins al unei ferestre este expus utilizându-se proprietatea `extendedWindowStyle` pe obiectele ferestrei și pe derivatele lor. (#9136)
* Sa actualizat pachetul comtypes la 1.1.7. (#9440, #8522)
* Când se folosește comanda informației de raportare a modulului, ordinea informațiilor se modifică pentru ca modulul să fie prezentat mai întâi. (#7338)
* S-a adăugat un exemplu care să demonstreze utilizarea nvdaControllerClient.dll din C#. (#9600)
* Sa adăugat o nouă funcție isWin10 la modulul winVersion, care indică dacă această copie de NVDA rulează sau nu (cel puțin) versiunile furnizate de Windows 10 (cum ar fi 1903). (#9761)
* Consola NVDA Python conține acum multe module utile în namespace-ul ei (cum ar fi appModules, globalPlugins, config și textInfos). (#9789)
* Rezultatul ultimei comenzi executată în consola NVDA Python este accesibil din variabila _ (line). (#9782)
 * Țineți cont de faptul că acesta umbrește funcția de traducere gettext, numită și „_”. Pentru a accesa funcția de traducere: del _

## 2019.1.1

Această versiune minoră aduce în atenția utilizatorilor următoarele erori rezolvate:

* NVDA nu mai face ca Excel 2007 să dea crash sau să refuze să raporteze o celulă care conține o formulă. (#9431)
* Google Chrome nu mai dă crash-uri la interacțiunea cu anumite listbox-uri. (#9364)
* A fost rezolvat un bug care împiedica copierea unei configurații de utilizator în profilul configurației de sistem. (#9448)
* În Microsoft Excel, NVDA utilizează din nou mesajele localizate la raportarea locației celulelor unite. (#9471)

## 2019.1

Caracteristicile principale ale acestei versiuni includ îmbunătățiri de performanță la accesarea Microsoft Word și Microsoft Excel, îmbunătățiri de stabilitate și securitate precum suportul pentru suplimente cu informații despre compatibilitatea versiunii și multe alte defecte rezolvate.

Vă rugăm să țineți cont de faptul că începând cu această versiune de NVDA, appModule-urile personalizate, globalPlugin-urile, driverele afișajelor braille și ale sintetizatoarelor nu vor mai fi încărcate automat din dosarul configurației utilizatorului. 
S-a ajuns la concluzia că ar fi mai bine ca acestea să fie instalate ca parte a unui supliment NVDA. Pentru cei care lucrează la un supliment, codul pentru test poate fi pus într-un dosar scratchpad pentru dezvoltatori, aflat în dosarul configurației utilizatorului NVDA, dacă opțiunea Developer scratchpad este activată din noul panou al setărilor avansate NVDA.
Aceste modificări sunt făcute pentru a asigura compatibilitatea codului personalizat, astfel încât NVDA să nu aibă probleme dacă acel cod devine incompatibil cu versiunile mai noi.
Vă rugăm să consultați cu atenție lista de modificări pentru mai multe detalii în legătură cu asta, iar astfel veți afla și cum suplimentele sunt mai bine versionate.

### Noi funcționalități

* Noi tabele braille: Afrikaans, arabă (braille în 8 puncte pentru calculator), arabă grad 2, spaniolă grad 2. (#4435, #9186)
* S-a adăugat o opțiune în setările mausului care face ca NVDA să se descurce în situațiile în care mausul este controlat de o altă aplicație. (#8452)
 * Aceasta va permite ca NVDA să urmărească mausul atunci când calculatorul este controlat de la distanță prin utilizarea TeamViewer sau a altui program de control de la distanță.
* S-a adăugat parametrul liniei de comandă `--enable-start-on-logon` pentru a ne permite să  setăm dacă vrem ca instalările silențioase de NVDA să îl facă să pornească la autentificarea în windows sau nu.
* Puteți dezactiva caracteristicile NVDA de înregistrare în jurnal setând nivelul de înregistrare la „dezactivat” din panoul setărilor generale. (#8516)
* Prezența formulelor în LibreOffice și în foile de calcul Apache OpenOffice este raportată. (#860)
* În Mozilla Firefox și Google Chrome, modul de navigare raportează elementul selectat din casetele de liste și din cele de tip vedere listă extinsă.
 * Aceasta funcționează în Firefox 66 și mai nou.
 * Nu funcționează pentru anumite casete de liste (controale de selectare HTML) din Chrome.
* Suport prematur pentru aplicații precum Mozilla Firefox pe calculatoare cu procesoare ARM64 (e.x. Qualcomm Snapdragon). (#9216)
* S-a adăugat o nouă categorie pentru setările avansate în dialogul setărilor NVDA, incluzând o opțiune de încercare a noului suport NVDA pentru Microsoft Word prin API-ul Microsoft UI Automation. (#9200)
* S-a adăugat suportul pentru vizualizarea grafică din Windows Disk Management. (#1486)
* S-a adăugat suportul pentru Handy Tech Connect Braille și Basic Braille 84. (#9249)

### Modificări

* S-a actualizat traducătorul braille liblouis la versiunea 3.8.0. (#9013)
* Autorii de suplimente pot stabili acum o versiune minimă necesară de NVDA pentru suplimentele lor. NVDA va refuza să instaleze sau să încarce un supliment a cărui versiune minimă necesară de NVDA este mai veche decât versiunea NVDA curentă. (#6275)
* Autorii de suplimente pot să specifice ultima versiune de NVDA cu care și-au testat suplimentul. Dacă un supliment a fost testat cu o versiune mai veche decât cea curentă, NVDA va refuza să instaleze sau să încarce acel supliment. (#6275)
* Această versiune de NVDA va permite instalarea și încărcarea suplimentelor care încă nu conțin informații despre versiunea minimă de NVDA și despre cea cu care au fost testate, însă actualizarea la viitoarele versiuni de NVDA (E.X. 2019.2) poate face ca aceste suplimente mai vechi să fie dezactivate.
* Comanda de deplasare a mausului la obiectul navigator este disponibilă acum și în Microsoft Word, precum și pentru comenzile UIA, în mod particular și în Microsoft Edge. (#7916, #8371)
* Raportarea textului de sub maus a fost îmbunătățită în Microsoft Edge și în alte aplicații UIA. (#8370)
* Când NVDA este pornit cu parametrul liniei de comandă `--portable-path`, calea furnizată este completată automat la încercarea de creare a unei copii portabile de NVDA utilizându-se meniul acestuia. (#8623)
* S-a actualizat calea către tabelul braille norvegian pentru reflectarea standardului din anul 2015. (#9170)
* La navigarea în paragrafe (control plus săgețile sus și jos( sau la cea în celulele de tabel (control plus alt plus toate săgețile), existența greșelilor de ortografie nu va mai fi anunțată, chiar dacă NVDA este configurat astfel încât să facă asta automat. Temeiul care stă la baza implementării acestei modificări este acela că paragrafele și celulele de tabel pot fi destul de mari, iar detectarea erorilor în unele aplicații poate fi foarte enervantă. (#9217)
* NVDA nu mai încarcă automat  appModule-uri personalizate, globalPlugin-uri și și drivere ale sintetizatoarelor și ale afișajelor braille din dosarul configurației utilizatorului. Acest cod trebuie să fie inclus într-un supliment NVDA, cu informații corecte despre versiune, asigurându-ne astfel că  codul incompatibil nu este executat cu versiunea curentă de NVDA. (#9238)
 * Pentru dezvoltatorii care vor să-și testeze codul, trebuie să activeze opțiunea „Activează dosarul scratchpad pentru dezvoltatorii NVDA”, aflată în categoria setărilor avansate NVDA, și să-și pună codul în folder-ul „scratchpad”, aflat în directorul configurației utilizatorului NVDA, atunci când această opțiune este activată.

### Defecte rezolvate

* La utilizarea sintetizatorului Windows OneCore pe actualizarea Windows 10 din aprilie 2018 sau mai nouă, nu se mai fac pauze mari în vorbire. (#8985)
* La deplasarea caracter cu caracter în editoarele de text de tip plain text control (cum ar fi Notepad) sau în modul de navigare, caracterele emoji pe 32 de biți care conțin două puncte de cod UTF-16 (cum ar fi đź¤¦) se vor citi corect. (#8782)
* S-a îmbunătățit dialogul de confirmare a repornirii după modificarea limbii de interfață a NVDA. Textele și etichetele butoanelor sunt acum mai concise și mai puțin confuze. (#6416)
* Dacă a treia parte din sintetizator eșuează să se încarce, NVDA va reveni la sintetizatorul Windows OneCore pe Windows 10, nu la Espeak. (#9025)
* S-a scos opțiunea dialogului de bun venit din meniul NVDA atâta timp cât acesta se află în ecranele securizate. (#8520)
* La deplasarea cu tasta Tab sau la folosirea navigării rapide în modul de navigare, legendele din panourile tabulator sunt raportate acum mai consistent. (#709)
* NVDA va anunța schimbările de selecție pentru anumite elemente de selectare a orei în aplicații din Windows 10 precum Alarme și Ceas. (#5231)
* În centrul de acțiuni din Windows 10, NVDA va anunța starea mesajelor la activarea sau dezactivarea acțiunilor rapide precum luminozitatea și asistarea focalizării. (#8954)
* În centrul de acțiuni din Windows 10 October 2018 Update și mai vechi, NVDA va recunoaște controlul acțiunii rapide de luminozitate ca buton în loc de buton de activare. (#8845)
* NVDA va urmări din nou cursorul și va anunța caracterele șterse din câmpurile de editare „Salt la” și „Caută” din Microsoft Excel. (#9042)
* S-a reparat o eroare rară aflată în modul de navigare din Mozilla Firefox. (#9152)
* NVDA nu mai eșuează să raporteze focalizarea pentru niște controale din pamblica Microsoft Office 2016 dacă aceasta este închisă.
* Ultimele taste de deplasare a cursorului pe afișajele eurobraille cu 80 de celule nu mai deplasează cursorul la o poziție la sau după începutul rândului braille. (#9152)
* S-a reparat navigarea de tabel în vizualizarea din Mozilla Thunderbird. (#8396)
* În Mozilla Firefox și Google Chrome, trecerea la modul de focalizare funcționează cum trebuie pentru anumite casete de liste tree-uri (unde caseta de listă sau tree nu este ea însăși focalizabilă, însă elementele ei sunt). (#3573, #9157)
* Modul de navigare este acum activat cum trebuie la citirea mesajelor din Outlook 2016/365 dacă se utilizează suportul experimental UI Automation al NVDA pentru documentele Word. (#9188)
* Acum, este mult mai puțin probabil ca NVDA să se blocheze astfel încât singura soluție rămasă să fie deconectarea dumneavoastră de la sesiunea curentă de Windows. (#6291)
* În Windows 10 October 2018 Update și mai nou, la deschiderea istoricului planșetei cloud, planșeta fiind goală, NVDA îi va anunța starea. (#9103)
* În Windows 10 October 2018 Update și mai nou, la căutarea emoji-urilor în panoul lor, NVDA va anunța topul rezultatelor căutării. (#9105)
* NVDA nu se mai blochează în fereastra principală a Oracle VirtualBox 5.2 și mai nou. (#9202)
* Reacția în Microsoft Word la navigarea rând cu rând, paragraf cu paragraf sau celulă cu celulă poate fi semnificativ îmbunătățită în unele documente. Memento: pentru cea mai bună performanță, setați Microsoft Word la vizualizare schiță cu alt+w după deschiderea unui document. (#9217)
* În Mozilla Firefox și Google Chrome, alertele false nu mai sunt raportate. (#5657)
* Îmbunătățiri semnificative de performanță la navigarea celulelor din Microsoft Excel, în mod particular atunci când foile de calcul conțin comentarii. (#7348)
* N-ar mai trebui să fie necesară activarea  opțiunilor de editare a celulelor din Microsoft Excel pentru accesarea controlului de editare a celulelor cu NVDA în Excel 2016/365. (#8146)
* S-a reparat o blocare raportată uneori în Firefox la navigarea rapidă printre repere atunci când suplimentul Enhanced Aria era în uz. (#8980)

### Modificări pentru dezvoltatori

* NVDA poate fi făcut acum cu toate edițiile Microsoft Visual Studio 2017 (nu doar cu ediția pentru comunitate). (#8939)
* Puteți include o ieșire de jurnal din liblouis în jurnalul NVDA setând steagul louis boolean în secțiunea debugLogging din configurația NVDA. (#4554)
* Autorii de suplimente pot furniza acum informații despre compatibilitatea versiunii NVDA în manifesturile suplimentelor. (#6275, #9055)
 * minimumNVDAVersion: Versiunea minimă necesară de NVDA cu care un supliment să funcționeze corespunzător..
 * lastTestedNVDAVersion: Ultima versiune de NVDA cu care a fost testat suplimentul.
* Obiectele OffsetsTextInfo  pot implementa metoda _getBoundingRectFromOffset pentru a permite recuperarea dreptunghiurilor asciate pe caractere în loc de puncte. (#8572)
* S-a adăugat o proprietate numită boundingRect la obiectele pentru recuperarea dreptunghiurilor asciate ale unei părți de text. (#8371)
* Proprietățile și metodele din clase pot fi marcate ca abstracte în NVDA. Aceste clase se vor scoate în față o eroare  dacă sunt instanțiate. (#8294, #8652, #8658)
* NVDA poate loga timpul de la intrare atunci când este vorba de text, ceea ce ajută la măsurarea reacției percepute. Aceasta poate fi activată setând opțiunea timeSinceInput la True în secțiunea debugLog a configurației NVDA. (#9167)

## 2018.4.1

Această versiune repară o eroare care apărea la pornirea NVDA dacă aragoneza era setată ca limbă de interfață a acestuia. (#9089)

## 2018.4

Caracteristicile principale ale acestei versiuni sunt performanța mai bună în versiunile noi de Firefox, raportarea de emoji cu toate sintetizatoarele, raportarea statusului „răspuns” sau „redirecționat” pentru e-mail-urile din MS Outlook, raportarea actualei distanțe a cursorului de la marginile de sus și din stânga paginii în MS Word și multe alte defecte rezolvate.

### Noi Funcționalități

* Noi tabele braille: chineză (China, mandarină) gradele 1 și 2. (#5553)
* Acum, starea Răspuns sau Redirecționat este raportată atunci când cursorul este focalizat pe elemente de e-mail din lista de mesaje Microsoft Outlook. (#6911)
* Acum, NVDA poate citi descrieri pentru emoji, precum și alte caractere care fac parte din depozitul de date locale comune Unicode. (#6523)
* În Microsoft Word, distanța cursorului de la marginile de sus și din stânga ale paginii poate fi raportată apăsând NVDA+tasta Delete de pe blocul numeric. (#1939)
* În Google Sheets cu modul braille activat, NVDA nu mai spune „selectat” la fiecare celulă atunci când focalizarea se deplasează între celule. (#8879)
* Programele Foxit Reader și  Foxit Phantom PDF sunt accesibile acum și cu NVDA (#8944)
* Instrumentul cu baze de date DBeaver este acum accesibil și cu NVDA. (#8905)

### Modificări

* Opțiunea „Anunță baloane de ajutor” din dialogul de prezentare a obiectelor a fost redenumită în „Anunță notificări”, pentru a include notificările toast din Windows 8 și mai nou. (#5789)
* În setările tastaturii din NVDA, casetele de bifat pentru activarea sau dezactivarea tastelor modificatoare ale acestui cititor de ecran sunt afișate acum într-o listă, mai degrabă decât separat.
* NVDA nu va mai prezenta informații redundante la citirea ceasului din zona de notificare (system tray) pe unele versiuni de windows. (#4364)
* S-a actualizat traducătorul braille liblouis la versiunea 3.7.0. (#8697)
* S-a actualizat eSpeak-NG la commit-ul 919f3240cbb

### Defecte Rezolvate

* În Outlook 2016/365, categoria și starea flag sunt raportate pentru mesaje. (#8603)
* Când NVDA este setat în limbi precum kirghiză, mongolă sau macedoneană, nu va mai afișa un dialog la pornire prin care să îl informeze pe utilizator că limba nu este suportată de sistemul de operare. (#8064)
* deplasarea mausului îl va muta cu mai multă acuratețe la poziția modului de navigare din Mozilla Firefox, Google Chrome și Acrobat Reader DC. (#6460)
* A fost îmbunătățită interacțiunea cu casetele combinate pe web în Firefox, Chrome și Internet Explorer. (#8664)
* Dacă rulează versiunea japoneză a Windows XP sau Vista, NVDA afișează alerta de cerințe ale versiunii OS așa cum era de așteptat. (#8771)
* Performanța crește în Mozilla Firefox la navigarea pe pagini mari cu mult conținut dinamic. (#8678)
* Braille-ul nu mai arată atributele de font dacă au fost dezactivate din setările formatării documentului. (#7615)
* NVDA nu mai dă rateuri la urmărirea focalizării din File Explorer și din alte aplicații care utilizează UI Automation atunci când o altă aplicație este ocupată. (cum ar fi procesul de prelucrare audio ). (#7345)
* În meniurile ARIA din web, tasta Escape nu va mai fi trecută prin meniu și nu va mai dezactiva modul de focalizare necondiționat. (#3215)
* În noua interfața web a Gmail, la utilizarea navigării rapide înăuntrul mesajelor în timpul citirii lor, corpul întreg al mesajului nu mai este raportat după elementul la care tocmai ați navigat. (#8887)
* După actualizarea NVDA, browserele precum Firefox și Google Chrome nu vor mai trebui să dea rateuri, iar modul de navigare ar trebui să continue să reflecteze corect actualizările la orice document curent încărcat. (#7641)
* NVDA nu mai raportează „clicabil” de mai multe ori pe același rând când găsește conținut clicabil în modul navigare. (#7430)
* Comenzile aplicate pe display-urile braille baum Vario 40 funcționează acum corect. (#8894)
* în Google prezentări (slides) cu Mozilla Firefox, NVDA nu mai raportează „text selectat” la fiecare control focalizat. (#8964)

### Modificări pentru Dezvoltatori

* Acum, gui.nvdaControls conține două clase care să creeze liste accesibile cu casete de bifat. (#7325)
 * CustomCheckListBox este o subclasă accesibilă a wx.CheckListBox.
 * AutoWidthColumnCheckListCtrl adaugă casete de bifat accesibile la un AutoWidthColumnListCtrl, care este bazat pe wx.ListCtrl.
* Dacă aveți nevoie să faceți un widget wx accesibil care să nu existe deja, puteți face astfel utilizând o instanță a gui.accPropServer.IAccPropServer_impl. (#7491)
 * Vedeți implementarea gui.nvdaControls.ListCtrlAccPropServer pentru mai multe informații.
* S-a actualizat configobj la 5.1.0dev commit 5b5de48a. (#4470)
* Acțiunea config.post_configProfileSwitch preia acum argumentul cuvânt cheie prevConf, permițând manipulatoarelor să ia măsuri pe baza diferențelor dintre configurație înainte și după comutarea profilului. (#8758)

## 2018.3.2

Aceasta este o versiune minoră care repară o eroare din Google Chrome la navigarea printre postări (tweet-uri) pe [www.twitter.com](http://www.twitter.com). (#8777)

## 2018.3.1

Aceasta este o versiune minoră care repară un defect critic din NVDA, defect care făcea ca versiunile de Mozilla Firefox bazate pe 32 de biți să dea rateuri. (#8759)

## 2018.3

Caracteristicile principale ale acestei versiuni includ detectarea automată a multor afișaje braille, suport pentru noile caracteristici ale Windows 10 precum panoul de intrare Emoji al Windows 10, dar și multe reparări ale erorilor.

### Noi Funcționalități

* NVDA raportează acum greșeli gramaticale la expunerea lor apropiată de către paginile web din Mozilla Firefox și Google Chrome. (#8280)
* Conținutul care este marcat ca fiind inserat sau șters din paginile web, este acum raportat în Google Chrome. (#8558)
* Când Braillenote este folosit ca afișaj braille, NVDA este acum compatibil cu joysticurile de rulare ale tastaturilor BrailleNote QT și Apex BT. (#6316)
* S-au creeat noi scripturi pentru raportarea timpului trecut și timpului total al titlului actual în Foobar2000. (#6596)
* Acum, simbolul tastei de comandă Mac (⌘) este anunțat la citirea textului cu orice sintetizator. (#8366)
* Prin atributul aria-roledescription, rolurilr personalizate sunt suportate acum în toate navigatoarele web.
* Tabele braille noi: cehă 8 puncte, curdă centrală, esperanto, maghiară și suedeză, braille în 8 puncte pentru calculator. (#8227)
* A fost adăugat suportul pentru detectarea automată a afișajelor braille din fundal. (#1271)
 * Afișajele ALVA, Baum/HumanWare/APH/Orbit, Eurobraille, Handy Tech, Hims, SuperBraille și HumanWare BrailleNote și Brailliant BI/B sunt suportate acum.
 * Puteți activa această caracteristică selectând opțiunea automată din lista afișajelor braille, care se află în dialogul selectării afișajelor braille.
 * Vă rugăm să consultați documentația pentru mai multe detalii.
* S-a adăugat suportul pentru diverse caracteristici de intrare moderne introduse în versiunile recente de Windows 10. Acestea includ panoul de emoji (Fall Creators Update), dictarea (Fall Creators Update), sugestiile de intrare ale tastatturii hardware (April 2018 Update) și lipirea pe planșeta cloud (October 2018 Update). (#7273)
* Conținutul marcat ca citat bloc utilizându-se ARIA (role blockquote) este suportat acum în Mozilla Firefox 63. (#8577)

### Modificări

* Acum, lista de limbi disponibile în dialogul setărilor generale este sortată pe baza numelor limbilor, nu pe baza codurilor ISO 639. (#7284)
* S-au adăugat gesturile implicite pentru alt shift tab și pentru windows tab cu toate afișajele braille suportate de la Freedom Scientific. (#7387)
* Pentru afișajele braille ALVA BC680 și protocol converter, este posibilă atribuirea unor funcții diverse la smart pad-ul stâng sau la cel drept, la tastele tumb sau etouch. (#8230)
* Pentru afișajele ALVA BC6,combinația de taste sp2+sp3 va anunța data și ora curentă, în timp ce sp1+sp2 simulează tasta Windows (#8230)
* La prima pornire a acestei versiuni NVDA, utilizatorii vor fi întrebați dacă acceptă ca NVDA să trimită statistici despre modul de folosire către NV Access de fiecare dată când NVDA  caută automat actualizări. (#8217)
* Dacă utilizatorul acceptă trimiterea statisticilor către NV Access în timpul verificării pentru actualizări noi, NVDA va trimite numele driverului pentru sintetizator și numele driverului pentru afișajul braille conectat. Aceste date vor ajuta la priorizarea lucrărilor din viitor cu referință la sintetizatoare și afișaje braille. (#8217)
* S-a actualizat traducătorul braille liblouis la versiunea 3.6.0. (#8365)
* S-a actualizat calea pentru tabelul rusesc în opt puncte pentru calculator. (#8446)
* S-a actualizat Espeak-NG la 1.49.3dev commit 910f4c2 (#8561)

### Defecte Rezolvate

* Etichetele accesibile pentru comenzile din Google Chrome sunt acum raportate cu ușurință în modul de navigare atunci când eticheta nu apare ca și conținut în sine. (#4773)
* Notificările sunt suportate acum în Zoom. De exemplu, aceasta include starea de activare/dezactivare și mesajele primite. .(#7754)
* Când sunteți în modul de navigare, commutarea prezentării contextului braille nu mai face ca ieșirea braille să oprească urmărirea. (#7741)
* Afișajele braille ALVA BC680 nu mai eșuează să se inițializeze. (#8106)
* În mod implicit, afișajele ALVA BC6 nu vor mai executa taste simulate ale tastaturii sistemului la apăsarea combinațiilor de taste care implică sp2+sp3 pentru declanșarea funcționalității interne. (#8230)
* Apăsarea sp2 pe un afișaj ALVA BC6 pentru simularea tastei alt funcționează acum ca anunțată. (#8360)
* NVDA nu mai anunță modificări redundante ale aspectului tastaturii. (#7383, #8419)
* Urmărirea mausului este mult mai precisă în Notepad și în alte editoare de text într-un document care conține mai mult de 65535 de caractere. (#8397)
* NVDA recunoaște mai multe dialoguri din Windows 10 și din alte aplicații moderne. (#8405)
* În Windows 10 October 2018 Update, Server 2019 și mai noi, NVDA nu mai eșuează să urmărească focalizarea sistemului atunci când o aplicație se blochează sau bombardează sistemul cu evenimente. (#7345, #8535)
* Acum, utilizatorii sunt informați atunci când încearcă să citească sau să copieze o bară de stare goală. (#7789)
* S-a reparat o eroare care făcea ca atunci când o casetă era nebifată, statutul acesteia să nu fie raportat în vorbire dacă respectiva casetă fusese parțial bifată anterior. (#6946)
* În lista de limbi din dialogul setărilor NVDA, numele de limbă pentru birmană este afișat corect în Windows 7. (#8544)
* În microsoft Edge, NVDA va anunța notificări precum disponibilitatea pentru vizualizarea lecturilor și progresul încărcării unei pagini. (#8423)
* La navigarea într-o listă de pe un site web, NVDA va raporta eticheta acesteia dacă autorul site-ului respectiv a furnizat-o. (#7652)
* Când se atribuie manual funcții la gesturi pentru un afișaj braille particular, aceste gesturi le vor afișa întotdeauna ca fiind atribuite la acel afișaj. În trecut, funcțiile erau afișate ca și cum ar fi fost atribuite la afișajul braille care era activ în acel moment. (#8108)
* Versiunea pe 64 de biți a Media Player Classic este suportată acum. (#6066)
* Au fost activate câteva îmbunătățiri la suportul braille din Microsoft Word cu UI Automation:
 * Similar cu multe câmpuri de text multilinie, când este poziționat la începutul unui document în braille, afișajul este afișat astfel încât primul caracter al documentului să fie la începutul afișajului. (#8406)
 * La focalizarea unui document Word, s-a redus prezentarea extrem de prolixă a focalizării atât în vorbire, cât și în braille. (#8407)
 * Acum, deplasarea cursorului în braille funcționează corect atunci când se află într-o listă dintr-un document Word. (#7971)
 * Bulinele sau numerele nou-inserate într-un document Word sunt raportate corect atât în vorbire, cât și în braille. (#7970)
* În Windows 10 1803 sau mai nou, puteți să instalați suplimente dacă este activată caracteristica pentru suportul utilizării Unicode UTF-8 pentru limbile din lumea întreagă. (#8599)

### Modificări pentru Dezvoltatori

* S-a adăugat scriptHandler.script, care poate fi folosit pe post de decorator pentru scripturile de pe obiectele scriptabile. (#6266)
* a fost introdus un test de sistem framework pentru NVDA. (#708)
* Au fost efectuate niște modificări la modulul hwPortUtils: (#1271)
 * listUsbDevices oferă acum dicționare cu informații despre dispozitive, inclusiv hardwareID și devicePath.
 * Dicționarele oferite de listComPorts conțin și o intrare usbID pentru porturile COM cu informații despre USB VID/PID în ID-ul lor hardware.
* S-a actualizat wxPython la 4.0.3. (#7077)
* Actualmente, întrucât NVDA suportă doar Windows 7 SP1 și mai nou, tasta „minWindowsVersion”, folosită să verifice dacă UIA ar trebui să fie activat pentru o versiume particulară de Windows, a fost eliminată. (#8422)
* Acum, vă puteți înregistra pentru a fi notificat cu privire la salvările configurațiilor sau la acțiunile de resetare prin noile config.pre_configSave, config.post_configSave, config.pre_configReset și prin acțiunile config.post_configReset. (#7598)
 * config.pre_configSave este folosit pentru ca dumneavoastră să fiți notificat atunci când configurația NVDA este pe punctul de a fi salvată, urmând ca după aceea să se apeleze la config.post_configSave.
 * config.pre_configReset și config.post_configReset includ steagul setărilor din fabrică pentru a specifica dacă setările sunt reîncărcate de pe disk (false) sau dacă resetarea la valorile implicite este necesară (true).
* config.configProfileSwitch a fost redenumit la config.post_configProfileSwitch pentru a reflecta faptul că această acțiune este apelată după ce comutarea profilului are loc. (#7598)
* Interfețele UI Automation au fost actualizate la Windows 10 October 2018 Update și Server 2019 (IUIAutomation6 / IUIAutomationElement9). (#8473)

## 2018.2.1

Această versiune include actualizări ale traducerilor din cauza eliminării în ultimul moment a unei caracteristici care cauza probleme.

## 2018.2

Caracteristicile principale ale acestei versiuni includ suport pentru citirea și navigarea în tabelele din aplicația Kindle pentru PC, suport pentru afișajele braille de la HumanWare BrailleNote Touch și BI14, precum și rezolvările multor defecte la vocile Windows Onecore și Sapi5. În plus, s-au introdus câteva mici funcții noi în Microsoft Outlook etc.

### Noi Funcționalități

* Extinderea coloanelor și rândurilor din tabele este acum raportată atât vocal, cât și în braille atunci când celulele unui tabel sunt legate. (#2642)
* Comenzile de navigare prin tabel ale NVDA-ului sunt suportate acum în Google Docs ( cu modul braille activat). (#7946)
* Acum NVDA poate citi și naviga prin tabelele  din Kindle pentru PC. (#7977)
* A fost introdus suportul prin USB și Bluetooth pentru display-urile braille de la HumanWare BrailleNote Touch și Brailliant BI 14. (#6524)
* În Windows 10 Fall Creators Update și mai nou, NVDA poate anunța notificări de la aplicații precum Calculator și Windows Store. (#7984)
* Noi tabele de traducere braille: lituaniană 8 puncte, ucraineană, română, mongolă grad 2. (#7839)
* S-a adăugat un script pentru raportarea informațiilor de formatare pentru un text de sub o celulă braille specifică. (#7106)
* La actualizarea NVDA, puteți să amânați instalarea noii versiuni și s-o realizați mai târziu. (#4263)
* Repertuarul limbilor în care NVDA este tradus s-a mărit, fiind adăugate mongola și germana elvețiană. 
* Acum, puteți comuta la control, shift, alt, windows și NVDA de la tastatura dumneavoastră braille și le puteți combina cu intrarea braille (e.x. apăsați control+s). (#7306) 
 * puteți să le atribuiți utilizând comenzile găsite sub tastele tastaturii simulate din dialogul gesturilor de intrare.
* S-a restaurat suportul pentru afișajele braille Handy Tech Braillino și Modular (cu firmware vechi). (#8016)
* Acum, data și ora pentru dispozitivele Handy Tech suportate (cum ar fi Active Braille și Active Star) vor fi sincronizate automat de NVDA atunci când nu se sincronizează mai mult de cinci secunde. (#8016)
* Acum se poate crea un gest de intrare nou în dialogul "gesturi de intrare" pentru a putea dezactiva temporar toate declanșările profilurilor de configurare. (#4935)

### Modificări

* Coloana de stare din administratorul de suplimente a fost modificată astfel încât să indice dacă suplimentul este activat sau dezactivat, mai degrabă decât indicarea faptului că acesta rulează sau că-i suspendat. (#7929)
* S-a actualizat traducătorul braille liblouis la 3.5.0. (#7839)
* Tabelul braille lituanian a fost redenumit în lituaniană 6 puncte pentru a se evita confuzia cu noul tabel în 8 puncte. (#7839)
* Tabelele franceză (Canada) grad 1 și 2 au fost șterse. În schimb, se vor utiliza tabelele franceze (unificate) braille pentru calculator în 6 puncte, respectiv tabelele de gradul 2. (#7839)
* Butoannele secundare de deplasare de pe afișajele Alva BC6, EuroBraille și Papenmeier raportează acum informații de formatare pentru un text de sub o celulă braille de-a acelui buton. (#7106)
* Tabelele braille de intrare abreviate vor reveni automat la modul neabreviat în cazurile needitabile (e.x. controalele în care nu există niciun cursor sau în modul de navigare). (#7306)
* Acum, NVDA este mai puțin vorbăreț atunci când o întâlnire sau un interval de timp din calendarul Outlook acoperă o zi întreagă. (#7949)
* Toate setările NVDA pot fi găsite acum laolaltă într-un dialog de setări din meniul NVDA -> Preferințe -> Setări, ne mai fiind împrăștiate  în multe dialoguri. (#577)
* Dacă se rulează Windows 10, sintetizatorul implicit este vorbirea OneCore, nu Espeak. (#8176)

### Defecte rezolvate

* NVDA nu mai eșuează să citească controalele focalizate în ecranul de autentificare din setări al contului Microsoft  după introducerea unei adrese de e-mail. (#7997)
* NVDA nu mai eșuează să citească pagina atunci când se merge înapoi la o pagină anterioară din Microsoft Edge. (#7997)
* NVDA nu va mai anunța incorect caracterul final al unui pin de autentificare în Windows 10 în momentul în care calculatorul se deblochează. (#7908)
* Etichetele casetelor de bifat și ale butoanelor rotative din Chrome și Firefox nu mai sunt raportate de două ori la deplasarea cu tab sau la utilizarea navigării rapide din modul de navigare. (#7960)
* Acum se raportează aria-curent cu o valoare de fals ca fiind falsă în loc de o valoare de adevăr (#7892).
* Sintetizatorul vocilor Windows OneCore nu va mai eșua să se încarce dacă vocea setată a fost dezinstalată. (#7553)
* Schimbarea vocilor din sintetizatorul OneCore este mult mai rapidă acum. (#7999)
* S-a reparat ieșirea braille malformată pentru câteva tabele braille, incluzând majusculele din tabelul danez abreviat în 8 puncte. (#7526, #7693)
* Acum, NVDA poate să raporteze mai multe tipuri de buline în Microsoft Word. (#6778)
* Apăsarea pe scriptul de raportare a formatării nu mai deplasează incorect poziția de examinare, iar prin urmare, apăsarea lui în mod repetat nu mai dă rezultate diferite. (#7869)
* Intrarea braille nu vă va mai permite să folosiți braille-ul în cazurile în care nu mai este suportat (e.x. cuvintele întregi nu vor mai fi trimise către sistem în afara conținutului textului și în modul de navigare). (#7306)
* S-au rezolvat problemele de stabilitate a conexiunii pentru afișajele Handy Tech Easy Braille și Braille Wave. (#8016)
* Pe Windows 8 sau mai nou, NVDA nu va mai spune „necunoscut” la deschiderea meniului de legătură rapidă )Windows+X) și la selectarea elementelor din acest meniu. (#8137)
* Gesturile specifice modelului  cu butoanele de pe afișajele Hims lucrează acum ca anunțate în ghidul de utilizare. (#8096)
* Acum, NVDA va încerca să corecteze probleme de sistem ale înregistrării COM care fac ca programe precum Firefox și Internet Explorer să devină inaccesibile, iar el să raporteze „necunoscut”. (#2807)
* S-a introdus o soluție la o eroare din managerul de activități care face  ca NVDA să nu le permită utilizatorilor să acceseze conținuturile detaliilor specifice despre procese. (#8147)
* Vocile mai noi Microsoft SAPI5 nu mai au întârziere la sfârșitul vorbirii, acest lucru făcând navigarea cu ele mult mai eficientă. (#8174)
* NVDA nu mai anunță marcările (RTL și LTR) în braille sau când se citește literă cu literă în ceasul din versiunile mai noi de Windows. (#5729)
* Tastele de deplasare ale afișajelor Hims Smart Beetle sunt acum detectate din nou în mod corect. (#6086)
* Privind controale text în anumite aplicații precum aplicațiile Delphi, informațiile despre editare și navigare sunt redate mult mai stabil de către NVDA. (#8102)
* În Windows 10 RS5, NVDA nu mai raportează informații redundante suplimentare la comutarea între activități cu alt+tab. (#8258)

### Modificări pentru Dezvoltatori

* Informația dezvoltatorului pentru obiectele UIA conține acum o listă a modelelor UIA disponibile. (#5712)
* Modulele de aplicație pot acum să forțeze anumite ferestre să folosească mereu UIA implementând metoda isGoodUIAWindow. (#7961)
* Steagul ascuns "outputPass1Only" din secțiunea braille a configurării a fost șters din nou. Liblouis nu mai suportă ieșirea Pass 1 Only. (#7839)

## 2018.1.1

Ei bine, aceasta este o versiune specială de NVDA carre a fost făcută pentru a reflecta repararea unui defect  care ar fi putut să fie în viitoarea versiune de Windows 10, Spring Creators update, alias Windows 10 Redstone 4 sau Windows 10 (versiunea 1803), dacă Microsoft nu l-ar fi reparat într-o versiune de Windows Insider. Acesta făcea ca vocile să vorbească cu un ton mai înalt și cu o viteză mult mai mare decât ar fi trebuit. (#8082)  

## 2018.1

Caracteristicile principale ale acestei versiuni includ suport pentru diagramele din Microsoft Word și Microsoft PowerPoint, suport pentru noi afișaje braille, incluzând Eurobraille și convertorul de protocol Optelec, suport îmbunătățit pentru afișajele braille Hims și Optelec, îmbunătățiri de performanță pentru Mozilla Firefox 58 sau mai nou și multe altele.

### Noi funcționalități

* Acum, este posibilă interacțiunea cu diagramele din Microsoft Word și Microsoft  PowerPoint, similară cu suportul existent pentru diagramele din Microsoft Excel. (#7046)
 * În modul de navigare din Microsoft Word, deplasați cursorul la o diagramă încorporată și apăsați enter pentru a interacționa cu ea.
 * La editarea unui diapozitiv din Microsoft PowerPoint: duceți-vă  cu tasta tab la un obiect diagramă, apoi apăsați enter sau spațiu pentru a interacționa cu diagrama.
 * Pentru a opri interacțiunea cu o diagramă, apăsați escape.
* Limbă nouă: Kirghiză.
* S-a adăugat suportul pentru VitalSource Bookshelf. (#7155)
* S-a adăugat suportul pentru convertorul de protocol Optelec, un dispozitiv care permite utilizarea afișajelor Braille Voiager și Satelite utilizând protocolul de comunicare ALVA BC6. (#6731)
* Acum, este posibilă folosirea intrării braille cu un afișaj braille ALVA 640 Comfort. (#7733)
 * Funcționalitatea de intrare braille a NVDA-ului poate fi utilizată cu acestea, precum și cu alte afișaje BC6 cu firmware 3.0.0 și mai nou.
* Suport inițial pentru Google Sheets cu modul braille activat. (#7935)
* Suport pentru afișajele Eurobraille Esys, Esytime și Iris. (#7488)

### Modificări

* Driverele afișajelor braille HIMS Braille Sense/Braille EDGE/Smart Beetle și Hims Sync Braille au fost înlocuite de un driver nou. Noul driver va fi activat automat pentru foștii utilizatori ai driver-ului syncBraille. (#7459)
 * Niște taste, mai exact cele de deplasare, au fost reatribuite pentru a urmări convențiile folosite de produsele Hims. Consultați ghidul utilizatorului pentru mai multe detalii.
* La scrierea cu tastatura de pe ecran prin interacțiunea tactilă, în mod implicit, trebuie să atingeți dublu fiecare tastă, în același mod în care ați activa un oricare alt control.
 * Pentru a folosi existenta „scriere tactilă”, pur și simplu ridicându-vă degetele de pe tastă, este suficient s-o activați. Pentru a face asta, activați această opțiune din noul dialog de setări al interacțiunii tactile din meniul Preferințe. (#7309)
* Nu mai este necesar să asociați explicit Braille-ul la  focalizare sau la examinare, întrucât asta se întâmplă automat în mod implicit. (#2385)
 * Rețineți faptul că asocierea automată la examinare va apărea numai la utilizarea unui cursor de examinare sau a unei comenzi de navigare prin obiect. Derularea nu va activa acest nou comportament.

### Defecte rezolvate

* Mesajele care pot fi redirecționate, cum ar fi afișarea formatării curente la apăsarea NVDA+f de două ori rapid, nu mai eșuează atunci când NVDA este instalat într-o cale cu caractere non-asci. (#7474)
* Focalizarea este din nou restaurată corect la întoarcerea la Spotify din altă aplicație. (#7689)
* NVDA nu mai eșuază să se actualizeze pe sisteme pe care e activată caracteristica de acces a dosarului controlat (disponibilă în Windows 10 Fall Creaters update). (#7696)
* Detectarea tastelor de deplasare pe afișajele Hims Smart Beetle nu mai este fiabilă. (#6086)
* O ușoară îmbunătățire a performanței la afișarea cantităților mari de conținut în Mozilla Firefox 58 și mai nou. (#7719)
* Se previn erori în timpul citirii mesajelor de poștă electronică din Microsoft Outlook. (#6827)
* Gesturile afișajelor braille care simulează modificatoare de taste ale tastaturii sistemului pot, de asemenea, să fie combinate cu alte modificatoare de taste ale tastaturii sistemului dacă unul sau mai multe dintre gesturile implicate sunt specifice modelului. (#7783)
* În Mozilla Firefox, modul de navigare funcționează corect în pop-up-urile create de extensii precum LastPass și bitwarden. (#7809)
* NVDA nu se mai blochează uneori la fiecare schimbare a focalizării în cazul în care Firefox sau Chrome au încetat să răspundă, de exemplu, din cauza unei blocări sau a unui crash. (#7818)
* În clienții de Twitter precum Chicken Nugget, NVDA nu mai ignoră ultimele 20 din 280 de caractere ale postărilor la citirea lor. (#7828)
* Acum, NVDA utilizează limba corectă la anunțarea simbolurilor atunci când textul este selectat. (#7687)
* În versiunile recente ale Office 365, este posibilă din nou navigarea prin diagramele Excel folosind săgețile. (#7046)
* În ieșirile de vorbire și braille, stările controalelor nu vor fi întotdeauna raportate în aceeași ordine, indiferent dacă sunt pozitive sau negative. (#7076)
* În aplicații precum Windows 10 Mail, NVDA nu va mai eșua să anunțe caracterele șterse la apăsarea tastei backspace. (#7456)
* Toate tastele de pe afișajele Hims Braille Sense Polaris funcționează așa cum era de așteptat. (#7865)
* NVDA nu mai eșuează să pornească în Windows 7, cu mesajul despre un dll intern pentru api-ms, atunci când a fost instalată o anumită versiune a lui VIsual Studio 2007 de către o altă aplicație. (#7975)

### Modificări pentru Dezvoltatori

* s-a adăugat un steag boolean ascuns la secțiunea braille din configurație: "outputPass1Only". (#7301, #7693, #7702)
 * Acest steag tinde să se îndrepte spre adevăr. Dacă e fals, regulile liblouis multi pass vor fi utilizate la ieșirea braille.
* A fost adăugat unn nou dicționar numit braille.RENAMED_DRIVERS pentru a permite o tranziție lină utilizatorilor ce folosesc drivere care au fost înlocuite de altele. (#7459)
* S-a actualizat pachetul comtypes la 1.1.3. (#7831)
* S-a implementat un sistem generic braille.BrailleDisplayDriver pentru a face față afișajelor care trimit pachete de confirmare. Luați ca exemplu driver-ul afișajului braille HandyTech. (#7590, #7721)
* În modulul config, o nouă variabilă „isAppX” poate fi utilizată pentru a detecta dacă NVDA rulează ca o aplicație Windows Desktop Bridge Store. (#7851)
* Pentru implementările documentelor precum NVDAObjects sau browseMode care au un textInfo, acum există o clasă documentBase.documentWithTableNavigation care poate fi folosită pentru a obține scripturi standard pentru navigarea prin tabel. Vă rugăm să faceți referire la această clasă pentru a vedea care dintre metodele ajutătoare trebuie să fie furnizate de implementarea dumneavoastră pentru ca navigarea prin tabel să funcționeze. (#7849)
* Fișierul scons batch este mai compatibil acum cu Python 3, făcând utilizarea lansatorului pentru lansarea exactă a python 2.7 pe 32 de biți. (#7541)
* hwIo.Hid ia un parametru adițional exclusiv care este implicit pe True. Dacă este setat pe False, le este permis altor aplicații să comunice cu un dispozitiv, atâta timp cât este conectat la NVDA. (#7859)

## 2017.4

Caracteristicile principale ale acestei versiuni includ multe reparări și îmbunătățiri la suportul pentru web, incluzând modul de navigare pentru dialogurile web în mod implicit, raportare mai bună a etichetelor grupurilor de câmpuri din modul de navigare, suport pentru noile tehnologii Windows 10, precum Windows Defender Application Guard și Windows 10 pe ARM64, dar și raportarea automată a orientării ecranului și a stării bateriei.  
Vă rugăm să rețineți faptul că această versiune nu mai suportă Windows XP sau Windows Vista. Cerința minimă pentru NVDA este acum Windows 7 cu Service Pack 1.

### Noi Funcționalități

* În modul de navigare este acum posibil să treceți peste / până la începutul reperelor, utilizând comenzile pentru a trece la sfârșitul / începutul containerelor. (virgulă/shift+virgulă). (#5482)
* În Firefox, în Chrome și în Internet Explorer, navigarea rapidă la câmpurile de editare și la câmpurile formular include acum conținut de text îmbogățit (e.x. contentEditable). (#5534)
* În navigatoarele web, lista elementelor poate lista acum câmpuri formular și butoane. (#588)
* Suport inițial pentru Windows 10 pe ARM64. (#7508)
* Suport inițial pentru citirea și navigarea interactivă a conținutului matematic pentru cărțile Kindle cu matematica accesibilă. (#7536)
* Suport adăugat pentru cititorul de cărți electronice Azardi. (#5848)
* Acum, este raportată informația versiunii suplimentelor când se face o actualizare. (#5324)
* S-au adăugat  parametri noi ai liniei de comandă pentru a crea o copie portabilă a NVDA-ului. (#6329)
* Suport pentru Microsoft Edge care rulează în Windows Defender Application Guard. (#7600)
* Dacă rulează pe un leptop sau pe o tabletă, NVDA va anunța atunci când un încărcător este conectat sau deconectat și atunci când orientarea ecranului se modifică. (#4574, #4612)
* Limbă nouă: macedoneană.
* Noi tabele braille de traducere: croată grad 1, vietnameză grad 1. (#7518, #7565)
* A fost adăugat Suportul pentru afișajul  braille Actilino d la Handy Tech. (#7590)
-  intrarea braille pentru afișajele Handy Tech este acum suportată. (#7590)

### Modificări

* Sistemul minim de operare acceptat de NVDA este acum Windows 7 cu Service Pack 1 sau Windows Server 2008 R2 cu Service Pack 1. (#7546)
* Dialogurile web din Firefox și Chrome folosesc automat modul de navigare dacă nu se află în cadrul unei aplicații web. (#4493)
* În modul de navigare, tabularea și deplasarea cu comenzile de navigare rapidă nu mai anunță „salt în afara containerelor”, cum ar fi liste și tabele, ceea ce face navigarea mai eficientă. (#2591)
* În modul de navigare pentru Firefox și Chrome, numele grupurilor de câmpuri formular sunt anunțate atunci când se deplasează la ele cu navigarea rapidă sau când se tabulează. (#3321)
* În modul de navigare, comanda navigării rapide pentru obiectele încorporate )O și shift+o) include acum elementele audio și video, precum și elementele cu aplicația și dialogul rolurilor aria. (#7239)
* A fost actualizat Espeak NG la versiunea 1.49.2, rezolvând niște probleme cu producerea lansărilor de compilări. (#7385)
* La a treia activare a comenzii de citire a barei de stare, conținutul va fi copiat pe planșetă. (#1785)
* Când se atribuie gesturi la taste pentru un afișaj Baum, le puteți limita la modelul afișajului braille în uz (e.x. VarioUltra sau Pronto). (#7517)
* Comanda pentru câmpul de filtrare din lista de elemente a modului de navigare a fost schimbată din alt+f în alt+e. (#7569)
* A fost adăugată o comandă nelegată pentru modul de navigare pentru comutarea la includerea tabelelor de aspect. O puteți găsi în categoria modului de navigare a dialogului gesturilor de intrare. (#7634)
* S-a actualizat traducătorul braille liblouis la 3.3.0. (#7565)
* Comanda pentru butonul rotativ „expresie regulată” din dialogul dicționarului a fost schimbată din alt+r în alt+e. (#6782)
* Fișierele dicționarului vocal sunt acum versionate și au fost mutate în dosarul 'speechDicts/voiceDicts.v1'. (#7592)
* Fișierele versionate (configurația utilizatorului, dicționarele vocale) modificările nu mai sunt salvate atunci când NVDA este executat din lansator. (#7688)
* Afișajele braille Braillino, Bookworm și Modular (cu vechiul firmware) de la Handy Tech nu mai sunt suportate. Instalați driver-ul universal Handy Tech și suplimentul NVDA pentru el pentru a utiliza aceste afișaje. (#7590)

### Defecte rezolvate

* Link-urile sunt indicate acum în braille în aplicații precum Microsoft Word. (#6780)
* NVDA nu mai este considerat mai lent atunci când multe file sunt deschise în browserele web Firefox sau Chrome. (#3138)
* Rotirea cursorului pentru afișajul MDV Lilli Braille nu mai deplasează incorect o celulă braille înainte de unde ar trebui să fie. (#7469)
* În Internet Explorer și în alte documente MSHTML, atributul HTML5 necesar este suportat acum pentru a indica starea necesară a unui câmp formular. (#7321)
* Afișajele braille sunt acum actualizate la tastarea de caractere arabe într-un document WordPad aliniat la stânga. (#511).
* Etichetele accesibile pentru comenzile din Mozilla Firefox sunt raportate acum mult mai ușor în modul de navigare atunci când eticheta nu apare drept conținut în sine. (#4773)
* În windows 10 Creaters Update, NVDA poate accesa din nou Firefox-ul după o repornire a lui. (#7269)
* La repornirea NVDA-ului cu focalizarea pe Mozilla Firefox, modul de navigare va fi din nou disponibil, deși e posibil să fiți nevoit să vă duceți cu alt+tab pe o altă fereastră și să reveniți din nou după aceea. (#5758)
* Acum este posibilă accesarea conținutului matematic din Google Chrome pe un sistem fără ca Mozilla Firefox să fie instalat. (#7308)
* Ar trebui ca sistemele de operare și alte aplicații să fie mult mai stabile în mod direct imediat după instalarea NVDA-ului înainte de repornire, după cum au fost comparate cu instalările versiunilor anterioare ale NVDA-ului. (#7563)
* În traducerea românească, a fost reparată o eroare care făcea ca instalarea NVDA-ului să eșueze. (#6326)
* La folosirea unei comenzi a conținutului de recunoaștere (e.x. NVDA+r), NVDA raportează acum un mesaj de eroare în loc de nimic dacă obiectul navigator a dispărut. (#7567)
* Funcționalitatea de derulare înapoi a fost reparată pentru afișajele Braille Freedom Scientific care conțin o bară de protecție la stânga. (#7713)

### Modificări pentru dezvoltatori

* acum, "scons tests" verifică dacă string-urile ce pot fi traduse au comentariile traducătorului. Puteți rula asta singur cu "scons checkPot". (#7492)
* Acum există un nou modul de extensie care oferă un framework generic pentru a activa extensibilitatea codului la punctele specifice din el. Acest lucru permite părților interesate să se înregistreze pentru a fi notificate atunci când are loc o acțiune (extensionPoints.Action), să modifice un anumit tip de date (extensionPoints.Filter) sau să participe la luarea unei decizii atunci când se va face ceva (extensionPoints.Decider). (#3393)
* Acum vă puteți înregistra pentru a fi notificat atunci când configurarea profilului se comută prin acțiunea config.configProfileSwitched. (#3393)
* Gesturile afișajului braille care simulează modificatoare de taste ale tastaturii sistemului (cum ar fi control și alt) pot fi combinate acum cu alte taste ale tastaturii simulate fără definiție explicită. (#6213) 
 * De exemplu: dacă aveți o tastă pe afișaj legată la tasta alt și o altă tastă de afișaj pentru a putea apăsa săgeată jos, combinarea acestor taste va rezulta simularea alt+săgeată jos.
* Clasa braille.BrailleDisplayGesture are acum o proprietate extra model. Dacă e furnizată, apăsarea unei taste va genera un identificator de gest suplimentar, specific pentru model. Aceasta îi permite unui utilizator să lege gesturile limitate la un model specific de afișaje braille. 
 * Încercați driver-ul Baum ca exemplu pentru această nouă funcționalitate.
* NVDA este compilat acum cu Visual Studio 2017 și Windows 10 SDK. (#7568)

## 2017.3

Caracteristicile principale ale acestei lansări includ intrările pentru braille abreviat, compatibilitate pentru noile voci Windows OneCore disponibile în Windows 10, integrare în aplicație a Windows 10 OCR și multe alte îmbunătățiri semnificative pentru braille și internet.

## Noi Funcționalități

* A fost adăugată o setare braille la opțiunea „arată mesajele pe termen nelimitat”. (#6669)
* În lista de mesaje din Microsoft Outlook, se raportează dacă un mesaj este semnalat. (#6374)
* În Microsoft Powerpoint, tipul exact al unei forme este raportat la editarea unui diapozitiv (exemplele includ: triunghi, cerc, video, săgeată), mai degrabă decât 'forma'. (#7111)
* Conținutul matematic )furnizat ca MathML) este acum suportat în Google Chrome. (#7184)
* NVDA poate vorbi utilizând noile voci Windows OneCore )cunoscute și ca voci mobile) incluse în Windows 10. Accesați-le selectând opțiunea „voci Windows OneCore” din dialogul de sintetizator al NVDA-ului. (#6159)
* Fișierele de configurare ale utilizatorului NVDA pot fi stocate în dosarul local de date al aplicației utilizatorului. Aceasta este activată printr-o setare din regiștri. Consultați 'Parametrii la nivel de sistem' din ghidul utilizatorului pentru mai multe detalii. (#6812)
* În navigatoarele web, NVDA-ul raportează valori de substituent pentru câmpuri (mai exact, acum este suportat aria-placeholder). (#7004)
* În modul de navigare pentru Microsoft Word, aveți acum posibilitatea de a naviga la erorile de ortografie utilizând navigarea rapidă (w și shift+w) (#6942)
* Suport adăugat pentru comanda de selectare a datei găsită în dialogurile de întâlnire ale Microsoft Outlook. (#7217)
* Sugestia selectată în prezent este acum raportată în câmpurile către și cc din Windows 10 Mail și în câmpul de căutare din setările Windows 10. (#6241)
* Un sunet este redat pentru a indica aspectul sugestiilor în anumite câmpuri de căutare din Windows 10, ca de exemplu ecranul de pornire, căutarea de setări, câmpurile către și cc din aplicația Windows 10 Mail. (#6241)
* În Skype pentru Afaceri Desktop notificările sunt raportate automat, cum ar fi atunci când cineva începe o conversație cu dumneavoastră. (#7281)
* Raportează automat mesajele de intrare într-o conversație din Skype pentru Afaceri. (#7286)
* În Microsoft Edge notificările sunt raportate automat, cum ar fi atunci când o descărcare începe. (#7281)
* Puteți scrie atât în braille-ul abreviat cât și în cel neabreviat pe un afișaj braille cu o tastatură braille. Vedeți secțiunea intrării braille a manualului de utilizare pentru detalii. (#2439)
* Puteți introduce caractere braille unicode de la tastatura braille pe un afișaj braille selectând Braille unicode ca tabel de intrare din setările braille. (#6449)
* Suport adăugat pentru afișajul SuperBraille folosit în Taiwan. (#7352)
Noi tabele de traducere braille: daneză - braille în 8 puncte pentru calculator, lituaniană, persană - braille în 8 puncte pentru calculator, persană grad 1, slovenă - braille în 8 puncte pentru calculator. (#6188, #6550, #6773, #7367)
* S-a îmbunătățit engleza (U.S.) - braille în 8 puncte pentru calculator, incluzând suport pentru simboluri bulină (liste), euro și litere cu accent. (#6836)
* NVDA poate acum folosi funcționalitatea OCR, inclusă în Windows 10, pentru a recunoaște text din imagini sau aplicații inaccesibile. (#7361)
 * Limba poate fi configurată din noua fereastră de dialog pentru opțiunile Windows 10 OCR din „Preferințele” NVDA
 * Pentru a recunoaște conținutul obiectului navigator curent, apăsați NVDA+r.
 * Vedeți secțiunea despre recunoașterea de conținut din manualul de utilizare al NVDA pentru mai multe detalii.
* Acum puteți selecta ce informație de context este prezentată pe afișajul dumneavoastră braille, atunci când un obiect este focalizat, folosind noua opțiune „Focalizarea informație de context” din fereastra de configurare a opțiunilor braille. (#217)
 * De exemplu, opțiunile „Umple afișajul cu schimbări ale contextului” și „Doar la derularea înapoi” pot face lucrul cu liste și meniuri mai eficient, din moment ce elementele nu-și vor schimba continuu poziția pe afișaj.
 * Vedeți secțiunea despre „Focalizarea contextului prezentării” din manualul utilizatorului, pentru mai multe detalii și exemple.
* În Firefox și Chrome, NVDA acum este compatibil cu griduri dinamice și complexe cum ar fi foi de calcul unde doar o parte a conținutului ar putea fi încărcat sau afișat (mai precis, atributele introduse în ARIA 1.1 aria-rowcount, aria-colcount, aria-rowindex and aria-colindex). (#7410)

### Modificări

* A fost adăugată o comandă neasciată pentru a reporni NVDA-ul la cerere. O puteți găsi în categoria „diverse” din dialogul pentru „Gesturi de intrare”. (#6396)
* Aspectul tastaturii poate fi setat din dialogul de întâmpinare al NVDA-ului. (#6863)
* Au fost create abrevieri pentru braille mult mai multor tipuri de controale și stări. Inclusiv reperele au fost abreviate. Vedeți secțiunea „Abrevieri pentru tipuri de controale, stări și repere” pentru braille din manualul de utilizare pentru lista completă. (#7188, #3975)
* S-a actualizat Espeak NG la versiunea 1.49.1 (#7280).
* Listele tabelelor braille de intrare și de ieșire din dialogul de setări braille sunt sortate alfabetic. (#6113)
* S-a actualizat traducătorul braille liblouis la versiunea 3.2.0. (#6935)
* Tabelul braille implicit este acum Engleza unificată cod braille grad 1. (#6952)
* Acum NVDA prezintă în mod implicit doar părțile care s-au modificat din informația de context a unui obiect focalizat, pentru afișajele braille. (#217)
 * Anterior era prezentată întotdeauna cât mai multă informație de context, indiferent dacă ați văzut această informație anterior.
 * Puteți reveni la vechiul comportament, schimbând noua opțiune pentru „Focalizarea contextului prezentării” din opțiunile braille în „Umple întotdeauna afișajul”.
* Când folosiți braille, cursorul poate fi configurat să aibe o altă formă când este asociat la focalizare sau examinare. (#7112)
* Logo-ul NVDA a fost actualizat. Noul logo este o combinație stilizată a literelor NVDA în alb, pe un fond violet. Această modificare asigură faptul că logo-ul va fi vizibil pe orice tip de culoare a fundalului și folosește violetul din logo-ul NV Access. (#7446)

### Defecte rezolvate

* Elementele editabile div din Chrome nu mai au eticheta raportată ca valoare în timp ce se află în modul de navigare. (#7153)
* Apăsarea tastei end în timp ce vă aflați în modul de navigare a unui document Word gol nu mai cauzează o eroare runtime. (#7009)
* Modul de navigare este suportat corect în Microsoft Edge unde un document a primit un rol specific Aria de document. (#6998)
* În modul de navigare, puteți selecta sau deselecta la sfârșitul rândului utilizând shift+end, chiar și atunci când cursorul de scriere este pe ultimul caracter al rândului. (#7157)
* Dacă un dialog conține o bară de progres, textul dialogului este actualizat când bara de progres suferă modificări. Asta înseamnă, de exemplu, că timpul rămas poate fi citit în dialogul din NVDA de descărcare a actualizărilor. (#6862)
* NVDA va anunța schimbări de selecție pentru anumite casete combinate Windows 10, cum ar fi autoredarea din Setări. (#6337).
* Informațiile inutile nu mai sunt anunțate la introducerea dialogurilor de creare a întâlnirilor din Microsoft Outlook. (#7216)
* Bipurile pentru dialogurile nedeterminate ale barei de progres, cum ar fi verificatorul de actualizare, numai atunci când ieșirea barei de progres este configurată să includă bipuri. (#6759)
* În Microsoft Excel 2007 și 2003, celulele sunt din nou raportate la navigarea în foile de lucru. (#7243)
* În Windows 10 Creators update și mai nou, modul de navigare este din nou activat automat atunci când citiți scrisori electronice în Windows 10 Mail. (#7289)
* Pe majoritatea afișajelor braille cu o tastatură braille, punctul 7 șterge ultima celulă braille sau ultimul caracter introdus, iar punctul opt apasă tasta enter. (#6054)
* La deplasarea cursorului de scriere în textul editabil (de exemplu cu tastele de cursor sau cu backspace), feedback-ul vorbit al NVDA-ului este mai precis în multe cazuri, particular în Chrome și în aplicațiile terminale. (#6424)
* Conținutul editorului semnăturii din Microsoft Outlook 2016 poate fi citit. (#7253)
* În aplicațile Java Swing, NVDA nu mai face ca uneori aplicația să dea eroare la navigarea prin tabele. (#6992)
* În Windows 10 Creators Update, NVDA nu va mai anunța notificările toast în mod repetat. (#7128)
* În meniul start din Windows 10, apăsarea tastei enter pentru închiderea meniului start după o căutare nu mai face ca NVDA-ul să anunțe textul căutării. (#7370)
* Efectuarea navigării rapide la rubricile din Microsoft Edge este acum mult mai rapidă. (#7343)
* În Microsoft Edge, navigarea din modul de navigare nu mai sare părți mari ale anumitor pagini web, cum ar fi tema Wordpress 2015. (#7143)
* În Microsoft Edge, reperele sunt localizate corect și în alte limbi decât în limba engleză. (#7328)
* Acum, braille urmărește corect la selecția de text dincolo de lățimea afișajului. De exemplu, dacă selectați linii multiple cu shift+săgeatăJos, braille afișează, mai nou, ultima linie pe care ați selectat-o. (#5770)
* În Firefox, NVDA nu mai raportează în mod fals „secțiune” de multiple ori, atunci când deschideți detaliile unui tweet pe twitter.com. (#5741)
* Comenzile de navigare în tabele nu mai sunt disponibile pentru tabele de aspect în mod navigare, decât dacă raportarea tabelelor de aspect este activată. (#7382)
* În Firefox și Chrome, comenzile de navigare în tabele din modul navigare acum sar peste celule de tabel ascunse. (#6652, #5655)

## Modificări pentru Dezvoltatori

* Timestamp-urile includ în log milisecundele. (#7163)
* NVDA trebuie să fie construit cu Visual Studio Community 2015. Visual Studio Express nu mai este suportat. (#7110)
 * Instrumentele Windows 10 și SDK-ul sunt de asemenea necesare și pot fi activate la instalarea Visual Studio.
 * Consultați secțiunea Dependențe instalate din documentație pentru detalii suplimentare.
* Suport pentru recunoașterea de conținut cum ar fi OCR și unelte pentru descrierea imaginilor, poate fi dezvoltat cu ușurință, folosind noul pachet contentRecog. (#7361)
* Pachetul json din Python este acum inclus în build-urile executabile ale NVDA. (#3050) 

## 2017.2

Caracteristicile principale ale acestei lansări includ suport complet pentru atenuarea audio în Windows 10 Creators Update; reparări ale mai multor erori de selecție în modul de navigare, incluzând probleme cu selectarea întregului conținut; îmbunătățiri semnificative la suportul pentru Microsoft Edge; și îmbunătățiri pe web, cum ar fi indicarea elementelor marcate ca actuale (folosind atributul aria-current).

### Noi Funcționalități

* Informația marginii celulei poate fi acum raportată în Microsoft Excel prin utilizarea `NVDA+f`. (#3044)
* În navigatoarele web, NVDA indică un element care a fost marcat ca actual folosind atributul aria-current. (#6358)
* Comutarea automată a limbii este suportată în Microsoft Edge. (#6852)
* Calculatorul Windows este suportat pe Windows 10 Enterprise LTSB (Long-Term Servicing Branch) și Server. (#6914)
* Efectuarea comenzii de citire a liniei curente de trei ori rapid citește linia cu descrieri de caractere. (#6893)
* Limbă nouă: birmană.
* Săgețile sus și jos unicode și simbolurile de fracție sunt acum rostite corespunzător. (#3805)

### Modificări

* Atunci când se navighează cu examinarea simplă în aplicații utilizând UI Automation, mai multe containere goale sunt ignorate făcând navigarea mai ușoară. (#6948, #6950) 

### Defecte rezolvate

* Elementele din meniul paginii web ) elementul de meniu și butoanele rotative din casetele de bifat) pot fi acum activate în timp ce vă aflați în modul de navigare. (#6735)
* Raportarea numelui foii Excel este acum tradusă. (#6848)
* Apăsarea tastei escape în timp ce comanda configurării profilului „Confirmă Ștergerea” este activă respinge fereastra de dialog. (#6851)
* S-au reparat unele erori în Mozilla Firefox și în alte aplicații Gecko unde caracteristica multi-proces este activată. (#6885)
* Raportarea culorii de fundal în examinarea ecranului este acum mai precisă atunci când textul a fost desenat cu un fundal transparent. (#6467)
* Suport îmbunătățit pentru describedby-aria în Internet Explorer 11, incluzând suport în iframe-uri și atunci când ID-uri multiple sunt furnizate. (#5784)
* În Windows Creaters Update, atenuarea audio a NVDA-ului funcționează ca în versiunile anterioare de Windows (I.e. Atenuează cu vorbire și sunete, atenuează totdeauna și fără atenuare sunt disponibile. (#6933)
* NVDA nu va mai eșua să navigheze sau să raporteze comenzi (UIA) unde o scurtătură nu este definită. (#6779)
* Două spații goale nu mai sunt adăugate în informația scurtăturii pentru anumite comenzi (UIA). (#6790)
* Anumite combinații ale afișajelor HIMS (e.g. spațiu+punct4) nu mai eșuează intermitent. (#3157)
* S-a rezolvat o problemă la deschiderea  unui port serial pe sistemele utilizatoare de anumite limbi, altele decât engleza, care au cauzat eșuarea în unele cazuri a conectării la afișajele braille. (#6845)
* S-a redus șansa de corupere a fișierului de configurare când Windows-ul  se închide. Fișierele de configurare sunt acum scrise într-o filă temporară înainte de înlocuirea fișierului actual de configurare. (#3165)
* La efectuarea comenzii de citire a liniei curente de două ori rapid pentru citirea liniei, limba apropiată este acum utilizată pentru caracterele citite. (#6726)
* Navigarea prin linie în Microsoft Edge este acum de până la trei ori mai rapidă în Windows 10 Creaters Update. (#6994)
* NVDA nu mai anunță „Web Runtime grouping” la focalizarea documentelor din Microsoft Edge în Windows 10 Creaters Update (#6948)
* Toate versiunile existente ale SecureCRT-ului sunt acum suportate. (#6302)
* Adobe Acrobat Reader nu se mai blochează în anumite documente PDF (în special cele care au goale atributele ActualText). (#7021, #7034)
* În modul de navigare în Microsoft Edge, tabelele interactive (grilele Aria) nu mai sunt omise când se navighează la tabele cu t și shift+t. (#6977)
* În modul de navigare, apăsarea shift+home după ce s-a selectat înainte,  selectează acum la începutul rândului așa cum era de așteptat. (#5746)
* În modul de navigare, selectarea întregului conținut (control+a) nu mai eșuează să selecteze tot textul dacă cursorul de scriere nu este la începutul textului. (#6909)
* S-au rezolvat niște probleme rare de selectare în modul de navigare. (#7131)

### Modificări pentru Dezvoltatori

* Argumentele Commandline sunt procesate acum cu modulul argparser al Python-ului, mai degrabă decât optparser-ul. Aceasta permite anumite opțiuni cum ar fi -r și -q pentru a fi manipulate în mod exclusiv. (#6865)
* core.callLater pune callback-ul la  coada principală a NVDA-ului după întârzierea dată, mai degrabă decât trezirea nucleului și executarea lui în mod direct. Aceasta oprește posibilele blocări datorită nucleului care intră în repaus accidental după procesarea unui callback în mijlocul unui apel de model cum ar fi afișarea unei casete de mesaj. (#6797) 
* Proprietatea InputGesture.identifiers a fost modificată, astfel încât aceasta nu mai este normalizată. (#6945)
* Subclasele nu mai sunt nevoite să normalizeze identificatoarele înainte de revenirea la ele de la această proprietate.
* Dacă vreți identificatoare normalizate, există acum o proprietate numită InputGesture.normalizedIdentifiers care normalizează identificatoarele returnate de proprietatea lor.
* Proprietatea InputGesture.logIdentifier este acum depreciată. Apelanții ar trebui să utilizeze InputGesture.identifiers[0] în locul ei. (#6945)
* Codul depreciat a fost eliminat:
 * În schimb, constantele `speech.REASON_*` și `controlTypes.REASON_*` ar trebui să fie folosite. (#6846)
 * În schimb, setarea pentru sintetizator `i18nName`, `displayName` și `displayNameWithAccelerator` ar trebui să fie folosite. (#6846)
 * `config.validateConfig`. (#6846, #667)
 * `config.save`: Ar trebui să fie folosit în schimb `config.conf.save`. (#6846)
* Lista de completări în meniul context de autocompletare a consolei Python nu mai prezintă nicio cale care să ducă până la  obiectele simbolului final pentru a fi completată. (#7023)
* Există acum un cadru de unitate de testare pentru NVDA. (#7026)
* Testele de unitate și infrastructura sunt localizate în dosarul tests/unit. Vedeți docstring-ul în fișierul tests\unit\init.py pentru detalii.
 * Puteți rula testele folosind „scons tests”. Vedeți secțiunea „Running Tests” din readme.md pentru detalii.
 * Dacă trimiteți un pull request pentru NVDA, ar trebui să rulați mai întâi testele și să vă asigurați că ele trec.

## 2017.1

Caracteristicile principale ale acestei lansări includ raportarea secțiunilor și a coloanelor de text în Microsoft Word; suport în citirea, navigarea și adnotarea cărților în Kindle for PC; și suport îmbunătățit pentru Microsoft Edge.

### Noi Funcționalități

* În Microsoft Word tipul de spațiere între secțiuni și nmărul secțiunilor poate fi anunțat. Aceasta este activată cu opțiunea „anunță numărul de pagini” în fereastra de dialog a formatării documentului. (#5946)
* În Microsoft Word coloanele de text pot fi acum anunțate. Aceasta este activată cu opțiunea „anunță numărul de pagini” în fereastra de dialog a formatării documentului. (#5946)
* Comutarea automată a limbii este acum suportată în Wordpad. (#6555)
* Comanda de găsire a NVDA-ului (NVDA+control+f) este acum suportată în modul de navigare pentru Microsoft Edge. (#6580)
* Navigarea rapidă pentru butoane în modul de navigare (b și shift+b) este acum suportată în Microsoft Edge. (#6577)
* Când se copiază o foaie în Microsoft Excel, coloana și antetele rândurilor setate sunt memorate. (#6628)
* Suport pentru citirea și navigarea în Kindle For PC, versiunea 1.19, incluzând acces la linkuri, note de subsol, grafice, text evidențiat și note pentru utilizatori. Vă rugăm să verificați secțiunea Kindle for PC în documentația NVDA-ului pentru mai multe informații. (#6247, #6638)
* Modul de navigare al navigării tabelului este acum suportat în Microsoft Edge. (#6594)
* În Microsoft Excel,localizarea comenzii  raportării examinării cursorului (desktop: NVDA+numpadDelete, laptop: NVDA+delete) raportează numele foii de lucru și locația celulei. (#6613)
* S-a adăugat o opțiune la dialogul ieșire pentru repornirea cu nivelul diagnosticării. (#6689)

### Modificări

* Frecvența minimă a intermitenței cursorului braille este acum 200 ms. Dacă aceasta era înainte setată la o valoare mai mică, ea va fi mărită cu 200 ms. (#6470)
* A fost adăugată o casetă de bifat în dialogul setărilor braille pentru a permite activarea/dezactivarea intermitenței cursorului braille. Înainte, o valoare de zero a fost utilizată pentru a realiza acest lucru. (#6470)
* S-a actualizat eSpeak NG (commit e095f008, 10 ianuarie 2017). (#6717)
* Datorită modificărilor aduse în Windows 10 Creators Update, modul „atenuare totdeauna” nu mai este disponibil în setările atenuării audio a NVDA-ului. Cu toate astea, el încă mai este disponibil în vechile lansări ale Windows 10. (#6684)
* Datorită schimbărilor aduse în Windows 10 Creators Update, modul  de reducere a volumului la redarea vorbirii sau a sunetelor nu poate asigura estomparea completă a sunetului înainte de vorbire sau va menține estomparea sufficient încât să oprească sincronizarea rapidă a volumului. Aceste setări nu afectează versiunile mai vechi ale Windows 10. (#6684)

### Defecte rezolvate

* S-a reparat blocarea în Microsoft Word la deplasarea paragrafului printr-un document mare în timpul modului de navigare. (#6368)
* Tabelele în Microsoft Word care au fost copiate din Microsoft Excel nu mai sunt tratate ca tabele de aspect, prin urmare nu mai sunt ignorate. (#5927)
* La încercarea de tastare în Microsoft Excel în timpul vizualizării protejate, NVDA nu emite un sunet mai degrabă decât vorbirea caracterelor care nu au fost tastate. (#6570)
* Apăsarea tastei escape în Microsoft Excel nu mai comută incorect la modul de navigare, dacă utilizatorul nu a comutat mai înainte la modul de navigare cu NVDA+spațiu și a intrat în modul de focalizare prin apăsarea tastei enter pe un câmp formular. (#6569)
* În cazul în care este fuzionat un rând întreg sau o coloană, NVDA nu se mai blochează în foile de calcul ale Excelului. 9#6216)
* Raportarea textului decupat/revărsat în celulele Excelului ar trebui să fie afișată cu mai multă acuratețe. (#6472)
* NVDA anunță când o casetă de bifat este doar-citire. (#6563)
* La lansarea NVDA nu se va mai afișa un dialog de avertizare atunci când nu se poate reda sunetul logo datorită indisponibilității unui dispozitiv audio. (#6289)
* Controalele în ribbonul Excelului care sunt nedisponibile sunt raportate ca atare. (#6430)
* NVDA nu va mai anunța „panou” la minimizarea ferestrelor. (#6671)
* Caracterele tastate sunt acum rostite în platforma universală a Windows-ului (UWP) aplicații (incluzând Microsoft Edge) în Windows 10 Creators Update. (#6017)
* Urmărirea mausului funcționează peste toate ecranele pe calculatoarele cu monitoare multiple. (#6598)
* NVDA nu mai devine inutilizabil după ieșirea din Windows Media Player în timp ce este focalizat pe un glisor de control. (#5467)

### Modificări pentru Dezvoltatori

* Profilurile și fișierele de configurare sunt acum actualizate automat pentru a cunoaște necesitățile modificărilor schematice. Dacă există o eroare pe durata upgrade-ului, o notificare este afișată, configurația este resetată, iar configurația veche este disponibilă în logul NVDA la nivelul 'Info'. (#6470)

## 2016.4

Caracteristicile principale ale acestei lansări includ suport îmbunătățit pentru Microsoft Edge; mod de navigare în aplicația Windows 10 Mail; și îmbunătățiri semnificative la dialogurile NVDA-ului.

### Noi Funcționalități

* NVDA poate acum să indice indentația rândurilor folosind tonuri. Opțiunea poate fi configurată folosind caseta combinată „Anunțare indentație rând” din fereastra cu preferințe pentru formatarea documentului din NVDA. (#5906)
* Suport pentru afișajul braille Orbit Reader 20. (#6007)
* A fost adăugată o opțiune pentru a deschide monitorul de vorbire la pornirea aplicației. Opțiunea poate fi activată printr-o căsuță de bifat din fereastra monitorului de vorbire. (#5050)
* La redeschiderea monitorului de vorbire, locația pe ecran și dimensiunile sale vor fi restabilite. (#5050)
* Câmpurile cu referință încrucișată din Microsoft Word sunt acum tratate ca hiperlink-uri. Acestea sunt raportate ca legături și pot fi activate. (#6102)
* Suport pentru afișajele braille Baum SuperVario2, Baum Vario 340 și HumanWare Brailliant2. (#6116)
* Suport inițial pentru actualizarea aniversară a navigatorului web Microsoft Edge. (#6271)
* Modul de navigare este acum utilizat la citirea mesajelor de poștă electronică în aplicația Windows 10 mail. (#6271)
* Limbă nouă: lituaniană.

### Modificări

* S-a actualizat liblouis, traducătorul braille, la versiunea 3.0.0. Aceasta include îmbunătățiri semnificative la Braille-ul englezesc unificat. (#6109, #4194, #6220, #6140)
* În managerul de suplimente butoanele Dezactivare și Activare supliment au acum comenzi rapide (alt+d și alt+e, respectiv). (#6388)
* Diferite probleme de aliniere și completare cu caractere au fost rezolvate în ferestrele de dialog ale NVDA. (#6317, #5548, #6342, #6343, #6349)
* Fereastra de dialog a formătării documentului a fost ajustată astfel încât conținutul poate fi derulat. (#6348)
* S-a ajustat aspectul casetei de dialog al rostirii simbolurilor, astfel încât întreaga lățime a ferestrei este folosită pentru lista de simboluri. (#6101)
* În mod navigare în browserele de internet, comenzile de navigare cu o singură literă pentru câmpul de editare (e și shift+e) și câmpul formular (f și shift+f), pot fi folosite acum la mutarea la câmpuri de editare în mod doar citire (care pot fi doar parcurse și nu modificate). (#4164)
* În setările de formatare a documentelor, opțiunea „Anunță schimbări de formatare după cursor” a fost redenumită în „Raportează schimbări de formatare după cursor” deoarece afectează atât vorbirea cât și scrierea braille. (#6336)
* S-a ajustat aspectul dialogului „bun venit” din NVDA. (#6350)
* Casetele de dialog NVDA au acum butoanele lor „OK” și „Anulare” aliniate la dreapta dialogului. (#6333)
* Controalele Spin sunt acum utilizate pentru câmpurile numerice de intrare cum ar fi configurarea „Procent schimbare amplitudine la citirea majusculelor”  din fereastra cu Setări Voce. Puteți introduce valoarea dorită, sau puteți folosi tastele sus și jos pentru a o ajusta. (#6099)
* Modul în care sunt raportate IFrame-urile (documente încorporate în alte documente) a fost realizat mai consistent pe diferite browsere. IFrame-urile sunt acum raportate prin „cadru” în Firefox. (#6047)

### Defecte rezolvate

* S-a corectat un defect rar la ieșirea din NVDA în timp ce monitorul de vorbire este deschis. (#5050)
* Hărțile grafice sunt randate în mod corespunzător în mod navigare în Mozilla Firefox. (#6051)
* Atunci când vă aflați în fereastra dicționarului, apăsarea tastei enter salvează toate modificările făcute și închide fereastra de dialog. Anterior, apăsarea tastei enter nu făcea nimic. (#6206)
* Mesajele sunt acum afișate în braille când se modifică moduri de intrare pentru o metodă de intrare (metodă introducere nativă/alfanumerică, Mod formă integrală/parțială, etc.). (#5892, #5893)
* Când dezactivați și reactivați imediat o extensie add-on sau vice versa, starea extensiei add-on revine în mod corect la ceea ce a fost înainte. (#6299)
* Când se folosește Microsoft Word, câmpurile de pagină în numărul antetului pot fi acum citite. (#6004)
* Mausul poate fi acum folosit pentru a deplasa focalizarea între lista de simboluri și câmpurile de editare în fereastra de dialog cu pronunțarea simbolurilor. (#6312)
* În mod navigare, în Microsoft Word, s-a corectat o situație care oprește lista de elemente de la apariție când un document conține un hiperlink invalid. (#5886)
* După ce a fost închisă fereastra din bara de activități sau cu scurtătura alt+F4, starea căsuței de bifat a monitorului de vorbire din meniul NVDA va reflecta vizibilitatea curentă a ferestrei. (#6340)
* Comanda de reîncărcare a plug-inurilor nu mai provoacă probleme pentru configurări de profiluri declanșate, documente noi în browsere de internet și la examinarea ecranului. (#2892, #5380)
* În lista de limbi din fereastra NVDA a Setărilor generale, limbi precum aragoneza sunt acum afișate corect în Windows 10. (#6259)
* Tastele simulate de sistem (de ex. un buton de pe afișajul braille care emulează apăsarea tastei Tab) sunt acum prezentate în ferestrele de configurare pentru limbă și ajutor pentru intrări precum și dialogul cu gesturi de intrare. Anterior acestea erau tot timpul afișate în engleză. (#6212)
* Modificarea limbii NVDA-ului (din dialogul setărilor generale) acum nu are niciun efect până când NVDA este repornit. (#4561)
* Nu mai este posibil să lăsați gol câmpul „model” pentru o nouă intrare în dicționarul vocal. (#6412)
* S-a rezolvat o problemă rară la scanarea porturilor serialelor pe unele sisteme care făceau unele drivere ale afișajelor braille inutilizabile. (#6462)
* În Microsoft Word, bulinele numerotate din celulele tabelului sunt acum citite la deplasarea celulă cu celulă. (#6446)
* Acum este posibil să atribuiți gesturi la comenzi pentru afișajul braille Handy Tech în dialogul gesturilor de intrare al NVDA-ului. (#6461)
* În Microsoft Excel, apăsarea tastelor Enter sau numpadEnter când se navighează pe o foaie de calcul, raportează corect acum navigarea la rândul următor. (#6500)
* iTunes nu se mai blochează intermitent când se utilizează modul de navigare pentru magazinul iTunes, Muzica Apple, etc. (#6502)
* S-au reparat erorile în Mozilla pe 64 biți și în aplicațiile bazate pe Chrome. (#6497)
* În Firefox cu opțiunea multi-proces activată, modul de navigare și câmpurile de text editabile funcționează corect. (#6380)

### Modificări pentru Dezvoltatori

* Acum este posibil să se furnizeze module app pentru executabile care conțin un punct (.) în numele lor. Punctele sunt înlocuite cu liniuțe joase (_). (#5323)
* Noul modul gui.guiHelper include utilități pentru a simplifica crearea GUI-urilor wxPython, incluzând gestionarea automată a spațierii. Acest lucru facilitează un aspect vizual mai bun și consistență, precum și facilitarea creerii unor noi GUI-uri pentru dezvoltatorii nevăzători. (#6287)

## 2016.3

Caracteristicile principale ale acestei lansări includ abilitatea de a dezactiva add-on-uri în mod individual; suport pentru câmpuri de formular în Microsoft Excel; îmbunătățiri semnificative ale raportării culorilor, corectării și îmbunătățiri asociate mai multor afișaje braille și remedieri; și îmbunătățiri ale compatibilității cu Microsoft Word.

### Noi Funcționalități

* Modul navigare poate fi acum folosit pentru citirea documentelor PDF în Microsoft Edge, pentru versiunile Windows 10 Aniversar. (#5740)
* Textele tăiate cu o linie sau linie dublă sunt acum anunțate dacă este cazul în Microsoft Word. (#5800)
* În Microsoft Word, este raportat titlul unui tabel dacă a fost definit. Dacă există o descriere, poate fi accesată folosind comanda de deschidere a descrierii detaliate (NVDA+d) în mod navigare. (#5943)
* În Microsoft Word, NVDA acum raportează informații despre poziție când sunt mutate paragrafe (alt+shift+săgeată jos și alt+shift+săgeată sus). (#5945)
* În Microsoft Word, spațierea între linii este raportată prin comanda NVDA de raportare a formatării, atunci când proprietatea este modificată cu diversele scurtături de taste specifice Microsoft, precum și la mutarea pe un text cu un alt tip de spațiere dacă opțiunea „Anunță spațiere linie” este activată din setările NVDA de formatare a documentului. (#2961)
* În Internet Explorer, elementele structurale de HTML5 sunt acum recunoscute (#6044)
* Raportarea comentariilor (cum sunt cele din Microsoft Word) poate fi acum dezactivată prin opțiunea „Anunță comentarii”, o căsuță de bifat din fereastra de dialog cu setările pentru „Formatare document”. (#5108)
* Acum este posibilă dezactivarea individuală pentru add-on-uri din Managerul de add-on-uri. (#3090)
* Au fost adăugate asocieri adiționale de taste pentru seriile ALVA BC640/680 de afișaje braille. (#5206)
* Există acum o comandă pentru a muta afișajul braille la focalizarea curentă. Momentan doar afișajele din seriile ALVA BC640/680 au o tastă asociată acestei comenzi, dar poate fi asociată manual pentru alte afișaje din fereastra cu gesturi de intrare, dacă se dorește. (#5250)
* În Microsoft Excel, puteți interacționa acum cu câmpuri de forumular. Navigați la câmpuri de formular, folosind lista de elemente sau navigarea cu o singură literă în mod navigare. (#4953)
* Puteți acum asocia un gest de intrare pentru comutarea la modul examinare simplă, folosind fereastra dialog cu „Gesturi de Intrare”. (#6173)

### Modificări

* NVDA acum raportează culori, folosind un set de bază și ușor de înțeles de 9 culori principale și 3 nuanțe, cu variații de luminozitate și tentă. Modul este ales mai degrabă decât cel cu folosirea de nume pentru culori care sunt mai subiective și greu de înțeles. (#6029)
* Comportamentul existent pentru comenzile NVDA+F9 apoi NVDA+F10 a fost modificat în selecția de text la prima apăsare a lui F10. Când F10 este apăsat de două ori (în succesiune rapidă) textul este copiat în planșetă. (#4636)
* Actualizare a eSpeak NG la versiunea Master 11b1a7b (22 iunie 2016). (#6037)

### Defecte rezolvate

* În mod navigare în Microsoft Word, copierea în planșetă acum menține formatarea. (#5956)
* În Microsoft Word, NVDA acum raportează corespunzător când se folosesc comenzile proprii Wordului de navigare a tabelelor (alt+home, alt+end, alt+pageUp și alt+pageDown) și comenzi de selecție pentru tabele (shift adăugat la comenzile de navigare). (#5961)
* În ferestrele de dialog Microsoft Word, navigarea prin obiecte a NVDA a fost îmbunătățită semnificativ. (#6036)
* În anumite aplicații precum Visual Studio 2015, tastele scurtătură (de ex. control+c pentru copiere) sunt acum anunțate cum ar trebui. (#6021)
* Corecție a unei situații rare la scanarea de porturi seriale pe anumite sisteme, care făcea ca anumite drivere de afișaje braille să nu poată fi folosite. (#6015)
* Raportarea de culori în Microsoft Word este acum mai exactă prin luarea în considerare a schimbărilor de teme în Microsoft Office. (#5997)
* Modul navigare pentru Microsoft Edge și compatibilitate pentru sugestiile de căutare din Meniul de Start sunt din nou disponibile pe variantele Windows 10 de după aprilie 2016. (#5955)
* În Microsoft Word, citirea automată a antetelor de tabel funcționează mai bine în cazul celulelor unite. (#5926)
* În aplicația Windows 10 Mail , NVDA nu mai eșuează în citirea conținutului mesajelor. (#5635) 
* Când tasta „Anunță comanda” este activată, tastele de blocare, cum ar fi CapsLock nu mai sunt anunțate de două ori. (#5490)
* Ferestrele de dialog pentru controlul conturilor de utilizator Windows sunt din nou citite corect în actualizarea Windows 10 Anniversary. (#5942)
* În pluginul Web Conference (cum este cel folosit pe out-of-sight.net) NVDA nu mai emite bipuri și nu mai anunță actualizări pentru bara de progres pentru intrările de la microfon. (#5888)
* Efectuarea unei comenzi de „găsește următor” sau „găsește anterior” în modul de navigare, va face acum corect distincția de majuscule, dacă operația de căutare originală a fost cu distincție de majuscule. (#5522)
* La modificarea înregistrărilor într-un dicționar, acum se va anunța folosirea unei expresii regulate invalide. NVDA nu va mai pica dacă un fișier dicționar conține o expresie regulată invalidă. (#4834)
* Dacă NVDA nu mai poate comunica cu afișajul braille (de ex. pentru că a fost deconectat), va dezactiva automat folosirea afișajului. (#1555)
* Performanță ușor îmbunătățită la filtrare în lista de elemente din modul navigare, în unele cazuri. (#6126)
* În Microsoft Excel, numele șabloanelor de fundal raportate de NVDA acum corespund celor folosite de Excel. (#6092)
* Suport îmbunătățit pentru ecranul de autentificare Windows 10, incluzând anunțul alertelor și activarea câmpului de parolă prin atingere. (#6010)
* NVDA acum detectează corect butoanele de mutare pentru seriile ALVA BC640/680 de afișaje braille. (#5206)
* NVDA poate din nou să raporteze notificări Windows Toast în versiunile recente ale Windows 10. (#6096)
* NVDA nu se mai oprește din a recunoaște câteodată apăsări de taste pe afișaje braille Baum-compatibile și HumanWare Brailliant B. (#6035)
* Dacă raportarea numerelor de rând este activată în opțiunile de formatare a documentului ale NVDA, sunt arătate numerele de rând pe afișajele braille. (#5941)
* Când modul vorbire este dezactivat, raportarea obiectelor (cum ar fi apăsarea NVDA+tab pentru anunțul focalizării) apare acum în Monitorul de vorbire așa cum este de așteptat. (#6049)
* În lista de mesaje din Outlook 2016, informația legată de schiță numai este raportată. (#6219)
* În Google Chrome sau alte navigatoare Chrome bazate pe acesta care au interfața în altă limbă decât engleză, modul navigare numai eșuează la deschiderea documentelor multiple. (#6249)

### Modificări pentru Dezvoltatori

* Introducerea directă în jurnale a informației de la o proprietate nu mai cauzează apelul recursiv la proprietatea respectivă în repetate rânduri. (#6122)

## 2016.2.1

Această lansare corectează defectele din Microsoft Word:

* NVDA nu mai provoacă închiderea imediată a Microsoft Word după ce este pornită în Windows XP. (#6033)
* S-a înlăturat raportarea erorilor gramaticale deoarece acest modul provoacă închideri premature în Microsoft Word. (#5954, #5877)

## 2016.2

Caracteristicile principale ale acestei noi lansări includ abilitatea de a raporta erorile de ortografie în timpul tastării; suport pentru raportarea erorilor de ortografie în Microsoft Word; și îmbunătățiri pentru integrarea cu Microsoft Office.

### Noi Funcționalități

* În mod explorare, pentru Internet Explorer și alte controloare MSHTML, acum, folosirea navigației cu prima literă pentru a urma adnotările (a și shift+a), mută la textul inserat și șters. (#5691)
* În Microsoft Excel, NVDA acum anunță nivelul unui grup de celule, precum și dacă este extins sau restrâns. (#5690)
* Dubla apăsare a comenzii „Raportează formatul textului” (NVDA+f) prezintă informația în modul navigare pentru a putea fi examinată. (#4908)
* În Microsoft Excel 2010 sau mai nou, nuanța și umplerea cu gradient pentru celulă sunt, acum, anunțate. Raportarea automată este controlată de opțiunea „Anunță culori” din preferințele pentru formatarea documentului ale NVDA. (#3683)
* Tabel nou de traducere braille: greacă comună. (#5393)
* În Vizualizatorul de Jurnale puteți salva jurnalul folosind combinația control+s. (#4532)
* Dacă raportarea erorilor de ortografie este activată și disponibilă pentru controlul cu focus, NVDA va reda un sunet pentru a vă notifica dacă a fost făcută o greșeală în timpul tastării. Aceasta poate fi dezactivată folosind noua poțiune „Redă sunet pentru erorile de ortografie în timpul tastării” în fereastra de preferințe a NVDA pentru setări tastatură. (#2024)
* Erorile de ortografie sunt acum raportate în Microsoft Word. Această setare poate fi dezactivată folosind noua opțiune „Anunță erori de ortografie” în fereastra de preferințe pentru formatarea documentului a NVDA. (#5877)

### Modificări

* În mod navigare și pentru câmpuri text editabile, NVDA acum tratează tasta Enter de pe blocul numeric la fel ca tasta Enter principală. (#5385)
* NVDA a trecut la sintetizatorul de vorbire eSpeak NG. (#5651)
* În Microsoft Excel, NVDA nu mai ignoră un antet de coloană pentru o celulă atunci când există un rând gol între celulă și antet. (#5396)
* În Microsoft Excel, coordonatele sunt acum anunțate înaintea antetelor pentru a elimina ambiguitățile dintre antete și conținut. (#5396)

### Defecte rezolvate

* În modul navigare, la încercarea de a folosi navigarea cu o singură literă pentru a se muta la un element care nu este suportat pentru respectivul document, NVDA anunță că acest lucru nu este suportat, față de precedentul anunț că nu există element în direcția respectivă. (#5691)
* La listarea foilor de lucru în Lista de elemente pentru Microsoft Excel, sunt acum incluse și foile care conțin doar diagrame. (#5698)
* NVDA nu mai anunță informații ciudate la comutarea ferestrelor într-o aplicație Java cu ferestre multiple, cum ar fi IntelliJ sau Android Studio. (#5732)
* În editoare bazate pe Scintilla, cum ar fi Notepad++, braille este acum actualizat corect când se mută cursorul folosind un afișaj braille. (#5678)
* NVDA nu mai are probleme de terminare prematură uneori când se activează ieșirile braille. (#4457)
* În Microsoft Word, indentația de paragraf este acum anunțată întotdeauna în unitatea de măsură aleasă de utilizator (de ex. centimetri sau inchi). (#5804)
* Când este folosit un afișaj braille, multe dintre mesajele NVDA care erau doar rostite, acum sunt și afișate braille. (#5557)
* În aplicații Java accesibilizate, nivelurile elementelor dintr-o structură arborescentă sunt acum anunțate. (#5766)
* Corectare erori de închidere prematură pentru Adobe Falsh în Mozilla Firefox pentru anumite cazuri. (#5367)
* În Google Chrome și browsere bazate pe Chrome, documentele din interiorul ferestrelor de dialog sau a aplicațiilor pot fi acum citite în mod navigare. (#5818)
* În Google Chrome și browsere bazate pe Chrome, puteți acum forța comutarea NVDA la modul navigare în ferestrele de dialog web sau aplicații. (#5818)
* În Internet Explorer și alte controale MSHTML, mutarea focusului la anumite controale (în specific unde este folosit aria-activedescendant) nu mai comută, incorect, la modul navigare. Aceasta se întâmpla, de exemplu, când se făcea mutarea la sugestii în câmpurile adresă la compunerea unui mesaj în Gmail. (#5676)
* În Microsoft Word, NVDA nu se mai blochează pentru tabele mari atunci când raportarea antetelor de rând/coloană ale tabelelor este activată. (#5878)
* În Microsoft word, NVDA nu mai raportează incorect textul cu un nivel de subliniere (dar nu pentru un stil de rubrică integrat) ca rubrică. (#5186)
* În mod navigare în Microsoft Word, comenzile de mutare după sfârșit/ la începutul obiectului conținător (virgulă și shift+virgulă) acum funcționează pentru tabele. (#5883)

### Modificări pentru Dezvoltatori

* componentele C++ ale NVDA sunt acum generate cu Microsoft Visual Studio 2015. (#5592)
* Acum se poate prezenta utilizatorului un mesaj text sau HTML în mod navigare folosind ui.browseableMessage. (#4908)
* În Ghidul Utilizatorului, când este folosită o comandă <!-- KC:setting pentru o setare care are o tastă comună pentru toate formatele, tasta poate fi pusă după un semn două puncte de mărime întreagă (：) precum și după un semn două puncte normal (:). (#5739) -->

