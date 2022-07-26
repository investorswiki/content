---
keywords: Investing,Cryptocurrency,Altcoins
title: Целевой хэш
description: Целевой хэш определяет сложность майнинга криптовалюты с использованием системы блокчейна с доказательством работы (PoW).
---

# Целевой хэш
## Что такое целевой хэш?

В майнинге криптовалют целевой хеш — это числовое значение, которое должно быть меньше или равно хешированному [заголовку блока, чтобы новый блок был присужден майнеру.](/block-header-cryptocurrency) Заголовки блоков идентифицируют отдельные блоки в блокчейне.

Майнинг криптовалюты относится к процессу сбора криптовалюты в качестве вознаграждения за выполненную работу. Суть этой работы заключается в проверке легитимности транзакций данной криптовалюты. Таким образом, майнеры криптовалюты по сути являются аудиторами. Когда вы майните, вы можете зарабатывать криптовалюту, не вкладывая в нее деньги.

Целевой хэш используется для определения сложности ввода и может быть скорректирован для обеспечения эффективной обработки блоков. Например, целевые хэши используются в криптовалютах, которые используют систему доказательства работы (PoW) для установки текущей [сложности майнинга](/difficulty-cryptocurrencies) [(](/difficulty-cryptocurrencies) включая Биткойн). Если криптовалюта использует другую систему для майнинга, целевой хэш может не требоваться.

## Как работает целевой хэш

[Криптовалюты](/cryptocurrency) полагаются на использование [блокчейнов](/blockchain),. которые содержат историю всех транзакций этой криптовалюты. Эти транзакции [хэшируются](/hash) или криптографически кодируются в серию буквенно-цифровых символов. Хеширование включает в себя взятие строки данных любой длины и обработку ее алгоритмом для получения вывода фиксированной длины. Выходные данные всегда будут одинаковой длины, независимо от того, насколько велики или малы входные данные (хотя количество перестановок хеша астрономически велико). Каждый блок будет содержать хэш заголовка предыдущего блока.

Проверка и кодирование блокчейна называется [майнингом](/bitcoin-mining). Майнинг предполагает использование компьютеров для запуска алгоритмов хеширования для обработки самого последнего блока; информация, которую пользователь должен добывать, находится в заголовке блока. Криптовалютная сеть устанавливает целевое значение для этого хэша, называемое целевым хешем, и майнеры пытаются определить, каково это значение, проверяя все возможные значения.

Заголовок блока содержит номер версии блока, временную метку, хэш, использованный в предыдущем блоке, хэш [корня](/merkle-root-cryptocurrency) [Меркла](/merkle-root-cryptocurrency),. [одноразовый номер](/nonce) и целевой хэш. Блок создается путем взятия хэша содержимого блока, добавления случайной строки чисел (одноразового номера) и повторного хэширования блока.

Если хэш соответствует требованиям цели, то блок добавляется в цепочку блоков. Перебор решений для угадывания одноразового номера называется [доказательством работы](/proof-work) (PoW), и майнер, который может найти значение, получает блок и получает оплату в криптовалюте.

## Особые соображения

### Целевой хэш для биткойнов

Биткойн использует алгоритм хеширования SHA-256. Этот алгоритм генерирует поддающиеся проверке случайные числа способом, который требует предсказуемой вычислительной мощности компьютера.

Добыча блока требует от майнера создания значения (одноразового номера), которое после хэширования (криптографического кодирования) меньше или равно значению, использованному в самом последнем блоке, принятом сетью биткойн. Это число находится в диапазоне от 0 (наименьший вариант) до 256 бит (наибольший вариант), но вряд ли когда-либо будет максимальным числом.

Поскольку целевой хэш может быть огромным числом, майнеру, возможно, придется протестировать большое количество значений, прежде чем добиться успеха. Неудачный майнер должен ждать следующего блока (поэтому майнеры, которые находят хэш-решение, сравниваются с победителями гонки или лотереи).

Целевой хэш периодически корректируется. Хеш-функции, используемые для создания новой цели, обладают особыми свойствами, предназначенными для обеспечения безопасности блокчейна (и его криптовалюты). Этот процесс является детерминированным, что означает, что он будет давать один и тот же результат каждый раз, когда используются одни и те же входные данные. Это достаточно быстро, чтобы не тратить слишком много времени на возврат хэша для ввода. Это также сильно затрудняет определение входных данных, особенно для больших чисел, и вносит небольшие изменения во входные данные, что приводит к совершенно другому результату хеширования.

## Особенности

- Целевые хэши используются в криптовалютах, которые используют систему доказательства работы (PoW) для установки текущей сложности майнинга (включая Биткойн); если криптовалюта использует другую систему для майнинга, целевой хэш может не требоваться.

- В майнинге криптовалюты целевой хеш — это числовое значение, которое должно быть меньше или равно хешированному заголовку блока (который используется для идентификации отдельных блоков в цепочке блоков), чтобы новый блок был присужден майнеру.

- Сеть Биткойн регулирует сложность майнинга, повышая или понижая целевой хэш, чтобы сохранить средний 10-минутный интервал между новыми блоками.

