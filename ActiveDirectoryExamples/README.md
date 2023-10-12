# ActiveDirectoryExamples
RPA-проект демонстрирует работу с библиотекой [Primo.ActiveDirectory](https://docs.primo-rpa.ru/primo-rpa/g_elements/el_extra/els_activediresctory).

Сценарий представлен в виде последовательности. В нем используется контейнер `Active Directory connection` для подключения к серверу **Active Directory** (далее **AD**), в котором помещаются все остальные действия. 

В проекте можно найти примеры:  
1. Поиска в **AD** объекта с помощью *LDAP-фильтра*[^1].
2. Поиска в **AD** пользователя по Имени (*CN* или *Common Name*).
3. Получения всех атрибутов пользователя.
4. Добавления пользователя в группу.
5. Получения списка групп, в которых состоит пользователь.
6. Удаления пользователя из группы.

Предполагается, что данный проект будет запускаться на машине, находящейся в одной сети с развернутым сервером Active Directory.

[^1]: [Статья](https://learn.microsoft.com/en-us/windows/win32/adsi/search-filter-syntax) о синтаксисе фильтров LDAP. 
[Список полей](https://learn.microsoft.com/en-us/windows/win32/adschema/attributes-all) Active Directory. 
