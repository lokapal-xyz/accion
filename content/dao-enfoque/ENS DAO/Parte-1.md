---
date: '2025-03-09T16:43:23-03:00'
draft: false
title: 'Parte 1 – La Estructura Principal de ENS DAO'
---

## Fundamentos de ENS DAO

Para quienes deseen explorar ENS DAO a fondo, el sitio web [**ENS DAO Basics**](https://basics.ensdao.org/) es un excelente recurso oficial. Aquí les ofrecemos una visión general resumida para brindarles un punto de partida claro y accesible.

Comencemos con un breve resumen de los aspectos principales de ENS:

- ENS significa **"Ethereum Name Service"** (traducción: **"Servicio de Nombres de Ethereum"**).
- Es un protocolo de nombres descentralizado.
- Funciona en la blockchain de Ethereum.
- Los nombres de dominio de ENS son legibles para humanos (por ejemplo, **vitalik.eth**).
- Se puede vincular la dirección de una billetera a un dominio de ENS.
- Se puede integrar nombres de dominio DNS regulares con nombres .eth.

A continuación, se presentan algunos datos clave sobre la gobernanza y la organización de ENS:

- ENS fue fundada en 2017 por Nick Johnson.
- A fecha de 2025, se han registrado más de 3,5 millones de nombres .eth.
- ENS está gobernado por la ENS DAO. 
- La DAO está representada en el mundo real por la Fundación ENS.

Los nombres ENS son **legibles para humanos**, lo que mejora la usabilidad de la cuenta. En lugar de trabajar con una dirección hexadecimal larga, los usuarios pueden compartir su nombre ENS (por ejemplo, satoshi.eth), lo que evita errores de uso. ENS ya tiene muchas aplicaciones, pero su potencial está lejos de agotarse. A medida que aumenta la adopción por parte de los usuarios y de las instituciones, podrían surgir nuevas opciones de uso.

---

## Token ENS

El token $ENS es un token de gobernanza que se utiliza para gestionar componentes clave del protocolo ENS. Estos son algunos de sus aspectos clave:

- El token $ENS se lanzó el 8 de noviembre de 2021, junto con la ENS DAO.
- $ENS es un token ERC-20 en la blockchain de Ethereum.
- Los titulares de $ENS pueden delegar tokens a los **delegados**.
- Los delegados utilizan esta delegación para presentar y votar propuestas.
- Las propuestas pueden implementar cambios en el protocolo ENS y gastos de la tesorería de la DAO.
- Originalmente, se acuñaron un total de 100 millones de tokens $ENS.
- Cada token representa un voto en la DAO.
- Los tokens $ENS se pueden comprar en plataformas de intercambio centralizadas y descentralizadas.

Esta fue la distribución inicial de $ENS:

- El 25 % (25 millones de $ENS) fue destinado a los principales contribuyentes, socios del ecosistema y miembros de la comunidad. 
- El 25% (25 millones de $ENS) estuvieron a disposición de las direcciones poseídas previamente mediante airdrops.
- El 50% (50 millones de $ENS) se destinó a la tesorería de la DAO, con un calendario de liberación establecido.

La DAO puede acuñar más tokens una vez al año, según una regla de "2% como máximo". Si la DAO aprueba una propuesta para aumentar su suministro total, deberá esperar al menos 365 días para su siguiente ventana de acuñación.

---

## Contratos de ENS DAO

Estos son los contratos más relevantes de la ENS DAO:

- [**wallet.ensdao.eth**](https://etherscan.io/address/0xfe89cc7abb2c4183683ab71653c4cdc9b02d44b7): la tesorería de ENS DAO.
- [**token.ensdao.eth**](https://etherscan.io/address/0xc18360217d8f7ab5e7c516566761ea12ce7f9d72): el contrato del token $ENS. 
- [**governor.ensdao.eth**](https://etherscan.io/address/0x323a76393544d5ecca80cd6ef2a560c6a395b7e3): el contrato de gestión de propuestas.
- [**tokenlock.ensdao.eth**](https://etherscan.io/address/0xd7a029db2585553978190db5e85ec724aa4df23f): el contrato de bloqueo de tokens. Este contrato retenía originalmente el 45 % del suministro total de $ENS, liberándolos durante un periodo de 4 años.

---

## Registro ENS y Ingresos del Protocolo

El protocolo ENS genera ingresos mediante el registro de nombres ENS **".eth"**. A continuación, se presentan algunos aspectos clave:

- Los nombres .eth pueden registrarse en app.ens.domains y otras plataformas externas de registro.
- Los ingresos por registro se destinan a contratos inteligentes controlados por la ENS DAO.
- El precio de registro de un nombre .eth varía según la longitud de caracteres (menos caracteres = precios más altos).
- Los nombres pueden registrarse por cualquier período futuro.
- Una vez que los nombres expiran, los registrantes tienen un período de gracia de 90 días para extender el registro de nombres ENS.
- Una vez expirado el período de gracia, el nombre entra en una subasta premium temporal durante 21 días.
- Al finalizar los 21 días, el nombre está disponible para registrarse con la tarifa de registro normal.

---

## Fundación ENS

La Fundación ENS es una fundación constituida en las Islas Caimán que representa a la ENS DAO en el mundo real:

- La Fundación ENS es una organización sin fines de lucro, sin accionistas.
- La Fundación ENS tiene tres directores: [**Nick Johnson**](https://twitter.com/nicksdjohnson), [**Kevin Gaspar**](https://twitter.com/ValidatorEth) y [**Alex Van de Sande**](https://twitter.com/avsa).
- Los directores se encargan de la gestión diaria de la fundación.
- La Fundación ENS cuenta con un supervisor, encargado de monitorear el desempeño de los directores.
- Los directores gestionan los gastos operativos, que posteriormente son reembolsados ​​por la DAO.
- La ENS DAO (conocida internamente como "The Council") tiene el control administrativo de la Fundación.
- La DAO puede instruir a los directores para que actúen en nombre de la Fundación.

---

## Constitución de la ENS DAO

Los objetivos e intenciones de la ENS DAO se establecen en su Constitución. Esta Constitución contiene cinco artículos:

- *Artículo 1* – No se infringirá la propiedad del nombre
- *Artículo 2* – Las tarifas son principalmente un mecanismo de incentivos
- *Artículo 3* – Los ingresos financian la ENS y otros bienes públicos
- *Artículo 4* – La ENS se integra con el espacio de nombres global
- *Artículo 5* – Las enmiendas a esta Constitución se logran por mayoría de votos

La Constitución completa de la ENS DAO está disponible [**aquí**](https://ensdao.eth.limo/constitution.pdf).

---

## Fondo patrimonial de ENS

El objetivo del Fondo Patrimonial es garantizar la viabilidad a largo plazo de ENS, asegurándose de que pueda cumplir con sus obligaciones financieras continuas a pesar de la volatilidad interna y externa. El objetivo es reservar una cantidad sustancial de la tesorería de la DAO y de los ingresos provenientes de las cuotas de registro.

Para lograr este objetivo, la DAO deberá diversificar e invertir su tesorería y las futuras cuotas de registro para crear una fuente de financiación sostenible. Esto permitirá a la DAO continuar operando y financiar el desarrollo continuo de ENS, independientemente de las condiciones del mercado.

- El gestor del fondo patrimonial es [**Karpatkey**](https://twitter.com/karpatkey).
- El Fondo Patrimonial se inició el 7 de marzo de 2023.
- Se financió con un depósito inicial de 16.000 ETH.
- La billetera del fondo patrimonial está controlada por la DAO y gestionada por Karpatkey.

---

## Consejo de Seguridad de la ENS DAO

En caso de que una propuesta amenace a la ENS DAO, un Consejo de Seguridad designado puede intervenir. El consejo no puede presentar propuestas ni modificarlas. Una multi-sig Safe 4-de-8 está autorizada a actuar exclusivamente en emergencias como:

- Ataques a la tesorería de la DAO.
- Ataques de gobernanza debido a una baja participación electoral.
- Propuestas que no se ajusten a la Constitución de la ENS, ya sea intencionalmente o no.

---

En el próximo artículo, exploraremos los mecanismos de votación de la ENS DAO, la creación de propuestas, los grupos de trabajo y más.