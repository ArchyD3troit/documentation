users.getCallsLeft

$description
Метод позволяет приложению проверить, не превышен ли предел вызова методов для указанного пользователя

$params#uid
Идентификатор пользователя

$params#methods
Список разделенных запятыми имен методов

$additional
Каждый пользователь приложения имеет определенное количество вызовов методов. Ограничения приведены в разделе Ограничения приложения.

Чтобы узнать оставшееся количество вызовов клиентского метода [showNotification](/dev/sdk/js/ui.showNotification), укажите специальную константу notifications.sendFromUser.