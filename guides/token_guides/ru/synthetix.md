# Синтетикс: простое объяснение

[Synthetix](https://synthetix.io/) — это децентрализованная платформа на Ethereum для торговли синтетическими активами, известными как Synths.

> Синтезы — это токены ERC-20, представляющие криптовалюты, акции, бумажные валюты, драгоценные металлы и другие торгуемые активы.

Эти синтезаторы созданы для отражения цены актива, который они представляют, но без каких-либо других его характеристик.

Например, sBTC — это синтетический токен биткойнов, которым можно торговать на Synthetix по текущей цене биткойнов.

Аналогичным образом, токен sMKR имеет ту же цену, что и реальный токен [MKR](../../token_guides/ru/makerdao.md), но не включает в себя право голоса.

- Владение синтетическими токенами обеспечивает такой же ценовой риск, как и владение реальными токенами, которые они представляют.
- Пользователи могут спекулировать на движении цен различных финансовых инструментов, не владея реальным активом.
- Синтетические активы могут передаваться между пользователями и продаваться на децентрализованных биржах.

Таким образом, Synthetix позволяет создавать токены ERC-20 на базе Ethereum, которые представляют собой реальные активы.

> Любой актив с ценовым потоком потенциально может быть добавлен в Synthetix в качестве синтетического актива.

В настоящее время доступные синтетические активы включают криптовалюты, акции и драгоценные металлы. Synthetix стремится расширить свои предложения, включив в них больше активов, обычно встречающихся на традиционных рынках, таких как акции.

## Поддерживаемые синтезаторы

Платформа Synthetix в настоящее время поддерживает около двух десятков различных синтезаторов, а возможно и больше.

> Любой актив с рыночной ценой может быть добавлен в Synthetix при условии наличия ценового канала и одобрения сообщества.

В настоящее время существует два типа синтетических активов:

1. **Стандартные синтезаторы**

 Они отслеживают цену актива, который они представляют, и подходят для тех, кто хочет открывать длинные позиции по активам.
 - sUSD: синтетический доллар США.
 - sEUR: синтетический евро
 - SAUD: синтетический доллар США.
 - sBTC: синтетический биткойн
 - СЕТ: синтетический эфир
 - sMKR: производитель синтетических материалов
 - sBNB: синтетический BNB
 - sXTZ: синтетический Tezos
 - SADA: синтетический кардано
 - sXRP: синтетическая Ripple
 - sLTC: синтетический Litecoin
 - sBCH: синтетические Bitcoin Cash
 - sXAU: синтетическая золотая унция.
 - sXAG: синтетическая унция серебра.
 - sDEFI: синтетический индекс DEFI.
 sLINK: синтетическое звено цепи.

2. **Инверсные синтезаторы**

 Это позволяет пользователям сокращать цену актива, получая обратную прибыль от снижения цены.
 - iBTC: обратный биткойн
 - iETH: обратный Эфириум
 - iBNB: обратный Binance
 - iXTZ: обратный Тезос
 - iADA: обратный Кардано
 - iXRP: обратная Ripple
 - iLTC: обратный Litecoin
 - iBCH: обратный Bitcoin Cash
 - iDEFI: обратный индекс DEFI
 - iLINK: обратное звено цепи

Синтезы торгуются круглосуточно и без выходных на некастодиальной площадке [Synthetix.Exchange](https://synthetix.exchange), что позволяет любому участнику [экосистемы Ethereum](../../token_guides/ru/ethereum.md) открывать длинные или короткие позиции по различным активам.

## Как создаются синтезаторы

Чтобы понять Synthetix, важно знать, как создаются и изымаются из обращения новые синтезаторы.

1. Synthetix позволяет пользователям создавать токены sUSD (синтетический доллар США) путем [блокировки](https://mintr.synthetix.io/) своих токенов SNX в смарт-контракте с коэффициентом обеспечения 600%.
2. Чтобы создать 1000 токенов sUSD, пользователь должен заблокировать токены SNX на сумму не менее 6000 долларов США. Эти токены возвращаются, когда пользователь погашает заемную сумму.
3. После создания токены sUSD можно будет обменять на бирже Synthetix на другие синтетические активы по текущим рыночным ценам.
4. Ордера на бирже Synthetix являются мгновенными и исполняются по рыночным ценам.
5. Трейдеры всегда торгуют против биржи, которая уничтожает полученный от пользователя актив и создает купленный пользователем актив.
6. Например, покупка sBTC, когда биткойн стоит 10 000 долларов США, предполагает уничтожение 10 000 долларов США и создание 1 sBTC.

Этот процесс гарантирует, что каждый актив синтезатора поддерживается токенами SNX.

Спекулянты также могут приобрести существующие sUSD или sETH на [децентрализованной бирже](../../defi/ru/3-decentralized-exchanges.md), например [Uniswap](../../token_guides/ru/uniswap. md) с использованием ETH.

## Как торгуются синты

Экосистема Synthetix включает в себя собственную децентрализованную биржу [Synthetix.Exchange](https://synthetix.exchange) для торговли синтезаторами.

- В отличие от других децентрализованных бирж, Synthetix.Exchange не требует механизмов сопоставления ликвидности, таких как книги заказов или [пулы ликвидности](../../defi/ru/3-decentralized-exchanges.md).
- Все ордера гарантированно исполняются по рыночным ценам в течение нескольких секунд.
- Торговые сборы варьируются от 0,1% до 1% (обычно 0,3%) и выплачиваются тем, кто создает токены sUSD, блокируя свои токены SNX в качестве залога.

Торговля на Synthetix.Exchange часто обходится дешевле, особенно для крупных заказов, что дает экономический стимул использовать его по сравнению с другими децентрализованными биржами, такими как [Uniswap](../../token_guides/ru/uniswap.md) или [Curve](. ./../token_guides/ru/curve-finance.md).

## Зачем создавать синтезаторы?

Торговля синтезаторами обходится дешевле и обеспечивает доступ к любому торгуемому активу в мире, и все это в блокчейне Ethereum. Это создает строн g стимулы для спекулянтов торговать синтами, а не реальными активами.

Коэффициент обеспечения 600% защищает стабильность синтетических активов от колебаний цен на SNX.

Те, кто привязывает свой SNX к платформе для создания новых синтезаторов, получают два типа вознаграждений:
1. **Награды за ставки SNX**: созданы в результате инфляционной денежно-кредитной политики SNX. В период с марта 2019 года по август 2023 года общий объем поставок SNX увеличится со 100 миллионов до 260,3 миллиона, при этом еженедельная скорость спада составит 1,25%.
2. **Комиссии за обмен**: Комиссии за торговлю синтезаторами на [Synthetix.Exchange](https://synthetix.exchange/#/) поступают в пул комиссий, который стейкеры SNX могут требовать еженедельно.

Стейкеры SNX создают долговую позицию, когда блокируют свои токены. Этот долг начинается с суммы отчеканенных sUSD и изменяется в зависимости от движения цен на все другие синтетические активы.

— Если бы все синтезаторы были sBTC, а цена BTC снизилась бы вдвое, общий долг сократился бы вдвое, и долг каждого стейкера также уменьшился бы вдвое.
- И наоборот, если бы только 50% составляли sBTC, а цена BTC удвоилась, долг каждого участника увеличился бы на одну четверть.

Таким образом, участники стейкинга SNX выступают в качестве объединенного контрагента для всех бирж синтезаторов, неся на себе риск общего долга системы.

## Статистика Синтетикс

Текущую статистику по платформе Synthetix, включая сумму заблокированных средств и количество синтезаторов в обращении, можно найти в обзоре Synthetix на сайте [DeFi Pulse](https://dashboard.synthetix.io).

По состоянию на 9 сентября 2020 г.:
- Общая заблокированная сумма (в долларах США): 650,2 млн долларов США.
- Всего заблокировано (в ETH): 1,9 млн ETH.
- Всего заблокировано (в BTC): 63,3 тыс. BTC
- Всего заблокировано (в SNX): 141M SNX
- % заблокированного предложения SNX: 70,36%