#### EphemerisToKml

#### Сборка:
1. Скачать gpstk-2.5, например [отсюда] (https://sourceforge.net/projects/gpstk/files/gpstk/2.5/gpstk-2.5.src.tar.gz/download)
2. Установить gpstk-2.5 по [инструкции] (https://github.com/moevm/GPSTk/blob/master/INSTALL.md)
3. Запустить терминал
4. Перейти в папку ephemeris_to_kml
5. Запустить скрипт build.sh, введя ./build.sh
6. Полученный исполнимый файл будет в папке build

#### Запуск:
1. Запустить терминал
2. Перейти в папку с исполнимым файлом ephemeris_to_kml
3. Ввести в терминале ./ephemeris_to_kml путь_к_RINEX-файлу путь_к_KML-файлу

#### Входной файл:
Входной файл должен быть в формате RINEX VERSION 2.10 GLONASS NAVIGATION MESSAGE FILE.
Пример файла в данном формате находится в папке ephemeris_to_kml/example
