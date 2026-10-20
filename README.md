# SolScribe

**Free voice dictation and transcription for Windows. Use local speech recognition without a subscription, or choose Groq as a cloud alternative.**

SolScribe turns speech into text for everyday dictation, meeting notes, and audio files. On a capable PC, use **Local** mode: the multilingual Whisper `small` model runs on your computer and is included in the Windows installer. No subscription, account, or API key is needed, and your audio stays on your device. If your PC is slower, **Groq API** is an optional cloud alternative that can do the transcription remotely.

## Download

Get the latest Windows installer from [Releases](https://github.com/allzhukov/SolScribe-Releases/releases/latest). Install SolScribe and launch it from the Start menu. The default interface is English, speech language is detected automatically, and recognition is set to Local.

Windows may show a SmartScreen warning because the app is not code-signed yet. Only download the installer from this repository's Releases page.

## How to use it

### Dictate into any app

1. Click the text field where you want the words to appear.
2. Hold **Right Alt** and speak.
3. Release **Right Alt**. SolScribe transcribes the recording and inserts the text into that field.

If automatic insertion is turned off, the recognized text is copied to the clipboard instead.

### Make a longer dictation

Press **Right Shift + Right Alt** to start recording. Press the same combination again to stop and transcribe. The text goes to the active text field, or to the clipboard when automatic insertion is disabled.

### Transcribe a meeting

Choose **Record meeting** to capture microphone and computer audio. Choose **Finish and save transcript** to stop. The transcript is saved as a text file in:

`%LOCALAPPDATA%\DictateLocal\Transcriptions`

Tell meeting participants that the meeting is being recorded and follow your local consent rules.

### Transcribe an audio file

Choose **Transcribe audio file**, select a file, and wait for processing. SolScribe supports WAV, MP3, M4A, MP4, MPEG, MPGA, OGG, WebM, and FLAC. The transcript is saved in the same `Transcriptions` folder.

## Choose how speech is recognized

- **Local** is a good choice if your PC handles Whisper comfortably or you want to keep recordings on your device. It needs no subscription, Groq account, or API key. Processing speed depends on your hardware.
- **Groq API** is a convenient alternative for a slower PC or when you prefer cloud processing. Groq currently offers free API limits that may be enough for occasional, basic use, depending on the account and model. Limits can change or be reached, so check [Groq's current limits](https://console.groq.com/settings/limits). You need a Groq account and API key; when Groq is selected, audio is sent to Groq for transcription. [Create a Groq API key](https://console.groq.com/keys).

Local transcription does not depend on Groq and remains available without a cloud account or subscription.

## Updates

SolScribe checks this repository for new releases and offers an update when one is available. Your settings and transcripts stay in your Windows user data folder when you update.

---

# SolScribe українською

**Безкоштовне голосове введення та транскрибування для Windows. Можна розпізнавати мовлення локально без підписки або вибрати Groq як хмарну альтернативу.**

SolScribe перетворює мовлення на текст для диктування, нотаток із мітингів та аудіофайлів. На комп’ютері, який добре справляється з Whisper, обирай режим **Локально**: багатомовна модель Whisper `small` працює на твоєму ПК і входить до інсталятора. Підписка, акаунт чи API-ключ не потрібні, аудіо залишається на пристрої. Якщо комп’ютер повільний, можна вибрати **Groq API** — хмарний режим, де розпізнавання виконується віддалено.

## Завантаження

Завантаж останній інсталятор Windows зі сторінки [Releases](https://github.com/allzhukov/SolScribe-Releases/releases/latest), встанови застосунок і запусти його з меню «Пуск». Спочатку інтерфейс буде англійською, мова мовлення визначатиметься автоматично, а розпізнавання працюватиме локально.

Windows може показати попередження SmartScreen, оскільки застосунок поки не має цифрового підпису. Завантажуй інсталятор лише зі сторінки Releases цього репозиторію.

## Як користуватися

### Диктування в будь-який застосунок

1. Клацни в текстове поле, куди треба вставити текст.
2. Затисни **Right Alt** і говори.
3. Відпусти **Right Alt**. SolScribe розпізнає запис і вставить текст у вибране поле.

Якщо автоматичну вставку вимкнено, розпізнаний текст потрапить у буфер обміну.

### Довге диктування

Натисни **Right Shift + Right Alt**, щоб почати запис. Натисни цю комбінацію ще раз, щоб зупинити запис і розпізнати мовлення. Текст буде вставлено в активне поле або скопійовано в буфер обміну, якщо автоматичну вставку вимкнено.

### Транскрипція мітингу

Натисни **Записати мітинг**, щоб записати мікрофон і звук комп’ютера. Натисни **Завершити й зберегти транскрипт**, щоб зупинити запис. Текстовий транскрипт буде збережено тут:

`%LOCALAPPDATA%\DictateLocal\Transcriptions`

Повідом учасників про запис і дотримуйся місцевих правил отримання згоди.

### Транскрипція аудіофайлу

Натисни **Транскрибувати аудіофайл**, вибери файл і дочекайся завершення. Підтримуються WAV, MP3, M4A, MP4, MPEG, MPGA, OGG, WebM і FLAC. Транскрипт буде в тій самій папці `Transcriptions`.

## Який режим розпізнавання обрати

- **Локально** — зручний вибір, якщо твій ПК нормально працює з Whisper або важливо, щоб записи не залишали пристрій. Підписка, акаунт Groq і API-ключ не потрібні. Швидкість залежить від комп’ютера.
- **Groq API** — зручна альтернатива для повільнішого ПК або якщо тобі зручніше обробляти звук у хмарі. Groq зараз пропонує безкоштовні ліміти API, яких може вистачити для базового чи нерегулярного використання — залежно від акаунта й моделі. Ліміти можуть змінюватися або вичерпуватися, тому перевіряй [актуальні ліміти Groq](https://console.groq.com/settings/limits). Потрібні акаунт Groq та API-ключ; у цьому режимі аудіо надсилається до Groq. [Створи API-ключ Groq](https://console.groq.com/keys).

Локальна транскрипція не залежить від Groq і доступна без хмарного акаунта чи підписки.

## Оновлення

SolScribe перевіряє цей репозиторій на наявність нових версій і пропонує оновитися. Під час оновлення налаштування й транскрипти залишаються у твоїй папці даних Windows.
