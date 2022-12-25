# Receipt-AVQA-2023

Страница конкурса на сайте конференции Диалог:

https://www.dialog-21.ru/evaluation/2023/receiptavqa2023/

## Описание задачи

Участникам предлагается к выполнению задача автоматической генерации ответов на вопросы к изображению (Visual Question Answering), а также генерации ответов на вопросы с использованием текстовой информации (Question Answering).
## Датасет 

Датасет, на основе которого необходимо выполнить задачу, представляет собой изображения товарных чеков с текстом на английском языке и вопросы и ответы к ним.  Для ответа на вопросы потребуется применение простейших операций агрегации к извлечённым данным (суммирование, умножение, усреднение и прочие).

Для задачи Visual Question Answering участники могут использовать в качества входных данные изображения товарных чеков и вопрос в текстовой форме.

Для задачи Question Answering для каждого товарного чека дополнительно доступен файл с текстовым содержимым товарного чека. 

Изображения хранятся в директории `images`. В директории `dev` хранятся изображения для валидационной. В директориях `train_part1`, `train_part2` хранятся изображения для обучающей выборки.

Отдельной в файле `questions_answers.csv` хранятся вопросы (столбец `question`) и ответы (столбец `answer`) к ним. Чтобы можно было сопоставить изображения/текстовую разметку с файлами для каждой пары вопрос-ответ предоставлена информация с выборке (столбец `split`) и имени файла (столбец `file_name`).

## График проведения соревнования

* **25 декабря** — публикация обучающего и валидационного датасетов;
* **18 февраля** — публикация тестового датасета;
* **1 марта** — предоставление участниками результатов;
* **5 марта** — публикация оценки результатов;
* **25 марта** — предоставление участниками статей.


