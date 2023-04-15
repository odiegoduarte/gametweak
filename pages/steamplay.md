<br>
<h1 align="center">Steam Play <img width="33" height="" src="../assets/icons/linux.png"></h1>
<h4 align="center">Runtime Proton Steam Play</h4>
<br><br>

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

<br>

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

<br>