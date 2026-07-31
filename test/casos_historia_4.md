# Casos de Prueba - Historia de Usuario 4 (Agregar productos al carrito)

## Caso de Prueba Positivo
**ID:** TC-401  
**Título:** Agregar productos correctamente al carrito  
**Objetivo:** Validar que el sistema permite agregar productos y muestra total actualizado.  
**Precondiciones:** El usuario debe estar autenticado.  
**Datos de prueba:**  
- Producto: Café Expreso  
- Cantidad: 2  

**Pasos:**  
1. Seleccionar producto del menú.  
2. Indicar cantidad válida.  
3. Presionar "Agregar al carrito".  

**Resultado esperado:** El producto se agrega y el total se actualiza.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  

---

## Caso de Prueba Negativo
**ID:** TC-402  
**Título:** Error al agregar cantidad inválida  
**Objetivo:** Validar que el sistema rechaza cantidades no permitidas.  
**Precondiciones:** Usuario autenticado.  
**Datos de prueba:**  
- Producto: Café Expreso  
- Cantidad: -1  

**Pasos:**  
1. Seleccionar producto del menú.  
2. Indicar cantidad inválida (-1).  
3. Presionar "Agregar al carrito".  

**Resultado esperado:** El sistema muestra mensaje de error “Cantidad inválida”.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  
