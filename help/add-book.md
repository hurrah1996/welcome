## Алгоритм добавления книги.
Данная инструкция является сокращенным извлечением из полной инструкции в репо lib-doc. 
Актуальна для проходящих вводную стажировку до получения доступа к репозиториям с кодом.

#### 0. Чтобы добавить книгу нужно зарегистрироваться и иметь статус Contributor.
Статус Contributor дает Administrator.
При наличии этого статуса вам доступна таблица статистики.
Выбирать книги для добавления нужно на ее основе (белые клетки означают отсутствие перевода в системе).

#### 1, 2. - не актуальны.

#### 3. Создать новую книгу на основе метакниги из предыдущего пункта на странице "Add book" в личном кабинете пользователя.
Если вы создали метакнигу, нужно добавить книги в нее на двух языках.
Публикация книги возможна только при наличии книг на двух языках.

#### 4. Добавить текст книги в созданную в пункте 3 книгу в соответствующее поле на странице "Add text" в личном кабинете пользователя.

#### 5. В личном кабинете проверить, что монолингвальный текст отображается правильно, сноски есть.

#### 6. Если книга отображается правильно, ее можно опубликовать соответствующей кнопкой в личном кабинете.
Опубликовать можно только книгу, для которой есть минимум одна парная с параллельным текстом.

#### 7. Если книга отображается не верно, ее надо стереть.

#### ПРАВИЛА РАЗМЕТКИ КНИГИ:
a. Текст размечается с помощью символов {, |, [], @.
b. Разметка главы:   { - это начало главы, | - это конец заголовка главы.
c. Разметка сносок: [Номер сноски] [Номер сноски] текст сноски @. Сноски размечаются прямо в тексте.
d. Между абзацами в тексте главы должно быть 2 переноса строки. То есть между двумя абзацами должна быть пустая строка.
e. Между названием главы и первым абзацем главы, а также между последним абзацем главы и названием новой главы должно быть тоже 2 переноса строк.
f. Размеченный текст завершается символом {.

ВАЖНО: Число глав в текстах книг, ассоциированных с одной метакнигой, должно совпадать.

--------
#### ПРИМЕР РАЗМЕЧЕННОГО ТЕКСТА:
#####  { Часть 1 |
######  { Глава 1 |  Текст главы 1
######  { Глава 2 |  Текст главы 2. Текст до сноски[1]. Текст после сноски.
#####  { Часть 2 |
######  { Глава 1 |  Текст главы 1
######  { Глава 2 |  Текст главы 2
######  { Глава 3|  Текст главы 3
######  {
###### \[1] текст сноски @
---------

#### ПРИМЕЧАНИЕ 1:
Если совершена ошибка с разметкой и добавлением книг/метакниг/авторов/текста, их надо удалить и добавить заново, исправив ошибки.
Удаление книги осуществляется на странице “My books” в личном кабинете пользователя с помощью кнопки “Delete book”.

#### ПРИМЕЧАНИЕ 2: При добавлении переводов книги, нужно указывать год перевода.