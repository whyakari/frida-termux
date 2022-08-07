## Frida-Termux (Android)
> Frida no android, usando o Termux. __ROOT__

###

**Requisitos**: 
 - Termux [v118](https://f-droid.org/repo/com.termux_118.apk) </br>
 - Root { [Magisk](https://github.com/topjohnwu/Magisk/releases/download/v25.2/Magisk-v25.2.apk) >= 25.2 }
 - MagiskFrida { **[Módulo](https://github.com/ViRb3/magisk-frida/releases/download/15.2.2-1/MagiskFrida-15.2.2-1.zip)** Magisk }

<br>

#### 1. instale o Termux: [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Termux.svg/240px-Termux.svg.png">](https://f-droid.org/repo/com.termux_118.apk)

#### 2. pacotes necessários no Termux:
    apt update && apt upgrade && apt update && apt install python -y && apt install tsu -y && pip install wheel && pip install frida-tools
> Depois de instalar o módulo MagiskFrida, Termux e pacotes necessários, podemos já usar o **Frida**!

#### 3. comandos do Frida.
 - verificar se o Frida instalou:
   > frida --version
 - comando de ajuda:
   > frida --help

<br>

__Mais informações aqui__:
  > [Documentação Frida](https://frida.re/docs) </br>
  > [Frida-Android](https://frida.re/docs/examples/android/)
