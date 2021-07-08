
<br>

<h1 align="center">Steam Game Launch Options</h1>

<br>

### Definir opções de inicialização

- Abra a Biblioteca Steam.
- Click botão direito em cima do jogo depois vá em Propiedades...
- Na aba Geral, haverá a seção Opções de inicialização.
- Insira as opções de inicialização que deseja aplicar (separando-as com espaços).
- Feche a janela de Propriedades do jogo e inicie-o.

<br>

Jogos | Argumentos | S.O
------------ | -------------| -------------
[CS GO](https://developer.valvesoftware.com/wiki/Console_Command_List) |-novid -forcenovsync -nojoy -high  | <img width="25" height="" src="assets/so/linux.png"> <img width="23" height="" src="assets/so/windows.png">
[BioShock](https://www.pcgamingwiki.com/wiki/BioShock)|PROTON_NO_D3D11=1 PROTON_NO_ESYNC=1 %command% | <img width="25" height="" src="assets/so/linux.png">
[BioShock Remastered](https://www.pcgamingwiki.com/wiki/BioShock_Remastered)|PROTON_USE_WINED3D10=1 PROTON_NO_ESYNC=1 %command% | <img width="25" height="" src="assets/so/linux.png">
[Gris](https://www.pcgamingwiki.com/wiki/GRIS) | [Proton GloriousEggroll](https://github.com/GloriousEggroll/proton-ge-custom/releases) | <img width="25" height="" src="assets/so/linux.png">
[Jogo]() | argumentos | IMG

<br> <br>

### Runtime Proton Steam Play

<br>

Runtime | Variável de ambiente | Descrição
------------ | -------------| -------------
wined3d | PROTON_USE_WINED3D | Use wined3d baseado em OpenGL em vez de DXVK baseado em Vulkan para d3d11, d3d10 e d3d9.
nod3d11 | PROTON_NO_D3D11	| Desative d3d11.dll , para jogos d3d11 que podem voltar e rodar melhor com d3d9.
nod3d10 | PROTON_NO_D3D10	| Desative d3d10.dll e dxgi.dll , para jogos d3d10 que podem voltar e rodar melhor com d3d9.
forcelgadd | PROTON_FORCE_LARGE_ADDRESS_AWARE | Força o Wine a habilitar o sinalizador LARGE_ADDRESS_AWARE para todos os executáveis. Ativado por padrão.
d9vk | PROTON_USE_D9VK | Nota: Obsoleto no Proton 5.0. Em versões anteriores, use DXVK baseado em Vulkan em vez de wined3d baseado em OpenGL para d3d9.
seccomp | PROTON_USE_SECCOMP | Habilite o filtro seccomp-bpf para emular syscalls nativos, necessários para algumas proteções DRM funcionarem.


<br> <br> <br>

### Comandos para CS GO
valor "1" ativo valor "0" desativado.

- cl_showfps 1 - Mostra os FPS.
- net_graph 1 - Mostra fps, ping, loss, choke, tick e var.
- cl_radar_always_centered - Centraliza o radar.
- +cl_show_team_equipment - Mostra armas e utilitários dos aliados sobre a cabeça.
- bot_add - Adiciona boots.
- voice_enable 0 - Desabilita o VOIP em game.
- kill -  Comando para matar seu personagem.

<br> <br> 

### Opções de inicialização
Para jogos que utilizem as engines Goldsrc e Source.

- -autoconfig - Restaura as configurações padrão. Ignora configurações de arquivos .cfg até a remoção deste parâmetro.
- -console - Inicia o jogo com o console de desenvolvedor ativado.
- -fullscreen - Força a engine a iniciar em tela cheia.
- -windowed - Força a engine a iniciar em modo janela.
- -refresh <taxa>  -  Força uma taxa de atualização específica.
- -novid - Ao iniciar um jogo com esse parâmetro, o vídeo de introdução da Valve não será reproduzido.



<br> <br> <br>

### Referências

- [Steam Definindo opções de inicialização de jogos](https://support.steampowered.com/kb_article.php?ref=1040-JWMT-2947&l&l=brazilian)
- [Valve Lista de Comandos do Console](https://developer.valvesoftware.com/wiki/Console_Command_List)
- [ValveSoftware Steamplay Github](https://github.com/ValveSoftware/Proton/blob/proton_5.0/README.md)
- [GloriousEggroll ProtonGE](https://github.com/GloriousEggroll/proton-ge-custom)
- [Protondb](https://www.protondb.com/)    
- [WineHQ](https://wiki.winehq.org/Download)

- [NomeSite](https://odiegoduarte.github.io)


<br> <br> <br>
