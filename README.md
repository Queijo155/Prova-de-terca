# TechPulse - Portal de Notícias de Tecnologia

Primeira versão da página inicial do portal TechPulse, feita com HTML5 e CSS3, com estrutura e estilo separados e layout que funciona em computador e celular.

## Estrutura do projeto

- index.html: página inicial (estrutura)
- style.css: arquivo de estilo (aparência)
- README.md: documentação do projeto

## Tecnologias e serviços utilizados

- HTML5: estrutura e semântica (header, nav, main, article, footer)
- CSS3: estilização em arquivo externo, Box Model e media query
- Git e GitHub: versionamento e hospedagem do repositório
- Picsum Photos: serviço gratuito de imagens usado na capa

## Especificações técnicas

- Seletor de tag: body, h2, p, img, ul, footer
- Classe reutilizável: .botao (link estilizado como botão)
- ID exclusivo: #cabecalho
- Box Model: padding, border e margin no cabeçalho, no article, no botão e no rodapé
- Responsividade: meta viewport e media query para telas de até 600px

## Justificativas

### Cores

- Azul escuro (#0d1b2a): cabeçalho e rodapé. Passa seriedade e remete à tecnologia.
- Azul ciano (#00b4d8): botão e detalhes. Destaca os elementos clicáveis.
- Cinza claro (#f4f6f8): fundo da página. Deixa a leitura mais confortável.
- Branco (#ffffff): cartão de conteúdo. Dá contraste com o fundo.
- Branco translúcido (rgba(255,255,255,0.8)): texto do rodapé. Deixa o rodapé discreto.

### Letras (tipografia)

Foi usada a fonte Arial, sem serifa, por ser simples e fácil de ler em qualquer tela. O título principal tem 36px, o subtítulo 26px e o texto corrido 18px, criando uma hierarquia visual clara. Os títulos são centralizados e os parágrafos justificados.

### Espaços

- Padding no cabeçalho, no article e no botão, para o conteúdo não ficar colado nas bordas.
- Margin entre as seções, para separar bem os blocos.
- Border no botão e no article, para dar acabamento visual.
- Largura máxima de 800px no conteúdo, para manter a leitura confortável.

## Sitemap visual

- Página Inicial (TechPulse)
  - Notícias
    - Inteligência Artificial
    - Hardware
    - Software
  - Reviews
    - Smartphones
    - Notebooks
    - Games
  - Tutoriais
    - Programação
    - Redes
    - Segurança Digital
  - Sobre
    - Equipe
    - Contato

## Hierarquia de conteúdo e taxonomia

- Nível 1: página inicial, que reúne todos os assuntos do portal.
- Nível 2: seções principais (Notícias, Reviews, Tutoriais e Sobre), que aparecem no menu de navegação.
- Nível 3: subcategorias, que organizam o conteúdo por assunto específico.

A taxonomia agrupa os conteúdos por tema, do mais geral para o mais específico. Assim o leitor encontra o que procura em poucos cliques e cada matéria pertence a uma categoria clara, sem duplicidade.
