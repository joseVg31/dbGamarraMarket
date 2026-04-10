# dbGamarraMarket

## Descripción
Base de datos para el sistema de ventas del mercado Gamarra.
Gestiona clientes, vendedores, ventas y prendas de vestir.

## Tablas
- **CLIENTE** — Datos de los clientes
- **VENDEDOR** — Datos de los vendedores
- **PRENDA** — Catálogo de prendas de vestir
- **VENTA** — Registro de ventas realizadas
- **VENTA_DETALLE** — Detalle de prendas por venta

## Relaciones
- CLIENTE → VENTA
- VENDEDOR → VENTA
- VENTA → VENTA_DETALLE
- PRENDA → VENTA_DETALLE

## Tecnología
- MySQL
- MySQL Workbench

