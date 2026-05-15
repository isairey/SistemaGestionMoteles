<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/139/139899.png" />

# 🏨 renzu_motels

### Sistema avanzado de gestión de moteles para FiveM 🚀

<p align="center">
  <b>renzu_motels</b> es un sistema de administración de moteles para servidores FiveM con soporte para alquiler por horas, gestión empresarial, habitaciones compartidas y compatibilidad con ESX/QBCore.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FiveM-Motel%20System-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/ESX-QBCore-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Lua-Framework-2C2D72?style=for-the-badge&logo=lua&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-RP%20Resource-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-dependencias">Dependencias</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**renzu_motels** es un recurso avanzado para servidores FiveM enfocado en la administración y renta de moteles mediante un sistema inmersivo de RolePlay.

La plataforma permite:

- 🏨 Gestión de moteles
- ⏳ Rentas por hora
- 👥 Administración de ocupantes
- 🔐 Control de acceso
- 🧳 Almacenamiento compartido
- 🚔 Interacción policial
- 🛠️ Compatibilidad MLO y Shells
- 🎮 Integración con frameworks RP

El sistema fue diseñado pensando en:

- ⚡ Experiencia inmersiva
- 🎭 RolePlay avanzado
- 🔒 Gestión segura de habitaciones
- 🧠 Configuración flexible
- 🚀 Alto rendimiento para servidores RP

---

# ✨ Características

## 🏨 Gestión de moteles

- 💼 Administración de negocios
- 💰 Configuración de tarifas
- 👨‍💼 Contratación de empleados
- 🚪 Gestión de habitaciones
- 👥 Control de ocupantes

---

## ⏳ Sistema de renta por horas

- 🕒 Alquiler temporal
- 📅 Tiempo configurable
- 💳 Cobro automático
- 📊 Gestión de expiración
- ⚡ Renovación rápida

---

## 🔐 Control de acceso

- 🔑 Llaves compartidas
- 📦 Stash configurable
- 👥 Habitaciones compartidas
- 🚪 Puertas bloqueables
- 🛠️ Lockpick integrado

---

## 🚔 Interacciones RolePlay

- 🔫 Policía puede irrumpir puertas
- 🚓 Integración policial
- 🧠 Eventos RP inmersivos
- ⚠️ Mecánicas de robo
- 🔓 Puertas forzables

---

## 🏗️ Compatibilidad avanzada

- 🏢 Soporte MLO
- 📦 Soporte Shells
- 👕 Compatibilidad con wardrobes
- 🎯 ox_target / qb-target
- 🧩 Sistemas metadata keys

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Framework RP

<p>
  <img src="https://skillicons.dev/icons?i=lua" />
</p>

- Lua
- FiveM
- ESX
- QBCore

---

## 📦 Inventarios soportados

- ox_inventory
- qb-inventory
- Metadata Keys

---

## 🎯 Sistemas Target

- ox_target
- qb-target
- Zone Markers

---

## 🧠 Librerías

- ox_lib
- Configuración modular
- Eventos sincronizados
- Gestión RP avanzada

---

# 📂 Estructura del proyecto

```bash
renzu_motels/
│
├── client/
│
├── server/
│
├── shared/
│
├── config/
│
├── html/
│
├── fxmanifest.lua
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- FiveM Server
- ESX o QBCore
- ox_lib
- ox_inventory o qb-inventory

---

# 🚀 Configuración del recurso

## 1️⃣ Descargar recurso

```bash
git clone https://github.com/your-user/renzu_motels.git
```

---

## 2️⃣ Mover recurso

Copiar carpeta a:

```bash
resources/[motels]/
```

---

## 3️⃣ Agregar al server.cfg

```cfg
ensure ox_lib
ensure renzu_motels
```

---

## 4️⃣ Configurar dependencias

Instalar:

- ox_inventory / qb-inventory
- ox_target / qb-target (opcional)

---

## 5️⃣ Reiniciar servidor

```bash
restart renzu_motels
```

---

# 🔑 Sistema de llaves

## 🗝️ Item requerido

```bash
keys
```

Las llaves permiten:

- Compartir habitaciones
- Acceso a ocupantes
- Gestión de permisos
- Interacción RP

---

# 🏨 Funcionalidades principales

## 👨‍💼 Administración empresarial

- Gestión de empleados
- Configuración de tarifas
- Administración motelera
- Control de habitaciones

---

## 🔐 Habitaciones avanzadas

- Habitaciones compartidas
- Lockpick system
- Puertas configurables
- Stash compartido

---

## 🚔 Integración RolePlay

- Policía puede romper puertas
- Eventos RP inmersivos
- Interacciones dinámicas
- Gestión criminal

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://user-images.githubusercontent.com/82306584/226111405-b162c926-6c00-4085-91ac-839f7ece117e.png" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Desarrollo FiveM
- Sistemas RP avanzados
- Frameworks ESX/QBCore
- Gestión de propiedades
- Eventos sincronizados
- Programación Lua
- Recursos multiplayer

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 🏢 Negocios administrados por jobs
- 📱 Aplicación motelera
- 🤖 Automatización avanzada
- 🔔 Notificaciones dinámicas
- 📊 Dashboard administrativo
- 💳 Sistema económico mejorado
- ☁️ Sincronización avanzada

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por la creación de sistemas RP avanzados, plataformas multiplayer y experiencias inmersivas para FiveM 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el recurso

---

# 📜 Licencia

Proyecto open source orientado a servidores RolePlay y desarrollo de recursos avanzados para FiveM.

---

<div align="center">

### 🏨 renzu_motels — sistema avanzado de moteles para FiveM 🚀

</div>
