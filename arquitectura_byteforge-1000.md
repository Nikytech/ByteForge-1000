# Arquitectura del Cyberdeck ByteForge 1000

## Circuito 1: Raspberry Pi + pantallas
- Raspberry Pi Zero 2 W con sistema operativo raspi desktop full 32 bit
- Pantalla IPS 7" HDMI 
- Pantalla OLED 1.3" con conexion I2C
- Batería 5V 3A 20,000mAh
- Voltimetro-amperimetro
- Interruptor ON/OFF pantalla IPS 7"
- Interruptor tipo switch de tres posiciones:
  - Pos 0 Sistema apagado
  - Pos I Sistema encendido con voltimetro
  - Pos II Sistema encendido con voltimetro y amperimetro
                                            

## Circuito 2: Sistema de ventilación y sonido
- Batería 5V 2A 3000mAh
- 2 ventiladores (100mA)
- LEDs decorativos
- 2 parlantes 3W con jack y alimentacion USB
- 3 interruptores ON/OFF para alimentacion de ventiladores, luces LEDs y parlantes.


## Circuito 3: Alimentación externa con convertidor DC-DC
- Fuente externa 20V 4.5A
- Convertidor con display de voltaje/corriente/potencia regulada
- Regleta atornillada de 4 pares (+/-) y USB de salida.
  
![Diagrama de conexiones del ByteForge 1000](fotos_cyberdeck/Diagrama_conexiones_ByteForge-1000.png)
