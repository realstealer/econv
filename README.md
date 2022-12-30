# econv
Программа позволяет конвертировать ЭЦП из файлового представления в файл реестра Windows, 
который уже можно импортировать в систему и пользоваться. 
Если ЭЦП является неэкспортируемой, после импорта она продолжает оставаться таковой, но уже в реестре

# Как пользоваться:
1) Запускаем контуровскую программу "Check Tokens", которая позволяет экспортировать неэкспортируемый контейнер в файловое представление. Экспортируем с ее помощью интересующую нас подпись в любое удобное место
2) Запускаем программу econv.exe, где заполняем:
    * SID пользователя в системе, на которого будем вешать подпись
    * Битность установленной CryptoPro
    * Выбираем все полученные на шаге #1 файлы
    * Нажимаем "Экспортировать", где указываем путь для сохранения полученного REG-файла
3) Также есть необязательная, но приятная мне опция "Сказать спасибо" на счет в Тинькове )))
4) Импортируем любым удобным образом полученный REG-файл в реестр

Успехов всем, удачи и добра
