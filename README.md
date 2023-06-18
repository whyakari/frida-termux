## Frida-Termux (Android)
> Frida no android, usando o Termux. __ROOT__

###

**Requisitos**: 
 - [Termux](https://github.com/HardcodedCat/termux-monet/releases/download/v0.118.0-24/termux-app_v0.118.0-24+apt-android-7-github-debug_universal.apk) </br>
 - [Root-Magisk](https://github.com/topjohnwu/Magisk/releases/download/v25.2/Magisk-v25.2.apk) >= 25.2
 - **[MagiskFrida Módulo](https://github.com/ViRb3/magisk-frida/releases/download/15.2.1-1/MagiskFrida-15.2.1-1.zip)**

##

#### 1. instale o Termux: <br><br> [<img src="https://raw.githubusercontent.com/HardcodedCat/termux-monet/master/art/ic_monet_dark.svg#gh-dark-mode-only" width="78">](https://github.com/HardcodedCat/termux-monet/releases/download/v0.118.0-24/termux-app_v0.118.0-24+apt-android-7-github-debug_universal.apk)    

#### 2. pacotes necessários no Termux:
    apt update && apt upgrade; pkg in -y root-repo; pkg in -y frida-python; apt install python -y; apt install tsu -y; pip install wheel; pip install frida-tools==10.8.0
> Depois de instalar o módulo MagiskFrida, Termux e pacotes necessários, podemos já usar o **Frida**!

#### 3. comandos do Frida:
 - verificar se o Frida instalou:
   > frida --version
 - comando de ajuda:
   > frida --help

<br>

__Mais informações aqui__:
  > Documentação Frida [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs) </br>
  > Frida-Android [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs/examples/android/) <br>
  > [](https://github.com/frida)

__Correções de erros, comente aqui__: <br>
   1. BootLoop Fixed [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/SakutaOficial/Frida-Termux/issues/1#issue-1331129541)
   2. Issues [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/SakutaOficial/Frida-Termux/issues/)

---

> if you think my work is cool or want to help me, make a small donation <3
#### send for btc address
```
 bc1qluadws0x8822urvhdufdeft4rs0ay290drlkpu
```
