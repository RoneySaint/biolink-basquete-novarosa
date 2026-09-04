# Basquete Nova Rosa da Penha — BioLink

BioLink criado para centralizar os principais canais e informações do Basquete Nova Rosa da Penha, em Cariacica - ES.

Projeto em produção: [biolink-basquete-novarosa.pages.dev](https://biolink-basquete-novarosa.pages.dev/)

## Sobre o projeto

O Basquete Nova Rosa da Penha precisava de uma página simples para reunir informações úteis em um único endereço. O BioLink concentra acesso à comunidade, redes sociais, horários de jogo, localização das quadras, rotas de chegada e parceiros do projeto.

A implementação foi feita como site estático para manter o carregamento leve, a manutenção simples e o deploy direto pelo Cloudflare Pages.

## Funcionalidades

- Centralização de links importantes do projeto.
- Acesso ao grupo do WhatsApp.
- Link para o Instagram do Basquete Nova Rosa da Penha.
- Horários dos jogos aos domingos e às terças-feiras.
- Links de localização das quadras no Google Maps.
- Orientações de chegada por linhas de ônibus.
- Lista de patrocinadores e parceiros com links públicos.

## Tecnologias

- HTML5
- CSS3
- JavaScript mínimo para inicialização de ícones
- Lucide Icons via CDN
- Git e GitHub
- Cloudflare Pages

## Estrutura do projeto

```text
.
|-- assets/
|-- index.html
|-- styles.css
`-- README.md
```

## Responsividade

O BioLink foi desenvolvido para funcionar bem em diferentes tamanhos de tela, com layout adaptado para navegação em celulares e desktops.

## Deploy

O projeto está publicado via Cloudflare Pages como uma página estática.

Configuração usada no deploy:

- Framework preset: `None`
- Build command: vazio
- Build output directory: `/`

## Como executar localmente

Abra o arquivo `index.html` diretamente no navegador.

Outra opção é servir a pasta localmente:

```bash
python -m http.server
```

Acesse `http://localhost:8000`.

## Aprendizados

Este projeto demonstra a construção de uma página estática de uso real, com organização de assets, responsividade, aplicação de identidade visual e publicação em uma plataforma de deploy estático.

## Status

Projeto funcional e em produção via Cloudflare Pages.

## Assets e direitos

Este projeto utiliza a identidade visual do Basquete Nova Rosa da Penha, além de logotipos e imagens de parceiros e patrocinadores. As marcas, logotipos e demais materiais de terceiros pertencem aos seus respectivos titulares e são utilizados apenas para fins de representação e divulgação.

Esses materiais não estão licenciados para reutilização, redistribuição ou uso comercial por terceiros.

## Licença

Este repositório não possui licença de código aberto. Todos os direitos sobre o código permanecem reservados ao autor, salvo indicação expressa em contrário.

## Autor

Roney Santo's
