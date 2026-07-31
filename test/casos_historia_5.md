# Casos de Prueba - Historia de Usuario 5 (Realizar pedido)

## Caso de Prueba Positivo
**ID:** TC-501  
**Título:** Confirmación exitosa de pedido  
**Objetivo:** Validar que el sistema permite confirmar pedido y genera número de orden.  
**Precondiciones:** El carrito debe tener productos.  
**Datos de prueba:**  
- Método de pago: Tarjeta simulada  

**Pasos:**  
1. Acceder al carrito.  
2. Revisar resumen del pedido.  
3. Seleccionar método de pago.  
4. Confirmar pedido.  

**Resultado esperado:** Se genera número único de orden.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  

---

## Caso de Prueba Negativo
**ID:** TC-502  
**Título:** Error al confirmar sin método de pago  
**Objetivo:** Validar que el sistema no permite confirmar pedido sin método de pago.  
**Precondiciones:** Carrito con productos.  
**Datos de prueba:** N/A  

**Pasos:**  
1. Acceder al carrito.  
2. Revisar resumen del pedido.  
3. No seleccionar método de pago.  
4. Presionar "Confirmar".  

**Resultado esperado:** El sistema muestra mensaje de error “Seleccione método de pago”.  
**Resultado obtenido:** Pendiente.  
**Estado:** Pendiente.  
