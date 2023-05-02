<br>
<h1 align="center">Steam Game Launch Options <img width="60" height="" src="../assets/icons/os.png"></h1>
<h4 align="center">Runtime Proton Steam Play</h4>
<br><br>

### Definir opções de inicialização

- Abra a Biblioteca Steam.
- Click botão direito em cima do jogo depois vá em Propiedades...
- Na aba Geral, haverá a seção Opções de inicialização.
- Insira as opções de inicialização que deseja aplicar (separando-as com espaços).
- Feche a janela de Propriedades do jogo e inicie-o.
- *Argumento "-vulkan" não funciona no Windows

<br>

Jogos | Argumentos | S.O
------------ | -------------| -------------
CS GO |-novid -forcenovsync -nojoy -high -full | <img width="50" height="" src="../assets/icons/os.png">
Dota 2 |-novid -vunkan -w 2560 -h 1080  | <img width="50" height="" src="../assets/icons/os.png">
BioShock Remastered | [Argumentos ->](../games/bioShockremastered.md) | <img width="50" height="" src="../assets/icons/os.png">
BioShock Remastered 2| [Argumentos ->](../games/bioShock2remastered.md) | <img width="50" height="" src="../assets/icons/os.png">
BioShock Infinite | [Argumentos ->](../games/bioShockargumentos.md) | <img width="25" height="" src="../assets/icons/linux.png">
Gris | -window-mode exclusive | <img width="50" height="" src="../assets/icons/os.png">
Left 4 Dead 2 |-novid -language portuguese brasil | <img width="50" height="" src="../assets/icons/os.png">
Team Fortress 2 | -novid | <img width="50" height="" src="../assets/icons/os.png">
The Forest | PROTON_NO_FSYNC=1 taskset -c 0,1,2,3 %command% | <img width="25" height="" src="../assets/icons/linux.png">
Valheim | -console|  <img width="50" height="" src="../assets/icons/os.png">
Splitgate | -windowed | <img width="50" height="" src="../assets/icons/os.png">
[Jogo]() | argumentos | <img width="25" height="" src="../assets/icons/linux.png"> <img width="23" height="" src="../assets/icons/windows.png">

<br>

### <img width="50" height="" src="../assets/icons/os.png"> Opções de inicialização Source

> *Goldsrc, Source e Source 2*

Comando | Descrição
------------ | -------------
-autoconfig | Restaura as configurações padrão. Ignora configurações de arquivos .cfg até a remoção deste parâmetro.
-console | Inicia o jogo com o console de desenvolvedor ativado.
-fullscreen | Força a engine a iniciar em tela cheia.
-windowed | Força a engine a iniciar em modo janela.
-refresh <120>  |  Força uma taxa de atualização específica.
-novid | Ao iniciar um jogo com esse parâmetro, o vídeo de introdução da Valve não será reproduzido.
-language portuguese brasil | Define idioma para jogo caso tenha suporte

<br>

### <img width="50" height="" src="../assets/icons/os.png"> Opções de inicialização Unity3d

> *Argumentos de linha de comando do Unity Standalone Player*

Comando | Descrição
------------ | -------------
-force-vulkan | Usar API VULKAN para renderização.
-force-wayland | Ative o suporte experimental para renderização Wayland.
-force-metal | Usar API Metal para renderização (MacOS).
-force-d3d11 | Usar API Direct3D 11  para renderização.
-force-d3d12 | Usar API Direct3D 12  para renderização.
-screen-fullscreen |Tela cheia padrão.
-screen-height | Alterar a altura padrão da tela.
screen-width  | Alterar a largura padrão da tela.
-screen-quality | Alterar a qualidade gráfica.
-single-instance | Execute apenas uma instância do aplicativo por vez (Somente Linux e Windows)
 
<br><br>

### Referências

- [Steam Definindo opções de inicialização de jogos](https://support.steampowered.com/kb_article.php?ref=1040-JWMT-2947&l&l=brazilian)
- [Valve Lista de Comandos do Console](https://developer.valvesoftware.com/wiki/Console_Command_List)
- [ValveSoftware Steamplay Github](https://github.com/ValveSoftware/Proton/blob/proton_5.0/README.md)
- [GloriousEggroll ProtonGE](https://github.com/GloriousEggroll/proton-ge-custom)
- [Unity Documentation](https://docs.unity3d.com/Manual/PlayerCommandLineArguments.html)
- [PCGamingWiki](https://www.pcgamingwiki.com/wiki/)
- [Proton Wiki](https://github.com/ValveSoftware/Proton/wiki)
- [Protondb](https://www.protondb.com/)
- [WineHQ](https://wiki.winehq.org/Download)
- [DXVK](https://github.com/doitsujin/dxvk/blob/master/README.md#hud)

<br><br><br>