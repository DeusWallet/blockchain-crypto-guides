# Zcash explicado de forma sencilla

Zcash es una criptomoneda similar a [Bitcoin](bitcoin.md), pero se centra en gran medida en la privacidad y utiliza algunas de las criptografías más avanzadas de la industria.

Esta guía explica qué hace que Zcash sea único, cómo usarlo y por qué está creciendo.

## 1. Orígenes de Zcash

Zcash se originó a partir de una propuesta experimental de un grupo de científicos y matemáticos con el objetivo de abordar la falta de privacidad de Bitcoin.

Lanzado el 28 de octubre de 2016 por [Electric Coin Co](https://electriccoin.co), Zcash fue la primera criptomoneda en utilizar [zk-SNARKs](https://www.investopedia.com/terms/z/ zksnark.asp), también conocida como pruebas de conocimiento cero.

> En términos simples, un zk-SNARK permite a una de las partes demostrar que posee cierta información sin revelar la información real.

Esto permite que la cadena de bloques Zcash verifique la validez de las transacciones (por ejemplo, confirmando que el gastador tiene fondos suficientes) sin exponer datos privados sobre las entidades involucradas.

Por el contrario, cada transacción de Bitcoin revela cierta información sobre el saldo del remitente y las transacciones pasadas/futuras.

## 2. Zcash frente a Bitcoin

En comparación con [Bitcoin](bitcoin.md) o [Ethereum](ethereum.md), Zcash ofrece mayor privacidad y permite transacciones totalmente confidenciales.

Los usuarios de Zcash pueden optar por enviar transacciones privadas según el contexto y la situación.

Aparte de la privacidad, Zcash es una bifurcación de Bitcoin y comparte muchas propiedades fundamentales, como un suministro limitado de 21 millones de tokens ZEC.

> Al igual que Bitcoin, las transacciones de Zcash son públicamente visibles en una cadena de bloques.
>
> Sin embargo, los usuarios de Zcash pueden optar por realizar transacciones de forma pública o privada. Las transacciones privadas no revelan ninguna información sobre las partes involucradas o el monto transferido.
>
> Los nodos de Zcash pueden validar transacciones privadas sin conocer los detalles de la transacción.

Para cumplimiento o auditorías (donde se requiere transparencia), Zcash ofrece una función de pago selectivo. Las [divulgaciones selectivas](https://www.zfnd.org/zcon/0/workshop-notes/selective-disclosure-workshop/) permiten a los usuarios compartir detalles de transacciones específicas manteniendo la privacidad del resto de la información.

Aspectos destacados de Zcash:

- El símbolo de Zcash es 'ZEC'. Una sola ZEC consta de 100 millones de subunidades llamadas zatoshis, similares a los satoshis de Bitcoin.
- Mientras que la cadena de bloques de Bitcoin tarda unos 10 minutos en procesar un bloque, Zcash procesa los bloques aproximadamente cada 75 segundos.
- Cada bloque procesado recompensa a los mineros con ZEC recién creado. A partir de noviembre de 2020, la recompensa en bloque es de 3,125 ZEC.
- Al igual que Bitcoin, la recompensa en bloque se reduce a la mitad aproximadamente cada cuatro años hasta que los 21 millones de ZEC estén en circulación.

## 3. Privacidad de Zcash

Zcash tiene dos tipos de direcciones: transparentes y blindadas.

- Las direcciones transparentes comienzan con "t" y se comportan como direcciones de Bitcoin, exponiendo el remitente, el destinatario y el monto de la transacción en la cadena de bloques.
- Las direcciones blindadas comienzan con "z" y ofrecen mayor confidencialidad.

Estas direcciones son interoperables, lo que permite a los usuarios enviar y recibir fondos entre diferentes tipos de direcciones.

Hay cuatro tipos de transacciones de Zcash:

- Totalmente blindado (z-a-z)
- Parcialmente blindado (z-to-t)
- Parcialmente blindado (t-to-z)
- Totalmente transparente (t-to-t)

Las transacciones totalmente protegidas cifran el remitente, el destinatario y el monto, lo que garantiza una privacidad total. Estas transacciones no se pueden rastrear a menos que el remitente o el destinatario revelen información.

Las transacciones totalmente transparentes son similares a las transacciones de Bitcoin, con direcciones visibles y montos de transacción en una cadena de bloques pública.

## 4. Ecosistema Zcash

Como todas las principales cadenas de bloques de criptomonedas, Zcash es de código abierto, lo que permite a cualquiera explorar su funcionamiento y reutilizar su código base.

Zcash ha creado una comunidad de contribuyentes, incluidos criptógrafos, activistas y luchadores por la libertad de talla mundial, debido a su enfoque en la privacidad.

> Cualquier proyecto global de criptomonedas que apunte a la supervivencia a largo plazo necesita una comunidad descentralizada dispuesta a continuar su desarrollo independientemente de otras entidades.

Si bien cualquiera puede contribuir a Zcash, las principales entidades que impulsan su crecimiento incluyen:

- **Compañía de monedas eléctricas (ECC)**

 ECC creó Zcash y respalda su desarrollo continuo a través de I+D, ingeniería, desarrollo empresarial y compromiso regulatorio. Fue el primer proyecto en implementar pruebas de conocimiento cero.

 Sitio web: [Electric Coin Co](https://electriccoin.co)

- **Fundación Zcash**

 Una entidad sin fines de lucro que mantiene y mejora el protocolo Zcash para todos los usuarios. Inicialmente financiado con donaciones de las partes interesadas de Zcash, ahora recibe financiación del Fondo de Desarrollo Comunitario.

 Sitio web: [https://www.zfnd.org](https://www.zfnd.org)

- **Comité de revisión de subvenciones principales (MGRC)**

 Iniciado como parte de la actualización de la red Canopy, MGRC ofrece importantes subvenciones a desarrolladores independientes para descentralizar aún más los esfuerzos de Zcash.

 Lea más sobre [MGRC](https://electriccoin.co/blog/ecc-welcomes-the-major-grants-review-committee/).

Estas entidades son fundamentales para el crecimiento, la expansión y el mayor descentramiento de Zcash. alización. Zcash se autofinancia con una sólida gobernanza comunitaria que alinea los incentivos de las partes interesadas clave.

- Desde el 28 de octubre de 2016 hasta el 18 de noviembre de 2020, el 10% de todas las monedas recién emitidas se destinó a la "Recompensa de los Fundadores".
- Después del 18 de noviembre, alrededor del 20% de todos los ZEC recién emitidos (aproximadamente 0,6 ZEC cada 75 segundos) se distribuye al Fondo de Desarrollo Comunitario, poniendo fin a la Recompensa de los Fundadores.

El Fondo de Desarrollo Comunitario apoya a los nuevos participantes para mejorar, desarrollar, ampliar y apoyar a Zcash.

## 5. Por qué Zcash está creciendo

Un problema importante con las criptomonedas existentes es la falta de privacidad. A pesar de la creencia popular, la mayoría de las criptomonedas ofrecen poca o ninguna privacidad.

A excepción de Zcash y algunas otras, la mayoría de las criptomonedas carecen de privacidad, lo que las hace inadecuadas para transacciones privadas.

Bitcoin, Ethereum y otras criptomonedas importantes no han abordado con éxito los problemas de privacidad, a menudo citados como su punto más débil.

La privacidad se ha vuelto aún más relevante a medida que los gigantes tecnológicos rastrean la actividad en Internet y los bancos centrales presionan por monedas exclusivamente digitales.

Los usuarios de criptomonedas preocupados por la privacidad y los primeros en adoptarlas necesitan monedas de privacidad, y Zcash es uno de los pocos que puede proporcionarlas.

Sus sólidos fundamentos y el respaldo de algunas de las mentes más brillantes en el espacio de las criptomonedas atraen a muchos a Zcash.

## 6. Desafíos de Zcash

Como la mayoría de las criptomonedas, Zcash enfrenta desafíos que podrían obstaculizar su crecimiento.

- **Configuración confiable**

 La tecnología de privacidad de Zcash se basa en una "configuración confiable" para formar parámetros iniciales para transacciones privadas. Si bien existen salvaguardias, los críticos sugieren que los fundadores podrían usar este sistema para crear tokens Zcash ilimitados. El equipo de investigación de Zcash está trabajando en [Halo](https://electriccoin.co/blog/explaining-halo-2/), lo que podría eliminar la necesidad de una configuración confiable.

- **Adopción blindada**

 El porcentaje de transacciones protegidas en la red Zcash es bajo en comparación con el uso total. Sin embargo, Zcash está avanzando hacia una mayor adopción protegida, incluido el apoyo de los principales intercambios.

- **Velocidad de la cadena de bloques**

 Si bien Zcash puede procesar más transacciones que Bitcoin, todavía está limitado a aproximadamente 20 transacciones por segundo. Esto no es un problema por ahora, ya que la actividad actual está por debajo del límite.

- **Competencia**

 Las criptomonedas competidoras como DASH y Monero también se centran en la privacidad. Si bien Monero tiene actualmente la capitalización de mercado más alta, queda por ver cuál atraerá a la mayor cantidad de usuarios a largo plazo.

Desde la perspectiva del usuario, esperamos que Zcash continúe creciendo y se convierta en la moneda de privacidad preferida para quienes buscan cumplimiento y privacidad bajo demanda.