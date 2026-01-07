# CASO 04 — GESTIÓN DE USUARIOS Y PERMISOS LOCALES

📄 Ruta: `casos/caso-04-gestion-usuarios-permisos.md`  
Entorno de ejecución: Máquina Virtual (Windows)

---

## OBJETIVO

Gestionar usuarios locales en Windows mediante la creación de una
cuenta estándar, validando la correcta asignación de grupos y
la aplicación de restricciones de privilegios.

---

## ESCENARIO

- Equipo institucional (simulado)
- Sistema operativo: Windows 10 / 11
- Acceso inicial con cuenta administrativa
- Uso posterior con cuenta estándar

---

## CONTEXTO TÉCNICO

En entornos institucionales no se debe operar con privilegios
administrativos de forma cotidiana.  
El área de soporte TI debe garantizar que los usuarios finales
tengan únicamente los permisos necesarios para su trabajo diario.

---

## 1. REVISIÓN DE USUARIOS LOCALES EXISTENTES

### Acciones realizadas

- Acceso a la consola Usuarios y grupos locales
- Revisión de cuentas existentes en el sistema

### Evidencia

| Archivo | Descripción |
|------|------------|
| 01-usuarios-existentes.png | Lista de usuarios locales existentes |

---

## 2. CREACIÓN DE USUARIO ESTÁNDAR

### Acciones realizadas

- Creación de un nuevo usuario local estándar
- Definición de contraseña
- Usuario destinado a uso diario

### Evidencia

| Archivo | Descripción |
|------|------------|
| 02-usuario-estandar-creado.png | Usuario estándar creado correctamente |

---

## 3. VERIFICACIÓN DE GRUPOS DEL USUARIO

### Acciones realizadas

- Revisión de los grupos asignados al usuario
- Confirmación de que no pertenece al grupo **Administradores**

### Evidencia

| Archivo | Descripción |
|------|------------|
| 03-grupos-usuario.png | Grupos asignados al usuario estándar |

---

## 4. INICIO DE SESIÓN CON USUARIO ESTÁNDAR

### Acciones realizadas

- Cierre de sesión administrativa
- Inicio de sesión con el usuario estándar
- Carga correcta del perfil

### Evidencia

| Archivo | Descripción |
|------|------------|
| 04-inicio-sesion-usuario.png | Escritorio cargado con usuario estándar |

---

## 5. VALIDACIÓN DE RESTRICCIÓN DE PRIVILEGIOS

### Acciones realizadas

- Intento de acceso a carpetas protegidas del sistema
- Confirmación de restricción por permisos insuficientes

### Evidencia

| Archivo | Descripción |
|------|------------|
| 05-restriccion-privilegios.png | Bloqueo de acceso por permisos |

---

## 6. VERIFICACIÓN FINAL DEL SISTEMA

### Acciones realizadas

- Uso normal del sistema por parte del usuario estándar
- Acceso a aplicaciones básicas
- Navegación web funcional

### Evidencia

| Archivo | Descripción |
|------|------------|
| 06-verificacion-final.png | Funcionamiento normal del sistema |

---

## RESULTADO FINAL

- Usuario estándar creado correctamente
- Permisos aplicados según buenas prácticas
- Restricción efectiva de privilegios administrativos
- Sistema listo para uso institucional

---

## CONCLUSIÓN

La correcta gestión de usuarios locales permite reducir riesgos
de seguridad, evitar cambios no autorizados en el sistema y
mantener un entorno controlado y estable para el usuario final.
