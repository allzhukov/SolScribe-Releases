# SolScribe

**Free voice dictation and transcription for Windows. Run speech recognition on your own computer, without a paid transcription subscription.**

SolScribe turns speech into text for everyday dictation, meeting notes, and audio files. Its default **Local** mode runs the multilingual Whisper `small` model on your PC. The model is included in the Windows installer, so local transcription does not require a subscription, an account, an API key, or uploading your audio to a transcription service.

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

## Local and Groq recognition

- **Local** is the recommended starting point. Audio is processed on your PC and does not leave it for transcription. There is no subscription or API key. Speed depends on your computer.
- **Groq API** is an optional cloud provider. When selected, audio is sent to Groq; its account terms, pricing, and usage limits apply. You do not need Groq to use SolScribe locally.

## Updates

SolScribe checks this repository for new releases and offers an update when one is available. Your settings and transcripts stay in your Windows user data folder when you update.

---

# SolScribe українською

**Безкоштовне голосове введення та транскрибування для Windows. Розпізнавання працює на твоєму комп’ютері — без платної підписки на сервіс транскрипції.**

SolScribe перетворює мовлення на текст для диктування, нотаток із мітингів та аудіофайлів. За замовчуванням використовується режим **Локально**: багатомовна модель Whisper `small` запускається на твоєму ПК. Модель входить до інсталятора, тому локальне розпізнавання не потребує підписки, акаунта, API-ключа чи надсилання аудіо до сервісу транскрипції.

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

## Локальне розпізнавання та Groq

- **Локально** — рекомендований режим. Аудіо обробляється на твоєму ПК і не надсилається для транскрипції в інтернет. Підписка й API-ключ не потрібні. Швидкість залежить від комп’ютера.
- **Groq API** — необов’язковий хмарний сервіс. Якщо його вибрати, аудіо надсилається до Groq; діють умови, тарифи та ліміти цього сервісу. Для локального користування SolScribe Groq не потрібен.

## Оновлення

SolScribe перевіряє цей репозиторій на наявність нових версій і пропонує оновитися. Під час оновлення налаштування й транскрипти залишаються у твоїй папці даних Windows.
