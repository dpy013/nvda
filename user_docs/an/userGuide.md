# Guida de l'Usuario d'o NVDA NVDA_VERSION

[TOC]

<!-- KC:title: NVDA NVDA_VERSION Referencia Rapida d'Ordens  -->



## Introducción {#Introduction}

Bienveniu/bienvenida en o NVDA!

O NonVisual Desktop Access (NVDA) ye un lector de pantalla libre y de codigo ubierto  pa o Sistema Operativo  Microsoft Windows.
Furnindo retroalimentación a traviés de voz sintetica y Braille, posibilita a la chent ciega u deficient visual accedir a ordinadors executando lo Windows por un coste no mayor a lo d'una persona vident.
O NVDA ye desembolicau por [NV Access](https://www.nvaccess.org/), con  colaboracions d'a comunidat.

### Caracteristicas chenerals {#GeneralFeatures}

O NVDA permite a personas ciegas y deficients visuals d'accedir y interactuar con o Sistema Operativo Windows y muitas aplicacions de tercers. 

Lo mas resinyable inclui: 

* Suporte pa aplicacions populars incluindo navegadors web, clients de correu, programas de chat en internet y suites d'usina
* Sintetizador de voz integrau que suporta sobre 80 idiomas
* Anunciau de formato de texto do siga disponible tal como nombre y grandaria d'a fuent, estilo y errors d'ortografía
* Anunciau automatico de texto baixo lo churi y indicación opcional audible  d'a posición d'o churi
* Suporte pa muitas linias braille dinamico incluindo la capacidat de detectar automaticament muitas d'ellas asinas como la dentrada de braille computerizau pa las linias que tiengan un teclau braille
* Capacidat pa executar-se de raso dende una memoria USB u atros meyos portables sin a necesidat d'instalación
* Instalador parlant facil d'emplegar
* Traduciu en 54 idiomas
* Suporte pa Sistemas Operativos Windows modernos incluindo as variants de 32 y 64 bits
* Capacidat pa executar-se mientras l'inicio de sesión en o Windows  y en pantallas seguras 
* Anunciau de controls y texto entre que s'emplega cenyos tactils
* Suporte pa interficies comunas d'accesibilidat tals como lo Microsoft Active Accessibility, o Java Access Bridge, l'IAccessible2 y l'UI Automation
* Suporte pa lo simbolo d'o sistema d'o Windows y as aplicacions de consola
* La capacidat de resaltar lo foco d'o sistema

### Internacionalización {#Internationalization}

Ye important que qualsiquier persona en o mundo, sin importar qué idioma charre, tienga igual acceso a la tecnolochía. 
Actualment o NVDA ye estau traduciu en 54 idiomas antiparti de l'anglés incluindo: Afrikaans, albanés, amárico, arabe, aragonés, Burmés, catalán, chinés tradicional y simplificau, crovata, checo, danés, holandés, farsi, finlandés, francés, gallego, griego, Cheorchiano, alemán (Alemania y Suiza), hebreu, hindi, hungaro, islandés, irlandés, italián , chaponés, Kyrgyz, coreán, lituánn, Macedonio, Mongol, nepalí, noruego, polaco, portugués (Brasil y Portugal), panyabí, rumano, ruso, serbio, eslovaco, esloveno, espanyol (Eespanya y Colombia), sueco, tamil, tailandés, turco, ucrainés, virmán y vietnamita.

### Suporte de Sintesi de Voz {#SpeechSynthesizerSupport}

Amás de furnir os suyos mensaches y interficie en quantos idiomas, o NVDA tamién puet posibilitar a l'usuario pa leyer contenius en qualsiquier idioma, malas que tiengan un sintetizador de voz que pueda charrar ixe idioma en particular. 

O NVDA ye equipau con [eSpeak NG](https://github.com/espeak-ng/espeak-ng), un sintetizador de voz multilingüe, libre, de codigo ubierto.

Se puet trobar información sobre atros sintetizadors de voz que suporta lo NVDA en a sección [Sintetizadors de Voz suportaus](#SupportedSpeechSynths).

### Suporte Braille {#BrailleSupport}

Pa los usuarios que poseigan una linia de braille dinamico, lo NVDA puet amostrar a suya información en braille. 
Tamién se suporta tanto la dentrada de braille no contraito como contraito a traviés d'un teclau braille.
Amás lo NVDA detectará muitas linias braille automaticament de traza predeterminada.
Por favor mira-te la sección de [linias Braille Suportadas](#SupportedBrailleDisplays) pa información sobre las linias braille suportadas.

O NVDA suporta codigos braille pa muitos idiomas, incluindo codigos braille contraito, no contraito y computerizau.

### Licencia y dreitos d'autor {#LicenseAndCopyright}

Lo NVDA ye copyright NVDA_COPYRIGHT_YEARS por los colaboradors d'o NVDA.

Lo NVDA ye disponible baixo la licencia publica cheneral de GNU  versión 2, con dos excepcions especials. 
Las excepcions se describen en o documento de licencia en as seccions de "components no GPL en complementos y controladors" y "codigo distribuible de Microsoft".
Lo NVDA tamién incluye y emplega components que son disponibles baixo diferents licencias de codigo ubierto y franco.
Yes libre pa compartir u modificar iste programa de qualsiquier traza que quieras encara que has de distribuir a licencia de conchunta con o programa, y fer tot o codigo fuent disponible a qui lo quiera. 
Ixo s'aplica a l'orichinal y a las copias modificadas d'o programa, mas qualsiquier software que utilice codigo preso dende iste programa. 

Pa mas detalles, puetz [mirar-te la licencia completa.](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
Pa detalles arredol d'as excepcions, accede t'o documento d'a licencia dende lo menú d'o NVDA baixo la sección d'"aduya".

## Requerimientos d'o Sistema {#SystemRequirements}

* Sistemas Operativos: todas las edicions de 32 y 64 bits d'o Windows 7, Windows 8, Windows 8.1, Windows 10, Windows 11 y totz los sistemas operativos servidors empecipiando dende lo Windows Server 2008 R2.
* Pa lo Windows 7 lo NVDA requier  lo Service Pack 1 u superior.
* Pa lo Windows Server 2008 R2 lo NVDA requier  lo Service Pack 1 u superior.
* A lo menos 150 MB d'espacio d'almagazenamiento.

## Obtenendo y Instalando lo NVDA {#GettingAndSettingUpNVDA}

Si agún no tiens una copia d'o NVDA, puetz descargar-la dende [la pachina web de NV Access](NVDA_URL).

Ves t'a sección download y bi trobarás un vinclo pa descargar la zaguer versión d'o NVDA.

En executar lo fichero que has descargau prencipiará una copia temporal d'o NVDA.
 Allora te se preguntará si quiers instalar o NVDA, creyar una copia portable, u nomás continar emplegando a copia temporal.

Si planeyas emplegar siempre lo NVDA en iste ordinador, trigarás instalar lo NVDA.
A lo instalar NVDA permitirás funcionalidat adicional tal como tener-lo encetau automaticament dimpués d'autentificar-te, que siga capaz de leyer as pantallas d'autentificación de Windows y as pantallas seguras (coseta que las copias portables y temporals no pueden fer), y a creyación d'os alcorces d'o menú Encieto y d'o Escritorio.
A copia instalable tamién ye capable de creyar una copia portable por si mesma en qualsiquier momento.

Si quiers tener o NVDA con tu en un lapiz USB u unatro meyo portatil, allora habrías a trigar creyar una copia portable.
A copia portable tamién tien a capacidat d'instalar-se en qualsiquier ordinador en una con posterioridat.
Manimenos, si deseyas copiar o NVDA en un meyo de nomás lectura tal como un CD, solament habrías de copiar o paquet descargau.
Executar a versión portable dreitament dende meyos de nomás lectura no ye suportau por agora.

Emplegar a copia temporal d'o NVDA ye tamién una opción, p. eix.: con propositos de contrimostración, ya que encetar o NVDA d'iste modo cada vez puet plegar a estar muit incomodo.

### Restriccions d'as Copias Portable y Temporal {#PortableAndTemporaryCopyRestrictions}

Amás d'a incapacidat d'encetar-se automaticament entre y/u dimpués de l'autentificación, as copias portable y temporal d'o NVDA tamién tienen as siguients restriccions:

* A incapacidat pa interactuar con as aplicacions que s'executen con privilechios d'administrador, a lo menos que, profés, o mesmo NVDA tamién siga estau executau con istos privilechios (no ye recomendable).
* A incapacidat de leyer as pantallas d'o Control de Cuentas d'Usuario (UAC) quan tracte d'encetar una aplicación con privilechios d'administrador.
* Windows 8 y superiors: a incapacidat pa suportar a dentrada dende una pantalla tactil.
* Windows 8 y superior: L'achiquida d'audio no ye suportada.
* Windows 8 y superiors: a incapacidat d'amanir caracteristicas tals como lo modo de navegación y lo charrau d'os caracters en escribir-los en aplicacions d'o Windows Store.

### Instalando lo NVDA {#InstallingNVDA}

Si t'instalas o NVDA dreitament dende o paquet descargau d'o NVDA, preta o botón Instalar o NVDA.
Si ya has zarrau iste dialogo, u quiers instalar-lo dende una copia portable, por favor triga l'elemento de menú Instalar o NVDA que se troba baixo Ferramientas en o menú NVDA.

O dialogo d'instalación que amaneix confirmará si quiers instalar o NVDA, y tamién te dirá si ista instalación esviellará una instalación anterior.
en Pretar o botón Continar prencipiará a Instalación d'o NVDA.
Bi ha tamién qualques opcions en iste dialogo que s'explican mas abaixo.
Una vez s'haiga completau a instalación, amaneixerá un mensache decindo-te que ye estada satisfactoria.
En pretar Acceptar en iste punto se reiniciará la copia nueva instalada d'o NVDA.

#### Alvertencia sobre los complementos incompatibles {#InstallWithIncompatibleAddons}

Si ya tiens complementos instalaus tamién puet haber-bi una alvertencia que se desenchegará los complementos incompatibles.
Antis de no poder pretar lo botón de continar habrás d'utilizar la caixeta de verificación pa confirmar que comprendes que ixos complementos se desenchegarán.
Tamién bi ha present un botón pa revisar los complementos que se desenchegarán.
Mira-te la [sección d'o dialogo de complementos incompatibles](#incompatibleAddonsManager) pa mas aduya sobre ixe botón.

#### Emplegar lo NVDA entre que s'inicia la sesión {#StartAtWindowsLogon}

Ista opción te permite trigar si lo NVDA habría a rancar automaticament u no pas entre que inicias la sesión en o Windows, antis de no haber ficau garra clau.
Ixo tamién inclui lo control d'as cuentas d'usuario y atras pantallas seguras.
Ixa opción ye enchegada de traza predeterminada pa las instalacions nuevas.

#### Creyar Alcorces d'o Escritorio (ctrl+alt+n) {#CreateDesktopShortcut}

Ista opción te permite trigar si o NVDA habría a creyar u no pas un alcorce en o escritorio ta encetar o NVDA. 
Si en ye creyau, a iste alcorce tamién le'n asignará un alcorce de teclas control+alt+n permitindo-te encetar o NVDA en qualsiquier inte con ista combinación de teclas.

#### Copiar la configuración portable de l'actual cuenta d'usuario {#CopyPortableConfigurationToCurrentUserAccount}

Ista opción te permite trigar si lo NVDA habría a copiar u no pas la configuración de l'usuario de l'actual NVDA en execución en a configuración pa l'usuario actualment autentificau, t'a copia instalada d'o NVDA. 
Ixo no copiará la configuración ta qualsiquier atro usuario d'ixe sistema ni t'a configuración d'o sistema pa emplegar-la entre que s'inicie la sesión d'o Windows y atras pantallas seguras.
Ista opción solament ye disponible quan s'instala dende una copia portable, no pas quan s'instala dreitament dende lo paquet Lanzador descargau.

### Creyando una Copia Portable {#CreatingAPortableCopy}

Si se creya una copia portable dreitament dende o paquet descargau d'o NVDA, simplament preta o botón Creyar Copia Portable.
Si ya has zarrau iste dialogo u yes executando una copia instalada d'o NVDA, triga l'elemento de menú Creyar una Copia Portable que se troba baixo Ferramientas en o menú NVDA.

O dialogo que amaneix te permite trigar do habría a creyar-se la copia portable.
Ixo puet estar un directorio en o tuyo disco duro, un puesto en un lapiz USB u belatro meyo portatil.
Tamién bi ha una opción ta trigar si o NVDA habría a copiar a sesión de configuración actual de l'usuario d'o NVDA ta emplegar-la con a nueva copia portable creyada.
Ista opción solament ye disponible quan se creya una copia portable dende una copia instalada, no pas quan se creya dende o paquet descargau.
En pretar Continar creyarás a copia portable.
Una vez que la creyación siga completada, amaneixerá un mensache decindo-te que ye estada exitosa.
Preta Acceptar ta zarrar iste dialogo.

## Prencipiando con o NVDA {#GettingStartedWithNVDA}
### Lanzando lo NVDA {#LaunchingNVDA}

Si has instalau o NVDA con l'instalador, allora rancar NVDA ye tant facil como pretar control+Alt+n, u trigar NVDA dende lo menú d'o NVDA en o menú d'inicio, submenú Programas. 
Adicionalment puetz tecliar NVDA en o dialogo Executar y pretar l'Intro.
Si lo NVDA ya se ye executando allora se renchegará.
Tamién puetz pasar-le bellas [opcions de linia de comandos](#CommandLineOptions) que te permiten salir (-q), desenchegar os complementos (--disable-addons), etc.

Pa las copias instaladas, o NVDA almagazena la configuración en a carpeta roaming application data de l'usuario actual por defecto (p. eix. "C:\Users\<user>\AppData\Roaming").
Ye posible cambiar ixo de forma que lo NVDA cargue a suya configuración dende a carpeta local de datos d'aplicación en cuenta.
Consulta la sección arredol de [parámetros d'o sistema](#SystemWideParameters) pa mas detalles.

Pa rancar la versión portable, ves t'o directorio que i descomprimiés lo NVDA y preta l'intro u fe doble clic sobre nvda.exe.
Si lo NVDA ya yera en execución, s'aturará automaticament dimpués de rancar la versión portable.

En que o NVDA ranque en primeras escuitarás un grupo ascendent de tons (que te dicen que o NVDA ye cargando-se). 
Pendendo cuán rapido siga o tuyo ordinador, u si yes executando lo NVDA dende un lapiz USB u belatro meyo lento, podrá demorar un poquet mientras ranca. 
Si ye tardando un tiempo extra largo en rancar, o NVDA habría a dicir "Se ye cargando lo NVDA. Aspera por favor...”

Si no escuitas brenca d'isto, escuitas o son d'error de Windows, u un grupo descendent de tons, allora isto significa que o NVDA tien una error, y posiblement amenesterás informar d'un fallo a os desembolicadors. 
Por favor investiga en o puesto Web d'o NVDA pa saber cómo fer ixo.

#### Dialogo de bienvenida {#WelcomeDialog}

Quan o NVDA ranque por primer vez, se te dará a bienvenida por meyo d'un quadro de dialogo que te furne bella información basica sobre a tecla modificadera d'o NVDA y d'o menú d'o NVDA. 
(Mira-te por favor as seccions subsiguients sobre istos temas). 
O quadro de dialogo tamién contién un quadro combinau y tres caixetas de verificación. 
O quadro combinau te permite seleccionar a distribución d'o teclau.
La primer caixeta de verificación te permite controlar si lo NVDA habría de fer servir lo BloqMayus como una tecla modificadera d'o NVDA.
La segunda especifica si lo NVDA habría de rancar automaticament dimpués d'autentificar-te en o Windows y nomás ye disponible pa copias instaladas d'o NVDA.
La tercera te permite controlar si iste dialogo de bienvenida habría d'amaneixer cada vez que lo NVDA ranque.

#### Dialogo d'estatisticas de datos d'uso {#UsageStatsDialog}

A partir d'o NVDA 2018.3, se pregunta a l'usuario si quiere permitir que los datos d'uso se ninvien ta NV Access pa aduyar a amillorar-lo en o futuro. 
En iniciar lo NVDA por primer vez, amaneixerá un dialogo que te preguntará si quiers acceptar lo ninvio de datos ta NV Access entre que lo emplegas.
Puetz leyer mas información sobre los datos replegaus por NV Access en a sección d'opcions chenerals, [permitir a lo prochecto NVDA que replegue estatisticas d'emplego d'o NVDA](#GeneralSettingsGatherUsageStats).
Nota: en pretar en "sí" u "no" s'alzará ixe achuste y lo dialogo no amaneixerá nunca mas de no estar que reinstales lo NVDA.
Manimenos, puetz enchegar u desenchegar lo proceso de replega de datos a man en o panel d'as opcions chenerals d'o NVDA. Pa cambiar ixa opción a man, puetz marcar u desmarcar la caixeta de verificación clamada [permitir a lo prochecto NVDA que replegue estatisticas d'emplego d'o NVDA](#GeneralSettingsGatherUsageStats).

### Sobre as Ordens de teclau d'o NVDA {#AboutNVDAKeyboardCommands}
#### A Tecla Modificadera d'o NVDA {#TheNVDAModifierKey}

A mayoría d'as ordens especificas de teclau d'o NVDA consisten normalment en a pulsación d'a tecla modificadera d'o NVDA, de conchunta con una u mas teclas. 
Notables excepcions a  isto son as ordens de revisión t'a distribución de teclau d'escritorio que nomás emplegan as teclas d'o teclau numerico por ellas mesmas, pero bi ha belatras excepcions tamién. 

O NVDA puet configurar-se de traza que a tecla Insert d'o teclau numerico, a Insert de l'extendiu y/u o BloqMayus puedan emplegar-sen como teclas modificaderas d'o NVDA.
De traza predeterminada tanto l'insert d'o teclau numerico como o d'o teclau extendiu pueden emplegar-se como teclas modificaderas.

Si deseyas fer que una d'as teclas modificaderas d'o NVDA actúe como usualment si o NVDA no estase enchegau (por eixemplo deseyas activar o BloqMayus quan tiens configurada o BloqMayus ta que siga una tecla modificadera d'o NVDA) puetz pretar a tecla dos veces en succesión rapida.

#### Distribucions de Teclau {#KeyboardLayouts}

Actualment o NVDA vien con dos conchuntos de  teclas d'ordens conoixidas como distribucions de teclau: a distribución sobremesa y a distribución portátil.
De traza predeterminada o NVDA ye configurau pa emplegar a distribución de sobremesa, anque puetz cambiar t'a distribución de portatils en a categoría de teclau d'o dialogo d'[opcions d'o NVDA](#NVDASettings) que se troba baixo as preferencias en o menú NVDA.

A distribución de sobremesa fa un uso amplo d'o teclau numerico (con o bloqueyo numerico desactivau).
Encara que a mayoría d'os portatils no tienen un teclau numerico fisico, qualques portatils en pueden emular un mantenendo preta la tecla FN y pretando letras y numers en a man dreita d'o teclau (7 8 9 u i o j k l etc.).
Si lo portatil tuyo no puet fer isto, u no te permite desenchegar lo bloqueyo numerico, podrás querer cambiar t'a distribución Portatil en cuenta.

### Cenyos tactils d'o NVDA {#NVDATouchGestures}

Si yes executando lo NVDA en un dispositivo con una pantalla tactil y yes executando lo Windows 8 u superior, tamién puetz controlar lo NVDA dreitament a traviés de cenyos tactils.
Entre que lo NVDA siga en execución, fueras que lo suporte d'interacción tactil siga desenchegau, toda la dentrada tactil irá dreitament t'o NVDA. 
Por tanto, las accions que puedan efectuar-sen normalment sin o NVDA no funcionarán.
<!-- KC:beginInclude -->
Pa conmutar lo suporte d'interacción tactil, preta NVDA+control+alt+t.
<!-- KC:endInclude -->
Tamién puetz enchegar u desenchegar lo [suporte d'interacción tactil](#TouchSupportEnable) dende la categoría d'interacción tactil d'as opcions d'o NVDA.

#### Explorando a Pantalla {#ExploringTheScreen}

A mayoría d'as accions basicas que puetz realizar con a pantalla tactil son anunciar o control u lo texto en qualsiquier punto en a pantalla.
Pa fer ixo, mete un dido en qualsiquier puesto sobre a pantalla.
Tamién puetz mantener o tuyo dido sobre a pantalla y mover-lo arredol ta leyer atros controls y texto sobre o qual vaigas movendo o dido.

#### Cenyos Tactils {#TouchGestures}

Quan se describa las ordens d'o NVDA d'agora en adebant en ista guida de l'usuario, podrán listar un cenyo tactil que se puet emplegar pa enchegar ixa orden con a pantalla tactil.
Contino va qualques instruccions sobre cómo levar a cabo quantos cenyos tactils.

##### Toques {#toc27}

Tocar a pantalla breument con un u mas didos.

A tocar una vez con un dido se le conoix simplament como un toque.
Tocar con dos didos a lo mesmo tiempo ye un toque de 2 didos y asinas succesivament.

Si o mesmo toque se realiza una u mas veces en succesión rapida, NVDA lo tractará en cuenta como un cenyo multi-toque.
Tocar dos veces resultará en un dople toque.
Tocar tres veces resultará en un triple toque y asinas succesivament.
Prou que istos cenyos multi-toque tamién reconoixen quántos didos estioron utilizaus, asinas ye posible tener cenyos como un 2 didos con triple toque, u un toque con 4 didos, etc. 

##### Eslizamientos {#toc28}

Eslizar o tuyo dido rapidament por a pantalla.

Bi ha 4 cenyos d'eslizamiento posibles pendendo de l'adreza: eslizar ta la cucha, eslizar ta la dreita, eslizar enta alto y eslizar enta abaixo.

Igual como con os toques, se puet emplegar mas d'un dido ta realizar o cenyo.
Por tanto, cenyos tals como eslizar dos didos enta alto u eslizar 4 didos ta la cucha son totz posibles.

#### Modos Tactils {#TouchModes}

Tal como bi ha muitas ordens d'o NVDA tamién bi ha atros cenyos tactils. O NVDA tien quantos modos tactils entre os quals puetz cambiar, que fan disponibles bells subconchuntos d'ordens.
Totz dos modos que existen por agora son o modo de texto y o modo d'obchecto. 
Bellas ordens d'o NVDA amostradas en iste documento podrán tener un modo tactil amostrau entre parentesi dimpués d'o cenyo tactil.
Por eixemplo: eslizar enta alto (modo de texto) significa que a orden se realizará si eslizas enta alto, pero nomás mientras sigas en o modo de texto.
Si a orden no tien un modo asociau con ella, funcionará en qualsiquier modo.

<!-- KC:beginInclude -->
Pa commutar entre totz dos modos, rializa un toque con 3 didos.
<!-- KC:endInclude -->

#### Teclau Tactil {#TouchKeyboard}

O teclau tactil s'utiliza pa ficar texto y comandos dende una pantalla tactil.
Quan s'enfoque un campo d'edición, puetz desplegar lo teclau tactil tocando dos veces sobre l'icono d'o teclau tactil en a parti inferior d'a pantalla.
Pa tablets tals como a Microsoft Surface Pro, lo teclau tactil siempre ye disponible quan se desbloqueya lo teclau.
Pa repuyar lo teclau tactil, toca dos vegadas l'icono d'o teclau tactil u sale difuera d'o campo d'edición.

Entre que lo teclau tactil siga activo, pa localizar las teclas en o teclau tactil, mueve lo dido t'o puesto en do se trobe lo teclau tactil (por un regular en a parti inferior d'a pantalla), y contino, desplaza-te por lo teclau con un dido.
En que trobes a tecla que deseyes pretar, toca dos veces a tecla u devanta o dido, seguntes las opcions trigadas dende la [categoría d'opcions d'interacción tactil](#TouchInteraction) d'as preferencias d'o NVDA.

### Modo d'Aduya de Dentrada {#InputHelpMode}

Muitas ordens de teclau y cenyos se mencionan a lo largo d'a resta d'ista guida de l'usuario, pero una traza facil d'explorar todas as diferents ordens ye activar l'aduya de dentrada.

T'activar l'aduya de dentrada, preta NVDA+1.
Pa desactivar-la, preta NVDA+1 de nuevas.
Mientras sigas en l'aduya de dentrada, pretando qualsiquier tecla u realizando qualsiquier cenyo tactil s'anunciará l'acción y se describirá qué'n fa (si ye que fa bella cosa).
As ordens actuals no s'executarán mientras se siga en o modo d'aduya de dentrada.

### O Menú d'o NVDA {#TheNVDAMenu}

O menú NVDA te permite controlar as opcions d'o NVDA, acceder ta l'aduya, alzar/tornar t'a tuya configuración, Modificar os diccionarios d'a fabla, leyer o fichero d'o rechistro, y salir d'o NVDA.

Pa desplegar o menú NVDA dende qualsiquier puesto d'o Windows mientras o NVDA se siga executando, preta NVDA+n en o teclau u fe un dople toque con 2 didos en a pantalla tactil. 
Tamién puetz desplegar o menú NVDA a traviés d'a servilla de sistema d'o Windows.
u fendo clic con o botón dreito sobre l'icono NVDA trobau en a servilla de sistema, u accedindo t'a servilla de sistema pretando a tecla con o logo de Windows+B, flecha abaixo dica l'icono d'o  NVDA y pretando a tecla aplicacions trobada de seguida a la tecla de control d'a dreita en a mayoría d'os teclaus. 
Quan amaneixca o menú, puetz emplegar as teclas de cursor pa navegar por o menú, y a tecla intro pa enchegar bell elemento.

### Comandos Basicos d'o NVDA {#BasicNVDACommands}

<!-- KC:beginInclude -->

| Nombre |Tecla escritorio |tecla portatil |Tactil |Descripción|
|---|---|---|---|---|
|Rancar u reenchegar lo NVDA |Control+alt+n |Control+alt+n |no |Ranca u reenchega lo NVDA dende lo Escritorio si ixe alcorce d'o Windows s'enchega mientras lo proceso d'instalación d'o NVDA. Iste ye un alcorce especifico d'o Windows conque no se puede reasignar en o dialogo de cenyos de dentrada.|
|Aturar la voz |Control |Control |toque con 2 didos |Atura la voz a l'inte|
|Pausar la Voz |Mayus |Mayus |no |Pausa la voz a l'inte, pretando-lo unatra vez continará charrando dende do se detenió (si lo pausau ye suportau por lo sintetizador actual)|
|Menú d'o NVDA |NVDA+n |NVDA+n |dople toque con 2 didos |desplega lo menú d'o NVDA pa permitir-te accedir ta preferencias, ferramientas, aduya etc.|
|Commutar lo Modo d'Aduya de dentrada |NVDA+1 |NVDA+1 |no |Pretando qualsiquier tecla  en iste modo s'anunciará la tecla, y la descripción de qualsiquier orden d'o NVDA asociada con ella|
|Commutar lo Modo de Voz |NVDA+s |NVDA+s |no |Commuta lo modo de voz entre charrar, chuflius y desactivau.|
|Salir d'o NVDA |NVDA+q |NVDA+q |no |Sale d'o NVDA|
|Deixar pasar la siguient tecla |NVDA+f2 |NVDA+f2 |no |Diz a lo NVDA que deixe pasar la siguient tecla pretada dreitament ta l'aplicación activa, si ye tractada por un regular como una tecla d'ordens d'o NVDA|
|activar y desactivar lo modo d'aplicación silencioso |NVDA+mayus+s |NVDA+mayus+z |no |Lo modo silencioso desactiva todas las ordens d'o NVDA y la salida de voz/braille pa l'aplicación actual. Isto ye mas util en aplicacions que furneixen la suya propia voz u caracteristicas de lectura de pantalla. Preta ista orden nuevament pa desactivar lo modo silencioso.|

<!-- KC:endInclude -->

### Anunciando Información d'o Sistema {#ReportingSystemInformation}

<!-- KC:beginInclude -->

| Nombre |tecla |Descripción|
|---|---|---|
|Anunciar la calendata/hora |NVDA+f12 |Pretando-lo una vez anuncia la hora actual, pretando-lo dos veces anuncia la calendata.|
|Anunciar lo estau d'a batería |NVDA+mayus+b |Anuncia lo estau d'a batería, ye decir si la electricidat ye emplegando-se u lo porcentache actual d'a carga.|
|Anunciar lo texto en o portafuellas |NVDA+c |Anuncia lo Texto en o portafuellas si bi'N ha belún.|

<!-- KC:endInclude -->

## Navegando con o NVDA {#NavigatingWithNVDA}

O NVDA te permite d'explorar y navegar o sistema de quantas trazas, incluindo interacción normal y revisión.

### Obchectos {#Objects}

Cada Aplicación y o propio sistema operativo constan de muitos obchectos.
Un obchecto ye un simple elemento tal como un trozo de texto, botón, caixeta de verificación, eslizador, lista u campo de texto editable.

### Navegando con o Foco d'o Sistema {#SystemFocus}

Lo foco d'o sistema, tamién conoixiu simplament como lo foco, ye o [obchecto](#Objects) que recibe teclas escritas en o teclau.
Por eixemplo, si yes escribindo en un campo de texto editable, o campo de texto editable tien o foco.

Lo modo mas común de navegar por lo Windows con o NVDA, ye nomás mover-se con as ordens de teclau normals, tals como tabulador y mayus tabulador Ta mover-se-ne enta avant y dezaga entre controls, pretando l'Alt Ta desplegar a barra de menú y dimpués emplegando as teclas de cursor ta navegar por os menús, emplegando l'Alt-tabulador Ta mover-se-ne entre as aplicacions en execución. 
Quan fagas ixo lo NVDA anunciará información sobre o que tien o foco, tal como o suyo nombre, tipo, valor, estau, descripción, alcorce de teclau y información posicional.
Quan lo [resaltau visual](#VisionFocusHighlight) siga enchegau, la localización d'o foco d'o sistema actual tamién se exposa visualment.

Bi ha qualques ordens de teclau utils quan nos movemos con o foco:
<!-- KC:beginInclude -->

| Nombre |tecla sobremesa |tecla portatil |Descripción|
|---|---|---|---|
|Anunciar lo foco actual |NVDA+tabulador |NVDA+tabulador |anuncia l'obchecto actual u lo control que tienga lo foco d'o sistema. Pretando-lo dos veces letriará la información|
|Anunciar lo titol |NVDA+t |NVDA+t |Anuncia lo titol d'a finestra activa actualment. Pretando-lo dos veces letriará la información. Pretando-lo tres veces la copiará t'o portafuellas|
|Leyer la finestra activa |NVDA+b |NVDA+b |leye totz los controls en a finestra actualment activa (util pa dialogos)|
|Anunciar la Barra d'Estau |NVDA+fin |NVDA+mayus+fin |Anuncia la barra d'estau si lo NVDA en troba una. En pretar dos veces letreya la información. En pretar tres veces lo copiará en o portafuellas|

<!-- KC:endInclude -->

### Navegando con o Cursor d'o Sistema {#SystemCaret}

Quan un [obchecto](#Objects) que permite navegación y/u edición de texto s'[enfoca](#SystemFocus), puetz mover-te-ne a traviés d'o texto emplegando lo cursor d'o sistema, tamién conoixiu como lo cursor d'edición.

Quan lo foco siga sobre un obchecto que tienga lo cursor d'o sistema, puetz emplegar las teclas de cursor, retroceso de pachina, abance de pachina, inicio, fin, etc. pa mover-te a traviés d'o texto.
Tamién puetz cambiar lo texto si lo control suporta edición.
Lo NVDA anunciará seguntes te muevas por caracters, parolas, linias, y tamién anunciará la selección y no selección de texto.

Lo NVDA furneix las siguients teclas d'ordens en relación a lo cursor d'o sistema:
<!-- KC:beginInclude -->

| nombre |tecla sobremesa |tecla portatil |descripción|
|---|---|---|---|
|Leyer-lo tot |NVDA+flecha abaixo |NVDA+A |Prencipia la lectura dende la posición actual d'o cursor d'o sistema movendo-lo seguntes se desplaza|
|Leyer la linia actual |NVDA+flecha alto |NVDA+L |Leye la linia en que siga situau actualment lo cursor d'o sistema. Pretando-lo dos veces letreya la linia. Pretando-lo tres veces letreya la linia fendo servir descripcions de caracters.|
|Leyer la selección de texto actual |NVDA+mayus+flecha alto |NVDA+mayus+S |Leye qualsiquier texto seleccionau actualment|
|Anunciar lo formato de texto |NVDA+f |NVDA+f |Anuncia lo formato d'o texto en que siga situau actualment lo cursor. Pretando-lo dos veces amuestra la información en o modo de navegación|
|Frase siguient |alt+flecha abaixo |alt+flecha abaixo |Mueve lo cursor t'a  siguient frase y l'anuncia. (No suportau que en o Microsoft Word y l'Outlook)|
|Frase anterior |alt+flecha alto |alt+flecha alto |Mueve lo cursor ta l'anterior frase y l'anuncia. (No suportau que en o Microsoft Word y l'Outlook)|

Quan sigas en una tabla, as siguients teclas d'ordens tamién son disponibles:

| Nombre |Tecla |Descripción|
|---|---|---|
|Mover-se-ne t'a columna anterior |control+Alt+Flecha Cucha |Mueve o cursor d'o sistema t'a columna anterior (remanindo en a mesma ringlera)|
|Mover-se-ne t'a columna siguient |control+Alt+Flecha Dreita |Mueve o cursor d'o sistema t'a columna siguient (remanindo en a mesma ringlera)|
|Mover-se-ne t'a ringlera anterior |control+Alt+Flecha Alto |Mueve o cursor d'o sistema t'a ringlera anterior (remanindo en a mesma columna)|
|Mover-se-ne t'a ringlera siguient |control+Alt+Flecha Abaixo |Mueve o cursor d'o sistema t'a siguient ringlera (remanindo en a mesma columna)|

<!-- KC:endInclude -->

### Navegación d'Obchectos {#ObjectNavigation}

A mayor parti d'o tiempo, treballarás con aplicacions emplegando  ordens que muevan [o foco](#SystemFocus) y [o cursor](#SystemCaret).
Manimenos, a veces, podrías querer explorar l'aplicación actual u lo Sistema Operativo sin mover o foco u lo cursor.
Tamién podrías querer treballar con [obchectos](#Objects) que no pueden accedir-se normalment emplegando lo teclau.
En ixos casos, puetz emplegar a navegación d'obchectos.

A navegación d'obchectos te permite mover-te-ne entre y obtener información sobre [obchectos](#Objects) individuals.
Quan te'n muevas ta un obchecto, o NVDA l'anunciará de modo semellant a l'anunciau d'o foco d'o sistema.
Pa una traza de revisar tot o texto seguntes amaneixca en a pantalla, puetz fer servir en cuenta la [revisión de pantalla](#ScreenReview).

Mas que mover-se-ne dezaga y abant entre cada simple obchecto en o sistema, os obchectos s'agrupan hierarquicament.
Ixo significa que has de mover-te-ne dentro de qualques obchectos ta accedir a os obchectos que contiengan.
Por eixemplo, una lista contién elementos de lista, asinas has de mover-te-ne adintro d'a lista t'accedir t'os suyos elementos.
Si t'en yes moviu ta un elemento de lista, te'n puetz mover t'o suyo obchecto contenedor ta tornar ta la lista y allora pasar-la si lo deseyas.
Movendo-te-ne ta un elemento de lista que contién un obchecto te levará enta dezaga en a lista.
Allora puetz pasar d'a lista si deseyas accedir t'atros obchectos.
D'a mesma traza, en una barra de ferramientas que contién controls, has de mover-te-ne adintro d'a barra de ferramientas ta accedir t'os controls d'a mesma.

L'obchecto actualment en revisión se diz navegador d'obchectos.
Una vez que navegues enta un obchecto, puetz revisar o suyo conteniu emplegando as [ordens de revisión de texto](#ReviewingText) mientras se siga en [modo de revisión d'obchectos](#ObjectReview).
Quan lo [resaltau visual](#VisionFocusHighlight) siga enchegau, la localización d'o foco d'o sistema actual tamién se exposa visualment.
De traza predeterminada, o navegador d'obchectos se mueve de conchunta con o foco  d'o Sistema, encara que iste comportamiento puet activar-se y desactivar-se.

Para cuenta: Que lo braille siga a la navegación d'obchectos  puet configurar-se a traviés d'[o braille ancorau a](#BrailleTether).

Pa navegar por obchectos, fe servir as siguients ordens:

<!-- KC:beginInclude -->

| Nombre |Tecla Sobremesa |Tecla Portatil |Tactil |Descripción|
|---|---|---|---|---|
|Anunciar l'obchecto actual |NVDA+5 Teclau numerico |NVDA+control+i |no |Anuncia lo navegador d'obchectos actual. Pretando-lo dos veces letreya la información y pretando-lo 3 veces copia ixe nombre y valor de l'obchecto en o portafuellas.|
|Navegar ta l'obchecto contenedor |NVDA+8 teclau numerico |NVDA+mayus+i |eslizar ent'alto (Modo d'obchecto) |Navega t'o contenedor d'o navegador d'obchectos actual|
|Navegar ta l'obchecto anterior |NVDA+4 teclau numerico |NVDA+control+j |eslizar t'a cucha (modo d'obchecto) |Navega ta l'obchecto dreitament antis de l'actual navegador d'obchectos|
|Navegar t'o siguient obchecto |NVDA+6 teclau numerico |control+NVDA+l |eslizar t'a dreita (modo d'obchecto) |Navega ta l'obchecto dreitament dimpués de l'actual navegador d'obchectos|
|Navegar t'o primer obchecto conteniu |NVDA+2 teclau numerico |NVDA+mayus+coma |eslizar ent'abaixo (modo d'obchecto) |Navega t'o primer obchecto conteniu por l'actual navegador d'obchectos|
|Navegar t'a fin d'o foco |NVDA+Menos teclau numerico |NVDA+Retroceso |no |Navega ta l'obchecto que tien actualment lo foco d'o sistema, y tamién coloca lo cursor de revisión en a posición d'o cursor d'o Sistema, si s'amuestra|
|Activar l'actual navegador d'obchectos |NVDA+Intro teclau numerico |NVDA+Intro |dople toque |Activa l'actual navegador d'obchectos (semellant a fer clic con o churi u pretar l'espacio quan tien lo foco d'o sistema)|
|Mover lo foco d'o Sistema ta l'actual navegador d'obchectos |NVDA+mayus+Menos teclau numerico |NVDA+mayus+retroceso |no |pretau una vez Mueve lo foco d'o Sistema t'o navegador d'obchectos actual, pretau dos veces mueve lo cursor d'o sistema t'a posición d'o cursor de revisión|
|Anunciar la ubicación d'o cursor de revisión |NVDA+Suprimir teclau numerico |NVDA+suprimir |no |Anuncia información arredol d'a ubicación d'o  texto u obchecto en o cursor de revisión.  Por eixemplo ixo puet incluir o porcentache  a traviés d'o documento a distancia dende lo canto d'a pachina u  la posición exacta en a pantalla. En pretar-lo dos veces puet anunciar-se-ne mas información.|
|Mover lo cursor de revisión t'a barra d'estau |garra |garra |garra |Anuncia la barra d'estau  si lo NVDA en troba una. Tamién mueve lo navegador d'obchectos ta ixa ubicación.|

<!-- KC:endInclude -->

nota: Las teclas d'o teclau numerico requieren que lo bloueryo numerico siga desenchegau pa funcionar apropiadament.

### Revisando Texto {#ReviewingText}

Lo NVDA te permite leyer lo conteniu d'a [pantalla](#ScreenReview), [documento actual](#DocumentReview) u l'[obchecto actual](#ObjectReview) por caracters, parolas u linias.
Isto ye prencipalment util en puestos (incluindo la consola d'o Dos d'o Windows) en do no bi haiga existencia d'un  [cursor d'o sistema](#SystemCaret).
Por eixemplo, lo ferías servir pa revisar lo texto d'un luengo mensache d'información en un dialogo.

En que se mueve lo cursor de revisión, lo cursor d'o Sistema no lo sigue, asinas puetz revisar texto sin perder a posición d'edición.
Manimenos, de traza predeterminada, en que lo cursor d'o Sistema se mueve lo cursor de revisión lo sigue.
Ixo puet enchegar-se y desenchegar-se.

Para cuenta: Que lo braille siga a lo cursor de revisión  puet configurar-se a traviés d'[o braille ancorau a](#BrailleTether).

Las siguients ordens son disponibles pa revisión de texto: 
<!-- KC:beginInclude -->

| Nombre |Tecla Sobremesa |Tecla Portatil |Tactil |Descripción|
|---|---|---|---|---|
|mover-se t'a linia superior en revisión |mayus+7 teclau numerico |NVDA+7 |no |Mueve lo cursor de revisión t'a linia superior d'o texto|
|Mover-se t'a linia anterior en revisión |7 teclau numerico |NVDA+u |eslizar enta alto (modo de texto) |Mueve lo cursor de revisión t'a linia anterior de texto|
|Anunciar la linia actual en revisión |8 teclau numerico |NVDA+i |no |Anuncia la linia actual de texto en do siga colocau lo cursor de revisión. Pretando-lo dos veces letreya la linia, Pretando-lo tres veces letreya la linia emplegando descripcions de caracters.|
|Mover-se t'a linia siguient en revisión |9 teclau numerico |NVDA+u |eslizar enta abaixo (modo de texto) |Mueve lo cursor de revisión t'a linia siguient de texto|
|Mover-se t'a linia inferior en revisión |mayus+9 teclau numerico |NVDA+9 |no |Mueve lo cursor de revisión t'a linia inferior de texto|
|Mover-se t'a parola anterior en revisión |4 teclau numerico |NVDA+j |eslizar con 2 didos t'a cucha (modo de texto) |Mueve lo cursor de revisión t'a parola anterior en o texto|
|Anunciar la parola actual en revisión |5 teclau numerico |NVDA+k |no |Anuncia la parola actual en o texto en do siga colocau lo cursor de revisión. Pretando-lo dos veces letreya la parola, pretando-lo tres veces letreya la parola emplegando descripcions de caracters.|
|Mover-se t'a siguient parola en revisión |6 teclau numerico |NVDA+l |desplazar con 2 didos ta la dreita (modo de texto) |Mueve lo cursor de revisión t'a siguient parola en o texto|
|mover-se ta l'inicio d'a linia en revisión |mayus+1 teclau numerico |NVDA+mayus+u |no |Mueve lo cursor de revisión t'o comienzo d'a linia actual en o texto|
|Mover-se t'o caracter anterior en revisión |1 teclau numerico |NVDA+m |eslizar t'a cucha (modo de texto) |Mueve lo cursor de revisión t'o caracter anterior en a linia actual en o texto|
|Anunciar lo caracter actual en revisión |2 teclau numerico |NVDA+coma |no |Anuncia lo caracter actual en a linia de texto en do siga colocau lo cursor de revisión. Pretando-lo dos veces anuncia una descripción u eixemplo d'ixe caracter. Pretando-lo tres veces anuncia la valor numerica d'o caracter en decimal y hexadecimal.|
|Mover-se t'o siguient caracter en revisión |3 teclau numerico |NVDA+punto |eslizar t'a dreita (modo de texto) |Mueve lo cursor de revisión t'o siguient caracter en a linia actual de texto|
|Mover-se t'a fin d'a linia en revisión |mayus+3 teclau numerico |NVDA+mayus+u |no |Mueve o cursor de revisión t'a fin d'a linia actual de texto|
|Leyer-lo tot con revisión |Mas teclau numerico |NVDA+mayus+Flecha abaixo |eslizar con 3 didos enta abaixo (modo de texto) |Leye dende la posición actual d'o cursor de revisión, movendo-lo seguntes baixa|
|Seleccionar y copiar dende lo cursor de revisión |NVDA+f9 |NVDA+f9 |no |Prencipia lo proceso de selección y copia dende la posición actual d'o cursor de revisión. L'acción actual no se leva a cabo dica que digas a lo NVDA dó ye lo final de rango de texto|
|Seleccionar y copiar en o cursor de revisión |NVDA+f10 |NVDA+f10 |no |En a primer pretada se copia lo texto dende la posición previament  establida como marcador d'inicio dica la posición actual d'o cursor de revisión incluindo-la.  Dimpués de pretar ista tecla una segunda vez se copiará lo texto  en o portafuellas d'o Windows|
|Mover-se t'a marca d'inicio pa copiar en a revisión |NVDA+shift+f9 |NVDA+shift+f9 |no |Mueve lo cursor de revisión t'a posición achustada previament como marca d'inicio pa copiar|
|Anunciar lo formato d'o texto |NVDA+mayus+f |NVDA+mayus+f |no |Informa d'o formato d'o texto en que siga colocau actualment lo cursor de revisión. Pretando-lo dos veces amuestra la información en o modo de navegación|
|Anunciar lo remplazo d'o simbolo actual |Garra |Garra |Garra |Diz lo simbolo en do siga colocau lo cursor de revisión. Pretau dos veces, amuestra lo simbolo y lo texto emplegau pa decir-lo en o modo de navegación.|

<!-- KC:endInclude -->

Para cuenta: Las teclas d'o teclau numerico requieren que lo bloqueyo numerico siga desenchegau pa funcionar apropiadament.

Una buena traza de remerar os comandos de texto basicos de revisión quan s'emplega o disenyo d'escritorio ye pensar en ells como en una quadricula de tres por tres, do d'a parti superior t'a inferior ye a linia, parola y caracter y de cucha ta dreita ye anterior, actual y siguient .	
A distribución ye ilustrada d'a siguient traza:

|Linia anterior |Linia actual |Linia siguient|
|Parola anterior |Parola actual |Parola siguient|
|caracter anterior |caracter actual |caracter siguient|

### Modos de Revisión {#ReviewModes}

As ordens de revisión de texto d'o NVDA pueden revisar o conteniu adintro d'o navegador d'obchectos actual, documento actual, u pantalla, pendendo d'o modo de revisión seleccionau.
Os modos de revisión son un  reemplazo ta l'antigo concepto de revisión plana d'o NVDA.

As ordens que siguen cambean entre os modos de revisión:
<!-- KC:beginInclude -->

| Nombre |Tecla Escritorio |Tecla Portatil |Tactil |Descripción|
|---|---|---|---|---|
|Cambiar t'o  modo de revisión siguient |NVDA+7 teclau numerico |NVDA+rePach |eslizar 2 didos enta alto |cambea t'o siguient modo de revisión disponible.|
|Cambiar t'o modo de revisión anterior |NVDA+1 teclau numerico |NVDA+avPach |eslizar 2 didos enta baixo |Cambea ta l'anterior modo de revisión disponible.|

<!-- KC:endInclude -->

#### Revisión d'Obchectos {#ObjectReview}

Mientras se siga en o modo de revisión d'obchectos, nomás podrás revisar o conteniu de l'actual [navegador d'obchectos](#ObjectNavigation).
Pa obchectos tals como campos d'edición u atros controls basicos de documento, Ixo será cheneralment o conteniu de texto.
Pa atros obchectos, ixo será o nombre y u valor.

#### Revisión de Documentos {#DocumentReview}

Quan o [navegador d'obchectos](#ObjectNavigation) siga adintro d'un documento en o modo de navegación (p. eix.: pachina web) u unatro documento complexo que contienga muitos obchectos (p. eix.: documentos de Lotus Symphony), ye posible cambiar t'o modo de revisión de documentos.
O modo de revisión de documentos te permite revisar o texto d'o documento entero.

Quan se cambeye dende revisión d'obchectos ta revisión de documentos, o cursor de revisión se coloca en o documento en a posición d'o navegador d'obchectos.
A lo mover-se-ne por o documento con os comandos de revisión, o navegador d'obchectos s'esviella automaticament ta l'obchecto que se troba en a posición  actual d'o cursor de revisión.

Para cuenta que o NVDA cambiará t'a revisión de documentos dende a revisión d'obchectos automaticament quan te muevas por documentos en o modo de navegación.

#### Revisión de Pantalla {#ScreenReview}

O modo de revisión de pantalla te permite revisar o texto tal como amaneixca visualment en a pantalla adintro de l'aplicación actual.
Isto ye semellant a la funcionalidat de revisión de pantalla u cursor d'o churi en muitos atros lectors de pantalla ta Windows.

 Quan se cambea t'o modo de revisión de pantalla, o cursor de revisión se coloca en a posición de pantalla de l'actual [navegador d'obchectos](#ObjectNavigation).
 En que nos movamos por a pantalla con as ordens de revisión, o navegador d'obchectos s'esviella automaticament ta l'obchecto trobau en a posición d'a pantalla d'o cursor de revisión.

 Para cuenta que en qualques aplicacions modernas, o NVDA podría no veyer belún u tot o texto disponible en a pantalla, a causa de l'uso d'as recients tecnolochías de dibuixo en pantalla que son imposibles de suportar en istos intes.

### Navegando con o churi {#NavigatingWithTheMouse}

En que mueves o churi, o NVDA informa de traza predeterminada d'o texto que siga dreitament baixo o puntero d'o mesmo, seguntes se mueva sobre ell. 
Do siga suportau, o NVDA leyerá a valor d'un paragrafo de texto, encara que qualques controls solament podrán leyer-se por linias.

O NVDA tamién puet configurar-se ta anunciar a mena de control u obchecto sobre o qual siga actualment o churi seguntes se mueva (p. eix.: lista, botón etc.). 
Isto podrá estar util ta usuarios ciegos totals quan qualques veces o texto no siga prou.

O NVDA proporciona un modo ta que os usuarios comprendan do ye o churi respective a las dimensions d'a pantalla, fendo sonar as coordenadas actuals d'o churi seguntes l'audio chufle. 
Contra mas alto siga o churi en a pantalla, mas alto será o ton en os chuflius. 
Contra mas enta la cucha u enta la dreita siga o churi en a pantalla, mas t'a cucha u t'a dreita pareixerá ir o son (asumindo que l'usuario tienga altavoces estereofonicos).

Istas caracteristicas extra d'o churi no son activadas de traza predeterminada en o NVDA. 
Si deseyas quitar partiu d'ellas, puetz configurar-las dende la categoría d'[opcions d'o churi](#MouseSettings), d'o dialogo d'[opcions d'o NVDA](#NVDASettings) que se troba en o menú de preferencias d'o NVDA.

Si bien un churi fisico u un trackpad se podrían emplegar pa navegar con o churi, o NVDA furneix bellas ordens relacionadas con o churi:
<!-- KC:beginInclude -->

| Nombre |Tecla sobremesa |Tecla Portatil |Toque |Descripción|
|---|---|---|---|---|
|Clic d'o botón cucho d'o churi |Dividir teclau numerico |NVDA+Flecha cucha |Denguno |Fa clic en o botón cucho d'o churi una vez. Lo común dople clic puet levar-se a cabo pretando ista tecla dos veces en rapida succesión|
|Blocar lo botón cucho d'o churi |mayus+Dividir teclau numerico |NVDA+mayus+Flecha cucha |Denguno |Mantién preto lo botón cucho d'o churi. Preta-lo de nuevo pa liberar-lo. Pa arrocegar lo churi,  preta ista tecla pa blocar lo botón cucho y allora mueve lo churi fisicament u fe servir belatra d'as ordens d'enrutamiento d'o churi|
|Clic d'o botón dreito d'o churi |Multiplicar teclau numerico |NVDA+flecha dreita |Tocar y tener |Fa Clic en o botón dreito d'o churi una vez, por un regular emplegau pa ubrir lo menú contextual en a ubicación d'o churi.|
|Blocar lo botón dreito d'o churi |mayus+Multiplicar teclau numerico |NVDA+mayus+flecha dreita |Denguno |Mantién preto lo botón dreito d'o churi. Preta unatra vez pa liberar-lo. Pa arrocegar o churi,  preta ista tecla  pa blocar lo botón dreito y allora mueve o churi fisicament u fe servir belatra d'as ordens d'enrutamiento d'o churi|
|Mover lo churi t'o navegador d'obchectos actual |NVDA+Dividir teclau numerico |NVDA+mayus+f9 |Denguno |Mueve lo churi t'a posición d'o navegador d'obchectos actual y lo cursor de revisión|
|navegar ta l'obchecto baixo lo churi |NVDA+Multiplicar teclau numerico |NVDA+mayus+f10 |Denguno |Mete lo navegador d'obchectos en l'obchecto localizau en a posición d'o churi|

<!-- KC:endInclude -->

## Modo de navegación {#BrowseMode}

Os documentos complexos de nomás lectura, tals como as pachinas Web, son representaus en o NVDA con un modo de navegación. 
Ixo inclui documentos en as siguients aplicacions:

* Lo Mozilla Firefox
* Lo Microsoft Internet Explorer
* Lo Mozilla Thunderbird
* Los mensaches en HTML d'o Microsoft Outlook
* Lo Google Chrome
* Lo Microsoft Edge
* L'Adobe Reader
* Lo Foxit Reader
* Los libros suportaus en l'Amazon Kindle pa PC 

Lo modo de navegación tamién ye disponible opcionalment pa los documentos d'o Microsoft Word.

En o modo de navegación, lo conteniu d'o documento se fa disponible por meyo d'una representación plana de conteniu tal como una pachina Web, por la qual te puetz mover con as teclas de cursor. 
Todas las teclas d'ordens d'o [cursor d'o sistema](#SystemCaret) d'o NVDA funcionarán en iste modo; p. eix.: leyer-lo tot, anunciar o formato, ordens de navegación de tabla, etc.
Quan lo [resaltau visual](#VisionFocusHighlight) siga enchegau, la localización d'o foco d'o sistema actual tamién se exposa visualment.
La información tal como si o texto ye un vinclo,  capitero, etc. s'anuncia de conchunta con o texto seguntes te muevas.

A veces, amenesterás interactuar dreitament con controls en istos documentos.
+Por eixemplo, amenesterás fer isto ta campos de texto editable y listas tal que puedas escribir caracters y emplegar as teclas de cursor ta treballar con o control.
Fe isto ta cambiar t'o modo de foco, an quasi todas as teclas se pasen a o control.
Quan se ye en modo Navegación, por defecto, o NVDA cambiará automaticament t'o modo de foco si tabulas ta u fas clic sobre un control en particular que lo requiera.
En cambeo, tabulando u fendo clic sobre un control que no requiera o modo de foco retornará t'o modo de navegación.
Tamién puetz pretar l'intro u lo espacio ta cambiar t'o modo de foco en controls que lo requieran.
Pretando lo escape tornarás t'o modo de navegación.
Amás, puetz forzar manualment o modo de foco, dimpués remanirá efectivo dica que trigues desactivar-lo.

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Commutar os modos de navegación/foco |NVDA+espacio |Commuta entre o modo de foco y o modo de navegación|
|Salir d'o modo de foco |escape |Cambea t'o modo de navegación si o modo de foco anteriorment heba cambiau automaticament|
|Refrescar o documento en o modo de navegación |NVDA+f5 |Recarga o conteniu d'o documento actual (util si bells contenius pareixen estar desapareixius d'o documento. No disponible en o Microsoft Word y l'Outlook)|
|Mirar |NVDA+control+f |Desplega un dialogo en que puetz tecliar bell texto pa trobar en  o documento actual. Mira-te [mirar texto](#SearchingForText) pa mas información.|
|Mirar a siguient |NVDA+f3 |Troba la siguient  ocurrencia d'o texto en o documento que mirés anteriorment|
|Mirar l'anterior |NVDA+mayus+f3 |Troba la ocurrencia anterior d'o texto en o documento que mirés anteriorment|
|ubrir a descripción luenga |NVDA+d d| Ubre una finestra nueva que contién una descripción luenga ta l'elemento sobre o qual sigas si en tien una.|

<!-- KC:endInclude -->

### Navegación con una sola letra {#SingleLetterNavigation}

Mientras se siga en o modo de navegación, ta una navegación mas rapida o NVDA tamién proporciona teclas d'un solo caracter ta blincar ta bells campos en o documento.
Note-se que no totz istos  comandos son suportaus en todas as menas de documento.

<!-- KC:beginInclude -->
As siguients teclas por ellas mesmas blincan t'o siguient campo, con a tecla mayus blincan ta l'anterior campo.

* h: Capitero
* l: Lista
* i: Elemento de lista
* t: Tabla
* k: Vinclo
* n: Texto que no ye vinclo
* f: Campo de formulario
* u: Vinclo no visitau
* v: Vinclo visitau
* e: Campo d'edición
* b: Botón
* x: Caixeta de verificación
* c: Quadro combinau
* r: Botón d'opción
* q: Cita
* s: Deseparador
* m: Bastida
* g: Grafico
* d: Zona
* o: Obchecto integrau (reproductor d'audio u vidio, aplicación, dialogo, etc.)
* 1 ta 6: Capiters d'1 ta 6 respectivament
* a: Anotación (comentario, revisión d'editor, etc.)
* w: error d'ortografía

Pa mover-te-ne t'o comienzo u final d'elementos contenedors tals como listas y tablas:

| nombre |tecla |descripción|
|---|---|---|
|Mover-se-ne t'o comienzo d'un contenedor |mayus+coma |Se mueve t'o comienzo d'o contenedor (lista, tabla etc.) an siga situau o cursor|
|Mover-se-ne t'a fin d'o contenedor |coma |Se mueve t'a fin d'o contenedor (lista, tabla etc.) an siga situau o cursor|

<!-- KC:endInclude -->

Bellas aplicacions tals como lo Gmail, o Twitter y o Facebook fan servir letras sueltas como teclas d'alcorce.
Si quiers fer servir-ne sin deixar d'estar capable de fer servir as teclas de cursor ta leyer en o modo de navegación puetz desenchegar temporalment as teclas de navegación d'una sola letra d'o NVDA.
<!-- KC:beginInclude -->
Pa enchegar u desenchegar a navegación d'una sola letra en o documento actual preta NVDA+mayus+espacio.
<!-- KC:endInclude -->

### La Lista d'Elementos {#ElementsList}

La lista d'elementos proporciona acceso ta una lista de quantos vinclos, capiters, campos de formulario,  botons u zonas en a pachina. 
Por eixemplo en os navegadors web a lista d'elementos puet incluir vinclos, capiters u zonas.
Los botons d'opción te permiten cambiar entre las diferents menas d'elementos. 
Se Proporciona tamién un campo d'edición en o dialogo o qual te permite filtrar a lista t'aduyar-te a buscar un elemento en particular en a pachina. 
Una vez haigas trigau un elemento, puetz emplegar os botons proporcionaus en o dialogo ta mover-te-ne ta, u activar, ixe elemento.
<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Lista d'elementos d'o modo de navegación |NVDA+f7 |Desplega a lista d'elementos que contién vinclos, capiters y zonas ARIA d'o documento actual|

<!-- KC:endInclude -->

### Mirar texto {#SearchingForText}

Iste dialogo te permite mirar termins en o documento actual.
En o campo "Tecleya lo texto que deseyes trobar", puede calar-se-bi lo texto pa trobar.
La caixeta de verificación "sensible a las mayusclas" fa que la busca considere letras en mayusclas y en minusclas de modo diferent.
Por eixemplo, con "sensible a las mayusclas" trigada puetz trobar "NV Access" pero no pas "nv access".
Fe servir las siguients teclas pa rializar  buscas:
<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Mirar texto |NVDA+control+f |Ubre lo dialogo de mirar|
|Mirar lo siguient |NVDA+f3 |Mira la siguient ocurrencia d'o termin actual mirau|
|Mirar l'anterior |NVDA+mayus+f3 |Mira la ocurrencia anterior d'o termin actual mirau|

<!-- KC:endInclude -->

### Obchectos Integraus {#ImbeddedObjects}

Las pachinas pueden incluir conteniu enriquiu emplegando tecnolochías tals como l'Oracle Java u l'HTML 5, asinas como aplicacions y dialogos. 
Do istas se troben en un modo de Navegación, o NVDA anunciará "obchecto integrau", "aplicación" u "dialogo", respectivament.
Tu puetz mover-te-ne a escape t'a ells fendo servir as teclas de navegación d'una sola letra pa obchectos integraus; o y mayus+o.
Pa interactuar con ixos obchectos puetz pretar l'intro en ells.
Si ye accesible, allora puetz tabular por ells y interactuar como con qualsiquier atra aplicación. 
Se proporciona una orden de teclau ta tornar t'a pachina orichinal que contién a l'obchecto integrau.
<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Mover-se-ne t'o conteniu d'o modo de navegación |NVDA+control+espacio |Mueve o foco difuera de l'actual obchecto integrau y lo mete adintro d'o documento que lo contién|

<!-- KC:endInclude -->

## Leyer lo conteniu Matematico {#ReadingMath}

Fendo servir lo MathPlayer 4 de Design Science, lo NVDA puet leyer y navegar interactivament  por lo conteniu matematico suportau.
Ixo requier que lo MathPlayer 4 siga instalau en l'ordinador.
Lo MathPlayer ye disponible como una descarga franca dende: https://www.dessci.com/en/products/mathplayer/

Lo NVDA suporta las siguients menas de conteniu matematico:

* MathML en o Mozilla Firefox, o Microsoft Internet Explorer y o Google Chrome.
* Design Science MathType en o Microsoft Word y PowerPoint.
Lo MathType ha d'estar instalau pa que ixo marche. 
La versión de preba en ye prou.
Puet descargar-se dende https://www.dessci.com/en/products/mathtype/
* MathML en l'Adobe Reader.
Nota que isto no ye un estandar oficial encara, allora no bi ha actualment software disponible publicament que pueda producir iste conteniu.
* Math en o Kindle pa PC pa os libros con matematicas accesibles.

En leyer un documento, o NVDA charrará qualsiquier conteniu matematico suportau do se produzca.
Si yes fendo servir una linia Braille, tamién s'amostrará en braille.

### Navegación interactiva {#InteractiveNavigation}

Si yes treballando prencipalment con a fabla, en a mayoría d'os casos ye prebable que deseyes examinar a expresión en segmentos mas chicotz en cuenta d'escuitar toda la expresión de vez.

Si yes en o modo de navegación, puetz fer ixo movendo lo cursor t'o conteniu matematico y pretando l'intro.

Si no yes en o modo de navegación:

1. mover o cursor de revisión t'o conteniu matematico .
Por defecto, o cursor de revisión sigue a lo cursor d'o sistema, allora puetz fer servir usualment  o cursor d'o sistema ta mover-lo t'o conteniu deseyau.
1. allora, activar o siguient comando:

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Interactuar con conteniu matematico |NVDA+alt+m |Empecipia a interacción con o conteniu matematico.|

<!-- KC:endInclude -->

En iste punto, puetz fer servir os comandos d'o MathPlayer tals como as teclas de flecha ta explorar a expresión.
Por eixemplo, puetz mover-te-ne a traviés d'a expresión con as teclas de flecha cucha y dreita y ampliar adintro d'una parti d'a expresión como una  truesa fendo servir a tecla de flecha abaixo.
Por favor mira-te [la documentación d'o MathPlayer sobre os comandos de navegación:](https://www.dessci.com/en/products/mathplayer/navigation_commands.htm) pa mas información.

Quan deseyes tornar t'o documento, simplament preta la tecla escape.

A veces lo conteniu matematico puet amostrar-se como un botón u belatro tipo d'elemento que en enchegar-se puet amostrar un dialogo u mas información relacionada con a formula.
Pa enchegar lo botón u lo elemento que contiene la formula, preta ctrl+intro.

## Braille {#Braille}

Si tiens una linia braille lo NVDA puet amostrar información en braille.
Si la tuya linia braille tien un teclau tipo Perkins, tamién puetz ficar-bi braille contraito u no contraito.
Tamién puet amostrarse lo braille en a pantalla fendo servir lo [visor d'o braille](#BrailleViewer) en cuenta de, u de vez, fendo servir una linia braille fisica.

Por favor, mira-te la sección de [linias Braille suportadas](#SupportedBrailleDisplays) pa información  arredol d'as linias braille suportadas.
Ixa sección tamién contién información sobre qué linias son compatibles con a función de detección automatica de linias braille d'o NVDA.
Puetz configurar o braille fendo servir la [categoría d'opcions d'o braille](#BrailleSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings).

### Abreviaduras braille de tipo de control, estau y puntos de referencia {#BrailleAbbreviations}

Con a finalidat de tener a mayor cantidat d'información posible en una pantalla braille s'ha definiu as siguients abreviaduras pa endicar a mena de control y estaus asinas como puntos de referencia.

| Abreviadura |Tipo de Control|
|---|---|
|ady |globo d'aduya|
|apl |aplicación|
|art |articlo|
|barb |botón d'envista d'arbol|
|bardsp |barra de desplazamiento|
|barfer |barra de ferramientas|
|barprg |barra de progreso|
|barst |barra d'estau|
|bmn |barra de menú|
|btcom |botón conmutable|
|btdiv |botón divisor|
|btdsp |botón desplegable|
|btmn |botón de menú|
|btn |botón|
|btno |botón d'opción|
|btrot |botón rotatorio|
|cN |numero de columna de tabla n, -. eix. c1, c2.|
|CaN |capitero de libel n, p. eix.: h1, h2.|
|ce |campo de texto editable|
|cecl |campo editable de  clau|
|cit |cita|
|cons |consello|
|ctrtab |control tab|
|cv |caixeta de verificación|
|dlg |dialogo|
|doc |documento|
|earb |envista d'arbol|
|elear |elemento d'envista d'arbol|
|elmn |elemento de menú|
|fig |figura|
|fns |finestra|
|int |obchecto integrau|
|gra |grafico|
|grp |grupo|
|lb N |elemento d'envista en arbol que tien un libel hierarquico N||
|lst |lista|
|mrc |conteniu marcau|
|mnu |menú|
|notaf |nota final|
|notap |nota a lo piet|
|pdr |punto de referencia|
|pnl |panel|
|qco |quadro combinau|
|rN |numero de ringlera de tabla n, p.eix. r1, r2.|
|secc |sección|
|tb |tabla|
|term |terminal|
|ttl |titol|
|vnc |vinclo|
|vncv |vinclo visitau|
|⠤⠤⠤⠤⠤ |separador|

Los siguients indicadors d'estau  tamién son definius:

| Abreviadura |Estau de Control|
|---|---|
|... |amostrau quan un obchecto suporta autocompletau|
|⢎⣿⡱ |Amostrau quan bell obchecto (p. eix. bell botón conmutable) ye pretau|
|⢎⣀⡱ |Amostrau quan bell obchecto (p. eix. bell botón conmutable) no ye pretau|
|⣏⣿⣹ |amostrau quan un obchecto (p. eix.: una caixeta de verificación) ye marcau|
|⣏⣸⣹ |amostrau quan un obchecto (p. eix.: una caixeta de verificación) ye  parcialment marcau|
|⣏⣀⣹ |amostrau quan un obchecto (p. eix.: una caixeta de verificación) no ye marcau|
|- |amostrau quan un obchecto (p. eix.: un elemento d'anvista d'arbol) ye plegable|
|+ |amostrau quan un obchecto (p. eix.: un elemento d'anvista d'arbol) ye desplegable|
|*** |Amostrau quan se troba un control u documento protechiu|
|clc |amostrau quan un obchecto ye clicable|
|cmnt |amostrau quan bi ha un comentario pa una celda de fuella de calculo u pa un troz de texto en un documento|
|frml |amostrau quan bi ha una formula en una celda de fuella de calculo|
|invaliu |amostrau quan s'ha feito una dentrada invalida|
|descl |amostrau quan un obchecto (por un regular un grafico) tien una descripción larga|
|mln |amostrau quan un campo de texto editable permite d'escribir multiples linias de texto como os campos de comentario en pachinas web|
|req |amostrau quan se troba un campo de formulario requiesto|
|nl |amostrau quan un obchecto (p. eix.: un campo de texto editable) ye de nomás lectura|
|sel |amostrau quan un obchecto ye seleccionau|
|nsel |amostrau quan un obchecto no ye seleccionau|
|ord asc |amostrau quan un obchecto ye ordinau ascendentment|
|ord desc |amostrau quan un obchecto ye ordinau descendentment|
|submnu |amostrau quan un obchecto tien un desplegable (normalment un submenú)|

Finalment, s'ha definiu as siguients abreviaduras pa puntos de referencia:

| Abreviadura |Punto de referencia|
|---|---|
|anc |anuncio|
|inff |información de conteniu|
|cmpl |complementario|
|form |formulario|
|pren |prencipal|
|nav |navegación|
|bsc |busca|
|rchn |rechión|

### Dentrada Braille {#BrailleInput}

Lo NVDA suporta a dentrada de braille  contraito y no contraito a traviés d'un teclau braille.
Puetz trigar a tabla de transcripción emplegada pa transcribir o braille en o texto fendo servir la opción de [tabla de dentrada](#BrailleSettingsInputTable) en a categoría d'o braille en o dialogo d'[opcions d'o NVDA](#NVDASettings).

Quan se siga emplegando braille no contraito, o texto se fica tant luego como s'introduz.
Quan se siga emplegando braille contraito, o texto se fica en pretar o espacio u l'intro a la fin d'una parola.
Para cuenta que la transcripción puet refleixar nomás la parola braille que sigas escribindo y no se pue considerar lo texto existent.
Por eixemplo, si yes emplegando un codigo braille que escomencipia os numers con un sinyal de numero y pretas o recule pa mover-te-ne t'o final d'un numero, te fará falta tecliar o sinyal de numero de nuevas pa ficar-bi numers adicionals.

<!-- KC:beginInclude -->
En pretar lo punto 7 borras la zaguer celda u caracter ficau.
Lo punto 8 transcribe qualsiquier dentrada braille y preta la tecla intro.
Pretando los puntos 7 y 8 transcribe qualsiquier dentrada braille, pero sin adhibir-bi un espacio u pretando l'intro.
<!-- KC:endInclude -->

## Visión {#Vision}

Tot y que lo NVDA ye endrezau prencipalment a personas ciegas u con problemas de visión que fagan servir prencipalment la voz y/u lo braille pa maniar un ordinador, tamién ufre funcions incorporadas pa cambiar lo conteniu d'a pantalla.
Adintro d'o NVDA, ixa aduya visual se denomina furnidor de millora d'a visión.

Lo NVDA ufre quantos furnidors de millora d'a visión incorporaus que se describe contino.
Se puede proporcionar furnidors adicionals de millora d'a visión en [complementos d'o NVDA](#AddonsManager).

Las opcions d'a visión d'o NVDA pueden cambiar-sen en a [categoría de visión](#VisionSettings) d'o dialogo d'[Opcions d'o NVDA](#NVDASettings).

### Resaltau visual {#VisionFocusHighlight}

Lo resaltau visual puede aduyar a identificar las posicions d'o [foco d'o sistema](#SystemFocus), [d'o navegador d'obchectos](#ObjectNavigation) y [d'o modo de navegación](#BrowseMode).
Ixas posicions se resaltan con un rectanglo de color.

* L'azul soliu resalta una combinación d'a localización d'o navegador d'obchectos y d'o foco d'o sistema (eix.: porque [lo navegador d'obchectos siga a lo foco d'o sistema](#ReviewCursorFollowFocus)).
* L'azul discontino resalta nomás l'obchecto d'o foco d'o sistema.
* Lo roso soliu resalta nomás lo navegador d'obchectos.
* L'amariello soliu resalta lo cursor virtual emplegau en o modo de navegación (en do no bi ha cursor fisico como en os navegadors web).

Quan lo resaltau visual ye enchegau en a [categoría de visión](#VisionSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings), [puetz cambiar si deseyas u no pas resaltar lo cursor d'o foco, d'o navegador d'obchectos u d'o modo de navegación](#VisionSettingsFocusHighlight).

### Cortina de Pantalla {#VisionScreenCurtain}

Como usuario ciego u con problemas de visión, a ormino no ye posible u necesario veyer lo conteniu d'a pantalla.
Amás, puede estar dificil asegurar-te que no bi haiga beluno mirando por alto d'o huembro tuyo.
Pa ixa situgación, lo NVDA contiene una caracteristica clamada "cortina de pantalla" que puede enchegar-se pa fer que la pantalla siga negra.

Puetz enchegar la Cortina de Pantalla en a [categoría de visión](#VisionSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings).

Quan la cortina de pantalla ye enchegada bellas fainasbasadas directament en lo que amaneix en a pantalla como la rialización de l'[OCR](#Win10Ocr) u prener una captrua de pantalla no se puet aconseguir.

A causa d'un cambeo en l'API de magnificación d'o Windows, la cortina de pantalla ha d'estar esviellada pa suportar las versions mas nuevas d'o Windows.
Fe servir lo NVDA 2021.2 pa activar la cortina de pantalla con o Windows 10 21H2 (10.0.19044) u superiors.
Por propositos de seguridat, en fer servir una nueva versión d'o Windows, obtiene confirmación visual de que la cortina de pantalla fa la pantalla negra de raso.

## Reconoixencia de Contenius {#ContentRecognition}

Quan os autors no furnen prau información pa que un usuario de lector de pantalla determine o conteniu de bella cosa, pueden fer-se servir bellas ferramientas pa mirar de reconoixer o conteniu dende una imachen.
Lo NVDA suporta la funcionalidat de reconoixencia optica de caracters (OCR) integrada en o Windows 10 y superiors pa reconoixer texto dende imachens.
Puet furnir-se reconoixedors de conteniu adicionals en complementos d'o NVDA.

Quan emplegues un comando de reconoixencia de conteniu, o NVDA reconoix conteniu dende o [navegador d'obchectos](#ObjectNavigation) actual.
Por defecto, lo navegador d'obchectos sigue a lo foco d'o sistema u a lo cursor d'o modo de navegación, asinas puetz mover normalment o foco u lo cursor d'o modo de navegación do deseyes.
Por eixemplo, si mueves  o cursor d'o modo de navegación ta un grafico, a reconoixencia reconoixerá o conteniu dende o grafico por defecto.
Por lo tanto, podrás deseyar emplegar a navegación d'obchectos dreitament pa, por eixemplo, reconoixer o conteniu de toda una finestra d'aplicación.

Una vez que a reconoixencia se complete, o resultau se presentará en un documento similar a lo modo de navegación, permitindo-te leyer a información con as teclas d'o cursor, etc.
Pretando l'intro u lo espacio activará (normalment un clic) o texto en o cursor si ye posible.
Pretando lo escape escartas o resultau d'a reconoixencia.

### OCR d'o Windows {#Win10Ocr}

Lo Windows 10 y superiors incluyen un OCR pa muitos idiomas.
Lo NVDA puet fer-lo servir pa reconoixer texto dende imachens u aplicacions inaccesibles.

Puetz configurar l'idioma a emplegar pa la reconoixencia de texto en a [categoría d'OCR d'o Windows](#Win10OcrSettings)d'o dialogo d'[opcions d'o NVDA](#NVDASettings).
Puet instalar-se-bi idiomas adicionals ubrindo lo menú d'inicio, esleyindo configuración, seleccionando hora y Idioma -> rechión y Idioma y dimpués esleyindo adhibir un Idioma.

L'OCR d'o Windows puet estar en parti u de raso incompatible con as [milloras d'a visión d'o NVDA](#Vision) u atras aduyas visuals externas. Puetz haber de desenchegar ixas aduyas antis de no proceder con un reconoiximiento.

<!-- KC:beginInclude -->
Pa reconoixer lo texto en l'actual navegador d'obchectos fendo servir l'OCR d'o Windows, preta NVDA+r.
<!-- KC:endInclude -->

## Caracteristicas Especificas pa aplicacións {#ApplicationSpecificFeatures}

O NVDA proporciona as suyas propias caracteristicas extra pa qualques aplicacions pa fer mas facils bells quefers u pa furnir acceso ta funcionalidat que d'unatro modo no ye accesible pa os usuarios d'un lector de pantalla.

### Microsoft Word {#MicrosoftWord}
#### Lectura automatica de capiters de columna y ringlera {#toc63}

O NVDA ye capable d'anunciar automaticament os capiters de ringlera y columna apropiaus en navegar por as tablas en o Microsoft Word.
Ixo requier en primeras que a opción d'anunciar os capiters de ringlera y columna de tabla en o dialogo de formatiau de documentos d'o NVDA, que se troba en o dialogo d'[opcions d'o NVDA](#NVDASettings), siga enchegada.
En segundas o NVDA amenista conoixer qué ringlera u columna contién os capiters en una tabla dada.
Dimpués de mover-te-ne t'a primera celda en a columna u ringlera que contién os capiters, fe servir un d'os siguients comandos:
<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Establir o capitero de columna |NVDA+mayus+c |Pretando isto una vez diz a lo NVDA que ista ye a primera celda de capitero en a ringlera que contién capiters de columna, que habría d'estar anunciada automaticament en mover-te-ne entre columnas baixo ista ringlera. Pretando-ne dos veces sacará ista opción.|
|Establir o capitero de ringlera |NVDA+mayus+r |Pretando isto una vez diz a lo NVDA que ista ye a primera celda de capitero en a columna que contién capiters de ringlera, que habría d'estar anunciau automaticament quan te'n desplaces entre as ringleras dimpués d'ista columna. Pretando-ne dos veces eliminará ista opción.|

<!-- KC:endInclude -->
Ixas opcions s'almagazenarán en o documento como marcapachinas compatibles con atros lectors de pantalla como lo JAWS.
Ixo significa que usuarios d'atros lectors de pantalla qui ubran ixe documento en una calendata posterior tendrán automaticament os capiters de ringlera y columna ya establius.

#### Modo de navegación en o Microsoft Word {#BrowseModeInMicrosoftWord}

Igual como en a web, o modo de navegación se puet fer servir en o Microsoft Word ta permitir-te fer servir caracteristicas tals como a navegación rapeda y a lista d'elementos.
<!-- KC:beginInclude -->
Pa activar u desactivar o modo de navegación en o Microsoft Word, preta NVDA+espacio.
<!-- KC:endInclude -->
Pa información detallada sobre o modo de navegación y a navegación rapeda, mira-te a [sección d'o modo de navegación](#BrowseMode).

##### A lista d'elementos {#WordElementsList}

<!-- KC:beginInclude -->
Mientras yes en o modo de navegación en o Microsoft Word puetz accedir t'a lista d'elementos pretando NVDA+f7.
<!-- KC:endInclude -->
A lista d'elementos puet listar capiters, vinclos, anotacions (que inclui comentarios y cambeos de seguimiento) y errors (actualment limitau nomás a errors d'ortografía).

#### Anunciau  de Comentarios {#WordReportingComments}

<!-- KC:beginInclude -->
Pa anunciar qualsiquier comentario en a posición actual d'o puntero preta NVDA+alt+c.
<!-- KC:endInclude -->
Totz os comentarios d'o documento de conchunta con o seguimiento d'atros cambeos tamién se pueden listar en a lista d'elementos d'o NVDA  en seleccionar anotacions como a mena.

### Microsoft Excel {#MicrosoftExcel}
#### Lectura automatica de capiters de columna y ringlera {#ExcelAutomaticColumnAndRowHeaderReading}

O NVDA ye capable d'anunciar automaticament os capiters de ringlera y columna apropiaus en navegar por as tablas en o Microsoft Excel.
Ixo requier en primeras que a opción d'anunciar os capiters de ringlera y columna de tabla en o dialogo de formatiau de documentos d'o NVDA, que se troba en o dialogo d'[opcions d'o NVDA](#NVDASettings), siga enchegada.
En segundas a lo NVDA le fa falta conoixer qué ringlera u columna contién os capiters en una tabla dada.
Dimpués de mover-te-ne t'a primera celda en a columna u ringlera que contién os capiters, fe servir un d'os siguients comandos:
<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Establir a ringlera de capiters de columna |NVDA+mayus+c |Pretando isto una vez diz a lo NVDA que ista ye a ringlera que contién capiters de columna, que habrían d'anunciar-se automaticament quan te'n muevas entre columnas por ista ringlera. Pretando-ne dos veces limpiará a opción.|
|Establir a columna de capiters de ringlera |NVDA+mayus+r |Pretando isto una vez  diz a lo NVDA que ista ye a columna que contién capiters de ringlera, que s'habrían d'anunciar automaticament  quan te'n muevas entre ringleras dimpués d'ista columna. Pretando-ne dos veces limpiará la opción.|

<!-- KC:endInclude -->
Ixas opcions s'almagazenarán en o libro de treballo como rangos de nombre definius compatibles con atros lectors de pantalla como lo JAWS.
Ixo significa que atros usuarios de lectors de pantalla qui ubran ixe libro de treballo en una calendata posterior tendrán automaticament os capiters de ringlera y columna ya establius. 

#### A lista d'elementos {#ExcelElementsList}

Igual como en a  web, o NVDA tien una lista d'elementos t'o Microsoft Excel que te permit  listar y accedir ta quantas menas diferents d'información.
<!-- KC:beginInclude -->
Pa accedir t'a lista d'elementos en l'Excel preta NVDA+f7.
<!-- KC:endInclude -->
As diferents menas d'información disponibles en a lista d'elementos son:

* Graficos: Isto lista totz os graficos en a fuella de treballo activa. 
Seleccionando un grafico y pretando l'intro u o botón mover ta enfoca o grafico ta navegar y leyer-lo con as teclas de flecha.
* Comentarios: Isto lista todas as celdas en a fuella de treballo activa que contiengan comentarios. 
S'amuestra l'adreza d'a celda de conchunta con os suyos comentarios ta cada celda. 
Pretando l'intro u lo botón mover ta en estar en un comentario listau se'n moverá dreitament t'a ixa celda.
* Formulas: Isto lista todas as celdas en a fuella de treballo que contiengan una formula. 
S'amuestra l'adreza d'a celda de conchunta con a suya formula ta cada celda.
Pretando l'intro u lo botón mover ta en una formula listada se'n moverá dreitament t'a ixa celda. 
* Fuellas: Isto lista todas as fuellas en o libro de treballo. 
Pretar f2 en estar en una fuella listada te permit renombrar a fuella. 
Pretando l'intro u lo botón de mover ta en estar en a fuella listada seleccionará ixa fuella.
* Campos de formulario: Isto lista totz os campos de formulario en a fuella de treballo activa.
Pa cada campo de formulario, a lista d'elementos amuestra o texto alternativo d'o campo de conchunta con as adrezas d'as celdas que cubre.
Seleccionando un campo de formulario y pretando l'intro u lo botón de mover ta se'n mueve ta ixe campo en modo de navegación.

#### Anunciau de notas {#ExcelReportingComments}

<!-- KC:beginInclude -->
Pa anunciar qualsiquier nota pa la celda actualment enfocada preta NVDA+alt+c.
En o Microsoft 2016, 365 y mas recients, s'ha renombrau los clasicos comentarios d'o Microsoft Excel como "notas".
<!-- KC:endInclude -->
Todas las notas d'a fuella de treballo pueden listar-sen tamién en a lista d'elementos d'o NVDA dimpués de pretar NVDA+F7.

Lo NVDA también puet amostrar un dialogo especifico pa anyadir u editar una determinada nota.
Lo NVDA sobrescribe la rechión d'edición de notas nativa d'o MS Excel a causa de restriccions d'accesibilidat, pero la pretada de tecla pa amostrar lo dialogo s'hereda d'o MS Excel y, por tanto, funciona tamién sin o NVDA executando-se.
<!-- KC:beginInclude -->
Pa anyadir u editar una determinada nota, en bella celda enfocada, preta mayus+f2.
<!-- KC:endInclude -->

Ixe alcorce de teclau no apareix y no se puet cambear en o dialogo de cenyos de dentrada d'o NVDA.

Para cuenta: Ye posible ubrir la rechión d'edición de notas en o MS Excel tamién dende lo menú contextual de bella celda d'a fuella de treballo.
Manimenos, ixo ubrirá la rechión d'edición de notas inaccesible y no pas lo dialogo d'edición de notas especifico d'o NVDA.

En o Microsoft Office 2016, 365 y mas recients, s'ha anyadiu un nuevo dialogo estilo de comentario.
Ixe dialogo ye accesible y furneix mas caracteristicas tals como respuestas a los comentarios, etc.
Tamién se puede ubrir dende lo menú de contexto d'una celda determinada.
Los comentarios anyadius a las celdas a traviés d'o nuevo dialogo estilo de comentario no son relacionaus con as "notas".

#### Leyer as celdas protechidas {#ExcelReadingProtectedCells}

Si un libro de treballo fuó protechiu, puet estar imposible mover o foco t'a celdas particulars que fuoron blocadas ta edición.
<!-- KC:beginInclude -->
Pa permitir mover-se-ne ta celdas blocadas cambea t'o modo de navegación pretando NVDA+espacio y allora fe servir os comandos estandar de movimiento de l'Excel como as teclas de flecha por todas as celdas en a fuella de treballo actual.
<!-- KC:endInclude -->

#### Campos de formulario {#ExcelFormFields}

As fuellas de treballo de l'Excel pueden incluir campos de formulario.
Puetz accedir ta ells fendo servir a lista d'elementos u as teclas de navegación d'una sola letra de campos de formulario; f y mayus+f.
Una vez que te'n yes moviu ta un campo de formulario en o modo de navegación puetz pretar l'intro u o espacio pa activar-lo u bien cambiar t'o modo de foco pa poder interactuar con ell, pendendo d'o control.
Pa mas información sobre o modo de navegación y a navegación d'una sola letra mira-te a [sección d'o modo de navegación](#BrowseMode).

### Microsoft PowerPoint {#MicrosoftPowerPoint}

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|commutar a lectura de notas de l'orador |control+mayus+s |Quan se ye en una presentación en execución, ista orden commutará entre las notas de l'orador t'a diapositiva y o conteniu d'a diapositiva. Isto solament afecta a o que leye o NVDA, no a o que s'amuestra en a pantalla.|

<!-- KC:endInclude -->

### foobar2000 {#Foobar2000}

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Anunciar lo tiempo restant |control+mayus+r |Anuncia lo tiempo restant d'a pista actualment en reproducción, si bi'n ha beluna.|
|Anunciar lo tiempo trescorriu |control+mayus+y |Anuncia lo tiempo trescorriu d'a pista actual en reproducción, si bi'n ha beluna.|
|Anunciar la longaria d'a pista |control+mayus+t |Anuncia la longaria d'a pista actual en reproducción, si bi'n ha beluna.|

<!-- KC:endInclude -->

Nota: los alcorces de teclau d'alto nomás funcionan con a cadena de formato predeterminada pa la linia d'estau d'o foobar.

### Miranda IM {#MirandaIM}

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Anunciar un mensache recient |NVDA+control+1-4 |Anuncia un d'os mensaches recients pendendo d'o numero pretau; p. eix.: NVDA+control+2 leye o segundo mensache mas recient.|

<!-- KC:endInclude -->

### Poedit {#Poedit}

<!-- KC:beginInclude -->

| Nombre |Tecla |Descripción|
|---|---|---|
|Anunciar a finestra de Comentarios |control+mayus+c |Anuncia qualsiquier comentario en a finestra de comentarios.|
|Anunciar las notas pa los traductors |control+mayus+a |Anuncia qualsiquier nota t'os traductors.|

<!-- KC:endInclude -->

### Kindle pa PC {#Kindle}

Lo NVDA suporta leyer y navegar por libros en l'Amazon Kindle pa PC.
Ixa funcionalidat no ye disponible que en libros Kindle disenyaus con "lector de pantalla: suportau", puetz comprebar-lo en a pachina de detalles d'o libro.

S'emplega o modo de navegación pa leyer libros.
S'enchega automaticament en que ubres bell libro u enfocas l'aria d'o libro.
Se pasará de pachina automaticament como ye de dar en que muevas o cursor u emplegues o comando de leyer-lo tot.
<!-- KC:beginInclude -->
Puetz pasar t'a siguient pachina manualment con a tecla abance de pachina y pasar t'a pachina anterior con a tecla de recule de pachina.
<!-- KC:endInclude -->

Se suporta a navegación d'una sola letra pa vinclos y graficos pero nomás adintro d'a pachina actual.
A navegación por vinclos tamién inclui as notas a o piet.

O NVDA furne suporte anticipau pa leyer y navegar interactivament en o conteniu matematico pa os libros con matematicas accesibles.
Mira-te a sección [leyendo lo conteniu matematico](#ReadingMath) pa mas información.

#### Selección de texto {#KindleTextSelection}

O Kindle te permite realizar qualques funcions en o texto seleccionau, incluindo obtener una definición de diccionario, adhibir notas y resaltaus, copiar o texto en o portafuellas y mirar en a web.
Pa fer ixo, en primeras selecciona texto como lo farías normalment en o modo de navegación, -. eix. fendo servir mayus y y as teclas de cursor.
<!-- KC:beginInclude -->
Una vez que haigas seleccionau texto preta a tecla d'aplicacións u mayus+f10 pa amostrar as opcions disponibles pa treballar con a selección.
<!-- KC:endInclude -->
Si fas ixo sin texto seleccionau, as opcions s'amostrarán pa la parola en que siga o cursor.

#### Notas d'Usuario {#KindleUserNotes}

Puetz adhibir bella nota respective a bella parola u a bell pasache de texto.
Pa fer ixo, en primeras selecciona o texto relevant y accede t'as opcions d'a selección como ye descrito alto.
Allora triga Adhibir una nota.

En leyer en o modo de navegación o NVDA se refier a istas notas como comentarios.

Pa veyer, editar y eliminar bella nota:

1. Mueve o cursor t'o texto que contién a nota.
1. Accede t'as opcions pa la selección como ye descrito alto.
1. Triga editar una Nota.

### Azardi {#Azardi}

<!-- KC:beginInclude -->
Quan se siga en a tabla d'envista de libros adhibius:

| Nombre |Tecla |Descripción|
|---|---|---|
|Intro |intro |Ubre o libro seleccionau.|
|Menú de Contexto |aplicacions |Ubre o menú de contexto pa o libro seleccionau.|

<!-- KC:endInclude -->

### Consola d'o Windows {#WinConsole}

Lo NVDA furneix compatibilidat pa la consola de comandos d'o Windows emplegada por l'indicativo d'o sistema, PowerShell, y lo  subsistema Windows pa Linux.
La finestra d'a consola ye de grandaria fixa, por un regular muito mas chica que no la memoria que contiene la salida.
En que s'escribe un nuevo texto, lo conteniu se desplaza enta alto y lo texto anterior ya no ye visible.
Lo texto que no s'amuestra visiblement en a finestra no ye accesible con os comandos de revisión de texto d'o NVDA.
Por tanto, ye necesario desplazar-se por la finestra d'a consola pa leyer lo texto anterior.
<!-- KC:beginInclude -->
Los siguients metodos abreviaus de teclau incorporaus en a Consola d'o Windows pueden estar utils a lo [revisar texto](#ReviewingText) con o NVDA:

| Nombre |Tecla |Descripción|
|---|---|---|
|Desplazar t'alto |control+flecha alto |Desplaza la finestra d'a consola enta alto, asinas se puede leyer lo texto anterior.|
|Desplazar t'abaixo |control+flecha abaixo |Desplaza la finestra d'a consola enta baixo, asinas se puede leyer lo texto posterior.|
|Desplazar t'o cobalto |control+inicio |Desplaza la finestra d'a consola t'o cobalto d'a memoria.|
|Desplazar t'o cobaixo |control+fin |Desplaza la finestra d'a consola t'o cobalto d'a meemoria.|

<!-- KC:endInclude -->

## Configurando lo NVDA {#ConfiguringNVDA}

La mas gran parti d'a configuración puet realizar-se fendo servir dialogos que se i accede por meyo d'o submenú de preferencias d'o menú NVDA.
Muitas d'istas opcions pueden trobar-sen en o dialogo multipachina d'[opcions d'o NVDA](#NVDASettings).
En totz los dialogos preta lo botón d'acceptar pa acceptar qualsiquier cambio que haigas feito.
Pa cancelar qualsiquier cambio preta lo botón de cancelar u a tecla d'escape.
Pa bells dialogos, puetz pretar lo botón d'aplicar pa fer que las opcions tiengan puesto immediatamente sin zarrar-lo.
Qualques opcions tamién pueden cambiar-sen emplegando teclas d'alcorce,  que se listan do sigan relevants en as seccions subsiguients.

### Opcions d'o NVDA {#NVDASettings}

<!-- KC:settingsSection: || Nombre | Tecla Escritorio | Tecla Portatil | Descripción | -->
Lo dialogo d'opcions d'o NVDA contién muitos parametros de configuración que se pueden cambiar.
Iste dialogo contién una lista con quantas categorías d'opcions entre las qualas trigar.
En trigar una categoría, s'amostrará quantas opcions relacionadas con ixa categoría en iste dialogo.
Ixas opcions se pueden aplicar utilizando lo botón d'aplicar, que en ixe caso lo dialogo remanirá ubierto.
Si deseyas alzar la configuración y zarrar lo dialogo d'opcions d'o NVDA, puetz utilizar lo botón d'acceptar.

Qualques categorías d'opcions tienen un alcorce de teclau adedicau.
Si se preta, ixe alcorce de teclau ubrirá  lo dialogo d'opcions d'o NVDA en ixa categoría en particular.
De traza predeterminada no se puet acceder ta todas las categorías con ordens de teclau.
Si deseyas acceder ta categorías que no tiengan alcorces de teclau adedicaus, utiliza lo [dialogo de cenyos de dentrada](#InputGestures) pa anyadir un cenyo personalizau tal como una orden de teclau u bell cenyo tactil pa ixa categoría.

Las categorías  d'opcions que se troba en o dialogo d'opcions d'o NVDA se describirán contino.

#### Cheneral (NVDA+control+g) {#GeneralSettings}

La categoría Cheneral d'o dialogo d'opcions d'o NVDA estableix lo comportamiento cheneral d'o NVDA, como l'idioma d'a interficie y si s'habría de comprebar las actualizacions u no pas.
Ista categoría contién las siguients opcions:

##### Idioma {#GeneralSettingsLanguage}

Isto ye un quadro combinau que te permite seleccionar l'idioma en que habría d'amostrar-se a interficie d'usuario y os mensaches d'o NVDA. 
Bi ha muitos idiomas, manimenos a zaguera esleción en a lista ye clamada "Predeterminau pa l'usuario". 
Ista esleción dirá a lo NVDA que faiga servir l'idioma en que lo Windows siga actualment configurau. 

Por favor para cuenta que lo NVDA ha d'estar reenchegau en que se cambeye l'idioma. 
En que amaneixca lo dialogo de confirmación triga "reenchegar agora" u "reenchegar mas tardi" si deseyas utilizar l'idioma nuevo agora u en bell momento posterior, respectivament. Si has trigau "reenchegar mas tardi", la configuración ha d'alzar-se (u manualment u fendo servir la funcionalidat d'alzar-la en salir).

##### Alzar a configuración en salir {#GeneralSettingsSaveConfig}

Ista opción ye una caixeta de verificación que quan se marca diz a lo NVDA que alce automaticament l'actual configuración en que salgas d'o NVDA. 

##### Amostrar las opcions de salida en salir d'o NVDA {#GeneralSettingsShowExitOptions}

Ista opción ye una caixeta de verificación que te permite trigar si amaneix u no pas un dialogo en que salgas d'o NVDA que te pregunte qué acción quiers fer.
Quan siga marcada, un dialogo amaneixerá en que intentes salir d'o NVDA preguntando-te si quiers salir, reenchegar, reenchegar con os complementos desenchegaus u instalar actualizacions pendients si bi'n ha.
Quan no siga marcada, se saldrá d'o NVDA inmediatament.

##### Reproducir sons en enchegar u desenchegar lo NVDA {#GeneralSettingsPlaySounds}

Ista Opción ye una caixeta de verificación que quan ye marcada diz a lo NVDA que reproduzca sons quan s'enchegue u desenchegue.

##### Libel de mensaches alzaus en o rechistro {#GeneralSettingsLogLevel}

Isto ye un quadro combinau que te permite trigar quánta información meterá lo NVDA en o rechistro seguntes s'executa. 
Por un regular a los usuarios no lis habría de fer falta tocar isto ya que no ye masiau amigable. 
Manimenos, si deseyas furnir información en bell informe de fallos, u enchegar u desenchegar tot lo rechistro, allora puet estar una opción util.

Los libels disponibles d'o rechistro son:

* Desenchegau: Antiparti d'un breu mensache d'inicio, lo NVDA no rechistrará cosa mientras s'execute.
* Información: Lo NVDA rechistrará la información basica tal como los mensaches d'inicio y información util pa los desembolicadors.
* Alvertencia de depuración: se rechistrará mensaches d'alvertencia que no sigan causaus por errors graus.
* Dentrada/salida: se rechistrará las dentradas d'as linias braille y d'os teclaus, asinas como la salida d'a voz y d'o braille.
 * Si te fas d'a privacidat, no configures ista opción de libel de rechistro.
* Depuración: amás d'os mensaches d'información, alvertencia y dentrada/salida, se rechistrará mensaches de depuración adicionals.
 * Igual como con a Dentrada/salida, si te fas d'a privacidat, no habrías de configurar lo libel de rechistro en ista opción.

##### Rancar lo NVDA automaticament dimpués de que s'inicie la sesión {#GeneralSettingsStartAfterLogOn}

Si ista opción ye activada, lo NVDA rancará automaticament malas que t'autentifiques en o Windows. 
Ista opción nomás ye disponible pa las copias instaladas d'o NVDA.

##### Rancar lo NVDA enentre que s'inicia la sesión (requiere privilechios d'administrador) {#GeneralSettingsStartOnLogOnScreen}

Si t'autentificas en o Windows furnindo un nombre d'usuario y una clau, allora activar ista opción ferá que lo NVDA ranque automaticament en a finestra d'autentificación en que lo Windows ranque. 
Ista opción nomás ye disponible pa las copias instaladas d'o NVDA.

##### Emplegar las opcions alzadas actualment entre que s'inicia la sesión y en pantallas seguras (requier privilechios d'administrador) {#GeneralSettingsCopySettings}

En pretar iste botón copias la tuya configuración d'usuario d'o NVDA actualment alzada t'o directorio de sistema de configuración d'o NVDA, de tal forma que lo NVDA lo ferá servir quan s'execute en l'autentificación, en o control de cuentas d'usuario (UAC) y en atras pantallas seguras d'o Windows.
Pa estar seguro que todas as tuyas opcions se transfieren, asegura-te d'alzar en primeras a tuya configuración con control+NVDA+c u alza a configuración en o menú NVDA.
Ista opción solament ye disponible pa las copias instaladas d'o NVDA.

##### Mirar automaticament as actualizacions d'o NVDA {#GeneralSettingsCheckForUpdates}

Si isto ye activau, o NVDA mirará automaticament versions esvielladas y t'informará quan una actualización siga disponible.
Tamién puetz mirar as actualizacions manualment seleccionando Mirar as Actualizacions baixo lo menú d'aduya en o menú NVDA.
En mirar actualizacions manual u automaticament, ye necesario pa NVDA ninviar bella información t'o servidor d'actualizacions pa recibir l'actualización correcta pa lo tuyo sistema.
Se ninvia siempre la siguient información: 

* Versión actual d'o NVDA
* Versión d'o Sistema Operativo
* Si lo Sistema Operativo ye de 64 u de 32 bits

##### Permitir a lo Prochecto NVDA que replegue Estatisticas d'emplego d'o NVDA {#GeneralSettingsGatherUsageStats}

Si isto ye activau, NV Access fará servir la información d'as buscas d'actualizacions pa seguir lo numero d'usuarios d'o NVDA incluyindo datos demograficos particulars tals como lo Sistema Operativo y lo país d'orichen.
Tiene en cuenta que encara que la tuya adreza IP s'emplegará pa calcular lo tuyo país entre la busca d'actualizacions, l'adreza IP nunca no se conservará.
Amás d'a información obligatoria necesaria pa buscar actualizacions, tamién se ninvia la siguient información adicional actualment:

* Idioma d'a interficie d'o NVDA
* Si ista copia d'o NVDA ye portable u instalada
* Lo nombre d'o sintetizador de voz actual en uso (incluyindo lo nombre d'o complemento que viene con o controlador)
* Lo nombre d'a pantalla Braille actual en uso (incluyindo lo nombre d'o complemento que viene con o controlador)
* La tabla de salida braille actual (si lo Braille ye en uso)

Ixa información aduya enormement a NV Access a priorizar lo desembolique futuro d'o NVDA.

##### Notificar las actualizacions pendients en enchegar {#GeneralSettingsNotifyPendingUpdates}

Si isto ye enchegau o NVDA t'informará en que bi haiga una actualización pendient en echegar-se, ufrindo-te a posibilidat d'instalar-la.
Tamién puetz instalar manualment l'actualización pendient dende lo dialogo de salir d'o NVDA (si ye enchegau), dende o menú NVDA, u en rializar una nueva busca dende o menú d'aduya.

#### Opcions de Voz (NVDA+control+v) {#SpeechSettings}

La categoría de voz en o dialogo d'opcions d'o NVDA contién achustes que te permiten de cambiar lo sintetizador de voz asinas como caracteristicas d'a voz pa lo sintetizador esleixiu.
Pa una traza alternativa rapida de controlar os parametros de voz dende qualsiquier puesto, por favor mira-te a sección [Grupo d'Opcions de Sintetizador](#SynthSettingsRing).

La categoría d'opcions de voz contién os siguients achustes:

==== Cambiar lo sintetizador ====SynthesizerSelection][SpeechSettingsChange]
Lo primer achuste en a categoría d'opcions de voz ye lo botón de cambiar... Iste botón activa lo dialogo de [seleccionar lo Sintetizador](#SelectSynthesizer), que te permite seleccionar lo sintetizador de voz activo y lo dispositivo de son.
Ixe dialogo s'ubre por dencima d'o dialogo d'opcions d'o NVDA.
Alzando u descartando los achustes en o dialogo de seleccionar lo sintetizador tornarás t'o dialogo d'opcions d'o NVDA.

##### Voz {#SpeechSettingsVoice}

La opción voz ye un quadro combinau que lista todas las voces d'o sintetizador actual que tiens instalau. 
Puetz emplegar as teclas de cursor pa escuitar todas las eslecions. 
Las flechas cucha y alto puyan por a lista, mientras que as flechas dreita y abaixo baixan por ella.

##### Variant {#SpeechSettingsVariant}

Si yes emplegando lo sintetizador Espeak NG empaquetau de conchunta con o NVDA, Iste ye un quadro combinau que te permite seleccionar la variant con que lo sintetizador habría de charrar. 
Las variants d'o Espeak NG son prou parellanas a las voces, pero furnen atributos licherament diferents pa la voz d'o ESpeak NG. 
Bellas variants sonarán como un hombre, belunas como una muller, y belunas como si tenesen carraspera.
Si fas servir bell sintetizador de tercers, tamién podrás cambiar ixa valor si la voz trigada lo suporta.

##### Velocidat {#SpeechSettingsRate}

Ista opción te permite cambiar la velocidat d'a voz. 
Ista ye una barra de desplazamiento que va dende 0 dica 100, (estando 0 la velocidat mas lenta y estando 100 la mas rapida).

##### Charrar a escape {#SpeechSettingsRateBoost}

Enchegar ista opción aumentará prou la velocidat d'a voz si lo sintetizador actual lo suporta.

##### Ton {#SpeechSettingsPitch}

Ista opción te permite cambiar lo ton d'a voz. 
Ista ye una barra de desplazamiento que va dende 0 dica 100, (estando 0 lo ton mas baixo y estando 100 lo mas alto). 

##### Volumen {#SpeechSettingsVolume}

Ista opción ye una barra de desplazamiento que va dende 0 dica 100, (estando 0 lo volumen mas baixo y estando 100 lo mas alto).

##### Entonación {#SpeechSettingsInflection}

Ista opción ye una barra de desplazamiento que te permite trigar quánta entonación (puyada y caita en lo ton) habría d'emplegar lo sintetizador pa charrar. (Lo solo sintetizador que furne ista opción actualment ye lo Espeak NG).

##### Cambio Automatico d'Idioma {#SpeechSettingsLanguageSwitching}

Ista caixeta de verificación te permite d'activar u de desactivar si lo NVDA habría de cambiar los idiomas d'o sintetizador de voz automaticament si lo texto pa leyer especifica lo suyo idioma.
Ista opción ye activada de traza predeterminada.

##### Cambio Automatico de Dialecto {#SpeechSettingsDialectSwitching}

Ista caixeta de verificación te permite d'activar u de desactivar  si los cambios de dialecto s'habrían de fer, en cuenta de nomás cambiar l'idioma actual.
Por eixemplo: Si se ye leyendo en una voz anglesa U.S. pero partis d'un documento tienen bell texto en anglés U.K. allora si ista caracteristica ye activada lo sintetizador cambiará lo suyo accento.
Ista opción ye desactivada de traza predeterminada.

<!-- KC:setting -->

##### Libel de Puntuación y simbolos {#SpeechSettingsSymbolLevel}

Tecla: NVDA+p

Ixo te permite trigar la cantidat de puntuación y atros simbolos que habría de charrar-sen como parolas.
Por eixemplo, quan se configura a toda, totz los simbolos se charrarán como parolas.
Ista opción s'aplica a totz os sintetizadors, no nomás a lo sintetizador activo actualment.

Pa cambiar la inclusión de datos de l'Unicode Consortium dende do siga, asigna un cenyo personalizau fendo servir lo [dialogo de cenyos de dentrada](#InputGestures).

##### Confidar en l'idioma d'a voz en procesar caracters y simbolos {#SpeechSettingsTrust}

Enchegada por defecto, ista opción le diz a lo NVDA si se puet confidar en l'idioma d'a voz actual en procesar simbolos y caracters .
Si trobas que lo NVDA ye leyendo puntuación en l'idioma incorrecto  pa bell sintetizador u voz particular  puetz querer  desenchegar ixo pa aforzar a lo NVDA  pa que faiga servir a suya opción d'idioma global en cuenta.

##### Incluyir los datos Unicode Consortium (incluyindo emoji) en procesar caracters y simbolos {#SpeechSettingsCLDR}

Quan ixa caixeta de verificación siga marcada lo NVDA incluyirá los diccionarios de pronuncia de simbolos adicionals en pronunciar caracters y simbolos.
Ixos diccionarios contienen descripcions pa simbolos (en particular emoji) furnius por lo [Unicode Consortium](https://www.unicode.org/consortium/) como parti d'o suyo [Common Locale Data Repository](http://cldr.unicode.org/).
Si quiers que lo NVDA diga las descripcions de caracters d'emoji basaus en ixos datos, habrías d'enchegar ixa opción.
Por tanto, si yes fendo servir bell sintetizador de voz que admita la verbalización de descripcions d'emoji nativament, habrías de desenchegar ixo.

Tiene en cuenta que las descripcions de caracters anyadidas u editadas manualment s'alzan como parti d'as tuyas opcions d'usuario.
Por tanto, si cambias la descripción de bell emoji en particular, la tuya descripción personalizada se verbalizará pa ixe emoji sin importar si ixa opción ye enchegada.
Puetz anyadir, editar u eliminar descripcions de simbolos en o [dialogo de pronuncia de puntuación y simbolos](#SymbolPronunciation) d'o NVDA.

##### Cambio de Porcentache de Ton pa las Mayusclas {#SpeechSettingsCapPitchChange}

Iste campo d'edición te permite tecliar la cantidat en que lo ton d'a voz cambiará quan se charre una letra mayuscla.
Ista valor ye un porcentache, en que una valor negativa baixa lo ton y una valor positiva lo puya.
Pa no cambiar lo ton s'emplega lo 0.
Por un regular lo NVDA agrandeix lo tono licherament pa qualsiquier letra en mayuscla, pero bells sintetizadors pueden no suportar-lo bien.
En o caso que no se suporte lo cambio de tono pa las mayusclas, considera fer servir lo [dicir "mayus" antis de mayusclas](#SpeechSettingsSayCapBefore) y/u [chuflar  pa las mayusclas](#SpeechSettingsBeepForCaps) en cuenta.

##### Dicir Mayus antis de Mayusclas {#SpeechSettingsSayCapBefore}

Ista opción ye una caixeta de verificación, que quan ye marcada diz a lo NVDA que diga la parola "mayus" antis de qualsiquier letra en mayuscla, quan se navega sobre ella u charrando-la quan ye estando escrita. 

##### chuflar pa las Mayusclas {#SpeechSettingsBeepForCaps}

Si ista caixeta de verificación ye marcada, lo NVDA fará un chicot chufliu cada vez que siga charrando un caracter en mayuscla. 

##### Emplegar a funcionalidat de letreyo si ye suportada {#SpeechSettingsUseSpelling}

Qualques parolas consisten en nomás un caracter, pero la pronuncia ye diferent pendendo de si lo caracter va a estar charrau como un caracter individual (tal como quan se letreya) u una parola.
Por eixemplo en aragonés "y" ye tanto una letra como una parola y se pronuncia de traza diferent en cada caso.
Ista opción permite a lo sintetizador de diferenciar entre istos dos casos si lo sintetizador lo suporta.
A mayoría d'os sintetizadors lo suportan.

Ista opción cheneralment habría d'activar-se.
Manimenos, qualques sintetizadors Microsoft Speech API no implementan isto correctament y funciona anomalament quan s'activa.
Si yes tenendo problemas con a pronuncia de caracters individuals,  preba desactivando ista opción.

#### Seleccionar lo sintetizador (NVDA+control+s) {#SelectSynthesizer}

Lo dialogo de sintetizador, que puet ubrir-se activando lo botón de cambiar... en a categoría de voz d'o dialogo d'opcions d'o NVDA, te permite seleccionar qué Sintetizador habría d'emplegar lo NVDA pa charrar.
Una vez haigas seleccionado lo sintetizador d'a tuya esleción, puetz pretar l'acceptar y lo NVDA cargará lo sintetizador seleccionau.
Si bi ha bella error en cargar lo sintetizador, lo NVDA te lo notificará con un mensache, y continará fendo servir l'anterior.

##### Sintetizador {#SelectSynthesizerSynthesizer}

Ista opción te permite trigar lo sintetizador  que deseyas que emplegue lo NVDA pa la salida de voz.

Pa una lista d'os sintetizadors que suporta lo NVDA, por favor mira-te a sección [Sintetizadors de Voz Suportaus](#SupportedSpeechSynths).

Un elemento especial que amaneixerá siempre en ista lista ye "Sin Voz", que te permite d'emplegar lo NVDA sin garra salida de voz.
Ixo podría estar util pa belún que deseye emplegar nomás lo NVDA con Braille, u  talment pa desembolicadors vidents que solament deseyen emplegar lo Visor d'a Voz.

##### Dispositivo de Salida {#SelectSynthesizerOutputDevice}

Ista opción te permite trigar lo dispositivo d'audio por lo qualo habría de mandar charrar lo NVDA a lo sintetizador seleccionau.

<!-- KC:setting -->

##### Modo d'achiquida d'audio {#SelectSynthesizerDuckingMode}

Tecla: NVDA+mayus+d

En o Windows 8 y superiors, ista opción te permite d'esleyir si lo NVDA habría de baixar lo volumen d'atras aplicacions entre que lo NVDA ye charrando, u tot lo rato entre que lo NVDA se ye executando.

* No achiquir: Lo NVDA nunca no baixará lo volumen d'atros sons. 
* Achiquir en que salga voz y sons: Lo NVDA nomás baixará lo volumen d'atros sons quan lo NVDA siga charrando u reproducindo sons. Ixo puet no marchar pa totz os sintetizadors. 
* Achiquir siempre: Lo NVDA mantendrá lo volumen d'atros sons más baixo tot lo rato que se siga executando.

Ista opción nomás ye disponible si o NVDA ye instalau.
No ye posible suportar l'achiquida d'audio en as copias portables y temporals d'o NVDA.

#### Aniello d'opcions de sintetizador {#SynthSettingsRing}

Si deseyas de cambiar rapidament opcions de voz  sin ir t'o dialogo d'Opcions de Voz, bi ha qualques teclas d'ordens d'o NVDA que te permiten de mover-te-ne a traviés d'as opcions de voz mas comunas, dende qualsiquier puesto mientras s'executa lo NVDA:
<!-- KC:beginInclude -->

| Nombre |Tecla Sobremesa |Tecla Portatil |Descripción|
|---|---|---|---|
|Mover-se-ne t'a siguient opción d'o sintetizador |NVDA+control+Flecha dreita |NVDA+control+Flecha dreita |Se mueve t'a siguient opción de voz disponible dimpués de l'actual, pasando por a primera opción de nuevo dimpués d'a zaguera|
|Mover-se-ne t'a opción anterior d'o sintetizador |NVDA+control+Flecha cucha |NVDA+control+Flecha cucha |Se mueve t'a opción de voz anterior disponible dimpués de l'actual, pasando por a primera opción de nuevo dimpués d'a zaguera|
|Incrementar l'actual opción d'o sintetizador |NVDA+control+Flecha alto |NVDA+control+Flecha alto |incrementa a opción de voz actual sobre a quala sigas. P. eix.: incrementa la velocidat, triga la siguient voz, incrementa o volumen|
|Decrementar l'actual opción d'o sintetizador |NVDA+control+Flecha abaixo |NVDA+control+Flecha abaixo |decrementa a opción de voz actual sobre a quala sigas. P. eix.: decrementa a velocidat, triga  a voz anterior, decrementa o volumen|

<!-- KC:endInclude -->

#### Braille {#BrailleSettings}

La categoría de braille en lo dialogo d'opcions d'o NVDA contién achustes que te permiten de cambiar quantos aspectos d'a dentrada y salida braille.
Ista categoría contién las siguients opcions:

##### Cambiar a linia braille {#BrailleSettingsChange}

Lo botón de cambiar... en la categoría de braille d'o dialogo d'opcions d'o NVDA activa lo dialogo de [seleccionar a linia braille](#SelectBrailleDisplay), que te permite seleccionar la linia braille activa.
Iste dialogo s'ubre sobre lo dialogo d'opcions d'o NVDA.
Alzando u descartando las opcions en o dialogo de seleccionar a linia braille tornarás t'o dialogo d'opcionns d'o NVDA.

##### Tabla de Salida {#BrailleSettingsOutputTable}

A siguient opción que vien en ista categoría ye lo quadro combinau d'a tabla de salida braille.
En iste quadro combinau, trobarás tablas braille, estandars braille y graus pa diferents idiomas.
A tabla trigada s'utilizará ta transcribir texto a braille ta presentar-lo en a linia braille.
Puetz mover-te-ne entre as tablas braille en a lista emplegando as teclas de cursor.

##### Tabla de Dentrada {#BrailleSettingsInputTable}

Complementariament con a opción anterior, o siguient achuste que trobarás ye o quadro combinau d'a tabla de dentrada braille.
La tabla trigada s'utilizará ta transcribir ta texto o braille introduciu en o teclau tipo perkins d'a linia braille.
Puetz mover-te entre las tablas braille en a lista emplegando as teclas de cursor.

Para cuenta que ista opción nomás ye util si a tuya linia braille tien un teclau tipo Perkins y si ista caracteristica ye suportada por o controlador d'a linia braille.
Si la dentrada no ye suportada en una linia que tienga un teclau braille, ixo se notificará en a sección de [linias braille suportadas](#SupportedBrailleDisplays).

##### Expandir ta braille d'ordinador a parola en o cursor {#BrailleSettingsExpandToComputerBraille}

Ista opción permite a la parola que ye baixo lo cursor amostrar-se en braille d'ordinador no contraito.

##### Amostrar lo cursor {#BrailleSettingsShowCursor}

Ista opción permite a lo cursor braille enchegar-se y desenchegar-se.
S'aplica a o cursor d'o sistema y a o cursor de revisión, pero no pas a o endicador d'a selección.

##### Cursor esparpellant {#BrailleSettingsBlinkCursor}

Ista opción permite que o cursor braille esparpelle.
Si o esparpello ye desenchegau, o cursor braille será constantment en a posición d'alto.
L'indicador de selección no ye afectau por ista opción, siempre ye con os puntos 7 y 8 sin esparpellar.

##### Velocidat d'esparpello d'o cursor (ms) {#BrailleSettingsBlinkRate}

Ista opción ye un campo numerico que te permite cambiar a velocidat de esparpello d'o cursor en milisegundos.

##### Forma d'o cursor pa o foco {#BrailleSettingsCursorShapeForFocus}

Ista opción te permite esleyir a forma (patrón de puntos) d'o cursor braille quan o braille siga a o foco.
L'indicador de selección no ye afectau por ista opción, siempre ye con os puntos 7 y 8 sin esparpellar.

##### Forma d'o Cursor pa la Revisión {#BrailleSettingsCursorShapeForReview}

Ista opción te permite d'esleyir a forma (patrón de puntos) d'o cursor braille quan o braille siga a la revisión.
L'indicador de selección no ye afectau por ista opción, siempre ye con os puntos 7 y 8 sin esparpellar.

##### Amostrar los Mensaches {#BrailleSettingsShowMessages}

Iste ye un quadro combinau que te permite trigar si lo NVDA habría d'amostrar los mensaches braille y quán habría de desapareixer automaticament.

##### Durada d'o Mensache (en seg) {#BrailleSettingsMessageTimeout}

Ista opción ye un campo numerico que controla entre quánto tiempo s'amuestra os mensaches d'o sistema en a linia braille.
Lo mensache d'o NVDA se zarra a l'inte en pretar un sensor en a linia braille, pero torna a amaneixer en pretar la correspondient tecla que l'aventó.
Ista opción no s'amuestra so que si se mete "amostrar los Mensaches" a "emplegar lo tiempo d'espera".

<!-- KC:setting -->

##### Lo braille ancorau a {#BrailleTether}

Tecla: NVDA+control+t

Ista opción te permite trigar si la linia braille seguirá a lo foco d'o sistema / cursor, a lo navegador d'obchectos / cursor de revisión, u a totz dos.
Quan se trigue "automaticament", lo NVDA seguirá a lo foco y a lo cursor d'o sistema por defecto.
En ixe caso, quan se cambeye la posición d'o navegador d'obchectos u d'o cursor de revisión mediant una interacción explicita de l'usuario, lo NVDA seguirá a la revisión temporalment, dica que lo foco u lo cursor cambeye.
Si quiers que siga a lo foco y a lo cursor nomás, te cal configurar lo braille ancorau a lo foco.
En ixe caso, lo braille no seguirá a lo navegador d'o NVDA entre la navegación d'obchectos u a lo cursor de revisión mientras la revisión.
Si quiers que lo braille siga a la navegación d'obchectos y a la revisión de texto en cuenta, te cal configurar lo braille ancorau a la revisión.
En ixe caso, lo braille  no seguirá a lo foco d'o sistema ni a lo cursor d'o sistema.

##### Leyer por Paragrafo {#BrailleSettingsReadByParagraph}

Si ye activau, o braille s'amostrará por paragrafos en cuenta de por linias.
Tamién, as ordens de linia siguient y anterior moverán por paragrafos en concordancia.
Isto significa que no tiens desplazamiento d'a linia braille t'a fin de cada linia mesmo quán bi haiga mas texto d'o que culle en a linia braille.
Isto podría permitir una lectura mas fluida de grans cantidatz de texto.
Isto ye desactivau de traza predeterminada.

##### Privar a división de parolas quan siga posible {#BrailleSettingsWordWrap}

Si isto ye activau, una parola que siga masiau gran ta cullir en o final d'a linia braille no será dividida.
En cuenta d'ixo, bi habrá bella mica d'espacio en blanco a la fin d'a linia.
En desplazar-te-ne por a pantalla podrás leyer a parola completa.
Ixo a veces se clama "achuste de linia".
Nota que si a parola ye masiau luenga ta cullir en a linia mesmo por sí mesma, a parola agún habrá de dividir-se.

Si isto ye desactivau, tanto como siga posible d'a parola  s'amostrará pero a resta en se tallará.
En que te'n desplaces por a pantalla allora podrás leyer a resta d'a parola.

Activar-la pue permitir una lectura mas fluida pero por un regular requier que te'n desplaces mas por a pantalla.

##### Presentación d'o Contexto d'o Foco {#BrailleSettingsFocusContextPresentation}

Ista opción te permite trigar qué información d'o contexto amostrará o NVDA en a linia braille quan bel obchecto obtienga o foco.
A información d'o contexto se refier a la hierarquía d'obchectos que contiengan o foco.
Por eixemplo, quan enfoques bell elemento de lista, ixe elemento de lista fa parti d'una lista.
Ixa lista podría estar contenida en un dialogo, etc.
Por favor, mira-te a sección arredol d'a [navegación d'obchectos](#ObjectNavigation) pa mas información sobre a hierarquía que s'aplica a os obchectos en o NVDA.

Quan se configure en replenar a pantalla pa cambios d'o contexto, o NVDA mirará d'amostrar tanta información de contexto como le siga posible en a linia braille, pero nomás pa las partis d'o contexto que haigan cambiadas.
Pa l'eixemplo d'alto, ixo significa que en que o foco cambeye por a lista, o NVDA amostrará l'elemento d'a lista en a linia braille.
Amás, si queda prau espacio en a linia braille, o NVDA mirará d'amostrar que l'elemento de lista fa parti d'una lista.
Si, contino, prencipias a mover-te-ne por a lista con as teclas de cursor, se suposa que yes conscient d'estar agún en a lista.
Por tanto, pa os elementos de lista restants que enfoques o NVDA nomás amostrará l'elemento d'a lista enfocau en a linia.
Pa leyer o contexto de nuevas (ye decir, que yes en una lista y que a lista fa parti d'un dialogo), habrás a desplazar a tuya pantalla braille enta zaga.

Quan ista opción siga configurada a replenar siempre a pantalla, o NVDA mirará d'amostrar tanta información de contexto como síga posible en a linia braille, independientment de si has visto a mesma información de contexto dinantis.
Ixo tien l'avantalla que o NVDA achustará tanta información como siga posible en a pantalla.
Por tanto, a desavantalla ye que siempre bi ha una diferencia en a posición que i prencipia l'enfoque en a linia braille.
Ixo puet fer dificil navegar por una lista larga d'elementos,  por eixemplo, ya que habrás a mover continament o dido pa trobar o escomencipio de l'elemento.
Ixe yera o comportamiento predeterminau pa o NVDA 2017.2 y anteriors.

Quan configures a opción de presentación d'o contexto d'o foco en amostrar nomás a información d'o contexto en desplazar-se-ne enta zaga, o NVDA nunca no amuestra a información d'o contexto en a linia braille por defecto.
Asinas, en l'eixemplo anterior, o NVDA amostrará que enfoqués un elemento de lista.
Por tanto, pa leyer o contexto (ye decir, que yes en una lista y que ixa lista fa parti d'un dialogo), habrás a desplazar a linia braille enta zaga.

Pa cambiar a presentación d'o contexto d'o foco dende qualsiquier puesto, por favor asigna un cenyo personalizau fendo servir o [dialogo de cenyos de dentrada](#InputGestures).

#### Seleccionar a linia braille (NVDA+control+a) {#SelectBrailleDisplay}

Lo dialogo de seleccionar a linia braille, que puet ubrir-se pretando lo botón de cambiar... en a categoría braille d'o dialogo d'opcions d'o NVDA, te permite seleccionar qué linia braille habría d'emplegar lo NVDA pa la salida braille.
Una vez haigas seleccionau la linia braille d'a tuya esleción, puetz pretar l'acceptar y lo NVDA cargará la linia seleccionada.
Si bi ha bella error carghando lo controlador d'a linia, lo NVDA te lo notificará con un mensache, y continará fendo servir la linia anterior, si bi'n ha beluna.

##### Linia braille {#SelectBrailleDisplayDisplay}

Iste cuadro combinau se te presenta con quantas opcions pendendo de qué controladors de linia braille sigan disponibles en o tuyo sistema.
Muéve-te-ne entre ixas opcions con as teclas d'as flechas.

La opción d'automatico permitirá a lo NVDA de mirar muitas linias braille admitidas en segundo plano.
Quan ixa caracteristica siga activada y connectes una linia admitida fendo servir l'USB u lo bluetooth, lo NVDA connectará automaticament con ella.

Sin braille quiere decir que no yes fendo servir lo braille.

Por favor mira-te la sección de [linias braille suportadas](#SupportedBrailleDisplays) pa mas información arredol de ditas linias braille y de quálas d'ellas suportan la detección automatica.

##### Puerto {#SelectBrailleDisplayPort}

Ista opción, si ye disponible, te permite d'esleixir qué puerto u tipo de connexión s'utilizará pa comunicar con a linia braille que haigas seleccionau.
Ye un quadro combinau que contién las eslecions posibles pa la tuya linia braille.

Por defecto lo NVDA emplega la detección de puerto automatica,  lo que quiere decir que la connexión con lo dispositivo braille s'establirá automaticament mirando los dispositivos USB y bluetooth en o tuyo sisttema.
Por tanto, pa bellas linias braille, podrás esleixir de propio qué puerto s'habría d'emplegar.
Las opcions comunas son "automatico" (que le diz a lo NVDA que emplegue lo procedimiento de selección de puerto automatico predeterminau), "USB", "Bluetooth" y puertos serie heredaus si la tuya linia braille suporta iste tipo de comunicación.

Ixa opción no será disponible si la tuya linia braille no suporta que detección automatica de puertos.

Puetz mirar-te la documentación pa la tuya linia braille en a sección de [linias braille suportadas](#SupportedBrailleDisplays) pa mirar mas detalles sobre los tipos compatibles de comunicación y puertos disponibles.

Por favor, para cuenta: Si connectas qualques linias braille t'a tuya maquina de vez que fagan servir lo mesmo controlador (p.eix. connectar dos linias Seika),
Actualment no ye posible decir-le a lo NVDA qué linia cal que emplegue.
Por tanto ye recomendau connectar nomás una linia braille d'un tipo dau u fabricant t'a maquina tuya de vez.

#### Visión {#VisionSettings}

La categoría de visión en o dialogo d'opcions d'o NVDA te permite enchegar, desenchegar y configurar [aduyas visuals](#Vision).

Tiene en cuenta que las opcions disponibles en ista categoría podrían enamplar-sen con [complementos d'o NVDA](#AddonsManager).
Por defecto, ista categoría d'achustes contiene las siguients opcions:

##### Resaltau visual {#VisionSettingsFocusHighlight}

Las caixetas de verificación en o grupo d'o resaltau visual controlan lo comportamiento d'a función integrada [resaltar lo foco](#VisionFocusHighlight) d'o NVDA.

* Enchegar lo Resaltau: Enchega y desenchega lo resaltau visual.
* Resaltar lo foco d'o sistema: Cambiará si se resalta u no pas lo [foco d'o sistema](#SystemFocus).
* Resaltar lo navegador d'obchectos: Cambia si se resaltará u no pas lo [navegador d'obchectos](#ObjectNavigation).
* Resaltar lo cursor d'o modo de navegación: Cambia si se resaltará u no pas lo [cursor virtual d'o modo de navegación](#BrowseMode).

Tiene en cuenta que marcar y desmarcar la caixeta de verificación "Enchegar lo resaltau" tamién cambiará lo estau d'as atras caixetas de verificación de l'arbol en concordancia.
Por tanto, si "enchegar lo resaltau" ye desenchegada y la marcas, las atras tres caixetas de verificación tamién se marcarán automaticament.
Si nomás quiers resaltar lo foco y deixar las caixetas d'o navegador d'obchectos y d'o modo de navegación desmarcadas, lo estau d'a caixeta de verificación "enchegar lo resaltau" será semi marcau.

##### Cortina de Pantalla {#VisionSettingsScreenCurtain}

Puetz enchegar la [cortina de pantalla](#VisionScreenCurtain) marcando la caixeta de verificación "meter la pantalla en negro (efecto immediato)".
Amaneixerá una alvertencia que la pantalla se tornará negra dimpués de l'enchegue.
Antis de no continar (trigando "sí"), asegura-te de tener enchegaus la voz y lo braille y podrás controlar lo tuyo ordinador sin fer servir la pantalla.
Triga "no" si ya no deseyas enchegar la Cortina de Pantalla.
Si en yes seguro, puetz trigar lo botón sí pa enchegar la cortina de pantalla.
Si ya no quiers veyer ixe mensache d'alvertencia cada vez, puetz cambiar ixe comportamiento en o dialogo que l'amuestra.
Siempre puetz restaurar l'alvertencia marcando la caixeta de verificación d'"amostrar siempre una alvertencia quan se cargue la Cortina de Pantalla" chunto a la caixeta de verificación de "meter la pantalla en negro".

Pa cambiar la cortina de pantalla dende qualsiquier puesto, por favor asigna un cenyo personalizau fendo servir lo dialogo de [cenyos de dentrada](#InputGestures).

De traza predeterminada se reproducirá sons en enchegar u desenchegar la cortina de pantalla.
Quan quieras cambiar ixe comportamiento, puetz esmarcar la caixeta de verificación "reproducir son en enchegar u desenchegar la cortina de pantalla".

##### Opcions pa aduyas visuals de tercers {#VisionSettingsThirdPartyVisualAids}

Se puede proporcionar furnidors de millora d'a visión adicionals en [complementos d'o NVDA](#AddonsManager).
Quan ixos furnidors tiengan opcions achustables, s'amostrarán en ista categoría d'opcions en grupos deseparaus.
Pa obtener mas información sobre la configuración de cada furnidor, por favor mira-te la documentación d'ixe furnidor.

#### Teclau (NVDA+control+k) {#KeyboardSettings}

La categoría de teclau en o dialogo d'opcions d'o NVDA contién achustes que estableixen lo comportamiento d'o NVDA quan usas y escribes en o tuyo teclau.
Ista categoría d'opcions contién los siguients achustes:

##### Disposición d'o Teclau {#KeyboardSettingsLayout}

Iste quadro combinau te permite trigar qué tipo de distribución de teclau habría d'emplegar lo NVDA. Actualment totz dos que vienen con o NVDA son Sobremesa y Portatil.

##### Seleccionar las Teclas Modificaderas d'o NVDA {#KeyboardSettingsModifiers}

Las caixetas de verificación en ista lista controlan qué teclas pueden utilizar-sen como [teclas modificaderas d'o NVDA](#TheNVDAModifierKey). Las siguients teclas son disponibles pa trigar:

* La tecla de bloqueyo de mayusclas
* La tecla de ficar en o teclau numerico
* La tecla de ficar extendida (trobada por un regular dencima d'as teclas de flecha, amán d'inicio y fin)

Si no se triga garra tecla como la tecla modificadera d'o NVDA podría estar imposible accedir ta bells comandos d'o NVDA.
Por tanto, lo dialogo d'opcions d'o NVDA amostrará un mensache d'error si todas las teclas son sin trigar  en pretar l'acceptar.
Dimpués de zarrar lo mensache d'error, has de trigar-ne a lo menos una antis de no poder pretar l'acceptar pa zarrar lo dialogo correctament.

<!-- KC:setting -->

##### Charrar los caracters en escribir-los {#KeyboardSettingsSpeakTypedCharacters}

Tecla: NVDA+2

Quan ye marcada significa que o NVDA anunciará totz los caracters seguntes los escribas en o teclau. 

<!-- KC:setting -->

##### Charrar las parolas en escribir-las {#KeyboardSettingsSpeakTypedWords}

Tecla: NVDA+3

Quan siga marcada significa que o NVDA anunciará todas las parolas en escribir-las en o teclau. 

##### Aturar a Voz quan s'escribe Caracters {#KeyboardSettingsSpeechInteruptForCharacters}

Si ye activada, ista opción causará que a voz s'ature cada vez que s'escriba un caracter. Isto ye activau de traza predeterminada.

##### Aturar a Voz quan se preta a Tecla Enter {#KeyboardSettingsSpeechInteruptForEnter}

Si ye activada, ista opción causará que a voz s'ature cada vez que se prete a tecla Enter. Isto ye activau de traza predeterminada.

##### Permitir a lectura superficial en charrar-lo Tot {#KeyboardSettingsSkimReading}

Si ye activada, bellas ordens de navegación (tals como a navegación rapida en o modo de navegación u lo movimiento por linias u por paragrafos) no aturan  o charrar-lo Tot, en cuenta charrar-lo Tot blinca  t'a nueva posición y contina leyendo-ye.

##### chuflar si se Tecleya Letras Minusclas Quan o BloqMayus ye Activau {#KeyboardSettingsBeepLowercase}

Quan ye activada, s'escuitará un chufliu d'aviso si s'escribe una letra con a tecla mayus entre que o BloqMayus ye activau.
Por un regular, escribir letras en mayusclas con o BloqMayus ye desintencionau y normalment ye a causa de no revisar que o BloqMayus siga activau.
Por tanto, puet estar prou util estar alvertiu sobre isto.

<!-- KC:setting -->

##### Charrar as teclas d'ordens {#KeyboardSettingsSpeakCommandKeys}

Tecla: NVDA+4

Quan ye marcada significa que NVDA anunciará todas as teclas que no sigan caracters en escribir-las en o teclau. Isto inclui combinacions de teclas tals como control mas qualsiquier atra letra. 

##### Reproducir son pa las errors d'ortografía entre que s'escribe {#KeyboardSettingsAlertForSpellingErrors}

Quan ye enchegada reproduz un son curto de bomboloniu en que una parola que escribas contienga una error d'ortografía.
Ista opción nomás ye disponible si l'anunciau d'errors d'ortografía ye habilitau en o dialogo d'[opcions de formatiau de documentos](#DocumentFormattingSettings) d'o NVDA, que se troba en o dialogo d'opcions d'o NVDA.

##### Teclas de maneyo d'atras aplicacions {#KeyboardSettingsHandleKeys}

Ista opción permite a l'usuario controlar si cal que o NVDA maníe as pulsacions de teclas cheneradas por aplicacions tals como teclaus en pantalla y o software de reconoixencia de voz.
Ista opción ye enchegada por defecto, anque qualques usuarios pueden deseyar desenchegar-la, como los que escriben vietnamita con o software de mecanografía UniKey ya que ferá que la dentrada de caracters siga incorrecta.

#### Churi (NVDA+control+m) {#MouseSettings}

La categoría d'o churi d'o dialogo d'opcions d'o NVDA permite a lo NVDA de realizar un seguimiento d'o churi, reproducir chuflius d'as suyas coordinadas  y configurar atras opcions d'uso d'o churi.
Ista categoría contién los siguients achustes:

##### Anunciar os Cambios en a Forma d'o churi {#MouseSettingsShape}

Una caixeta de verificación, que quan se marca significa que o NVDA anunciará a forma d'o puntero d'o churi cada vez que cambee. 
O puntero d'o churi en Windows cambea a forma d'ell ta comunicar bella información tal como quan bella cosa ye editable, u quan bella cosa ye cargable etc.

<!-- KC:setting -->

##### Activar  o seguimiento  d'o churi {#MouseSettingsTracking}

Tecla: NVDA+m

Quan ye marcada significa que lo NVDA anunciará lo texto actualment baixo lo puntero d'o churi, seguntes lo muevas por a pantalla. Isto te permite trobar cosas en a pantalla, movendo fisicament lo churi, en cuenta de tractar de trobar-las a traviés d'o navegador d'obchectos.

##### Unidat de Resolución de Texto {#MouseSettingsTextUnit}

Si lo NVDA ye configurau pa anunciar lo texto baixo lo churi seguntes lo muevas, ista opción te permite trigar exactament quánto texto será charrau. 
Las opcions son caracter, parola, linia y paragrafo.

Pa cambiar la unidat de resolución de texto dende qualsiquier puesto, por favor asigna un cenyo personalizau fendo servir lo [dialogo de cenyos de dentrada](#InputGestures).

##### Anunciar lo paper quan o churi dentre en l'Obchecto {#MouseSettingsRole}

Si ista caixeta de verificación ye marcada, lo NVDA anunciará lo paper (mena) d'obchecto en que lo churi se i mueva adintro d'ell.

##### Reproducir son quan se mueva lo churi {#MouseSettingsAudio}

Marcando ista caixeta de verificación fas que lo NVDA reproduzca chuflius quan lo churi se mueva, asinas que l'usuario pueda resolver do ye o churi respective a las dimensions d'a pantalla.
Contra más alto siga o churi en a pantalla más alto o ton d'os chuflius.
Contra más t'a cucha u dreita  siga localizau o churi en a pantalla más t'a cucha u dreita se reproducirá o son (asumindo que l'usuario tien altavoces estereo u auriculars).

##### O Brilo controla o volumen d'as coordenadas d'o son {#MouseSettingsBrightness}

Si a caixeta de verificación 'reproducir son quan se mueva o churi' ye marcada, allora marcar ista caixeta de verificación significa que o volumen d'os chuflius d'audio ye controlau por cómo o brilo d'a pantalla siga baixo o churi. 
Isto ye desmarcau de traza predeterminada.

##### Ignorar la dentrada d'o churi dende atras aplicacions {#MouseSettingsHandleMouseControl}

Ista opción permite a l'usuario ignorar los eventos d'o churi (incluyindo lo movimiento d'o churi y las pretadas de botons) cheneraus por atras aplicacions como lo TeamViewer y atros programas de control remoto.
Ista opción ye desmarcada por defecto.
Si marcas ista opción y tiens enchegada la opción d'"enchegar lo seguimiento d'o churi", lo NVDA no anunciará lo que bi haiga debaixo d'o churi si lo mueve belatra aplicación.

#### Interacción tactil {#TouchInteraction}

Ista categoría d'opcions, nomás disponible en ordinadors que executen lo Windows 8 y posteriors con capacidatz tactils, te permite configurar la forma en que lo NVDA interactúa con las pantallas tactils.
Ista Categoría contién las siguients opcions:

##### Enchegar lo suporte d'interacción tactil {#TouchSupportEnable}

Ista caixeta de verificación enchega lo suporte d'interacción tactil d'o NVDA.
Si s'enchega, puetz emplegar los tuyos didos pa navegar y interactugar con os elementos en a pantalla fendo servir un dispositivo tactil.
Si se desenchega, lo suporte de pantalla tactil se desenchegará como si lo NVDA no estase correndo.
Ista opción tamién puede conmutar-se fendo servir NVDA+control+alt+t. 

##### Modo d'escritura tactil {#TouchTypingMode}

Ista caixeta de verificación te permite d'especificar o metodo que deseyas emplegar en ficar texto fendo servir o teclau tactil.
Si ista caixeta de verificación ye enchegada, en que trobes una tecla en o teclau tactil, puetz devantar o dido y a tecla seleccionada se pretará.
Si ye desenchegada, habrás de tocar dos veces a tecla en a pantalla pa pretar-la.

#### Cursor de revisión {#ReviewCursorSettings}

La categoría de cursor de revisión en o dialogo d'opcions d'o NVDA s'emplega pa configurar lo comportamiento d'o cursor de revisión d'o NVDA.
Ista categoría contién las siguients opcions:

<!-- KC:setting -->

##### Siguir a lo Foco d'o sistema {#ReviewCursorFollowFocus}

Tecla: NVDA+7

Quan s'activa, o cursor de revisión siempre se colocará en o mesmo obchecto que l'actual foco d'o sistema siempre que  iste  cambee.

<!-- KC:setting -->

##### Siguir a lo Cursor d'o Sistema {#ReviewCursorFollowCaret}

Tecla: NVDA+6

Quan s'activa, o cursor de revisión se moverá automaticament t'a posición d'o cursor d'o Sistema cada vez que se mueva.

##### Siguir a lo cursor d'o churi {#ReviewCursorFollowMouse}

Quan s'activa, o cursor de revisión seguirá a lo churi seguntes se mueva.

##### Modo de Revisión Simpla {#ReviewCursorSimple}

Quan s'activa, o NVDA filtrará a hierarquía d'obchectos que puet navegar-se, pa excluir qualsiquier obchecto que no siga de l'intrés ta l'usuario; p. eix.: obchectos inveyibles y obchectos utilizaus solament con propositos de disenyo.

Pa alternar lo modo de revisión dende do siga asigna un cenyo personalizau fendo servir lo [dialogo de cenyos de dentrada](#InputGestures).

#### Presentación d'obchectos (NVDA+control+o) {#ObjectPresentationSettings}

La categoría de presentación d'obchectos d'o dialogo d'opcions d'o NVDA s'emplega pa establir la cantidat d'información que lo NVDA presentará sobre controls tals como descripción, información de posición, etc.
Istas opcions no s'aplican tipicament a lo modo de navegación.
Istas opcions s'aplican tipicament a l'anunciau d'o foco y a la navegación d'obchectos d'o NVDA, pero no pas en leyer conteniu de texto, p.eix. lo modo de navegación.

##### Anunciar los consellos {#ObjectPresentationReportToolTips}

Una caixeta de verificación que quan ye marcada diz a lo NVDA que anuncie los consellos seguntes amaneixcan. 
Muitas finestras y controls amuestran un chicot mensache (u consello) quan mueves o puntero d'o churi sobre ells, u qualques veces quan te mueves con o foco por ells.

##### Anunciar las notificacions {#ObjectPresentationReportBalloons}

Ista caixeta de verificación quan ye marcada diz a lo NVDA que anuncie los globos d'aduya y las notificacions en que amaneixcan. 

* Los globos d'aduya son como los consellos, pero por un regular son mas grans, y son asociaus con eventos d'o Sistema tals como la desconnexión de bell cable de ret, u talment alertar-te sobre problemas de seguranza d'o Windows.
* Las notificacions se son introduitas en o Windows 10 y amaneixen en o centro de notificacions en a servilla d'o sistema, informando sobre qualques eventos (por eixemplo: si s'ha descargau bella actualización, ha amaneixiu bell nuevo correu electronico en a tuya servilla de dentrada, etc.).

##### Anunciar las teclas d'alcorce d'os obchectos {#ObjectPresentationShortcutKeys}

Quan ista caixeta de verificación ye verificada, lo NVDA incluirá la tecla d'alcorce que siga asociada con cierto obchecto u control en que siga anunciau. 
Por eixemplo o menú Fichero en una barra de menú podrá tener una tecla d'alcorce Alt+F.

##### Anunciar la información d'a posición de l'obchecto {#ObjectPresentationPositionInfo}

Ista opción te permite trigar en do deseyas tener una posición de l'obchecto anunciada (p. eix.: 1 de 4) quan te mueves ta l'obchecto con o foco u lo navegador d'obchectos.

##### Deducir la información de posición de un obchecto quan no siga disponible {#ObjectPresentationGuessPositionInfo}

Si l'anunciau d'información de posición de l'obchecto ye desenchegau, ista opción permite a lo NVDA deducir la información de posición de l'obchecto quan no siga disponible pa un control en particular.

Quan siga activau lo NVDA anunciará información de posición pa mas controls tals como los menús y las barras de ferramientas, manimenos ista información podrá estar licherament incorrecta. 

##### Anunciar las descripcions d'os obchectos {#ObjectPresentationReportDescriptions}

Desmarca ista caixeta de verificación si creyes que no te fa falta escuitar la descripción anunciada de conchunta con os obchectos.

<!-- KC:setting -->

##### Salida d'a Barra de Progreso {#ObjectPresentationProgressBarOutput}

Tecla: NVDA+u

Ista opción se te presienta con un quadro combinau que controla cómo anuncia lo NVDA as actualizacions d'as barras de progreso. 

Tien as siguients opcions:

* Desactivau: As barras de progreso no serán anunciadas seguntes en cambeen.
* Charrar: Ista opción diz a lo NVDA que charre as barras de progreso en porcentaches. Cada vez que a barra de progreso cambee, o NVDA charrará la valor nueva. 
* chuflar: Isto diz a lo NVDA que chufle cada vez que a barra de progreso cambee. Ta un chufliu mas alto, o completau d'a barra de progreso ye mas proximo
* chuflar y Charrar: Ista opción diz a lo NVDA que chufle y charre en que s'actualiza una barra de progreso.

##### Anunciar as Barras de Progreso en Segundo Plano {#ObjectPresentationReportBackgroundProgressBars}

Ista ye una opción que, quan ye marcada, diz a lo NVDA que mantienga l'anunciau d'una barra de progreso, encara si no'n ye fisicament en o primer plano. 
Si minimizas u cambeas ta unatra finestra que contienga una barra de progreso, o NVDA mantendrá a pista d'ella, permitindo-te fer atras cosetas mientras o NVDA sigue a la barra de progreso.

<!-- KC:setting -->

##### Anunciar os cambios de conteniu dinamico {#ObjectPresentationReportDynamicContent}

Tecla: NVDA+5

Commuta l'anunciau de conteniu nuevo en obchectos particulars tals como terminals y o control d'historico en programas de chat.

##### Reproducir un son en amaneixer sucherencias automaticas {#ObjectPresentationSuggestionSounds}

Cambia l'anunciau de l'aparición de sucherencias automaticas, y si ye enchegau, o NVDA reproducirá un son pa endicar-lo.
As sucherencias automaticas son listas de dentradas sucheridas basadas en o texto introduciu en qualques campos d'edición y documentos.
por eixemplo, quan introduzcas texto en o quadro de busca en o menú d'inicio en o Windows Vista y posteriors, o Windows amuestra una lista de sucherencias basadas en lo que escribiés.
Pa bells campos d'edición  tals como campos de busca en qualques aplicacions d'o Windows 10, o NVDA puet notificar-te que ha amaneixiu una lista de sucherencias en escribir-bi texto.
A lista de sucherencias automaticas se zarrará malas que te'n muevas por o campo d'edición, y pa bells campos, o NVDA puet notificar-te d'ixo en que ixo ocurra.

#### Redacción de dentrada {#InputCompositionSettings}

La categoría de redacción de dentrada te permite controlar cómo anuncia lo NVDA la dentrada de Caracters Asiaticos, tals como con IME u metodos de Servicio de dentrada de texto .
Tiene en cuenta que a causa d'o feito que los metodos de dentrada vareyan en gran mida por las suyas caracteristicas disponibles y por cómo transmiten la información, lo mas prebable será que siga necesario de configurar istas opcions de modo diferent pa cada metodo de dentrada pa obtener la experiencia d'escritura mas eficient.

##### Anunciar Automaticament totz os Candidatos Disponibles {#InputCompositionReportAllCandidates}

Ista opción, que ye activada de traza predeterminada, te permite trigar si totz os candidatos veyibles habrían d'anunciar-se automaticament en que amaneixca una lista de candidatos u a suya pachina cambee.
Tener ista opción activada pa metodos de dentrada pictografica tals como lo chino Nuevo ChangJie u lo Boshiami, ye util pos puetz escuitar totz os simbolos automaticament y os suyos numers y puetz trigar-ne un immediatament.
Manimenos, pa os metodos de dentrada foneticos tals como chino Nuevo Fonetico, Podría estar mas util desactivar ista opción ya que totz os simbolos sonarán igual y habrás d'emplegar as teclas de cursor pa navegar por os elementos d'a lista individualment pa obtener mas información d'a descripción de caracters pa cada candidato.

##### Anunciar lo Candidato trigau {#InputCompositionAnnounceSelectedCandidate}

Ista Opción, que ye activada por omisión, te permite trigar si o NVDA habría d'anunciar o candidato seleccionau en que amaneixe una lista de candidatos u quan a selección se cambió.
Pa os metodos de dentrada an a selección se puet cambiar con as teclas de flechas (tal como lo Chino Nueva Fonetica) isto ye necesario, pero pa qualques metodos de dentrada podría estar mas eficient tecliar con ista opción desactivada.
Para cuenta que agún con ista opción desactivada, o cursor de revisión encara se colocará sobre o candidato seleccionau permitindo-te emplegar a navegación d'obchectos ta revisar-ne manualment ta leyer iste u atros candidatos.

##### Incluir siempre una descripción curta d'o caracter quan s'anuncie candidatos {#InputCompositionCandidateIncludesShortCharacterDescription}

Ista Opción, que ye enchegada por defecto, te permite trigar si o NVDA habría de furnir u no pas una descripción curta pa cada caracter en un candidato, u en que se seleccione u en que  se leiga automaticament en que amaneixca la lista de candidatos.
Para cuenta que ta localizacions tals como lo Chino, l'anunciau de descripcions extra de caracters t'o candidato seleccionau no ye afectau por ista opción.
Ista opción podría estar util t'os metodos de dentrada Coreán y chaponés.

##### Anunciar los Cambios en a cadena de lectura {#InputCompositionReadingStringChanges}

Qualques metodos de dentrada como lo Chino Nuevo Fonetico y lo Nuevo ChangJie tienen una cadena de lectura (conoixida a veces como una cadena de precomposición).
Puetz trigar si o NVDA habría d'anunciar os caracters nuevos en estar tecliaus en ista cadena de lectura con ista opción.
Ista opción ye activada de traza predeterminada.
Para cuenta que qualques metodos de dentrada antigos tals como lo Chino ChangJie podrían no emplegar a cadena de lectura ta contener os caracters de precomposición, en cuenta podrían emplegar a cadena de composición dreitament. Por favor mira a siguient opción ta configurar l'anunciau d'a cadena de redacción. 

##### Anunciar los Cambios en a cadena de redacción {#InputCompositionCompositionStringChanges}

Dimpués que a lectura u os datos de precomposición haigan estau combinaus dentro d'un simbolo pictográfico valido, a mayoría d'os metodos de dentrada colocan iste simbolo dentro d'una cadena de composición ta un almagazenamiento temporal de conchunta con atros simbolos combinaus antis que finalment se fiquen dentro d'o documento.
Ista Opción te permite trigar si lo NVDA habría d'anunciar u no pas simbolos nuevos seguntes amaneixcan en a cadena de redacción.
Ista opción ye activada por omisión.

#### Modo de navegación (NVDA+control+b) {#BrowseModeSettings}

La categoría de modo de navegación d'o dialogo d'opcions d'o NVDA s'emplega pa configurar lo comportamiento d'o NVDA en leyer y en navegar por documentos compleixos como pachinas web.
Ista categoría contién las siguients opcions:

##### Maximo Numero de Caracters en Una Linia {#BrowseModeSettingsMaxLength}

Iste campo mete l'amplaria maxima d'una linia d'o modo virtual (en caracters).

##### Maximo numero de Linias por Pachina {#BrowseModeSettingsPageLines}

Iste campo achusta a cantidat de linias que moverás quan pretes Abance de pachina u Retroceso de pachina mientras sigas en o modo de navegación.

<!-- KC:setting -->

##### Fer servir o disenyo de pantalla {#BrowseModeSettingsScreenLayout}

Tecla: NVDA+v

Ista opción te permite especificar si lo conteniu en o modo de navegación ha de calar cosas tals como vinclos y atros campos cadagún en a suya propia linia, u si ha de conservar-los en o fluixo de texto seguntes s'amuestre visualment.
Si la opción ye enchegada, allora las cosas remanirán seguntes s'amuestren visualment, pero si ye desenchegada, allora los campos serán colocaus en a suya propia linia.

##### Enchegar lo modo de navegación en cargar la Pachina {#BrowseModeSettingsEnableOnPageLoad}

Ista caixeta de verificación cambia si s'ha d'enchegar automaticament lo modo de navegación en cargar una pachina.
Quan ista opción siga desenchegada, lo modo de navegación agún puede enchegar-se manualment en pachinas u en documentos en do s'admita lo modo de navegación.
Mira-te la [sección d'o modo de navegación](#BrowseMode) pa una lista d'as aplicacions admitidas por lo modo de navegación.
Tiene en cuenta que ista opción no s'aplica a situacions en qe lo modo de navegación siga siempre opcional, por eixemplo, en o Microsoft Word.
Ista opción ye enchegada por defecto.

##### Charrar-lo Tot Automaticament en Cargar a Pachina {#BrowseModeSettingsAutoSayAll}

Ista caixeta de verificación commuta a verbalización automatica d'una pachina dimpués de cargar-la en o modo de navegación.
Ista opción ye activada por defecto.

##### Incluir as Tablas de Disenyo {#BrowseModeSettingsIncludeLayoutTables}

Ista opción afecta a cómo manea lo NVDA las tablas utilizadas exclusivament con fins de disenyo.
Quan ye activada, NVDA las tracta como tablas normals, anunciando-las basando-se en as [Opcions de Formatiau de Documento](#DocumentFormattingSettings) y localizando-las con as ordens de navegación rapida.
Quan ye desactivada, no s'anuncian ni se troban con a navegación rapida.
Manimenos, o conteniu d'as tablas encara s'incluirá como texto normal.
Ista opción ye desactivada de traza predeterminada.

Pa conmutar a inclusión d'as tablas de disenyo dende qualsiquier puesto, asigna bell cenyo personalizau fendo servir o [dialogo de cenyos de dentrada](#InputGestures).

##### Configurando l'anunciau de campos tals como vinclos y capiters {#BrowseModeLinksAndHeadings}

Por favor mira-te las opcions en a  [categoría de formatiau de documentos](#DocumentFormattingSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings) pa configurar los campos que s'anuncia quan se navega, tals como vinclos, capiters y tablas.

##### Modo de foco automatico pa cambios d'o foco {#BrowseModeSettingsAutoPassThroughOnFocusChange}

Ista opción permite a lo modo de foco d'invocar-se si o foco cambea. 
Por eixemplo, quan yes en una pachina Web, si pretas o tabulador y cayes sobre un formulario, si ista opción ye verificada, o modo de foco s'invocará automaticament.

##### Modo de foco automatico pa lo movimiento d'o cursor {#BrowseModeSettingsAutoPassThroughOnCaretMove}

Ista opción, quan ye marcada, permite a lo NVDA dentrar en y abandonar o modo de foco en que s'utilizan as flechas. 
Por eixemplo, si vas pretando flecha abaixo por una pachina Web y cayes sobre un quadro d'edición, lo NVDA activará automaticament lo modo de foco. 
Si pretas las flechas pa salir d'o quadro d'edición, lo NVDA te tornará a meter en o modo de navegación.

##### Indicación d'audio d'os modos de foco y de navegación {#BrowseModeSettingsPassThroughAudioIndication}

Si ista opción ye activada lo NVDA reproducirá sons especials quan cambeye entre o modo de navegación y o modo de foco en cuenta de charrar o cambeo.

##### Capturar los cenyos que no son comandos pa que no aconsigan lo  documento {#BrowseModeSettingsTrapNonCommandGestures}

Enchegada de traza predeterminada, ista opción te permite trigar si os cenyos (tals como la pretada de teclas) que no sigan comandos d'o NVDA y que no se considere que sigan teclas de comandos en cheneral habrían de capturar-sen pa no pasar t'o documento que siga en o foco actualment. 
Como un eixemplo, en estar enchegada, si se pretó la letra j habría de capturar-se pa no aconseguir lo documento ya que no ye ni una tecla de navegación rapeda ni ye prebable que siga un comando d'a mesma aplicación.
En ixe caso lo NVDA pedirá a lo Windows que reproduzca un son predeterminau por cada vez que se prete una tecla que quede apercazada.

##### Meter lo Foco d'o Sistema Automaticament en os Elementos Enfocables {#BrowseModeSettingsAutoFocusFocusableElements}

Tecla: NVDA+8

Desenchegada por defecto, ista opción te permite trigar si lo foco d'o sistema s'habría de meter automaticament en os elementos que puedan tener lo foco d'o sistema (vinclos, campos de formulario, etc.) en navegar por contenius con lo cursor d'o modo de navegación.
Deixando ista opción desenchegada no s'enfocará automaticament los elementos enfocables  en que se seleccionen con o cursor d'o modo de navegación.
Ixo podría fer como resultau una experiencia de navegación mas rapeda y una millor respuesta en o modo de navegación.
Lo foco encara s'esviellará en l'elemento en particular en que s'interactugue con ell (eix.: pretando un botón u marcando una caixeta de verificación).
Enchegar ista opción puede amillorar lo suporte pa bells puestos web a costa d'o rendimiento y d'a estabilidat.

#### Formatiau de documentos (NVDA+control+d) {#DocumentFormattingSettings}

A mayoría d'as caixetas de verificación en iste dialogo son pa configurar qué tipo de formato deseyas d'escuitar automaticament en que muevas o cursor por os documentos. 
Por Eixemplo, si marcas a caixeta de verificación anunciar o nombre d'a fuent, cada vez que navegues por o texto con una fuent diferent, o nombre d'a fuent será anunciau.

Las opcions de formatiau de documentos son organizadas en grupos.
Puetz configurar l'anunciau de:

* Fuent
 * Nombre d'a fuent
 * Grandaria d'a fuent
 * Atributos d'a fuent
 * Superescritos y subescritos
 * Enfasi
 * Texto resaltau (marcau)
 * Estilo
 * Colors
* Información de documento
 * Comentarios
 * Revisions de l'editor
 * Errors d'ortografía
* Pachinas y espaciau
 * Numers de pachina
 * Numers de linia
 * Anunciau d'a sangría de linia (desenchegau, fabla, tons, todas dos fabla y tons) #DocumentFormattingSettingsLineIndentation
 * Sangría de paragrafo (por eixemplo: sangría francesa, sangría d'a primera linia)
 * Espaciau de linia (simple, dople, etc.)
 * Aliniación
* Información de tabla
 * Tablas
 * Capiters de ringlera y columna
 * Coordenadas de celdas
 * Cantos d'as celdas [(desenchegau, estilos, totz dos Colors y estilos)
* Elementos
 * Capiters
 * Vinclos
 * Graficos
 * Listas
 * Citas
 * Grupos
 * Zonas
 * Articlos
 * Bastidas
 * Clicable

Pa trigar istas opcions dende qualsiquier puesto asigna cenyos personalizaus fendo servir o [dialogo de cenyos de dentrada](#InputGestures).

##### Anunciar los cambios de formato dimpués d'o cursor {#DocumentFormattingDetectFormatAfterCursor}

Si ye activada, ista opción diz a lo NVDA que prebe y detecte totz os cambeos de formato en una linia seguntes l'anuncia, si se fa isto podría ralentizar-se a rispuesta d'o NVDA.

De traza predeterminada, o NVDA detectará o formato en a posición d'o cursor d'o Sistema / Revisión, y en qualques casos podría detectar o formato en a resta d'a linia, nomás si no bi ye causando un decremento d'a respuesta.

Enchega ista opción mientras comprebas a lectura de documentos en aplicacions tals como lo WordPad en do lo formato ye important.

##### Anunciau d'a sangría d'a linia {#DocumentFormattingSettingsLineIndentation}

Ista opción te permite configurar cómow s'anuncia a sangría en o prencipio d'as linias.
O quadro combinau d'"anunciar a sangría d'a linia con" tien quatro opcions.

* Desenchegau: O NVDA no tractará a sangría de traza especial.
* Voz: Si se triga voz, en que a cantidat d'a sangría cambeye o NVDA dirá bella cosa como "dotze espacio" u "quatro tabulación."
* Tons: Si se triga tons, en que a cantidat de sangría cambeye os tons indicarán a cantidat de cambeyo en a sangría.
O ton puyará de ton cada espacio, y pa una tabulación, puyará os tons equivalents a 4 espacios.
* Todas dos, voz y tons: Ista opción leye a sangría fendo servir totz dos metodos debantditos.

#### Opcions de l'OCR d'o Windows {#Win10OcrSettings}

Las opcions en ista categoría te permiten configurar [l'OCR d'o Windows](#Win10Ocr).
Ista categoría contién las siguients opcions:

##### Idioma de reconoixencia {#Win10OcrSettingsRecognitionLanguage}

Iste quadro combinau te permite esleyir l'idioma pa emplegar con a reconoixencia de texto.

#### Opcions Abanzadas {#AdvancedSettings}

Alvertencia! Las opcions d'ista categoría son pa los usuarios abanzaus y pueden causar que lo NVDA no marche correctament si se configura de traza incorrecta.
Rializa cambios en istas opcions nomás si yes seguro que sabes lo que yes fendo u si has recibiu las instruccions especificas de bell desembolicador d'o NVDA.

##### Fer cambios en as opcions abanzadas {#AdvancedSettingsMakingChanges}

Pa rializar cambios en as Opcions Abanzadas, los controls han d'estar enchegaus confirmando con a caixeta de verificación, que comprendes los risgos de modificar ixas opcions.

##### Restablir las opcions predeterminadas {#AdvancedSettingsRestoringDefaults}

Lo botón restableix las valors predeterminadas pa las opcions, mesmo si la caixeta de confirmación no ye marcada.
Dimpués de cambiar las opcions ye posible que deseyes tornar t'as valors predeterminadas.
Ixe tamién puet estar lo caso si no yes seguro que s'haiga cambiau las opcions.

##### Enchegar la carga de codigo personalizau dende lo directorio Developer Scratchpad {#AdvancedSettingsEnableScratchpad}

En desembolicar complementos pa lo NVDA, ye util poder prebar lo codigo enrte que l'escribes.
Ista opción en estar enchegada, permite a lo NVDA cargar appModules personalizaus, globalPlugins, brailleDisplayDrivers y synthDrivers, dende un directorio especial de desembolicadors scratchpad d'o tuyo directorio de configuración d'usuario d'o NVDA.
Anteriorment, lo NVDA cargaba codigo personalizau dreitament dende lo directorio de configuración de l'usuario, sin posibilidat de desenchegar-lo.
Ista opción ye desenchegada de forma predeterminada, lo que guarencia que nunca no s'execute garra codigo no prebau en o NVDA sin la conoixencia explicita de l'usuario.
Si deseyas distribuyir codigo personalizau a otris, has d'empaquetar-lo como un complemento d'o NVDA.

##### Ubrir lo directorio Developer Scratchpad {#AdvancedSettingsOpenScratchpadDir}

Iste botón ubre lo directorio en do puetz colocar lo codigo personalizau mientras lo desembolicas.
Iste botón nomás ye enchegau si lo NVDA ye configurau pa permitir la carga de codigo personalizau dende lo directorio de desembolicadors d'o Scratchpad.

##### Enchegar lo rechistro selectivo pa los eventos y cambios de propiedatz pa l'UI Automation {#AdvancedSettingsSelectiveUIAEventRegistration}

Ista opción cambia cómo rechistra lo NVDA los eventos aventaus por l'API d'accesibilidad Microsoft UI Automation.
Quan ista opción ye desenchegada, lo NVDA rechistra muitos  eventos UIA que se procesan y se descartan adintro d'o mesmo NVDA.
Ixo tien un mayor impacto negativo en o rendimiento, especialment en as aplicacions como lo Microsoft Visual Studio.
Por lo tanto, quan s'enchega ista opción, lo NVDA limitará lo rechistro d'eventos a lo foco d'o sistema pa la mayoría d'os eventos.
Si sufres problemas de rendimiento en una u mas aplicacions, te recomendamos que prebes ista funcionalidat a mirar si lo rendimiento amillora.

##### Fer servir l'UI automation pa acceder ta controls de documento d'o Microsoft Word quan siga disponible {#AdvancedSettingsUseUiaForWord}

Quan ista opción siga activada, lo NVDA mirará de fer servir l'API d'accesibilidat de Microsoft UI Automation pa obtener información d'os controls de documentos d'o Microsoft Word, mesmo pa las versions menos recients d'o Microsoft Office 2016 / 365.
Ixo incluye lo mesmo Microsoft Word, y tamién lo visor de mensaches y la redacción d'o Microsoft Outlook.
Pa las versions mas recients d'o Microsoft Office 2016 / 365 correndo sobre lo WIndows 10 y posteriors, lo suporte d'UI Automation ye prou completo pa furnir acceso ta docuemntos d'o Microsoft Word quasi igual como lo suporte existtent d'o NVDA pa lo Microsoft Word, con l'avantalla anyadida que la respuesta ye mayorment amillorada. 
Manimenos, podría haber-bi bella información que no siga exposada, u exposada incorrectament en bellas  construccions mas viellas d'o Microsoft Office, lo que quiere decir que no siempre se puet confidar con iste suporte d'UI automation.
Encara no se recomienda que la mas gran parti d'usuarios encheguen isto por defecto, anque son bienvenius los usuarios de l'Office 2016 / 365 que preben ista caracteristica y en furneixcan retroalimentación.

##### Fer servir l'UI Automation pa acceder t'a consola d'o Windows quan siga disponible {#AdvancedSettingsConsoleUIA}

Quan ista opción siga enchegada, lo NVDA fará servir lo suyo suporte pa la consola d'o Windows que da avantallas de [milloras d'accesibilidat feitas por Microsoft](https://devblogs.microsoft.com/commandline/whats-new-in-windows-console-in-windows-10-fall-creators-update/). Ista caracteristica ye sumament experimental y encara ye incompleta conque l'uso suyo encara no ye recomendau. Manimenos, una vez completau, ixo anticipa que ixe suporte nuevo esdevienga lo predeterminau, amillorando lo rendimiento y la estabilidat d'o NVDA en as consolas de comandos d'o Windows.

##### Verbalizar as Claus en as consolas UIA {#AdvancedSettingsWinConsoleSpeakPasswords}

Ista opción controla si los caracters se charran por [charrar los caracters en escribir-los](#KeyboardSettingsSpeakTypedCharacters) u [charrar las parolas en escribir-las](#KeyboardSettingsSpeakTypedWords) en situgacions en que la pantalla no s'actualice (tal como la dentrada de contraseñas) en a consola d'o Windows con a compatibilidat con l'UI automation enchegada. Por razons de seguridat, ixa opción ha de deixar-se desenchegada. Manimenos, ye posible que deseyes enchegar-la si experimentas problemas de rendimiento u inestabilidat con l'anunciau d'os caracters y/u las parolas escritas mientras s'emplegue lo nuevo suporte experimental pa consolas d'o NVDA.

##### Fer servir l'UIA con o Microsoft Edge y atros navegadors basaus en o Chromium quan siga disponible {#ChromiumUIA}

Permite especificar que s'utilizará l'UIA quan siga disponible en os navegadors basaus en o Chromium tals como lo Microsoft Edge.
Lo suporte UIA pa los navegadors basaus en o Chromium ye en una fase temprana de desembolique y puet estar que no ufra lo mesmo libel d'acceso que IA2.
Lo quadro combinau tiene las siguients opcions:

* Por defecto (Nomás quan ye necesario): La valor por defecto d'o NVDA, actualment ye "Nomás quan siga necesario". Ixa valor por defecto puet cambear en o futuro a mida que la tecnolochía madure.
* Nomás quan siga necesario: Quan lo NVDA no pueda inyectar en o proceso d'o navegador pa usar IA2 y UIA siga disponible, allora lo NVDA tornará a usar UIA.
* Sí: si lo navegador fa accesible a UIA, lo NVDA lo utilizará.
* No: no utiliza UIA, mesmo si lo NVDA no puet inyectar en o proceso. Esto puede estar util pa los desembolicadors que depuren problemas con IA2 y quieren asegurar-se que lo NVDA no torne a utilizar UIA.

##### Anotacions {#Annotations}

Iste grupo d'opcions s'emplega pa enchegar caracteristicas que adhiben suporte experimental pa las anotacions ARIA.
Belunas d'istas caracteristicas pueden estar incompletas.
Existe las siguients opcions: 

* "Anunciar los detalles en o modo de navegación": enchega l'anunciau si un obchecto tien detalles en o modo de navegación.
L'anunciau d'o resumen d'ixos detalles se puet fer asignando-bi un cenyo fendo servir lo [dialogo de cenyos de dentrada](#InputGestures).
* "Anunciar siempre las descripcions aria":
  Quan la fuent de `accDescription` ye aria-description, s'anuncia la descripción.
  Ixo ye util pa las anotacions en a web.
  Nota:
  * Bi ha muitas fuents pa `accDescription` belunas tienen una semantica mixta u poco fidable.
    Historicament AT no ye estau capaz de diferenciar las fuents de `accDescription` tipicament no se verbalizaba a causa d'a semantica mixta.
  * Ista opción ye en un desembolique muito primitivo, se basa en as caracteristicas d'o navegador que encara no son ampliament disponibles.
  * S'aspera que funcione con Chromium 92.0.4479.0+

##### Fer servir l'UI automation pa acceder ta controls en fuellas de calculo d'o Microsoft  Excel quan siga disponible {#UseUiaForExcel}

Quan ista opción ye enchegada, lo NVDA mirará d'emplegar l'API d'accesibilidat Microsoft UI Automation  pa obtener información d'os controls d'as fuellas de calculo d'o Microsoft Excel.
Ista ye una funcionalidat experimental y qualques caracteristicas d'o Microsoft Excel pueden no estar disponibles en iste modo.
Por eixemplo, las caracteristicas d'a Lista d'Elementos d'o NVDA pa enumerar formulas y comentarios y la tecla rapida de navegación d'o modo de navegación pa blincar campos de formulario en una fuella de calculo no son disponibles.
Manimenos, pa la navegación y edición basica d'as fuellas de calculo, ista opción puet furnir una gran millora de rendimiento.
Encara no recomendamos que la mayoría d'os usuarios encheguen ista opción por defecto, encara que convidamos a los usuarios d'o Microsoft Excel  compilación 16.0.13522.10000 u superior a que preben ista función y nos den la suya opinión.
La implementación de UI automation d'o Microsoft Excel cambea constantment y ye posible que las versions d'o Microsoft Office anteriors a la 16.0.13522.10000 puedan no exposar prou información pa que ista opción siga util.

##### Fer servir lo suporte nuevo de caracters escritos en a consola d'o Windows quan siga disponible {#AdvancedSettingsKeyboardSupportInLegacy}

Ista opción enchega un metodo alternativo pa detectar caracters en escribir en as consolas de comandos d'o Windows.
Encara que amillora lo rendimiento y priva que s'especifique la salida d'a consola, puede estar incompatible con qualques programas de terminal.
Ista caracteristica ye disponible y enchegada por defecto en versions d'o Windows 10 1607 y posteriors quan l'UI Automation no siga disponible u siga desenchegau.
Alvertencia: con ista opción enchegada, los caracters escritos que no amaneixcan en a pantalla, tals como las claus, no se suprimirán.
En entornos no confidables, podrás desenchegar temporalment lo [charrar los caracters en escribir-los](#KeyboardSettingsSpeakTypedCharacters) y lo [charrar las parolas en escribir-las](#KeyboardSettingsSpeakTypedWords) en ficar claus.

##### Algorismo Diff {#DiffAlgo}

Ista opción controla la forma en a quala lo NVDA determina lo nuevo texto pa charrar en as terminals.
Lo quadro combinau de l'algorismo diff tiene tres opcions:

* Automatico: a partir d'o NVDA 2021.2, ista opción equivale a "permitir Diff Match Patch".
* Permitir Diff Match Patch: Ista opción fa que lo NVDA calcule los cambeos por caracters en o texto d'a terminal.
Puet amillorar lo rendimiento quan s'escriba grans volumens de texto en a consola y permite un anunciau mas preciso d'os cambeos rializaus en o meyo d'as linias.
Manimenos puet estar incompatible con qualques aplicacions, allora no se i emplega lo Diff Match Patch.
Ista función ye compatible con a consola d'o Windows en o Windows 10 versión 1607 y posteriors.
Amás, puet estar disponible en atras terminals en versions anteriors d'o Windows.
* Aforzar lo Difflib: Ista opción fa que lo NVDA calcule los cambeos en o texto d'a terminal por linias.
Ye identico a lo comportamiento d'o NVDA en a versión 2020.4 y anteriors.

##### Mirar de cancelar la voz pa eventos d'expiración d'o foco {#CancelExpiredFocusSpeech}

Ista opción enchega lo comportamiento que mira de cancelar la voz pa eventos d'expiración d'o foco.
Concretament mover-se rapedament a traviés de mensaches en o Gmail con o Chrome puet causar que lo NVDA charre información aviellada.
Ista funcionalidat ye enchegada por defecto dende lo NVDA 2021.1.

##### Tiempo d'aspera pa lo movimiento d'o cursor (en MS) {#AdvancedSettingsCaretMoveTimeout}

Ista opción te permite configurar lo numero de milisegundos que lo NVDA asperará a que lo cursor (punto d'inserción) se mueva en os controls de texto editables.
Si veyes que lo NVDA aparenta estar seguindo incorrectament lo cursor, por eixemplo, pareixe estar siempre un caracter per dezaga u repetindo linias, alavez puetz intentar aumentar ista valor.

##### Anunciar la transparencia d'as colors {#ReportTransparentColors}

Ista opción permite anunciar quan son transparents las colors, util pa los desembolicadors de complementos y modulos d'aplicación que chuntan información pa amillorar la experiencia de l'usuario con una aplicación de tercers.
Qualques aplicacions GDI resaltan lo texto con una color de fundo, lo NVDA (a traviés d'o modelo de visualización) mira d'informar d'ixa color.
En qualques situgacions, lo fundo d'o texto puet estar transparent de raso, con o texto en capas sobre belatro elemento d'a GUI.
Con quantas APIs de GUI historicament populars, lo texto puet estar renderizau con un fundo transparent, pero visualment la color de fondo cal.

##### Categorías d'o rechistro de depuración {#AdvancedSettingsDebugLoggingCategories}

Las caixetas de verificación d'ista lista te permiten enchegar categorías especificas de mensaches de depuración en o rechistro d'o NVDA.
Lo rechistro d'ixos mensaches puede resultar en un menor rendimiento y en fichers de rechistro de gran grandaria.
Activa-ne nomás un d'ells si bell desembolicador d'o NVDA t'ha dau instruccions especificas, por eixemplo, a lo depurar por qué un controlador de linia braille no ye funcionando correctament.

##### Reproducir un son pa las errors rechistradas {#PlayErrorSound}

Ista opción permite especificar si lo NVDA reproducirá un son d'error caso que se rechistre una error.
Trigando Nomás en versions de preba (por defecto) fa que lo NVDA reproduzca sons d'error nomás si la versión actual de NVDA ye una versión de preba (alfa, beta u executada dende lo codigo fuent).
Trigando Sí permite enchegar los sons d'error qualsiquiera que siga la versión actual d'o NVDA.

### Opcions miscelanias {#MiscSettings}

Amás d'o dialogo d'[opcions d'o NVDA](#NVDASettings), lo submenú Preferencias d'o menú NVDA contién atros elementos que se describe contino.

#### Diccionarios d'a Fabla {#SpeechDictionaries}

O menú de Diccionarios d'a fabla, (trobau en o menú Preferencias) contién dialogos que te permiten controlar o modo en que o NVDA pronuncia parolas u frases particulars. 
Bi ha actualment tres menas diferents de diccionarios d'a fabla. 
son:

* Predeterminau: Las reglas en iste diccionario afectan a todas las voces en o NVDA.
* Voz: un diccionario que las suyas reglas afectan a la voz pa lo sintetizador que actualment ye estando utilizau.
* Temporal: Las reglas en iste diccionario afectan a todas las voces en lo NVDA, pero nomás pa la sesión actual. Istas reglas son temporals y se perderán si se reenchega lo NVDA

Te fa falta asignar cenyos personalizaus fendo servir lo [dialogo de cenyos de dentrada](#InputGestures) si deseyas ubrir bel'un d-istos dialogsos de diccionario dende qualsiquier puesto.

Totz los dialogos de diccionario contienen una lista de reglas que serán utilizadas pa procesar a voz. 
Lo dialogo tamién contién os botons Adhibir, Editar y Eliminar.

Pa adhibir un nuevo regle a lo diccionario, preta o botón Adhibir, y replena os campos d'o quadro de dialogo que amaneix y allora preta Acceptar. 
Allora berás o tuyo nuevo regle en a lista de regles. 
Asinasmesmo pa asegurar-te que o tuyo regle ye actualment alzau, asegura-te de pretar Acceptar pa salir completament d'o dialogo de diccionario Una vez haigas finalizau d'adhibir/editar regles.

Los regles pa los diccionarios de voz d'o NVDA te permiten cambiar una cadena de caracters por unatra. 
Por eixemplo, si quereses tener lo NVDA decindo a parola mixín cada vez que hese de decir a parola can. 
En o dialogo d'adhibir un regle, o modo mas facil de fer isto ye tecliar a parola can en o campo Patrón, y a parola mixín en o campo de substitución. 
podrías tamién querer tecliar una descripción d'o regle en o campo Comentario (bella cosa como: cambiar can por mixín).

Los diccionarios d'a fabla d'o NVDA asinasmesmo son muito mas poderosos que un simple reemplazo de parolas. 
Lo dialogo d'Adhibir regles tamién contién Una Caixeta de verificación que diz si quiers u no pas que o regle siga sensible a las mayusclas (significando que o NVDA habría de parar cuenta si os caracters son en mayusclas u en minusclas. 
Lo NVDA ignora las mayusclas y minusclas de traza predeterminada). 

Finalment, un conchunto de botons de radio te permite dicir-le a lo NVDA si o tuyo patrón ha de coincidir en cualsiquier puesto, ha de coincidir nomás si ye una parola completa u ha d'estar tractau como una "expresión regular".
Establir o patrón pa coincidir con una parola completa significa que nomás se ferá a substitución si o patrón no coincide con parti d'una parola larga.
Ixa condición se cumple si los caracters immediatament anterior y posterior a la parola no son una letra, un numero u un guión baixo, u si no bi ha garra caracter.
Por tanto, fendo servir l'eixemplo anterior d'a substitución d'a parola "can" con "mixín", si fueses a fer d'iste conchunto un reemplazo de parola, sería no coincidir con "canya" u "cans".

Una expresión regular ye un patrón que contién simbolos especials que te permiten emparellar mas d'un caracter de vez, u emparellar nomás numers, u nomás letras, seguntes bells pocos eixemplos. 
Las expresions regulars no son cubiertas en ista Guida de l'Usuario.
Pa un tutorial introductorio, por favor mira-te [https://docs.python.org/3.7/howto/regex.html].

#### Pronuncia de Puntuación y simbolos {#SymbolPronunciation}

Iste dialogo te permite cambiar lo modo en que son pronunciaus la puntuación y atros simbolos, asinas como o libel d'os simbolos en que se'n verbalizan. 

L'idioma que se ye editando a suya pronuncia  de simbolos s'amostrará en o titol d'o dialogo.
Tiene en cuenta que iste dialogo respecta la opción "Confidar en l'idioma d'a voz en procesar simbolos y caracters" que se troba en a [categoría de voz](#SpeechSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings) ye decir, fa servir l'idioma d'a voz en cuenta d'a opción de l'idioma global d'o NVDA quan ixa opción siga habilitada.

Pa cambiar un simbolo, en primeras selecciona-lo en a lísta de Simbolos.
Puetz tresminar los simbolos ficando lo simbolo u una parti d'a suya substitución en o quadro d'edición de tresminar por.

* Lo campo de reemplazar te permite cambiar lo texto que habría de charrar-se en cuenta d'iste simbolo.
* Fendo servir lo campo de libel puetz achustar lo libel mas baixo d'o simbolo tal como ixe simbolo habría de charrar-se.
* Lo campo de ninviar lo simbolo rial t'o sintetizador especifica quan habría de ninviar-se t'o sintetizador lo simbolo (en contraste con a suya substitución) .
Ixo ye util si lo simbolo causa que lo sintetizador se pause u cambie la entonación d'a voz.
Por eixemplo una coma causa que o sintetizador se pause.
Bi ha tres opcions:
* nunca: Nunca no ninviar lo simbolo rial t'o sintetizador.
 * siempre: Ninviar siempre lo simbolo real t'o sintetizador.
 * nomás por baixo  d'o libel d'os simbolos: Ninviar o simbolo real nomás si o libel de simbolos d'a fabla configurauye mas baixo que no lo libel establiu por iste simbolo.
 Por eixemplo, podrías fer servir ixo pa que bell simbolo tienga a suya substitución charrada en os libels mas altos sin pausar-se-ne mientras agún ye indicada con una pausa en os libels más baixos.

Puetz adhibir simbolos nuevos pretando lo botón d'adhibir.
En o dialogo que amaneixca introduz lo simbolo y preta lo botón d'acceptar.
Allora cambia los campos pa lo simbolo nuevo como lo ferías pa atros simbolos.

Puetz eliminar un simbolo que adhibiés anteriorment pretando lo botón d'eliminar.

En que remates, preta lo botón d'acceptar pa alzar los tuyos cambios u lo botón de cancelar pa descartar-los.

En o caso de simbolos compleixos, lo campo de reemplazar puede haber d'incluyir qualques referencias de grupo d'o texto coincident. Por eixemplo, pa un patrón que coincida con una calendata completa, \1, \2, y \3 habría d'amaneixer en o campo, pa estar reemplazau por las partis correspondients d'a calendata.
Por tanto, las barras inversas normals en o campo de reemplazar habrían de duplicar-sen, por eixemplo, "a\\b" habría d'escribir-se pa obtener lo reemplazo "a\b".

#### Cenyos de Dentrada {#InputGestures}

En iste dialogo, puetz personalizar os cenyos de dentrada (teclas en o teclau, botons en a pantalla braille, etc.) ta ordens d'o NVDA.

Nomás s'amuestran as ordens que s'apliquen immediatament antis que o dialogo s'ubra.
Por eixemplo, si quiers personalizar ordens relacionadas con o modo de navegación, habrías d'ubrir o dialogo Cenyos de dentrada mientras sigas en o modo de navegación.

L'arbol en iste quadro de dialogo amuestra todas as ordens d'o NVDA aplicables agrupadas por categorías.
Puetz tresminar-los introducindo una u más parolas d'o nombre d'os cenyos adentro d'o quadro d'edición Tresminar-ne por en qualsiquier orden.
Qualsiquier cenyo asociau con una orden se lista baixo ixa orden.

Pa adhibir un cenyo de dentrada a una orden, selecciona la orden y preta lo botón d'adhibir.
Contino, realiza lo cenyo de dentrada que deseyes asociar, por eixemplo, preta una tecla d'o teclau u un botón en una pantalla Braille.
A ormino, un cenyo puet interpretar-se de mas d'una traza.
Por eixemplo, si has pretau una tecla en o teclau, puet que deseyes que siga especifica t'a distribución de teclau actual (por eixemplo, d'escritorio u portatil) u puet que deseyes que s'aplique a todas as distribucions.
En iste caso, amaneixerá un menú que te permite seleccionar a opción deseyada.

Pa borrar un cenyo d'una orden, selecciona lo cenyo y preta lo botón d'eliminar.

La categoría de teclas emuladas d'o teclau d'o sistema contiene comandos d'o NVDA que emulan teclas d'o teclau d'o sistema.
Ixas teclas emuladas d'o teclado d'o sistema pueden emplegar-se pa controlar un teclau d'o sistema dreitament dende la tuya linia braille.
Pa anyadir bell cenyo de dentrada emulau, selecciona la categoría de teclas emuladas d'o teclau d'o sistema y preta lo botón d'anyadir.
Allora, preta en o teclau la tecla que deseyes emular.
Dimpués d'ixo, la tecla será disponible dende la categoría de teclas emuladas d'o teclau d'o sistema y podrás asignarli un cenyo de dentrada seguntes s'ha descrito anteriorment.

Para cuenta:

 * Las teclas asignadas han de tener cenyos asignaus pa persistir quan s'alcen u se zarre lo dialogo.
 * Un cenyo de dentrada con teclas modificaderas puede no estar capaz de mapiar-se ta un cenyo emulau sin teclas modificaderas.
 Por eixemplo, configurar la dentrada emulada 'a' y configurar un cenyo de dentrada de 'ctrl+m', puede resultar 
 en que l'aplicación reciba un 'ctrl+a'.

En que haigas rematau de rializar cambeos, preta lo botón d'acceptar pa alzar-los u lo botón de cancelar pa descartar-los.

### Alzando y Recargando la configuración {#SavingAndReloading}

De traza predeterminada lo NVDA alzará automaticament las tuyas opcions en salir.
Para cuenta, manimenos, que ista opción predeterminada puet cambiar-se baixo las opcions chenerals en o menú de preferencias. 
Pa alzar las opcions manualment en qualsiquier ocasión, triga l'elemento d'alzar la configuración en o menú d'o NVDA.

Si t'entivocas con as tuyas opcions y te cal tornar t'as opcions alzadas, puetz trigar l'elemento "tornar t'a configuración alzada" en o menú d'o NVDA.
Tamién puetz reiniciar as tuyas opcions a las suyas valors predeterminadas de fabrica orichinals trigando Reiniciar a Configuración t'as Valors Predeterminadas de Fabrica, que tamién se troba en o menú NVDA.

As siguients teclas d'ordens d'o NVDA tamién son utils:
<!-- KC:beginInclude -->

| Nombre |Tecla Sobremesa |Tecla Portatil |Descripción|
|---|---|---|---|
|Alzar a configuración |NVDA+control+c |NVDA+control+c |Alza a tuya configuración actual tal que no se pierda quan salgas d'o NVDA|
|Revertir a configuración |NVDA+control+r |NVDA+control+r |Pretando-ne una vez reinicia a tuya configuración a quan la alcés por zaguera vez. Pretando-ne tres veces la reiniciará t'as valors predeterminadas de fabrica.|

<!-- KC:endInclude -->

### Perfils de Configuración {#ConfigurationProfiles}

A veces, ye posible que deseyes tener diferents configuracions pa diferents situacions.
Por eixemplo, ye posible que deseyes tener l'anunciau de sangría habilitau mientras yes editando u l'anunciau d'os atributos d'a fuent activau mientras yes correchindo.
Lo NVDA te permite fer ixo fendo servir perfils de configuración.

Un perfil de configuración contién nomás las opcions que se cambian mientras que lo perfil ye estando editau.
La mayoría d'as opcions se pueden cambiar en os perfils de configuración difueras d'ixas que sigan en a categoría cheneral d'o dialogo d'[opcions d'o NVDA](#NVDASettings) , que s'aplican a la totalidat d'o NVDA.

Los perfils de configuración pueden enchegar-sen manualment, ya siga dende un quadro de dialogo u fendo servir cenyos anyadius personalizaus.
Tamién se pueden enchegar de traza automatica a causa de disparadors tals como lo cambio ta una aplicación en particular.

#### Maneyo Basico {#ProfilesBasicManagement}

Maneyas os perfils de configuración seleccionando "Perfils de Configuración" en o menú NVDA.
Tamién puetz fer isto utilizando una orden de teclau:
<!-- KC:beginInclude -->

* NVDA+control+p: Amuestra o quadro de dialogo Perfils de configuración.

<!-- KC:endInclude -->

O primer control d'iste dialogo ye a lista de perfils que se puet seleccionar un d'os perfils disponibles.
En que ubras o dialogo, se selecciona o perfil que sigas editando actualment.
Tamién s'amuestra información adicional ta perfils activos, indicando si s'activoron manualment, se disparoron y/u si son estando editaus.

Pa cambiar o nombre d'un perfil u eliminar-lo, preta os botons Renombrar u Eliminar, respectivament.

Preta lo botón Zarrar pa zarrar o dialogo.

#### Creyando un Perfil {#ProfilesCreating}

Pa creyar un perfil, preta lo botón Nuevo.

En o quadro de dialogo Nuevo perfil, puetz introducir un nombre pa o perfil.
Tamién puetz seleccionar cómo cal usar iste perfil.
Si nomás deseyas fer servir iste perfil manualment, selecciona enchegau manual, que ye a valor predeterminada.
En caso contrario, selecciona o disparador que habría d'activar automaticament iste perfil.
Pa mayor comodidat, si no s'ha introduciu garra nombre pa lo perfil, en seleccionar un disparador se replenará un nombre en conseqüencia.
Mira-te [mas abaixo](#ConfigProfileTriggers) pa mas información sobre os disparadors.

Pretando l'Acceptar se creyará o perfil y se zarrará o quadro de dialogo de configuración de perfils pa que puedas editar-lo.

#### Enchegau Manual {#ConfigProfileManual}

Puetz enchegar manualment un perfil seleccionando un perfil y pretando lo botón enchegau Manual.
Una vez enchegau, encara se pueden enchegar belatros perfils a causa d'os disparadors, pero as opcions d'o perfil enchegau manualment tienen prioridat.
Por eixemplo, si un perfil se dispara ta l'aplicación actual y l'anunciau de vinclos ye activau en ixe perfil, pero desactivau en o perfil activau manualment, os vinclos no s'anunciarán.
Manimenos, si has cambiau a voz en o perfil disparau, pero nunca no s'ha cambiau en o perfil activau manualment, se ferá servir a voz a partir d'o perfil disparau.
As valors que se modifiquen s'alzarán en o perfil activau manualment.
Ta desenchegar un perfil enchegau manualment, selecciona-lo en o quadro de dialogo Perfils de configuración y preta o botón desenchegau Manual.

#### Disparadors {#ConfigProfileTriggers}

A lo pretar o botón de Disparadors en o quadro de dialogo Perfils de configuración te permite cambiar os perfils que han d'estar activaus automaticament por diversos disparadors.

A lista de disparadors amuestra os disparadors disponibles, que son os siguients:

* Aplicación actual: Se dispara quan se cambee t'a l'aplicación actual.
* Charrar-lo tot: Se dispara entre a lectura con a orden charrar-lo Tot.

Ta cambiar o perfil que debe estar activau automaticament por un disparador, selecciona o disparador y dimpués selecciona o perfil deseyau en a lista de perfils.
Puetz seleccionar (configuración normal) si no quiers utilizar un perfil.

Preta lo botón de zarrar pa tornar t'o quadro de dialogo de perfils de configuración.

#### Editando un Perfil {#ConfigProfileEditing}

Si has activau manualment un perfil, as opcions que modifiques s'alzarán en ixe perfil.
En caso contrario, as opcions que se modifiquen s'alzarán en o perfil disparau mas recientment.
Por eixemplo, si has asociau un perfil con l'aplicación Bloc de notas y cambeas t'o Bloc de notas, as opcions modificadas s'alzarán en ixe perfil.
Por zaguer, si no bi ha garra perfil enchegau manualment ni un disparau, as opcions que se modifiquen s'alzarán en a configuración normal.

Pa editar o perfil asociau a charrar-lo tot, has d'[enchegar manualment](#ConfigProfileManual) ixe perfil.

#### Desenchegar Temporalment os Disparadors {#ConfigProfileDisablingTriggers}

A veces, ye util desactivar temporalment totz os disparadors.
Por eixemplo, podrías deseyar editar un perfil enchegau manualment u la configuración normal, sin perfils disparadors interferindo-bi.
Puetz fer ixo marcando a caixeta de verificación de desactivar temporalment totz os disparadors en o quadro de dialogo  d'os perfils de configuración.

Pa activar u desactivar los disparadors dende qualsiquier puesto, por favor asigna un cenyo personalizau utilizando lo [dialogo de cenyos de dentrada](#InputGestures).

#### Activar un perfil fendo servir cenyos de dentrada {#ConfigProfileGestures}

Pa cada perfil que anyadas, podrás asignar uno u mas cenyos de dentrada pa activar-lo.
Por defecto, los perfils de configuración no tienen cenyos de dentrada asignaus.
Puetz anyadir cenyos pa activar un perfil fendo servir lo [dialogo de cenyos de dentrada](#InputGestures).
Cada perfil tiene la suya propia dentrada en a categoría de perfils de configuración.
Quan renombres un perfil, qualsiquier cenyo que anyadises con anterioridad encara será disponible.
Borrar un perfil eliminará automaticament lo cenyo asociau con ell.

### Ubicación d'os Fichers de Configuración {#LocationOfConfigurationFiles}

Las versions portatils d'o NVDA almagazenan todas las suyas opcions y complementos en un directorio clamau userConfig, que se troba en o directorio d'o NVDA.

Las versions instaladas d'o NVDA almagazenan todas las suyas opcions y complementos en un directorio especial d'o NVDA localizau en o tuyo perfil d'usuario d'o Windows. 
Ixo significa que cada usuario en o sistema puet tener las suyas propias opcions d'o NVDA. 
Pa ubrir lo tuyo directorio d'opcions dende qualsiquier puesto puetz fer servir lo [dialogo de cenyos de dentrada](#InputGestures) pa anyadir un cenyo personalizau.
Amás pa una versión instalada d'o NVDA, en o menú d'inicio puetz ir ta  programas -> NVDA -> explorar lo directorio de configuración d'usuario.

Las opcions pa lo NVDA quan s'executa entre que s'inicia la sesión u en pantallas de control de cuentas d'usuario s'almagazenan en o directorio SystemConfig en o directorio d'instalación d'o NVDA.
Por un regular ixa configuración no habría de tocar-se.
Pa cambiar cómo se configura lo NVDA en ntre que s'inicia la sesión y en as pantallas de control de cuentas d'usuario, configura lo NVDA como deseyes mientras yes autentificau en o Windows, alza la configuración y dimpués preta lo botón d'"emplegar los achustes alzaus actualment en l'inicio de sesión y atras pantallas seguras en a categoría cheneral d'o dialogo d'[opcions d'o NVDA](#NVDASettings) .

## Ferramientas Extra {#ExtraTools}
### Visor d'o rechistro {#LogViewer}

Lo visor d'o rechistro, trobau en Ferramientas en o menú NVDA, te permiten veyer toda la salida que haiga ocurriu dica agora dende quan iniciés lo NVDA por zaguer vez.
Fendo servir NVDA+F1 s'ubrirá lo visor d'o rechistro y amostrará información de desemboliqe sobre lo navegador d'obchectos actual.

Antiparti de leyer lo conteniu, tamién puetz alzar una copia d'o fichero de rechistro, u refrescar lo visor pa que s'amuestre la salida mas recient dende que s'ubrió lo visor d'o rechistro.
Ixas accions son disponibles baixo lo menú d'o visor d'o rechistro.

### Visor d'a Voz {#SpeechViewer}

Pa desembolicadors vidents de Software u chent contrimostrando lo NVDA a una audiencia vident, ye disponible una finestra flotant que te permite veyer tot o texto que o NVDA siga charrando actualment.

Pa activar o visor d'a voz, marca l'elemento de menú "Visor d'a Voz" baixo Ferramientas en o menú NVDA.
Desmarca l'elemento de menú pa desactivar-lo.

La finestra d'o visor d'a voz contién una caixeta de verificación clamada "Amostrar o visor d'a voz en rancar".
Si ye enchegada, o visor d'a voz s'ubrirá en que o NVDA ranque.
La finestra d'o visor d'a voz mirará de reubrir-se siempre con as mesmas dimensions y ubicación que quan se zarró.

Mientras lo visor de voz ye activau, s'actualiza constantment t'amostrar-te o texto mas recient que ye estando charrau.
Manimenos, si fas clic u colocas o foco adintro d'o visor,  o NVDA aturará temporalment l'actualización d'o texto, tal que podrás seleccionar u copiar facilment o conteniu existent.

Pa trigar o visor d'a voz dende qualsiquier puesto asigna un cenyo personalizau fendo servir o [dialogo de cenyos de dentrada](#InputGestures).

### Visor d'o braille {#BrailleViewer}

Pa los desembolicadors vidents d'aplicacions u las personas que fagan demostracions d'o NVDA pa audiencias con visión, bi ha disponible una finestra flotant que les permite veyer la salida braille y lo texto equivalent pa cada caracter braille.
Lo visor d'o braille puet fer-se servir ded vez que una linia  braille fisica, lo qual coincidirá con o numero de celdas d'o dispositivo fisico.
Entre que lo visor d'o braille siga enchegau, s'actualiza constantment pa amostrar-te lo braille que s'amostraría en a linia braille fisica.

Pa enchegar lo visor d'o braille, marca l'elemento de menú "visor d'o braille" en ferramientas en o menú d'o NVDA.
Desmarca l'elemento de menú pa desenchegar-lo.

Las linias braille fisicas gosan tener botons pa desplazar-se enta debant u enta dezaga, pa enchegar lo desplazamiento con a ferramienta de visor d'o braille fe servir lo [dialogo de cenyos de dentrada](#InputGestures) pa asignar alcorces de teclau que "desplace la linia braille enta dezaga" y "desplace la linia braille enta debant"

La finestra d'o visor d'o braille contiene una caixeta de verificación clamada "amostrar lo Visor d'o braille en rancar".
Si ixa opción ye marcada, lo visor d'o braille s'ubrirá en que s'inicie lo NVDA.
La finestra d'o visor d'o braille siempre mirará de tornar a ubrir-se con as mesmas dimensions y ubicación que quan se zarró.

La finestra d'o visor d'o braille contiene una caixeta de verificación etiquetada como "Esvolastriar pa lo enrotamiento d'a celda", por defecto ye esmarcada.
Si se marca, pasar lo churi sobre una celda braille enchegará un comando "enrotar a celda braille" pa ixa celda.
A ormino s'emplega ixo pa mover lo cursor u enchegar l'acción d'un control.
Ixo puede estar util pa comprebar que lo NVDA siga capable de revertir correctament lo mapa d'una celda braille.
Pa privar lo enrotamiento involuntario t'as celdas, lo comando tiene un retardo.
Lo churi ha de desplazar-se dica que la celda se torne verda.
La celda prencipiará con una color amariella clara, pasará a estar narancha, y de momento se tornará verda.

### Consola Python {#PythonConsole}

La consola Python d'o NVDA, que se troba baixo las ferramientas en o menú d'o NVDA, ye una ferramienta de desembolique que ye util pa depurar, inspeccions chenerals d'a parti interna d'o NVDA u inspección d'a hierarquía d'accessibilidat de bella aplicación.
Pa mas información, por favor mira-te la [guida de desembolique d'o NVDA](https://www.nvaccess.org/files/nvda/documentation/developerGuide.html).

### Administrador de Complementos {#AddonsManager}

L'Administrador de Complementos, t'o que s'accede seleccionando l'administrador de complementos baixo as ferramientas en o menú d'o NVDA, te permite instalar, desinstalar, enchegar y desenchegar paquetz de complementos pa o NVDA.
Ixos paquetz son furnius por a comunidat y contienen codigo personalizau que podrá adhibir u cambiar caracteristicas en o NVDA u tamién proporcionan suporte pa linias Braille u sintetizadors de voz extra.

L'Administrador de Complementos contién una lista que amuestra totz os complementos instalaus actualment en a tuya configuración d'usuario d'o NVDA. 
S'amuestra o nombre d'o paquet, o estau, a versión y l'autor pa cada complemento, encara que se puet veyer mas información como una descripción y una URL seleccionando lo complemento y pretando lo botón arredol d'o complemento.
Si bi ha aduya disponible pa o complemento seleccionau puetz acceder ta ella pretando o botón d'aduya d'o complemento.

Pa examinar y descargar los complementos disponibles en linia preta o botón d'obtener complementos.
Ixe botón ubre la [pachina de complementos d'o NVDA](https://addons.nvda-project.org/).
Si lo NVDA ye instalau y correndo en o tuyo sistema puetz ubrir dreitament o complemento dende o navegador pa prencipiar o proceso d'instalación como se describe contino.
En caso contrario, alza o paquet de complemento y sigue as instruccions mas abaixo.

Pa instalar bell complemento que obteniés previament, preta o botón d'instalar.
Ixo te permitirá examinar un paquet de complemento  (fichero .nvda-addon) en o tuyo ordinador u en un ret.
Una vez que pretes ubrir, empecipiará o proceso d'instalación.

En que se va a instalar un complemento, o NVDA en primeras te pedirá que confirmes que realment deseyas instalar-lo.
A causa que a funcionalidat d'os complementos no tien restriccions adintro d'o NVDA, que en teoría podría incluir l'acceso t'os tuyos datos personals u mesmo ta tot o sistema si o NVDA ye una copia instalada, ye muit important que instales nomás complementos dende fuents fiables.
Una vez que lo complemento siga instalau, lo NVDA debe reenchegar-se pa que lo complemento prencipie la suya execución. 
Malas que lo fagas, un estau d'"instalar" s'amostrará pa ixe complemento en a lista.

Pa eliminar bell complemento, selecciona lo complemento dende la lista y preta lo botón d'eliminar.
Lo NVDA te preguntará si realment deseyas fer ixo.
Igual como con la instalación, lo NVDA debe reenchegar-se pa que lo complemento siga eliminau de raso.
Dica que lo fagas, un estau d'"eliminar" s'amostrará pa ixe complemento en a lista.

Pa desenchegar bell complemento preta lo botón de desenchegar.
Pa enchegar bell complemento previament desenchegau preta lo botón d'enchegar.
Puetz desenchegar bell complemento si lo estau d'o complemento endica que ye enchegau, u enchegar-lo si lo complemento ye desenchegau.
Pa cada pretada d'o botón d'enchegar u desenchegar cambia lo estau d'o complemento pa endicar qué pasará en que lo NVDA se reenchegue.
Si lo complemento estió desenchegau anteriorment, s'amostrará un estau "enchegau dimpués de reenchegar".
Si lo complemento estió anteriorment "enchegau", s'amostrará un estau "desenchegau dimpués de reenchegar".
Igual como quan instales u elimines complementos te caldrá reenchegar lo NVDA pa que los cambios fagan efecto.

L'administrador tamién tien un botón de zarrar pa zarrar o dialogo.
Si has instalau, eliminau u cambiau lo estau de bell complemento, lo NVDA en primeras te preguntará si deseyas reenchegar-lo pa que los cambeos puedan fer efecto.

Bells complementos antigos pueden ya no estar compatibles con a versión d'o NVDA que tiens.
Quan utilices una versión mas antiga d'o NVDA, bels complementos nuevos pueden no estar-bi compatibles.
Mirar d'instalar bell complemento incompatible resultará en una error explicando por qué lo complemento se considera incompatible.
Pa inspeccionar ixos complementos incompatibles puetz fer servir lo botón "veyer los complementos incompatibles" pa lanzar l'administrador de complementos incompatibles.

Pa acceder t'o Administrador de complementos dende qualsiquier puesto, por favor asigna un cenyo personalizau fendo servir o [dialogo de cenyos de dentrada](#InputGestures).

#### Administrador de complementos incompatibles {#incompatibleAddonsManager}

L'Administrador de Complementos Incompatibles, t'o qual se puet acceder a traviés d'o botón de "veyer los complementos incompatibles" en l'Administrador de Complementos, te permite inspeccionar qualsiquier complemento incompatible y la razón por la quala se consideran incompatibles.
Los complementos se consideran incompatibles quan no son estaus esviellaus pa funcionar con cambios significativos d'o NVDA, u quan se basan en una caracteristica no disponible en a versión d'o NVDA que yes emplegando.
L'Administrador de Complementos Incompatibles tien un mensache breu pa explicar lo suyo proposito asinas como la versión d'o NVDA.
Los complementos incompatibles se presientan en una lista con as siguients columnas:

1. paquet, lo nombre d'o complemento
1. versión, la versión d'o complemento
1. razón d'incompatibilidad, una explicación de por qué lo complemento se considera incompatible

L'Administrador de Complementos Incompatibles tamién tien un botón de "sobre lo complemento...".
Ixe dialogo te dará a conoixer totz los detalles d'o complemento, lo qual ye d'aduya quan contactes con l'autor d'o complemento.

### Creyar una copia portable {#CreatePortableCopy}

Isto ubrirá un dialogo que te permite creyar una copia portable d'o NVDA a partir d'a versión instalada.
De qualsiquier modo, en executar una copia portable d'o NVDA, en o submenú de ferramientas extra l'elemento de menú se clamará "instalar lo NVDA en iste ordinador" en cuenta de "creyar una copia portable).

Lo dialogo pa creyar una copia portable d'o NVDA u pa instalar lo NVDA en iste ordinador t'indicará pa trigar una rota d'a carpeta en que s'habría de creyar la copia portable u en que s'habría d'instalar lo NVDA.

En ixe dialogo puetz enchegar u desenchegar lo siguient:

* Copiar la configuración actual de l'usuario (ixo incluye los fichers en %appdata%\roaming\NVDA u en a configuración d'usuario d'a tuya copia portable y tamién incluye los complementos y atros modulos)
* Rancar la nueva copia portable dimpués d'a creyación u rancar lo NVDA dimpués d'a instalación (ranca lo NVDA automaticament dimpués d'a creyación d'a copia portable u d'a instalación)

### Executar la ferramienta COM registration fixing... {#RunCOMRegistrationFixingTool}

La instalación u desinstalación de programas en un ordinador puet, en bells casos, provocar que los fichers COM DLL no se rechistren.
Dau que las Interficies COM tals como IAccessible penden en os rechistros correctos de COM DLL, puet amaneixer problemas caso que falte lo rechistro correcto.

Ixo puet succeder, por eixemplo, dimpués d'instalar y desinstalar l'Adobe Reader, lo Math Player y atros programas.

Lo rechistro faltant puet causar problemas en os navegadors, aplicacions d'escritorio, barra de fayenas y atras interficies.

Especificament, los siguients problemas pueden resolver-sen executando ixa ferramienta:

* Lo NVDA anuncia "desconoixiu" en navegar con navegadors tals como lo Firefox, lo Thunderbird etc.
* Lo NVDA falla en cambiar entre lo modo de foco y lo modo de navegación
* Lo NVDA ye muito pando en navegar con os navegadors mientras s'utiliza lo modo de navegación
* Y posiblement atros fallos.

### Recargar os plugins {#ReloadPlugins}

Iste elemento, una vez activau, recarga os modulos d'aplicación y os plugins globals sin reenchegar o NVDA, o qual ye util ta desembolicadors.

## Sintetizadors de Voz Suportaus {#SupportedSpeechSynths}

Ista sección contién información sobre os sintetizadors de voz suportaus por o NVDA.
Pa una lista mas extensa d'os sintetizadors libres y comercials que puetz descargar y mercar pa emplegar con o NVDA, por favor mira-te la [pachina de voces extra](https://github.com/nvaccess/nvda/wiki/ExtraVoices).

### eSpeak NG {#eSpeakNG}

Lo sintetizador [eSpeak NG](https://github.com/espeak-ng/espeak-ng/) se construi dreitament en o NVDA y no requier garra atro controlador u components especials pa instalar-se.
En o Windows 7, 8 y 8.1, lo NVDA fa servir lo Espeak NG de traza predeterminada (lo [Windows OneCore](#OneCore) s'emplega en o Windows 10 y superiors por defecto).
Como ixe sintetizador ye integrau en o NVDA, ye una gran esleción ta quan s'executa lo NVDA en  una memoria USB u en un CD en atros sistemas.

Cada voz que vien con o eSpeak NG charra un idioma diferent.
Bi ha sobre 43 idiomas diferents suportaus por  o eSpeak NG.

Tamién bi ha muitas variants que pueden trigar-se ta alterar o son d'a voz.

### Microsoft Speech API versión 4 (SAPI 4) {#SAPI4}

SAPI 4 ye un antigo estandar de Microsoft pa software sintetizador de voz.
O NVDA encara suporta ixo pa usuarios que agún tiengan sintetizadors SAPI 4 instalaus.
Manimenos Microsoft ya no suporta ixo y cal components que ya no son disponibles dende Microsoft.

Quan emplegues iste sintetizador con o NVDA, las voces disponibles (que se i accedeix dende la  [categoría de voz](#SpeechSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings) u por l'[aniello d'opcions d'o sintetizador](#SynthSettingsRing)) contendrán totas las voces de totz los motors instalaus SAPI 4 trobaus en o tuyo sistema.

### Microsoft Speech API versión 5 (SAPI 5) {#SAPI5}

Lo SAPI 5 ye un estandar de Microsoft pa software de sintetizadors de voz.
Muitos sintetizadors de voz que cumplen con iste estandar podrán mercar-se u descargar-se de baldes dende quantas companyías y puestos Web, encara que prebablement o tuyo sistema ya vendrá con a lo menos una voz SAPI 5 preinstalada.
Quan s'utiliza iste sintetizador con o NVDA, las voces disponibles (que se i accedeix dende la [categoría de voz](#SpeechSettings) d'o dialogo d'[opcions d'o NVDA](#NVDASettings) u por l'[aniello d'opcions d'o Sintetizador](#SynthSettingsRing)) contendrán totas las voces de totz los motors SAPI 5 instalaus trobaus en o tuyo sistema.

### Microsoft Speech Platform {#MicrosoftSpeechPlatform}

La Microsoft Speech Platform proporciona voces ta muitos idiomas que s'utilizan habitualment en o desembolique d'aplicacions basadas en servidors de fabla. 
Istas voces tamién pueden emplegar-se con o NVDA.

Pa emplegar istas voces, te fará falta instalar dos components:

* Microsoft Speech Platform - Runtime (Versión 11) , x86: https://www.microsoft.com/download/en/details.aspx?id=27225
* Microsoft Speech Platform - Runtime Languages (Versión 11): https://www.microsoft.com/download/en/details.aspx?id=27224
 * Ista pachina inclui muitos fichers tanto de reconoixencia como de texto ta voz.
 Triga los fichers que contiengan los datos TTS pa los idiomas y voces deseyaus.
 Por eixemplo, lo fichero MSSpeech_TTS_en-US_ZiraPro.msi ye una voz anglesa U.S..

### Voces Windows OneCore {#OneCore}

Lo Windows 10 y superiors incluyen nuevas voces conoixidas como voces "OneCore" u "mobile".
Se furne voces pa muitos idiomas y son mas achils que no as voces Microsoft disponibles en fer servir o Microsoft Speech API versión 5.
En o Windows 10 y superiors, lo NVDA fa servir voces Windows OneCore por defecto (lo [eSpeak NG](#eSpeakNG) s'emplega en atras versions).

Pa anyadir nuevas voces de l'OneCore d'o Windows, ves t'as opcions de voz, adentro d'as opcions d'o sistema d'o Windows.
Fe servir la opción d'anyadir voces y mira la luenga desiada.
Muitas luengas incluyen qualques variants.
"Reino unido" y "Australia" son dos d'as variants anglesas.
"Francia", "Canadá" y "Suiza" son variants francesas disponibles.
Mira la luenga mas cheneral (tal como anglés u francés) y dimpués troba la variant en a lista.
Triga bellas luengas desiadas y fe servir lo botón d'anyadir pa anyadir-las.
Una vez anyadidas, reenchega lo NVDA.

Porfavor, mira-te iste articlo de Microsoft pa veyer una lista de voces disponibles: https://support.microsoft.com/en-us/windows/appendix-a-supported-languages-and-voices-4486e345-7730-53da-fcfe-55cc64300f01

## Linias Braille Suportadas {#SupportedBrailleDisplays}

Ista sección contién información sobre as linias braille suportadas por lo NVDA.

### Linias que suportan la detección automatica {#AutomaticDetection}

Lo NVDA tien la capacidat pa detectar muitas linias braille en segundo plano automaticament, u a traviés d'USB u de bluetooth.
Iste comportamiento s'aconsigue trigando la opción d'automatico como la linia braille preferida dende lo [dialogo d'opcions de braille](#BrailleSettings) d'o NVDA.
Ista opción ye trigada predeterminadament.

Las siguients linias suportan ista funcionalidat de detección automatica.

* Linias Handy Tech
* Linias Baum/Humanware/APH/Orbit braille
* Series d'as HumanWare Brailliant BI/B
* HumanWare BrailleNote
* SuperBraille
* Series d'as Optelec ALVA 6
* Series d'as HIMS Braille Sense/Braille EDGE/Smart Beetle/Sync Braille
* Linias Eurobraille Esys/Esytime/Iris
* Linias Nattiq nBraille
* Qualsiquier linia que suporte lo protocolo estandar HID braille

### Series d'a Freedom Scientific Focus/PAC Mate {#FreedomScientificFocus}

Todas las linias Focus y PAC Mate de [Freedom Scientific](https://www.freedomscientific.com/) se suportan quan se connectan a traviés de l'USB u d'o bluetooth.
Te fará falta los controladors de linias braille de Freedom Scientific instalaus en o tuyo sistema.
Si no los tiens encara, puetz obtener-los dende https://support.freedomscientific.com/Downloads/Focus/FocusBlueBrailleDisplayDriver.
Encara que ista pachina no mencione que a linia Focus 40 Blue, lo controlador suporta todas las linias Focus y Pacmate de Freedom Scientific.

Predeterminadament, lo NVDA puet detectar automaticament y connectar-se a istas linias tanto a traviés d'USB como de bluetooth.
Manimenos, quan se configura la linia, puetz seleccionar explicitament los puertos "USB" u "Bluetooth" pa restrinchir la mena de connexión a emplegar.
Isto podría estar util si quiers connectar la linia focus a lo NVDA emplegando bluetooth, y encara podrías cargar-la emplegando a enerchía de l'USB dende o tuyo ordinador.
La detección automatica de linias braille d'o NVDA tamién reconoixerá la linia por USB u por Bluetooth.

Contino va las asociacions de teclas pa ista linia con o NVDA.
Por favor mira-te la documentación d'a linia pa descriptcions de do puet trobar-se istas teclas.
<!-- KC:beginInclude -->

| Nombre |tecla|
|---|---|
|Desplazar a linia braille enta zaga |sensorSuperior1 (primera celda en a linia)|
|Desplazar a linia braille enta abant |sensorSuperior20/40/80 (zaguera celda en a linia)|
|Desplazar a linia braille enta zaga |barraDeAvance cucha|
|Desplazar a linia braille enta avant |barraDeAvance dreita|
|Commutar o seguimiento de braille |leftGDFButton+rightGDFButton|
|Commutar l'acción d'a rueda cucha |pretar a rueda cucha|
|Mover-se-ne enta zaga emplegando l'acción d'a rueda cucha |rueda cucha enta alto|
|Mover-se-ne enta debant emplegando l'acción d'a rueda cucha |rueda cucha enta baixo|
|Commutar l'acción d'a rueda dreita |pretar rueda dreita|
|Mover-se-ne enta zaga emplegando l'acción d'a rueda dreita |rueda dreita enta alto|
|Mover-se-ne enta debant  emplegando l'acción d'a rueda dreita |rueda dreita enta baixo|
|Guidar ent'a celda braille |sensor|
|tecla mayus+tabulador |barra espaciadera braille+punto1+punto2|
|tecla tabulador |barra espaciadera braille+punto4+punto5|
|tecla flecha abaixo |barra espaciadera braille+punto1|
|tecla flecha alto |barra espaciadera braille+punto4|
|tecla control+flecha cucha |barra espaciadera braille+punto2|
|tecla control+flecha dreita |barra espaciadera braille+punto5|
|tecla flecha cucha |barra espaciadera braille+punto3|
|tecla flecha dreita |barra espaciadera braille+punto6|
|tecla encieto |barra espaciadera braille+punto1+punto3|
|tecla fin |Barra espaciadera braille+punto4+punto6|
|tecla control+encieto |barra espaciadera braille+punto1+punto2+punto3|
|tecla control+fin |barra espaciadera braille+punto4+punto5+punto6|
|tecla alt |barra espaciadera braille+punto1+punto3+punto4|
|tecla alt+tabulador |barra espaciadera braille+punto2+punto3+punto4+punto5|
|tecla alt+mayus+tabulador |barra espaciadera braille+punto1+punto2+punto5+punto6|
|tecla windows+tabulador |barra espaciadera braille+punto2+punto3+punto4|
|tecla escape |barra espaciadera braille+punto1+punto5|
|tecla windows |barra espaciadera braille+punto2+punto4+punto5+punto6|
|tecla espacio |barra espaciadera braille|
|tecla windows+d (minimizar todas as aplicacions) |barra espaciadera braille+punto1+punto2+punto3+punto4+punto5+punto6|
|Anunciar la Linia Actual |barra espaciadera braille+punto1+punto4|
|Menú NVDA |barra espaciadera braille+punto1+punto3+punto4+punto5|

Pa los modelos mas recients d'a Focus que contienen teclas de garnelas (focus 40, focus 80 y focus blue):

| Nombre |Tecla|
|---|---|
|Mover a linia braille t'a linia anterior |garnela cucha alto, garnela dreita alto|
|Mover a linia braille t'a linia siguient |garnela cucha abaixo, garnela dreita abaixo|

Nomás pa la Focus 80:

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta zaga |barra frontal cucha alto, barra frontal dreita alto|
|Desplazar a linia braille enta avant |barra frontal cucha abaixo, barra frontal dreita abaixo|

<!-- KC:endInclude -->

### Series d'Optelec ALVA 6 / conversor de protocolo {#OptelecALVA}

Todas dos linias ALVA BC640 y BC680 d'[Optelec](https://www.optelec.com/) son suportadas quan se connectan por l-SB u por lo bluetooth.
Alternativament puetz connectar una linia antiga d'Optelec, tal como una Braille Voyager, fendo servir un conversor de protocolo furniu por Optelec.
No te cal instalar garra controlador en especial pa emplegar istas linias.
Nomás enchega la linia y configura lo NVDA pa emplegar-la.

Nota: Lo NVDA podría no estar capaz d'usar una linia ALVA BC6 con Bluetooth quan s'emparella fendo servir la utilidat ALVA Bluetooth.
Quan haigas emparellau lo tuyo dispositivo fendo servir a suya utilidat y o NVDA no pueda detectar-lo, te recomendamos d'enparellar a tuya linia ALVA d'a forma ordinaria fendo servir as opcions de Bluetooth d'o Windows.

Nota: dau que belunas d'istas linias tienen un teclau braille, maneyan a transcripción de braille ta texto por ellas mesmas por defecto.
Ixo significa que o sistema de dentrada braille d'o NVDA no se ye emplegando en a situgación predeterminada (ye decir, a tabla de dentrada braille configurada no tien efecto).
Pa linias ALVA con firmware recient, ye posible desenchegar ixa simulación de teclau HID fendo servir un cenyo de dentrada.

Contino va las asignacions de teclas pa ista linia con o NVDA.
Por favor mira-te la documentación d'a linia pa descripcions de dó pueden trobar-sen istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar la linia braille enta zaga |t1, etouch1|
|Mover la linia braille t'a linia anterior |t2|
|Mover-se-ne t'o foco actual |t3|
|Mover la linia braille t'a linia siguient |t4|
|Desplazar la linia braille enta debant |t5, etouch3|
|Guidar t'a celda braille |sensor|
|Anunciar o formato de texto baixo a celda braille |sensors secundarios|
|Conmutar a simulación de teclau HID |t1+spEnter|
|Mover-se-ne t'a linia d'alto en a revisión |t1+t2|
|Mover-se-ne t'a linia d'abaixo en a revisión |t4+t5|
|Alternar o braille ancorau ta |t1+t3|
|Anunciar lo titol |etouch2|
|Anunciar la barra d'estau |etouch4|
|tecla mayus+tab |sp1|
|tecla alt |sp2, alt|
|tecla escape |sp3|
|tecla tabulador |sp4|
|tecla flecha alto |spUp|
|tecla flecha abaixo |spDown|
|tecla flecha cucha |spLeft|
|tecla flecha dreita |spRight|
|tecla intro |spEnter, enter|
|Anunciar la calendata u la hora |sp2+sp3|
|menú NVDA |sp1+sp3|
|tecla windows+d (minimizar todas as aplicacions) |sp1+sp4|
|Tecla windows+b (servilla de sistema d'o foco) |sp3+sp4|
|tecla windows |sp1+sp2, windows|
|tecla alt+tabuladorb |sp2+sp4|
|control+tecla d'inicio |t3+spUp|
|control+tecla de fin |t3+spDown|
|tecla d'inicio |t3+spLeft|
|tecla de fin |t3+spRight|
|tecla control |control|

<!-- KC:endInclude -->

### Linias Handy Tech {#HandyTech}

Lo NVDA suporta la gran parti d'as linias de [Handy Tech](https://www.handytech.de/) quan son connectadas a traviés d'USB, puerto serie u bluetooth.
Pa qualques linias antigas USB, te fará falta instalar los controladors USB d'Handy Tech en o tuyo sistema.

Las siguients linias no se suportan en quitar-las d'a caixa pero se pueden fer servir a traviés d'o [controlador universal de Handy Tech](https://handytech.de/en/service/downloads-and-manuals/handy-tech-software/braille-display-drivers) y o complemento d'o NVDA:

* Braillino
* Bookworm
* Linias modulars con a versión d'o firmware 1.13 u inferior. Por favor para cuenta que o firmware d'ixas linias se puet esviellar.

Contino van as asignacions de teclas pa las linias Handy Tech con o NVDA.
Por favor mira-te a documentación d'a linia pa descripcions de do pueden trobar-sen istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta zaga |cucha, alto, b3|
|Desplazar a linia braille enta debant |Dreita, abaixo, b6|
|Mover a linia braille t'a linia anterior |b4|
|Mover a linia braille t'a linia siguient |b5|
|Guidar t'a celda braille |sensor|
|tecla mayus+tabulador |esc, triple acción  d'a tecla cucha alto+abaixo|
|tecla alt |b2+b4+b5|
|tecla escape |b4+b6|
|tecla tabulador |enter, triple acción  d'a tecla dreita alto+abaixo|
|tecla intro |esc+enter, triple acción  d'a tecla dreita alto+abaixo, accionar o ceprén|
|tecla flecha alto |ceprén t'alto|
|tecla flecha abaixo |ceprén t'abaixo|
|tecla flecha cucha |ceprén t'a cucha|
|tecla flecha dreita| ceprén t'a dreita|
|menú d'o NVDA |b2+b4+b5+b6|
|Conmutar o seguimiento d'o braille |b2|
|Conmutar o cursor braille |b1|
|Conmutar a presentación d'o contexto d'o foco |b7|
|Conmutar a dentrada braille |espacio+b1+b3+b4 (espacio+B mayuscla)|

<!-- KC:endInclude -->

### MDV Lilli {#MDVLilli}

La linia braille Lilli disponible dende [MDV](https://www.mdvbologna.it/) ye suportada.
No te cal instalar garra controlador especifico pa emplegar ista linia.
Solament enchega a linia y configura lo NVDA ta emplegar-la.

Ista linia encara no suporta la funcionalidat de detección automatica en segundo plan d'o NVDA.

Contino va las asignacions de teclas pa ista linia con o NVDA.
Porfavor mira-te la documentación d'a linia pa descripcions de do se puede trobar istas teclas.
<!-- KC:beginInclude -->

| Nombre |tecla|
|---|---|
|Desplazar enta zaga la linia braille |LF|
|Desplazar enta debant a linia braille |RG|
|Mover a linia braille t'a linia anterior |UP|
|Mover a linia braille t'a linia siguient |DN|
|Enrotar ent'a celda braille |route|
|Tecla mayus+tabulador |SLF|
|Tecla tabulador |SRG|
|Tecla alt+tabulador |SDN|
|Tecla alt+mayus+tabulador |SUP|

<!-- KC:endInclude -->

### Linias braille Baum/Humanware/APH/Orbit {#Baum}

Quantas linias braille de [Baum](https://www.visiobraille.de/index.php?article_id=1&clang=2), [HumanWare](https://www.humanware.com/), [APH](https://www.aph.org/) y [Orbit](https://www.orbitresearch.com/). As linias son suportadas quan se connectan a traviés de l'USB, d'o bluetooth u d'o puerto serie.
Istas incluyen:

* Baum: SuperVario, PocketVario, VarioUltra, Pronto!, SuperVario2, Vario 340
* HumanWare: Brailliant, BrailleConnect, Brailliant2
* APH: Refreshabraille
* Orbit: Orbit Reader 20

Belatras linias fabricadas por Baum tamién podrían funcionar, encara que no son estadas prebadas.

Si se connecta a traviés d'USB as linias que no fan servir l'HID, en primeras has d'instalar los controladors USB proporcionaus por o fabricant.
La VarioUltra y la Pronto! fan servir l'HID.
La Refreshabraille y a Orbit Reader 20 pueden fer servir l'HID si son configuradas apropiadament.

Lo modo de serie USB d'a Orbit Reader 20 actualment no ye suportau que en o Windows 10 y superiors.
Por un regular s'habría de fer servir l'USB HID en cuenta.

Contino va las asignacions de teclas pa istas linias con o NVDA.
Por favor mira-te la tuya documentación d'a linia braille pa descripcions de do se puet trobar istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta zaga |d2|
|Desplazar a linia braille enta debant |d5|
|Mover a linia braille t'a linia anterior |d1|
|Mover a linia braille t'a linia siguient |d3|
|Guidar t'a celda braille |sensor|

Pa linias que tiengan un joystick:

| Nombre |Tecla|
|---|---|
|Tecla flecha alto |alto|
|Tecla flecha abaixo |abaixo|
|Tecla flecha cucha |cucha|
|Tecla flecha dreita |dreita|
|Tecla intro |seleccionar|

<!-- KC:endInclude -->

### hedo ProfiLine USB {#HedoProfiLine}

La hedo ProfiLine USB d'[hedo Reha-Technik](https://www.hedo.de/) ye suportada.
En primeras has d'instalar los controladors USB furnius por lo fabricant.

Ista linia encara no suporta la funcionalidat de detección automatica en segundo plan d'o NVDA.

Contino va las asignacions de teclas pa ista linia con o NVDA.
Por favor mira-te la documentación d'a linia pa descripcions de do se puede trobar istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta dezaga |K1|
|Desplazar a linia braille enta debant |K3|
|Mover a linia braille t'a linia anterior |B2|
|Mover a linia braille t'a siguient linia |B5|
|Enrotar t'a celda braille |sensors|
|Commutar o seguimiento braille |K2|
|Leyer-lo tot |B6|

<!-- KC:endInclude -->

### hedo MobilLine USB {#HedoMobilLine}

Se suporta la hedo MobilLine USB d'[hedo Reha-Technik](https://www.hedo.de/).
En primeras has d'instalar los controladors USB furnius por lo fabricant.

Ista linia encara no suporta la funcionalidat de detección automatica en segundo plan d'o NVDA.

Contino va las asignacions de teclas pa ista linia con o NVDA.
Por favor mira-te la documentación d'a linia pa descripcions de do puede trobar-sen istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta dezaga |K1|
|Desplazar a linia braille enta abant |K3|
|Mover a linia braille t'a linia anterior |B2|
|Mover a linia braille t'a siguient linia |B5|
|Ir t'a celda braille |sensors|
|Commutar lo seguimiento de braille |K2|
|Leyer-lo tot |B6|

<!-- KC:endInclude -->

### Series d'a HumanWare Brailliant BI/B / BrailleNote Touch {#HumanWareBrailliant}

Las linias braille Brailliant series BI y B de [HumanWare](https://www.humanware.com/), incluindo BI 14, BI 32, BI 20X, BI 40, BI 40X y B 80, se suportan en que se connectan a traviés de l'USB u lo bluetooth.
Si la connectas a traviés d'USB con o protocolo establiu a HumanWare en primeras has d'instalar os controladors USB furnius por o fabricant.
Los controladors USB no se requieren si lo protocolo ye establiu a OpenBraille.

Los siguients dispositivos extra tamién se suportan (y no requieren garra controlador especial pa instalar-sen):

* APH Mantis Q40
* APH Chameleon 20
* Humanware BrailleOne
* NLS eReader

Contino va las asignacions de teclas pa las linias Brailliant BI/B y BrailleNote touch con o NVDA.
Por favor mira-te la documentación d'a linia pa descripcions de do puede trobar-sen istas teclas.

#### Asignacions de teclas pa totz los modelos {#toc263}

<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta zaga |cucha|
|Desplazar a linia braille enta debant |dreita|
|Mover a linia braille t'a linia anterior |alto|
|Mover a linia braille t'a linia siguient |abaixo|
|Guidar dica la celda braille |sensors|
|Activar y desactivar o seguimiento de braille |alto+abaixo|
|tecla flecha alto |espacio+punto1|
|tecla flecha abaixo |espacio+punto4|
|tecla flecha cucha |espacio+punto3|
|tecla flecha dreita |espacio+punto6|
|tecla mayus+tabulador |espacio+punto1+punto3|
|tecla tabulador |espacio+punto4+punto6|
|tecla alt |espacio+punto1+punto3+punto4 (espacio+m)|
|tecla escape |espacio+punto1+punto5 (espacio+y)|
|tecla intro |punto8|
|tecla windows |espacio+punto3+punto4|
|tecla alt+tabulador |espacio+punto2+punto3+punto4+punto5 (espacio+t)|
|Menú NVDA |espacio+punto1+punto3+punto4+punto5 (espacio+n)|
|tecla windows+d (minimizar todas as aplicacions) |espacio+punto1+punto4+punto5 (espacio+d)|
|Leyer-lo tot |espacio+punto1+punto2+punto3+punto4+punto5+punto6|

<!-- KC:endInclude -->

#### Asignacions de teclas pa Brailliant BI 32, BI 40 y B 80 {#toc264}

<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Menú NVDA |c1+c3+c4+c5 (comando n)|
|tecla windows+d (minimizar todas as aplicacions) |c1+c4+c5 (comando d)|
|Leyer-lo tot |c1+c2+c3+c4+c5+c6|

<!-- KC:endInclude -->

#### Asignacions de teclas pa Brailliant BI 14 {#toc265}

<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|tecla flecha alto |joystick alto|
|tecla flecha abaixo |joystick abaixo|
|tecla flecha cucha |joystick cucha|
|tecla flecha dreita |joystick dreita|
|tecla intro |Pretar joystick|

<!-- KC:endInclude -->

### Series d'a HIMS Braille Sense/Braille EDGE/Smart Beetle/Sync Braille {#Hims}

Lo NVDA suporta las linias Braille Sense, Braille EDGE, Smart Beetle y Sync Braille de [Hims](https://www.hims-inc.com/) quan se connectan a traviés d'USB u bluetooth. 
Si se connectan a traviés d'USB te fará falta instalar los controladors USB d'HIMS en o sistema.
Puetz descargar-los dende aquí: http://www.himsintl.com/upload/HIMS_USB_Driver_v25.zip

Contino va las asignacions de teclas pa istas linias con o NVDA.	
Por favor mira-te la documentación d'as linias pa descripcions d'án pueden trobar-sen istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Ir t'a celda braille |sensors|
|Desplazar enta dezaga la linia braille |leftSideScrollUp, rightSideScrollUp, leftSideScroll|
|Desplazar entabant a linia braille |leftSideScrollDown, rightSideScrollDown, rightSideScroll|
|Mover a linia braille t'a linia anterior |leftSideScrollUp+rightSideScrollUp|
|Mover a linia braille t'a linia siguient |leftSideScrollDown+rightSideScrollDown|
|Mover-se-ne t'a linea anterior en revisión |rightSideUpArrow|
|Mover-se-ne t'a linia siguient en revisión |rightSideDownArrow|
|Mover-se-ne t'o caracter  anterior en revisión |rightSideLeftArrow|
|Mover-se-ne t'o caracter siguient en revisión |rightSideRightArrow|
|Mover-se-ne t'o foco actual |leftSideScrollUp+leftSideScrollDown, rightSideScrollUp+rightSideScrollDown, leftSideScroll+rightSideScroll|
|Tecla control |smartbeetle:f1, brailleedge:f3|
|Tecla windows |f7, smartbeetle:f2|
|tecla alt |punto1+punto3+punto4+espacio, f2, smartbeetle:f3, brailleedge:f4|
|tecla mayus |f5|
|tecla insert |punto2+punto4+espacio, f6|
|tecla d'aplicacions |punto1+punto2+punto3+punto4+espacio, f8|
|tecla bloqueyo de mayusclas |punto1+punto3+punto6+espacio|
|tecla tabuladera |punto4+punto5+espacio, f3, brailleedge:f2|
|teclas mayus+alt+tabuladera |f2+f3+f1|
|teclas alt+tabuladera |f2+f3|
|teclas mayus+tabuladera |punto1+punto2+espacio|
|tecla fin |punto4+punto6+espacio|
|teclas control+fin |punto4+punto5+punto6+espacio|
|tecla inicio |punto1+punto3+espacio, smartbeetle:f4|
|teclas control+inicio |punto1+punto2+punto3+espacio|
|teclas alt+f4 |punto1+punto3+punto5+punto6+espacio|
|tecla flecha cucha |punto3+espacio, leftSideLeftArrow|
|teclas control+mayus+flecha cucha |punto2+punto8+espacio+f1|
|teclas control+flecha cucha |punto2+espacio|
|teclas mayus+flecha cucha |punto2+punto7+f1|
|teclas alt+flecha cucha |punto2+punto7|
|tecla flecha dreita |punto6+espacio, leftSideRightArrow|
|teclas control+mayus+flecha dreita |punto5+punto8+espacio+f1|
|teclas control+flecha dreita |punto5+espacio|
|teclas mayus+alt+flecha dreita |punto5+punto7+f1|
|teclas alt+flecha dreita |punto5+punto7|
|tecla rePach |punto1+punto2+punto6+espacio|
|teclas control+rePach |punto1+punto2+punto6+punto8+espacio|
|tecla flecha alto |punto1+espacio, leftSideUpArrow|
|teclas control+mayus+flecha alto |punto2+punto3+punto8+espacio+f1|
|teclas control+flecha alto |punto2+punto3+espacio|
|teclas mayus+alt+flecha alto |punto2+punto3+punto7+f1|
|teclas alt+flecha alto |punto2+punto3+punto7|
|teclas mayus+flecha alto |leftSideScrollDown+espacio|
|tecla avPach |punto3+punto4+punto5+espacio|
|teclas control+avPach |punto3+punto4+punto5+punto8+espacio|
|tecla flecha abaixo |punto4+espacio, leftSideDownArrow|
|teclas control+mayus+flecha abaixo |punto5+punto6+punto8+espacio+f1|
|teclas control+flecha abaixo |punto5+punto6+espacio|
|teclas mayus+alt+flecha abaixo |punto5+punto6+punto7+f1|
|teclas alt+flecha abaixo |punto5+punto6+punto7|
|teclas mayus+flecha abaixo |espacio+rightSideScrollDown|
|tecla escape |punto1+punto5+espacio, f4, brailleedge:f1|
|tecla suprimir |punto1+punto3+punto5+espacio, punto1+punto4+punto5+espacio|
|tecla f1 |punto1+punto2+punto5+espacio|
|tecla f3 |punto1+punto4+punto8+espacio|
|tecla f4 |punto7+f3|
|teclas windows+b |punto1+punto2+f1|
|teclas windows+d |punto1+punto4+punto5+f1|
|teclas control+insert |smartbeetle:f1+rightSideScroll|
|teclas alt+insert |smartbeetle:f3+rightSideScroll|

<!-- KC:endInclude -->

### Linias Braille Seika {#Seika}

Se suporta las linias braille Seika Versions 3, 4 y 5 (40 celdas) y Seika80 (80 celdas) de [Nippon Telesoft](https://www.nippontelesoft.com/).
Puetz trobar mas información sobre las linias y los controladors requiestos en https://en.seika-braille.com/down/index.html
En primeras has d'instalar los controladors USB furnius por lo fabricant.

Istas linias encara no suportan la funcionalidat de detección automatica en segundo plan d'o NVDA.

Contino va las asignacions de teclas pa istas linias con o NVDA.
Por favor mira-te la documentación d'a linia pa descripcions de do se troba istas teclas.
<!-- KC:beginInclude -->

| Nombre |tecla|
|---|---|
|Desplazar a linia braille enta dezaga |cucha|
|Desplazar a linia braille enta abant |dreita|
|Mover a linia braille t'a linia anterior |b3|
|Mover a linia braille t'a siguient linia |b4|
|Commutar o seguimiento d'o braille |b5|
|Leyer-lo tot |b6|
|tabulador |b1|
|mayus+tabulador |b2|
|alt+tabulador |b1+b2|
|Menú NVDA |cucha+dreita|
|Ir t'a celda braille |sensors|

<!-- KC:endInclude -->

### Modelos mas recients de Papenmeier BRAILLEX {#Papenmeier}

Se suporta las siguients linias Braille: 

* BRAILLEX EL 40c, EL 80c, EL 20c, EL 60c (USB)
* BRAILLEX EL 40s, EL 80s, EL 2d80s, EL 70s, EL 66s (USB)
* BRAILLEX Trio (USB y bluetooth)
* BRAILLEX Live 20, BRAILLEX Live y BRAILLEX Live Plus (USB y bluetooth)

Istas linias encara no suportan la funcionalidat de detección automatica en segundo plan d'o NVDA.

Si ye instalau lo BrxCom, lo NVDA emplegará lo BrxCom.
Lo BrxCom ye una ferramienta que permit a la dentrada de teclau dende la linia braille  marchar independientment d'un lector de pantalla.
La dentrada de teclau ye posible con os modelos Trio y BRAILLEX Live 20.

La mas gran parti d'os dispositivos tienen una Barra d'Acceso Facil (EAB) que permite operar rapida y intuitivament.
La EAB puet mover-se-ne en quatro adrezas do en cheneral cada adreza tien dos posicions.
Las series c y Live son as solas excepcións a iste regle.

La serie c y belatras linias tienen dos ringleras de sensors asinas que la ringlera superior s'utiliza pa anunciar información de formato.
Mantenendo pretada una d'as teclas superiors y pretando la EAB en os dispositivos d'a serie c s'emula la segunda posición.
Las linias d'a serie live no tienen que una flecha d'enrotamiento y la  EAB tien un trango por adreza.
Lo segundo trango puet estar emulau pretando una d'as teclas d'enrotamiento y pretando la EAB en a correspondient adreza.
Pretando y mantenendo las teclas alto, abaixo, dreita y cucha (u la EAB) se causa que l'acción correspondient se repita. 

Por un regular, las siguients teclas son disponibles en istas linias braille:

| Nombre |Tecla|
|---|---|
|l1 |Tecla cucha frontal|
|l2 |Tecla cucha trasera|
|r1 |Tecla dreita frontal|
|r2 |Tecla dreita trasera|
|alto |1 trango alto|
|alto2 |2 trangos alto|
|cucha |1 trango enta la cucha|
|cucha2 |2 trangos enta la cucha|
|dreita |1 trango enta la dreita|
|dreita2 |2 trangos enta la dreita|
|dn |1 trango abaixo|
|dn2 |2 trangos abaixo|

Contino va las asignacions d'ordens d'a Papenmeier pa lo NVDA:
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta dezaga |cucha|
|Desplazar a linia braille enta abant |dreita|
|Mover a linia braille t'a linia anterior |alto|
|Mover a linia braille t'a linia siguient |dn|
|Ir t'a celda braille |sensors|
|Anunciar o caracter actual en revisión |l1|
|Activar l'actual navegador d'obchectos |l2|
|Conmutar o braille ligau a |r2|
|Anunciar o titol |l1+alto|
|Anunciar a barra d'estau |l2+abaixo|
|Mover-se-ne ta l'obchecto conteniu |alto2|
|Mover-se-ne t'o primer obchecto conteniu |dn2|
|Mover-se-ne ta l'obchecto anterior |cucha2|
|Mover-se-ne t'o siguient obchecto |dreita2|
|Anunciar o formato de texto baixo a celda braille| ringlera de sensors superior|

<!-- KC:endInclude -->

O modelo Trio tien quatro teclas adicionals que se troban debant d'o teclau braille.
Istas son (ordenadas de cucha a dreita):

* Tecla de pulgar cucho (lt)
* Espacio
* Espacio
* Tecla de  pulgar dreito (rt)

Actualment, a tecla de pulgar dreito no ye en uso.
As teclas internas s'asignan ambas a lo espacio.

|| Nombre |Clau|

<!-- KC:beginInclude -->

|Tecla d'escape |espacio con o punto 7|
|Fflecha alto |espacio con o punto 2|
|Fflecha cucha |espacio con o punto 1|
|Flecha dreita |espacio con o punto 4|
|Flecha abaixo |espacio con o punto 5|
|Tecla control |lt + punto 2|
|Tecla Alt |lt + punto 3|
|Control + tecla d'escape |espacio con os puntos 1 2 3 4 5 y 6|
|Tabulador |espacio con os puntos 3 y 7|

### Modelos Antigos de Papenmeier Braille BRAILLEX {#PapenmeierOld}

Se suporta las siguients linias Braille: 

* BRAILLEX O 80, O 2D-80, O 40 P
* BRAILLEX Tiny, 2D Screen

Para cuenta que istas linias solament se pueden connectar a traviés d'un puerto serie.
A causa d'ixo, istas linias no suportan la funcionalidat de detección automatica en segundo plan d'o NVDA.
Habrías de  trigar lo puerto que bi ye connectada la pantalla dimpués d'haber trigau ixe controlador en o dialogo de [seleccionar linia braille](#SelectBrailleDisplay).

Beluns d'istos dispositivos tienen una barra d'acceso rapedo (EAB) que permite un accionamiento rapedo y intuitivo.
L'EAB se puet mover en quatro adrezas an, cheneralment, cada adreza tien dos movimientos.
Pretando y mantenendo las teclas Alto, abaixo, dreita y cucha (u EAB) se fa que l'acción correspondient siga repetida.
Los dispositivos mas antigos no tienen una EAB; s'utiliza en cuenta teclas frontals .

Por un regular, las siguients teclas son disponibles en las linias braille:

| Nombre |Tecla|
|---|---|
|l1 |Tecla frontal cucha|
|l2 |Tecla trasera cucha|
|r1 |Tecla frontal dreita|
|r2 |Tecla trasera dreita||
|up |1 paso alto||
|up2 |2 pasos alto|
|Left |1 paso a la cucha|
|Left2 |2 pasos a la cucha|
|right |1 paso a la dreita|
|right2 |2 pasos a la dreita|
|dn |1 paso abaixo|
|dn2 |2 pasos abaixo|

Contino va las asignacions d'ordens d'as Papenmeier pa lo NVDA:

<!-- KC:beginInclude -->
Dispositivos con EAB:

| Nombre |Tecla|
|---|---|
|Desplazar a linia braille enta dezaga |cucha|
|Desplazar a linia braille enta abant |dreita|
|Mover a linia braille t'a linia anterior |alto|
|Mover a linia braille t'a linia siguient |abaixo|
|Ir t'a celda braille |sensors|
|Anunciar o caracter actual en revisión |l1|
|Activar o navegador d'obchectos actual |l2|
|Anunciar o titol |l1up|
|Anunciar a Barra d'Estau| l2down|
|Mover-se-ne ta l'obchecto contenedor |up2|
|Mover-se-ne t'o primer obchecto conteniu |dn2|
|Mover-se-ne t'o siguient obchecto |left2|
|Mover-se-ne ta l'obchecto anterior |right2|
|Anunciar o formato de texto baixo a celda braille |Upper routing strip|

BRAILLEX Tiny:

| Nombre |Tecla|
|---|---|
|Anunciar o caracter actual en revisión |l1|
|Activar o navegador d'obchectos actual |l2|
|Desplazar a linia braille enta dezaga |left|
|Desplazar a linia braille enta abant |right|
|Mover a linia braille t'a linia anterior |up|
|Mover a linia braille t'a linia siguient |dn|
|Activar y desactivar o seguimiento de braille |r2|
|Mover-se-ne ta l'obchecto contenedor |r1+up|
|Mover-se-ne t'o primer obchecto conteniu |r1+dn|
|Mover-se-ne ta l'obchecto anterior |r1+left|
|Mover-se-ne t'o siguient obchecto |r1+right|
|Anunciar o formato de texto baixo a celda braille |sensors superiors|
|Anunciar o titol |l1+alto|
|Anunciar a barra d'estau |l2+abaixo|

BRAILLEX 2D Screen:

| Nombre |Tecla|
|---|---|
|Anunciar o caracter actual en revisión |l1|
|Activar o navegador d'obchectos actual |l2|
|Activar u desactivar o seguimiento de braille |r2|
|Anunciar o formato de texto baixo a celda braille |sensors superiors|
|Mover a linia braille t'a linia anterior| up|
|Desplazar a linia braille enta dezaga |left|
|Desplazar a linia braille enta abant |right|
|Mover a linia braille t'a linia siguient |dn|
|Mover-se-ne ta l'obchecto siguient |left2|
|Mover-se-ne ta l'obchecto contenedor |up2|
|Mover-se-ne t'o primer obchecto conteniu |dn2|
|Mover-se-ne ta l'obchecto anterior |right2|

<!-- KC:endInclude -->

### HumanWare BrailleNote {#HumanWareBrailleNote}

Lo NVDA suporta los anotadors electronicos BrailleNote d'[Humanware](https://www.humanware.com) quan actuguen como un terminal braille pa un lector de pantalla.
Se'n suporta los siguients modelos:

* BrailleNote Classic (solament connexión serie)
* BrailleNote PK (Connexions serie y bluetooth)
* BrailleNote MPower (Connexions serie y bluetooth)
* BrailleNote Apex (Connexions USB y Bluetooth)

Pa lo BrailleNote Touch, por favor mira-te la sección de [series d'as Brailliant BI / BrailleNote Touch {#HumanWareBrailliant].

Difuera de pa lo BrailleNote PK, s'admiten totz dos teclaus braille (BT) y QWERTY (QT).
Pa lo BrailleNote QT, no s'admite la emulación d'o teclau de PC.
Tamién puetz ficar-bi puntos braille utilizando lo teclau QT.
Por favor mira-te la sección de terminal braille d'a guida manual d'o BrailleNote pa detalles.

Si lo tuyo dispositivo suporta mas d'una mena de connexión, en que connectes lo tuyo BrailleNote t'o NVDA, has de configurar o puerto d'a terminal braille en as opcions de terminal braille.
Por favor mira-te lo manual d'o BrailleNote pa detalles.
En o NVDA, tamién te podría fer falta configurar lo puerto en o dialogo de [selección de linia braille](#SelectBrailleDisplay).
Si te yes connectando a traviés d'USB u bluetooth, puetz configurar o puerto en "automatico", "USB" u "Bluetooth", pendendo d'as opcions disponibles.
Si te yes connectando emplegando un puerto serie (u un convertidor d'USB a serie) u si no amaneix garra d'as opcions anteriors, has de trigar explicitament o puerto de comunicación a emplegar-se dende a lista de puertos hardware.

Antis de no connectar o tuyo BrailleNote Apex emplegando lo suyo client d'interficie USB, has d'instalar os controladors proporcionaus por HumanWare.

En o BrailleNote Apex BT, puetz utilizar la rueda de desplazamiento ubicada entre los puntos 1 y 4 pa quantas ordens de NVDA.
La rueda consiste en  quatro puntos direccionals, un clic en o botón central, y una rueda que chira en o sentiu u contra lo sentiu d'as agullas d'o reloch.

Contino va las asignacions d'ordens d'o BrailleNote t'o NVDA.
Por favor mira-te a documentación d'o BrailleNote pa trobar en do se localiza istas teclas.

<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar enta dezaga la linia braille |retroceder|
|Desplazar enta abant a linia braille |abanzar|
|Mover a linia braille t'a linia anterior |anterior|
|Mover a linia braille t'a linia siguient |siguient|
|Levar t'a celda braille |sensors|
|menú NVDA |espacio+punto1+punto3+punto4+punto5 (espacio+n)|
|Activar y desactivar o seguimiento de braille |anterior+siguient|
|Tecla flecha alto |espacio+punto1|
|Tecla flecha abaixo |espacio+punto4|
|Tecla flecha cucha |espacio+punmto3|
|Tecla flecha dreita |espacio+punto6|
|Tecla retroceso de pachina |espacio+punto1+punto3|
|Tecla abance de pachina |espacio+punto4+punto6|
|Tecla inicio |espacio+punto1+punto2|
|Tecla Fin |espacio+punto4+punto5|
|teclas Control+encieto |espacio+punto1+punto2+punto3|
|Teclas Control+fin |espacio+punto4+punto5+punto6|
|tecla espacio |espacio|
|intro |espacio+punto8|
|Retroceso |espacio+punto7|
|Tecla Tabulador |espacio+punto2+punto3+punto4+punto5 (espacio+t)|
|Teclas Mayus+tabulador |espacio+punto1+punto2punto5+punto6|
|Tecla Windows |espacio+punto2+punto4+punto5+punto6 (espacio+w)|
|Tecla Alt |espacio+punto1+punto3+punto4 (espacio+m)|
|Activar y desactivar l'aduya de dentrada |espacio+punto2+punto3+punto6 (espacio+h)|

Contino va las ordens asignadas a lo BrailleNote QT quan no ye en o modo de dentrada braille.

| Nombre |Tecla|
|---|---|
|Menú NVDA |leyer+n|
|Tecla flecha alto |flecha alto|
|Tecla flecha abaixo |flecha abaixo|
|Tecla flecha cucha |flecha cucha|
|Tecla flecha dreita |flecha dreita|
|Tecla recule de pachina |función+flecha alto|
|Tecla abance de pachina |función+flecha abaixo|
|Tecla encieto |función+flecha cucha|
|Tecla fin |función+flecha dreita|
|Control+teclas encieto |leyer+t|
|Control+teclas fin |leyer+b|
|Tecla intro |intro|
|Tecla recule |recule|
|Tecla tabulador |tab|
|Teclas mayus+tabulador |shift+tab|
|Tecla Windows |leyer+w|
|Tecla Alt |leyer+m|
|Commutar l'aduya de dentrada |leyer+1|

Contino va las ordens asignadas a la rueda de desplazamiento:

| Nombre |Tecla|
|---|---|
|Tecla flecha alto |flecha alto|
|Tecla flecha abaixo |flecha abaixo|
|Tecla flecha cucha |flecha cucha|
|Tecla flecha dreita |flecha dreita|
|Tecla intro |botón central|
|Tecla Tabulador |desplazar la rueda en o sentiu d'as agullas d'o reloch|
|tecla mayus+tabulador |desplazar la rueda en o sentiu contrario a las agullas d'o reloch|

<!-- KC:endInclude -->

### EcoBraille {#EcoBraille}

Lo NVDA suporta las linias EcoBraille d'[ONCE](https://www.once.es/).
En son suportaus los siguients modelos:

* EcoBraille 20
* EcoBraille 40
* EcoBraille 80
* EcoBraille Plus

En o NVDA puetz establir lo puerto serie que la linia bi ye connectada en o dialogo de [seleccionar linia braille](#SelectBrailleDisplay).
Istas linias no suportan la funcionalidat de detección automatica en segundo plan d'o NVDA.

Contino son las asignacions de teclas pa las linias EcoBraille.
Por favor mira-te la [documentación d'EcoBraille](ftp://ftp.once.es/pub/utt/bibliotecnia/Lineas_Braille/ECO/) ta descripcions de do se puet trobar ixas teclas.

<!-- KC:beginInclude -->

| nombre |tecla|
|---|---|
|Desplazar enta zaga la linia braille |T2|
|Desplazar enta devant a linia braille |T4|
|Mover a linia braille t'a linia anterior |T1|
|Mover a linia braille t'a linia siguient |T5|
|Enrutar t'a celda braille |Routing|
|Activar l'actual obchecto d'o navegador |T3|
|Cambiar t'o siguient modo de revisión |F1|
|Mover-se-ne ta l'obchecto contenedor |F2|
|Cambiar ta l'anterior modo de revisión |F3|
|Mover-se-ne ta l'obchecto anterior |F4|
|Anunciarl'obchecto actual |F5|
|Mover-se-ne t'o siguient obchecto |F6|
|Mover-se-ne ta l'obchecto d'o foco |F7|
|Mover-se-ne t'o primer obchecto conteniu |F8|
|Mover o foco d'o sistema u lo cursor t'a posición actual de revisión |F9|
|Anunciar a ubicación d'o cursor de revisión |F0|
|Conmutar o braille ancorau a |A|

<!-- KC:endInclude -->

### SuperBraille {#SuperBraille}

Lo dispositivo SuperBraille, disponible prencipalment en Taiwán, puet connectar-se por USB u por serie.
Como lo SuperBraille no tien denguna tecla fisica pa escribir u botons de desplazamiento, toda la dentrada ha a realizar-se a traviés d'un teclau estandar d'ordinador.
A resultas d'ixo, y pa mantener a compatibilidad con atros lectors de pantalla en Taiwán, se furne dos combinacions de teclas pa o desplazamiento d'a linia braille:
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar ta zaga a linia braille |Menos teclau numerico|
|Desplazar entabant a linia braille |Mas teclau numerico|

<!-- KC:endInclude -->

### Linias Eurobraille Esys/Esytime/Iris {#Eurobraille}

Lo NVDA suporta las linias Esys, Esytime y Iris d'[Eurobraille](https://www.eurobraille.fr/).
Los dispositivos Esys y Esytime-Evo se suportan quan se connecten a traviés d'USB u bluetooth.
Los dispositivos Esytime antigos nomás suportan l'USB.
Las linias Iris nomás se pueden connectar a traviés d'un puerto serie.
Por tanto, pa ixas linias, habrías de seleccionar o puerto a lo que se connecta dimpués d'haber trigau iste controlador en o dialogo d'opcions de braille.

Las linias Iris y Esys tienen un teclau braille con 10 teclas.
D'as dos teclas colocadas como barra espaciadera, la tecla d'a zurda se corresponde con a tecla de recule y a tecla dreita con a barra espaciadera.

Contino va las asignacions de teclas pa istas linias con o NVDA.
Por favor mira-te la documentación d'a pantalla pa descripcions d'do puede trobar-sen istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar la linia braille enta zaga |switch1-6Zurda, l1|
|Desplazar la linia braille entadebant |switch1-6Dreita, l8|
|Mover-se t'o foco actual |switch1-6Zurda+switch1-6Dreita, l1+l8|
|Enrotar t'a celda braille |sensors|
|Anunciar lo formato d'o texto baixo la celda braille |doble sensor|
|Mover-se t'a linia anterior en revisión |ceprén1Alto|
|Mover-se t'a siguient linia en revisión |ceprén1Baixo|
|Mover-se t'o caracter anterior en revisión |ceprén1Cucha|
|Mover-se t'o caracter siguient en revisión |ceprén1Dreita|
|Cambiar t'o modo de revisión anterior |ceprén1Cucha+ceprén1Alto|
|Cambiar t'o siguient modo de revisión |ceprén1Dreita+ceprén1Abaixo|
|Eliminar la zaguer celda braille u caracter ficau |recule|
|Transcribir qualsiquier dentrada braille y pretar la tecla intro |recule+espacio|
|tecla insert |punto3+punto5+espacio, l7|
|tecla suprimir |punto3+punto6+espacio|
|tecla inicio |punto1+punto2+punto3+espacio, ceprén2Cucha+ceprén2Alto|
|tecla fin |punto4+punto5+punto6+espacio, ceprén2Dreita+ceprén2Abaixo|
|tecla flecha cucha |punto2+espacio, ceprén2Cucha, flecha cucha|
|tecla flecha dreita |punto5+espacio, ceprén2Dreita, flecha dreita|
|tecla flecha alto |punto1+espacio,ceprén2Alto, flecha alto|
|tecla flecha abaixo |punto6+espacio, ceprén2Abaixo, flecha abaixo|
|tecla intro |ceprén2Centro|
|tecla RePach |punto1+punto3+espacio|
|tecla AvPach |punto4+punto6+espacio|
|tecla 1 numerico |punto1+punto6+recule|
|tecla 2 numerico |punto1+punto2+punto6+recule|
|tecla 3 numerico |punto1+punto4+punto6+recule|
|tecla 4 numerico |punto1+punto4+punto5+punto6+recule|
|tecla 5 numerico |punto1+punto5+punto6+recule|
|tecla 6 numerico |punto1+punto2+punto4+punto6+recule|
|tecla 7 numerico |punto1+punto2+punto4+punto5+punto6+recule|
|tecla 8 numerico |punto1+punto2+punto5+punto6+recule|
|tecla 9 numerico |punto2+punto4+punto6+recule|
|tecla Insert numerico |punto3+punto4+punto5+punto6+recule|
|tecla punto numerico |punto2+recule|
|tecla dividir numerico |punto3+punto4+recule|
|tecla multiplicar numerico |punto3+punto5+recule|
|tecla menos numerico |punto3+punto6+recule|
|tecla mas numerico |punto2+punto3+punto5+recule|
|tecla intro numerico |punto3+punto4+punto5+recule|
|tecla escape |punto1+punto2+punto4+punto5+espacio, l2|
|tecla tabuladera |punto2+punto5+punto6+espacio, l3|
|tecla mayus+tabuladera |punto2+punto3+punto5+espacio|
|tecla imprentar pantalla |punto1+punto3+punto4+punto6+espacio|
|tecla pausa |punto1+punto4+espacio|
|tecla aplicacions |punto5+punto6+recule|
|tecla f1 |punto1+recule|
|tecla f2 |punto1+punto2+recule|
|tecla f3 |punto1+punto4+recule|
|tecla f4 |punto1+punto4+punto5+recule|
|tecla f5 |punto1+punto5+recule|
|tecla f6 |punto1+punto2+punto4+recule|
|tecla f7 |punto1+punto2+punto4+punto5+recule|
|tecla f8 |punto1+punto2+punto5+recule|
|tecla f9 |punto2+punto4+recule|
|tecla f10 |punto2+punto4+punto5+recule|
|tecla f11 |punto1+punto3+recule|
|tecla f12 |punto1+punto2+punto3+recule|
|tecla windows |punto1+punto2+punto3+punto4+recule|
|tecla bloqMayus |punto7+retroceso, punto8+recule|
|tecla BloqNum |punto3+recule, punto6+recule|
|tecla mayus |punto7+espacio, l4|
|Conmutar a tecla mayus |punto1+punto7+espacio, punto4+punto7+espacio|
|tecla control |punto7+punto8+espacio, l5|
|Conmutar a tecla control |punto1+punto7+punto8+espacio, punto4+punto7+punto8+espacio|
|Tecla alt |punto8+espacio, l6|
|Conmutar a tecla alt |punto1+punto8+espacio, punto4+punto8+espacio|
|Commutar a simulación de dentrada de teclau HID |esytime):l1+ceprén1Abaixo, esytime):l8+ceprén1Abaixo|

<!-- KC:endInclude -->

### Linias Nattiq nBraille {#NattiqTechnologies}

Lo NVDA suporta linias de [Nattiq Technologies](https://www.nattiq.com/) en connectar-se a traviés d'USB.
Lo Windows 10 y superiors detectan las linias braille en connectar-las, te puet fer falta instalar los controlaldors USB si emplegas versions mas antigas d'o Windows (anteriors a Win10).
Puetz obtener-los dende lo puesto web d'o fabricant.

Contino va las asignacions de teclas pa las linias de Nattiq Technologies con o NVDA.
Por favor, mira-te la documentación d'a linia pa descripcions de do se puet trobar istas teclas.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar la linia braille enta zaga |alto|
|Desplazar la linia braille entadebant |abaixo|
|Mover la linia braille t'a linia anterior |cucha|
|Mover la linia braille t'a linia siguient |dreita|
|Guidar t'a celda braille |enrotamiento|

<!-- KC:endInclude -->

### BRLTTY {#BRLTTY}

[BRLTTY](https://www.brltty.com/) ye un programa por deseparau que puet emplegar-se pa suportar muitas linias braille.
Pa emplegar-lo te fa falta instalar [BRLTTY pa lo Windows](https://www.brltty.com/download.html).
Habrías de descargar y instalar o zaguer paquet instalable, que se dirá, por eixemplo, brltty-win-4.2-2.exe.
Quan configures la linia y puerto a emplegar,  asegura-te d'amprar gran ficacio a las instruccions, especialment si yes emplegando una linia USB y ya tiens os controladors d'o fabricant instalaus.

Pa las linias que tiengan un teclau braille, lo BRLTTY actualment maneya la dentrada braille por ell mesmo.
Por tanto, la opción de tabla braille de dentrada d'o NVDA ye irrelevant.

Lo BRLTTY no ye embrecau en a funcionalidat de detección automatica en segundo plan de linias braille d'o NVDA.

Contino va las asignacions a ordens BRLTTY pa lo NVDA.
Por favor mira-te las [listas de vinclos de teclas de BRLTTY](http://mielke.cc/brltty/doc/KeyBindings/) pa información sobre cómo se mapeya las ordens de BRLTTY pa controlar las linias braille.
<!-- KC:beginInclude -->

| Nombre |orden de BRLTTY|
|---|---|
|Desplazar a linia braille enta zaga |fwinlt (va t'a cucha una finestra)|
|Desplazar a linia braille ent'a dreita |fwinrt (va una finestra ent'a dreita)|
|Mover a linia braille t'a linia anterior |lnup (va una linia enta alto)|
|Mover a linia braille t'a siguient linia |lndn (va una linia enta baixo)|
|Guidar t'a celda braille |route (leva o cursor t'o caracter)|

<!-- KC:endInclude -->

### Linias estandar HID braille {#HIDBraille}

Iste ye un controlador experimental pa la nueva Especificación Estandar HID Braille, alcordada en 2018 por Microsoft, Google, Apple y quantas interpresas de tecnolochía d'asistencia, incluyindo NV Access. 
La esperanza ye que totz los futuros modelos de linias Braille creyaus por qualsiquier fabricant, fagan servir iste protocolo estandar que eliminará la necesidat de controladors braille especificos d'o fabricant.

La detección automatica de linias braille d'o NVDA tamién reconoixerá qualsiquier linia que suporte iste protocolo.

Contino va las asignacions de teclas actuals pa istas linias.
<!-- KC:beginInclude -->

| Nombre |Tecla|
|---|---|
|Desplazar la linia braille enta zaga |pan t'a zurda u garnela alto|
|Desplazar la linia braille enta debant |pan t'a dreita u garnela abaixo|
|Mover la linia braille t'a linia anterior |espacio+punto1|
|Mover la linia braille t'a linia siguient |espacio+punto4|
|Levar t'a celda braille |conchunto de sensors de enrotamiento 1||
|Alternar lo seguimiento de braille |alto+abaixo|
|Tecla flecha alto |ceprén alto|
|Tecla flecha enta baixo |ceprén enta baixo|
|Tecla flecha cucha |espacio+punto3 u ceprén t'a zurda|
|Tecla flecha dreita |espacio+punto6 u ceprén t'a dreita|
|Teclas mayus+tab |espacio+punto1+punto3|
|tecla tab |espacio+punto4+punto6|
|tecla alt |espacio+punto1+punto3+punto4 (espacio+m)|
|tecla escape |espacio+punto1+punto5 (espacio+y)|
|tecla intro |punto8 u intro d'o ceprén|
|tecla windows |espacio+punto3+punto4|
|teclas alt+tab |espacio+punto2+punto+punto4+punto5 (espacio+t)|
|Menú NVDA |espacio+punto1+punto3+punto4+punto5 (espacio+n)|
|teclas windows+d (minimizar todas las aplicacions) |espacio+punto1+punto4+punto5 (espacio+d)|
|Verbalizar-lo tot |espacio+punto1+punto2+punto3+punto4+punto5+punto6|

<!-- KC:endInclude -->

## Temas Abanzaus {#AdvancedTopics}
### Opcions d'a linia de comandos {#CommandLineOptions}

Lo NVDA puet acceptar una u más opcions adicionals en rancar que alteran lo suyo comportamiento.
Puetz pasar-le tantas d'opcions como amenistes
Ixas opcions se pueden pasar en rancar dende un acceso dreito (en as propiedatz de l'acceso dreito), dende o dialogo d'executar (Menú inicio -> Executar u Windows+r) u dende una consola de comandos d'o Windows.
Las opcions han d'estar deseparadas d'o nombre d'o fichero executable d'o NVDA y d'atras opcions por spacios.
Por eixemplo, una opción util ye --disable-addons, que diz a lo NVDA que suspenda totz os complementos en execución.
Ixo te permite determinar si un problema ye causau por un complemento y recuperar-lo de problemas serios causaus por complementos.

A modo d'eixemplo, puetz salir d'a copia actualment en execución d'o NVDA metendo lo siguient en o dialogo d'executar:

nvda -q

Belunas d'as opcions d'a linia de comandos tienen una versión curta y unatra larga entre que atras en tienen nomás versión larga.
Pa ixas que tienen una versión curta, puetz combinar-las asinas

|nvda -mc rotaDeConfiguración |Ixo iniciará lo NVDA con sons de rancada y lo mensache desenchegau, y la configuración especificada|
|nvda -mc rotaDeConfiguración --disable-addons |Lo mesmo que la d'alto, pero con os complementos desenchegaus|

Belunas d'as opcions acceptan parametros adicionals; p. eix. quanto s'ha de detallar o libel de rechistro u la rota t'o directorio de configuración de l'usuario.
Ixos parametros han d'estar mesos dimpués d'a opción, deseparaus d'a opción por un espacio quan se fa servir a versión curta u un simbolo igual (=) quan se fa servir a versión larga; p.eix.:

|nvda -l 10 |Diz a lo NVDA que ranque con o libel de rechistro establiu a depuración|
|nvda --log-file=c:\nvda.log |Diz a lo NVDA que escriba o suyo rechistro en c:\nvda.log|
|nvda --log-level=20 -f c:\nvda.log |Diz a lo  NVDA que ranque con o libel de rechistro establiu a información y que escriba o suyo rechistro en c:\nvda.log|

Contino va las opcions d'a linia de comandos d'o NVDA:

| Curta |Larga |Descripción|
|---|---|---|
|-h |--help |Amostrar l'aduya d'a linia de comandos y salir|
|-q |--quit |Salir d'a copia ya en execución d'o NVDA|
|-k |--check-running |Anunciar si lo NVDA se ye executando a traviés d'o codigo de salida; 0 si se ye executando, 1 si not se ye executando|
|-f nombre_fichero |--log-file=nombre_fichero |O fichero an s'han d'escribir os mensaches de rechistro|
|-l LOGLEVEL |--log-level=LOGLEVEL |Lo libel mas baixo de mensaches registraus (depuración 10, dentrada/salida 12, alvertencia de depuración 15, información 20, alvertencia 30, error 40, critico 50, desenchegau 100), predeterminadament ye alvertencia|
|-c rota_de_configuración |--config-path=rota_de_configuración |A rota an son almagazenadas todas as opcions d'o NVDA|
|-m |--minimal |Sin sons, sin interficie, sin mensache de ranque, etc|
|-s |--secure |Modo seguro: Desenchega la consola d'o Python, las caracteristicas d'os perfils como la creyación, borrau, renombrau de perfils, etc., la comprebación d'as actualizacions, bellas caixetas de verificación en o dialogo de bienvenida y en a categoría d'opcions chenerals (p. eix: Emplegar lo NVDA dimpués d'iniciar la sesión, alzar la configuración en salir, etc.), asinas como lo visor d'o rechistro y las caracteristicas de rechistro, a ormino emplegau en as pantallas seguras|
|garra |--disable-addons |Oscomplementos no tendrán efecto|
|garra |--debug-logging |Enchega lo libel de rechistro de depuración nomás pa ista execución. Ista configuración sobreescribirá qualsiquier atro argumento dau de libel de rechistro ( --loglevel, -l) incluyindo la opción de no rechistro.|
|garra |--no-logging |Desenchega lo rechistro mientras l'uso d'o NVDA. Ista opción se puet sobreescribir si s'especifica bell libel de rechistro ( --loglevel, -l) dende la linia de comandos u si lo rechistro de depuración ye enchegau.|
|garra |--no-sr-flag |No cambiar l'indicador global de lector de pantalla d'o sistema|
|garra |--install |Instala o NVDA (rancando a copia recient instalada)|
|garra |--install-silent |Instala o NVDA silenciosament (no ranca la copia recient instalada)|
|garra |--enable-start-on-logon=True|False |En instalar, enchega lo [emplegar lo NVDA en a pantalla d'inicio](#StartAtWindowsLogon) d'o NVDA|
|garra |~~copy-portable-config |En instalar, copia la configuración portable dende la rota furnida (~~config-path, -c) t'a lactual cuenta d'usuario|
|garra |--create-portable |Creya una copia portable d'o NVDA (rancando a copia creyada recientment). Requier que --portable-path siga especificada|
|garra |--create-portable-silent |Creya una copia portable d'o NVDA (sin rancar a copia recientment instalada). Requier que --portable-path siga especificada|
|garra |--portable-path=PORTABLEPATH |A rota en do se creyará una copia portable|

### Parametros d'o Sistema {#SystemWideParameters}

Lo NVDA permite configurar bellas valors en o rechistro d'o sistema que alteran o comportamiento de tot o sistema d'o NVDA.
Ixas valors s'almagazenan en o rechistro d'o sistema baixo una d'as siguients claus:

* Sistema de 32 bits: "HKEY_LOCAL_MACHINE\SOFTWARE\nvda"
* Sistema de 64 bits: "HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\nvda"

Las siguients valors pueden configurar-se baixo istas claus d'o rechistro:

| Nombre |Tipo |Valors Posibles |Descripción|
|---|---|---|---|
|configInLocalAppData |DWORD |0 (predeterminau) pa desenchegau, 1 pa enchegau |Si ye enchegau, almagazena la configuración d'usuario d'o NVDA en a carpeta local de datos d'aplicación en cuenta d'en os datos d'aplicación de roaming|
|serviceDebug |DWORD |0 (predeterminau) pa desenchegau, 1 pa enchegau |Si s'enchega, desenchega o modo seguro en os escritorios seguros d'o windows, permitindo a utilización d'a consola de Python y d'o visor d'o Rechistro. Debiu a qualques implicacions importants de seguranza, a utilización d'ista opción ye altament desaconsellada|

## Información Adicional {#FurtherInformation}

Si requiers d'información adicional u asistencia respective a lo NVDA, por favor visita o puesto Web d'o NVDA en NVDA_URL.
Aquí puetz trobar documentación adicional, asinas como suporte tecnico y recursos d'a comunidat.
Iste Puesto tamién furneix información y recursos concernients a lo desembolique d'o NVDA.

