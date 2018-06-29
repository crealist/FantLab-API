# Форум

## Плюсование/минусование поста
В данном запросе потребуется обработать такие ситуации, как повторное плюсование/минусование, голосование за собственный пост etc.

Запрос
```
/GET https://fantlab.ru/votepost{id}{plus|minus}
```
Параметры
```
id - id поста
cookie - авторизационный хэдер (fl_s=*)
```
Пример
```
/GET https://fantlab.ru/votepost1plus - плюсануть пост #1
```
Ответ
```
HTML
```