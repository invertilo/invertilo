# ¡Hola! Soy Vinicius 👋

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=invertilo&theme=radial&hide_border=true" alt="GitHub Streak" />
</p>

### **🛠️ C++ Low-Level Developer | 🔍 Game Security & Reverse Engineer | 🛡️ Grey Hat Offensive Cybersecurity**
*Especializado en ingeniería inversa, desarrollo de loaders de seguridad en C++, extracción de offsets de memoria (dumping), exploits de videojuegos, cheats externos (destacando **Fernet External para Roblox**), evasión de anticheats (VAC, EAC, BE, Byfron) y desarrollo defensivo/ofensivo.*

---

<div align="left">
  <a href="https://github.com/invertilo">
    <img src="https://img.shields.io/github/followers/invertilo?label=Followers&style=for-the-badge&color=2563EB&logo=github" alt="Followers" />
  </a>
  <img src="https://img.shields.io/badge/Status-Activo-10B981?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Focus-Low__Level_%26_Game__Security-6366F1?style=for-the-badge" alt="Focus" />
  <img src="https://img.shields.io/badge/Ethic-Grey__Hat-grey?style=for-the-badge&logo=spyder" alt="Ethic" />
</div>

---

## 🧑‍💻 Presentación Profesional

Tengo 19 años y soy un apasionado del desarrollo de software a bajo nivel, la ingeniería inversa y la **ciberseguridad ofensiva bajo una filosofía de Sombrero Gris (Grey Hat)**. Considero que la mejor forma de defender un sistema es entendiendo a la perfección cómo atacarlo y vulnerarlo de manera efectiva.

Dedico mi tiempo a la investigación de vulnerabilidades lógicas en videojuegos comerciales y plataformas multijugador masivas (como **FiveM**, **Roblox** y **Counter-Strike 2**), desarrollando cargadores seguros en **C++20** con renders de alto rendimiento (**DirectX 11 / ImGui**), y creando soluciones heurísticas defensivas basadas en el comportamiento real de los exploits actuales.

---

## ⚡ Áreas de Especialización y Enfoque Técnico

### 💀 Ciberseguridad Ofensiva & Filosofía Sombrero Gris (Grey Hat)
* **Investigación de Vulnerabilidades (Vulnerability Research):** Identificación y explotación ética de fallos de diseño lógicos en APIs web y arquitecturas cliente-servidor de videojuegos.
* **Desarrollo de Exploits a Medida:** Creación de vectores de ataque de prueba (Proof of Concept - PoC) y herramientas automatizadas para demostrar fallos de control de integridad en memoria y red.
* **Análisis de Malware e Inyectores:** Desensamblado y auditoría de software malicioso, ejecutables de trampeo (mod menus) y inyectores DLL para entender sus técnicas de ocultamiento, ganchos de API (**API Hooking**) y métodos de inyección.
* **Seguridad Ofensiva en FiveM:** Auditoría de servidores para detectar vulnerabilidades en el procesamiento de eventos mediante la inyección y manipulación de llamadas remotas no autorizadas (`TriggerServerEvent`).

### 🔍 Ingeniería Inversa y Memory Hacking (Exploits de Juegos)
* **Manipulación de Memoria Activa:** Desarrollo de software externo de lectura y escritura de memoria virtual del sistema operativo utilizando APIs nativas de Windows para mapeo de memoria y evasión de privilegios.
* **Extracción de Offsets (Automated Dumping):** Desarrollo de escáneres heurísticos dinámicos y herramientas de extracción de firmas de bytes (**AOB Scanning / Pattern Scanning**) para mantener los offsets de memoria de juegos actualizados en tiempo real.
* **Evasión de Sistemas Anti-Cheat:**
  * **VAC (Valve Anti-Cheat):** Evasión de escaneos de firmas en memoria de usuario.
  * **EasyAntiCheat (EAC) & BattlEye:** Análisis de comunicación a nivel de kernel (drivers de nivel Ring 0) y suplantación de llamadas legítimas.
  * **Byfron / Hyperion (Roblox):** Análisis de mecanismos de virtualización, descifrado y empaquetamiento del espacio de usuario (User-mode obfuscation).
