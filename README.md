# Proyecto

IPO:
Entradas:
- El monto del pepido (Decimal)
- Ciudad de destino (String)
- Tipo de cliente: nuevo/recurrente (string)
- Cantidad de ítems (int)

Proceso:
- Definir que el valor sea mayor a 0
- Definir el o o los lugares de destino
- Definir si el cliente es nuevo o recurrente
- Definir la cantidad de ítems 
- Definir si el Envío gratis si monto ≥ $150.000 Y cliente recurrente.
- Definir si el Envío express si ítems ≥ 5 O monto ≥ $300.000.
- Definir si el Envío estándar en todos los demás casos.
- Definir el Costo adicional si ciudad destino es "exterior".

Salidas: 
- Categorias de despacho:
 * Gratis
 * Expres
 * Estandar
 * Adicional
- Costo del envio
- Mensaje al cliente 

Tabla de variables: 
Nombre:            Tipo C#:          Propósito:
Monto              Decimal           Valor 
Ciudad             String            Destino del envío
CntItems           Int               Número de ítems
TipoCliente        String            "Nuevo" o "Recurrentes"
CostoEnvio         Decimal           Resultado calculado
Categoria          String            Tipo de despacho asignado

ESTEBAN BEDOYA YEPES
ANDRES MUÑETON
