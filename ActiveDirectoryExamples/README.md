# ActiveDirectoryExamples
Проект содержит процесс, демонстрирующий пример работы с пакетом элементов [Primo.ActiveDirectory](https://docs.primo-rpa.ru/primo-rpa/g_elements/el_extra/els_activediresctory)

Процесс построен в одной последовательности и использует контейнер `Active Directory connection` для подключения к серверу **Active Directory** (далее **AD**), в котором и выполняются все действия. 

В проекте можно найти примеры для выполнения следующих действий:  
1. Поиск в **AD** объекта с помощью *LDAP-фильтра*[^1].
2. Поиск в **AD** пользователя по Имени (*CN* или *Common Name*).
3. Получение всех атрибутов пользователя.
4. Добавление пользователя в группу.
5. Получение списка групп, в которых состоит пользователь.
6. Удаление пользователя из группы.

Предполагается, что данный проект будет запускаться на машине, находящейся в одной сети с развернутым сервером Active Directory.

[^1]: [Статья](https://learn.microsoft.com/en-us/windows/win32/adsi/search-filter-syntax) о синтаксисе фильтров LDAP. 
[Список полей](https://learn.microsoft.com/en-us/windows/win32/adschema/attributes-all) Active Directory. 