3D-атлас биомолекул — статический сайт

Состав
  index.html       главная страница
  insulin.html     инсулин (PDB 1WAV)
  kyna-quin.html   кинуреновая и хинолиновая кислоты
  img/             превью для главной
  vendor/          3Dmol.js 2.5.5 (лицензия BSD-3-Clause, см. 3Dmol-LICENSE.txt)

Сервер не нужен: подходит любой хостинг статических файлов.
index.html должен лежать в корне сайта.

GitHub Pages
  1. Создайте публичный репозиторий на github.com.
  2. Add file -> Upload files: перетащите все файлы и папки img и vendor, нажмите Commit changes.
  3. Settings -> Pages -> Build and deployment -> Source: Deploy from a branch,
     ветка main, папка / (root) -> Save.
  4. Через несколько минут сайт откроется по адресу https://<логин>.github.io/<репозиторий>/

Netlify
  Войдите на netlify.com и перетащите папку сайта (или этот архив) на app.netlify.com/drop.
  Адрес будет вида https://<имя>.netlify.app

Локально страницы тоже открываются: достаточно открыть index.html в браузере.
