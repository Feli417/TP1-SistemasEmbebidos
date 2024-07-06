# TP1-SistemasEmbebidos
Sistema de riego automático.

Se reemplazó el sensor de Temperatura y Humedad, por un LM35 (temp) y sensor de humedad arduino, debido a que requería comunicación. Sensor de humedad = https://articulo.mercadolibre.com.ar/MLA-705913501-modulo-sensor-de-humedad-de-suelo-tierra-arduino-nubbeo-_JM#is_advertising=true&position=2&search_layout=grid&type=pad&tracking_id=051d295c-9d2f-4e65-b1ce-17e0fe4e8b8b&is_advertising=true&ad_domain=VQCATCORE_LST&ad_position=2&ad_click_id=YmMzN2FkMzQtNDAwNC00YzcyLWExOGItMTMwOTA3NGU3MmE2.

La bomba se quemó por lo que se omite en el TP, pero se debe activar una salida digital que está conectada a un relay, que a su vez permite que se alimente la bomba con 12V.
La fuente de 12V es una fuente de alimentación de celular motorola con un stepDown.

**Plataforma de desarrollo**: _NÚCLEO-L476RG_.

**Periféricos utilizados**:

- DigitalIN: Sensor de humedad

- AnalogIN: LDR y LM35 (temperatura)

- DigitalOUT: LED2 y Bomba
