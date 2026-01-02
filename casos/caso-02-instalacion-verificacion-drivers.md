#  CASO 02 — INSTALACIÓN Y VERIFICACIÓN DE DRIVERS

📄 **Ruta:** `casos/caso-02-instalacion-verificacion-drivers.md`  
 **Entorno de ejecución:** Máquina Virtual (entorno no documentado)

---

## 🎯 OBJETIVO

Instalar y verificar los **drivers necesarios del sistema** después de una instalación limpia de Windows, asegurando el correcto funcionamiento del hardware y la estabilidad del equipo.

---

## 🖥️ ESCENARIO

- **Equipo:** Estación de trabajo institucional (simulada)
- **Sistema operativo:** Windows 10 / 11
- **Estado inicial:** Sistema recién instalado (Caso 01)
- **Contexto:** Post-instalación del sistema operativo

---

## 🧠 CONTEXTO TÉCNICO

Después de una instalación limpia de Windows, el sistema puede utilizar
controladores genéricos o no reconocer correctamente algunos dispositivos.
Es responsabilidad del soporte TI verificar e instalar los drivers necesarios.

---

## 🔹 1️⃣ REVISIÓN DEL ESTADO INICIAL DE LOS DRIVERS

### Acciones realizadas:

- Acceso al **Administrador de dispositivos**
- Revisión del estado de los dispositivos
- Identificación de advertencias o drivers genéricos

### 📸 Captura:

| Archivo | Contenido |
|------|----------|
| 01-administrador-dispositivos.png | Estado inicial de los dispositivos |

---

## 🔹 2️⃣ IDENTIFICACIÓN DE DRIVERS FALTANTES

### Acciones realizadas:

- Identificación de dispositivos sin controlador
- Revisión de adaptadores de red, video y otros componentes
- Análisis de iconos de advertencia

### 📸 Captura:

| Archivo | Contenido |
|------|----------|
| 02-drivers-faltantes.png | Dispositivos sin driver |

---

## 🔹 3️⃣ INSTALACIÓN DE DRIVERS NECESARIOS

### Acciones realizadas:

- Instalación de drivers mediante:
  - Windows Update
  - Controladores disponibles del sistema
- Prioridad de instalación:
  - Chipset
  - Video
  - Red

### 📸 Captura:

| Archivo | Contenido |
|------|----------|
| 03-instalacion-drivers.png | Proceso de instalación |

---

## 🔹 4️⃣ REINICIO DEL SISTEMA

### Acciones realizadas:

- Reinicio del sistema para aplicar correctamente los controladores
- Inicio normal del sistema operativo

---

## 🔹 5️⃣ VERIFICACIÓN FINAL DE DRIVERS

### Acciones realizadas:

- Nueva revisión del Administrador de dispositivos
- Confirmación de ausencia de errores o advertencias
- Validación del correcto reconocimiento del hardware

### 📸 Captura:

| Archivo | Contenido |
|------|----------|
| 04-drivers-correctos.png | Drivers correctamente instalados |

---

## 🔹 6️⃣ VALIDACIÓN FUNCIONAL DEL SISTEMA

### Acciones realizadas:

- Verificación de:
  - Resolución de pantalla correcta
  - Funcionamiento de red
  - Estabilidad general del sistema

### 📸 Captura:

| Archivo | Contenido |
|------|----------|
| 05-resolucion-correcta.png | Resolución de pantalla ajustada |

---

## ✅ RESULTADO FINAL

- Drivers críticos instalados correctamente
- Dispositivos reconocidos sin errores
- Sistema estable y operativo
- Equipo listo para configuraciones posteriores

---

## 📁 ESTRUCTURA DE CAPTURAS
screenshots/caso-02/

├── 01-administrador-dispositivos.png

├── 02-drivers-faltantes.png

├── 03-instalacion-drivers.png

├── 04-drivers-correctos.png

└── 05-resolucion-correcta.png


---

**Este caso documenta una fase clave del soporte TI**, validando que el sistema
esté correctamente preparado para su uso productivo.
