# CASO 03 — CONFIGURACIÓN Y VERIFICACIÓN DE SEGURIDAD BÁSICA EN WINDOWS

📄 **Ruta:** `casos/caso-03-seguridad-basica-windows.md`  
**Entorno de ejecución:** Máquina Virtual (entorno no documentado)

---

## OBJETIVO

Configurar y verificar los **controles básicos de seguridad del sistema operativo Windows** después de una instalación limpia, asegurando que el equipo cuente con protección activa contra amenazas y una configuración mínima adecuada para su uso institucional.

---

## ESCENARIO

- **Equipo:** Estación de trabajo institucional (simulada)
- **Sistema operativo:** Windows 10 / 11
- **Estado inicial:** Sistema operativo instalado y con drivers verificados (Casos 01 y 02)
- **Contexto:** Post-instalación y endurecimiento básico del sistema

---

## CONTEXTO TÉCNICO

Después de instalar el sistema operativo y los controladores, es responsabilidad del soporte TI validar que los mecanismos de seguridad integrados en Windows se encuentren activos, actualizados y operativos, minimizando riesgos básicos antes de la entrega del equipo al usuario final.

---

## 1. VERIFICACIÓN DEL ESTADO INICIAL DE SEGURIDAD

### Acciones realizadas:

- Acceso a Seguridad de Windows
- Revisión del estado general de protección del sistema
- Identificación de alertas o configuraciones pendientes

### Captura:

| Archivo | Contenido |
|------|----------|
| 01-defender-estado-inicial.png | Estado inicial de la seguridad del sistema |

---

## 2. VERIFICACIÓN DEL FIREWALL DE WINDOWS

### Acciones realizadas:

- Acceso a Firewall y protección de red
- Verificación de perfiles de red disponibles
- Confirmación de firewall activo

### Captura:

| Archivo | Contenido |
|------|----------|
| 02-firewall-activo.png | Firewall de Windows habilitado |

---

## 3. CONFIGURACIÓN BÁSICA DE MICROSOFT DEFENDER

### Acciones realizadas:

- Acceso a la configuración de Protección contra virus y amenazas
- Verificación de:
  - Protección en tiempo real
  - Protección basada en la nube
- Confirmación de que los controles críticos se encuentran habilitados

### Captura:

| Archivo | Contenido |
|------|----------|
| 03-defender-configuracion.png | Configuración básica de Defender |

---

## 4. ACTUALIZACIÓN DE DEFINICIONES DE SEGURIDAD

### Acciones realizadas:

- Acceso a Actualizaciones de protección
- Búsqueda manual de actualizaciones
- Validación de definiciones de virus actualizadas

### Captura:

| Archivo | Contenido |
|------|----------|
| 04-defender-definiciones-actualizadas.png | Definiciones de seguridad actualizadas |

---

## 5. EJECUCIÓN DE ANÁLISIS RÁPIDO

### Acciones realizadas:

- Ejecución de un análisis rápido del sistema
- Espera de finalización del proceso
- Revisión de resultados del análisis

### Captura:

| Archivo | Contenido |
|------|----------|
| 05-analisis-rapido.png | Análisis rápido completado |

---

## 6. VERIFICACIÓN FINAL DEL ESTADO DE SEGURIDAD

### Acciones realizadas:

- Revisión final del panel principal de Seguridad de Windows
- Confirmación de ausencia de alertas
- Validación de estado seguro del sistema

### Captura:

| Archivo | Contenido |
|------|----------|
| 06-seguridad-verificada.png | Estado de seguridad verificado |

---

## RESULTADO FINAL

- Mecanismos básicos de seguridad habilitados
- Firewall activo y operativo
- Antivirus actualizado y funcional
- Sistema preparado para uso institucional o configuración avanzada posterior

---

📁 ## ESTRUCTURA DE CAPTURAS

screenshots/caso-03/

├── 01-defender-estado-inicial.png

├── 02-firewall-activo.png

├── 03-defender-configuracion.png

├── 04-defender-definiciones-actualizadas.png

├── 05-analisis-rapido.png

└── 06-seguridad-verificada.png


---

 **Este caso documenta controles básicos de seguridad**, aplicables a escenarios reales de soporte TI y preparación de equipos antes de su entrega al usuario final.
