---
keywords: Business,Business Leaders,Math and Statistics
title: гомоскедастический
description: Гомоскедастичность относится к состоянию, при котором дисперсия члена ошибки в регрессионной модели постоянна.
---

# гомоскедастический
## Что такое гомоскедастичный?

Гомоскедастический (также пишется как «гомоскедастический») относится к состоянию, при котором дисперсия остатка или [члена ошибки](/errorterm) в регрессионной модели постоянна. То есть член ошибки не сильно меняется при изменении значения переменной-предиктора. Другими словами, [дисперсия](/variance) точек данных примерно одинакова для всех точек данных.

Это предполагает уровень согласованности и упрощает моделирование и работу с данными посредством регрессии; однако отсутствие гомоскедастичности может свидетельствовать о том, что регрессионная модель должна включать дополнительные переменные-предикторы для объяснения эффективности зависимой переменной.

## Как работает гомоскедастичность

Гомоскедастичность является одним из предположений в [моделировании](/mlr) [близкой регрессии](/mlr),. и данные этого типа хорошо работают с [методом наименьших квадратов](/least-squares-method). Если дисперсия ошибок вокруг линии регрессии сильно различается, модель регрессии может быть плохо определена.

Противоположностью гомоскедастичности является гетероскедастичность, так же как противоположность «гомогенного» — «гетерогенность». [Гетероскедастичность](/heteroskedasticity) (также пишется как «гетероскедастичность») относится к состоянию, при котором дисперсия члена ошибки в уравнении регрессии не является постоянной.

## Особые соображения

Простая регрессионная модель или уравнение состоит из четырех членов. С левой стороны находится зависимая переменная. Он представляет явление, которое модель пытается «объяснить». С правой стороны находятся константа, предикторная переменная и невязка или ошибка. Член ошибки показывает количество изменчивости в зависимой переменной, которая не объясняется переменной-предиктором.

## Пример гомоскедастичности

Например, предположим, что вы хотите объяснить результаты тестов учащихся, используя количество времени, которое каждый студент потратил на учебу. В этом случае результаты тестов будут зависимой переменной, а время, потраченное на учебу, будет переменной-предиктором.

Термин ошибки будет показывать величину дисперсии результатов тестов, которая не объясняется количеством времени, затраченным на обучение. Если эта [дисперсия](/variance) равномерна или гомоскедастична, то это предполагает, что модель может быть адекватным объяснением эффективности теста, объясняя ее с точки зрения времени, затраченного на обучение.

Но дисперсия может быть гетероскедастичной. График данных об ошибках может показать, что большое количество времени обучения очень близко соответствовало высоким результатам теста, но что результаты теста с низким временем обучения сильно различались и даже включали некоторые очень высокие баллы.

Таким образом, дисперсия баллов не может быть хорошо объяснена просто одной переменной-предиктором — количеством времени обучения. В этом случае, вероятно, действует какой-то другой фактор, и модель может потребовать усовершенствования, чтобы идентифицировать его или их.

> Учитывая, что дисперсия представляет собой измеренную разницу между прогнозируемым результатом и фактическим результатом данной ситуации, определение гомоскедастичности может помочь определить, какие факторы необходимо скорректировать для обеспечения точности.

>

Дальнейшее расследование может выявить, что некоторые учащиеся видели ответы на тест заранее или что они ранее проходили аналогичный тест, и поэтому им не нужно было готовиться к этому конкретному тесту. Если на то пошло, может просто оказаться, что у студентов были разные уровни способности сдавать тесты, независимо от их времени обучения и их результатов на предыдущих тестах, независимо от предмета.

Чтобы улучшить регрессионную модель, исследователь должен был опробовать другие независимые переменные, которые могли бы обеспечить более точное соответствие данным. Если, например, некоторые учащиеся видели ответы заранее, [регрессионная модель](/regression) будет иметь две объясняющие переменные: время обучения и то, знал ли учащийся заранее ответы.

С этими двумя переменными можно было бы объяснить большую часть дисперсии результатов теста, и тогда дисперсия члена ошибки могла бы быть гомоскедастичной, предполагая, что модель была четко определена.

## Особенности

- Если дисперсия члена ошибки гомоскедастична, модель определена правильно. Если дисперсии слишком много, модель может быть определена неправильно.

- Гомоскедастичность возникает, когда дисперсия члена ошибки в регрессионной модели постоянна.

- Наоборот, гетероскедастичность возникает, когда дисперсия члена ошибки не является постоянной.

- Добавление дополнительных переменных-предикторов может помочь объяснить производительность зависимой переменной.

## ЧАСТО ЗАДАВАЕМЫЕ ВОПРОСЫ

### Почему важна гомоскедастичность?

Гомоскедастичность важна, потому что она выявляет различия в популяции. Любая дисперсия в популяции или выборке, которая неравномерна, приведет к искаженным или предвзятым результатам, что сделает анализ неверным или бесполезным.

### Что означает гетероскедастичность?

Гетероскедастичность в статистике — это дисперсия ошибки. Это зависимость рассеяния, возникающая в пределах выборки с минимумом одной независимой переменной. Это означает, что стандартное отклонение предсказуемой переменной непостоянно.

### Как узнать, является ли регрессия гомоскедастичной?

Вы можете определить, является ли регрессия гомоскедастичной, по соотношению между наибольшей и наименьшей дисперсией. Если отношение равно 1,5 или меньше, то регрессия гомоскедастична.

