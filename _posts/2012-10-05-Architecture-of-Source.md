---
layout: post
title: "Архитектура кода"
description: ""
category: 
tags: [design, wtf]
---
{% include JB/setup %}

<img class="img-center" src="http://31808.selcdn.ru/it-prm/pics/blueprint-1.jpg" alt="Архитектура кода">

Сегодня на работе стал свидетелем жаркой дискуссии между менеджером и разработчиками. Суть спора заключалась в том, что программисты решили что необходима определенная фишка, и ее обязательно нужно заложить в архитектуру, а еще лучше — сделать. Менеджеру эта фишка казалась чуть более, чем полностью не нужной. Кричали, матерились, но разработчики стояли на своем — нужно заложить фичу в архитектуру. Допустим, правы все — фича логичная, но, сейчас не нужная. Менеджер предложил сделать проект без фичи, а в следующей интерации над ней подумать, программисты сказали, что так нельзя, нужно делать сейчас — что бы потом все не переписывать заново.

Из этого спора я сделал вывод — или я не понимаю, что такое архитектура и проектирование, или разработчики. По-моему **в архитектуру закладываются не фичи, а возможность их реализации.** При чем, не конкретной фичи, или модуля, а определенного типа модулей и фич. Конечно это увеличивает время на разработку, но под проектированием я подразумеваю именно создание модели такой системы, для внесения существенных изменений в которую не придется переделывать все заново. А если одну "фичу в архитектуру заложить", то где гарантия, что при чуть изменившихся требованиях к фиче не придется свое детище учить ходить на костылях?

WTF?! Кто прав?