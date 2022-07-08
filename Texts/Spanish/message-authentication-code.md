---
keywords: Personal Finance,Banking
title: Código de autenticación de mensajes (MAC)
description: Un código de autenticación de mensajes (MAC), o etiqueta, es un código de seguridad que ingresa el usuario de una computadora para acceder a cuentas o portales.
---

# Código de autenticación de mensajes (MAC)
## ¿Qué es un código de autenticación de mensajes?

Un código de autenticación de mensajes (MAC), o **etiqueta,** es un código de seguridad que ingresa el usuario de una computadora para acceder a cuentas o portales. Este código se adjunta al mensaje o solicitud enviada por el usuario. Los códigos de autenticación de mensajes (MAC) adjuntos al mensaje deben ser reconocidos por el sistema receptor para otorgar acceso al usuario.

## Comprender el código de autenticación de mensajes (MAC)

Los códigos de autenticación de mensajes (MAC) se usan comúnmente en [las transferencias electrónicas de fondos](/electronic-funds-transfer-act) (EFT) para mantener la integridad de la información. Confirman que un mensaje es auténtico; que realmente viene, es decir, del remitente declarado, y que no ha sufrido ningún cambio en el camino. Un verificador que también posea la clave puede usarla para identificar cambios en el contenido del mensaje en cuestión.

Los códigos de autenticación de mensajes generalmente se requieren para acceder a cualquier tipo de cuenta financiera. Los bancos, las casas de bolsa, las compañías fiduciarias y cualquier otra compañía de depósitos, inversiones o seguros que ofrezca acceso en línea pueden emplear estos códigos. Son un componente vital de la criptografía financiera.

## Algoritmos utilizados para generar MAC

Tres algoritmos típicamente comprenden un MAC: un algoritmo de generación de claves, un algoritmo de firma y un algoritmo de verificación. El algoritmo de generación de claves elige una clave al azar. El algoritmo de firma envía una etiqueta cuando se le da la clave y el mensaje. El algoritmo de verificación se utiliza para verificar la autenticidad del mensaje cuando se le proporciona la clave y la etiqueta; devolverá un mensaje de **aceptado** si el mensaje y la etiqueta son auténticos e inalterados, pero de lo contrario, devolverá un mensaje de **rechazado.**

Por ejemplo, el remitente envía un mensaje, como un EFT, a través del algoritmo MAC, que genera una clave y adjunta una etiqueta de datos MAC al mensaje. El destinatario recibe el mensaje, lo vuelve a ejecutar a través del algoritmo MAC con la misma clave y obtiene una segunda etiqueta de datos. Luego compararán esta etiqueta de datos MAC con la primera adjunta al mensaje cuando se transmitió. Si el código es el mismo en ambos extremos, el destinatario puede asumir con seguridad que la integridad de los datos del mensaje está intacta. Sin embargo, si no, significa que el mensaje fue alterado, manipulado o falsificado.

Sin embargo, el mensaje en sí debe contener algunos datos que garanticen que este mensaje solo se puede enviar una vez. Por ejemplo, se podría usar una MAC, una marca de tiempo o un número de secuencia de una sola vez para garantizar que el mensaje solo se pueda enviar una vez. De lo contrario, el sistema podría ser vulnerable a un ataque de repetición, en el que un atacante intercepta el mensaje después de haberlo decodificado y lo retransmite más tarde, replicando los resultados originales e infiltrándose en el sistema.

## Códigos de integridad de mensajes (MIC)

A veces, se utilizará el término código de integridad del mensaje (MIC) en lugar de MAC. Esto se hace con mayor frecuencia en la industria de las comunicaciones, donde MAC tradicionalmente significa dirección de control de acceso a medios (dirección MAC). Sin embargo, MIC también se puede usar para referirse a **resumen de mensajes**, que no usa claves secretas de la misma manera que MAC y no puede ofrecer el mismo nivel de seguridad sin cifrado adicional.

