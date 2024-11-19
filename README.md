# Tienda de comercio electrónico

<img src="img.drawio.png">

## Actores

### Cliente

| Actor | Cliente |
|---|---|
| Descripción | Cliente común |
| Características ||
| Relaciones ||
| Referencias | Navegar por el catalogo, Añadir al carrito, Pagar |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Sistema

| Actor | Sistema |
|---|---|
| Descripción | Sistema automatizado |
| Características ||
| Relaciones ||
| Referencias | Verificar pago, facturar compra, e-mail de confirmacion |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Banco

| Actor | Banco |
|---|---|
| Descripción | Banco del cliente |
| Características ||
| Relaciones ||
| Referencias | Confrma el pago |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

## Casos de uso

### Proporcionar datos personales

| Caso de Uso CU.1 | Navegar por catalogo |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente navega por el catalogo |
| Flujo básico ||
| Pre-condiciones ||
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Añadir al carrito

| Caso de Uso CU.2 | Añadir al carrito |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente añade al carrito |
| Flujo básico ||
| Pre-condiciones | Navegar por el catalogo |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Pagar

| Caso de Uso CU.3 | Pagar |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente paga su compra |
| Flujo básico ||
| Pre-condiciones | Añadir al carrito |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Confirma el pago

| Caso de Uso CU.4 | Confirma el pago |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Banco |
| Descripción | El banco confirma el pago |
| Flujo básico ||
| Pre-condiciones | El usuario procede a pagar |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Verificar pago

| Caso de Uso CU.5 | Verificar pago |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Sistema |
| Descripción | El Sistema verifica el pago |
| Flujo básico ||
| Pre-condiciones | El banco confirma el pago |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Facturar compra

| Caso de Uso CU.6 | Facturar compra |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Sistema |
| Descripción | El Sistema factura la compra |
| Flujo básico ||
| Pre-condiciones | El sistema confirmo la compra |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### E-mail de confirmacion

| Caso de Uso CU.7 | E-mail de confirmacion |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Sistema |
| Descripción | El Sistema envia un correo de compra realizada |
| Flujo básico ||
| Pre-condiciones | El sistema facturo la compra |
| Post-condiciones ||
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

# Sistema Videomax

<img src="sistema_videmoax.png">

## Actores

### Cliente

| Actor | Cliente |
|---|---|
| Descripción | Cliente común |
| Características ||
| Relaciones ||
| Referencias | Proporciona datos personales, Alquila peliculas, Reserva peliculas |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Proveedor

| Actor | Proveedor |
|---|---|
| Descripción | Provee peliculas |
| Características ||
| Relaciones ||
| Referencias | Abastece peliculas segun existencias |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Administrador

| Actor | Administrador |
|---|---|
| Descripción | Administrador de videomax |
| Características ||
| Relaciones ||
| Referencias | Registrar clientes, Registrar alquiler, Registrar reserva, Registrar pelicula, Actualizar proveedor |   
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

## Casos de uso

### Proporcionar datos personales

| Caso de Uso CU.1 | Proporcionar datos personales |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente proporciona sus datos personales |
| Flujo básico ||
| Pre-condiciones ||  
| Post-condiciones | Que el sistema registre al cliente |  
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Alquilar peliculas

| Caso de Uso CU.2 | Alquilar peliculas |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente alquila peliculas |
| Flujo básico | Selecciona la pelicula a alquilar y la alquila |
| Pre-condiciones | Seleccionar la pelicula |  
| Post-condiciones | Devolver la pelicula |  
| Requerimientos ||
| Notas | El sistema registra el alquiler |
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Reservar pelicula

| Caso de Uso CU.3 | Reservar peliculas |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Cliente |
| Descripción | El cliente reserva peliculas |
| Flujo básico | Selecciona la pelicula a reservar y la reservar |
| Pre-condiciones | Seleccionar la pelicula |  
| Post-condiciones ||  
| Requerimientos ||
| Notas | El sistema registra la reserva |
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Abastecer peliculas 

| Caso de Uso CU.4 | Abastecer peliculas |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Proveedor |
| Descripción | El proveedor provee de peliculas |
| Flujo básico | Abastece de peliculas segun existencias |
| Pre-condiciones ||  
| Post-condiciones ||  
| Requerimientos ||
| Notas | El sistema registra las peliculas |
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Registra a los clientes 

| Caso de Uso CU.5 | Registra a los clientes |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Administrador |
| Descripción | El sistema registra a los clientes |
| Flujo básico ||
| Pre-condiciones | El cliente proporciona sus datos |  
| Post-condiciones ||  
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Registrar alquiler 

| Caso de Uso CU.6 | Registra alquiler |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Administrador |
| Descripción | El sistema registra los alquileres |
| Flujo básico ||
| Pre-condiciones | El cliente alquila una pelicula |
| Post-condiciones ||
| Requerimientos | El cliente alquila una pelicula |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Registrar reserva

| Caso de Uso CU.7 | Registrar reserva |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Administrador |
| Descripción | El sistema registra las reservas |
| Flujo básico ||
| Pre-condiciones | El cliente realiza una reserva |  
| Post-condiciones ||
| Requerimientos | El cliente realiza una reserva |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Registrar peliculas

| Caso de Uso CU.8 | Registrar peliculas |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Administrador |
| Descripción | El sistema registra las peliculas |
| Flujo básico ||
| Pre-condiciones | El proveedor proovea peliculas |  
| Post-condiciones ||
| Requerimientos | El proveedor proovea peliculas |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |

### Actualizar proveedor

| Caso de Uso CU.9 | Actualizar proveedor |
|---|---|
| Fuentes | [GibHub jpexposito](https://github.com/jpexposito/code-learn-practice/tree/main/primero/ets/unidades/unidad-3/simulacro-1) |
| Actor | Administrador |
| Descripción | El sistema actualiza al proveedor |
| Flujo básico ||
| Pre-condiciones ||
| Post-condiciones ||
| Requerimientos ||
| Notas | Creo que este caso de uso deveria estar conectado con el caso del uso del proveedor |
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 19/Nov/2024 |