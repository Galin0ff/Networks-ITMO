# Задание 1:
1. Примените утилиты ping, netstat, traceroute, nslookup для сбора данных о сетевых подключениях.
2. Запишите результаты каждой команды в файл формата markdown.
3. Создайте отчет, в котором объясните функционал каждой утилиты и вставите результат выполнения команд.

## PING - проверяет сетевое подключение.

Обмен пакетами с ya.ru [5.255.255.242] с 32 байтами данных:
Ответ от 5.255.255.242: число байт=32 время=11мс TTL=54
Ответ от 5.255.255.242: число байт=32 время=11мс TTL=54
Ответ от 5.255.255.242: число байт=32 время=11мс TTL=54
Ответ от 5.255.255.242: число байт=32 время=11мс TTL=54

Статистика Ping для 5.255.255.242:
    Пакетов: отправлено = 4, получено = 4, потеряно = 0
    (0% потерь)
Приблизительное время приема-передачи в мс:
    Минимальное = 11мсек, Максимальное = 11 мсек, Среднее = 11 мсек

## NETSTAT - тображает активные TCP-подключения, порты, на которых компьютер прослушивает статистику.

  Имя    Локальный адрес        Внешний адрес          Состояние
  TCP    127.0.0.1:27060        KOMPUTER:60667         ESTABLISHED
  TCP    127.0.0.1:60607        KOMPUTER:60613         ESTABLISHED
  TCP    127.0.0.1:60609        KOMPUTER:60612         ESTABLISHED
  TCP    127.0.0.1:60612        KOMPUTER:60609         ESTABLISHED
  TCP    127.0.0.1:60613        KOMPUTER:60607         ESTABLISHED
  TCP    127.0.0.1:60667        KOMPUTER:27060         ESTABLISHED
  TCP    127.0.0.1:61383        KOMPUTER:61384         ESTABLISHED
  TCP    127.0.0.1:61384        KOMPUTER:61383         ESTABLISHED
  TCP    192.168.168.103:49676  20.54.36.229:https     ESTABLISHED
  TCP    192.168.168.103:49716  lk-in-f188:5228        ESTABLISHED
  TCP    192.168.168.103:50263  api:https              ESTABLISHED
  TCP    192.168.168.103:50332  yandex:https           ESTABLISHED
  TCP    192.168.168.103:50345  yandex:https           ESTABLISHED
  TCP    192.168.168.103:50470  yandex:https           ESTABLISHED
  TCP    192.168.168.103:50475  api:https              ESTABLISHED
  TCP    192.168.168.103:51627  music:https            ESTABLISHED
  TCP    192.168.168.103:52576  149.154.167.41:https   ESTABLISHED
  TCP    192.168.168.103:54466  yandex:https           ESTABLISHED
  TCP    192.168.168.103:55480  ya:https               ESTABLISHED
  TCP    192.168.168.103:55482  yandex:https           ESTABLISHED
  TCP    192.168.168.103:56403  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:58019  yandex:https           ESTABLISHED
  TCP    192.168.168.103:60622  162-254-197-54:27030   ESTABLISHED
  TCP    192.168.168.103:60908  mc:https               ESTABLISHED
  TCP    192.168.168.103:61034  104.19.155.82:https    ESTABLISHED
  TCP    192.168.168.103:61062  162.159.128.235:https  TIME_WAIT
  TCP    192.168.168.103:61099  172.67.69.234:https    ESTABLISHED
  TCP    192.168.168.103:61258  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:61380  170.114.52.2:https     CLOSE_WAIT
  TCP    192.168.168.103:61381  170.114.52.2:https     CLOSE_WAIT
  TCP    192.168.168.103:61382  170.114.52.2:https     CLOSE_WAIT
  TCP    192.168.168.103:61388  159-124-8-132:https    ESTABLISHED
  TCP    192.168.168.103:61389  159-124-8-132:https    ESTABLISHED
  TCP    192.168.168.103:61397  xiva-daria:https       ESTABLISHED
  TCP    192.168.168.103:61404  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:61892  139.45.207.41:https    CLOSE_WAIT
  TCP    192.168.168.103:61893  a104-68-66-114:https   CLOSE_WAIT
  TCP    192.168.168.103:62345  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:62346  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:62347  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:62408  yabs:https             ESTABLISHED
  TCP    192.168.168.103:62565  ec2-35-174-127-31:https  ESTABLISHED
  TCP    192.168.168.103:62962  srv6-237-186-93:https  ESTABLISHED
  TCP    192.168.168.103:63008  srv90-190-240-87:https  ESTABLISHED
  TCP    192.168.168.103:63131  api:https              ESTABLISHED
  TCP    192.168.168.103:63152  api:https              ESTABLISHED
  TCP    192.168.168.103:63156  api:https              ESTABLISHED
  TCP    192.168.168.103:63236  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:63237  91.105.192.100:http    ESTABLISHED
  TCP    192.168.168.103:63260  188.114.97.1:https     ESTABLISHED
  TCP    192.168.168.103:63277  162.159.136.234:https  TIME_WAIT
  TCP    192.168.168.103:63430  lb-140-82-114-25-iad:https  ESTABLISHED
  TCP    192.168.168.103:63434  104.19.155.82:https    ESTABLISHED
  TCP    192.168.168.103:63438  168:https              TIME_WAIT
  TCP    192.168.168.103:63491  149.154.167.51:https   ESTABLISHED
  TCP    192.168.168.103:63499  srv164-137-240-87:https  ESTABLISHED
  TCP    192.168.168.103:63514  91.105.192.100:https   ESTABLISHED
  TCP    192.168.168.103:63516  162.159.135.232:https  TIME_WAIT
  TCP    192.168.168.103:63517  149.154.167.223:https  TIME_WAIT
  TCP    192.168.168.103:63518  149.154.167.223:http   TIME_WAIT
  TCP    192.168.168.103:63526  li-in-f18:https        ESTABLISHED
  TCP    192.168.168.103:63530  a2-16-21-9:http        TIME_WAIT
  TCP    192.168.168.103:63531  a2-16-21-9:http        TIME_WAIT
  TCP    192.168.168.103:63532  a2-16-21-9:http        TIME_WAIT
  TCP    192.168.168.103:63533  a2-16-21-9:http        TIME_WAIT
  TCP    192.168.168.103:63534  a2-16-21-9:http        TIME_WAIT
  TCP    192.168.168.103:63539  149.154.167.223:https  TIME_WAIT
  TCP    192.168.168.103:63540  149.154.167.223:https  TIME_WAIT
  TCP    192.168.168.103:63541  149.154.167.223:http   TIME_WAIT
  TCP    192.168.168.103:63542  149.154.167.223:http   TIME_WAIT
  TCP    192.168.168.103:63543  91.105.192.100:https   ESTABLISHED
  TCP    192.168.168.103:63544  91.105.192.100:http    TIME_WAIT
  TCP    192.168.168.103:63545  api:https              ESTABLISHED
  TCP    192.168.168.103:63549  static:https           ESTABLISHED
  TCP    192.168.168.103:63550  13.107.5.93:https      ESTABLISHED
  TCP    192.168.168.103:63551  152.199.19.160:https   ESTABLISHED
  TCP    192.168.168.103:63552  13.107.213.53:https    ESTABLISHED
  TCP    192.168.168.103:63553  104.46.162.226:https   ESTABLISHED
  TCP    192.168.168.103:63554  104.46.162.226:https   ESTABLISHED
  TCP    192.168.168.103:63556  91.105.192.100:https   ESTABLISHED
  TCP    192.168.168.103:63557  91.105.192.100:http    TIME_WAIT
  TCP    192.168.168.103:63558  storage:https          ESTABLISHED
  TCP    192.168.168.103:63559  91.105.192.100:https   ESTABLISHED
  TCP    192.168.168.103:63561  104.19.155.82:https    ESTABLISHED
  TCP    192.168.168.103:63562  104.19.155.82:https    ESTABLISHED


## NSLOOKUP - применяется для выполнения DNS-запросов и получения сведений о доменных именах или IP-адресах.

C:\Users\Great>nslookup
╤хЁтхЁ яю єьюыўрэш■:  UnKnown
Address:  192.168.168.1