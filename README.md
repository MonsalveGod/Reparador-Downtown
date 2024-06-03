# Sistema de Reparacion para Downtown MTA

Trata de markets de reparación que solo se activan si no hay mecanicos en servicio (Tienen un comando para ponerse en servicio, bastante vital para que el sistema funcione correctamente) el comando es "/dutym", si hay solo 1 meca en servicio no dejara reparar el vehiculo ni nada.

## Principales Caracteristicas
- Cada reparación le da presupuesto a una faccion determinada por ti en el archivo `config.lua`
- Vehiculos extentos, estos vehiculos pueden ser faccionarios y más para que no se les cobre nada, y igual le dara presupuesto a meca
- Cambiar coste de reparación
- Cooldown para volver a usar el punto
- Tiempo que tiene que esperar cuando entra al punto para que se repare el vehiculo
- Checkpoints configurables donde quieras
- Mensajes por InfoBox
- Sonido a la hora de reparar (Se puede quitar desede el `config.lua`)
