
#  Integrated Development Environment (IDE)<br> Programming C/C++

<p align="center"> 
<img src="/TOOLS/IMG/IDE-C.png" width="400" align="center">
</p 

<br>

## Concept
**Software for C/C++**
 
**Code::Blocks IDE**<br>
Windows<br>
NOTE: The codeblocks-20.03mingw-setup.exe file includes additionally the GCC/G++/GFortran compiler and GDB debugger from MinGW-W64 project (version 8.1.0, 32/64 bit, SEH).<br>
codeblocks-20.03mingw-setup.exe<br>
codeblocks-20.03mingw-nosetup.zip

**Code::Blocks IDE**<br>
Ubuntu<br>

1. Documentação<br>
* [Download Code::Blocks IDE](http://www.codeblocks.org/downloads/binaries/#imagesoslinux48pnglogo-linux-32-and-64-bit)
* [Documentação codeblocks-devs ](https://launchpad.net/~codeblocks-devs)
* [Documentação codeblocks-devs release ](https://launchpad.net/~codeblocks-devs/+archive/ubuntu/release)
2. Fazer atualização <br>
```
sudo apt update
```
3. Instalar<br>
```
sudo apt install codeblocks
```
**Visual Studio Code IDE**<br>
Online<br>
* [Visual Studio Code Online](https://vscode.dev/)<br>
Após fazer Sign in no github.com, no diretório que deseja realizar as alteração pressione "." isso encaminha você ao VScode - Online

**Visual Studio Code IDE**<br>
Windows<br>

* [Documentação e Download ](https://code.visualstudio.com/docs/?dv=win)
* [Estensão C/C++ for Visual Studio Code ](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
* [Documentação Using GCC with MinGW ](https://code.visualstudio.com/docs/cpp/config-mingw)
<br>
Crie um arquivo "primeiro.cpp"<br> 
Neste momento temos a imagem pedindo para instalar a extensão<br>
<p align="center"> 
<img src="/TOOLS/IMG/001-AutoInstallCpp.png" width="400" align="center">
</p 
<br>
Uma outra forma de instalar a extensão é pesquisar a C/C++ Extension Pack <br>
<p align="center"> 
<img src="/TOOLS/IMG/002-ExtensionPackCpp.png" width="400" align="center">
</p 
<br>
Também é possível instalar somente esta extensão, porém recomendo instalar as duas <br>
<p align="center"> 
<img src="/TOOLS/IMG/003-ExtensionCpp.png" width="400" align="center">
</p 
<br>
Agora com as extensões instaladas é necessário uma configuração para que seja possivel compilar projetos em C++<br>
Para quem tem o CodeBlocks instalado realizar o passo a passo  abaixo ou <a href="https://code.visualstudio.com/docs/cpp/config-mingw"> Documentação Using GCC with MinGW</a>.
<br>
<br>


Add the path to your Mingw-w64 bin folder to the Windows PATH environment variable by using the following steps:

1. In the Windows search bar, type **'settings'** to open your Windows Settings.<br>
2. Search for **'Edit environment variables for your account'**.<br>
3. Choose the **'Path'** variable in your User variables and then select **'Edit'**.<br>
4. Select **'New'** and add the Mingw-w64 destination folder path to the system path. The exact path depends on which version of Mingw-w64 you have installed and where you installed it. If you used the settings above to install Mingw-w64, then add this to the path: C:\Program Files\CodeBlocks\MinGW\bin. <br>
5. Select OK to save the updated PATH. You will need to reopen any console windows for the new PATH location to be available.
6. Reboot or Sign out  <br>
**Check your MinGW installation**<br>
To check that your Mingw-w64 tools are correctly installed and available, open a new Command Prompt and type: <br>
```
gcc --version 
g++ --version 
gdb --version 
```
**Visual Studio Code IDE**<br>
Ubuntu <br>
1. Download VScode<br>
* [Visual Studio Code IDE](https://code.visualstudio.com) for Windows, Linux or Mac OS.
2. Instalar VScode<br>
https://help.ubuntu.com/kubuntu/desktopguide/C/manual-install.html<br>
```
sudo dpkg -i package_file.deb
```
3. Instalar a extesão C/C++ Extension Pack no VScode<br>

4. Verificar se o gcc e g++ esta instalado <br>
```
gcc --version
g++ --version
```
5. Instalar gcc e g++ <br>
```
sudo apt install gcc
-Erro
sudo apt install g++ 
-Erro
```
6. Fazer atualização <br>
```
sudo apt update
apt list --upgradable
```
7. Tentar instalar novamente gcc e g++<br>
```
sudo apt install gcc
sudo apt install g++
```
8. Instalação com sucesso <br>
```
gcc --version
g++ --version
```
## Software
* [Dev C++ IDE](https://sourceforge.net/projects/orwelldevcpp/files/latest/download) for Windows
* [Code::Blocks IDE](http://www.codeblocks.org/downloads/binaries) for Windows, Linux or Mac OS.
* [Visual Studio Code IDE](https://code.visualstudio.com) for Windows, Linux or Mac OS.
## Extension for Visual Studio Code :

EMMET (extensão) - Produtividade 
* [EMMET](https://docs.emmet.io/cheat-sheet/)
    
Remote (extensão) - SSH
* [Remote](https://code.visualstudio.com/docs/remote/ssh-tutorial)

Code Runner (extensão) - .run
* [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
