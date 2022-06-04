# **HTML / CSS**

Olá! Neste projeto, construímos uma simplificação do [site da Conpec](https://www.conpec.com.br/) usando HTML e CSS. Para entender mais sobre o projeto e conseguir baixá-lo e rodá-lo em sua máquina, siga as instruções a seguir

## **Sobre a Estrutura de Pastas do Projeto (Arquitetura)**

```
├── node_modules <- pasta gerada automaticamente pelo npm; onde ficam as bibliotecas baixadas
│
└── src <- pasta com o conteúdo do projeto desenvolvido (site)
    │
    ├── assets <- imagens e vídeos
    │
    └── pages  <- códigos .html e .css
        │
        └── Home
            │
            ├── index.html <- estrutura da Home
            │
            └── style.css  <- estilização da Home
│
├── README.md <- instruções sobre instalação e uso do projeto
│
├── package-lock.json <- arquivo de configuração do projeto gerado automaticamente pelo npm
│
└── package.json <- lista de dependências do projeto (bibliotecas instaladas) gerada pelo npm
```

Vale lembrar que a ideia da pasta ```pages``` é ter, dentro dela, uma pasta para cada página a ser desenvolvida no site, nomeada com o próprio nome dessa página. Aqui dentro, teremos um arquivo .html (nomeado com o nome da página) e um arquivo .css com as estilizações feitas nesssa página.

> Atenção! Essa arquitetura de projeto é apenas uma sugestão de como vocês podem estruturar futuros projetos de site, mas ela pode (e deve) ser alterada caso vocês sintam que a arquitetura não faz sentido para as necessidades de um cliente, projeto ou equipe de desenvolvimento

## **Baixando o Projeto em seu Computador**

1. Abra um terminal

2. Navegue até a pasta onde você deseja salvar o projeto com o comando ```cd```

> Alternativamente, você pode entrar no seu gerenciador de arquivos, clicar com o botão direito na pasta em que você deseja salvar o projeto, e selecionar a opção "Abrir no Terminal"

3. Rode o seguinte comando: ```git clone ``` 

## **Instalação e Setup**

### *Instale Extensões no navegador (opcional)*

Essa etapa não precisa ser cumprida para que você consiga rodar o site no seu computador, mas deixo aqui a recomendação de 2 extensões para o navegador ```Google Chrome``` (ou para a versão open source dele, o ```Chromium```) que podem ser úteis durante o desenvolvimento de um site:

- [Color by Fardos - Color Picker](https://chrome.google.com/webstore/detail/color-by-fardos-color-pic/iibpgpkhpfggipbacjfeijkloidhmiei) (te permite verificar o padrão RGB das cores usadas num site)

- [Find website used fonts](https://chrome.google.com/webstore/detail/find-website-used-fonts/lnebjgioddkafaldaaeooeghlcholnnp) (te mostra uma lista com todas as fontes usadas num site)

### *Instale extensões no vscode (opcional)*

- [Colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize) (display RGB colors in vscode)
- [Emoji](https://marketplace.visualstudio.com/items?itemName=Perkovec.emoji) (insert emojis in your code)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (config and automatic validate javascript code format)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) (connect git with vscode)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (run web pages in real time)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) (code formatter)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) (add icons in folders ans files in vscode)

### *Instale as Dependências (bibliotecas) do Projeto*

Abra um terminal e rode:
```
npm install
```

> para instalar node e npm, siga: https://nodejs.org/en/download/ 

> se você usa um sistema operacional *Linux*, *macOS* ou então o *WindowsWSL* (ferramente que permite a execução de um ambiente Linux dentro do Windows), node e npm também podem ser instalados através do nvm (Node Version Manager): https://github.com/nvm-sh/nvm#installing-and-updating

Ou, alternativamente, rode:
```
yarn install
```

> para instalar o yarn, siga: https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable

> Atenção! npm (Node Package Manager) e yarn são ferramentas poderosas para instalar bibliotecas em nossos projetos. A diferença entre eles é que o yarn tem mais recursos de cache e segurança que o npm, mas na prática ambos funcionam da mesma maneira!

## **Execução**

1. Baixe a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) do vscode

2. Caso a extensão não seja habilitada automaticamente após a instalação, habilite ela através no vscode:

    - digite ```Ctrl + Sfift + X``` para entrar na área de extensões do vscode
    - procure pela extensão Live Server na barra de pesquisas e clique nela
    - clique no botão ```Habilitar``` que deve aparecer na tela de informações sobre a extensão

3. Clique com o botão direito num arquivo .html que você gostaria de ver no navegador padrão do seu computador

4. Clique na opçẽo "Abrir com Live Server" (deve ser a primeira opção disponível)