# Receipt-AVQA-2023

Страница соревнования на платформе CodaLab:

https://codalab.lisn.upsaclay.fr/competitions/11087


## Формат сабмита

- В качестве сабмита принимается zip файл, который содержит текстовый файл answer.txt.
- Каждая строка в файле является ответом на соответствующий вопрос сплита датасета. Во время `development` стадии соревнования - это `dev` сплит, в `final` стадии соревнования - это `test` сплит датасета.
- Количество строк должно совпадать с количеством вопросов в соответсвующем сплите.
- Ответ на каждый вопрос предполагает в `float` формате, т.е. это потенциальная конвертация строки в число - это часть вашего решения. Если какой-то ответ не конвертируется во `float`, при расчете метрики этот ответ будет рассматриваться со значением `0.0`.

Пример файла сабмита для `dev` сплита датасета - `submission1.zip`.