## Frida-Termux (Android)
> **Frida no android com Termux**.

###

**Requisitos**: 
 - [Termux](https://github.com/HardcodedCat/termux-monet/releases) </br>
 - [Magisk](https://github.com/topjohnwu/Magisk/releases/download/v25.2/Magisk-v25.2.apk) / [KSU](https://github.com/whyakari/kernel_Moe_ginkgo)
 - **[MagiskFrida](https://github.com/ViRb3/magisk-frida/releases/download/15.2.1-1/MagiskFrida-15.2.1-1.zip)**

##

#### 1. Instale o Termux: <br><br> [<img src="https://raw.githubusercontent.com/HardcodedCat/termux-monet/master/art/ic_monet_dark.svg#gh-dark-mode-only" width="78">](https://github.com/HardcodedCat/termux-monet/releases)    

#### 2. Instale os pacotes:
    apt update && apt upgrade; pkg in -y root-repo; pkg purge python -y; apt autoremove; pkg in subversion -y; clear; svn export https://github.com/AkariOficial/termux-packages/trunk/python3.10.8; cd python3.10.8; dpkg -i *.deb; cd; rm -rf python3.10.8; apt install tsu -y; pip install wheel; pip install frida-tools==10.8.0
> **read** [#here](https://github.com/whyakari/frida-termux/issues/3#issue-1762058184) **first**

#### 3. Comandos do Frida:
 - **verificar se o Frida está instalado**:
   > frida --version
 - **para mais comandos, use**:
   > frida --help

<br>

__Mais informações aqui__:
  > Documentação Frida [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs) </br>
  > Frida-Android [<img src="https://avatars.githubusercontent.com/u/4073090?s=200&v=4" width="20x100">](https://frida.re/docs/examples/android/) <br>
  > [](https://github.com/frida)

-----
__Correções de erros:__ <br>
   1. BootLoop Fixed [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/whyakari/Frida-Termux/issues/1#issue-1331129541)
   2. frida not work in Py3.11+ [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/whyakari/Frida-Termux/issues/3#issue-1762058184)
   3. Issues [<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" width="80x100">](https://github.com/whyakari/Frida-Termux/issues/)

----
