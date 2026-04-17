**Pseudocodigo de Usuario**

**Registro**

Inicio



Mostrar formulario de registro



Leer nombre

Leer usuario

Leer contraseña



Si usuario ya existe Entonces

&#x20;   Mostrar "Usuario ya registrado"

Sino

&#x20;   Crear Usuario

&#x20;   Guardar usuario en el sistema

&#x20;   

&#x20;   Crear Perfil de usuario

&#x20;   Asociar perfil al usuario

&#x20;   

&#x20;   

&#x20;   Mostrar "Usuario creado correctamente"

FinSi



Fin



Inicio de sesión

Inicio



Mostrar formulario de inicio de sesión



Leer usuario

Leer contraseña



Si usuario existe Entonces

&#x20;   Si contraseña es correcta Entonces

&#x20;       Crear Sesión

&#x20;       Mostrar "Bienvenido al sistema"

&#x20;   Sino

&#x20;       Mostrar "Contraseña incorrecta"

&#x20;   FinSi

Sino

&#x20;   Mostrar "Usuario no existe"

FinSi



Fin

 

**Gestión de Perfil**

Inicio



Verificar si hay sesión activa



Si sesión activa Entonces

&#x20;   Mostrar datos del perfil

&#x20;   

&#x20;   Preguntar "¿Desea editar perfil?"

&#x20;   

&#x20;   Si respuesta = "Sí" Entonces

&#x20;       Leer nuevos datos

&#x20;       Actualizar Perfil de usuario

&#x20;       Guardar cambios

&#x20;       Mostrar "Perfil actualizado correctamente"

&#x20;   FinSi

Sino

&#x20;   Mostrar "Debe iniciar sesión"

FinSi



Fin

 

**Pseudocodigo de Venta**

**Registrar Venta**

Inicio



Mostrar lista de productos



Seleccionar producto

Leer cantidad



Calcular total



Crear Venta



Crear Detalle de Venta

&#x20;   Guardar producto

&#x20;   Guardar cantidad

&#x20;   Guardar precio



Guardar venta en el sistema



Mostrar "Venta registrada correctamente"



Fin

 

&#x20;**Historial de Venta**

Inicio



Verificar si hay ventas registradas



Si existen ventas Entonces

&#x20;   Mostrar lista de ventas

&#x20;   Mostrar fecha, total y productos vendidos

Sino

&#x20;   Mostrar "No hay ventas registradas"

FinSi



Fin



**Generar Comprobante**

Inicio



Seleccionar venta



Si venta existe Entonces

&#x20;   Crear Comprobante

&#x20;   

&#x20;   Mostrar datos:

&#x20;       Productos vendidos

&#x20;       Cantidad

&#x20;       Total pagado

&#x20;   

&#x20;   Mostrar "Comprobante generado"

Sino

&#x20;   Mostrar "Venta no encontrada"

FinSi



Fin



**Pseudocodigo de Producción**

&#x09;**Registro de producción**

Inicio



Leer cantidad de leche disponible



Seleccionar producto a elaborar

&#x20;   (queso, natilla, otros)



Leer cantidad de leche a utilizar



Si leche disponible es suficiente Entonces

&#x20;   Crear Registro de producción

&#x20;   

&#x20;   Guardar cantidad de leche utilizada

&#x20;   

&#x20;   Calcular cantidad estimada de producto

&#x20;   

&#x20;   Guardar producto elaborado

&#x20;   

&#x20;   Mostrar "Producción registrada correctamente"

Sino

&#x20;   Mostrar "No hay suficiente leche"

FinSi



Fin

**Transformación de la leche**

Inicio



Leer cantidad de leche disponible



Seleccionar producto a elaborar

&#x20;   (queso, natilla, otros)



Leer cantidad de leche a utilizar



Si leche disponible es suficiente Entonces

&#x20;   Crear Registro de producción

&#x20;   

&#x20;   Guardar cantidad de leche utilizada

&#x20;   

&#x20;   Calcular cantidad estimada de producto

&#x20;   

&#x20;   Guardar producto elaborado

&#x20;   

&#x20;   Mostrar "Producción registrada correctamente"

Sino

&#x20;   Mostrar "No hay suficiente leche"

FinSi



Fin

**Control de Cantidades Producidas**

Inicio



Verificar registros de producción



Si existen registros Entonces

&#x20;   Mostrar lista de productos elaborados

&#x20;   Mostrar cantidades producidas

Sino

&#x20;   Mostrar "No hay producción registrada"

FinSi



Fin

Seguimiento del uso de la leche

Inicio



Leer cantidad total de leche



Leer cantidad de leche utilizada



Calcular leche restante



Mostrar leche utilizada

