# Azure DevOps - Pipeline
1. Заходим в Azure с помощью своего университетского аккаунта. Проверяем доступность ресурсов.
![info](./Images/1.jpg)

2. Содаем новы ресурс.
![info](./Images/2.jpg)

3. Устанавливаем pytest, настраиваем Pycharm для запуска тестов через IDE.
![info](./Images/3.jpg)

4. Запуск тестов.
![info](./Images/4.jpg)

5. В классе Calculator допускаем ошибку в функции. Пишем, что 4+7 = 12.
![info](./Images/5.jpg)

6. Устанавливаме модуль selenium.
![info](./Images/6.jpg)

7. Скачиваем необходимый драйвер (chrome) и вкладываем в папку с функциональными тестами.
![info](./Images/7.jpg)

8. Запускаем веб-приложение.
![info](./Images/8.jpg)

9. Запускаем тесты.Проверяем, чтобы все были пройдены.
![info](./Images/9.jpg)

10. Открываме проект.
![info](./Images/10.jpg)

11. Создаём CI pipeline, выбираем Git как источник кода, выбираем репозитори PipelinePractice, в yaml файл вставляем нужны код.
![info](./Images/11.jpg)

12. Нажимаем Run. Переходим в пайплайн. Убеждаемся, что все stages выполнены
![info](./Images/12.jpg)

13. Смотрим артефакты.
![info](./Images/13.jpg)

14. В Azure DevOps создаем Release
![info](./Images/14.jpg)

15. В артефакт добавляем результат pipeline из CI конвейра, ставим триггер. 
16. Добавляем Stage. Stage называем deploy.
![info](./Images/15.jpg)

17. Удаляем все stages. Добавляем Azure App Service Deploy.
![info](./Images/16.jpg)

18. Конфигурируем настройки сервиса в Azure.
19. Нажимаем Create release. 
![info](./Images/17.jpg)

