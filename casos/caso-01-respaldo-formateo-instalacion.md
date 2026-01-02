# CASO 01 — RESPALDO, FORMATEO E INSTALACIÓN DE WINDOWS

**Tipo de caso:** Soporte TI – Mantenimiento correctivo  
**Entorno:** Máquina virtual (no documentado)  
**Sistema objetivo:** Windows 10  
**Rol:** Técnico de soporte

---

## 🎯 OBJETIVO

Realizar un proceso completo de *soporte técnico profesional*, que incluya:

- Respaldo previo de información del usuario
- Formateo lógico del equipo
- Instalación limpia del sistema operativo Windows
- Verificación final del correcto funcionamiento del sistema

El objetivo principal es *evitar la pérdida de información* y entregar un equipo operativo y estable.

---

## 🖥️ ESCENARIO

- **Equipo:** Estación de trabajo institucional (simulada)
- **Estado inicial:** Equipo con Windows instalado previamente
- **Problema:** Requiere reinstalación completa del sistema
- **Contexto:** Mantenimiento correctivo preventivo

---

## 🧠 CONSIDERACIÓN PROFESIONAL PREVIA

Antes de realizar cualquier formateo, se ejecuta un **respaldo de la información del usuario**, siguiendo buenas prácticas de soporte TI.  
El respaldo se realiza desde un **entorno WinPE**, permitiendo acceder al disco sin iniciar el sistema original.

---

### Acciones realizadas

- Arranque del equipo desde **WinPE**
- Detección del disco del sistema
- Acceso a la carpeta del usuario
- Copia de archivos importantes a un medio externo

### 📸 Evidencias

| Archivo | Descripción |
|------|-----------|
| `00-arranque-winpe.png` | Inicio del entorno WinPE |
| `01-disco-detectado.png` | Disco del sistema reconocido |
| `02-carpeta-usuario.png` | Carpeta del usuario accesible |
| `03-respaldo-finalizado.png` | Respaldo completado |

📌 **Resultado:** Información del usuario respaldada correctamente antes del formateo.

---

## 🔹 1️⃣ INICIO DEL INSTALADOR DE WINDOWS

### Acciones realizadas

- Arranque del equipo desde el medio de instalación de Windows
- Carga inicial del instalador

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `04-inicio-instalador.png` | Pantalla inicial de Windows Setup |

---

## 🔹 2️⃣ CONFIGURACIÓN REGIONAL

### Acciones realizadas

- Selección de idioma del sistema
- Configuración regional
- Selección del tipo de teclado

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `05-idioma-teclado.png` | Configuración de idioma y teclado |

---

## 🔹 3️⃣ INICIO DE LA INSTALACIÓN

### Acciones realizadas

- Selección de la opción **“Instalar ahora”**

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `06-instalar-ahora.png` | Inicio del proceso de instalación |

---

## 🔹 4️⃣ TIPO DE INSTALACIÓN

### Acciones realizadas

- Selección de **Instalación personalizada (avanzada)** para una instalación limpia

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `07-tipo-instalacion.png` | Instalación personalizada seleccionada |

---

## 🔹 5️⃣ GESTIÓN DE DISCO (FORMATEO LÓGICO)

### Acciones realizadas

- Eliminación de todas las particiones existentes
- Confirmación de espacio no asignado
- Creación automática de nuevas particiones por el instalador

📌 **Este paso constituye el formateo lógico del equipo.**

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `08-particiones-eliminadas.png` | Disco sin particiones previas |

---

## 🔹 6️⃣ INSTALACIÓN DEL SISTEMA OPERATIVO

### Acciones realizadas

- Copia de archivos de Windows
- Instalación automática del sistema
- Reinicios controlados del equipo

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `10-instalacion-progreso.png` | Progreso de la instalación |

---

## 🔹 7️⃣ CONFIGURACIÓN INICIAL DEL SISTEMA (OOBE)

### Acciones realizadas

- Configuración inicial del sistema
- Creación de usuario local
- Ajustes básicos de privacidad

---

## 🔹 8️⃣ PRIMER INICIO DE SESIÓN

### Acciones realizadas

- Acceso al escritorio de Windows
- Verificación visual del entorno

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `13-escritorio-inicial.png` | Escritorio inicial del sistema |

---

## 🔹 9️⃣ VERIFICACIÓN DEL SISTEMA

### Acciones realizadas

- Verificación de versión del sistema operativo
- Validación del estado general del sistema

### 📸 Evidencia

| Archivo | Descripción |
|------|-----------|
| `14-winver.png` | Versión final de Windows |

---

## ✅ RESULTADO FINAL

- ✔ Información del usuario respaldada correctamente
- ✔ Formateo lógico realizado
- ✔ Windows instalado desde cero
- ✔ Sistema operativo funcional y estable

El equipo queda listo para tareas posteriores como instalación de drivers, antivirus o unión a dominio.

---
## 📁 RUTA DE EVIDENCIAS

screenshots/caso-01/


---

❗ **Este caso refleja un flujo real de soporte TI**, priorizando la protección de datos del usuario y la correcta reinstalación del sistema operativo.
