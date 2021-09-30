Maneira de instalação e configuração do appium e os demais programas para teste mobile 
#  Configuração de máquina para Appium

<h2 align="center"> 
	🚧  Instalar JDK 🚀 
</h2>

* Acessar o site http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
* Selecionar o item Accept License Agreement
* Clicar no link referente ao instalador de acordo com seu sistema operacional (Linux, Solaris, MacOSx, Windows)
* Aguardar o download do arquivo instalador
* Clicar no arquivo executável e seguir os passos propostos pelo instalador

<h2 align="center"> 
	🚧  Configurar JDK no Windows 🚀 
</h2>

* Vá até as Variáveis de Ambiente no Windows e:
* Adicione a seguinte variável com o respectivo valor e clique em OK
* Nome da variável: JAVA_HOME
* Valor da variável: C:\Program Files\Java\jdk1.8.0_121
* Atenção: o Valor da variável é ilustrativo. O diretório correto deve ser o local onde está instalado o JDK, podendo haver diferenças na versão (números após o jdk1.8.0)
* Selecione a variável PATH e clique em Editar...
* Clique no botão Novo e adicione o seguinte valor de variável %JAVA_HOME%\bin
* Atenção: se a variável PATH não existir, crie a variável com o mesmo valor de variável.
* Feche todas as telas clicando no botão OK e abra o Prompt de Comando. Se ele estiver aberto, feche-o e abra um novo Digite, no Prompt de Comando a palavra java e pressione a tela ENTER Deve ser apresentado uma lista de opções (parâmetros) para o comando. A primeira linha possui o texto “Uso: java [-options] class [args...]”

<h2 align="center"> 
	🚧  Baixar Android Studio 🚀 
</h2>

* Acessar o site https://developer.android.com/studio/index.html
* Clicar no botão Download Android Studio
* Aceitar os termos e condições marcando a opção I have read and agree with the above terms and conditions
* Clicar no botão Download Android Studio abaixo dos termos e condições
* Aguardar o download do arquivo instalador
* Clicar no arquivo executável e seguir os passos propostos pelo instalador
* Você pode seguir o vídeo que da página que é exibida após o início do download para instalar o Android Studio. Alternativamente você pode acessá-lo através deste link https://developer.android.com/studio/install.html

<h2 align="center"> 
	🚧  Atualizar o android sdk 🚀 
</h2>

*Abra o Android Studio
* Na tela inicial clique o item Configure e depois no item SDK Manager
* Você precisa instalar e/ou atualizar os seguintes itens em cada aba
* SDK Platform (aba)
* Android 8.1 (Oreo)
* SDK Tools (aba)
* Android SDK Build-Tools
* Android Emulator 27.3.9 (ou superior)
* Android SDK Platform-Tools 28.0.0 (ou superior)
* Android SDK Tools 26.1.1 (ou superior)
* Se existir, marque também o item Intel x86 Emulator Accelerator (HAXM installer)
* Clique no botão Apply para atualizar o Android SDK
* Ao término da atualização, feche o Android Studio
* Observação: as versões listadas para a aba SDK Tools provavelmente devem estar desatualizadas. Sempre utilize a versão que está sendo exibida para você

<h2 align="center"> 
	🚧  Configurar JDK 🚀 
</h2>

* Abra o Android Studio
* Na tela inicial clique o item Configure e depois no item SDK Manager
* Copie o caminho apresentado no campo Android SDK Location
* Vá até as Variáveis de Ambiente no Windows e:
* Adicione a seguinte variável com o respectivo valor e clique em OK
* Nome da variável: ANDROID_HOME
* Valor da variável: Diretório presente no campo Android SDK Location
* Selecione a variável PATH e clique em Editar...
* Clique no botão Novo e adicione o seguinte valor de variável o %ANDROID_HOME%\tools
* Clique novamente no botão Novo e adicione o seguinte valor de variável %ANDROID_HOME%\tools\bin
* Clique novamente no botão Novo e adicione o seguinte valor de variável %ANDROID_HOME%\platform-tools
* Feche todas as telas clicando no botão OK e abra o Prompt de Comando. Se ele estiver aberto, feche-o e abra um novo
* No Prompt de Comando digite uiautomatorviewer e pressione ENTER
* Uma janela com o título UI Automator Viewer deve ser apresentada. Feche a janela
* Ainda no Prompt de Comando digite adb e pressione ENTER
* Deve ser apresentado uma lista de opções (parâmetros) para o comando. A primeira linha possui o texto Android Debug Bridge version

<h2 align="center"> 
	🚧  Instalar NodeJs 🚀 
</h2>

* Acessar o site https://nodejs.org/en/download/
* Clique no icone referente a o seu sistema operacional
* Aguardar o download do arquivo
* Clicar no arquivo executável e seguir os passos propostos pelo instalador

<h2 align="center"> 
	🚧  Instalar appium via npm 🚀 
</h2>

* Abra o Prompt de Comando ou Terminal
* Digite os seguintes comandos e pressione ENTER
* npm install -g appium

* Se algum problema ocorrer durante a instalação no Windows:
* Abra o PowerShell e execute os comandos abaixo, um de cada vez:
* Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
* npm install -g npm-windows-upgrade
* npm-windows-upgrade
* npm install -g appium

<h2 align="center"> 
	🚧  Instalar appium via desktop 🚀 
</h2>

* Acessar o site https://github.com/appium/appium-desktop/releases/
* Para a última versão que contenha os Assets selecione o instala dor de acordo com o seu sistema operacional
* Aguardar o download do arquivo
* Clicar no arquivo executável e seguir os passos propostos pelo instalador

<h2 align="center"> 
	🚧  Instalar Genymotion 🚀 
</h2>

* Acesse a página https://www.genymotion.com/fun-zone/
* Clique no botão Download Genymotion Personal Edition
* Se você não possui um conta é necessário criá-la, caso contrario efetue o login na página
* Clique no botão de Download que será apresentado após o login
* Aguardar o download do arquivo instalador
* Clicar no arquivo executável e seguir os passos propostos pelo instalador
* Abra o Genymotion
* Clique no item Personal Use na mensagem que será apresentada
* Aceite os termos de licença
* Clique no botão Add. Será necessário clicar no botão Sign in e efetuar o login com usuário senha cadastrados anteriormente
* Na combo Android Version selecione o item 6.0.0
* Na lista de dipositivos selecione o item Google Nexus 5 – 6.0.0 – API 23 – 1080 x 1920 e clique em Next
* Clique em Next na tela de confirmação de criação da máquina virtual Android e aguarde o término
* Feche o Genymotion

<h2 align="center"> 
	🚧  Projeto Base 🚀 
</h2>

* Acesse o repositório do projeto https://github.com/eliasnogueira/appium-workshop
* Clique no botão verde no canto direito chamado Clone or download
* Clique no botão Download Zip
* Copie a pasta appium-workshop-master para um local que você irá lembrar
* Abra o Eclipse
* Clique no menu File -> Import
* Clique na pasta Maven e selecione o item Existing Maven Projects. Clique em Next
* Clique no botão Browse
* Vá até o diretório Vá até o diretório appium-workshop-master, selecione a pasta projeto-apppium e clique em Open
* Clique no botão Finish
