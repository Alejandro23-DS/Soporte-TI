# CASO 02 — INSTALACIÓN Y VERIFICACIÓN DE DRIVERS

Ruta: `casos/caso-02-instalacion-verificacion-drivers.md`  
Entorno de ejecución: Máquina Virtual (entorno no documentado)

---

## OBJETIVO

Instalar y verificar los controladores (drivers) necesarios del sistema después
de una instalación limpia de Windows, asegurando que todo el hardware sea
reconocido correctamente y que el sistema funcione de manera estable.

---

## ESCENARIO

- Equipo: Estación de trabajo institucional (simulada)
- Sistema operativo: Windows 10
- Estado inicial: Sistema recién instalado (resultado del Caso 01)
- Contexto: Post-instalación del sistema operativo

---

## CONTEXTO TÉCNICO

Después de una instalación limpia de Windows, el sistema puede utilizar
controladores genéricos o no contar con drivers específicos para ciertos
dispositivos.  
Es responsabilidad del área de soporte TI verificar el estado de los drivers e
instalar los necesarios para evitar problemas de rendimiento o funcionalidad.

---

## 1. REVISIÓN DEL ESTADO INICIAL DE LOS DRIVERS

### Acciones realizadas

- Acceso al Administrador de dispositivos.
- Revisión general del estado del hardware.
- Identificación de dispositivos con advertencias o controladores faltantes.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 01-administrador-dispositivos.png | Vista inicial del Administrador de dispositivos |

---

## 2. IDENTIFICACIÓN DE DRIVERS FALTANTES

### Acciones realizadas

- Revisión de la sección “Otros dispositivos”.
- Identificación de dispositivos con ícono de advertencia.
- Confirmación de controladores no instalados correctamente.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 02-drivers-faltantes.png | Dispositivo sin driver identificado |

---

## 3. INSTALACIÓN DE DRIVERS NECESARIOS

### Acciones realizadas

- Acceso a Windows Update.
- Descarga e instalación de actualizaciones disponibles.
- Aplicación de controladores proporcionados automáticamente por el sistema.

### Método utilizado

- Windows Update (método estándar en entornos institucionales y virtualizados).

### Evidencia

| Archivo | Descripción |
|------|------------|
| 03-instalacion-drivers.png | Proceso de descarga e instalación de drivers |

---

## 4. REINICIO DEL SISTEMA

### Acciones realizadas

- Reinicio del sistema para aplicar correctamente los controladores instalados.
- Inicio normal del sistema operativo después del reinicio.

(No se requiere evidencia gráfica para este paso).

---

## 5. VERIFICACIÓN FINAL DE LOS DRIVERS

### Acciones realizadas

- Nueva revisión del Administrador de dispositivos.
- Confirmación de que no existen dispositivos con advertencias.
- Validación del reconocimiento correcto del hardware.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 04-drivers-correctos.png | Administrador de dispositivos sin errores |

---

## RESULTADO FINAL

- Drivers críticos instalados correctamente.
- No se detectan errores en el Administrador de dispositivos.
- Hardware reconocido de forma adecuada.
- Sistema estable y listo para configuraciones posteriores.

---

## ESTRUCTURA DE CAPTURAS

screenshots/caso-02/

├── 01-administrador-dispositivos.png

├── 02-drivers-faltantes.png

├── 03-instalacion-drivers.png

└── 04-drivers-correctos.png

---

Este caso documenta un proceso realista de soporte TI posterior a la
instalación del sistema operativo, siguiendo prácticas estándar de verificación
y corrección de controladores.

