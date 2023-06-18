## Frida-Termux (Android)
> Frida no android, usando o Termux. __ROOT__

###

**Requisitos**: 
 - [Termux](https://github.com/HardcodedCat/termux-monet/releases) </br>
 - [Root-Magisk](https://github.com/topjohnwu/Magisk/releases/download/v25.2/Magisk-v25.2.apk) >= 25.2
 - **[MagiskFrida Módulo](https://github.com/ViRb3/magisk-frida/releases/download/15.2.1-1/MagiskFrida-15.2.1-1.zip)**

##

#### 1. Instale o Termux: <br><br> [<img src="https://raw.githubusercontent.com/HardcodedCat/termux-monet/master/art/ic_monet_dark.svg#gh-dark-mode-only" width="78">](https://github.com/HardcodedCat/termux-monet/releases)    

#### 2. Instale os pacotes:
    apt update && apt upgrade; pkg in -y root-repo; pkg in -y frida-python; apt install python -y; apt install tsu -y; pip install wheel; pip install frida-tools==10.8.0
> Depois de instalar o módulo MagiskFrida, Termux e pacotes necessários, podemos já usar o **Frida**!

#### 3. Comandos do Frida:
 - verificar se o Frida está instalado:
   > frida --version
 - para mais comandos, use:
   > frida --help

<br>

__Mais informações aqui__:
  > Documentação Frida [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs) </br>
  > Frida-Android [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs/examples/android/) <br>
  > [](https://github.com/frida)

__Correções de erros, comente aqui__: <br>
   1. BootLoop Fixed [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/whyakari/Frida-Termux/issues/1#issue-1331129541)
   2. Issues [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/whyakari/Frida-Termux/issues/)

----
