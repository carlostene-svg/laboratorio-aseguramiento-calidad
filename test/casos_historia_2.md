# Casos de Prueba - Historia de Usuario 2 (Inicio de sesión)

## Caso de Prueba Positivo
**ID:** TC-201  
**Título:** Inicio de sesión exitoso  
**Objetivo:** Validar que el sistema permite acceder con credenciales correctas.  
**Precondiciones:** El usuario debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario_valido@correo.com  
- Contraseña: Ab123#

**Pasos:**  
1. Ingresar al formulario de inicio de sesión.  
2. Introducir correo y contraseña válidos.  
3. Presionar "Iniciar sesión".  

**Resultado esperado:** El sistema permite el acceso y mantiene la sesión activa.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  

---

## Caso de Prueba Negativo
**ID:** TC-202  
**Título:** Inicio de sesión fallido por credenciales incorrectas  
**Objetivo:** Validar que el sistema rechaza credenciales inválidas.  
**Precondiciones:** El usuario debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario_valido@correo.com  
- Contraseña: ContraseñaErronea  

**Pasos:**  
1. Ingresar al formulario de inicio de sesión.  
2. Introducir correo válido y contraseña incorrecta.  
3. Presionar "Iniciar sesión".  

**Resultado esperado:** El sistema muestra mensaje de error.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  
