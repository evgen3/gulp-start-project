Файлы .lock для сохранения пустых директорий

Содержимое папки resources копируется в dist без изменений (для фавиконов и других подобных вещей)

Icons - svg-иконки для создания svg-спрайта

Скрипты и стили подключать в vendor через rigger

Требуется gulp-cli глобально

$ npm install gulpjs/gulp-cli -g

нужна поддержка editorconfig для текстового редактора/IDE

Для разработки просто gulp, для продакшн NODE_ENV=production gulp (убирает sourcemaps и тд)
