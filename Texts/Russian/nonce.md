---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: одноразовый номер
description: В технологии блокчейн одноразовый номер означает число, добавляемое к хешированному или зашифрованному блоку, которое при повторном хэшировании соответствует ограничениям уровня сложности. Блокчейн-майнеры стремятся решить одноразовый номер.
---

# одноразовый номер
Nonce относится к числу или значению, которое можно использовать только один раз. Nonces часто используются в протоколах аутентификации и криптографических хеш-функциях. В контексте технологии блокчейн одноразовый номер относится к псевдослучайному числу, которое используется в качестве счетчика в процессе майнинга.

Например, биткойн-майнеры должны попытаться угадать действительный одноразовый номер, поскольку они выполняют несколько попыток вычислить хэш блока, который соответствует определенным требованиям (т. е. начинается с определенного количества нулей). Соревнуясь за добычу нового блока, первый майнер, который находит одноразовый номер, который приводит к действительному хешу блока, получает право добавить следующий блок в [цепочку блоков](/blockchain) и получает за это вознаграждение.

Другими словами, процесс майнинга состоит из майнеров, выполняющих множество хэш-функций со множеством различных значений одноразовых номеров, пока не будет получен действительный результат. Если результат хэширования майнера падает ниже заданного порога, блок считается действительным и добавляется в цепочку блоков. Если вывод недействителен, майнер продолжает попытки с разными значениями nonce. Когда новый блок успешно добыт и проверен, процесс начинается заново.

В Биткойне — и в большинстве систем Proof of Work — одноразовый номер — это просто случайное число, которое майнеры используют для итерации вывода своих хеш-вычислений. Майнеры используют метод проб и ошибок, при котором каждый расчет принимает новое значение одноразового номера. Они делают это потому, что вероятность точного угадывания действительного одноразового номера близка к нулю.

Среднее количество попыток хеширования автоматически регулируется протоколом, чтобы гарантировать, что каждый новый блок генерируется в среднем каждые 10 минут. Этот процесс известен как корректировка сложности и определяет порог майнинга (т. е. сколько нулей должен начинаться с хэша блока, чтобы считаться действительным). Сложность майнинга нового блока связана с объемом хэш-мощности (скоростью хеширования), выделенной для системы блокчейна. Чем больше хэш-мощности выделяется сети, тем выше будет пороговое значение, а это означает, что для конкурентоспособного и успешного майнера потребуется больше вычислительной мощности. Напротив, если майнеры решат прекратить добычу, сложность будет скорректирована, а порог снизится, поэтому для майнинга потребуется меньше вычислительной мощности, но протокол будет следить за тем, чтобы генерация блоков выполнялась в соответствии с 10-минутным графиком, независимо от .

## Особенности

- Майнеры открывают новые блоки, генерируя одноразовый номер, который делает хэш, который они создают, меньше, чем хеш из блока, который они проверяют.

- Nonce, «число, используемое только один раз», относится к числу, которое майнер блокчейна должен обнаружить, прежде чем найти блок в блокчейне.

- Как только майнер находит хэш, он получает награду за блок.

## ЧАСТО ЗАДАВАЕМЫЕ ВОПРОСЫ

### Как используются одноразовые номера?

В криптовалюте одноразовые номера используются как число, которое используется в хеше для проверки транзакций и других данных, содержащихся в блоке.

### Что означает Nonce?

В криптовалюте nonce — это аббревиатура от «числа, используемого только один раз», то есть числа, добавляемого к хешированному или зашифрованному блоку в блокчейне, который при повторном хешировании соответствует ограничениям уровня сложности. Nonce — это число, которое майнеры блокчейна решают, чтобы получить вознаграждение за блок.

### Что такое одноразовый номер блокчейна?

Одноразовый номер блокчейна — это число, добавляемое к хешированному или зашифрованному блоку в блокчейне.

