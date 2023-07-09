---
layout: portfolio
language: fr
translationKey: "portfolio-technologies"
---

## Technologies

Cette page présente les différentes technologies et le matériel que j'ai utilisés à un moment ou à un autre.

**La principale chose à retenir de cette liste est qu'elle n'est pas exhaustive. Elle sert à indiquer les outils et les solutions que j'ai utilisés dans le cadre de mes projets et activités personnels, professionnels ou associatifs.**

Ceci étant dit, si vous avez besoin d'éclaircissements, ou du contexte dans lequel j'ai utilisé un logiciel/matériel spécifique, envoyez-moi un mail à samuel@tugler.fr. Je m'assurerai de vous répondre et de mettre à jour la page.

### Devellopment logiciel
#### {{< mdi "mdi-database" >}}  Technologies
 - Languages:
   - Préféré: ``Python``, or ``C`` / ``C++``
   - Travaillé avec: ``C#`` / ``PHP`` / ``Javascript`` / ``Java`` / [``E-Basic``](https://support.pstnet.com/hc/en-us/articles/115012937148-SCRIPTING-Introducing-E-Basic-22871-)
   - Scripté avec: ``Bash`` / ``Batch`` / ``Powershell``
 - Frameworks / Libraries
   - Web frontend: [``VueJS``](https://vuejs.org/) (with [``Vuetify``](https://vuetifyjs.com/en/)) / [``DTL`` <small>(Django)</small>](https://docs.djangoproject.com/en/4.2/ref/templates/language/) / [``Jinja2`` <small>(Flask)</small>](https://jinja.palletsprojects.com/en/3.1.x/) / [``Twig`` <small>(Symfony)</small>](https://twig.symfony.com/)
   - Web backend: [``Django``](https://www.djangoproject.com/) / [``Flask``](https://flask.palletsprojects.com/en/2.3.x/) / [``FastAPI``](https://fastapi.tiangolo.com/) / [``Express``](https://expressjs.com/) / [``Symfony``](https://symfony.com/)
   - UI: [``PyQT5``](https://pypi.org/project/PyQt5/) / [``PySide5``](https://pypi.org/project/PySide5/) / [``SDL``](https://www.libsdl.org/)
 - Databases / Caches: 
   - SQL: [``SQLite3``](https://www.sqlite.org/index.html) / [``MariaDB``](https://mariadb.org/) / [``Postgresql``](https://www.postgresql.org/)
   - NOSQL: [``MongoDB``](https://www.mongodb.com/)
   - Cache: [``Redis``](https://redis.com/)
 - Messengers:
   - PubSub: [``MQTT``](https://mqtt.org/) (traditionel et avec websockets) / [``ZMQ``](https://zeromq.org/)
 - Manigances Windows:
   - [Extenion d'agent SNMP](https://learn.microsoft.com/en-us/windows/win32/snmp/snmp-functions) customiser pour ajouter du monitoring a un programme
   - Politique locale par utilisateur basée sur la configuration du registren appliquée à l'ouverture de session


#### {{< mdi "mdi-code-braces" >}}  Logiciel
 - IDEs / Editors:
   - Préféré: [``Jetbrains IDEs``](https://www.jetbrains.com/) / [``VSCode``](https://code.visualstudio.com/)
   - Travaillé avec: [``Visual Studio 2019 (and up)``](https://visualstudio.microsoft.com/) / [``Sublime Text``](https://www.sublimetext.com/) / [``NP++``](https://notepad-plus-plus.org/) / [``Thony``](https://thonny.org/) / [``E-Prime``](https://pstnet.com/products/e-prime/)
 - Contrôle de la source: [``Git``](https://git-scm.com/)

### Hardware / 3D
#### {{< mdi "mdi-cpu-64-bit" >}}  Puces electronique
 - SOC
   - Raspberry Pi: ``Raspberry pi 0,1,2,3,4`` / ``Compute module 4``
   - Orange pi: [``Orange Pi Zero LTS``](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-Zero-LTS.html)
   - Onion: [``Omega2``](https://onion.io/omega2/)
 - MCU:
   - Atmel: [``Atmega328``](https://www.microchip.com/en-us/product/atmega328)
   - STMicro: [``STM32F103``](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html#:~:text=STM32F103%20microcontrollers%20use%20the%20Cortex,full%2Dspeed%20interface%20and%20CAN.)
   - Raspberry Pi: [``RP2040``](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html)
   - Espressif: [``ESP32``](https://www.espressif.com/en/products/socs/ESP32) / [``ESP8266``](https://www.espressif.com/en/products/socs/esp8266) / [``ESP8285``](https://www.espressif.com/sites/default/files/documentation/0a-esp8285_datasheet_en.pdf)
 - IC:
   - Audio: [``CC85XX``](https://www.ti.com/product/CC8520) / [``RDA1846s``](https://datasheetspdf.com/pdf/1473066/RDA/RDA1846/1)
   - Ethernet:  [``W5500``](https://www.wiznet.io/product-item/w5500/) / [``LAN8720a``](https://www.microchip.com/en-us/product/LAN8720A)
   - Sans-fil: ``NRF24L01`` / [``CC1101``](https://www.ti.com/product/CC1101) / [``NEO-M8N``](https://www.u-blox.com/en/product/neo-m8-series)
   - Lumiere: ``WS2811`` / ``WS2812``
   - Autre: Conversion de signal (ie ``MAX485``), interfaces (ie ``FT232``), ect.

#### {{< mdi "mdi-desktop-classic" >}}  Logiciels
 - IDEs / Editeurs de texte:
   - Préféré: ``VSCode`` (with the appropriate module: [``ESP-IDF``](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/)/[``Pico-SDK``](https://github.com/raspberrypi/pico-sdk)/[``PlatformIO``](https://platformio.org/))
   - Travaillé avec: [``Stm32CubeIDE``](https://www.st.com/en/development-tools/stm32cubeide.html) / [``Arduino IDE``](https://www.arduino.cc/en/software/)
 - Languages:
   - ``C`` / ``C++``
   - [``Micropython``](https://micropython.org/) / [``Circuitpython``](https://circuitpython.org/)

#### {{< mdi "mdi-printer-3d" >}}  3D
 - CAD:
   - [``SolidWorks``](https://www.solidworks.com/)
   - [``OpenSCAD``](https://openscad.org/) basique
 - Slicing: [``Cura``](https://ultimaker.com/software/ultimaker-cura/)

### Audio visuel
#### {{< mdi "mdi-light-flood-down" >}} Lumière
 - Reseau [DMX](https://en.wikipedia.org/wiki/DMX512) classique (desing and deploiment)
 - [``Sunlite suite 2``](https://www.sunlitepro.com/en/sunlite.htm)
 - [``Freestyler``](https://www.freestylerdmx.be/)
  
#### {{< mdi "mdi-audio-input-rca" >}} Audio
 - Console analogiques
 - [``Midas M32``](https://www.midasconsoles.com/product.html?modelCode=P0C7R)
   - Mixing
   - Configuration / Interfacage ([Protocole OSC Midas](https://wiki.munichmakerlab.de/images/1/17/UNOFFICIAL_X32_OSC_REMOTE_PROTOCOL_%281%29.pdf) / Midi)
 - Enregistrement multi-piste avec [Reaper](https://www.reaper.fm/)
 - Audio sur [``AES50``](https://en.wikipedia.org/wiki/AES50) / [``VBAN``](https://vb-audio.com/Voicemeeter/vban.htm)
  
#### {{< mdi "mdi-video" >}} Video
 - Production video en direct [``vMix``](https://www.vmix.com/)
   - Configuration multicam quintuple utilisée simultanément en direct et en enregistrement
   - [IMAG](https://en.wikipedia.org/wiki/IMAG)
   - Syncronisation: [``LTC``](https://en.wikipedia.org/wiki/Linear_timecode) 
   - Transports: [``SDI``](https://fr.wikipedia.org/wiki/SDI) / [``NDI``](https://ndi.video/) / [``SRT``](https://www.haivision.com/products/srt-solutions/) / [``MPEG-TS``](https://en.wikipedia.org/wiki/MPEG_transport_stream) 
 - [``OBS``](https://obsproject.com/)
 - [``FFMpeg``](https://ffmpeg.org/)
 - Montage:
   - [``Adobe Premiere Pro``](https://www.adobe.com/fr/products/premiere.html) (basique)
   - [``Davinici resolve``](https://www.blackmagicdesign.com/products/davinciresolve) (basique)
   - [``Kdenlive``](https://kdenlive.org/en/) (basique)

#### {{< mdi "mdi-tune" >}} Surfaces de controle
  - OSC: [``TouchOSC``](https://hexler.net/touchosc)
  - Midi: [``BCF2000``](https://www.behringer.com/product.html?modelCode=P0246)

### Administration systeme

#### {{< mdi "mdi-desktop-tower-monitor" >}} Infrastructure
 - PVE Clusteuriser
 - Reseaux 1G/10G
 - Reseaux fibres
 - Deploiments automatique:
   - [``Ansible``](https://www.ansible.com/) / [``Chef``](https://www.chef.io/)
   - [``Github Actions``](https://github.com/features/actions)

#### {{< mdi "mdi-server" >}} Virtualisation
 - Proxmox:
   - [``Proxmox VE``](https://www.proxmox.com/en/proxmox-ve) (VM + LXC)
   - [``Proxmox BS``](https://www.proxmox.com/en/proxmox-backup-server)
 - VMWare  (basique):
   - [``vCenter``](https://www.vmware.com/products/vcenter.html)
   - [``vMotion``](https://www.vmware.com/products/vsphere/vmotion.html)
 - Microsoft  (basique):
   - [``HyperV``](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/)

#### {{< mdi "mdi-network" >}} Reseau
 - Materiel:
   - [``Mikrotik routers & switches``](https://mikrotik.com/)
   - ``Cisco switches``
   - ``SonicWall (TZ300)``
 - VPNs:
   - [``Wireguard``](https://www.wireguard.com/)
   - Solutions baser sur du SSL-VPN:
     - [``OpenVPN``](https://openvpn.net/)
       - Installation manuelle
       - [``Pritunl``](https://pritunl.com/)
     - [``SonicWall Net-Extender``](https://www.sonicwall.com/products/remote-access/vpn-clients/)
   - L2TP/IPsec avec IKEv2

#### {{< mdi "mdi-harddisk" >}} Stockage
- Platformes:
  - [``Synology``](https://www.synology.com/en-global)
  - ``Truenas`` ([``Core``](https://www.truenas.com/truenas-core/) + [``Scale``](https://www.truenas.com/truenas-scale/))
- Technologies:
  - [``ZFS``](https://en.wikipedia.org/wiki/ZFS)
  - [``Ceph``](https://docs.ceph.com/en/quincy/) (basique)
- Protocole de partage: [``iSCSI``](https://fr.wikipedia.org/wiki/ISCSI) / [``NFS``](https://en.wikipedia.org/wiki/Network_File_System) / [``SMB``](https://fr.wikipedia.org/wiki/Server_Message_Block) / [``S3``](https://aws.amazon.com/s3/) (et equivalents tel que [minio](https://min.io/))

#### {{< mdi "mdi-apps" >}} Solutions logiciel
 - Syncro horaire: [``ntpd``](https://linux.die.net/man/8/ntpd) / [``chrony``](https://en.wikipedia.org/wiki/Chrony)
 - DNS: [``bind 9``](https://www.isc.org/bind/) / [``pihole``](https://pi-hole.net/) (HA with [``gravity-sync``](https://github.com/vmstan/gravity-sync))
 - Couriel:
   - MTA: [``postfix``](https://www.postfix.org/) (Incluant authentification LDAP, rejet spams, relais, dkim, ...)
   - IMAP: [``dovecot``](https://www.dovecot.org/) (Incluant authentification LDAP)
   - Clients: [``roundcube``](https://roundcube.net/)
 - Securitée:
   - Autentification:
     - SSO: [``Keycloak``](https://www.keycloak.org/) / [``Authelia``](https://www.authelia.com/)
     - Domaine: [``Active directory Domain Services``](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview)
   - Authoritée de certification locale avec le seveur acme [``step-ca``](https://smallstep.com/docs/step-ca/)
   - Access distant: [``Guacamole``](https://guacamole.apache.org/)
 - Serveur webs: [``Caddy``](https://caddyserver.com/) / [``Apache``](https://httpd.apache.org/) / [``NGINX``](https://www.nginx.com/)
 - Monitoring: [``Observium``](https://www.observium.org/) / [``SNMP``](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol) / [``inetd``](https://en.wikipedia.org/wiki/Inetd) / [``CheckMK``](https://checkmk.com/) / [``Zabbix`` ](https://www.zabbix.com/)
 - Managment du code: [``Gitlab``](https://about.gitlab.com/) / [``Gitea``](https://about.gitea.com/)
 - Voix:
   - [``FreePBX``](https://www.freepbx.org/) (En combinaison d'un SPA3102 et de softphones)
 - Traitement des documents & documentation:
   - [``Paperless-NGX``](https://github.com/paperless-ngx/paperless-ngx)
   - [``Kiwix``](https://www.kiwix.org/)
   - [``Docuwiki``](https://www.dokuwiki.org/dokuwiki) (Avec devellopment de themes)

### Radio & Espace 
#### {{< mdi "mdi-radio-tower" >}} Radio
 - Connaissances basique en radio-communications
 - Lien de données [``AX.25``](https://en.wikipedia.org/wiki/AX.25)
 - Reseau [``SLIP``](https://fr.wikipedia.org/wiki/Serial_Line_Internet_Protocol) / [``PPP``](https://en.wikipedia.org/wiki/Point-to-Point_Protocol) sur LoRa
  
#### {{< mdi "mdi-space-station" >}} Sattelites
 - Météorologie:
   - Serie [``NOAA``](https://www.noaa.gov/satellites) (Reception [``APT``](https://www.sigidwiki.com/wiki/Automatic_Picture_Transmission_(APT)) analogique)
   - Serie [``Meteor-M``](https://en.wikipedia.org/wiki/Meteor_(satellite)#Meteor-M) (Reception [``LRPT``](https://en.wikipedia.org/wiki/Low-rate_picture_transmission))
 - Ham radio
   - [``QO-100``](https://amsat-uk.org/satellites/geo/eshail-2/)

#### {{< mdi "mdi-star-shooting" >}} Espace & Astrophotographie
 - Connaissances basique en photographie et stacking

### Miscellaneous 