* **Análisis de Estructuras y Reconstrucción:** Reconstrucción de clases de motores gráficos (Unity, Unreal Engine, Source) utilizando **IDA Pro**, **x64dbg** y **ReClass.NET**.

### 🖥️ Desarrollo en C++ de Bajo Nivel y APIs Gráficas
* **C++ Moderno (C++20):** Implementación de código de alto rendimiento sin dependencias externas, reduciendo al máximo la firma en memoria.
* **Interfaces Dear ImGui:** Creación de overlays interactivos, menús premium y loaders con animaciones fluidas renderizados nativamente sobre **DirectX 11** y **DirectX 9**.
* **Protección de Código:** Ofuscación estática, encriptación en tiempo de compilación y carga dinámica de funciones API de Windows para evitar la detección heurística.

### 🛡️ FiveM Security y Desarrollo de Anticheats
* **Protección contra Inyección de Eventos:** Aseguramiento y sanitización de llamadas en el backend frente a inyecciones no autorizadas de `TriggerServerEvent` mediante validaciones estrictas de origen, tokens dinámicos temporales y límites de tasa (*rate limiting*).
* **Detección de Conductas Maliciosas:** Creación de algoritmos heurísticos cliente/servidor para identificar anomalías de movimiento (noclip, speedhack), spawns no autorizados de entidades y manipulación de variables nativas.
* **Detección de Executors:** Implementación de contramedidas activas para detectar la inyección y ejecución de scripts externos (executors de cheats) mediante el escaneo/monitoreo de tablas globales, recursos ocultos y funciones nativas alteradas.

---

## 🎮 Proyecto Destacado: Fernet External (Roblox Memory Reader)

Mi proyecto más avanzado en el ecosistema de Roblox es **Fernet External**, un asistente externo de última generación programado íntegramente en **C++20**. A diferencia de los exploits de scripting tradicionales (Luau Executors), Fernet opera de forma **totalmente externa al proceso del juego**, leyendo y escribiendo directamente la memoria virtual de `RobloxPlayerBeta.exe` mediante las APIs nativas de Windows (`ReadProcessMemory` / `WriteProcessMemory`).

Esta arquitectura externa, combinada con un overlay interactivo en **Dear ImGui y DirectX 11**, permite ejecutar funcionalidades de trampa de alto rendimiento sin modificar el código Lua interno del motor ni alterar las tablas globales del juego, minimizando drásticamente la huella de detección frente a sistemas como **Byfron (Hyperion)**.

**Capacidades Clave del Software Externo:**
* **Aimbot y Triggerbot Silencioso:** Cálculos geométricos y predicción de trayectorias sin inyectar hilos dentro del motor de Roblox.
* **Desincronización (Desync) y Anti-Aim:** Manipulación externa de ángulos de red y paquetes para confundir a otros jugadores.
* **Visuales y ESP Avanzado:** Renderizado externo de chams, cajas 2D/3D y esqueletos sobre el overlay de DirectX, basándose en datos leídos de las estructuras de entidades del juego.
* **Modificaciones del Mundo y del Jugador:** Alteración de físicas del personaje (Speedhack, Noclip, Fly) y parámetros de iluminación global mediante parches de memoria seguros.
* **Protección Anti-Cracking y Anti-Depuración:** Sistema de autodefensa del ejecutable con cifrado de strings en tiempo de compilación y monitoreo de heartbeats para evadir debuggers.

