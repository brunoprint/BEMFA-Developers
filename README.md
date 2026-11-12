# BEMFA Developers

Site institucional da **BEMFA Developers**, equipe formada por estudantes do curso de Desenvolvimento de Software Multiplataforma (DSM) da Fatec Itapira. O site apresenta a equipe, seus integrantes e projetos acadêmicos.

## Sobre o site

Este repositório contém um site estático feito com HTML e CSS. A página inicial reúne a apresentação da equipe, cartões com links para os perfis dos integrantes e páginas com informações sobre os projetos. Não há dependências de instalação, etapa de compilação ou servidor de aplicação necessários para visualizar o site.

## Conteúdo

- **Equipe:** cinco integrantes, com páginas individuais que apresentam perfil, competências, interesses, participação nos projetos e links de contato.
- **GoraGo:** projeto interdisciplinar do primeiro semestre, voltado à busca e inscrição em vagas de estágio e emprego.
- **SGCB:** projeto do segundo semestre, voltado à gestão de contêineres, contratos, clientes e usuários da empresa cliente.

As páginas dos projetos descrevem as tecnologias e funcionalidades planejadas ou desenvolvidas para cada trabalho. Elas não significam que essas tecnologias façam parte da implementação deste site institucional.

## Tecnologias

### Site institucional

- HTML5
- CSS3
- Imagens PNG e logotipos SVG

### Tecnologias mencionadas nas páginas dos projetos

- **GoraGo:** HTML, CSS e JavaScript.
- **SGCB:** HTML5, CSS3, PHP e JavaScript.

## Como visualizar

### Abrir diretamente

Abra `index.html` em um navegador. Os links entre as páginas e os recursos usam caminhos relativos, portanto a estrutura de pastas deve ser mantida.

### Servir localmente

Também é possível iniciar um servidor HTTP estático na pasta do projeto. Por exemplo, com Python instalado:

```bash
python -m http.server 8000
```

Em seguida, acesse <http://localhost:8000>. Não é necessário instalar pacotes ou compilar os arquivos.

## Navegação

1. A página inicial apresenta a equipe e lista os integrantes e projetos.
2. Selecione um integrante para abrir seu perfil.
3. Selecione GoraGo ou SGCB para abrir a respectiva página de detalhes.
4. Nas páginas internas, use **Página principal** para voltar ao início.

## Interface e acessibilidade

- Layout responsivo, com ajustes para telas estreitas.
- Textos alternativos nas imagens e rótulos acessíveis nos cartões de navegação.
- Indicação visual de foco para navegação por teclado.
- Animações de entrada e efeitos visuais feitos em CSS, com suporte à preferência de movimento reduzido do sistema.
- Páginas em português do Brasil (`pt-BR`).

## Manutenção

- Ao adicionar um integrante, inclua seu retrato em `images/`, crie a página em `perfis/` e atualize o cartão correspondente em `index.html`.
- Ao adicionar um projeto, inclua seu logotipo em `images/`, crie a página em `projetos/` e atualize a lista de projetos em `index.html`.
- Preserve os caminhos relativos dos arquivos e os estilos compartilhados de cada seção.

## Equipe

| Integrante | Atuação apresentada no site |
|---|---|
| Alex Silva | Desenvolvimento Back-End |
| Bruno Gabriel | Desenvolvimento Front-End e documentação técnica |
| Eduardo Sales | Desenvolvimento Front-End e documentação técnica |
| Fabricio Teodoro | Desenvolvimento Full Stack |
| Mauro Yida | Project Owner |