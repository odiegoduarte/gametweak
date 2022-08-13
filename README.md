<br>

<h1 align="center">Game Tweak</h1>

<br><br>

Jogos | Local do arquivo | Tweak | S.O
------------ | ------------- | ------------- | -------------
[El Matador](https://www.pcgamingwiki.com/wiki/El_Matador) | /El Matador | [FOV HUD Fix, Wide, Ultra Wide e 4K](https://community.pcgamingwiki.com/files/file/1496-el-matador-fov-and-hud-fix/) | <img width="50" height="" src="/assets/icons/os.png">
[Viscera Cleanup Detail](https://www.pcgamingwiki.com/wiki/Viscera_Cleanup_Detail) |Viscera/Engine/Config/BaseEngine.ini | bSmoothFrameRate=FALSE | <img width="50" height="" src="/assets/icons/os.png">
[Viscera Cleanup Detail](https://www.pcgamingwiki.com/wiki/Viscera_Cleanup_Detail) |Viscera/UDKGame/Config/UDKEngine.ini | bSmoothFrameRate=FALSE | <img width="50" height="" src="/assets/icons/os.png">

<br><br>

<h1 align="center">Steam Game Launch Options</h1>

<br>

### Definir opções de inicialização

- Abra a Biblioteca Steam.
- Click botão direito em cima do jogo depois vá em Propiedades...
- Na aba Geral, haverá a seção Opções de inicialização.
- Insira as opções de inicialização que deseja aplicar (separando-as com espaços).
- Feche a janela de Propriedades do jogo e inicie-o.

<br>

Jogos | Argumentos Opcionais| S.O
------------ | -------------| -------------
[CS GO](https://developer.valvesoftware.com/wiki/Console_Command_List) |-novid -forcenovsync -nojoy -high -full  | <img width="50" height="" src="/assets/icons/os.png">
[BioShock](https://www.pcgamingwiki.com/wiki/BioShock)|PROTON_NO_D3D11=1 PROTON_NO_ESYNC=1 %command% | <img width="25" height="" src="assets/icons/linux.png">
[BioShock Remastered](https://www.pcgamingwiki.com/wiki/BioShock_Remastered)|PROTON_USE_WINED3D10=1 PROTON_NO_ESYNC=1 %command% | <img width="25" height="" src="/assets/icons/linux.png">
[Gris](https://www.pcgamingwiki.com/wiki/GRIS) | [Proton GloriousEggroll](https://github.com/GloriousEggroll/proton-ge-custom/releases) | <img width="25" height="" src="/assets/icons/linux.png">
[Left 4 Dead 2](https://developer.valvesoftware.com/wiki/Console_Command_List) |-novid -language portuguese brasil  |<img width="50" height="" src="/assets/icons/os.png">
[Team Fortress 2](https://www.pcgamingwiki.com/wiki/Team_Fortress_2) | -novid | <img width="50" height="" src="/assets/icons/os.png">
[The Forest](https://www.pcgamingwiki.com/wiki/The_Forest) | PROTON_NO_FSYNC=1 taskset -c 0,1,2,3 %command% | <img width="25" height="" src="/assets/icons/linux.png">
[Valheim](https://www.pcgamingwiki.com/wiki/Splitgate) | ./start_game_bepinex.sh %command%  (MOD)| <img width="25" height="" src="assets/icons/linux.png">
[Slitgate](Splitgate) | -windowed | <img width="50" height="" src="/assets/icons/os.png">
[Jogo]() | argumentos | <img width="25" height="" src="/assets/icons/linux.png"> <img width="23" height="" src="/assets/icons/windows.png">

<br> <br>

### <img width="25" height="" src="/assets/icons/linux.png"> Runtime Proton Steam Play

<br>

Runtime | Variável de ambiente | Descrição
------------ | -------------| -------------
wined3d | PROTON_USE_WINED3D | Use wined3d baseado em OpenGL em vez de DXVK baseado em Vulkan para d3d11, d3d10 e d3d9.
nod3d11 | PROTON_NO_D3D11	| Desative d3d11.dll , para jogos d3d11 que podem voltar e rodar melhor com d3d9.
nod3d10 | PROTON_NO_D3D10	| Desative d3d10.dll e dxgi.dll , para jogos d3d10 que podem voltar e rodar melhor com d3d9.
forcelgadd | PROTON_FORCE_LARGE_ADDRESS_AWARE | Força o Wine a habilitar o sinalizador LARGE_ADDRESS_AWARE para todos os executáveis. Ativado por padrão.
d9vk | PROTON_USE_D9VK | Nota: Obsoleto no Proton 5.0. Em versões anteriores, use DXVK baseado em Vulkan em vez de wined3d baseado em OpenGL para d3d9.
seccomp | PROTON_USE_SECCOMP | Habilite o filtro seccomp-bpf para emular syscalls nativos, necessários para algumas proteções DRM funcionarem.
dxvk | DXVK_HUD=1 %command% | Habilitar o DXVK HUD com Proton 

<br>

### DXVK_HUD Variáveis

>*O "DXVK_HUD" variável de ambiente controla o HUD que pode exibir taxa de quadros e algumas  estatísticas. 
>Ele aceita uma lista separada por vírgulas das seguintes opções:*

Variável de ambiente | Descrição
------------ | -------------
DXVK_HUD=1 %command% | Habilitar o DXVK HUD com Proton 
devinfo | Exibe o nome da GPU e a versão do driver
fps|  Mostra a taxa de FPS.
frametimes | Mostra o frametime.
memory | Mostra a quantidade de memória da GPU alocada e usada.
gpuload | Mostra a carga estimada da GPU
version | Mostra a versão DXVK.
api | Mostra o nível de recurso D3D pela
cs | Mostra as estatísticas do thread de trabalho
compiler | Mostra a atividade do shader compiler
scale=x | dimensiona o HUD por um fator de x(por exemplo 1.5)

<br> <br> <br>

### <img width="50" height="" src="/assets/icons/os.png"> Comandos para CS GO

>*Valor "1" ativo valor "0" desativado.*

Comando | Descrição
------------ | -------------
cl_showfps 1 | Mostra os FPS.
net_graph 1 | Mostra fps, ping, loss, choke, tick e var.
cl_righthand 0 | Troca a arma da mão direita para esquerda.
bindtoggle v cl_righthand | Define tecla V para trocar a arma de mão.
hud_scaling 0.70 | Tamanho da HUD, mínimo é 0.5 e o máximo é 0.95
cl_radar_always_centered | Centraliza o radar.
cl_radar_scale 1 | Escala do mapa dentro do radar 0 visão próxima 1 afastada.
cl_radar_rotate 0 | comando para que o radar gire conforme você gira padrão é 1.
cl_show_team_equipment | Mostra armas e utilitários dos aliados sobre a cabeça.
voice_enable 0 | Desabilita o VOIP em game.
bot_add | Adiciona boots.
kill |  Comando para matar seu personagem.

<br>

### <img width="50" height="" src="/assets/icons/os.png"> Opções de inicialização Source

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

### <img width="50" height="" src="/assets/icons/os.png"> Opções de inicialização Unity3d

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
 
<br> <br> <br>

### Referências

- [Steam Definindo opções de inicialização de jogos](https://support.steampowered.com/kb_article.php?ref=1040-JWMT-2947&l&l=brazilian)
- [Valve Lista de Comandos do Console](https://developer.valvesoftware.com/wiki/Console_Command_List)
- [ValveSoftware Steamplay Github](https://github.com/ValveSoftware/Proton/blob/proton_5.0/README.md)
- [GloriousEggroll ProtonGE](https://github.com/GloriousEggroll/proton-ge-custom)
- [Unity Documentation](https://docs.unity3d.com/Manual/PlayerCommandLineArguments.html)
- [Proton Wiki](https://github.com/ValveSoftware/Proton/wiki)
- [Protondb](https://www.protondb.com/)
- [WineHQ](https://wiki.winehq.org/Download)
- [DXVK](https://github.com/doitsujin/dxvk/blob/master/README.md#hud)


<br> <br> <br>
