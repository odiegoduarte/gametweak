<br>
<h1 align="center"> BioShock Remastered <img width="55" height="" src="../assets/icons/os.png"></h1>
<h4 align="center">Steam Play</h4>
<br><br>

### Pasta Save Game

- <img width="18" height="" src="../assets/icons/linux.png"> /steamapps/compatdata/409710/pfx
- <img width="18" height="" src="../assets/icons/windows.png"> %APPDATA%\BioshockHD\Bioshock\

<br>

### Argumento de inicialização bypass no Laucher da 2K

> *OBS: Argumento "-nointro" é opcional serve pra pular vídeos de introdução*.

- <img width="18" height="" src="../assets/icons/linux.png"> SteamPlay
~~~
bash -c 'exec "${@/2KLauncher\/LauncherPatcher.exe/Build\/Final\/BioshockHD.exe}"' -- %command% -nointro
~~~

- <img width="18" height="" src="../assets/icons/windows.png"> Windows
~~~
"<path-to-game>\BioShockHD.exe" -run %command% -nointro
~~~

<br>

### Tradução PT-BR

- Download da tradução [Tribo Gamer](https://tribogamer.com/noticias/42393_traducao-bioshock-remastered.html)
- Copiar o arquivo "Localizedint" para:

- <img width="17" height="" src="../assets/icons/linux.png"> "/steamapps/common/BioShock Remastered/ContentBaked/pc"
- <img width="17" height="" src="../assets/icons/windows.png"> "\Steam\steamapps\common\BioShock Remastered\ContentBaked\pc"

<br>

### <img width="40" height="" src="../assets/icons/os.png"> Fix e Tweaks

- Editar o Arquivo Default.ini
- /steamapps/common/BioShock Remastered/Build/Final/

~~~
[WinDrv.WindowsClient]
WindowedViewportX=2560    // Setar Largura
WindowedViewportY=1080    // Setar Altura
FullscreenViewportX=2560  // Setar Largura
FullscreenViewportY=1080  // Setar Altura
~~~

~~~
[Havok]
HavokNumThreads=4
~~~

~~~
[Engine.GameEngine]
CacheSizeMegs=512
~~~

<br>

### <img width="40" height="" src="../assets/icons/os.png"> GUI Mod Bioshock

- Baixar o mod no site moddb [GUI for BioShock](https://www.moddb.com/mods/a-gui-mod-for-bioshock-remastered)
- Copiar os arquivos da pasta "FlashMovies" para o diretório
- "/steamapps/common/BioShock Remastered/ContentBaked/pc/FlashMovies/"

<br>

### Referências

- [PCGamingWiki](https://www.pcgamingwiki.com/wiki/BioShock_Remastered)
- [GamingOnLinux](https://www.gamingonlinux.com/2022/09/various-bioshock-games-get-a-2k-launcher-calling-it-a-quality-of-life-update/)
- [ProtonDB](https://www.protondb.com/app/409710)

<br><br><br>