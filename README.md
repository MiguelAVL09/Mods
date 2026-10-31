# 🚀 ModSync Pro — Sincronizador Inteligente de Modpacks de Minecraft

<div align="center">

[![Versión](https://img.shields.io/badge/Versión-v1.3.0-10b981?style=for-the-badge&logo=electron&logoColor=white)](https://github.com/MiguelAVL09/Mods/releases/latest)
[![Plataforma](https://img.shields.io/badge/Plataforma-Windows_x64-0078d7?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MiguelAVL09/Mods/releases/latest)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.16_a_1.21+-65a30d?style=for-the-badge&logo=minecraft&logoColor=white)](https://github.com/MiguelAVL09/Mods)
[![Discord RPC](https://img.shields.io/badge/Discord-Rich_Presence-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-f59e0b?style=for-the-badge)](LICENSE)

**La solución definitiva para creadores de modpacks y comunidades de jugadores.**  
*Mantén a todos tus amigos sincronizados al 100% en tiempo real o mediante la nube 24/7, sin pasar gigabytes por Drive o Mega.*

[📥 **Descargar Instalador (Setup v1.3.0)**](https://github.com/MiguelAVL09/Mods/releases/latest/download/ModSync.Pro.Setup.1.3.0.exe) • [⚡ **Versión Portable (Sin instalación)**](https://github.com/MiguelAVL09/Mods/releases/latest/download/ModSync.Pro.1.3.0.exe) • [✨ **Novedades v1.3.0**](#-novedades-de-la-versión-v130)

</div>

---

## ⚡ ¿Por qué ModSync Pro?

¿Cansado de actualizar un mod en el servidor y tener que avisar a todos tus amigos por WhatsApp o Discord, subir la carpeta a Google Drive / Mega y esperar que descarguen 500 MB para solo un archivo de 2 MB? 

| El Método Tradicional 😫 | Con ModSync Pro 🚀 |
|---|---|
| Enlaces de Google Drive / Mediafire caídos | **Sincronización en 1 Clic** por hash SHA-256 |
| Descargar carpetas enteras de gigabytes | **Descarga diferencial**: solo baja lo que cambió |
| Amigos con versiones repetidas o corruptas | **Limpieza automática** de versiones obsoletas con respaldo |
| Pantallas negras y crashes inexplicables | **Doctor de Crashes**: detecta conflictos al instante |
| Obligados a usar Radmin VPN o Hamachi | **Cloud Hub 24/7 en GitHub** o P2P Directo sin VPNs |
| Amigos perdiendo sus shaders o minimapas | **Lista blanca inteligente**: protege sus mods personales |

---

## 🌟 Características Principales

### ☁️ 1. ModSync Cloud Hub 24/7 (Integración Nativa con GitHub)
* **Juega cuando quieras**: El Administrador publica los cambios una sola vez en el repositorio y los jugadores pueden sincronizarse **las 24 horas del día**, aunque el Admin tenga su computadora apagada.
* **Empaquetado inteligente de configuraciones**: Sincroniza carpetas `config/`, `defaultconfigs/` y scripts KubeJS comprimidos en gzip para garantizar que todos jueguen exactamente con las mismas reglas.

### ⚡ 2. ModSync Direct (P2P en Tiempo Real)
* Conexión directa ultrarrápida entre Administrador y Jugadores mediante WebSockets seguros.
* **Cero configuración de red**: Detección automática de UPnP y NAT Traversal.
* Genera códigos cortos de invitación de 1 clic: `MSYNC://...`.

### 🧹 3. Limpiador de Espacio de Minecraft (¡Nuevo en v1.3.0!)
* **Ahorra gigabytes en tu disco**: Escanea y elimina con 1 clic archivos basura acumulados en Minecraft:
  * Logs antiguos comprimidos (`.log.gz`).
  * Historial de registros viejos (`.log`), protegiendo siempre `latest.log`.
  * Reportes de fallos antiguos (`crash-reports`).
  * Archivos temporales huérfanos (`.modsync-tmp-*`).
* **100% Seguro**: Nunca borra tus mundos (`saves`), capturas de pantalla ni configuraciones personales.

### 📸 4. Galería F2 & Copiado Directo a Discord (¡Nuevo en v1.3.0!)
* Visualiza todas las capturas de pantalla tomadas con `F2` dentro de Minecraft en una galería fluida con miniaturas y fechas.
* **Botón Copiar a Discord**: Coloca la imagen en el portapapeles de Windows en formato nativo. Solo ve a Discord o WhatsApp, presiona `Ctrl + V` y envíala al instante sin buscar carpetas.

### 🎮 5. Discord Rich Presence Nativo (¡Nuevo en v1.3.0!)
* Muestra en tu perfil de Discord qué modpack estás jugando, tu recuento de mods, tu estado de sincronización y tu tiempo de sesión.
* Conexión ultra ligera por *Windows Named Pipes* (cero dependencias externas y desactivable en Ajustes).

### 🔄 6. Auto-Actualizador en Tiempo Real (¡Nuevo en v1.3.0!)
* ModSync Pro se actualiza a sí mismo en 1 clic.
* Notificaciones nativas de Windows en cuanto se publica una nueva versión oficial en GitHub.
* **Pantalla de bienvenida y novedades**: Tras actualizar, una ventana emergente te describe las nuevas funciones añadidas para que no te pierdas nada.

### 🛡️ 7. Doctor de Crashes & Diagnóstico Preventivo
* Analiza automáticamente el archivo `latest.log` y tus reportes de fallos.
* Detecta incompatibilidades comunes (p. ej. OptiFine junto a Sodium / Iris, versiones incorrectas de Java o mods duplicados).

### ⚡ 8. Optimizador de FPS & Detección de Shaders
* Identifica la presencia de shaders y recomienda automáticamente los mejores mods de rendimiento según tu loader (Fabric, Forge, NeoForge).

### 🌐 9. Estado y Ping del Servidor de Minecraft en Vivo (SLP)
* Muestra el estado del servidor de Minecraft (Online/Offline), mensaje del día (MOTD) y conteo de jugadores conectados en tiempo real directamente en la cabecera.

### 🎨 10. 5 Temas Gamer & Widget Chibi Miku con Música Lo-Fi
* Personaliza tu interfaz con temas: *Default Dark*, *Hatsune Miku Cyberpunk*, *Sakura Cherry*, *Nether Glow* y *Sculk Deep Dark*.
* Incluye reproductor de música lo-fi relajante con control de volumen para acompañar tus partidas.

---

## 📥 Descarga e Instalación

### Requisitos del Sistema
* **Sistema Operativo**: Windows 10 o Windows 11 (64-bit).
* **Minecraft**: Cualquier versión (1.12.2, 1.16.5, 1.18.2, 1.19.2, 1.20.1, 1.21+).
* **Launchers compatibles**: Cualquier launcher oficial o alternativo (CurseForge, Modrinth App, Prism Launcher, Prism, TL, Launcher Oficial de Mojang, ATLauncher, etc.).

### Opciones de Descarga
1. **[Instalador Recomendado (.exe)](https://github.com/MiguelAVL09/Mods/releases/latest/download/ModSync.Pro.Setup.1.3.0.exe)**: Crea accesos directos, se actualiza automáticamente y se integra con la bandeja del sistema.
2. **[Versión Portable (.exe)](https://github.com/MiguelAVL09/Mods/releases/latest/download/ModSync.Pro.1.3.0.exe)**: Ejecútala directamente desde cualquier carpeta o memoria USB sin instalar nada.

---

## 🚀 Guía Rápida de Uso

### 👑 Para el Administrador (Creador del Modpack)
1. Abre **ModSync Pro** en modo **Administrador**.
2. Pulsa en **`+ Nuevo Perfil`** y selecciona la carpeta de tu modpack (ej. `.minecraft` o la carpeta de tu launcher).
3. Haz clic en **`Compartir Modpack`**:
   * **Modo Cloud Hub (Recomendado)**: Sube tu modpack a GitHub con 1 clic para que esté disponible 24/7.
   * **Modo Directo**: Comparte el código `MSYNC://...` con tus amigos que jueguen en tiempo real.
4. Cada vez que agregues, actualices o quites un mod en tu PC, ModSync Pro se encargará del resto.

### 🎮 Para los Jugadores
1. Abre **ModSync Pro** en modo **Jugador**.
2. Haz clic en **`Unirse con Código o GitHub`**.
3. Pega el enlace de GitHub (`https://github.com/MiguelAVL09/Mods/...`) o el código `MSYNC://...` que te dio tu Administrador.
4. Selecciona tu carpeta de Minecraft y pulsa **`Sincronizar Ahora`**.
5. ¡Listo! Tu juego tendrá exactamente los mismos mods y configuraciones que el servidor.

---

## 🔒 Privacidad y Seguridad

* **Verificación Criptográfica**: Cada mod descargado se verifica contra su suma de comprobación **SHA-256** antes de copiarse.
* **Protección Anti-Pérdida de Datos**: Antes de eliminar mods viejos, ModSync Pro crea un respaldo local en `.modsync-backups`.
* **Protección de Partidas y Mundos**: El software solo opera en la carpeta `mods/` y archivos de configuración explícitos; tus mundos, inventarios y partidas guardadas jamás se modifican.

---

## 📋 Novedades de la Versión v1.3.0
* 🧹 **Limpiador de Minecraft**: Liberación de espacio en disco en 1 clic (logs viejos, temporales, cachés).
* 📸 **Capturas F2 directas a Discord**: Copiado de imagen al portapapeles para pegar con `Ctrl + V` en Discord o WhatsApp.
* 🎮 **Discord Rich Presence**: Estado de actividad y modpack en tiempo real en tu perfil.
* 🔄 **Auto-Actualizador de Software**: Actualizaciones automáticas con notificaciones de Windows.
* ✨ **Pantalla de Novedades**: Información emergente con los cambios al iniciar por primera vez tras una actualización.

---

<div align="center">
Desarrollado con ❤️ para la comunidad de Minecraft.  
Si te gusta ModSync Pro, ¡déjanos una ⭐ en el repositorio!
</div>
