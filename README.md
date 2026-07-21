# CrewChiefV4_RU

Русский голосовой пакет **SileroEugene** для Crew Chief.

Пакет можно использовать одновременно как:

- **Chief voice** — голос инженера;
- **Spotter voice** — голос споттера;
- **Radio check** — стартовое приветствие при запуске Crew Chief.

## Скачать

Готовый архив находится во вкладке **Releases** этого репозитория.

## Содержимое архива

После распаковки внутри должны быть три папки:

```text
SileroEugene
radio_check_SileroEugene
spotter_SileroEugene
```

## Установка

### 1. Закройте Crew Chief

Перед копированием файлов полностью закройте программу.

### 2. Установите Chief voice

Скопируйте папку:

```text
SileroEugene
```

в:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\alt\
```

Итоговый путь:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\alt\SileroEugene
```

### 3. Установите Spotter voice

Скопируйте папку:

```text
spotter_SileroEugene
```

в:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\
```

Итоговый путь:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\spotter_SileroEugene
```

### 4. Установите Radio check

Скопируйте папку:

```text
radio_check_SileroEugene
```

в:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\
```

Итоговый путь:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\radio_check_SileroEugene
```

### 5. Выберите голоса в Crew Chief

Запустите Crew Chief и выберите:

```text
Chief voice: SileroEugene
Spotter voice: SileroEugene
```

После смены голоса программа может попросить перезапуск интерфейса.

Нажмите **Start** и проверьте:

- русское стартовое приветствие;
- сообщения инженера;
- сообщения споттера: «слева», «справа», «чисто» и другие.

## Обновление

Перед установкой новой версии закройте Crew Chief и удалите старые папки:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\alt\SileroEugene
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\spotter_SileroEugene
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\radio_check_SileroEugene
```

Затем установите новую версию по инструкции выше.

## Удаление

Закройте Crew Chief и удалите:

```text
%LOCALAPPDATA%\CrewChiefV4\Sounds\alt\SileroEugene
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\spotter_SileroEugene
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice\radio_check_SileroEugene
```

## Примечание

Это неофициальный пользовательский русский голосовой пакет для Crew Chief.
