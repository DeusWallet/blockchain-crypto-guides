# Zcash expliqué simplement

Zcash est une crypto-monnaie similaire à [Bitcoin](bitcoin.md), mais elle se concentre fortement sur la confidentialité, en utilisant certaines des cryptographies les plus avancées du secteur.

Ce guide explique ce qui rend Zcash unique, comment l'utiliser et pourquoi il se développe.

## 1. Origines de Zcash

Zcash est né d'une proposition expérimentale d'un groupe de scientifiques et de mathématiciens visant à remédier au manque de confidentialité de Bitcoin.

Lancé le 28 octobre 2016 par [Electric Coin Co](https://electriccoin.co), Zcash a été la première crypto-monnaie à utiliser les [zk-SNARK](https://www.investopedia.com/terms/z/ zksnark.asp), également connue sous le nom de preuves sans connaissance.

> En termes simples, un zk-SNARK permet à une partie de prouver qu'elle possède certaines informations sans révéler les informations réelles.

Cela permet à la blockchain Zcash de vérifier la validité des transactions (par exemple, confirmer que le dépensier dispose de suffisamment de fonds) sans exposer les données privées sur les entités impliquées.

En revanche, chaque transaction Bitcoin révèle des informations sur le solde de l'expéditeur et les transactions passées/futures.

## 2. Zcash contre Bitcoin

Comparé à [Bitcoin](bitcoin.md) ou [Ethereum](ethereum.md), Zcash offre une confidentialité améliorée et permet des transactions entièrement confidentielles.

Les utilisateurs de Zcash peuvent choisir d'envoyer des transactions privées en fonction du contexte et de la situation.

Outre la confidentialité, Zcash est un fork de Bitcoin et partage de nombreuses propriétés fondamentales, comme une offre limitée de 21 millions de jetons ZEC.

> Comme Bitcoin, les transactions Zcash sont visibles publiquement sur une blockchain.
>
> Cependant, les utilisateurs de Zcash peuvent choisir d'effectuer des transactions publiques ou privées. Les transactions privées ne révèlent aucune information sur les parties impliquées ou sur le montant transféré.
>
> Les nœuds Zcash peuvent valider des transactions privées sans connaître les détails de la transaction.

Pour la conformité ou les audits (où la transparence est requise), Zcash propose une fonctionnalité de paiement sélectif. [Divulgations sélectives](https://www.zfnd.org/zcon/0/workshop-notes/selective-disclosure-workshop/) permettent aux utilisateurs de partager des détails de transaction spécifiques tout en gardant les autres informations privées.

Points forts de Zcash :

- Le symbole de Zcash est « ZEC ». Une seule ZEC se compose de 100 millions de sous-unités appelées zatoshis, similaires aux satoshis de Bitcoin.
- Alors que la blockchain Bitcoin prend environ 10 minutes pour traiter un bloc, Zcash traite les blocs environ toutes les 75 secondes.
- Chaque bloc traité récompense les mineurs avec une ZEC nouvellement créée. Depuis novembre 2020, la récompense globale est de 3,125 ZEC.
- Comme Bitcoin, la récompense de bloc est réduite de moitié environ tous les quatre ans jusqu'à ce que les 21 millions de ZEC soient en circulation.

## 3. Confidentialité Zcash

Zcash a deux types d'adresses : transparentes et blindées.

- Les adresses transparentes commencent par « t » et se comportent comme des adresses Bitcoin, exposant l'expéditeur, le destinataire et le montant de la transaction sur la blockchain.
- Les adresses protégées commencent par « z » et offrent une confidentialité renforcée.

Ces adresses sont interopérables, permettant aux utilisateurs d'envoyer et de recevoir des fonds entre différents types d'adresses.

Il existe quatre types de transactions Zcash :

- Entièrement blindé (z-à-z)
- Partiellement blindé (z-to-t)
- Partiellement blindé (t-to-z)
- Entièrement transparent (t-to-t)

Les transactions entièrement protégées chiffrent l’expéditeur, le destinataire et le montant, garantissant ainsi une confidentialité totale. Ces transactions ne peuvent être retracées que si l'expéditeur ou le destinataire révèle des informations.

Les transactions entièrement transparentes sont similaires aux transactions Bitcoin, avec des adresses et des montants de transaction visibles sur une blockchain publique.

## 4. Écosystème Zcash

Comme toutes les principales blockchains de crypto-monnaie, Zcash est open source, permettant à quiconque d'explorer son fonctionnement et de réutiliser sa base de code.

Zcash a développé une communauté de contributeurs, notamment des cryptographes, des activistes et des combattants de la liberté de classe mondiale, en raison de l'accent mis sur la confidentialité.

> Tout projet mondial de cryptomonnaie visant sa survie à long terme a besoin d'une communauté décentralisée prête à poursuivre son développement indépendamment des autres entités.

Bien que tout le monde puisse contribuer à Zcash, les principales entités qui stimulent sa croissance sont :

- **Société de pièces électriques (ECC)**

 ECC a créé Zcash et soutient son développement continu par la R&D, l'ingénierie, le développement commercial et l'engagement réglementaire. C'était le premier projet à mettre en œuvre des preuves sans connaissance.

 Site Web : [Electric Coin Co](https://electriccoin.co)

- **Fondation Zcash**

 Une entité à but non lucratif qui maintient et améliore le protocole Zcash pour tous les utilisateurs. Initialement financé par les dons des parties prenantes de Zcash, il reçoit désormais un financement du Fonds de développement communautaire.

 Site Web : [https://www.zfnd.org](https://www.zfnd.org)

- **Comité d'examen des subventions majeures (MGRC)**

 Lancé dans le cadre de la mise à niveau du réseau Canopy, le MGRC accorde des subventions importantes aux développeurs indépendants pour décentraliser davantage les efforts de Zcash.

 En savoir plus sur [MGRC](https://electriccoin.co/blog/ecc-welcomes-the-major-grants-review-committee/).

Ces entités sont fondamentales pour la croissance, l'expansion et la décentration de Zcash. alisation. Zcash est autofinancé avec une gouvernance communautaire solide qui aligne les incitations des principales parties prenantes.

- Du 28 octobre 2016 au 18 novembre 2020, 10 % de toutes les pièces nouvellement émises ont été versées à la « Récompense des fondateurs ».
- Après le 18 novembre, environ 20 % de toutes les ZEC nouvellement émises (environ 0,6 ZEC toutes les 75 secondes) sont distribuées au Fonds de développement communautaire, mettant fin à la récompense des fondateurs.

Le Fonds de développement communautaire aide les nouveaux participants à améliorer, développer, étendre et soutenir Zcash.

## 5. Pourquoi Zcash se développe

L’un des problèmes majeurs des crypto-monnaies existantes est le manque de confidentialité. Malgré la croyance populaire, la plupart des crypto-monnaies offrent peu ou pas de confidentialité.

À l’exception de Zcash et de quelques autres, la plupart des crypto-monnaies manquent de confidentialité, ce qui les rend impropres aux transactions privées.

Bitcoin, Ethereum et d’autres crypto-monnaies majeures n’ont pas réussi à répondre aux problèmes de confidentialité, souvent cités comme leur point le plus faible.

La confidentialité est devenue encore plus pertinente à mesure que les géants de la technologie surveillent l’activité Internet et que les banques centrales font pression pour des monnaies uniquement numériques.

Les utilisateurs de crypto-monnaie soucieux de leur confidentialité et les premiers utilisateurs ont besoin de pièces de confidentialité, et Zcash est l'un des rares à pouvoir le fournir.

Ses fondamentaux solides et le soutien de certains des esprits les plus brillants du secteur des crypto-monnaies attirent de nombreuses personnes vers Zcash.

## 6. Défis Zcash

Comme la plupart des crypto-monnaies, Zcash est confronté à des défis qui pourraient entraver sa croissance.

- **Configuration approuvée**

 La technologie de confidentialité de Zcash repose sur une « configuration de confiance » pour former les paramètres initiaux des transactions privées. Bien que des garanties soient en place, les critiques suggèrent que les fondateurs pourraient utiliser ce système pour créer un nombre illimité de jetons Zcash. L'équipe de recherche de Zcash travaille sur [Halo](https://electriccoin.co/blog/explaining-halo-2/), qui pourrait éliminer le besoin d'une configuration fiable.

- **Adoption protégée**

 Le pourcentage de transactions protégées sur le réseau Zcash est faible par rapport à l'utilisation totale. Cependant, Zcash progresse vers une adoption croissante du secteur protégé, notamment avec le soutien des principales bourses.

- **Vitesse de la blockchain**

 Bien que Zcash puisse traiter plus de transactions que Bitcoin, il reste limité à environ 20 transactions par seconde. Ce n’est pas un problème pour l’instant, car l’activité actuelle est inférieure à la limite.

- **Concours**

 Les crypto-monnaies concurrentes comme DASH et Monero se concentrent également sur la confidentialité. Bien que Monero ait actuellement la capitalisation boursière la plus élevée, il reste à voir lequel attirera le plus d'utilisateurs à long terme.

Du point de vue de l'utilisateur, nous espérons que Zcash continuera de croître et deviendra la pièce de référence en matière de confidentialité pour ceux qui recherchent la conformité et la confidentialité à la demande.