<p align="center"><img src="https://media.giphy.com/media/WT3ulJmR8Fv1fidZIK/giphy.gif"></p>

# Привет!

Если ты здесь, значит у тебя возникла ошибка компиляции doctest'a. Если ошибка в переполнении переменной(это указанно в логах), то, скорее всего, причина в версии доктеста. Сейчас мы исправим данную ошибку.
Для этого вы загрузим в проект новые файлы

# Решение проблемы

Нам понадобится изменить 2 файла. Их вы можете найти в том числе и в этом репозитории.
<br><br>
Для начала зайдём в репозиторий, который нам нужно поправить:

<p align = "center"><img src="https://i.ibb.co/CK0GmT8/Rep-Dock-open.png"></p>

Здесь сразу находим первый файл, `.gitgnore`, нам необходимо открыть его:

<p align = "center"><img src="https://i.ibb.co/LQz300Y/Open-file.png"></p>

В правом верхнем углу окна с кодом есть кнопочка карандаша, нам необходимо нажать её, чтобы отредактировать файл:

<p align = "center"><img src="https://i.ibb.co/qJC1X5Z/Edit-button.png"></p>

<br><br>

В открывшемся окне мы можем изменить содержимое файла. Вместо старого содержания вставьте туда текст файла из этого репозитория и нажмите кнопку `commit changes`, в таком случае файл обновиться.

Аналогично нужно сделать с файлом `doctest.h`. Он находится в `isogram/external/doctest`. Аналогично его заменяем. Объём текста большой, для быстрого выделения можно использовать сочетание `CTRL + A`.
После обновления этих двух файлов, тесты должны заработать

<br>

# Послесловие

Вообще, вы можете любым способом обновить эти файлы. Главное - это обновить их к нужной версии. Описанный способ самый топорный и прямой, однако действенный).
<br><br>
В случае, если что-то у вас не работает или вам не понятно, не стесняйтесь открывать `issue`. Обязательно посмотрю и постараюсь помочь.

<p align= "center"> <img src= "https://media.giphy.com/media/3tsV0vUau14uM8LyNh/giphy.gif"> </p>
