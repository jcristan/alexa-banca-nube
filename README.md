# alexa-banca-nube

## DESCRIPCIÓN GENERAL DEL DEMO

Alexa es el servicio de voz desplegado en la nube de Amazon, disponible en los dispositivos de Amazon (Echo, Echo Dot, Echo Show, entre otros), y en dispositivos de terceros autorizados por Alexa. Con Alexa, puedes crear experiencias de voz naturales para ofrecer a los usuarios  una forma más intuitiva de interactuar con la tecnología que usan a diario. 

El Skill de Banca Nube permite pedirle a Alexa que interactue con canal virtual bancario adicional, este skill te permite  hacer diferentes consultas y transacciones por medio de la voz,inicialmente tenemos cuatro funcionalidades principales que podemos utilizar:

1. *Consulta de Saldo*, Conocer el saldo actual de mi cuenta de ahorros
2. *Consulta de tarjeta de crédito*: Conocer cuanto debo pagar en mi tarjeta de crédito, mi cupo disponible y mi próxima fecha de pago
3. *Solicitud de Avance*: Esta funcionalidad me permite solicitar un valor de avance de mi tarjeta de crédito, para que el mismo sea abonado a mi cuenta de ahorros.
4. *Pago de tarjeta de Crédito*: Esta funcionalidad me permite pagar el valor deseado de mi tarjeta de crédito, el cual debe ser debitado de mi cuenta de ahorros. 


El demo adicionalmente esta compuesto de una interfaz web, que permite validar los valores y cambios de tus transacciones en tiempo real, para validar cada una de las operaciones realizadas. Cómo se puede ver en el siguiente diseño de arquitectura.

## Arquitectura de la demo

[Image: image.png]

Comandos de Voz

Cada una de las funciones tiene un modelo de interacción el cual permite interactuar con Alexa

## Inicio del Skill
Para activar o iniciar el Skill de Alexa, es necesario decir: “Alexa, abre Banca Nube”

Si quieres saber sobre Cuenta de ahorros, pregunta: 

  “Alexa, ...:
  * dame el  saldo de mi cuenta de ahorros”
  * cual es el  balance de mi cuenta”
  * cuanto  tengo en mi cuenta de ahorros”

Si quieres hablar de Tarjeta de crédito, pregunta: 

  “Alexa, ...:
  * quiero  pagar tarjeta de crédito”
  * cuanto  tengo de cupo en mi tarjeta de crédito”
  * cual es mi  deuda en mi tarjeta de crédito”
  * qué saldo  tengo disponible en mi tarjeta de crédito”

Cuando quieras conocer de Avances, pregunta: 

  “Alexa,...:
  * necesito  un avance de crédito”
  * quiero  hacer un avance de mi tarjeta”
  * necesito  un avance”



