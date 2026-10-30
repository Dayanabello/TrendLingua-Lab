# 06. Solución y flujo de información

## Solución propuesta

**¿Qué cambia en el proceso con la solución (máximo 5 líneas):**

Se implementa un contador robótico de pastillas con piezas impresas en 3D, que se activa al ingresar el medicamento y la cantidad solicitada.  
El sistema cuenta y dispensa automáticamente la dosis, reduciendo el conteo manual y el tiempo de atención.  
El auxiliar verifica en pantalla que la cantidad dispensada coincida con el pedido y luego empaca y entrega el medicamento.  
Si la cantidad no es correcta, se ajusta el conteo antes de continuar.  
Así se disminuyen los errores y se mejora la rapidez y precisión del servicio.

## Flujo de información

assets/flujo-informacion modi.png

| Paso | Entrada (qué información llega) | Proceso (qué se hace) | Responsable (quién) | Salida (qué información sale) |
|---|---|---|---|---|
| 1 | Solicitud del cliente: medicamento y cantidad de pastillas. | Recibir la solicitud y registrar el medicamento y la dosis requerida. | Auxiliar de farmacia. | Pedido registrado con medicamento y cantidad solicitada. |
| 2 | Pedido registrado. | Buscar y seleccionar el medicamento solicitado. | Auxiliar de farmacia. | Medicamento seleccionado y listo para el conteo. |
| 3 | Medicamento seleccionado y cantidad solicitada. | Ingresar la cantidad en el sistema y activar el contador robótico 3D. | Auxiliar de farmacia. | Contador configurado con la cantidad objetivo. |
| 4 | Medicamento y cantidad objetivo ingresada. | El contador robótico cuenta y dispensa las pastillas automáticamente; el auxiliar verifica el resultado. | Contador robótico 3D y auxiliar de farmacia. | Cantidad dispensada y resultado de verificación; si no coincide, se ajusta y se repite el conteo. |
| 5 | Dosis verificada y cantidad correcta. | Empacar las pastillas y entregar la dosis al cliente. | Auxiliar de farmacia. | Dosis entregada y cliente atendido. |

## Antes y después

| Proceso actual | Proceso con la solución |
|---|---|
| El auxiliar recibe el pedido y selecciona el medicamento. | El auxiliar recibe el pedido, registra el medicamento y la cantidad solicitada. |
| Cuenta las pastillas manualmente frente al cliente. | Ingresa la cantidad y activa el contador robótico 3D. |
| Si se equivoca, debe volver a contar manualmente. | El sistema realiza el conteo automático y permite repetirlo si la cantidad no coincide. |
| Empaca y entrega la dosis después del conteo manual. | El auxiliar verifica la cantidad, empaca y entrega la dosis exacta. |
| El proceso puede tardar más y presentar errores de conteo. | Se reducen los tiempos de atención y la posibilidad de errores en el conteo. |