*Descubre más sobre el ecosistema de desarrollo de trampas externas en el repositorio oficial:*
➡️ **[Fernet External](https://github.com/invertilo/fernet-external)**

---

## 🛠️ Tech Stack Extendido

### 🚀 Lenguajes de Programación y Scripting
<div align="left">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white" alt="Lua" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</div>

### ⚙️ Herramientas de Ingeniería Inversa y Desarrollo de Exploits
<div align="left">
  <img src="https://img.shields.io/badge/IDA_Pro-000000?style=for-the-badge&logo=reverseengineering&logoColor=white" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/x64dbg-3F51B5?style=for-the-badge&logo=powershell&logoColor=white" alt="x64dbg" />
  <img src="https://img.shields.io/badge/Cheat_Engine-009688?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Cheat Engine" />
  <img src="https://img.shields.io/badge/ReClass.NET-4A4A4A?style=for-the-badge&logo=target&logoColor=white" alt="ReClass.NET" />
  <img src="https://img.shields.io/badge/Dear_ImGui-78D2FF?style=for-the-badge&logo=target&logoColor=black" alt="ImGui" />
</div>

### 🛡️ Ciberseguridad Ofensiva y Pentesting
<div align="left">
  <img src="https://img.shields.io/badge/Metasploit-000000?style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Nmap-007396?style=for-the-badge&logo=nmap&logoColor=white" alt="Nmap" />
  <img src="https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP" />
</div>

### 🎮 Entornos, Render y Plataformas Específicas
<div align="left">
  <img src="https://img.shields.io/badge/Roblox-000000?style=for-the-badge&logo=roblox&logoColor=white" alt="Roblox" />
  <img src="https://img.shields.io/badge/Byfron_Hyperion-FF0000?style=for-the-badge&logo=robloxstudio&logoColor=white" alt="Byfron/Hyperion" />
  <img src="https://img.shields.io/badge/FiveM-F0822B?style=for-the-badge&logo=fivem&logoColor=white" alt="FiveM" />
  <img src="https://img.shields.io/badge/DirectX_11-000000?style=for-the-badge&logo=windows&logoColor=white" alt="DirectX 11" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>

---

## 🎯 Objetivos y Enfoques de Investigación
* 🔍 **Desarrollo de Controladores Kernel (Drivers Ring 0):** Implementación de controladores firmados/mapeados dinámicamente para la lectura de memoria física saltando la protección de Handles estándar.
* 🛡️ **Análisis de Virtualización de Código:** Investigación de mecanismos avanzados de des-ofuscación para rutinas virtualizadas en VMProtect y Themida.
* 🧠 **Byfron Internals & Luau Decompilation:** Ampliar la investigación sobre el ofuscamiento del bytecode de Luau y las protecciones anti-tampering de Hyperion para mejorar las técnicas de evasión de Fernet External.
* 🐳 **Sistemas de Seguridad Distribuida:** Integración de sistemas de seguridad en loaders conectados a bases de datos relacionales robustas para mitigar el cracking por software.

---

## 📂 Proyectos Destacados

* **[Fernet External](https://github.com/invertilo/fernet-external):** Software de asistencia externa premium para Roblox. Lee y escribe la memoria del proceso del juego usando C++20 para ofrecer Aimbot, Visuales ESP, y modificaciones del mundo mediante un overlay fluido de Dear ImGui y DirectX 11, evadiendo las protecciones de Byfron/Hyperion.
* **[Fernet Loader](https://github.com/invertilo/fernet):** Gestor premium multijuegos desarrollado en C++ y Dear ImGui que permite inyectar y ejecutar menús de asistencia y cheats externos de forma controlada y segura, minimizando las firmas de detección e implementando evasión dinámica.
* **[askforvinicius](https://github.com/invertilo/askforvinicius):** Portfolio personal de seguridad premium para ejecutivos y líderes tecnológicos. Incluye un sistema integrado de simulación de intrusión (honeypot) para registrar e identificar intentos de explotación no autorizados.

---

## 📊 Estadísticas de GitHub

<p align="center">
  <img src="https://img.shields.io/github/stars/invertilo/askforvinicius?style=flat-square&logo=github&color=yellow&label=Stars%20in%20askforvinicius" alt="Stars" />
  &nbsp;
  <img src="https://img.shields.io/github/followers/invertilo?style=flat-square&logo=github&color=blue" alt="Followers" />
</p>

---
*Diseñando soluciones seguras a bajo nivel e impulsando la ciberseguridad defensiva y ofensiva.*
