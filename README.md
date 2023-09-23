# TRABAJO_FINAL_GYA
 Trabajo final Gestion y almacenamiento de datos

- Cuál es su problemática?

- Que se encuentra en su repositorio?

En el respositorio se encuentra un notebook llamado dataProveedores.ipynb el cual contiene la informacion de la data inicial, limpieza de datos y la data final con la que se trabajo para la problematica y solcuion del problema.Tambien se encuentra el notebook llamado BD_PROVEEDORES.ipynb el cual contiene el CRUD (create, read, update, delete) que se realiza en sqlite y python.

Se enuentra un archivo en formato PDF llamado (SENTECIAS SQL.pdf) en donde se puede observar las imagenes de los scripts o sentencias utilizados para modificar la data en la tabla proveedores, por ejp se realiza un conteo de registros , se reliza un update , insert , delete ect etc.

-Cuantos datos tomó, de que son y cuantas características tienen?
Se cuenta con 60.206 registros de 5 proveedores, y sus caracteristicas son :
Nit: Número de identificación de la IPS o persona que presto el servicio.
Tipo de dato: NUMBER (15).
Prestador: Razón social de la IPS o persona que presto el servicio.
Tipo de dato: VARCHAR2 (50).
Departamento: Departamento asociado a la factura donde se prestó el servicio.
Tipo de dato: VARCHAR2 (30).
Radicado: Número de radicación interno asignado por la EPS.
Tipo de dato: NUMBER (10). 
Número Factura: Factura emitida por la IPS.
Tipo de dato: VARCHAR2 (20).
Valor Factura: Valor de la factura presentada por la IPS.
Tipo de dato: NUMBER (16).
Estado Factura: Estado en el que se encuentra la factura (A: aprobado, B: Autorizado, G: pago).
Tipo de dato: CHAR (1)
Fecha de causación: Fecha de que ingreso la factura al ERP Financiero.
Tipo de dato: DATE
Valor saldo: Saldo actual de la factura.
Tipo de dato: NUMBER (16).
Valor cruce: Valor de los cruces aplicados a la factura.
Tipo de dato: NUMBER (16).
Valor Pago: Valor de los pagos aplicados a la factura.
Tipo de dato: NUMBER (16).
Fecha Pago: Fecha que se efectuó el pago de la factura

-Que encontró en los datos?

Se encontro informacion de 5 ips los cuales radican facturacion a la eps, en si se puede observar los pagos saldo y cruces que se realizan a una factura por proveedor (ips).

-Cómo su descubrimiento podría dar valor a una empresa?

Esto no va permitir dar una respuesta oportuna y cinsisa a la hora de conciliar con el proveedor o prestador del servicio, esto veneficia tanto a la IPS como a la EPS ya que serian datos confiables y en tiempo real.
