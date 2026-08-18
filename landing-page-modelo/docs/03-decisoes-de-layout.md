# Decisões de Layout

## Estrutura semântica
O documento utiliza header, main, nav, section e footer para organizar o
conteúdo. Cada section representa um bloco de informação independente,
acessível pelo menu por meio de um identificador (id).

## Grid e componentes
O layout utiliza o sistema de grid do Bootstrap (container, row, col-*) para
garantir alinhamento e responsividade sem a necessidade de reescrever regras
de layout já resolvidas pelo framework.

## Navegação fixa
A navbar utiliza a classe fixed-top para permanecer visível durante a
rolagem. Para compensar a sobreposição do cabeçalho fixo sobre o conteúdo,
foi definido um padding-top no body.

## Paleta de cores
A cor de destaque segue o verde padrão do Bootstrap (text-success /
btn-success), reforçando a identidade institucional e mantendo contraste
adequado sobre fundo branco e fundo claro (bg-light).

## Cards para conteúdo repetitivo
Vagas, indicadores e competências foram organizados em cards, pois esse
padrão visual facilita a leitura de blocos de informação semelhantes e
repetidos ao longo da página.

## CSS próprio
Apesar do uso do Bootstrap, foi criado um arquivo CSS próprio (style.css)
para ajustes específicos do projeto, como o espaçamento entre seções, o
tamanho da logo, o link de pular para o conteúdo (skip link) e o respeito à
preferência de redução de movimento do usuário.

## Caminhos relativos
Todos os arquivos internos (imagens, ícones, CSS) são referenciados por
caminhos relativos, evitando problemas de publicação no GitHub Pages.

## Origem dos dados exibidos
Os cards da seção de vagas, os indicadores da seção de pesquisa e os badges
da seção de tecnologias refletem os resultados reais da pesquisa exploratória
descrita em docs/01-visao-geral.md, coletada entre 01/08/2026 e 04/08/2026
nas plataformas LinkedIn, Infojobs e Jobsora. As referências completas das
vagas consultadas estão em docs/05-referencias.md.
