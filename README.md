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

LA tabla verificacion del Query:
<img width="735" height="553" alt="image" src="https://github.com/user-attachments/assets/84bd9112-5ec0-409d-91f1-782e912dcbbc" />

La estructura de la tabla:
<img width="741" height="574" alt="image" src="https://github.com/user-attachments/assets/3ad468a7-203c-41b4-958d-fe8119ec210a" />

