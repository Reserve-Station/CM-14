<p align="center"> <img alt="Space Station 14" width="400" height="400" src="https://github.com/user-attachments/assets/320ad459-8997-4e5b-9f7e-fc7e7d7dcb73" /></p>

RMC-14 вдохновлен CM13, Space Station 13, который работает на [Robust Toolbox](https://github.com/space-wizards/RobustToolbox).

Цель этого форка - попытаться повторить ощущения и опыт CM13, используя SS14 в качестве основы.

Это основной репозиторий для RMC-14. Чтобы предотвратить форк Robust Toolbox, клиент и сервер загружают пакет «контента». Этот контент-пак содержит все необходимое для игры на одном конкретном сервере.

Если вы хотите разместить или создать контент для RMC-14, это репозиторий, который вам нужен. Оно содержит как RobustToolbox, так и контент-пак для разработки новых контент-паков.

## Ссылки

[RMC-14 Community Wiki](https://wiki.rouny-ss14.com/) | [Discord](https://discord.gg/rouny) | [SS14 Steam Launcher](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Launcher Download](https://spacestation14.io/about/nightlies/)

## Вклад

Мы рады принять вклад от любого человека. Свяжитесь с нами в Discord, если хотите помочь. У нас есть [список проблем](https://github.com/RMC-14/RMC-14/issues), которые нужно решить, и любой может их подхватить. Не бойтесь просить о помощи!

## Билд

1. Клонируйте это репозиторий. (git clone https://github.com/Reserve-Station/CM-14)
2. Запустите `RUN_THIS.py` для инициализации подмодулей и загрузки движка. (git submodule update --init --recursive)
3. Скомпилируйте репозиторий. (dotnet build --configuration Release)

[Более подробные инструкции по сборке проекта.](https://docs.spacestation14.com/en/general-development/setup.html)

## Лицензия

Весь код для хранилища контента лицензирован под [MIT](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).

Большинство активов лицензировано под [CC-BY-SA-3.0](https://creativecommons.org/licenses/by-sa/3.0/), если не указано иное. Лицензия и авторские права на активы указаны в файле метаданных. [Пример](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Обратите внимание, что некоторые активы лицензированы под некоммерческой [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) или аналогичной некоммерческой лицензией и должны быть удалены, если вы хотите использовать этот проект в коммерческих целях.