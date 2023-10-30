# Camaleon_
Máquina virtual para investigaciones en fuentes abiertas OSINT

Camaleón es una iniciativa que busca diversificar las alternativas, en cuanto a maquinas virtuales en español se refiere, para investigaciones en fuentes abiertas.

![BG_v2](https://github.com/Pr3ventor/Camaleon/assets/52586785/79655ac9-b3c1-444a-9dc7-365279f6e854)



En el mundo de la ciberseguridad han aparecido con el tiempo ciertos sistemas operativos que se han orientado a una actividad especifica como las auditorias o pentesting en
el caso de Kali Linux, Parrot, Atenea, o como en la disciplina del cómputo forense como Cain, Tsurgi, entre otras. En la disciplina de las investigaciones en fuentes abiertas o como se
le conoce OSINT, hace falta alternativas que se puedan adecuar a nuestras necesidades.

Ha habido algunas iniciativas como **Buscador** creada por Michael Bazzel en inglés (Hoy no disponible) y muy especialmente en español como **Hurón** y **Osintux**. Sin embargo, la actividad
investigativa es muy dinámica y no necesariamente los investigadores poseen grandes capacidades a nivel de hardware para poder levantar un laboratorio osint. Por ello, adelanto
esta propuesta pensada desde la máxima seguridad posible, cuidando la securización y bastionado, levantando solo los servicios o puertos necesarios para ejecutar la investigación
que corresponda.

Es una distribución en GNU/Linux basada en [Debian](https://www.debian.org/index.es.html) 12 que se ha configurado con el mínimo de herramientas posibles para garantizar que sea ligera
y que ocupe la menor cantidad de recursos. Se realizo una desinstalación de las aplicaciones que no son necesarias para una investigación por lo que
reducimos la superficie de ataque al no correr riesgo de tener una aplicación vulnerable por desactualización. También se ha securizado según la
normativa vigente del becnhmark correspondiente al sistema Debian 12.

El concepto de la distribución está basado en el Camaleón o Chamaeleonidae, que posee la capacidad increíble de cambiar de color o camuflajearse con su entorno como medida
de protección ante un posible escenario de defensa o ataque. De esa forma cumplimos la premisa principal de Camaleón: **_No ser encontrado... No ser detectado_**

# Seguridad en Camaleón

* Bastionado según CIS (Center for Internet Security)
* Defensa en profundidad
* Mínima superficie de exposición
* Mínimo privilegio posible
* Escaneo periódico con [Lynis](https://cisofy.com/lynis/)
* ClamAV
* Rkhunter
* UFW (Uncomplicated Firewall)

**Herramientas incluidas**

*	[Photon](https://github.com/s0md3v/Photon) 
*	[Dmitry](https://github.com/jaygreig86/dmitry)
*	[Exiftool](https://github.com/exiftool/exiftool)
*	[Holehe](https://github.com/megadose/holehe)
*	[Geo-Recon](https://github.com/radioactivetobi/geo-recon)
*	[Osintgram](https://github.com/Datalux/Osintgram)
*	[ProtOsint](https://github.com/pixelbubble/ProtOSINT)
*	[Recong-ng](https://github.com/lanmaster53/recon-ng)
*	[Sherlock](https://github.com/sherlock-project/sherlock)
*	[SocialScan](https://github.com/iojw/socialscan)
*	[Spiderfoot](https://github.com/smicallef/spiderfoot)
*	[Namechk](https://github.com/GONZOsint/Namechk)
*	[Trape](https://github.com/jofpin/trape)
*	[OsrFramework](https://github.com/i3visio/osrframework)

 # Navegadores
Solo he agregado navegadores que permitan un nivel optimo de seguridad, privacidad y de personalización:
* **Firefox** al mejor estilo bunker.
* **Brave** con una configuración restrictiva pero funcional para investigar.
  - En Brave contamos con acceso a la red Tor con la que podemos visitar cualquier recurso en el dominio .onion.
* **Tor** con un conjunto de utilidades y buscadores en la red onion
* No cuenta con marcadores pues te obliga, si o si, a estar con la máquina encendida para poder utilizarlos.

# Utilidades web

Cuando llegamos al corazón de la actividad investigativa, nos damos cuenta que no precisamos de cientos de herramientas automaticas, sino de la herramienta mas peligrosa que puede tener un investigador... Un navegador y su conocimiento. Por ello, la propuesta de Camaleón es un repositorio muy completo en la plataforma [start.me](https://es.about.start.me/) que permite:
* Mayor flexibilidad en su configuración visual.
* Acceso desde cualquier lugar y desde cualquier dispositivo con navegador.
* Mayor privacidad y seguridad al poder configurar clave de acceso.

El repositorio esta dividido en tres categorías:

* Búsqueda de Activos y Ficheros
  - Telegram
  - Pinterest
  - Seguridad Web
  - Tweets Borrados
  - Descarga de Sitios y Enlaces
  - Privacidad y Anonimato
  - Buscadores
  - Cabeceras de Emails Análisis
* Búsqueda de Personas
  - Facebook
  - TikTok
  - SnapChat
  - Instagram
  - Teléfonos
  - NickNames
  - Dni / Jurídico
  - YouTube
  - Emails Personas
* Búsqueda de Empresas
  - Direcciones IPs
  - Histórico DNS/IP
  - Empresas
  - Lista de IPs Bloqueadas
  - Tweets Borrados
  - Web
  - Buscadores
  - Imágenes
  - Video / Imágenes
  - Filtraciones por Emails
  - Entre muchos otros
  
  ![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/b4ed165d-18ed-4837-9e4a-083956eb3e92)



# Privacidad y anonimato

* Cuenta con el antivirus ClamAV para protección de malware.
* Cuenta con Rkhunter y protección en tiempo real contra rootkit.
* Posee la utilidad Lynis que permite una periódica revisión de los aspectos de seguridad y hardening.
* Diseñada y configurada bajo el esquema de defensa en profundidad, mínimo privilegio posible y mínima superficie de exposición.
* Cuenta con NordVPN la cual se debe configurar con las credenciales del investigador y a disfrutar de una navegación anónima.
* Onionshare
  
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/99168dd0-244e-475e-8595-effad3233504)
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/cbc8fcb7-b0dc-4900-854b-c5b5b268b0b5)
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/5f107ac6-14be-4858-a67d-441355a5db73)
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/9411f083-bcfb-4b67-b89c-1f17fe3e9da9)
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/90f3859d-a990-4a90-986d-43b185a56de7)

# Funcionalidad
Camaleón cuenta con un script de tipo launcher, que permite acceder a un menú que tiene listadas todas las herramientas por categorías para poder
evaluar y decidir según corresponda.

![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/88275da7-da24-4951-a78c-e1ccffc2a984)


# Versiones

Camaleón propone brindar las capacidades, tanto a quien puede virtualizar en modo completo, como quien no posee potencia en hardware y solo puede virtualizar en modo servidor.
Esto hace de Camaleón una de las propuestas más completas en cuanto a rendimiento y utilidad para el investigador. Dándole la alternativa en su versión full o su
versión mínima para casos extremos. 

* **Versión completa**
  
  - Entorno XFCE
  - Ulauncher
  - Navegadores
  - Dock
  - Bastionado y securización
  - Herramientas y utilidades instaladas
  - Anitnivurs
  - Antimalware
  - Rkhunter
  - Lynis
  - Script de herramientas *Camaleón.sh*
  - NordVPN
  - Onionshare

![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/3171dd73-773a-4b75-a2d6-3c952bec876a)


 
* **Versión minimal**
  
Camaleón  minimal esta disponible en su versión server o modo consola, es deicr que ofrece solo la consola pura y dura que, en circuntancias austeras, nos ofrece todo lo necesario para hacer la recopilación de información mediante las herramientas a vase de script automaticos. Este modo minimal cuenta  con  las  mismas  configuraciones  que  la  versión completa en cuanto a:
  - Bastionado y securización
  - Herramientas y utilidades instaladas
  - Anitnivurs
  - Antimalware
  - Rkhunter
  - UFW (Uncomplicated Firewall)
  - Lynis
  - Script de herramientas *Camaleón.sh*
  - NordVPN
  - Onionshare
  - Bajo consumo de recursos
  - Facilidad de uso mediante conexión retoma ssh
 
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/a322fc3d-e35c-4334-bf76-0f6cc734c9eb)


# Descarga y uso

La versión 1 de Camaleón esta disponible en sus dos modalidades en:
* Enlace a repositorio mega: https://mega.nz/folder/mBNTFRia
* **Decryption key**: pfsMdmfPZIn9NQQreDsNaA
* **SHA256sum**: 60BFD883FDDE934994B58A8B03B2169C922921056767CF3D1012A0603EA026D3
* **Formato**: Ova (VirtualBox)
* **Credenciales**: Usuario: **investigador** Contraseña: **osint**
> [!IMPORTANTE]
> Recomiendo la personalización inmediata de la contraseña por una robusta siguiendo las siguientes sugerencias:
>    - No almacenar las contraseñas en texto plano.
>    - Una longitud de entre 6 y 10 caracteres.
>    - Que contenga al menos un carácter en mayúsculas y un carácter numérico.
>    - No emplear nombres o fechas personales o de familiares
>    - No emplear contraseñas comunes como 123456 o asdfghjk
>    - Cambiar la contraseña cada 3 meses.
   
> [!WARNING]
> Recuerda que todas las actividades enmarcadas en el proceso de investigación deben estar dentro del marco legal y jurudico vigente en la localidad donde estes. Es muy importante que
> conozcas bien este marco juridico para que no incurras en un delito informatico sin saberlo. 
   
# Contacto
Para cualquier duda o sugerencia pueden contactarme por:
* pr3ventor@proton.me
* Instagram: Pr3ventor

  
![image](https://github.com/Pr3ventor/Camaleon/assets/52586785/f96d4bad-978a-4cde-91a9-f774bd15d9c4)

  

  


