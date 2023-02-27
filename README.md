# Data Lovers

## Índice

* [1. Preâmbulo](#1-preâmbulo)
* [2. Resumo do projeto](#2-resumo-do-projeto)
* [3. Objetivos de aprendizagem](#3-objetivos-de-aprendizagem)
* [4. Definição de produto](#4-definição-de-produto)
* [5. Protótipos](#5-protótipos)
* [6. Testes de usabiliade](#6-testes-de-usabilidade)
* [7. Testes unitários](#7-testes-unitários)
* [8. Checklist](#8-checklist)

***

## 1. Preâmbulo

Segundo a
[Forbes](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read)
90% dos dados que existem hoje foram gerados durante os últimos dois anos. A
cada dia geramos 2.5 milhões de terabytes de dados, uma cifra sem precedentes.

Apesar disso, os dados por si só são de pouca utilidade. Para que essas grandes
quantidades de dados se convertam em **informação** compreensível para os
usuários, precisamos entender e processar estes dados. Uma forma simples de
fazer isso é criando _interfaces_ e _visualizações_.

Na imagem seguinte, você pode ver como os dados que estão na parte esquerda
podem ser usados para construir a interface amigável e compreensível que está na
parte direita.

![json-interface](https://lh4.googleusercontent.com/Tn-RPXS26pVvOTdUzRT1KVaJ-_QbFs9SpcGLxSPE43fgbHaXtFgMUInuDt7kV41DkT1j8Tt29V0LxQW7SMtC6digOIhfTXSBKdwI08wUwhD3RAqlwy0hjfmhZ2BFe91mtmCSEqysfgk)

## 2. Resumo do projeto

Neste projeto proposto pela Laboratoria, construimos uma página web para visualizar um conjunto (set) de dados que se adeque às necessidades do nosso usuário. Como itens excenciais era necessário uma página web que permita visualizar dados, filtrá-los, ordená-los e fazer algum cálculo agregado.

Definimos nossa área de interesse diante dos temas propostos e procuramos entender quem seria nosso usuário e o que exatamente ele necessitaria saber ou ver, para assim conseguir construir uma interface que o ajude a interagir e entender melhor os dados.

Este foi nosso "dado" escolhido:

* [Pokémon](src/data/pokemon/pokemon.json): Neste conjunto você encontrará uma
  lista com os 151 Pokémon da região de Kanto, com suas respectivas estatísticas
  utilizadas no jogo [Pokémon GO](http://pokemongolive.com).
  - [Pesquisa com jogadores de Pokémon Go](src/data/pokemon/README.pt-BR.md)


O objetivo principal deste projeto foi aprender a desenhar e construir uma
interface web onde se possa visualizar e manipular dados, entendendo o que o
usuário necessita.

## 3. Objetivos de aprendizagem

Neste projeto tinhamos objetivos claros, que foram acordados mediante dialogos ou necessidades para o andamento do projeto. Esses objetivos estão listados a seguir:

- [ ] **Uso de HTML semântico**

- [ ] **Uso de seletores de CSS**

- [ ] **Empregar modelo de caixa (box model): borda, margem, preenchimento**

- [ ] **Uso de flexbox em CSS**

- [ ] **Uso de seletores de DOM**

- [ ] **Manipulação de eventos de DOM (listeners, propagação, delegação)**

- [ ] **Manipulação dinâmica de DOM**

- [ ] **Diferenciar entre tipos de dados primitivos e não primitivos**

- [ ] **Arrays (arranjos)**

- [ ] **Objetos (key, value)**

- [ ] **Variáveis (declaração, atribuição, escopo)**

- [ ] **Uso de condicionais (if-else, switch, operador ternário, lógica booleana)**

- [ ] **Uso de laços (while, for, for..of)**

- [ ] **Funções (params, args, return)**

- [ ] **Testes unitários (unit tests)**

- [ ] **Módulos de ECMAScript (ES modules)**

- [ ] **Uso de linter (ESLINT)**

- [ ] **Uso de identificadores descritivos (Nomenclatura e Semântica)**

- [ ] **Diferença entre expressões (expressions) e declarações (statements)**

- [ ] **Git: Instalação e configuração**

- [ ] **Git: Controle de versão com git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integração de mudanças entre ramos (branch, checkout, fetch, merge, reset, rebase, tag)**

- [ ] **GitHub: Criação de contas e repositórios, configuração de chave SSH**

- [ ] **GitHub: Implantação com GitHub Pages**

- [ ] **GitHub: Colaboração pelo Github (branches | forks | pull requests | code review | tags)**

- [ ] **Desenhar e desenvolver um produto ou serviço colocando as usuárias no centro**

- [ ] **Criar protótipos para obter feedback e iterar**

- [ ] **Aplicar os princípios de desenho visual (contraste, alinhamento, hierarquia)**

- [ ] **Planejar e executar testes de usabilidade**

## 4. Definição de produto

O projeto foi construido para jogadores de POKEMON GO. Onde os usuários pudessem ter uma série de informações dos pokemons para assim escolher quais captura-los.

Com tais informações sua escolha será mais precisa na hora de jogar. Para auxiliar na busca, o projeto conta com a barra de pesquisa, o filtro por tipo, e a opção de ordenar.

### Histórias de usuários

Para a excução correta do projeto, planejamos um protótimo capaz de suprir as necessidades de nosso publico alvo. Partindo de nossas histórias de usuario.

1 - Eu como jogador novato de Pokemon Go, quero ter acesso a uma lista de pokemons para conhecê-los;
2 - Eu como jogador quero saber características únicas de cada pokémons para me ajudar nas decisões durante o jogo;
3 - Eu como mestre pokemon quero saber quantas e quais são as evoluções dos pokemons e tambem quantos candies serão necessários para um pokemon evoluir.

Ao acessar o site, o usuário clica na pokebola e vai visualizar todos os Pokemóns.
Cada card possui na parte frontal informações como: peso, altura, raridade, e geração. Ao passar o mouse pelo card, o mesmo vira e trás informações de: fraqueza, resistência, evoluções e quantos candies são necessários para sua evolução.


## 5. Protótipos

Uma vez tendo essa referências do tópico acima, seguimos para o desenvolvimento de dois protótipos. Um voltado para desktop e outro para mobile.

### Protótipo de baixa fidelidade

Inserir protótipo....

### Protótipo de alta fidelidade

Inserir protótipo....


## 6. Testes de usabilidade

Fizemos testes de usabilidades e constatamos que os cards dos pokemons....

## 7. Testes unitários

Durante o projeto escrevemos nossos testes unitários para as funções encarregadas de processar, filtrar e ordenar os dados, assim como calcular estatísticas.

Nossos testes unitários tiveram uma cobertura mínima de ___ de statements (sentenças), functions (funções), lines (linhas), e branches (ramos) do arquivo src/data.js


## 8. Checklist

* [✓] Usar VanillaJS.
* [✓] Passa pelo linter (`npm run pretest`)
* [✓] Passa pelos testes (`npm test`)
* [✓] Testes unitários cobrem um mínimo de 70% de statements, functions, lines e
  branches.
* [✓] Inclui uma _definição de produto_ clara e informativa no `README.md`.
* [✓] Inclui histórias de usuário no `README.md`.
* [✓] Inclui rascunho da solução (protótipo de baixa fidelidade) no `README.md`.
* [✓] Inclui uma lista de problemas detectados nos testes de usabilidade no
  `README.md`.
* [✓] UI: Mostra lista/tabela/etc com dados e/ou indicadores.
* [✓] UI: Permite ordenar dados por um ou mais campos (asc e desc).
* [✓] UI: Permite filtrar dados com base em uma condição.
* [✓] UI: É _responsivo_.
