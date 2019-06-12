### Тестовое задание на C#

Реализуй следующие функции в виде скрипта или приложения на C#:

1. Запуститься и выкачать репозиторий: https://github.com/niknames/testcase-posharp;
2. Проверять наличие изменений во всех ветках репозитория в заданный интервал времени.
3. При обнаружении изменений в ветке выкачать их и собрать приложение.
4. Запустить приложение и сохранить консольный вывод в файл.
5. Запаковать приложение в NuGet-пакет с метаданными:
	* ID пакета: название проекта / приложения (фиксированное значение);
	* Version: версия приложения, сформированная при сборке из исходников;
	* Description: консольный вывод приложения и хеш последнего коммита;
	* Authors: автор коммита.
6. Полученный NuGet-пакет выложить на www.nuget.org или другой публичный NuGet-репозиторий.


Задания со звездочкой: 

7. * Вынести настройки скрипта / приложения (URL-репозитория, частота проверки и другие) в файл конфигурации, либо передавать их при запуске в виде аргументов.
8. * Реализовать обработку исключений и отправка на почту неудачных попыток:
	8.1.  * проверки изменений;
	8.2. * сборки проекта;
	8.3. * запаковки в NuGet-пакет.

 
master 7








