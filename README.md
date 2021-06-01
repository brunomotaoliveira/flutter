![](https://github.com/brunomotadev/flutter/blob/main/assets/flutter.jpg)

# flutter

Conhecimentos em Flutter





- [Instalando e configurando o Flutter no Windows 10](https://flutter.dev/docs/get-started/install/windows#android-setup)

Erro ao rodar `flutter doctor --android-licenses`

`Exception in thread "main" java.lang.NoClassDefFoundError: javax/xml/bind/annotation/XmlSchema`

![](https://github.com/brunomotadev/flutter/blob/main/assets/errorfluterdoctor-android-licenses.jpg)

Solução:

[Instale o Android Studio](https://developer.android.com/news)

Clique em "File" > "Settings" 

![](https://github.com/brunomotadev/flutter/blob/main/assets/androidstudio1-file-settings.jpg)

Agora em "System Settings" > "Android SDK" > Agora clique na aba "SDK Tools" > Marque "Android SDK Command-line Tools"> Clique em Apply

![](https://github.com/brunomotadev/flutter/blob/main/assets/androidstudio2-systemSettings-androidSDK-SDKtools.jpg)

Irá fazer o download, depois de instalado é só rodar o comando `flutter doctor --android-licenses` no terminal. E concluir a instalação do flutter.

Fonte e outras soluções: https://stackoverflow.com/questions/46402772/failed-to-install-android-sdk-java-lang-noclassdeffounderror-javax-xml-bind-a
