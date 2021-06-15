from os import environ

# Настройки записи, можно не менять, но на всякий случай
OWNER_ID = -174105461
POST_ID = 35135

# Токен(ы) пользователей
TOKENS = environ.get('#access_token=464a830b57b010214c7b98861739f088157d368f2dcf0e0be2554464da117f956bb7ba591cb0c15468e2a&expires_in').split(',')

# Задержка в секундах (на данный момент 4 часа и 15 секунд)
DELAY = (60 * 60 * 4) + 15

# Удалять коментарий? (True - да, False - нет)
DELETE_COMMENTS = True

# Задержка перед удалением коментариев (в секундах, не стоит ставить меньше 5)
DELAY_BEFORE_DELETION = 10