Mostrar leche restante



Estimar producción posible según leche disponible



Mostrar "Estimación de producción"



Fin

 

**Pseudocodigo de Productos**

**Agregar Producto**

Inicio



Mostrar formulario de producto



Leer nombre del producto

Leer categoría

Leer precio

Leer cantidad inicial



Crear Artículo



Asignar categoría al producto



Guardar producto en Inventario



Mostrar "Producto agregado correctamente"



Fin



 

Editar producto

Inicio



Seleccionar producto



Si producto existe Entonces

&#x20;   Mostrar datos actuales

&#x20;   

&#x20;   Leer nuevos datos

&#x20;       (nombre, categoría, precio, cantidad)

&#x20;   

&#x20;   Actualizar Artículo

&#x20;   Actualizar Inventario

&#x20;   

&#x20;   Mostrar "Producto actualizado"

Sino

&#x20;   Mostrar "Producto no encontrado"

FinSi



Fin

 

**Eliminar producto**

Inicio



Seleccionar producto



Si producto existe Entonces

&#x20;   Eliminar Artículo del sistema

&#x20;   Actualizar Inventario

&#x20;   

&#x20;   Mostrar "Producto eliminado"

Sino

&#x20;   Mostrar "Producto no encontrado"

FinSi



Fin

**Consultar inventario**

Inicio



Verificar si hay productos en inventario



Si existen productos Entonces

&#x20;   Mostrar lista de productos

&#x20;   Mostrar cantidades disponibles

&#x20;   Mostrar categorías

Sino

&#x20;   Mostrar "Inventario vacío"

FinSi



Fin

**Pseudocodigo de clientes**

**Registrar cliente**

Inicio



Mostrar formulario de cliente



Leer nombre

Leer teléfono



Verificar si cliente ya existe



Si no existe Entonces

&#x20;   Crear Cliente

&#x20;   Guardar datos

&#x20;   

&#x20;   Mostrar "Cliente registrado correctamente"

Sino

&#x20;   Mostrar "El cliente ya está registrado"

FinSi



Fin

**Historial de compras**

Inicio



Seleccionar cliente



Si cliente existe Entonces

&#x20;   Buscar Historial de compras

&#x20;   

&#x20;   Si tiene historial Entonces

&#x20;       Mostrar compras realizadas

&#x20;           (productos, fechas, montos)

&#x20;   Sino

&#x20;       Mostrar "El cliente no tiene compras registradas"

&#x20;   FinSi

Sino

&#x20;   Mostrar "Cliente no encontrado"

FinSi



Fin

 

**Clientes frecuentes**

Inicio



Revisar Historial de compras de todos los clientes



Para cada cliente Hacer

&#x20;   Contar cantidad de compras

&#x20;   

&#x20;   Si cantidad de compras es alta Entonces

&#x20;       Marcar como cliente frecuente

&#x20;   FinSi

Fin





Mostrar lista de clientes frecuentes



Fin

**Pseudocodigo de Reportes**

**Reporte de ventas diarias** 

Inicio



Leer fecha



Buscar ventas del día



Si existen ventas Entonces

&#x20;   Mostrar lista de ventas

&#x20;   Mostrar total de ventas del día

Sino

&#x20;   Mostrar "No hay ventas registradas en esa fecha"

FinSi



Fin

**Productos más vendidos**

Inicio



Obtener lista de ventas



Si existen ventas Entonces

&#x20;   Contar cantidad vendida por producto

&#x20;   

&#x20;   Ordenar productos de mayor a menor

&#x20;   

&#x20;   Mostrar productos más vendidos

Sino

&#x20;   Mostrar "No hay datos de ventas"

FinSi



Fin

**Reporte de producción** 

Inicio



Obtener registros de producción



Si existen registros Entonces

&#x20;   Mostrar cantidad de leche utilizada

&#x20;   Mostrar productos elaborados

Sino

&#x20;   Mostrar "No hay producción registrada"

FinSi



Fin

**Rendimiento de producción**

Inicio



Leer cantidad de leche utilizada

Leer cantidad de productos elaborados



Si leche utilizada > 0 Entonces

&#x20;   Calcular rendimiento

&#x20;   

&#x20;   Mostrar rendimiento de producción

Sino

&#x20;   Mostrar "No hay datos suficientes"

FinSi



Fin

**Resumen general**

Inicio



Leer cantidad de leche utilizada

Leer cantidad de productos elaborados



Si leche utilizada > 0 Entonces

&#x20;   Calcular rendimiento

&#x20;   

&#x20;   Mostrar rendimiento de producción

Sino

&#x20;   Mostrar "No hay datos suficientes"

FinSi



Fin



