# ¡Hola! Soy Vinicius 👋

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=invertilo&theme=radial&hide_border=true" alt="GitHub Streak" />
</p>

### **🛠️ C++ Low-Level Developer | 🔍 Game Security & Reverse Engineer | 🛡️ Anticheat Developer**
*Desarrollador enfocado en sistemas de bajo nivel, manipulación de memoria de procesos, ingeniería inversa aplicada a videojuegos comerciales, bypasses de seguridad (VAC, EasyAntiCheat, BattlEye, Byfron/Hyperion) y desarrollo defensivo en Lua/C++.*

---

<div align="left">
  <a href="https://github.com/invertilo">
    <img src="https://img.shields.io/github/followers/invertilo?label=Followers&style=for-the-badge&color=2563EB&logo=github" alt="Followers" />
  </a>
  <img src="https://img.shields.io/badge/Status-Activo-10B981?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Focus-Low__Level_%26_Game__Security-6366F1?style=for-the-badge" alt="Focus" />
</div>

---

## 🧑‍💻 Presentación Profesional

Tengo 19 años y me especializo en la programación de sistemas a bajo nivel, la ciberseguridad ofensiva/defensiva y el análisis estático y dinámico de malware y binarios protegidos. Mi enfoque está orientado hacia el entendimiento profundo de cómo interactúan las aplicaciones con el hardware, el núcleo del sistema operativo y los componentes de integridad.

A lo largo de mi trayectoria, he investigado a fondo la arquitectura interna del sistema operativo **Windows (Windows Internals)**, dominando técnicas de inyección de código, manipulación del espacio de direcciones virtuales de procesos externos y evasión de sistemas de protección corporativos y lúdicos. Diseño cargadores dinámicos cifrados (**Secure Loaders**) en **C++20** y overlays interactivos optimizados usando aceleración por hardware.

---

## ⚡ Áreas de Especialización y Enfoque Técnico

### 🖥️ Desarrollo en C++ de Bajo Nivel y APIs Gráficas
* **C++ Moderno (C++20):** Implementación de código altamente eficiente y seguro, optimizando el uso de recursos y manejo manual de memoria sin dejar huellas en disco (*Memory-Only Execution*).
* **Dear ImGui & Overlays Premium:** Diseño de cargadores visuales modernos con animaciones cinemáticas suaves, utilizando renders personalizados sobre **DirectX 11** y **DirectX 9**.
* **Integración y Cifrado:** Consumo seguro de APIs con cifrado estático de cadenas en tiempo de compilación y llamadas cifradas a librerías dinámicas (**lazy loading**).

### 🔍 Ingeniería Inversa, Exploits y Memory Hacking
* **Análisis de Memoria Virtual:** Explotación de procesos a través de la lectura y escritura externa (`ReadProcessMemory`, `WriteProcessMemory`, `VirtualAllocEx`) y manipulación avanzada de tablas de descriptores.
* **Extracción de Offsets (Automated Dumping):** Desarrollo de escáneres heurísticos dinámicos y herramientas de extracción de firmas de bytes (**AOB Scanning / Pattern Scanning**) para mantener los offsets actualizados de forma autónoma.
* **Evasión de Sistemas Anti-Cheat:**
  * **VAC (Valve Anti-Cheat):** Análisis de firmas de escaneo y técnicas para evitar análisis en tiempo de ejecución.
  * **EasyAntiCheat (EAC) & BattlEye:** Investigación de vectores a nivel de kernel (comunicación mediante drivers IRP, manipulación de `CR3` y protección de handles).
  * **Byfron / Hyperion:** Análisis de las técnicas de virtualización y ofuscación de código del lado del usuario (User-mode protection) para descifrar el flujo del ejecutable.
* **Desensamblado y Depuración:** Deconstrucción de ejecutables comerciales protegidos mediante **IDA Pro**, **Ghidra**, **x64dbg** y **ReClass.NET**.

### 🛡️ FiveM Security y Desarrollo de Anticheats
* **Protección contra Inyección de Eventos:** Aseguramiento y sanitización de llamadas en el backend frente a inyecciones no autorizadas de `TriggerServerEvent` mediante validaciones estrictas de origen, tokens dinámicos temporales y límites de tasa (*rate limiting*).
* **Detección de Conductas Maliciosas (Cheats):** Creación de algoritmos heurísticos cliente/servidor para identificar anomalías de movimiento (noclip, speedhack), spawns no autorizados de entidades (vehículos, objetos, armas) y manipulación de memoria/variables nativas.
* **Detección de Mod Menus y Executors:** Implementación de contramedidas activas para detectar la inyección y ejecución de scripts externos (executors de cheats) mediante el escaneo/monitoreo de tablas globales, recursos ocultos y funciones nativas alteradas.

### 🛡️ Seguridad Web y Pentesting Ético
* **Auditoría de APIs:** Identificación de vulnerabilidades guiado por el estándar **OWASP Top 10 API Security** para evitar fugas de información.
* **Protección Perimetral:** Investigación en entornos de laboratorio sobre el comportamiento de sistemas WAF, mitigación de bots y mecanismos de validación (Captcha/Cloudflare) para entender cómo mejorar su configuración y robustez.

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

### 🎮 Entornos, Render y DevOps
<div align="left">
  <img src="https://img.shields.io/badge/FiveM-F0822B?style=for-the-badge&logo=fivem&logoColor=white" alt="FiveM" />
  <img src="https://img.shields.io/badge/DirectX_11-000000?style=for-the-badge&logo=windows&logoColor=white" alt="DirectX 11" />
  <img src="https://img.shields.io/badge/DirectX_9-000000?style=for-the-badge&logo=windows&logoColor=white" alt="DirectX 9" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>

---

## 🎯 Objetivos y Enfoques de Investigación
* 🔍 **Desarrollo de Controladores Kernel (Drivers Ring 0):** Implementación de controladores firmados/mapeados dinámicamente para la lectura de memoria física saltando la protección de Handles estándar.
* 🛡️ **Análisis de Virtualización de Código:** Investigación de mecanismos avanzados de des-ofuscación para rutinas virtualizadas en VMProtect y Themida.
* 🐳 **Sistemas de Seguridad Distribuida:** Integración de sistemas de seguridad en loaders conectados a bases de datos relacionales robustas para mitigar el cracking por software.

---

## 📂 Proyectos Destacados

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
