# security_chat

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Comandos utilizados

```zsh
# Crear el proyecto en el directorio actual
flutter create --project-name security_chat --org com.usbbog --platforms=android .

# Actualizar Flutter
flutter upgrade

# Verificar la instalación y dependencias
flutter doctor

# Aceptar licencias de Android
flutter doctor --android-licenses

# Instalar CocoaPods (para macOS/iOS)
sudo gem install cocoapods

# Instalar Android SDK Command-line Tools (desde Android Studio o manualmente)
# sdkmanager "cmdline-tools;latest"

# Configurar variables de entorno (añadir a ~/.zshrc)
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$ANDROID_HOME/cmdline-tools/latest/bin:$PATH

# Cambiar Xcode por defecto y ejecutar configuración inicial
sudo xcode-select --switch /Applications/Xcode.app
sudo xcodebuild -runFirstLaunch
```