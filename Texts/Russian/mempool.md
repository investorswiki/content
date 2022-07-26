---
keywords: Crypto
title: Мемпул
description: Мемпул. Механизм узла для отслеживания неподтвержденных транзакций, которые видел узел (но еще не были добавлены в блок).
---

# Мемпул
Мемпул (сокращение памяти и пула) — это механизм узла криптовалюты для хранения информации о неподтвержденных транзакциях. Он действует как своего рода зал ожидания для транзакций, которые еще не были включены в [блок](/block).

Когда транзакция широковещательная, она отправляется с узла на его одноранговые узлы, которые затем передают ее своим одноранговым узлам. Это продолжается до тех пор, пока транзакция не будет широко распространена, чтобы майнеры могли добавить ее в блок. Очень важно, чтобы эта буферная зона существовала, поскольку транзакции не добавляются в блокчейн сразу.

Узлы проведут серию проверок, чтобы убедиться, что транзакция действительна, т. е. проверяет правильность подписей, выходы не превышают входы и средства еще не были потрачены. Если он не удовлетворяет этим условиям, он отклоняется.

Мы часто говорим о мемпуле, но следует отметить, что универсального пула, разделяемого всеми узлами, не существует. Каждый из них настроен по-разному и получает транзакции в разное время. Устройства более низкого уровня с ограниченными ресурсами могут выделять лишь небольшой объем памяти для регистрации транзакций, тогда как устройства более высокого уровня могут выделять значительно больше.

Поскольку майнеры мотивированы главным образом прибылью, транзакции с более высокими комиссионными, скорее всего, будут удалены из мемпула в первую очередь, как только они будут подтверждены. Точная оценка комиссий затруднена, особенно когда пространство блока ограничено, а спрос высок, но мемпул обеспечивает отправную точку.

Чтобы оценить комиссию, можно просмотреть текущие неподтвержденные транзакции. Само собой разумеется, что пользователи не должны переплачивать во времена низкой пропускной способности. Они также не должны недоплачивать за срочные транзакции в часы пик, поскольку может пройти некоторое время, прежде чем они будут подтверждены. Принимая во внимание распределение комиссий в данный момент, они могут сделать обоснованное предположение о том, как быстро их транзакция будет включена.

