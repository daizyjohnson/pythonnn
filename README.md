# pythonnn
Добавление встроенных учетных записей портала
При добавлении встроенных учетных записей портала формат каждой записи в текстовом файле выглядит следующим образом:

- username|password|email address|name|user type|role|description
# username 
– имя пользователя, используемое для встроенной учетной записи. Имена пользователей должны быть уникальны; два участника не могут иметь одинаковые имена.
# password 
– пароль, заданный для данной учетной записи. Пользователи могут использовать его во время первого входа на портал, а затем изменить пароль, отредактировав свой профиль.
# email address 
– Укажите адрес email для учетной записи. Этот параметр является обязательным. Поэтому укажите адрес email, даже если он некорректный.
name – псевдоним учетной записи, который будет использоваться в вашей организации ArcGIS. При подключении пользователя к веб-сайту портала это имя появляется в верхней части веб-сайта портала.
# Тип пользователя
 – название типа пользователя, к которому он будет приписан. Выберите любой доступный тип пользователя из ниспадающего списка. Вы можете нажать на совместимые роли и количество совместимых дополнительных лицензий, чтобы узнать, что совместимо с выбранным типом пользователя.. Более подробно см. Типы пользователей, роли и права доступа.
# role
– роль, назначенная учетной записи в организации ArcGIS. Корректными значениями ролей являются: user (пользователь), publisher (издатель), admin (администратор) и custom_role_name, где custom_role_name – это имя настраиваемой роли (к примеру, hostedservicepublisher).
# description 
– описание, содержит текст с описанием учетной записи. Описание не может быть более 250 символов.

Ниже представлен пример записи, добавляющей встроенную учетную запись портала с именем пользователя pub1 для Барбары Уильямс и адресом электронной почты bwilliams@domain.com. В этом примере для pub1 назначена роль издателя.

 pub1|changepasswordlater|bwilliams@domain.com|Barbara Williams|Creator|publisher
Ниже представлен пример записи, добавляющей встроенную учетную запись портала с именем пользователя jcho для Jon Cho и адресом электронной почты jcho@domain.com. Этой же записью для jcho назначается роль администратора с описанием ГИС-менеджер.

- jcho|changepasswordlater|jcho@domain.com|Jon Cho|GISProfessional|admin|GIS Manager 
![](https://avatars.mds.yandex.net/get-zen_doc/2977209/pub_5fa5166f1aeb58326ca04d85_5fa517748eb5b23a308f74d6/scale_1200)
спасибо за внимание, вот вам енотик с пиццей 
