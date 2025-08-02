# Custom Android 10 ROM for VMOS Pro

Este proyecto contiene una configuración base para crear una ROM personalizada basada en Android 10, optimizada para entornos virtualizados como **VMOS Pro**. Se incluye acceso root, herramientas de desarrollo, y estructura modular para compilar desde AOSP.

## 📦 Contenido del repositorio

- `manifest.xml`: Archivo de definición `repo` para sincronizar AOSP y proyectos requeridos.
- `sync.sh`: Script bash para ejecutar `repo init` y `repo sync`.
- `build.sh`: Script automatizado para compilar la ROM para un dispositivo determinado.
- `patches/`: Parcheo opcional (como integración de Magisk, root por default o apps del sistema).
- `root/`: Archivos para incluir root permanente (por ejemplo, Magisk).
- `README.md`: Este archivo con pasos explicativos.

## 📥 Clonar y preparar el entorno

