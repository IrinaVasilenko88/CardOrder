[![Build status](https://ci.appveyor.com/api/projects/status/m6oruy249xks9pkr?svg=true)](https://ci.appveyor.com/project/IrinaVasilenko88/cardorder)

# Обучение в Нетологии.

## Домашнее задание по курсу Автоматизированное тестирование

## Тема: Тестирование веб-интерфейсов, Selenium и Selenide

Автоматизация тестов на приложение ```app-order.jar``` с использованием селекторов на базе Gradle, с использованием Selenide

![](https://github.com/netology-code/aqa-homeworks/blob/aqa4/web/pic/order.png)

Требования к содержимому полей:

Поле Фамилия и имя - разрешены только русские буквы, дефисы и пробелы.
Поле телефон - только цифры (11 цифр), символ + (на первом месте).
Флажок согласия должен быть выставлен.
Тестируемая функциональность: отправка формы.

Условия: если все поля заполнены корректно, то вы получаете сообщение об успешно отправленной заявке:

![](https://github.com/netology-code/aqa-homeworks/blob/aqa4/web/pic/success.png)

Условия: если какое-то поле не заполнено, или заполнено неверно, то при нажатии на кнопку "Продолжить" должны появляться сообщения об ошибке (будет подсвечено только первое неправильно заполненное поле):

![](https://github.com/netology-code/aqa-homeworks/blob/aqa4/web/pic/error.png)

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/IrinaVasilenko88/CardOrder.git
``` 
2. Открыть склонированный проект в Intellij IDEA
3. Открыть в терминале каталог ```artifacts```
4. Для запуска приложения ввести команду ```java -jar app-order.jar```
5. Для запуска в браузере ввести ссылку http://localhost:9999/
6. Запустить команду ```gradlew test```
