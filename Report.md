# Отчёт о тестировании "Precision"
	
## Краткое описание
	
29.08.2021 - 29.08.2021 было проведено тестирование "Проверка работоспособности кода" приложения "Precision"
	
На тестирование затрачено: 2
	
В результате тестирования выявлены следующие дефекты:
* [Issue:Application displays invalid value in 'totalBonus' data](https://github.com/Margo-785/Precision/issues/1#issue-981937937)
	
##Описание процесса тестирования

* Запуск кода приложения
* Анализ результата
	
В качестве тестовых данных использовались данные:
* double regularBonus = 0.3
* double specialBonus = 0.6
* double totalBonus = regularBonus + specialBonus

Тестирование производилось в следующем окружении:
* Windows 10 Домашняя для одного языка, версия 2004, сборка ОС 19041.1052 (64bit)
* Java version 11.0.12
* IntelliJ IDEA 2021.2(Community Edition) Build #IC-212.4746.92, built on July 27, 2021