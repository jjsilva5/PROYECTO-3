# PROYECTO-3


Integrantes:

Pamela Montatixe

Joaquin Silva

Mauricio taco

1. OBJETIVOS

1.1 Objetivo General:

- Analizar el funcionamiento del alambrado publico, mediante la creacion de un circuito en protoboard.

1.2 Objetivos especificos:

- Analizar el funcionamiento de los componentes del circuito.
- Asemejar la distincion de luz con la del alambrado publico.
- Recrear un circuito capaz de detectar la variacion de luz en el entorno.
- Determinar la polaridad de los diferentes elementos utilizados.

2.MARCO TEÓRICO

Circuito Integrado U741

El circuito integrado U741 es un amplificador operacional de alta ganancia y ancho de banda. Fue introducido por primera vez en 1968 por Fairchild Semiconductor y es uno de los amplificadores operacionales más antiguos. El U741 es un dispositivo de ocho pines que tiene dos entradas y una salida. Es un amplificador diferencial que amplifica la diferencia entre las dos entradas, con una ganancia alta y estable en una amplia gama de frecuencias. El U741 se utiliza en aplicaciones que requieren una alta precisión, como en la instrumentación de medición y control. También se utiliza en circuitos de retroalimentación, filtros activos, osciladores y amplificadores de instrumentación.

El U741 está diseñado para funcionar con una fuente de alimentación simétrica (+Vcc y -Vcc). La tensión de alimentación típica es de ±15V, pero puede funcionar con una tensión de hasta ±22V. El U741 es un dispositivo bipolar de un solo polo, lo que significa que sólo puede amplificar las señales de voltaje que varían en la misma dirección que la fuente de alimentación. El U741 tiene un ancho de banda típico de 1 MHz y una ganancia típica de 200,000. Es capaz de manejar una corriente de salida de ±25mA.

Relé

El relé es un dispositivo electromecánico que permite controlar el flujo de corriente eléctrica en un circuito mediante un interruptor accionado por un electroimán. El relé se compone de dos partes principales: una bobina y unos contactos. Cuando se aplica una corriente a la bobina, esta genera un campo magnético que atrae una armadura, que a su vez, cierra o abre los contactos del relé. El relé es capaz de activar y desactivar circuitos de alta potencia mediante una señal de entrada de baja potencia, lo que lo hace muy útil en aplicaciones de automatización y control.

Existen varios tipos de relés, entre ellos, el relé de contactos normalmente abiertos (NO), normalmente cerrados (NC) y los relés de cambio. El relé NO se encuentra en reposo abierto, y al aplicar una corriente a la bobina, los contactos se cierran. El relé NC se encuentra en reposo cerrado, y al aplicar una corriente a la bobina, los contactos se abren. El relé de cambio, como su nombre indica, puede cambiar entre los modos NO y NC.

El relé se utiliza en una amplia variedad de aplicaciones, como el control de motores, la iluminación, el control de la temperatura, la automatización y el control de procesos industriales. También se utiliza en aplicaciones de seguridad, como en sistemas de alarma y protección de sobrecarga.

TIP120

El TIP120 es un transistor bipolar de potencia NPN, capaz de manejar altas corrientes y voltajes. Es utilizado en aplicaciones donde se requiere amplificar o controlar la corriente. El TIP120 es un dispositivo de tres pines que consta de una base, un colector y un emisor. La corriente fluye desde el colector hasta el emisor cuando se aplica una corriente a la base.

3.EXPLICACIÓN DEL PROCEDIMIENTO

Materiales:

- 1 fotoresistencia

- 1 potenciometro de 10kohm

- 2 resistencias de 10kohms

- Un circuito integrado UA741

- TIP 120

- Relay

Para simular las luces de encendido de la calle con un TIP120, un relé, un foco de 110V, un LDR y un potenciómetro, puedes seguir los siguientes pasos:

Materiales necesarios:

TIP120 (transistor Darlington)
Relé de 5V
Diodo de protección (1N4001 o similar)
Resistencia de 1k ohmios
Fuente de alimentación de 5V
Foco de 110V
LDR (resistencia dependiente de la luz)
Potenciómetro de 10k ohmios
Cableado y protoboard

![image](https://user-images.githubusercontent.com/117045943/222012108-05319884-09a1-4626-a503-5ffaf78de61c.png)}

![image](https://user-images.githubusercontent.com/117045943/222012350-966a01b4-62b2-4ff1-a797-7157a2bdb0e8.png)

![image](https://user-images.githubusercontent.com/117045943/222012364-9f413880-973b-4975-961f-649e529b09d7.png)

Pasos:

Conecta el TIP120 en la protoboard, asegurándote de que la base, el colector y el emisor estén separados. Conecta el diodo de protección en paralelo con la bobina del relé (los terminales del relé son los de bobina y los de contacto).

Conecta una resistencia de 1k ohmios en serie con la base del TIP120.

Conecta la fuente de alimentación de 5V al relé y al TIP120 (el relé se alimentará de 5V, mientras que el TIP120 se alimentará de 5V a través de la resistencia de 1k ohmios).

Conecta el foco de 110V a los terminales de contacto del relé.

Conecta el LDR en serie con el potenciómetro y una resistencia de 1k ohmios en la protoboard. Asegúrate de que el potenciómetro y la resistencia de 1k ohmios estén conectados en serie con el LDR.

Conecta el potenciómetro al circuito, conectando un extremo al positivo de la fuente de alimentación de 5V y el otro extremo a la resistencia de 1k ohmios que está en serie con el LDR.

Conecta el otro extremo de la resistencia de 1k ohmios que está en serie con el LDR al negativo de la fuente de alimentación de 5V.

Conecta el LDR al TIP120, conectando un extremo al colector y el otro extremo a la resistencia de 1k ohmios que está en serie con la base del TIP120.

Simula la activación de las luces de la calle variando la luz que recibe el LDR a través del potenciómetro. Esto cambiará la resistencia del LDR, lo que a su vez cambiará la tensión en la base del TIP120, y encenderá o apagará el relé y el foco de 110V.

Es importante destacar que trabajar con corriente de línea de 110VAC es peligroso y se deben tomar medidas de seguridad adecuadas para evitar descargas eléctricas. Si se desea implementar este circuito en una aplicación real, es necesario tomar en cuenta muchos otros factores, como la carga que manejará el relé, la protección contra sobrecargas, entre otros. Se recomienda buscar asesoramiento profesional antes de realizar cualquier proyecto eléctrico o electrónico.

4.VIDEO

https://youtu.be/7BQvvKdDEUA

5.CONCLUSIONES

El TIP120 es un transistor de potencia Darlington NPN diseñado para manejar cargas de alta corriente y alta tensión. Es un componente comúnmente utilizado en circuitos electrónicos para controlar motores, solenoides, lámparas, y otros dispositivos de alta potencia.

El TIP120 tiene tres pines: la base, el colector y el emisor. La corriente fluye desde la base hacia el colector y luego hacia el emisor. Debido a que es un transistor Darlington, tiene una ganancia de corriente muy alta, lo que significa que una pequeña corriente en la base puede controlar una corriente mucho mayor en el colector.

Es importante tener en cuenta que el TIP120 es un transistor de tipo "saturación", lo que significa que cuando está completamente encendido, tiene una caída de voltaje relativamente alta entre el colector y el emisor. Por lo tanto, se recomienda utilizarlo con cargas que no sean sensibles a pequeñas variaciones de voltaje.

6.BIBLIOGRAFÍA

Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education

Anonimo (2022). Fotocelda. Definición.xyz
