# История изменений

Все заметные изменения в этом проекте будут документироваться в этом файле. См. [конventional commits](https://www.conventionalcommits.org/) для получения информации о правилах коммитов.

---

## [1.7.0](https://github.com/mumu-lhl/Ciyue/compare/v1.7.0-beta.1..v1.7.0) - 2025-03-23

### Исправления ошибок

- Обновление меток перевода для локализации - ([09ee403](https://github.com/mumu-lhl/Ciyue/commit/09ee403dc3a497e27cb6dc22548bbd5f15255d9c)) - Mumulhl
- Пустой экран при редактировании псевдонима названия отключенного словаря - ([95f41b0](https://github.com/mumu-lhl/Ciyue/commit/95f41b01493d96e55211a9f459ceac65a1079543)) - Mumulhl
- Исправление ошибок при импорте - ([f002509](https://github.com/mumu-lhl/Ciyue/commit/f0025095466ec864a65bf452c5aae76300dbce4d)) - Mumulhl
- Обновление ярлыков языков и настройки AI Explain - ([324383b](https://github.com/mumu-lhl/Ciyue/commit/324383bdae2e2e3296c648079de77e10c605b965)) - Mumulhl

### Документация

- Добавление徽章 GitHub в раздел установки в файлах README - ([5f713f7](https://github.com/mumu-lhl/Ciyue/commit/5f713f71a9d9dba6e609e0a0ab285837aebb7ee5)) - Mumulhl
- Добавление функции AI translate в README - ([d833b18](https://github.com/mumu-lhl/Ciyue/commit/d833b1818088f535ed0553929ef231c55451aa27)) - Mumulhl
- Обновление README для уточнения поддержки MDX/MDD на Linux - ([f91bf20](https://github.com/mumu-lhl/Ciyue/commit/f91bf20aba54661159fc0dc076c2c483bd3cb14e)) - Mumulhl
- Добавление Политики конфиденциальности, Условий и免责声明 в документацию - ([520b896](https://github.com/mumu-lhl/Ciyue/commit/520b8963a502d9c9883b91db7303758c93b94bf9)) - Mumulhl
- Обновление скриншотов - ([3940bcb](https://github.com/mumu-lhl/Ciyue/commit/3940bcb469d08405bde9f355f435c5187edc7a98)) - Mumulhl

### Функции

- **(AIExplain)** Динамическое задание языка вывода на основе настроек пользователя - ([af088e5](https://github.com/mumu-lhl/Ciyue/commit/af088e5c61b8559cc479881adbb61c4bae424711)) - Mumulhl
- **(l10n)** Добавление обновлений переводов для нескольких языков - ([bc1c281](https://github.com/mumu-lhl/Ciyue/commit/bc1c281ba8288e06bc5489747f3432d8acb2c87e)) - Mumulhl
- **(translation)** Переведено с использованием Weblate (English) - ([cc79d77](https://github.com/mumu-lhl/Ciyue/commit/cc79d773b3117fc6fd2bbe09fb50eb75ce371047)) - Allan Nordhøy
- Разрешение многострочного ввода для перевода текста - ([d561011](https://github.com/mumu-lhl/Ciyue/commit/d5610113a1e9513d9a5d0d50f97e062a4216a875)) - Mumulhl
- Сделать виджет markdown прокручиваемым - ([45e3184](https://github.com/mumu-lhl/Ciyue/commit/45e31846e5b23f8cd4125c330950ebc6596330dd)) - Mumulhl
- Добавление заголовков для Политики конфиденциальности и Условий использования - ([0c5bcae](https://github.com/mumu-lhl/Ciyue/commit/0c5bcaebb37289a311c7aaea0acda761a2d92b55)) - Mumulhl
- Включение объяснения слова - ([8e455bd](https://github.com/mumu-lhl/Ciyue/commit/8e455bdf1e0005bce96846f7ffe6c58b96b4c30c)) - Mumulhl
- Скрытие вкладки при наличии только одного словаря - ([e4cd0e0](https://github.com/mumu-lhl/Ciyue/commit/e4cd0e0602c8d4298f22d3ef3320669b0e545a1f)) - Mumulhl
- Добавление функции AI Explain Word - ([90d9416](https://github.com/mumu-lhl/Ciyue/commit/90d9416bc1296714333fbb40e61bb9c5605c4609)) - Mumulhl
- Добавление функции проверки обновлений в настройках - ([f0a0183](https://github.com/mumu-lhl/Ciyue/commit/f0a0183975e85f6648efa8d52320ce6b06648b85)) - Mumulhl
- Добавление опции включения предварительных релизов обновлений в настройках - ([2c25149](https://github.com/mumu-lhl/Ciyue/commit/2c25149ee577af574371339902bc82c289334dc7)) - Mumulhl

### Разнообразные хлопоты

- **(deps)** Обновление flutter_local_notifications с 18.0.1 до 19.0.0 - ([e6a9364](https://github.com/mumu-lhl/Ciyue/commit/e6a936466d95f01cbb3e9b1a8ffd9ededa191ca0)) - dependabot[bot]
- **(deps)** Замена flutter_markdown на gpt_markdown - ([717feef](https://github.com/mumu-lhl/Ciyue/commit/717feef68e970994a7473910fe556141814acdf2)) - Mumulhl
- Добавление flutter_local_notifications_windows в список FFI плагинов - ([0a62e7c](https://github.com/mumu-lhl/Ciyue/commit/0a62e7c6674f28046a16a4186be34d3b95c11fe5)) - Mumulhl
- Обновление описания пакета для включения поддержки Windows/Linux - ([b0ecb0b](https://github.com/mumu-lhl/Ciyue/commit/b0ecb0b85cf102343ff423814e6a124db753e816)) - Mumulhl

### Рефакторинг

- Сохранение состояния AiTranslatePage - ([cfee517](https://github.com/mumu-lhl/Ciyue/commit/cfee517abedb193ebebfd881523ba7c757d0e43e)) - Mumulhl
- Обновление обработки ввода для использования TextEditingController для перевода - ([321ef49](https://github.com/mumu-lhl/Ciyue/commit/321ef49dcf472247e540058716b09cc477a48e4c)) - Mumulhl
- Перемещение объявления переменной _isRichOutput в уровень выше - ([23b44b1](https://github.com/mumu-lhl/Ciyue/commit/23b44b1272153a44989c1a22b58d7398064d5069)) - Mumulhl

### Стиль

- Форматирование кода - ([c1d93e0](https://github.com/mumu-lhl/Ciyue/commit/c1d93e0c2f1ad8f3befa1aea6a228ef1f8523688)) - Mumulhl

---

## [1.7.0-beta.1](https://github.com/mumu-lhl/Ciyue/compare/v1.6.0..v1.7.0-beta.1) - 2025-03-16

### Исправления ошибок

- Открытие политики конфиденциальности - ([f8b488f](https://github.com/mumu-lhl/Ciyue/commit/f8b488f89827111f8dc2899ff8aa9674c2f8f77b)) - Mumulhl
- Исправление имени модели - ([0f0cc48](https://github.com/mumu-lhl/Ciyue/commit/0f0cc481477971ec8a00a4154d885113e92365a1)) - Mumulhl

### Документация

- Обновление информации о многоплатформенной поддержке в README - ([89c6b38](https://github.com/mumu-lhl/Ciyue/commit/89c6b38ac23ee6ea2556200868a5931c0372f913)) - Mumulhl

### Функции

- **(l10n)** Добавление автоматического определения - ([a015c4c](https://github.com/mumu-lhl/Ciyue/commit/a015c4c73aa98fc44e1ce1462fbd1d28d6bb03c1)) - Mumulhl
- **(l10n)** Добавление нового перевода - ([26bfa79](https://github.com/mumu-lhl/Ciyue/commit/26bfa796384fb3f90d4d39c6032b3dff739ec69b)) - Mumulhl
- **(translation)** Переведено с использованием Weblate (Chinese (Traditional Han script)) - ([5a51678](https://github.com/mumu-lhl/Ciyue/commit/5a51678e51757bfc1396bd7d495c257a60d0ed6d)) - plum7x
- **(translation)** Переведено с использованием Weblate (English) - ([d93a5f0](https://github.com/mumu-lhl/Ciyue/commit/d93a5f0bc90dc8c01398162ebd88f1f355047080)) - Integral
- **(translation)** Переведено с использованием Weblate (Chinese (Simplified Han script)) - ([b3e7706](https://github.com/mumu-lhl/Ciyue/commit/b3e770675d3f508dd57a0737728fbb5d2cd2a312)) - Integral
- **(translation)** Переведено с использованием Weblate (Chinese (Traditional Han script, Hong Kong)) - ([d0f5042](https://github.com/mumu-lhl/Ciyue/commit/d0f50420adf8fb1aa448157f91baf42290c38818)) - Integral
- **(translation)** Переведено с использованием Weblate (Norwegian Bokmål) - ([6b3044f](https://github.com/mumu-lhl/Ciyue/commit/6b3044fd1ff4f3dc26bc403b974d407154467c8a)) - Integral
- **(translation)** Переведено с использованием Weblate (Russian) - ([7bdfde2](https://github.com/mumu-lhl/Ciyue/commit/7bdfde2819f2c362b2bf6dccfc54e9cf722e689d)) - Integral
- **(translation)** Переведено с использованием Weblate (Sardinian) - ([835dbca](https://github.com/mumu-lhl/Ciyue/commit/835dbcab468527280b53ecba9fba6c99d9afd5c1)) - Integral
- **(translation)** Переведено с использованием Weblate (Tamil) - ([741f7ea](https://github.com/mumu-lhl/Ciyue/commit/741f7ea0dceb5389372b5ce8041fe4e1360aafbf)) - Integral
- **(translation)** Переведено с использованием Weblate (Persian) - ([2ddabc4](https://github.com/mumu-lhl/Ciyue/commit/2ddabc4c11a8b4e44f366d0ada8da5a48ba1d533)) - Integral
- **(translation)** Переведено с использованием Weblate (German) - ([48eb51d](https://github.com/mumu-lhl/Ciyue/commit/48eb51d86215ca9c1b259672dbdde58a90c48968)) - Integral
- Добавление страницы настроек AI - ([971c6ea](https://github.com/mumu-lhl/Ciyue/commit/971c6ea375e4d6fa56ef1736b8d7d09ceb5885af)) - Mumulhl
- Реализация конфигурации AI - ([2d00106](https://github.com/mumu-lhl/Ciyue/commit/2d0010653417d777a482e9916a05c758ee498544)) - Mumulhl
- Улучшение выбора модели AI с подробной информацией о модели - ([e74f3ac](https://github.com/mumu-lhl/Ciyue/commit/e74f3ac4b72cb40e253ac67df708348b80f5c356)) - Mumulhl
- Добавление настроек для объяснения слова AI - ([605497a](https://github.com/mumu-lhl/Ciyue/commit/605497a5f0701140cdafe1f305ab6d8650d170df)) - Mumulhl
- Реализация классов поставщиков AI для OpenAI и Gemini API - ([ff31cf5](https://github.com/mumu-lhl/Ciyue/commit/ff31cf529889e7b538e9feead2cd3b43b1d2efe1)) - Mumulhl
- Обновление поставщика OpenAI для поддержки совместимого URL API и переименования класса - ([36ddcc3](https://github.com/mumu-lhl/Ciyue/commit/36ddcc32a8ca7636e170c072653d10d413e54353)) - Mumulhl
- Добавление функции перевода AI - ([908b767](https://github.com/mumu-lhl/Ciyue/commit/908b767b4b7d2b1a72ff2dcb80df6287dbc13d54)) - Mumulhl
- Добавление Политики конфиденциальности - ([6e7e3fa](https://github.com/mumu-lhl/Ciyue/commit/6e7e3fa9cddb69caec1842944ef442881b3784b9)) - Mumulhl
- Добавление синтетической конфигурации в l10n.yaml - ([5c5dd50](https://github.com/mumu-lhl/Ciyue/commit/5c5dd50f2440059e1ec454d5a5cd11669bcc1c80)) - Mumulhl
- Добавление Условий использования - ([5e4b282](https://github.com/mumu-lhl/Ciyue/commit/5e4b28217fcf5827318f4f000c71864d1de7ec49)) - Mumulhl
- Добавление更多языковой поддержки в Translate - ([35189a1](https://github.com/mumu-lhl/Ciyue/commit/35189a19b7443f408cb4a6e6bdd616df405ae049)) - Mumulhl
- Поддержка Deepseek - ([52984b2](https://github.com/mumu-lhl/Ciyue/commit/52984b280a2d072d9fd740d791f970b9369979c2)) - Mumulhl
- Поддержка Authropic - ([c3f5419](https://github.com/mumu-lhl/Ciyue/commit/c3f5419dc5326490794ef5eadb255d4559caaea0)) - Mumulhl

### Разнообразные хлопоты

- **(ci)** Добавление Builds Linux в workflow - ([a7754e6](https://github.com/mumu-lhl/Ciyue/commit/a7754e69f4cc075c27db4632a768b8ec9677028d)) - Integral
- **(ci)** Обновление версии Flutter - ([b51d946](https://github.com/mumu-lhl/Ciyue/commit/b51d946ef5ffb77f20958e555a6df99ed7bfc9d3)) - Mumulhl
- **(ci)** Исправление ci - ([b9bff36](https://github.com/mumu-lhl/Ciyue/commit/b9bff36790ab6b416fe8afa44f4e6df8c15ef54e)) - Mumulhl
- **(ci)** Удаление избыточных шагов генерации локализации из workflow - ([cad997d](https://github.com/mumu-lhl/Ciyue/commit/cad997dc7bd0b461f0a428348de4f0cba8e601bf)) - Mumulhl
- **(ci)** Исправление ci - ([e7bf648](https://github.com/mumu-lhl/Ciyue/commit/e7bf648a0e74f5c62e115a8af636219c7bdc6c65)) - Mumulhl
- **(deps)** Обновление drift с 2.25.1 до 2.26.0 - ([0616e0d](https://github.com/mumu-lhl/Ciyue/commit/0616e0d537b9b7b6d90ccb74db89ce5c4b0b12d5)) - dependabot[bot]
- Обновление версий пакетов и SHA256 контрольных сумм в pubspec.lock - ([5f7b305](https://github.com/mumu-lhl/Ciyue/commit/5f7b305f1da4e9e20a8f2b0d80d6499cc43283de)) - Mumulhl
- Обновление pubspec.lock и l10n - ([d3a1c69](https://github.com/mumu-lhl/Ciyue/commit/d3a1c69d33d2cc1096f5e4cd568c3a2078e3de95)) - Mumulhl
- Добавление сгенерированных файлов в .gitignore - ([b67670b](https://github.com/mumu-lhl/Ciyue/commit/b67670b6e66c398f31bbfd958c7380c3df3efcc7)) - Mumulhl

### Рефакторинг

- **(ui)** Улучшение макета страницы политики конфиденциальности для лучшей читаемости - ([ad1b4a9](https://github.com/mumu-lhl/Ciyue/commit/ad1b4a9ed71183df8b3ff4a14b0b2c37e0f1d90b)) - Mumulhl
- **(ui)** Центрирование и ограничение макета страницы AI Translate для улучшения презентации - ([02d40b0](https://github.com/mumu-lhl/Ciyue/commit/02d40b0478fe84a21418b7d855d88f88f2fc662c)) - Mumulhl
- Перемещение файлов в директорию settings - ([c862c7d](https://github.com/mumu-lhl/Ciyue/commit/c862c7d66130daedb6b803ff4aa6770025cc9d2c)) - Mumulhl
- Обновление-default model в конфигурации AI provider - ([cb1eb04](https://github.com/mumu-lhl/Ciyue/commit/cb1eb045dfa0bfbe10caa6018a01b01ea8497ff4)) - Mumulhl
- Рефакторинг инициализации AI provider и языков перевода - ([c8d5216](https://github.com/mumu-lhl/Ciyue/commit/c8d5216a448a933bc44b8f544b66951838a6724b)) - Mumulhl
- Отключение переключателя AI Explain Word - ([b548366](https://github.com/mumu-lhl/Ciyue/commit/b54836622888411716c85176bba7f185ad99c31a)) - Mumulhl

### Стиль

- Форматирование кода - ([f672327](https://github.com/mumu-lhl/Ciyue/commit/f672327356f6130e31a7a30a36346872263ff2bc)) - Mumulhl
- Форматирование кода - ([f0ef90e](https://github.com/mumu-lhl/Ciyue/commit/f0ef90ecd0340de70e454a6ece789d0fcd56a31f)) - Mumulhl
- Форматирование кода - ([e16b801](https://github.com/mumu-lhl/Ciyue/commit/e16b801090e9a05813d62552b7660860957b2d07)) - Mumulhl

---

## [1.6.0](https://github.com/mumu-lhl/Ciyue/compare/v1.5.0..v1.6.0) - 2025-03-09

### Исправления ошибок

- Исправление даты слова в wordbook - ([382d01d](https://github.com/mumu-lhl/Ciyue/commit/382d01d3bf2192e7946a49e18f3af73b8dcf5a55)) - Mumulhl
- Фильтрация дублирующихся результатов поиска - ([dcb6a1c](https://github.com/mumu-lhl/Ciyue/commit/dcb6a1ceead81de7a012cab001df8b4ee70cf460)) - Mumulhl
- Исправление Sardinian - ([6595f51](https://github.com/mumu-lhl/Ciyue/commit/6595f51dbd490f9e89a45193c7e8c8ec00c47f48)) - Mumulhl

### Разнообразные хлопоты

- **(deps)** Обновление path с 1.9.0 до 1.9.1 - ([2c63401](https://github
