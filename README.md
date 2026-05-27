# 🎮 SERVER - Gestor de Servidor Minecraft

Un script Python para descargar, instalar y gestionar servidores de Minecraft con soporte para múltiples versiones y mods.

## ✨ Características

- 📦 **Descarga automática** de la última versión de MSP
- 🔧 **Soporte para múltiples versiones**:
  - Forge
  - Mohist
  - Fabric
  - Vanilla
  - Paper
  - PurPur
- 🌐 **Soporte para ngrok** con múltiples regiones geográficas
- ⚙️ **Instalación y configuración automática**
- 🔐 **.gitignore automático** para mantener tu repositorio limpio

## 📋 Versiones Disponibles

| Versión | Descripción |
|---------|-------------|
| **Vanilla** | Servidor oficial de Minecraft |
| **Forge** | Soporte para mods avanzados |
| **Mohist** | Híbrido Forge + Bukkit |
| **Fabric** | Cargador de mods ligero |
| **Paper** | Versión optimizada de Spigot |
| **PurPur** | Fork de Paper con más optimizaciones |

## 🌍 Regiones de ngrok

```
ap          Asia / Pacífico (Singapore)
au          Australia (Sydney)
eu          Europa (Frankfurt)
in          India (Mumbai)
jp          Japón (Tokyo)
sa          Sudamérica (São Paulo)
us          Estados Unidos (Ohio)
us-cal-1    Estados Unidos (California)
```

## 🚀 Instalación

### Requisitos previos

- Python 3.x
- pip (gestor de paquetes de Python)
- ngrok (opcional, para tunelizado)

### Pasos de instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/santyshark/SERVER.git
   cd SERVER
   ```

2. **Instala las dependencias**:
   ```bash
   pip install requests
   ```

3. **Ejecuta el script**:
   ```bash
   python server.py
   ```

## 📝 Uso

```bash
python server.py
```

El script realizará automáticamente:
1. ✅ Descargará la última versión de MSP
2. ✅ Eliminará versiones antiguas
3. ✅ Ejecutará la instalación
4. ✅ Configurará tu servidor

## ⚠️ Advertencia Importante

> **No edites nada debajo de la sección de comentarios en `server.py`**, podrías dañar el funcionamiento del script.

## 📂 Estructura del Proyecto

```
SERVER/
├── server.py              # Script principal
├── README.md              # Este archivo
├── .gitignore             # Archivos ignorados (generado automáticamente)
├── playit.tunnels         # Configuración de túneles
├── playit.status          # Estado de playit.io
└── respaldos/             # Directorio para respaldos
```

## 🔧 Dependencias

- `requests` - Para descargar archivos desde internet
- `os` - Para operaciones del sistema de archivos
- `base64` - Para decodificar configuraciones
- `glob` - Para búsqueda de archivos
- `time` - Para gestión de tiempos

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

