# 🏰 CastleOS Recon — Herramienta de Reconocimiento de Reinos Digitales 🔍🛡️

## 📜 Historia del Reino Digital

En los vastos territorios de la red, se alzan majestuosos castillos (dispositivos) que pertenecen a diferentes reinos (sistemas operativos).  
**Lord RodHammer**, maestro herrero y estratega, ha creado un artefacto mágico (*script*) para identificar estos reinos sin alertar a sus centinelas (firewalls/seguridad).

Con la ayuda de sus leales consejeros:

- 📨 **El Maestro de Mensajería** (`subprocess`): Envía heraldos y espías (comandos Ping/Nmap)
- 🗺️ **El Cartógrafo Real** (`platform`): Identifica el terreno actual (Windows/Linux/macOS)
- 🔐 **El Descifrador de Runas** (`re`): Lee señales ocultas en pergaminos (salidas de comandos)
- 🚪 **El Guardián de la Puerta** (`sys`): Controla quién accede al artefacto (argumentos)
- 🧙 **El Consejero de Privilegios** (`os`): Verifica tu rango (root/admin) para técnicas avanzadas

---

## ⚙️ Instalación del Artefacto

### 1. Recluta a Python 3.12+ (El Lenguaje de los Hechizos)

python --version

## 2. Instala al Espía Maestro (Nmap)
Reino	Comando de Reclutamiento
🪟 Windows	Descargar desde nmap.org → Marcar "Add Nmap to PATH"
🐧 Linux	sudo apt update && sudo apt install nmap -y
🍎 macOS	brew install nmap

# 🗡️ Guía de Uso: La Estrategia de Lord RodHammer
python castleOS_recon.py <IP_del_Castillo>

## 📌 Ejemplo:

python castleOS_recon.py 192.168.1.1

# 🧭 Fases de la Misión
## 1. Reconocimiento Sigiloso (Nmap)
Si tienes rango real (root/admin):

Usa Flechas Veloces (-sS): Golpean la puerta y huyen antes de ser detectados.

Si eres un simple heraldo:

Usa Mensajeros Diplomáticos (-sT): Negocian formalmente la entrada.

# 🏹 2. Plan B: El Arquero Real (Ping + TTL)
Lanza una flecha de reconocimiento (ping)

Mide la resistencia del muro (TTL) para identificar el reino:

Resistencia (TTL)	Reino Detectado	Analogía Medieval
0–64	Linux/Unix	🧝 Fortaleza Élfica
65–128	Windows	🏰 Castillo de Piedra
129–254	Dispositivo de red	🗼 Torre de Vigilancia

# ⚔️ Ejemplos de Batalla
## 🟢 Éxito con Espía Maestro (Nmap):

[+] Explorando el castillo: 192.168.1.10

[+] ¡El espía regresó con noticias!
    Reino detectado: Linux 5.4.0-91-generic

[+] ¡Misión cumplida!
## 🟡 Respaldo con Arquero (TTL):
[+] Explorando el castillo: 192.168.1.20

[!] ¡El espía fue detectado! Enviando arquero...
    Resistencia del muro (TTL): 128
    Reino probable: Windows

[+] ¡Misión cumplida!
## 🔴 Castillo Impenetrable:
[+] Explorando el castillo: 192.168.1.30

[!] ¡El espía fue capturado! 
[!] ¡El arquero falló su flecha!

[!] El castillo guarda sus secretos... por ahora.
# 🧾 Requisitos para la Misión
🐍 Python 3.12+ (El pergamino de hechizos)

🌐 Conexión a la red (Tu caballo de batalla)

👑 Permisos (opcional): Sello real (root/admin) para técnicas sigilosas

# 🤝 Contribuir a la Forja
¿Quieres mejorar el artefacto? Envía un mensaje por paloma real:

🛡️ GitHub: github.com/RogerTeruel

✉️ Email: rodhammer.forge@proton.me

"En el mundo digital, como en los campos de batalla medievales,
el conocimiento es tu mejor armadura."
— Lord RodHammer.forge 🔨✨

⚠️ Advertencia de Caballería
🛡️ ¡Usa este artefacto con sabiduría! Solo para pruebas legales y defensa de reinos digitales.

## 🏰 CastleOS Recon — Digital Kingdom Reconnaissance Tool 🔍🛡️
📖 Digital Realm Lore
Across the vast lands of cyberspace, mighty castles (devices) rise — belonging to various kingdoms (operating systems).
Lord RodHammer, master blacksmith and strategist, has forged a magical artifact (script) to identify these kingdoms without alerting their sentinels (firewalls/security).

With the help of his loyal council:

📨 The Master of Messaging (subprocess): Sends heralds and spies (Ping/Nmap commands)

🗺️ The Royal Cartographer (platform): Identifies the current terrain (Windows/Linux/macOS)

🔐 The Rune Decoder (re): Reads hidden signals in scrolls (command output)

🚪 The Gatekeeper (sys): Controls who can access the artifact (arguments)

🧙 The Privilege Advisor (os): Checks if you hold royal rank (root/admin) for advanced techniques

⚙️ Installing the Artifact
1. Recruit Python 3.12+ (The Language of Spells)
python --version
🔗 Download from python.org

2. Install the Master Spy (Nmap)
Realm	Recruitment Command
🪟 Windows	Download from nmap.org → Check "Add Nmap to PATH"
🐧 Linux	sudo apt update && sudo apt install nmap -y
🍎 macOS	brew install nmap

🗡️ Usage Guide: Lord RodHammer’s Strategy

python castleOS_recon.py <TARGET_IP>
📌 Example:

python castleOS_recon.py 192.168.1.1
🧭 Mission Phases
🥷 1. Stealth Recon (Nmap)
If you have royal rank (root/admin):

Use Swift Arrows (-sS): They strike the gate and vanish before detection.

If you're a mere herald:

Use Diplomatic Messengers (-sT): Formally request entry.

🏹 2. Plan B: The Royal Archer (Ping + TTL)
Fires a scouting arrow (ping)

Measures the wall’s resilience (TTL) to deduce the kingdom:

Resistance (TTL)	Detected Kingdom	Medieval Analogy
0–64	Linux/Unix	🧝 Elven Fortress
65–128	Windows	🏰 Stone Castle
129–254	Network Device	🗼 Watchtower

⚔️ Battle Reports
🟢 Victory via Master Spy (Nmap):

[+] Scouting the castle: 192.168.1.10

[+] The spy returned with news!
    Detected kingdom: Linux 5.4.0-91-generic

[+] Mission accomplished!
🟡 Backup with Archer (TTL):

[+] Scouting the castle: 192.168.1.20

[!] Spy was detected! Sending archer...
    Wall resistance (TTL): 128
    Probable kingdom: Windows

[+] Mission accomplished!
🔴 Impenetrable Castle:

[+] Scouting the castle: 192.168.1.30

[!] Spy was captured! 
[!] Archer missed the shot!

[!] The castle keeps its secrets... for now.
📋 Mission Requirements
🐍 Python 3.12+

🌐 Network connectivity

👑 Privileges (optional): Royal seal (root/admin) for stealthy techniques

🤝 Contribute to the Forge
Want to improve the artifact? Send a raven:

🛡️ GitHub: github.com/RogerTeruel

✉️ Email: rodhammer.forge@proton.me

"In digital realms, as in medieval battlefields,
knowledge is your finest armor."
— Lord RodHammer.forge 🔨✨

⚠️ Code of Chivalry
🛡️ Use this artifact wisely. For legal testing and defense of digital kingdoms only.
