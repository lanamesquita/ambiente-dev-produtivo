# 💻 VSCode
O Visual Studio Code (VSCode) é um editor de código-fonte (não é uma IDE) gratuito e de código aberto, desenvolvido pela Microsoft, projetado para diversas linguagens de programação. Ele combina simplicidade, desempenho e extensibilidade, tornando-se uma das ferramentas mais populares entre programadores.

![VSCode](images/vscode.jpg)

## 🌟 Características do VSCode

1. **Extensões e Personalização**: vasta gama de extensões no marketplace e interface altamente customizável com temas e atalhos. Configure o Settings Sync para fazer backup das suas configurações.
2. **Depurador Integrado**: possui ferramentas robustas para depuração de código diretamente no editor.
3. **Git e Controle de Versão**: possui integração nativa com Git.
4. **IntelliSense**: autocompletar inteligente.
5. **Terminal Integrado**: Terminal embutido para executar comandos diretamente no editor.
6. **Live Share**: possibilita a colaboração em tempo real com outros desenvolvedores.
7. **Interface Amigável**: Design intuitivo e leve, ideal para iniciantes e profissionais.
8. **Suporte a Linguagens**: compatível com várias linguagens de programação.
9. **Comunidade Ativa**: Grande comunidade que desenvolve extensões e fornece suporte.
10. **Leve e rápido**: quando comparado a outras IDEs.
11. **Docker**: Suporte a desenvolvimento remoto e Docker.

## 🛠️ Extensões

![Extensões](images/extensions.jpg)

Extensões interessantes e úteis no VSCode:

### [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
Um corretor ortográfico básico que funciona bem com códigos e documentos. Importe o [Brazilian Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian). 

### [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
Na tentativa de resolver [Tabs x Spaces](https://www.youtube.com/watch?v=oRva7UxGQDw), Prettier é um formatador de código opinativo.

![Tabs vs Spaces](https://media.crystallize.com/crystallize_marketing/images/648_developer_comics_tabs_vs_spaces.jpg)

Comandos:
1. `Ctrl + Shift + P` -> Format Document 
2. Selecione o texto -> `Ctrl + Shift + P` -> Format Selection

### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
A extensão Docker facilita a criação, o gerenciamento e a implantação de aplicativos em contêineres.

### Dev Containers
A extensão Dev Containers permite que você use um contêiner Docker como um ambiente de desenvolvimento completo, de forma isolada e portátil. Utiliza um arquivo `.devcontainer` para configurar automaticamente o ambiente do contêiner, incluindo dependências, extensões e configurações específicas.

### Extensões de Controle de Versão
* [Github Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github): permite que você revise e gerencie solicitações de pull e problemas do GitHub.
* [Github Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub): permite que você navegue, pesquise, edite e faça commit rapidamente em qualquer repositório remoto do GitHub.
* [Github Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions): gerencie seus fluxos de trabalho e visualize o histórico de execução.
* [Git Blame](https://marketplace.visualstudio.com/items?itemName=solomonkinard.git-blame): mostra quem alterou uma linha de código. 
* [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): oferece funcionalidades avançadas do Git, como anotações e hovers personalizáveis.

### AI
* [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot): Ferramenta de programação assistida por IA. Gratuito para estudantes e professores no [GitHub Student Developer Pack](https://education.github.com/pack).

![Copilot em Ação](https://github.com/microsoft/vscode-copilot-release/blob/main/images/readme-gif.gif?raw=true)

* [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat): formato de chat para o Copilot.

### [WSL (Windows)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
A extensão WSL permite que você use o VSCode no Windows para criar aplicativos Linux que são executados no WSL.

![Visual Studio Code Remote - WSL](https://microsoft.github.io/vscode-remote-release/images/remote-wsl-open-code.gif)

### Requests
* [Rest Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client): envie solicitações HTTP e visualize a resposta diretamente no VSCode.
* [Postman](https://marketplace.visualstudio.com/items?itemName=humao.rest-client): Desenvolva e teste suas APIs diretamente no VSCode.

### [Live Share](https://visualstudio.microsoft.com/pt-br/services/live-share/)
Compartilhe seus códigos e colabore em tempo real.

![Live Share Hero](https://visualstudio.microsoft.com/wp-content/uploads/2023/02/liveshare-hero-optimized.png)

### [Figma for VSCode](https://marketplace.visualstudio.com/items?itemName=figma.figma-vscode-extension)
Navegue e inspecione arquivos de design diretamente no VSCode.
![Design no Figma](https://static.figma.com/uploads/a4510b0ae063e1ae709281f30ef95f974299e6b5)

### [GitHub Theme para VSCode](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
Temas de alto contraste para o VSCode.

### [SonarQube for IDE](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
Detecta problemas de codificação, como bugs e vulnerabilidades, em tempo real.

### [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
O ESLint analisa estaticamente seu código para encontrar problemas rapidamente.

## 🛠️ Configurações no VSCode

### Backup e sincronização das configurações do VSCode
Ative o backup e sincronização com o servidor do GitHub: [Settings Sync](https://code.visualstudio.com/docs/editor/settings-sync).

### Modo de salvamento de arquivos
Ative clicando em `File` > `Auto Save`.

### Selecionar texto no terminal com o mouse
Ative: `"terminal.integrated.copyOnSelection": true`.

## 💡 Outras dicas

### [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
Adiciona ferramentas de depuração do React ao navegador. Veja mais detalhes no [React Developer Tools](https://pt-br.react.dev/learn/react-developer-tools).
