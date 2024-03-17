# Скрипт для ончейн действий в Linea

## Предупреждение
Скрипт делает исключительно ончейн действия, тебе все еще нужно прожать layer3 руками. В целях безопасности я настоятельно не рекомендую использовать браузерные автоматизации (selenium, pyautogui, bas).

## Установка скрипта

### Олдскул
1. `git clone https://github.com/Reilighost/linea_park`
2. `cd linea_park`
3. `pip install -r requirements.txt`
4. `python main.py`

Перед запуском посети `config.py` и настрой там все как считаешь нужным.

## Требования
Скрипту необходимы приватные ключи и прокси в формате `user:pass@ip:port`. Помести их в табличку `data\data.xlsx`. Не забудь установить зависимости.

## Коммиты
К сожалению ты не сможешь клонировать репозиторий, поэтому все свои улучшения оформляй в виде открытого issue. Я обязательно рассмотрю его и добавлю в код. Так же в `staff.py` есть неиспользованные функции (следы моих попыток автоматизировать таски которые остались)
