# OpenIPC Wiki
[Оглавление](../index.md)

Дискуссия по дорожной карте проекта
-----------------------------------


| Сервис или служба | Текщая реализация | Статус и предложения на будущее |
|-------------------|-------------------|---------------------------------|
| gpio management   | majestic          |                                 |
| netip             | majestic          |                                 |
| onvif             | majestic          |                                 |
| rtsp              | majestic          |                                 |
| web               | majestic / httpd  |                                 |
| wdt               | модули / в ядре   | Вынести всё в модули для возможности выгрузки/остановки с единым интерфейсом управления |
| motors            | разрозненная      | Единый motors.ko, который при загрузке получает информацию о наличии P,T,Z,F,D,ircut, концевиках, на каких ногах это всё сидит. Доступен на чтение/запись всех положений |
|                   |                   |                                 |
| список дополнить  |                   |                                 |


