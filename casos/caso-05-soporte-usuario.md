# CASO 05 — SOPORTE A USUARIO (REVISIÓN Y SOLUCIÓN BÁSICA)

Ruta: `casos/caso-05-soporte-usuario.md`  
Entorno de ejecución: Equipo host (entorno no documentado)

---

## OBJETIVO

Simular una atención básica de soporte a usuario, realizando la revisión del
estado general del sistema, verificación del servicio de impresión, aplicación
de una solución simple y validación final del funcionamiento.

---

## ESCENARIO

- Equipo: Estación de trabajo institucional (simulada)
- Sistema operativo: Windows 10
- Usuario: Usuario estándar
- Contexto: Atención de incidencia básica reportada por el usuario

---

## CONTEXTO TÉCNICO

En soporte TI de primer nivel, es común que los usuarios reporten problemas
relacionados con el rendimiento del sistema o servicios básicos como la
impresión.  
El técnico debe revisar el estado del sistema, validar servicios críticos,
aplicar soluciones seguras y confirmar que el problema haya sido resuelto.

Este caso simula una atención preventiva sin necesidad de que exista una falla
real.

---

## 1. REVISIÓN DEL ESTADO GENERAL DEL SISTEMA

### Acciones realizadas

- Acceso al Administrador de tareas.
- Revisión del uso de CPU, memoria y disco.
- Validación del estado general del sistema.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 01-estado-sistema.png | Estado general del sistema en Administrador de tareas |

---

## 2. ANÁLISIS DE PROCESOS ACTIVOS

### Acciones realizadas

- Ordenamiento de procesos por uso de CPU.
- Ordenamiento de procesos por uso de memoria.
- Observación de consumo de recursos.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 02-analisis-procesos.png | Procesos ordenados por consumo de recursos |

---

## 3. VERIFICACIÓN DEL SERVICIO DE IMPRESIÓN

### Acciones realizadas

- Acceso a la consola de servicios del sistema.
- Ubicación del servicio “Cola de impresión”.
- Verificación de que el servicio se encuentre en ejecución.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 03-servicio-impresion.png | Servicio de impresión en estado activo |

---

## 4. REVISIÓN DE LA COLA DE IMPRESIÓN

### Acciones realizadas

- Acceso a la configuración de impresoras del sistema.
- Apertura de la cola de impresión.
- Verificación del estado de la cola.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 04-cola-impresion.png | Cola de impresión visualizada |

---

## 5. APLICACIÓN DE SOLUCIÓN BÁSICA

### Acciones realizadas

- Reinicio del servicio “Cola de impresión”.
- Aplicación de la acción como medida correctiva estándar.
- Confirmación del reinicio del servicio.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 05-solucion-aplicada.png | Reinicio del servicio de impresión |

---

## 6. VALIDACIÓN FINAL DEL SERVICIO

### Acciones realizadas

- Ejecución de una impresión de prueba.
- Uso de la impresora virtual “Microsoft Print to PDF”.
- Confirmación del funcionamiento correcto del servicio.

### Evidencia

| Archivo | Descripción |
|------|------------|
| 06-validacion-final.png | Impresión de prueba realizada correctamente |

---

## RESULTADO FINAL

- Estado general del sistema revisado.
- Servicio de impresión verificado y reiniciado.
- Impresión de prueba exitosa.
- Incidencia simulada atendida correctamente.

---

## 📁 ESTRUCTURA DE CAPTURAS

screenshots/caso-06/

├── 01-estado-sistema.png  
├── 02-analisis-procesos.png  
├── 03-servicio-impresion.png  
├── 04-cola-impresion.png  
├── 05-solucion-aplicada.png  
└── 06-validacion-final.png  

---

Este caso documenta una atención básica de soporte a usuario, aplicando
procedimientos estándar de diagnóstico, solución y validación en entornos de
soporte técnico.
