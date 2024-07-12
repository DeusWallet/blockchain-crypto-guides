# Transacciones DeFi

Realizar transacciones en plataformas DeFi implica consideraciones y complejidades únicas. Aquí hay algunos puntos clave para entender:

- **Complejidad de los pasos**: las transacciones DeFi pueden implicar numerosos pasos con lógica condicional.
- **Tarifas de procesamiento más altas**: las transacciones más complejas suelen generar tarifas más altas.
- **Privacidad**: las transacciones DeFi son tan privadas como la cadena de bloques Ethereum en la que se basan.

## Complejidad de la transacción

Las transacciones DeFi pueden ser extremadamente complejas y a menudo se las denomina dinero programable. A continuación se muestra un ejemplo de una transacción compleja que involucra varios pasos:

1. Solicite un préstamo rápido de ETH.
2. Envíe el ETH prestado a DEX1.
3. Convierta ETH a USDT en DEX1.
4. Envíe USDT a DEX2.
5. Convierta USDT a USDC en DEX2.
6. Envíe USDC a DEX3.
7. Convierta USDC a ETH en DEX3.
8. Devolver el préstamo ETH (conservando las ganancias).

Los contratos inteligentes de DeFi son interoperables, lo que permite conectar múltiples servicios DeFi mediante programación, de forma similar a construir con bloques de Lego. Si bien dichas transacciones actualmente están limitadas a aquellos con un profundo conocimiento del ecosistema y algunas habilidades de programación, cualquiera puede comenzar a experimentar con criptomonedas personales o préstamos flash.

Para ver un ejemplo de la vida real, consulte [esta publicación](https://www.coindesk.com/first-mover-how-a-defi-trader-made-an-89-profit-in- Minutes-slinging- stablecoins) que detalla una transacción en la que alguien ganó aproximadamente $40,000 en minutos utilizando múltiples servicios DeFi.

## Tarifas de transacción

Las transacciones simples de Ethereum, como enviar Ethereum o tokens de una dirección a otra, generalmente son menos costosas que las transacciones complejas de DeFi, que implican tarifas de procesamiento más altas.

> Las transacciones de Ethereum DeFi suelen ser más complejas y, por lo tanto, requieren tarifas de procesamiento más altas que las transferencias de tokens estándar.

Este problema de altas tarifas podría mitigarse a medida que la cadena de bloques Ethereum expanda su capacidad o cuando los servicios DeFi migren a cadenas de bloques más rápidas como Solana, Avalanche o Algorand. Hasta entonces, es probable que los costos de transacción de DeFi sigan aumentando, especialmente a medida que el ecosistema atrae a más usuarios.

## Tarifas del servicio DeFi

La mayoría de los servicios DeFi cobran pequeñas tarifas, aunque es posible que algunos no. Por ejemplo, los intercambios descentralizados (DEX) cobran a los comerciantes una pequeña tarifa de servicio por cada operación. En consecuencia, los comerciantes suelen pagar:

- Una tarifa de servicio (por ejemplo, 0,02% - 0,04%) para el contrato inteligente DEX.
- Una tarifa de transacción para los nodos de la red Ethereum.

De manera similar, los servicios de préstamo como Aave o Compound cobran tarifas por prestar criptomonedas, además de las tarifas de transacción de blockchain.

## Transacciones de aprobación

Un aspecto importante de las transacciones DeFi son las transacciones de aprobación. Al interactuar con un contrato inteligente, los usuarios a menudo necesitan otorgar permiso al contrato para acceder a sus fondos.

> Otorgar permiso implica una 'transacción de aprobación', que no transfiere fondos pero permite que el contrato inteligente gaste una cantidad específica de los tokens del usuario.

La mayoría de los servicios DeFi requieren una transacción de aprobación antes de que los usuarios puedan utilizar el servicio.

## Privacidad de DeFi

Dado que la mayoría de los proyectos DeFi se basan en la cadena de bloques Ethereum, la privacidad de DeFi está ligada al modelo de privacidad de Ethereum. Todas las transacciones DeFi exponen su dirección Ethereum, lo que permite a cualquiera ver el historial completo de transacciones y los saldos de tokens asociados con esa dirección. Si bien esto no se vincula directamente con su identidad, sí revela su actividad en blockchain.

Para mejorar la privacidad, considere usar múltiples billeteras Ethereum:

- **Monedero de almacenamiento de activos**: utilice este monedero para almacenar de forma segura tokens y activos de Ethereum. Evite usarlo para transacciones con otras entidades para mantener sus saldos privados.
- **Monedero de pagos genérico**: configure un monedero separado para las transacciones diarias.
- **Monedero de transacciones DeFi**: considere crear otro monedero específicamente para transacciones DeFi. Al igual que la billetera de almacenamiento, evite usarla para transacciones con entidades conocidas para mantener la privacidad.