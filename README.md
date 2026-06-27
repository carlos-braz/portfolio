# Portfólio

Site estático de portfólio pessoal desenvolvido com HTML, CSS e JavaScript simples. O projeto apresenta informações sobre Carlos, sua formação, exemplos de trabalhos e um formulário de contato com validação básica de e-mail no navegador.

## Proposta

O objetivo do projeto é servir como uma página pessoal organizada, leve e fácil de publicar, reunindo:

- apresentação pessoal;
- formação acadêmica e cursos;
- lista de projetos e exemplos de atuação;
- formulário para solicitação de contato ou proposta de serviço.

## Páginas

- `index.html`: página inicial com acesso às seções principais.
- `sobre-mim.html`: apresentação pessoal e interesses na área de tecnologia.
- `formacao.html`: escolaridade, formação acadêmica e cursos complementares.
- `portfolio.html`: exemplos de sites e aplicações web.
- `contato.html`: formulário de contato com validação de e-mail.

## Tecnologias

- HTML5
- CSS3
- JavaScript

O projeto não depende de frameworks, bibliotecas externas ou processo de build.

## Estrutura

```text
.
├── index.html
├── sobre-mim.html
├── formacao.html
├── portfolio.html
├── contato.html
├── nav.css
└── box.png
```

## Como executar localmente

Como o site é estático, existem algumas formas simples de executar localmente.

### Abrindo diretamente no navegador

Abra o arquivo `index.html` no navegador.

### Usando Python

```bash
python3 -m http.server 8000
```

Depois, acesse:

```text
http://localhost:8000
```

### Usando PHP

```bash
php -S localhost:8000
```

Depois, acesse:

```text
http://localhost:8000
```

### Usando Node.js com npx

```bash
npx serve .
```

O terminal informará o endereço local para acesso, geralmente algo como:

```text
http://localhost:3000
```

### Usando a extensão Live Server

No Visual Studio Code, instale a extensão Live Server, abra a pasta do projeto e execute a opção `Open with Live Server` no arquivo `index.html`.

## Manutenção

- Edite os arquivos `.html` para atualizar conteúdo, links e textos.
- Edite `nav.css` para ajustar layout, cores, responsividade e estilos do formulário.
- Substitua `box.png` caso queira alterar a imagem usada nos cards da página inicial.

## Status

Projeto em formato de site estático funcional, adequado para estudos, apresentação pessoal e evolução incremental do portfólio.
