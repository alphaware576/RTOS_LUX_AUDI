
# Retroalimentacion para GHOU Totems Audio|Luz

Proyecto de Retroalimentacion audible y de luz que engloba en una sola placa y potenciado por RTOS el costo y uso de hardware para el proyecto Totems GHOU.


## Deployment

To deploy this project run

```bash
 - Cortar pines fisicos de la shield sfemp3 en D11, D12, D13 
 - Hacer un puente entre los pines D11 -> D51 ,D12 -> 50 ,D13 -> 52 fisicos de la shield hacia los pines fisicos del Arduino MEGA 2560
 - Pin de datos I2C LED D22
```

