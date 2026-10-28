# Zingen

Landing page do **Zingen**, um aplicativo fictício de karaokê. Este projeto foi desenvolvido durante o curso da **Formação Fullstack da Rocketseat**, como prática de construção de interfaces com HTML e CSS.

## Sobre o projeto

A página apresenta o aplicativo e suas funcionalidades, exibe opções de assinatura e convida o visitante a baixar o app. O conteúdo está em português e a interface foi organizada em seções navegáveis por links internos.

## Conteúdos praticados

- **HTML semântico:** estruturação da página com `header`, `nav`, `main`/`section` e `footer`, títulos, listas e links.
- **Acessibilidade básica:** textos alternativos para imagens, rótulos acessíveis em links e uso de elementos semânticos.
- **CSS organizado em módulos:** estilos separados por responsabilidade e reunidos por `@import` em `styles/index.css`.
- **Fundamentos de CSS:** reset, seletores, pseudo-classes, cores, tipografia, espaçamento e fundos.
- **Variáveis CSS:** tokens de cores, fontes, tamanhos e espaçamentos definidos em `:root`.
- **Layouts:** composição com Flexbox e CSS Grid, incluindo colunas de larguras iguais e alinhamento de elementos.
- **Responsividade:** ajustes por media query para telas maiores e classes para elementos exibidos apenas no desktop.
- **Navegação e experiência:** âncoras para navegar entre seções e rolagem suave.
- **Recursos visuais:** uso de imagens, ícones e fontes externas (Google Fonts).

## Seções da página

- **Início:** chamada principal para conhecer e baixar o aplicativo.
- **Conheça o app:** apresentação da proposta do Zingen e do uso de inteligência artificial no karaokê.
- **Funcionalidades:** biblioteca de músicas, experiência gamificada, gravação, comunidade e letras em tempo real.
- **Planos e preços:** comparação entre os planos Básico, Premium e Família.
- **Download:** chamadas para baixar o aplicativo pela App Store ou Google Play.
- **Rodapé:** navegação agrupada por produto, empresa e informações legais, além de links sociais.

## Estrutura de arquivos

```text
.
├── index.html
├── README.md
├── assets/
│   ├── icons/
│   └── imagens, ilustrações, logotipo e botões de loja
└── styles/
    ├── index.css       # ponto de entrada e imports
    ├── global.css      # reset, tokens e estilos globais
    ├── utility.css     # classes utilitárias e layout responsivo
    └── ...             # estilos por componente e seção
```

## Como visualizar

Não há etapa de build ou dependências para instalar. Abra `index.html` diretamente no navegador ou use a extensão **Live Server** no Visual Studio Code para servir a página localmente.

As fontes são carregadas do Google Fonts; para obtê-las, é necessária conexão com a internet. As demais imagens e folhas de estilo são arquivos locais do projeto.
