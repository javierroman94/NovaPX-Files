<div align="center">
  <img src="https://raw.githubusercontent.com/javierroman94/NovaPX-Files/main/Assets/NovaPX.ico" width="100" height="100">
  <h1>Nova PX - Event Launcher Infrastructure</h1>
  
  [![Status](https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge)]()
  [![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-blue?style=for-the-badge&logo=minecraft)]()
  [![Framework](https://img.shields.io/badge/Framework-WPF_.NET-purple?style=for-the-badge)]()
</div>

## 🚀 Estado del Desarrollo (V 1.2.1-Beta)

Actualmente la infraestructura de **Nova PX** se encuentra en una fase avanzada de integración técnica:

- [x] **Sistema de Seguridad:** Validación dinámica de llaves vía GitHub y persistencia de sesión local.
- [x] **Motor Gráfico:** Renderizado de Skins 3D dinámicas (Premium/No-Premium).
- [x] **UX/UI:** Galería de eventos con animaciones, scrollbar moderna y Staff automático.
- [x] **Backend:** Gestión remota de versiones de Minecraft, Fabric y Mods via JSON.
- [ ] **Despliegue:** Subida oficial del ejecutable `.exe` (Pendiente).
- [ ] **QA:** Pruebas de carga con 100+ jugadores simultáneos.

---

# 🛠️ Centro de Recursos y Configuración

Este repositorio actúa como el **Backend dinámico** de Nova PX. El launcher consulta estos archivos en tiempo real para garantizar una experiencia sincronizada para todos los participantes.

### 📂 Estructura de Archivos

* **`config.json`**: Define la versión de Minecraft, el loader de Fabric y las librerías de mods.
* **`access.json`**: Puerta de enlace de seguridad. Controla las llaves de acceso activas.
* **`Assets/`**: Recursos visuales del launcher e iconos del sistema.
* **`Assets/Events/`**: Galería de imágenes para el centro de novedades (usar formato `Nombre by Autor.png`).

---

## 🔒 Protocolo de Seguridad

El acceso a los eventos está blindado mediante un sistema de dos pasos:
1. **Validación Remota:** El launcher compara la entrada del usuario con el `event_key` alojado en este repositorio.
2. **Cifrado Local:** Una vez validado, la clave se almacena de forma segura en el perfil del usuario para evitar logueos repetitivos.



---

## 👥 Staff de Nova PX (Game Masters)

Nuestra infraestructura es operada por un equipo de 8 especialistas dedicados a la experiencia del jugador:

| Miembro | Rol | Especialidad |
| :--- | :--- | :--- |
| **JavierRoman94** | Lead Developer | Arquitectura de Software & C# |

---

## 🔗 Conecta con nosotros

* [Discord Oficial](https://discord.gg/tunlace)
* [Twitter / X](https://twitter.com/tuusuario)

---
<div align="center">
  <i>Mantenido con ❤️ por el equipo de Nova PX.</i>
</div>
