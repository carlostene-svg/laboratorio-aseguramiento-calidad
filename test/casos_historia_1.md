# Casos de Prueba - Historia de Usuario 1 (Registro de usuario)

## Caso de Prueba Positivo
**ID:** TC-101  
**Título:** Registro exitoso de usuario  
**Objetivo:** Validar que el sistema permite crear una cuenta con datos válidos.  
**Precondiciones:** El usuario no debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario_valido@correo.com  
- Contraseña: Ab123#  

**Pasos:**  
1. Ingresar al formulario de registro.  
2. Introducir correo válido y contraseña válida.  
3. Presionar "Registrar".  

**Resultado esperado:** El sistema crea la cuenta y envía correo de confirmación.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  
**Notas/Evidencias:** Se completará tras ejecución.  

---

## Caso de Prueba Negativo
**ID:** TC-102  
**Título:** Registro fallido por contraseña inválida  
**Objetivo:** Validar que el sistema rechaza contraseñas que no cumplen requisitos.  
**Precondiciones:** El correo no debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario_valido@correo.com  
- Contraseña: 12345  

**Pasos:**  
1. Ingresar al formulario de registro.  
2. Introducir correo válido y contraseña inválida.  
3. Presionar "Registrar".  

**Resultado esperado:** El sistema muestra mensaje de error indicando requisitos de contraseña.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  
**Notas/Evidencias:** Se completará tras ejecución.  
