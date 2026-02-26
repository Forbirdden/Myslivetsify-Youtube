<div align = center>

# Myslivetsify

Ваш YouTube скучен? Вам не хватает кликбейта?

**Не беспокойтесь**

Это расширение добавляет популярного ютубера **Daniel Myslivets** на каждое превью!

</div>

<a href="https://github.com/Forbirdden/Myslivetsify-Youtube/releases/latest/download/youtube-myslivetsify-signed.xpi"><img alt="Скачать для FireFox" src="https://img.shields.io/github/downloads/Forbirdden/Myslivetsify-Youtube/latest/youtube-myslivetsify-signed.xpi?displayAssetName=false&style=for-the-badge&logo=firefoxbrowser&logoColor=%23ff9500&label=%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B4%D0%BB%D1%8F%20Firefox&labelColor=%239c78ff&color=%23ff9500"></a>

<a href="https://github.com/Forbirdden/Myslivetsify-Youtube/releases/latest/download/Chromium.zip"><img alt="Скачать для Chrome" src="https://img.shields.io/github/downloads/Forbirdden/Myslivetsify-Youtube/latest/Chromium.zip?displayAssetName=false&style=for-the-badge&logo=googlechrome&logoColor=%23f2f2f2&label=%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B4%D0%BB%D1%8F%20Chrome&labelColor=%23DB4437&color=%23f2f2f2"></a>

[![Star History Chart](https://api.star-history.com/svg?repos=Forbirdden/Myslivetsify-Youtube&type=date&legend=bottom-right)](https://www.star-history.com/#Forbirdden/Myslivetsify-Youtube&type=date&legend=bottom-right)

# [!!!!! ВНИМАНИЕ ЕСЛИ Я НАРУШИЛ КАКИЕ-ТО АВТОРСКИЕ ПРАВА НА КАРТИНКИ В ПАПКЕ IMAGES ПИШИТЕ РАЗБЕРЁМСЯ !!!!!](https://forbirdden.rf.gd/contacts.html)

## Примечания

- Это расширение должно быть совместимо с любым браузером на основе Firefox / Chromium.

- Это неофициальное расширение, не связанное с Daniel Myslivets или YouTube.

## Создание собственного расширения

Хотите настроить это расширение, добавив другого ютубера или личность? Вот как это сделать:

1. **Создайте форк этого репозитория** или клонируйте его на свой локальный компьютер.
2. **Замените изображения**:

- Замените изображения в папке `images/` своими собственными (пронумерованными последовательно: `1.png`, `2.png`, `3.png` и т. д. Не оставляйте пробелов в нумерации). Вы можете использовать такие сайты, как [Photoroom](https://www.photoroom.com/tools/background-remover), чтобы удалить фон ваших изображений, и такие сайты, как [compresspng](https://compresspng.com/), чтобы сжать ваши изображения.

- Обновите `icon.png`, добавив свою иконку.
3. **Обновите манифест**:

- Отредактируйте `manifest.json` и `manifest v3.json`, изменив название расширения, номер версии и описание.
4. **Обработка текстовых изображений** (необязательно):

- Если какие-либо изображения содержат текст, который не должен быть перевернут, добавьте его в `images/flip_blacklist.json`.

- При необходимости создайте альтернативные перевернутые версии в `images/textFlipped/`.

- Если вам не нужен черный список перевернутых изображений, удалите файл `flip_blacklist.json`.

5. **Протестируйте локально**: Загрузите расширение в режиме разработчика в предпочитаемом браузере. Это важно. Не загружайте неработающие расширения!

6. **Соберите расширение**: Если у вас установлен 7-Zip, запустите `build.bat` для сборки расширения. Это создаст zip-файл в корневом каталоге репозитория. (К сожалению, зависимость от 7-Zip необходима, поскольку встроенная в Windows функция сжатия архивов по какой-то причине полностью не работает). При ручной упаковке включайте только `images/`, `manifest.json`, `icon.png`, `settings.html`, `settings.js` и `mrbeastify.js`. При упаковке для Chrome используйте файл `manifest v3.json`, но переименуйте его в `manifest.json`.

7. **Загрузка в магазины расширений**: Вы можете загрузить свою модифицированную версию в Chrome Web Store, Firefox Add-ons и т. д.
