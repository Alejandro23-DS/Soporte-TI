# CASO 06 — MANTENIMIENTO PREVENTIVO DEL SISTEMA

Ruta: `casos/caso-06-mantenimiento-preventivo.md`  
Entorno de ejecución: Equipo host (entorno no documentado)

---

## OBJETIVO

Realizar un mantenimiento preventivo básico del sistema operativo, verificando
el estado general del equipo, uso de recursos, espacio en disco, limpieza de
archivos temporales y estado de actualizaciones, con el fin de prevenir futuros
incidentes.

---

## ESCENARIO

- Equipo: Estación de trabajo institucional (simulada)
- Sistema operativo: Windows 10
- Usuario: Usuario estándar
- Estado inicial: Sistema operativo funcional
- Contexto: Mantenimiento preventivo programado

---

## CONTEXTO TÉCNICO

El mantenimiento preventivo permite detectar condiciones que puedan afectar el
rendimiento, seguridad o estabilidad del sistema antes de que se conviertan en
incidencias.  
En soporte TI, estas tareas se realizan de forma periódica para garantizar la
continuidad operativa de los equipos.

Este caso documenta un procedimiento preventivo sin necesidad de que exista una
falla activa.

---

## 1. REVISIÓN DEL ESTADO GENERAL DEL SISTEMA

### Acciones realizadas

- Acceso al Administrador de tareas.
- Revisión del uso de CPU, memoria y disco.
- Validación visual del estado general del sistema.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 01-estado-sistema.png | Estado general del sistema en Administrador de tareas |

---

## 2. ANÁLISIS DE USO DE RECURSOS

### Acciones realizadas

- Ordenamiento de procesos por uso de CPU.
- Ordenamiento de procesos por uso de memoria.
- Identificación de consumo de recursos.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 02-uso-recursos.png | Procesos ordenados por consumo de recursos |

---

## 3. VERIFICACIÓN DE ESPACIO EN DISCO

### Acciones realizadas

- Acceso a “Este equipo”.
- Revisión visual del espacio disponible en el disco local.
- Confirmación de capacidad libre suficiente.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 03-espacio-disco.png | Estado del espacio en disco local |

---

## 4. LIMPIEZA DE ARCHIVOS TEMPORALES

### Acciones realizadas

- Acceso a la carpeta de archivos temporales del usuario.
- Eliminación de archivos temporales no necesarios.
- Confirmación de liberación de espacio.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 04-limpieza-temporales.png | Limpieza de archivos temporales |

---

## 5. VERIFICACIÓN DE ACTUALIZACIONES DEL SISTEMA

### Acciones realizadas

- Acceso a la sección Windows Update.
- Búsqueda de actualizaciones disponibles.
- Identificación del estado de soporte del sistema operativo.

### Observación

El sistema indica que ha alcanzado el fin de soporte y no recibe nuevas
actualizaciones de seguridad, condición que fue identificada y registrada como
parte del mantenimiento preventivo.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 05-windows-update.png | Estado de Windows Update del sistema |

---

## 6. VALIDACIÓN FINAL DEL SISTEMA

### Acciones realizadas

- Apertura de aplicaciones básicas del sistema.
- Confirmación de funcionamiento normal.
- Verificación de estabilidad general.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 06-validacion-final.png | Sistema operativo funcionando correctamente |

---

## RESULTADO FINAL

- Estado general del sistema verificado.
- Uso de recursos y espacio en disco revisados.
- Archivos temporales eliminados correctamente.
- Estado de actualizaciones identificado y documentado.
- Sistema validado como operativo y estable.

---

## 📁 ESTRUCTURA DE CAPTURAS

screenshots/caso-06/

├── 01-estado-sistema.png  
├── 02-uso-recursos.png  
├── 03-espacio-disco.png  
├── 04-limpieza-temporales.png  
├── 05-windows-update.png  
└── 06-validacion-final.png  

---

Este caso documenta un mantenimiento preventivo básico del sistema, aplicando
procedimientos reales de soporte TI orientados a la prevención de incidencias.
