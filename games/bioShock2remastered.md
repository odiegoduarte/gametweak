<br>
<h1 align="center"> BioShock 2 Remastered <img width="55" height="" src="../assets/icons/os.png"></h1>
<h4 align="center">Steam Play</h4>
<br><br>

### Pasta Save Game

- <img width="18" height="" src="../assets/icons/linux.png"> /steamapps/compatdata/409720/pfx
- <img width="18" height="" src="../assets/icons/windows.png"> 	%USERPROFILE%\Documents\BioshockHD\Bioshock2\SaveGames\

<br>


### Argumento de inicialização bypass no Laucher da 2K

> OBS: Argumento "-nointro" é opcional serve pra pular vídeos de introdução

- <img width="18" height="" src="../assets/icons/linux.png"> SteamPlay
~~~sh
bash -c 'exec "${@/2KLauncher\/LauncherPatcher.exe/Build\/Final\/Bioshock2HD.exe}"' -- %command% -nointro
~~~

- <img width="18" height="" src="../assets/icons/windows.png"> Windows
~~~
"<path-to-game>\BioShock2HD.exe" -run %command% -nointro
~~~

<br>

### Tradução PT-BR

- Download da tradução [Tribo Gamer](https://tribogamer.com/noticias/42393_traducao-bioshock-remastered.html)
- Extrair e copiar todos os arquivos para:

- <img width="17" height="" src="../assets/icons/linux.png"> "/steamapps/common/BioShock 2 Remastered/ContentBaked/pc/System"
- <img width="17" height="" src="../assets/icons/windows.png"> "\Steam\steamapps\common\BioShock 2 Remastered\ContentBaked\pc\System"

<br>

### <img width="40" height="" src="../assets/icons/os.png"> Fix Áudio

- [FIX armas silenciosas e áudio desbalanceado](https://steamcommunity.com/sharedfiles/filedetails/?id=322637977)
- [MOD Áudio Remasterizado](https://www.nexusmods.com/bioshock/mods/6)

<br>

### <img width="40" height="" src="../assets/icons/os.png"> Configurações gráficas avançadas

- Pasta arquivos de configurações
+ <img width="18" height="" src="../assets/icons/linux.png"> /steamapps/compatdata/409720/pfx
+ <img width="18" height="" src="../assets/icons/windows.png"> %APPDATA% \BioshockHD\Bioshock2\

- Edite o arquivo Bioshock2SP.ini

<br>

 Option | Values | Description
------------ | ------------- | -------------
Shadows | True/False | Shadow Maps
UseHighDetailPostProcEffects | True/False | High Detail Post Processing
HighDetailShaders | True/False | High Details Shaders
UseHighDetailShadowMaps | True/False | Use Detail Surfaces
UseHighDetailSoftParticles | True/False | Enabling soft particles has no effect
HighDetailActors |True/False| Actor Detail
SuperHighDetailActors|True/False|Set both to false for low, only first option to true for medium, both to true for high
TextureDetail | Low/Medium/High/UltraHigh | Texture Detail

<br>

### Referências

- [PCGamingWiki](https://www.pcgamingwiki.com/wiki/BioShock_2_Remastered)
- [GamingOnLinux](https://www.gamingonlinux.com/2022/09/various-bioshock-games-get-a-2k-launcher-calling-it-a-quality-of-life-update/)
- [ProtonDB](https://www.protondb.com/app/409720)

<br><br><br>