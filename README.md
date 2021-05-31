# flutter
Conhecimentos em Flutter





- [Instalando e configurando o Flutter no Windows 10](https://flutter.dev/docs/get-started/install/windows#android-setup)

Erro ao rodar `flutter doctor --android-licenses`

`Exception in thread "main" java.lang.NoClassDefFoundError: javax/xml/bind/annotation/XmlSchema`

Solução:

[Instale o Android Studio](https://developer.android.com/news)

Clique em "File" > "Settings" 



Agora em "System Settings" > "Android SDK" > Agora clique na aba "SDK Tools" > Marque "Android SDK Command-line Tools"> Clique em Apply

Irá fazer o download, depois de instalado é só rodar o comando `flutter doctor --android-licenses` no terminal. E concluir a instalação do flutter.

