### Генерация кода из openapi:
```commandline
mvn clean compile
```
Комментарий задается в x-additional-comment у метода openapi и генерируется в интерфейсах Api и Delegate
##### Пример:
```
  /notifications:
    patch:
      x-additional-comment: Метод для переключения режима уведомлений
```
