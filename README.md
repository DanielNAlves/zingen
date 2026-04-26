# Zingen

Landing page responsiva de um aplicativo ficticio de karaoke, desenvolvida com HTML e CSS.

## Visao geral

O `Zingen` e uma pagina institucional de produto com foco em apresentacao comercial. O layout foi estruturado para destacar proposta de valor, funcionalidades, planos e chamada para instalacao do aplicativo.

### Objetivos da pagina

- apresentar o produto e seus diferenciais;
- comunicar funcionalidades de forma visual;
- detalhar opcoes de assinatura;
- conduzir o usuario para a secao de download.

## Tecnologias

- HTML5
- CSS3
- Google Fonts

## Estrutura do projeto

```text
zingen/
├── assets/          # imagens, ilustracoes, icones e logos
├── styles/          # estilos organizados por secao/componente
└── index.html       # ponto de entrada da aplicacao
```

## Como executar localmente

Por ser um projeto estatico, nao ha dependencias ou etapa de build.

### Execucao simples

1. Abra a pasta do projeto.
2. Execute o arquivo `index.html` no navegador.

### Execucao recomendada (ambiente de desenvolvimento)

1. Abra o projeto no Cursor ou VS Code.
2. Instale a extensao Live Server.
3. Inicie o servidor a partir de `index.html` com a opcao **Open with Live Server**.

## Mapeamento de secoes

- `#hero`: mensagem principal e chamadas para acao;
- `#about`: apresentacao do aplicativo;
- `#features`: grade de funcionalidades;
- `#pricing`: planos Basico, Premium e Familia;
- `#download`: botoes para lojas de aplicativos;
- `footer`: navegacao complementar e redes sociais.

## Consideracoes tecnicas

- arquitetura de estilos modularizada em arquivos CSS por contexto;
- marcacao sem dependencia de frameworks;
- links com `href="#"` representam pontos de integracao ainda nao conectados.

## Contexto

Projeto academico de front-end desenvolvido na trilha da Rocketseat.
