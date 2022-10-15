## Frida-Termux (Android)
> Frida no android, usando o Termux. __ROOT__

###

**Requisitos**: 
 - Termux [v118](https://f-droid.org/repo/com.termux_118.apk) </br>
 - Root { [Magisk](https://github.com/topjohnwu/Magisk/releases/download/v25.2/Magisk-v25.2.apk) >= 25.2 }
 - MagiskFrida { **[Módulo](https://github.com/ViRb3/magisk-frida/releases/download/16.0.1-1/MagiskFrida-16.0.1-1.zip)** Magisk }

##

#### 1. instale o Termux: <br><br> [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Termux.svg/240px-Termux.svg.png" width="78">](https://github.com/HardcodedCat/termux-monet/releases/download/v0.118.0-20/termux-app_v0.118.0-20+apt-android-7-github-debug_universal.apk)    

#### 2. pacotes necessários no Termux:
    apt update && apt upgrade; pkg in -y root-repo; pkg in -y frida-python; apt install python -y; apt install tsu -y; pip install wheel; pip install frida-tools
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
