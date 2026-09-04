# Basquete Nova Rosa da Penha - BioLink

BioLink estatico criado para centralizar os principais canais, horarios, locais de jogo e parceiros da comunidade Basquete Nova Rosa da Penha, em Cariacica - ES.

Projeto em producao: [biolink-basquete-novarosa.pages.dev](https://biolink-basquete-novarosa.pages.dev/)

## Sobre o projeto

O projeto organiza informacoes publicas do Basquete Nova Rosa da Penha em uma pagina simples, direta e responsiva. A proposta e facilitar o acesso ao grupo da comunidade, redes sociais, locais das quadras, orientacoes de chegada e patrocinadores.

A solucao foi mantida como site estatico para reduzir complexidade, facilitar manutencao e permitir deploy rapido pelo Cloudflare Pages.

## Funcionalidades

- Acesso ao grupo do WhatsApp da comunidade.
- Link para o Instagram do projeto.
- Horarios dos jogos de domingo e terca-feira.
- Links de localizacao das quadras no Google Maps.
- Orientacoes de chegada por linhas de onibus.
- Area de patrocinadores e parceiros com links publicos.
- Footer com credito do desenvolvedor.

## Tecnologias

- HTML5
- CSS3
- JavaScript minimo para inicializacao dos icones Lucide
- Lucide Icons via CDN
- Git e GitHub
- Cloudflare Pages

## Estrutura

```text
.
|-- assets/
|   |-- calendar-icon.png
|   |-- ilario-reis-logo.png
|   |-- instagram-icon.png
|   |-- newrose-logo-transparent.png
|   |-- santos-dev-logo.png
|   |-- sbcustom-logo.png
|   |-- sixstreet-logo.png
|   |-- sponsor-icon.png
|   `-- whatsapp-icon.png
|-- index.html
|-- styles.css
`-- README.md
```

## Responsividade

O layout foi desenvolvido para funcionar em telas desktop e mobile, com ajustes de grade, espacamento e legibilidade para dispositivos menores.

## Deploy

O deploy utiliza Cloudflare Pages com uma configuracao estatica simples:

- Framework preset: `None`
- Build command: vazio
- Build output directory: `/`

Nenhuma credencial, token ou configuracao privada e necessaria no repositorio.

## Como executar localmente

Por ser um projeto estatico, basta abrir o arquivo `index.html` no navegador.

Tambem e possivel servir a pasta localmente:

```bash
python -m http.server
```

Depois, acesse `http://localhost:8000`.

## Aprendizados

Este projeto demonstra:

- estruturacao de pagina estatica;
- organizacao de assets;
- aplicacao de identidade visual em um produto real;
- design responsivo sem uso de framework;
- preparacao de projeto simples para deploy estatico;
- documentacao de repositorio para portfolio.

## Status

Projeto funcional e em producao via Cloudflare Pages.

## Assets e direitos

O repositorio utiliza logos e imagens associadas ao Basquete Nova Rosa da Penha, patrocinadores/parceiros e ao desenvolvedor. Antes de tornar o repositorio publico, confirme se todos os assets podem ser exibidos publicamente no GitHub.

## Licenca

Este repositorio ainda nao possui uma licenca definida.

## Autor

Roney Santo's
