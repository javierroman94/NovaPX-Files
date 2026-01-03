## 🚧 Estado del Proyecto: En Desarrollo (V 1.0.0-Beta)
Actualmente estamos trabajando en la infraestructura del Launcher. 
- [x] Sistema de autenticación.
- [x] Validación de llaves por GitHub.
- [ ] Subida oficial del ejecutable (Pendiente).
- [ ] Pruebas de carga con 100 jugadores.
- [ ] # 🚀 Nova PX - Centro de Recursos y Configuración

![NovaPX Banner](https://img.shields.io/badge/Minecraft-Eventos_Especiales-blueviolet?style=for-the-badge&logo=minecraft)
![Version](https://img.shields.io/badge/Versión_Launcher-1.0.0-green?style=for-the-badge)

Bienvenido al repositorio central de **Nova PX**. Aquí se gestionan los archivos críticos que alimentan el ecosistema de nuestro launcher exclusivo para eventos.

---

## 🛠️ Contenido del Repositorio

Este repositorio actúa como un **Backend dinámico**. El launcher consulta estos archivos en tiempo real para garantizar que todos los jugadores tengan la misma experiencia de juego:

* **`config.json`**: Controla las versiones de Minecraft, Fabric y las URLs de descarga de mods.
* **`access.json`**: Gestiona las llaves de acceso dinámicas para los eventos privados.
* **`Assets/`**: Almacena los recursos gráficos, imágenes de eventos y avatares del staff.

---

## 🔒 Seguridad y Acceso

El acceso a los eventos de **Nova PX** está restringido. 
1. Los administradores generan una clave en `access.json`.
2. El launcher valida esta clave antes de permitir la descarga de recursos.
3. Si la clave no es válida, el acceso al servidor es denegado automáticamente.

---

## 👥 Equipo Nova PX

Nuestra infraestructura es mantenida por el equipo oficial:

| Miembro | Rol | Especialidad |
| :--- | :--- | :--- |
| **JavierRoman94** | Lead Developer | Arquitectura de Software |
| **Equipo Nova** | Staff | Gestión de Eventos |

---

## 🔗 Enlaces Útiles

* [Discord Oficial](https://discord.gg/tunlace)
* [Twitter / X](https://twitter.com/tuusuario)

---
*Mantenido con ❤️ por el equipo de Nova PX.*
