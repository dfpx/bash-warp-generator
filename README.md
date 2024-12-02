# Сгенерируйте конфиг Cloudflare WARP для AmneziaWG
Этот bash скрипт сгенерирует конфиг Cloudflare WARP для AmneziaWG.

Не стоит выполнять его локально, так как РКН заблокировал запросы для получения конфига. Вместо этого лучше выполнять на удалённых серверах.

## Вариант 1: Aeza Terminator
1. Заходим на https://terminator.aeza.net/en/
2. Выбираем **Debian**
3. Вставляем команду:
```bash
bash <(wget -qO- https://raw.githubusercontent.com/dfpx/bash-warp-generator/main/warp_generator.sh)
```
4. После того, как конфиг сгенерируется, копируем его, либо скачиваем файлом по ссылке и импортируем в AmneziaWG!👍

## Что-то не получается?
### После подключении в AmneziaWG ничего не работает, в строке **Передача**: получено 0 Б
К сожалению, AmneziaWG не удалось обойти блокировку WireGuard от вашего провайдера :(
