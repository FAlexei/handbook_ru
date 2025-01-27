---
Title: Установка Vanilla OS
Description: Узнайте, как установить Vanilla OS на свое устройство.
PublicationDate: 2023-11-11
Authors:
    - kra-mo
    - kbdharun
    - FAlexei
---

## Подготовка

### Требования для установки

- Флэш-накопитель емкостью не менее **8 Гб**.
- 64-разрядный (amd64) [x64] процессор.
- Диск с объемом памяти не менее **50 Гб** (требуется для разделов [ABRoot](https://documentation.vanillaos.org/docs/ABRoot/)).
- Не менее **4 ГБ** оперативной памяти** (рекомендуется **8 ГБ**).
- От 30 минут до часа вашего времени.
- Желательно включить **Secure Boot**.

### Создание загрузочного USB-носителя

В этом разделе мы расскажем о том, как создать загрузочный USB-накопитель с Vanilla OS.

#### Загрузка Vanilla OS

Сначала [**загрузите образ диска**](https://vanillaos.org/) с Vanilla OS, который будет записан на USB-накопитель.

#### Установка Etcher

Чтобы записать образ диска на USB-накопитель, скачайте и установите [**balenaEtcher**](https://www.balena.io/etcher/).

При желании можно использовать и другое знакомое Вам программное обеспечение, например [**Ventoy**](https://www.ventoy.net/) или [**Rufus**](https://rufus.ie/).

#### Запись образа

**Предупреждение**: при этом будут удалены **все данные** на USB-накопителе. Перед выполнением операции обязательно создайте резервную копию важных данных!

Откройте Etcher, выберите загруженный образ диска и Ваш USB-накопитель, затем нажмите кнопку "Flash!".

![Запись образа](/assets/uploads/Installation/installation-flashing.webp)

По окончании процесса вы получите загрузочный USB-носитель с операционной системой Vanilla OS на нем.

### Загрузка с флэш-накопителя USB

Вставьте USB-накопитель в компьютер, на который вы хотите установить Vanilla OS, и включите или перезагрузите устройство.

Если устройство не загружается автоматически с установочного носителя Vanilla OS, перезагрузите его и во время запуска удерживайте нажатой клавишу `выбора загрузочного устройства` или `меню загрузки`, на что указывает подсказка на экране загрузки. Наиболее распространенными клавишами являются F2, F10, F11, F12, Delete и Escape. Если подсказка отсутствует, попробуйте выполнить поиск в Интернете для конкретной модели. В загрузочном меню выберите Vanilla OS или имя USB-накопителя.

После успешной загрузки устройства с USB-накопителя должно появиться окно приветствия, предлагающее попробовать или установить Vanilla OS.

![Приветствие](/assets/uploads/Installation/installer-welcome.webp)

Вы можете опробовать Vanilla OS, не внося никаких изменений в устройство. Если вы удовлетворены, можно снова открыть программу установки (первый значок в Доке) и продолжить установку.

## Установка Vanilla OS

### Первые шаги

Нажмите кнопку "Установить Vanilla OS" и установите предпочтительный язык, раскладку клавиатуры и часовой пояс.

### Типы установки

В зависимости от того, хотите ли вы выполнить двойную или мультизагрузку Vanilla OS наряду с другими операционными системами, вам потребуется выполнить различные шаги при выборе диска.

Данное руководство поможет вам при выполнении следующих типов установки:

- [Установка только Vanilla OS](/2022/11/05/installation.html#title10)
- [~~Дополнительная установка~~ (в настоящее время отключена)](/2022/11/05/installation.html#title11)

### Установка только Vanilla OS

В этом разделе мы рассмотрим процесс установки Vanilla OS на весь диск, **удалив все прошлые данные на нем**. Перед началом работы обязательно сделайте резервную копию всех важных данных!

Выберите диск, на который будет установлена Vanilla OS, нажмите "Настроить", выберите "Использовать весь диск", нажмите "Применить" и просмотрите изменения.

![Использовать весь диск](/assets/uploads/Installation/installation-partitioning.webp)

Создайте учетную запись пользователя и ознакомьтесь с изменениями, которые будут внесены в систему. Нажмите кнопку "Установить Vanilla OS", и начнется установка.

![Подтверждение установки](/assets/uploads/Installation/installer-confirm-installation.webp)

## Загрузка в Vanilla OS

### Если у вас установлена только Vanilla OS

После завершения работы программы установки достаточно перезагрузиться и извлечь USB-накопитель. Vanilla OS будет ждать Вас.

### При двойной или мультизагрузке

#### На одном диске

После завершения работы программы установки достаточно перезагрузиться, и на экране появится меню загрузки с установленными операционными системами. Выберите Vanilla OS, дождитесь ее загрузки и извлеките USB-накопитель.

#### На разных дисках

После завершения работы программы установки необходимо перезагрузиться и выбрать Vanilla OS из загрузочного меню устройства, доступ к которому можно получить, удерживая нажатой определенную клавишу во время запуска устройства, о чем свидетельствует подсказка на загрузочном экране. Если подсказки нет, попробуйте поискать ее в Интернете для конкретной модели. Войдя в Vanilla OS, извлеките USB-накопитель.

Порядок загрузки по умолчанию можно настроить в параметрах встроенного ПО устройства.

## Первоначальная настройка

После установки Vanilla OS для настройки системы можно следовать руководству [**по первоначальной настройке**](/2022/11/18/first-setup.html).
