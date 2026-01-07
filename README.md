<div align="center">
  <img src="https://raw.githubusercontent.com/javierroman94/NovaPX-Files/main/Assets/NovaPX.ico" width="120" height="120">
  <h1>Nova PX - Event Launcher Infrastructure</h1>
  
  [![Version](https://img.shields.io/badge/Version-1.4.0--Stable-purple?style=for-the-badge)](https://github.com/javierroman94/NovaPX-Files/releases)
  [![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-blue?style=for-the-badge&logo=minecraft)](https://www.minecraft.net/)
  [![Status](https://img.shields.io/badge/Status-Live-green?style=for-the-badge)]()
</div>

## 🌐 Arquitectura del Sistema
Nova PX utiliza una arquitectura híbrida donde el cliente (WPF) se sincroniza en tiempo real con este repositorio de archivos para gestionar la seguridad y el despliegue de mods.



---

## 💎 Características de la Versión 1.4.0

- [x] **Runtime Automation:** Instalación automática de **Java 17 (OpenJDK)** aislada del sistema.
- [x] **Discord RPC:** Presencia enriquecida con estados dinámicos y botones de invitación.
- [x] **Selective Sync:** Actualización de mods vía ZIP con limpieza de caché inteligente.
- [x] **Crash Handler:** Detección de errores del proceso de Minecraft y recolección automática de logs.
- [x] **Multi-Auth:** Soporte para sesiones persistentes y validación de llaves de evento.

---

## 🛠️ Centro de Gestión (Backend JSON)

El launcher es totalmente configurable editando los archivos en este repositorio:

| Archivo | Función | Parámetro Crítico |
| :--- | :--- | :--- |
| `config.json` | Orquestación de Versiones | `modpack_version`, `fabric_loader` |
| `access.json` | Control de Puerta (Gatekeeper) | `event_key` |

### 📂 Gestión de Assets
Los recursos visuales se cargan dinámicamente:
* **Fondo Principal:** `/Assets/fondo.jpg`
* **Cartelera de Eventos:** `/Assets/oneblock_fondo.png` (Recomendado 800x400px)

---

## 🛡️ Protocolo de Despliegue de Seguridad

1. **Handshake:** El launcher descarga `access.json` vía `HttpClient`.
2. **Challenge:** Se solicita la `event_key` si el hash local no coincide con el remoto.
3. **Execution:** Solo tras la validación se liberan los argumentos de la JVM para iniciar el juego.



---

## 👥 Equipo de Operaciones

| Miembro | Rol | Contacto |
| :--- | :--- | :--- |
| **javierroman94** | Lead Developer | [GitHub](https://github.com/javierroman94) |

---

<div align="center">
  <p><b>¿Necesitas soporte técnico?</b></p>
  <a href="https://discord.gg/VAfuFEQtjv">
    <img src="https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord">
  </a>
</div>

<div align="center">
  <br>
  <i>Nova PX - High Performance Event Infrastructure.</i>
</div>
