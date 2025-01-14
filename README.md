# Ambiente produtivo para desenvolvimento

- [Ambiente produtivo para desenvolvimento](#ambiente-produtivo-para-desenvolvimento)
  - [Sobre o repositório](#sobre-o-repositório)
  - [Conteúdo](#conteúdo)
  - [Ambiente de desenvolvimento](#ambiente-de-desenvolvimento)
    - [Instalação em WSL 2](#instalação-em-wsl-2)
    - [Instalação Docker](#instalação-docker)
  - [Ferramentas adicionais](#ferramentas-adicionais)
    - [oh my zsh](#oh-my-zsh)
      - [Plugins e complementos:](#plugins-e-complementos)
    - [Power Toys](#power-toys)
  - [Editor de código](#editor-de-código)

## Sobre o repositório
Esse repositório é baseado no ótimo conteúdo de Luiz Carlos:   
[/argentinaluiz/ambiente-dev-produtivo](https://github.com/argentinaluiz/ambiente-dev-produtivo) e [/argentinaluiz/my-vscode-settings/](https://github.com/argentinaluiz/my-vscode-settings). Se estiver buscando mais informações, pode acessar os repositórios originais. 

## Conteúdo

O foco deste conteúdo é no ambiente usado, no Terminal e configurações do VSCode para desenvolvimento Web e Mobile. Vamos trabalhar nos pilares:

* Ambiente estruturado 
* Terminal bem configurado
* Visual Studio Code com extensões

## Ambiente de desenvolvimento
Você tem as seguintes opções:
1. Windows: Trabalhar em uma máquina Windows
2. Linux: Trabalhar em uma máquina Linux
3. WSL2: Usar o WSL2 no Windows para trabalhar em um ambiente Linux
4. [+indicada] Docker: Usar container como ambiente de desenvolvimento instalado ou no Linux, ou no Windows ou na WSL2.
5. Codespace Github: Trabalhar em um ambiente virtual disponibilizado pelo GitHub

A escolha do ambiente depende de sua predileção. Cada escolha possui vantagens e desvantagens, e a decisão deve levar em conta fatores como máquina disponível, facilidade de configuração, desempenho e integração com ferramentas específicas. Avalie também a curva de aprendizado para tomar a melhor decisão.

Como as instalações Windows e Linux são padrões, vamos descrever WSL2 e Docker.

### Instalação em WSL 2

Os desenvolvedores podem aproveitar o Windows e o Linux ao mesmo tempo em um computador Windows. O WSL (Subsistema do Windows para Linux) permite que os desenvolvedores instalem uma distribuição do Linux, como Ubuntu, e usem aplicativos, utilitários e ferramentas de linha de comando bash do Linux diretamente no Windows, sem modificação, sem a sobrecarga de uma máquina virtual tradicional ou configuração dualboot. Desta forma aproveitamos o Ambiente Linux e todos seus benefícios.


[Guia de Instalação do WSL](https://learn.microsoft.com/pt-br/windows/wsl/install)

É indicado que após instalar o WSL2, use o Windows Terminal (É um terminal, não é um shell).

![Windows Terminal com Ubuntu](images/windows_terminal.jpg)

### Instalação Docker
Docker é um conjunto de produtos de plataforma como serviço (PaaS) que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados **contêineres**. Os contêineres são isolados uns dos outros e agrupam seus próprios softwares, bibliotecas e arquivos de configuração. 

Docker é uma ferramenta usada para automatizar a implantação de aplicativos em contêineres leves para que os aplicativos possam funcionar de forma eficiente em diferentes ambientes de forma isolada. 

Docker é uma ferramenta bastante utilizada no mercado de trabalho. Conhecimento e experiência na ferramenta são bastante valorizadas para diversos perfis no desenvolvimento de software.

Você pode instalar o Docker no Windows, no Linux ou no WSL2. É indicado um mínimo de 16 GB de RAM e 100 GB de espaço livre em disco no computador no qual o Docker será instalado. Veja abaixo os detalhes de cada instalação:

* No Windows pode usar o [Docker Desktop](https://www.docker.com/products/docker-desktop/), uma interface gráfica com ferramentas adicionais ao Docker Engine. Uma das desvangagens do Docker Desktop é o recurso necessário. Usuários relatam que pode consumir até 3Gb de memória logo após a instalação sem containers ativos [(fonte)](https://forums.docker.com/t/docker-desktop-idle-memory-usage/138540?utm_source=chatgpt.com).
* [+indicada] No Linux e WSL2, é possível instalar somente o [Instalação do Docker Engine](https://docs.docker.com/engine/install/). O [Guia de Quickstart para WSL2 e Docker](https://github.com/codeedu/wsl2-docker-quickstart) pode ajudá-lo tanto na instalação do WSL2 quanto na instalação e configurações do Docker no WSL2.

## Ferramentas adicionais
### oh my zsh
Oh My Zsh é uma estrutura open source para personalizar o shell Zsh, amplamente usada em Linux e macOS. Zsh é um shell projetado para uso interativo, semelhante ao Bash, usado em sistemas Unix/Linux e macOS.

Com WSL, pode ser instalado no Ubuntu do Windows Terminal. Oferece temas, plugins e atalhos para melhorar a produtividade e a aparência do terminal. Fácil de instalar, é popular entre desenvolvedores por sua flexibilidade e vasta comunidade. Suas funcionalidades são:
* Autocompletar e correção de comandos
* Temas e cores
* Gerência avançada do histórico de comandos
* Variedade enorme de plugins, comunidade ativa.

[Instalação do Oh My Zsh](https://ohmyz.sh/#install)

#### Plugins e complementos:
Dica de template para o ohmyzsh: [PowerLevel10k](https://github.com/romkatv/powerlevel10k)

Coleção de complementos adicionais ao ohmyzsh: O [zsh-completions](https://github.com/zsh-users/zsh-completions) é uma coleção de complementos adicionais para o Zsh (Z Shell), projetada para melhorar a experiência de autocompletar comandos e opções no terminal. 

[Fast Syntax Highlighting](https://github.com/zdharma/fast-syntax-highlighting) é um plugin para o shell Zsh que fornece realce de sintaxe (syntax highlighting) em tempo real para comandos digitados no terminal. Ele ajuda os usuários a identificar erros, comandos válidos e argumentos enquanto escrevem.

### Power Toys
[PowerToys](https://apps.microsoft.com/detail/xp89dcgq3k6vld?hl=en-US&gl=BR) é um conjunto de ferramentas gratuitas da Microsoft projetadas para melhorar a produtividade e personalização no Windows. Alguns recursos do Power Toys são:

Algumas ferramentas do PowerToys:
* Seletor de Cores: Um seletor de cores universal que exibe os valores RGB e HEX de qualquer ponto da tela. `win + Shift + c`
* Localizar Meu Mouse: Criar um foco no mouse `Ctrl Ctrl`
* Espiada: Extensões no Explorador de Arquivos: `Ctrl + space`
* Miniaturas de arquivor: permite visualizar arquivos como svg e md no Explorador de arquivos. 
* Extrator de Texto: Extrai texto de imagens ou outras fontes visuais usando OCR. `win + Shift + t`
* PowerToys Run: Um lançador rápido de aplicativos e comandos, semelhante ao Spotlight no macOS. `alt + space`
* Colar avançado: permite colocar o conteúdo da área de transferência em qualquer formato necessário. `win + Shift + v`


## Editor de código
Estas são algumas opções de editores de código: 

1. [Sublime Text](https://www.sublimetext.com/): Editor de texto leve, rápido e eficiente, ideal para programadores e escritores. Tem suporte para JSX e TypeScript, realce de sintaxes e preenchimento automático embutidos.
2. [Atom](https://github.blog/news-insights/product-news/sunsetting-atom/): Editor de texto altamente personalizável, desenvolvido pelo GitHub.
3. [JetBrains IntelliJ IDEA](https://www.jetbrains.com/): IDE poderosa para desenvolvimento profissional, com suporte a várias linguagens. [Gratuita para alunos e professores](https://www.jetbrains.com/community/education/).
4. [Neovim](https://neovim.io/): Editor de texto avançado baseado no Vim, com foco em extensibilidade e modernidade.
5. [Eclipse](https://www.eclipse.org/): IDE open source, amplamente usada para desenvolvimento em Java e outras linguagens.
6. **[+indicado]** [VSCode](https://code.visualstudio.com/): Editor de código da Microsoft, amplamente utilizado, com suporte a extensões, depuração e diversas linguagens.
7. WebStorm é um ambiente de desenvolvimento integrado projetado especificamente para JavaScript.

A página abaixo descreve o VSCode e indica extensões úteis:

[VSCode](VSCODE.md)
