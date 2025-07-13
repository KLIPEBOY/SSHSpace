# SSHSpace

**SSHSpace** — кроссплатформенный SSH/SFTP клиент с космическим sci-fi интерфейсом, файловым менеджером и терминалом в реальном времени. Работает на Windows, macOS, Linux, Web, Android, iOS. Основан на Flutter.

---

## 🚀 Описание (Русский)
- Современный минималистичный интерфейс в стиле sci-fi/cyberpunk
- Поддержка SSH и SFTP (управление файлами, терминал)
- Анимированный вход с космонавтом и терминалом
- Кастомные иконки, плавные анимации, поддержка drag-and-drop
- Адаптивный дизайн для десктопа и мобильных устройств

### Как запустить
1. Установите [Flutter](https://flutter.dev/docs/get-started/install)
2. Клонируйте репозиторий:
   ```sh
   git clone <repo_url>
   cd sshgogo_app/lib/flutter_app
   ```
3. Установите зависимости:
   ```sh
   flutter pub get
   ```
4. Запустите на нужной платформе:
   - **Windows:** `flutter run -d windows`
   - **macOS:** `flutter run -d macos`
   - **Linux:** `flutter run -d linux`
   - **Web:** `flutter run -d chrome`
   - **Android/iOS:** через эмулятор или устройство

### Сборка релиза
- **Windows:** `flutter build windows`
- **macOS:** `flutter build macos`
- **Linux:** `flutter build linux`
- **Web:** `flutter build web`

### Кастомизация иконок
- Иконки для всех платформ лежат в соответствующих папках (`windows/runner/resources/`, `macos/Runner/Assets.xcassets/AppIcon.appiconset/`, `web/icons/` и т.д.)
- Для генерации иконок используйте PNG/SVG из корня проекта (`sshspace_icon.png`, `sshspace_icon.svg`) и скрипты (`create_windows_icon.py`, `create_icon.ps1`)
- Подробнее — см. `ICON_CREATION_README.md` и `WINDOWS_ICON_GUIDE.md`

---

## 🌍 Description (English)
**SSHSpace** is a cross-platform SSH/SFTP client with a cosmic sci-fi UI, file manager, and real-time terminal. Runs on Windows, macOS, Linux, Web, Android, iOS. Built with Flutter.

### Features
- Modern minimalistic sci-fi/cyberpunk interface
- SSH and SFTP support (file manager, terminal)
- Animated login with astronaut and terminal
- Custom icons, smooth animations, drag-and-drop
- Responsive design for desktop and mobile

### Getting Started
1. Install [Flutter](https://flutter.dev/docs/get-started/install)
2. Clone the repository:
   ```sh
   git clone <repo_url>
   cd sshgogo_app/lib/flutter_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run on your platform:
   - **Windows:** `flutter run -d windows`
   - **macOS:** `flutter run -d macos`
   - **Linux:** `flutter run -d linux`
   - **Web:** `flutter run -d chrome`
   - **Android/iOS:** via emulator or device

### Build Release
- **Windows:** `flutter build windows`
- **macOS:** `flutter build macos`
- **Linux:** `flutter build linux`
- **Web:** `flutter build web`

### Customizing Icons
- App icons for all platforms are in their respective folders (`windows/runner/resources/`, `macos/Runner/Assets.xcassets/AppIcon.appiconset/`, `web/icons/`, etc.)
- Use the PNG/SVG in the project root (`sshspace_icon.png`, `sshspace_icon.svg`) and scripts (`create_windows_icon.py`, `create_icon.ps1`) to generate icons
- See `ICON_CREATION_README.md` and `WINDOWS_ICON_GUIDE.md` for details

---

**Разработчик / Developer:** after (https://github.com/after)
