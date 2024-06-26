# junior-frontend-test-task
В этом репозитории находится тестовое задание для вакансии https://hh.ru/vacancy/95682575?from=employer&amp;hhtmFrom=employer

## Задание
### Предисловие
При развитии проектов в рамках работы нашего отдела бывает так, что мы ищем альтернативы технологиям, которые уже используем. Для этого составляются оценочные матрицы, по которым идёт сравнение технологий.

Однако, недостаток такого подхода заключается в том, что система оценки является относительной. Иными словами, при добавлении новой технологии в матрицу, значнеия по ключевым критерями технологий необходимо заполнять заново.

Кроме того, мы должны составлять такую матрицу для каждого вида технологий - это неудобно и отнимает время.

Ввиду всех вышеперечисленных факторов Вам предлагается разработать приложение, которое бы помогло решить эту задачу.

### Исходные данные
Вам дан массив данных, записанных в JSON. JSON можно найти в этом репозитории, файл называется `test_task.json`. В этом массиве хранится информация о технологиях, которые мы используем или рассматриваем в качестве здоровой альтернативы. Поля следующие:
- "id" - уникальный идентификатор технологии, INT;
- "name" - название технологии, STRING;
- "price_per_month" - цена подписки на сервис, предоставляющий доступ к технологии (цена указана в долларах; если технология бесплатна, то значение - "Free"), STRING;
- "category" - тип технологии, STRING;
- "in_usage" - поле показывает, используется ли технология в данный момент, BOOLEAN.

### Суть задания

Разработайте небольшое приложение с использованием Вашего фреймворка, которое бы позволяло:

- [ ] Фильтровать технологии по категории;
- [ ] Фильтровать технологии по критерию "in_usage";
- [ ] Выбирать все только бесплатные технологии;
- [ ] Проводить мультифакторную фильтрацию. То есть, необходимо рассмотреть кейс, при котором нам, например, необходимо отобрать все бесплатные технологии, находящиеся в категории LLM, которые мы в данный момент используем;
- [ ] Сортировать полученную в процессе фильтрации выборку по возрастанию и убыванию цены. Бесплатные технологии вне зависимости от направления сортировки по цене должны быть упорядочены по алфавиту в порядке возрастания.

### Как делиться решением
Код решения необходимо разместить в `публичном` репозитории GitHub. `Ссылку на него необходимо прислать Вашему HR`.
Решение можно развернуть непосредственно в GH (+ к карме), либо указать подробные инструкции к разворачиванию приложения локально. 

#### Желаю успехов!

Если после прочтения текста задания, у Вас остались вопросы, пришлите их HR.
